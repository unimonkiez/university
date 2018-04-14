<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# ש"ב פיזיקה - תרגיל 4
## יובל סרף

1. עשינו בכיתה
2. נתון:  
$R = 2m$  
$T = \frac{60}{21}$  
$f = \frac{21}{60}$  
$\dot{\theta} = \omega = 2\pi\cdot \frac{21}{60} = \frac{21\pi}{30}$  
צ"ל:  
$\max{T}$
פתרון:  
נמצא את הכוח המקסימלי הפועל על החומרים כאשר $R=2m$ ולאחר מכן נמיר זאת לכל $R$.  

$$F = ma$$
$$a = \vec{\ddot{r}} = (\ddot{r} - r\dot{\theta}^2)\hat{r} + (2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta}$$
$$r = 2$$
$$\dot{r} = 0$$
$$\ddot{r} = 0$$
$$\dot{\theta} = \frac{21\pi}{30}$$
$$\ddot{\theta} = 0$$
$$\Downarrow$$
$$a = (0 - 2\cdot (\frac{21\pi}{30})^2)\hat{r} + (0 +0)\hat{\theta}$$
$$a = -(\frac{21\pi}{15})^2\hat{r}$$
$$a = -(\frac{21\pi}{15})^2\hat{r}$$
$$F = (-\frac{441\pi}{225}\hat{r})m$$
$$F^1 = F^2$$
$$\Downarrow$$
$$(-\frac{441\pi}{225}\hat{r})m = m \cdot ((\ddot{r} - r\dot{\theta}^2)\hat{r} + (2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta})$$
$$r = R$$
$$\dot{r} = 0$$
$$\ddot{r} = 0$$
$$\dot{\theta} = x$$
$$\ddot{\theta} = 0$$
$$\Downarrow$$
$$(-\frac{441\pi}{225}\hat{r})m = m \cdot ((0 - Rx^2)\hat{r} + (0 + 0)\hat{\theta})$$
$$-\frac{441\pi}{225}\hat{r} = (0 - Rx^2)\hat{r} + (0 + 0)\hat{\theta}$$
$$-\frac{441\pi}{225}\hat{r} = -Rx^2\hat{r}$$
$$-\frac{441\pi}{225} = -Rx^2$$
$$Rx^2 = \frac{441\pi}{225}$$
$$x^2 = \frac{441}{225}\cdot \frac{\pi}{R}$$
$$x = \frac{21}{15} \cdot \sqrt[]{\frac{\pi}{R}}$$
$$\Downarrow$$
$$T = \frac{1}{f} = \frac{2\pi}{x}$$
$$T = \frac{2\pi}{\frac{21}{15} \cdot \sqrt[]{\frac{\pi}{R}}}$$
$$T = \frac{2\pi\sqrt[]{R}\cdot 15}{21\sqrt[]{\pi}}$$
$$T_{sec} = \frac{30\sqrt[]{\pi}\sqrt[]{R}}{21}$$
$$T_{min} = \frac{30\sqrt[]{\pi}\sqrt[]{R}}{21 \cdot 60} = \frac{\sqrt[]{\pi}\sqrt[]{R}}{42}$$

קצב הסיבוב המקסימלי הוא $\frac{\sqrt[]{\pi}\sqrt[]{R}}{42}$ סל"ד.

3. תחילה נחשב את הכוח הצנטריפוגלי - 

$$r = R$$
$$\dot{r} = 0$$
$$\ddot{r} = 0$$
$$\dot{\theta} = v_0$$
$$\ddot{\theta} = 0$$
$$F = ma = m \cdot ((\ddot{r} - r\dot{\theta}^2)\hat{r} + (2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta})$$
$$F = m \cdot ((0 - Rv_0^2)\hat{r} + (0 + 0)\hat{\theta})$$
$$F = m \cdot (-Rv_0^2)\hat{r}$$
$$F = -mRv_0^2\hat{r}$$
$$\Downarrow$$
$$F = -mRv_0^2\hat{x}$$

נבחר x בכיוון מרכז החרוט, וy בכיוון הנגדי לכוח המשיכה - 

|שם|x|y|
|:---:|:---:|:---:|
|נורמלי|$N\cos{\theta}$|$N\sin{\theta}$|
|כבידה||$-mg$|
|צנטריפוגלי|$-mRv_0^2$||

