<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# ש"ב פיזיקה 2 - תרגיל 1
## יובל סרף
1.  
    1. לא נכון:

        $$(\vec{A}\times\vec{B})\times\vec{C} = \vec{A}\times(\vec{B}\times\vec{C})$$
        $$((A_yB_z - A_zB_y)\hat{x} + (A_zB_x - A_xB_z)\hat{y} + (A_xB_y - A_yB_x)\hat{z})\times\vec{C} = \vec{A}\times((B_yC_z - B_zC_y)\hat{x} + (B_zC_x - B_xC_z)\hat{y} + (B_xC_y - B_yC_x)\hat{z})$$

        נמשיך לפתוח את המשוואה רק עבור $\hat{x}$:

        $$(A_zB_x - A_xB_z)C_z - (A_xB_y - A_yB_x)C_y = A_y(B_xC_y - B_yC_x) - A_z(B_zC_x - B_xC_z)$$
        $$A_zB_xC_z - A_xB_zC_z - A_xB_yC_y + A_yB_xC_y = A_yB_xC_y - A_yB_yC_x - A_zB_zC_x + A_zB_xC_z$$
        $$ A_xB_zC_z + A_xB_yC_y = A_yB_yC_x + A_zB_zC_x$$
        והבטויים הללו לא בהכרח שווים.

    2. 
        לא נכון: 

        $$\vec{A}\cdot (\vec{B}\times \vec{C}) = (\vec{A}\cdot \vec{B})\times \vec{C}$$
        אגף שמאל הוא סקאלר, אגף ימין לא מוגדר (כפל וקטורים הוא סקלאר, ואז מכפלה וקטורית לא מוגדרת עבור סקאלר).
    3.
        לא נכון, שוב, חיבור וקטור עם סקאלר אינו מוגדר.
2.
    1. $$\vec{\nabla}\cdot (f \vec{A}) = (\vec{\nabla}f)\cdot \vec{A} + f(\vec{\nabla}\cdot \vec{A})$$
    $$\vec{\nabla}\cdot (f \vec{A})$$
    $$\frac{\delta}{\delta x}(fA_x) + \frac{\delta}{\delta y}(fA_y) + \frac{\delta}{\delta z}(fA_z)$$
    $$(\frac{\delta}{\delta x}A_x+f\frac{\delta A_x}{\delta x}) + (\frac{\delta}{\delta y}A_y+f\frac{\delta A_y}{\delta y}) + (\frac{\delta}{\delta z}A_z+f\frac{\delta A_z}{\delta z})$$
    $$(\frac{\delta f}{\delta x}\hat{x} + \frac{\delta f}{\delta y}\hat{y} + \frac{\delta f}{\delta z}\hat{z})\cdot(A_x\hat{x} + A_y\hat{y} + A_z\hat{z})+f(\frac{\delta A_x}{\delta x} + \frac{\delta A_y}{\delta y} + \frac{\delta A_z}{\delta z})$$
    $$(\vec{\nabla}f)\cdot \vec{A} + f(\vec{\nabla}\cdot \vec{A})$$

    2. $$\vec{\nabla}\cdot (\vec{A} \times \vec{B}) = \vec{B}\cdot (\vec{\nabla} \times \vec{A}) - \vec{A}\cdot (\vec{\nabla} \times \vec{B})$$
    $$\vec{\nabla}\cdot (\vec{A} \times \vec{B})$$
    $$\vec{\nabla}\cdot ((A_yB_z-A_zB_y)\hat{x} + (A_zB_x-A_xB_z)\hat{y} + (A_xB_y-A_yB_x)\hat{z})$$
    $$\vec{\nabla}\cdot ((A_yB_z\hat{x}+A_zB_x\hat{y} + A_xB_y\hat{z}) - (A_zB_y\hat{x} + A_xB_z\hat{y} + A_yB_x\hat{z}))$$
    $$\vec{\nabla}\cdot (A_yB_z\hat{x}+A_zB_x\hat{y} + A_xB_y\hat{z}) - \vec{\nabla}\cdot (A_zB_y\hat{x} + A_xB_z\hat{y} + A_yB_x\hat{z})$$
    $$(\frac{\delta}{\delta x}A_yB_z+\frac{\delta}{\delta y}A_zB_x + \frac{\delta}{\delta z}A_xB_y) - (\frac{\delta}{\delta x}A_zB_y + \frac{\delta}{\delta y}A_xB_z + \frac{\delta}{\delta z}A_yB_x)$$
    $$B_x(\frac{\delta}{\delta y}A_z-\frac{\delta}{\delta z}A_y)+B_y(\frac{\delta}{\delta z}A_x-\frac{\delta}{\delta x}A_z)+B_z(\frac{\delta}{\delta x}A_y-\frac{\delta}{\delta y}A_x)+A_x(\frac{\delta}{\delta y}B_z-\frac{\delta}{\delta z}B_y)+A_y(\frac{\delta}{\delta z}B_x-\frac{\delta}{\delta x}B_z)+A_z(\frac{\delta}{\delta x}B_y-\frac{\delta}{\delta y}B_x)$$
    $$\vec{B}\cdot((\frac{\delta}{\delta y}A_z-\frac{\delta}{\delta z}A_y)\hat{x}+(\frac{\delta}{\delta z}A_x-\frac{\delta}{\delta x}A_z)\hat{y}+(\frac{\delta}{\delta x}A_y-\frac{\delta}{\delta y}A_x)\hat{z})+\vec{A}\cdot((\frac{\delta}{\delta y}B_z-\frac{\delta}{\delta z}B_y)\hat{x}+(\frac{\delta}{\delta z}B_x-\frac{\delta}{\delta x}B_z)\hat{y}+(\frac{\delta}{\delta x}B_y-\frac{\delta}{\delta y}B_x)\hat{z})$$
    $$\vec{B}\cdot(\vec{\nabla} \times \vec{A})+\vec{A}\cdot(\vec{B}\times \vec{\nabla})$$
    $$\vec{B}\cdot(\vec{\nabla} \times \vec{A})-\vec{A}\cdot(\vec{\nabla}\times \vec{B})$$

    3. $$\vec{\nabla} \times (\vec{\nabla} \times \vec{A}) = \vec{\nabla}(\vec{\nabla} \cdot \vec{A}) - \nabla^2\vec{A}$$
