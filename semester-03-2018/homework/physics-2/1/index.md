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
    2. $$\vec{\nabla}\cdot (\vec{A} \times \vec{B}) = (\vec{\nabla}f)\cdot \vec{A} + f(\vec{\nabla}\cdot \vec{A})$$
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
        $$\frac{1}{4} (\frac{1}{6}-\frac{6}{5}+\frac{13}{4}-4+2) = \frac{1}{240}(10-72+)$$
    2.  
        $$\int_{0}^{6}\int_{0}^{12-2y}\int_{0}^{4-\frac{2y}{3}-\frac{x}{3}}xyz \delta x \delta y \delta z$$
        $$\frac{1}{2}\int_{0}^{6}\int_{0}^{12-2y}(xyz^2|_0^{4-\frac{2y}{3}-\frac{x}{3}}) \delta x \delta y$$
        $$\frac{1}{2}\int_{0}^{6}\int_{0}^{12-2y}xy(4-\frac{2y}{3}-\frac{x}{3})^2 \delta x \delta y$$
        $$\frac{1}{4}\int_{0}^{6}(xy^2(4-\frac{2y}{3}-\frac{x}{3})^2|_0^{12-2y}) \delta x$$