$$\sum F_x = 0$$
$$\sum F_y = 0$$
$$\Downarrow$$
$$I. \ \ \ N\cos{\theta} - mRv_0^2 = 0$$
$$II. \ \ \ N\sin{\theta} - mg = 0$$
$$II. \ \ \ N\sin{\theta} = mg$$
$$II. \ \ \ N = \frac{mg}{\sin{\theta}}$$
$$I. \ \ \ \frac{mg}{\sin{\theta}}\cos{\theta} - mRv_0^2 = 0$$
$$I. \ \ \ mRv_0^2 = \frac{mg}{\sin{\theta}}\cos{\theta}$$
$$I. \ \ \ Rv_0^2 = \frac{g\cos{\theta}}{\sin{\theta}}$$
$$I. \ \ \ R = \frac{g\cos{\theta}}{v_0^2\sin{\theta}}$$
4. עשינו בכיתה
5. **להשלים**
6. נתון:  

    $$\dot{\theta}_{t=0} = \omega_0$$
    $$r_{t=0} = R_0$$
    $$L_{(t)} = R_0-v_0t$$
    1. צ"ל  

    $$\vec{v_{AB}} = ?\hat{r}$$
    $$\vec{v_{AB}} = F_{AB} = m_B \cdot \vec{a}$$
    $$\vec{a} = \vec{\ddot{r}} = (\ddot{r} - r\dot{\theta}^2)\hat{r} + (2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta}$$
    $$r = R_0-v_0t$$
    $$\dot{r} = v_0$$
    $$\ddot{r} = 0$$
    $$\vec{a} = (0 - (R_0 - v_0t)\dot{\theta}^2)\hat{r} + (2v_0\dot{\theta} + (R_0 - v_0t)\ddot{\theta})\hat{\theta}$$
    $$\vec{v_{AB}} = m_B \cdot ((0 - (R_0 - v_0t)\dot{\theta}^2)\hat{r} + (2v_0\dot{\theta} + (R_0 - v_0t)\ddot{\theta})\hat{\theta})$$
    2. נתון
    $\vec{a} \cdot \hat{\theta} = 0$

    $$\Downarrow$$
    $$2v_0\dot{\theta} + (R_0 - v_0t)\ddot{\theta} = 0$$
    $$L = r = R_0-v_0t$$
    $$\dot{L} = \dot{r} = v_0$$
    $$\Downarrow$$
    $$2\dot{L}\dot{\theta} + L\ddot{\theta} = 0$$
    $$2\dot{L}\dot{\theta} =- L\ddot{\theta}$$
    3.
    $$L = R_0-v_0t$$
    $$\dot{L} = v_0$$
    $$2\dot{L}\dot{\theta} =- L\ddot{\theta}$$
    $$\Downarrow$$
    $$2\dot{L}\dot{\theta} =- L\ddot{\theta}$$
    $$2\dot{L}\dot{\theta} =- L\ddot{\theta}$$

7. נתון  

$$Ay_{(x)} + Cy_{(x)}^2 - B = 0 \Rightarrow y_{(x)} = (\frac{B}{C})^{\frac{1}{2}}tanh{[A^{-1}(\frac{B}{C})^{\frac{1}{2}}(x+C)]}$$
$$F = -kv^2$$
$$v_0 = 0$$
נבחר ציר x וציר y בכיוון כוח המשיכה.  

|שם|x|y|
|:---:|:---:|:---:|
|כבידה||$mg$|
|חיכוך אוויר||$-kv^2$|

$$\sum F_x = ma$$
$$\sum F_y = ma$$
$$\Downarrow$$
$$ma_x = 0$$
$$a_x = 0$$
$$ma_y = mg-kv^2$$
$$a_y = g-\frac{kv^2}{m}$$
$$v_x = \int a_x$$
$$v_{x(t)} = v_{x0}$$
$$v_{x(t)} = 0$$
$$v_y = \int a_y$$
$$v_{y(t)} = (g-\frac{kv^2}{m})t + v_{y0}$$
$$v_{y(t)} = (g-\frac{kv^2}{m})t$$
$$v = (g-\frac{kv^2}{m})t$$
$$v = gt -\frac{kv^2t}{m}$$
$$v+\frac{kv^2t}{m} = gt$$
$$\frac{kv^2t+vm}{m} = gt$$
$$kv^2t+vm = gtm$$
$$ktv^2+mv-gtm = 0$$
$$Ay_{(x)} + Cy_{(x)}^2 - B = 0 \Rightarrow y_{(x)} = (\frac{B}{C})^{\frac{1}{2}}tanh{[A^{-1}(\frac{B}{C})^{\frac{1}{2}}(x+C)]}$$
$$ktv^2+mv-gtm = 0$$
$$A = m$$
$$B = -gtm$$
$$C = kt$$
$$\Downarrow$$
$$v_{y(t)} = (\frac{-gtm}{kt})^{\frac{1}{2}}tanh{[m^{-1}(\frac{-gtm}{kt})^{\frac{1}{2}}(t+kt)]}$$
$$v_{y(t)} = (\frac{-gm}{k})^{\frac{1}{2}}tanh{[\frac{1}{m}(\frac{-gm}{k})^{\frac{1}{2}}(k+1)t]}$$
$$v_{y(t)} = (\frac{-gm}{k})^{\frac{1}{2}}tanh{[(\frac{-gm}{km^2})^{\frac{1}{2}}(k+1)t]}$$
$$v_{y(t)} = (\frac{-gm}{k})^{\frac{1}{2}}tanh{[(\frac{-g}{km})^{\frac{1}{2}}(k+1)t]}$$
$$v_{y(t)} = (\frac{-gm}{k})^{\frac{1}{2}}tanh{[(\frac{-g(k+1)^2}{km})^{\frac{1}{2}}t]}$$
$$v_{(t)} = (\frac{-gm}{k})^{\frac{1}{2}}tanh{[(\frac{-g(k+1)^2}{km})^{\frac{1}{2}}t]}\hat{y}$$


8. עשינו בכיתה  
צ"ל

$$N = mg(cos{\theta} - sin{\theta}(tan{\theta}))$$

|x|y|
|:---:|:---:|
||$N$|
|$-mg\sin{\theta}$|$-mg\cos{\theta}$|
|$T\cos{\theta}$|$T\sin{\theta}$|

$$\sum F_x = 0$$
$$\sum F_y = 0$$
$$\Downarrow$$
$$I. \ \ \ N = mg\cos{\theta} -T \sin{\theta}$$
$$II. \ \ \ mg\sin{\theta} = T\cos{\theta}$$

9. **להשלים**
10. **להשלים**