3.
    1.
        $$\int_{0}^{1}\int_{0}^{1-x}\int_{0}^{2-x}xyz \delta x \delta y \delta z$$
        $$\frac{1}{2}\int_{0}^{1}\int_{0}^{1-x}xy(2-x)^2 \delta x \delta y$$
        $$\frac{1}{4}\int_{0}^{1} (xy^2(2-x)^2|_{0}^{1-x}) \delta x$$
        $$\frac{1}{4}\int_{0}^{1} x(1-x)^2(2-x)^2 \delta x$$
        $$\frac{1}{4}\int_{0}^{1} x(1-2x+x^2)(4-4x+x^2) \delta x$$
        $$\frac{1}{4}\int_{0}^{1} x(4-4x+x^2-8x+8x^2-2x^3+4x^2-4x^3+x^4) \delta x$$
        $$\frac{1}{4}\int_{0}^{1} x(x^4-6x^3+13x^2-12x+4) \delta x$$
        $$\frac{1}{4}\int_{0}^{1} (x^5-6x^4+13x^3-12x^2+4x )\delta x$$
        $$\frac{1}{4} (\frac{1}{6}x^6-\frac{1}{5}6x^5+\frac{1}{4}13x^4-\frac{1}{3}12x^3+\frac{1}{2}4x^2|_{0}^{1})$$
        $$\frac{1}{4} (\frac{1}{6}-\frac{6}{5}+\frac{13}{4}-4+2)$$
        $$\frac{1}{240}(10-72+195-240+120)$$
        $$\frac{13}{240}$$
    2.  
        $$\int_{0}^{6}\int_{0}^{12-2y}\int_{0}^{4-\frac{2y}{3}-\frac{x}{3}}xyz \delta x \delta y \delta z$$
        $$\frac{1}{2}\int_{0}^{6}\int_{0}^{12-2y}(xyz^2|_0^{4-\frac{2y}{3}-\frac{x}{3}}) \delta x \delta y$$
        $$\frac{1}{2}\int_{0}^{6}\int_{0}^{12-2y}xy(4-\frac{2y}{3}-\frac{x}{3})^2 \delta x \delta y$$
        $$\frac{1}{2}\int_{0}^{6}y\delta y\int_{0}^{12-2y}x(16-\frac{8y}{3}-\frac{4x}{3}-\frac{8y}{3}+\frac{4y^2}{9}+\frac{2xy}{9}-\frac{4x}{3}+\frac{2xy}{9}+\frac{x^2}{9}) \delta x$$
        $$\frac{1}{2}\int_{0}^{6}y\delta y\int_{0}^{12-2y}x(16-\frac{16y}{3}-\frac{8x}{3}+\frac{4y^2}{9}+\frac{4xy}{9}+\frac{x^2}{9}) \delta x$$
        $$\frac{1}{2}\int_{0}^{6}y\delta y\int_{0}^{12-2y}(16x-\frac{16xy}{3}-\frac{8x^2}{3}+\frac{4xy^2}{9}+\frac{4x^2y}{9}+\frac{x^3}{9}) \delta x$$
        $$\frac{1}{2}\int_{0}^{6}y\delta y(8x^2-\frac{8x^2y}{3}-\frac{8x^3}{9}+\frac{2x^2y^2}{9}+\frac{4x^3y}{27}+\frac{x^4}{36}|_{0}^{12-2y})$$
        $$\frac{1}{2}\int_{0}^{6}y\delta y(8(12-2y)^2-\frac{8(12-2y)^2y}{3}-\frac{8(12-2y)^3}{9}+\frac{2(12-2y)^2y^2}{9}+\frac{4(12-2y)^3y}{27}+\frac{(12-2y)^4}{36})$$
        $$\frac{1}{2}\int_{0}^{6}\delta y (y(12-2y)^2(8-\frac{8y}{3}-\frac{96-16y}{9}+\frac{2y^2}{9}+\frac{36y-8y^2}{27}+\frac{144-48y+4y^2}{36}))$$
        $$\frac{1}{2}\int_{0}^{6}\delta y (y(12-2y)^2(8-\frac{8y}{3}-\frac{96-16y}{9}+\frac{2y^2}{9}+\frac{48y-8y^2}{27}+\frac{36-12y+y^2}{9}))$$
        $$\frac{1}{2}\int_{0}^{6}\delta y (y(12-2y)^2(\frac{216-72y-288+48y+6y^2+48y-8y^2+108-36y+3y^2}{27}))$$
        $$\frac{1}{54}\int_{0}^{6}\delta y (y(12-2y)^2(y^2-12y+36))$$
        $$\frac{1}{54}\int_{0}^{6}\delta y (y(4y^2-48y+144)(y^2-12y+36))$$
        $$\frac{2}{27}\int_{0}^{6}\delta y (y(y^2-12y+36)(y^2-12y+36))$$
        $$\frac{2}{27}\int_{0}^{6}\delta y (y(y-6)^4)$$
        $$y=t+6 \rightarrow t=y-6$$
        $$\frac{2}{27}\int_{-6}^{0}\delta t ((t+6)t^4)$$
        $$\frac{2}{27}\int_{-6}^{0}\delta t (t^5+6t^4)$$
        $$\frac{2}{27}(\frac{t^6}{6}+\frac{6t^5}{5}|_{-6}^{0})$$
        $$\frac{2}{27}(0-\frac{(-6)^6}{6}-\frac{6(-6)^5}{5})$$
        $$\frac{2}{27}(6^5-\frac{6^6}{5})$$
        $$\frac{2}{27}(6^5-\frac{6^6}{5}) = 460.8$$
