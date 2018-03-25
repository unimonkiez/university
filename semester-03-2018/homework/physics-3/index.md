<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# ש"ב פיזיקה - תרגיל 3
## יובל סרף

4.  
    נתון:  
    
    $$x = v_0t$$
    $$y = y_0$$

    פתרון:  

    $$\overline{x}_{(t)} = v_0t\hat{x} + y_0\hat{y}$$
    $$\overline{v}_{(t)} = v_0\hat{x}$$
    $$\overline{a}_{(t)} = 0$$
    $$\Downarrow$$
    $$\overline{r}_{(t)} = v_0t(\cos{\theta}\hat{r} - \sin{\theta}\hat{\theta}) + y_0(\sin{\theta}\hat{r} + \cos{\theta}\hat{\theta})$$
    $$\overline{r}_{(t)} = (v_0 t \cos{\theta} + y_0 \sin{\theta})\hat{r} + (-v_0 t \sin{\theta} + y_0 \cos{\theta})\hat{\theta}$$
    $$\overline{v}_{(t)} = v_0(\cos{\theta}\hat{r} - \sin{\theta}\hat{\theta})$$
    $$\overline{v}_{(t)} = v_0\cos{\theta}\hat{r} - v_0\sin{\theta}\hat{\theta}$$
    $$\overline{a}_{(t)} = 0$$

5. נתון  

$$\vec{v}_{(t)} = 2t\hat{r} + (1+t^2)\hat{\theta}$$
$$x_{(t=0)} = 1$$
$$y_{(t=0)} = 0$$ 
פתרון:  

$$\vec{v}_{(t)} = \dot{\vec{r}}_{(t)} = \dot{r}\hat{r} + r\dot{\theta}\hat{\theta}$$
$$\dot{r}\hat{r} + r\dot{\theta}\hat{\theta} = 2t\hat{r} + (1+t^2)\hat{\theta}$$
$$\dot{r} = 2t$$
$$\Downarrow$$
$$r = t^2 + 1$$
$$\ddot{r} = 2$$
$$r\dot{\theta} = 1+t^2$$
$$\Downarrow$$
$$(t^2 + 1)\dot{\theta} = 1+t^2$$
$$\dot{\theta} = 1$$
$$\theta = t$$
$$\ddot{\theta} = 0$$
$$\vec{r} = |\vec{r}|\hat{r}$$
$$\vec{r} = (t^2 + 1)\hat{r}$$
$$\vec{a} = \ddot{\vec{r}} = (\ddot{r} - r\dot{\theta}^2)\hat{r} + (2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta}$$
$$\Downarrow$$
$$\vec{a} = (2 - (t^2+1)1^2)\hat{r} + (2(2t)1 + (t^2+1)0)\hat{\theta}$$
$$\vec{a} = (2 - t^2 - 1)\hat{r} + 4t\hat{\theta}$$
$$\vec{a} = (1-t^2)\hat{r} + 4t\hat{\theta}$$

6. נתון:   

    $$\omega_1 > 0$$
    $$\omega_2 > 0$$
    $$r_1 = r_2 = R$$
    $$\dot{\theta_1} = \omega_1$$
    $$\dot{\theta_2} = -\omega_2$$
    $$\Downarrow$$
    $$\dot{r_1} = \dot{r_2} = 0$$
    $$\ddot{r_1} = \ddot{r_2} = 0$$
    $$\theta_1 = \omega_1 t$$
    $$\theta_2 = -\omega_2 t$$
    $$\ddot{\theta_1} = 0$$
    $$\ddot{\theta_2} = 0$$

    1.

    $$\vec{v} = \dot{r}\hat{r} + r\dot{\theta}\hat{\theta}$$
    $$\Downarrow$$
    $$\vec{v}_{1(t)} = 0\hat{r} + R\omega_1\hat{\theta}$$
    $$\vec{v}_{1(t)}= R\omega_1\hat{\theta}$$
    $$\vec{v}_{2(t)} = -R\omega_2\hat{\theta}$$
    $$\vec{v}_{1-2(t)} = R\omega_1\hat{\theta} - (-R\omega_2\hat{\theta})$$
    $$\vec{v}_{1-2(t)} = R(\omega_1 + \omega_2)\hat{\theta}$$
    2.  לפי הנוסחא $\vec{v}_{1-2(t)} = R(\omega_1 + \omega_2)\hat{\theta}$, המהירות היחסית מתאפסת בשני תנאים, $R=0$ או $\omega_1 + \omega_2 = 0$, אך נתון כי $\omega_1 > 0, \omega_2 > 0$ ולכן סכומם לעולם לא יתאפס.
    התשובה היא רק כאשר $R=0$, ללא תלות בזמן.  

    $$$$