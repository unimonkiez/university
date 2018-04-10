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
$\dot{\theta} = 21$  
צ"ל:  
$\max{\dot{\theta}}$
פתרון:  
נמצא את הכוח המקסימלי הפועל על החומרים כאשר $R=2m$ ולאחר מכן נמיר זאת לכל $R$.  

$$F = ma$$
$$a = \vec{\ddot{r}} = (\ddot{r} - r\dot{\theta}^2)\hat{r} + (2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta}$$
$$r = 2$$
$$\dot{r} = 0$$
$$\ddot{r} = 0$$
$$\dot{\theta} = 21$$
$$\ddot{\theta} = 0$$
$$\Downarrow$$
$$a = (0 - 2\cdot 21^2)\hat{r} + (0 +0)\hat{\theta}$$
$$a = -882\hat{r}$$
$$F = (-882\hat{r})m$$
$$F^1 = F^2$$
$$\Downarrow$$
$$(-882\hat{r})m = m \cdot ((\ddot{r} - r\dot{\theta}^2)\hat{r} + (2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta})$$
$$r = R$$
$$\dot{r} = 0$$
$$\ddot{r} = 0$$
$$\dot{\theta} = x$$
$$\ddot{\theta} = 0$$
$$\Downarrow$$
$$(-882\hat{r})m = m \cdot ((0 - Rx^2)\hat{r} + (0 + 0)\hat{\theta})$$
$$-882\hat{r} = (0 - Rx^2)\hat{r} + (0 + 0)\hat{\theta}$$
$$-882\hat{r} = -Rx^2\hat{r}$$
$$-882 = -Rx^2$$
$$Rx^2 = 882$$
$$x^2 = \frac{882}{R}$$
$$x = \sqrt[]{\frac{882}{R}} = \dot{\theta}$$

קצב הסיבוב המקסימלי הוא $\sqrt[]{\frac{882}{R}}$ סל"ד.

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

נבחר x בכיוון תנועת החלקיק, וy בכיוון הנגדי לכוח המשיכה - 

|שם|x|y|
|:---:|:---:|:---:|
|נורמלי|$N\cos{\theta}$|$N\sin{\theta}$|
|כבידה||$-mg$|
|צנטריפוגלי|$-mRv_0^2$||

$$F_x = 0$$
$$F_y = 0$$
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
3. **להשלים**
3. **להשלים**
3. **להשלים**
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