4.
5.
    $$\rho_{(x,y)}=x^2+y^3$$
    $$\delta s=\delta x\delta y$$
    $$Q = \int \delta s \rho$$
    $$Q = \int_0^1\delta y\int_y^1\delta x (x^2+y^3)$$
    $$\int_0^1\delta y\int_y^1\delta x (x^2+y^3)$$
    $$\int_0^1\delta y(\frac{1}{3}x^3+xy^3|_y^1)$$
    $$\int_0^1\delta y(\frac{1}{3}+y^3-\frac{1}{3}y^3-y^4)$$
    $$\int_0^1\delta y(\frac{2}{3}y^3-y^4+\frac{1}{3})$$
    $$(\frac{1}{6}y^4-\frac{1}{5}y^5+\frac{1}{3}y|_0^1)$$
    $$\frac{1}{6}-\frac{1}{5}+\frac{1}{3}$$
    $$\frac{5-6+10}{30}$$
    $$\frac{3}{10}C$$
6. 
    $$F_{(r,\phi,\theta)} = \frac{1}{r}$$
    $$r=\sqrt[]{6}$$
    $$\frac{\pi}{4}<\theta<\arctan(2)$$
    $$\int\int\int F_{(r,\phi,\theta)}\delta V$$
    $$\Downarrow$$
    $$V=\{0<r<\sqrt[]{6},\frac{\pi}{4}<\theta<\arctan(2), 0<\phi<\frac{\pi}{2}\}$$
    $$\Downarrow$$
    $$\int_0^{\sqrt[]{6}}\delta r \int_0^{\frac{\pi}{2}} \delta \phi \int_{\frac{\pi}{4}}^{\arctan(2)}\delta \theta (\frac{1}{r})r^2\sin(\theta)$$
    $$\int_0^{\sqrt[]{6}}\delta r \int_0^{\frac{\pi}{2}} \delta \phi \int_{\frac{\pi}{4}}^{\arctan(2)}\delta \theta (r\sin(\theta))$$
    $$\int_0^{\sqrt[]{6}}\delta r (r) \int_0^{\frac{\pi}{2}} \delta \phi \int_{\frac{\pi}{4}}^{\arctan(2)}\delta \theta (\sin(\theta))$$
    $$\int_0^{\sqrt[]{6}}\delta r (r) \int_0^{\frac{\pi}{2}} \delta \phi (-\cos(\theta) |_{\frac{\pi}{4}}^{\arctan(2)})$$
    $$\int_0^{\sqrt[]{6}}\delta r (r) \int_0^{\frac{\pi}{2}} \delta \phi (\cos(\frac{\pi}{4})-\cos(\arctan(2)))$$
    $$(\cos(\frac{\pi}{4})-\cos(\arctan(2))\int_0^{\sqrt[]{6}}\delta r (r) \int_0^{\frac{\pi}{2}} \delta \phi$$
    $$(\cos(\frac{\pi}{4})-\cos(\arctan(2))\int_0^{\sqrt[]{6}}\delta r (r) (\phi|_0^{\frac{\pi}{2}})$$
    $$(\cos(\frac{\pi}{4})-\cos(\arctan(2))\int_0^{\sqrt[]{6}}\delta r (r) (\frac{\pi}{2})$$
    $$\frac{\pi}{2}(\cos(\frac{\pi}{4})-\cos(\arctan(2))\int_0^{\sqrt[]{6}}\delta r (r)$$
    $$\frac{\pi}{2}(\cos(\frac{\pi}{4})-\cos(\arctan(2))(\frac{1}{2}r^2|_0^{\sqrt[]{6}})$$
    $$\frac{3\pi}{2}(\cos(\frac{\pi}{4})-\cos(\arctan(2))$$
7.
    $$p_{(r,\phi,\theta)} = \frac{\sin(\theta)}{r^2}p_0$$
    $$V=\{a<r<b,0<\theta<\pi, 0<\phi<2\pi\}$$
    $$\Downarrow$$
    $$\int_a^b \delta r \int_0^{\pi} \int_0^{2\pi} \delta \phi (\frac{\sin(\theta)}{r^2}p_0)$$
    $$p_0 \int_a^b \delta r (\frac{1}{r^2}) \int_0^{\pi} (\sin(\theta)) \int_0^{2\pi} \delta \phi$$
    $$p_0 \int_a^b \delta r (\frac{1}{r^2}) \int_0^{\pi} (\sin(\theta)) (\phi|_0^{2\pi})$$
    $$p_0 \int_a^b \delta r (\frac{1}{r^2}) \int_0^{\pi} (\sin(\theta)) (2\pi)$$
    $$2\pi p_0 \int_a^b \delta r (\frac{1}{r^2}) \int_0^{\pi} (\sin(\theta))$$
    $$2\pi p_0 \int_a^b \delta r (\frac{1}{r^2}) (-\cos(\theta) |_0^{\pi})$$
    $$2\pi p_0 \int_a^b \delta r (\frac{1}{r^2}) (-\cos(\pi)+\cos(0))$$
    $$2\pi p_0 \int_a^b \delta r (\frac{1}{r^2}) (-0+1)$$
    $$2\pi p_0 \int_a^b \delta r (\frac{1}{r^2})$$
    $$2\pi p_0 (-\frac{1}{r}|_a^b)$$
    $$2\pi p_0 (\frac{1}{a}-\frac{1}{b})$$
