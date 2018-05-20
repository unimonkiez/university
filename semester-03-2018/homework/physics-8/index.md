<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# ש"ב פיזיקה - תרגיל 8
## יובל סרף
1. **עשינו בכיתה**
2. 
    $$F_x = -\frac{U}{\delta x}$$
    $$F_y = -\frac{U}{\delta y}$$
    $$F_z = -\frac{U}{\delta z}$$
    1. $$U_{(x, y, z)} = 3x^2z-z^3$$
    $$F_x = -6zx$$
    $$F_y = 0$$
    $$F_z = 3z^2-3x^2$$
    2. $$U_{(x, y, z)} = (x^2 + y^2 + z^2)^3$$
    $$F_x = -6x(x^2 + y^2 + z^2)^2$$
    $$F_y = -6y(x^2 + y^2 + z^2)^2$$
    $$F_z = -6z(x^2 + y^2 + z^2)^2$$
    3. $$U_{(x, y, z)} = \cos{(xy^2z)}$$
    $$F_x = y^2z\sin{(xy^2z)}$$
    $$F_y = 2xyz\sin{(xy^2z)}$$
    $$F_z = xy^2\sin{(xy^2z)}$$
3. 
    1. $$\vec{F}_{(x, y, z)} = x^2\hat{x} + y^2\hat{y}$$
    $$\frac{F_x}{\delta y} = \frac{F_x}{\delta z} = \frac{F_y}{\delta x} = \frac{F_y}{\delta z} = \frac{F_z}{\delta x} = \frac{F_z}{\delta y} = 0$$
    $$\Downarrow$$
    $$U_{(x, y, z)} = \int_0^xx^2\hat{x} + \int_0^yy^2\hat{y}$$
    $$U_{(x, y, z)} = \frac{x^3}{3}|_0^x\hat{x} + \frac{y^3}{3}|_0^y\hat{y}$$
    $$U_{(x, y, z)} = -\frac{x^3}{3}\hat{x} - \frac{y^3}{3}\hat{y}$$
    
    2. $$\vec{F}_{(x, y, z)} = y^2\hat{x} + x^2\hat{y}$$
    $$\frac{F_x}{\delta y} = 2y$$
    $$\frac{F_y}{\delta x} = 2x$$
    $$\Downarrow$$
    $$\frac{F_x}{\delta y} \neq \frac{F_y}{\delta x}$$
    3. **עשינו בכיתה**
    4. $$\vec{F}_{(x, y, z)} = (x^2 + y^2 + z^2)(x\hat{x} + y\hat{y} + z\hat{z})$$
    $$\frac{F_x}{\delta y} = \frac{F_y}{\delta x} = 2yx$$
    $$\frac{F_x}{\delta z} = \frac{F_z}{\delta x} = 2xz$$
    $$\frac{F_y}{\delta z} = \frac{F_z}{\delta y} = 2yz$$
    $$\Downarrow$$
    $$U_{(x, y, z)} = \int_0^x(x^3 + xy^2 + xz^2)\hat{x} + \int_0^y(yx^2 + y^3 + yz^2)\hat{y} + \int_0^z(zx^2 + zy^2 + z^3)\hat{z}$$
    $$U_{(x, y, z)} = (\frac{x^4}{4} + \frac{x^2y^2}{2} + \frac{x^2z^2}{2})|_0^x\hat{x} + (\frac{x^2y^2}{2} + \frac{y^4}{4} + \frac{y^2z^2}{2})|_0^y\hat{y} + (\frac{x^2z^2}{2} + \frac{y^2z^2}{2} + \frac{z^4}{4})|_0^z\hat{z}$$
    $$U_{(x, y, z)} = -(\frac{x^4}{4} + \frac{x^2y^2}{2} + \frac{x^2z^2}{2})\hat{x} - (\frac{x^2y^2}{2} + \frac{y^4}{4} + \frac{y^2z^2}{2})\hat{y} - (\frac{x^2z^2}{2} + \frac{y^2z^2}{2} + \frac{z^4}{4})\hat{z}$$
4. $$\vec{F} = x^3\hat{x} + xy^2\hat{y}$$
    1. $$W = F\Delta r = \int_0^0x^3\hat{x} + \int_0^{2R}xy^2\hat{y}$$
    $$W = \int_0^0x^3\hat{x} + \int_0^{2R}xy^2\hat{y}$$
    $$W = \frac{xy^3}{3}|_0^{2R}\hat{y}$$
    $$W = -\frac{x(2R)^3}{3}\hat{y}$$
    $$W = -\frac{8xR^3}{3}\hat{y}$$
    2. 
    $$\frac{F_x}{\delta y} = 0$$
    $$\frac{F_y}{\delta x} = y^2$$
    $$\Downarrow$$
    $$\frac{F_x}{\delta y} \neq \frac{F_y}{\delta x}$$

    הכוח לא משמר ולכן יש חשיבות למסלול בחישוב העבודה.
5. **עשינו בכיתה**
6. 
    1. צ"ל: $h = ?$

    $$h = x_2 - x_1$$
    $$x_1 = 0$$
    $$v_0$$
    $$v_2 = 0$$
    $$U_1 + E_{k1} = U_2 + E_{k2}$$
    $$U_1 = -mgx_1 = 0$$
    $$U_2 = -mgx_2 = -mgh$$
    $$E_{k1} = \frac{1}{2}mv_0^2$$
    $$E_{k2} = \frac{1}{2}mv_2^2 = 0$$
    $$\Downarrow$$
    $$mgh = \frac{1}{2}mv_0^2$$
    $$h = \frac{v_0^2}{2g}$$

    2. צ"ל: $v_{0_{min}} \geq ?$

    $$E_{k1} = \frac{1}{2}mv_0^2$$
    $$U_1 = -\frac{GMm}{r}$$
    $$U_2 = -\frac{GMm}{R_0} \rightarrow^{R_0 \rightarrow \infty} \leq 0$$
    $$\Downarrow$$
    $$E = \frac{1}{2}mv_0^2 -\frac{GMm}{r} \geq 0$$
    $$\frac{1}{2}mv_0^2 \geq \frac{GMm}{r}$$
    $$v_0^2 \geq \frac{2GM}{r}$$
    $$v_0 \geq \sqrt{\frac{2GM}{r}}$$

    3. $$v_y = \sin{\alpha} \cdot v_0$$
    $$v_y^2 \geq \frac{2GM}{r}$$
    $$\Downarrow$$
    $$(\sin{\alpha} \cdot v_0)^2 \geq \frac{2GM}{r}$$
    $$v_0^2 \geq \frac{2GM}{r\sin^2{\alpha}}$$
    $$v_0 \geq \sqrt{\frac{2GM}{r\sin^2{\alpha}}}$$
    
7. 
    1. צ"ל: $v_{\theta} = ?$

    $$\vec{F}\hat{r} = -mg\cos{\theta} - T = 0$$
    $$\vec{F}\hat{\theta} = -mg\sin{\theta}$$
    $$W = \vec{F}\Delta r$$
    $$W = \int_{\theta_0}^{\theta}(-mg\sin{\theta}l)$$
    $$W = (\cos{\theta})|_{\theta_0}^{\theta}mgl$$
    $$W = mgl(\cos{\theta} - \cos{\theta_0})$$
    $$W = \Delta E$$
    $$W = \frac{mv_{\theta}^2}{2} - \frac{mv_0^2}{2} = \frac{mv_{\theta}^2}{2}$$
    $$\Downarrow$$
    $$\frac{mv_{\theta}^2}{2} = mgl(\cos{\theta} - \cos{\theta_0})$$
    $$v_{\theta}^2 = 2gl(\cos{\theta} - \cos{\theta_0})$$
    $$v_{\theta} = \sqrt{2gl(\cos{\theta} - \cos{\theta_0})}$$

    2. צ"ל: $\theta_{max} = ?, v_{\theta_{max}} = ?$  
    הכוח משמר, לכן למהירות מקסימלית צריך עבודה מקסימלית, וזה קורה כאשר המסה נמצאת למטה ($\theta = \pi$)

    $$v_{\theta} = \sqrt{2gl(\cos{\theta} - \cos{\theta_0})}$$
    $$\theta = \pi$$
    $$\Downarrow$$
    $$v_{\theta} = \sqrt{2gl(1 - \cos{\theta_0})}$$

8. $$U_p = \int_0^{\theta}-mg\cos{\theta}r\delta \theta$$
   $$U_p = (-mg\sin{\theta}R)|_0^{\theta}$$
   $$U_p = mg\sin{\theta}R$$
   $$\Downarrow$$
   $$\frac{1}{2}mv^2 = mg\sin{\theta}R$$
   $$v^2 = 2g\sin{\theta}R$$
   $$v = \sqrt{2g\sin{\theta}R}$$
   $$v_{\theta = \frac{\pi}{2}} = \sqrt{2gR}$$
9. **עשינו בכיתה**
10.   
    $$F_{x_M} = -N_1\sin{\frac{\pi}{4}}$$
    $$F_{y_M} = 0$$
    $$F_{x_m} = N_1\cos{\frac{\pi}{4}}$$
    $$F_{y_m} = -mg + N_1\sin{\frac{\pi}{4}}$$
    $$U_p = \int_h^0(-mg+N_1\cos{\frac{\pi}{4}})\hat{y}$$
    $$U_p = (-mg+N_1\cos{\frac{\pi}{4}})y|_h^0$$
    $$U_p = (mg+N_1\cos{\frac{\pi}{4}})h$$
    $$\Downarrow$$
    $$\frac{mv_y^2}{2}=(mg+N_1\cos{\frac{\pi}{4}})h$$
    $$v_y^2=(mg+N_1\cos{\frac{\pi}{4}})\frac{2h}{m}$$
    $$v_y=\sqrt{(mg+N_1\cos{\frac{\pi}{4}})\frac{2h}{m}}$$