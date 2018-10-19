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

1. עשינו בתרגול
2. עשינו בתרגול
3. עשינו בתרגול
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

7. עשינו בתרגול
8.  
    תרשים כוחות עבור $m_1$
    
    $$F \rightarrow$$
    $$N_1 \leftarrow$$
    תרשים כוחות עבור $m_2$
    
    $$N_1 \rightarrow$$
    $$N_2 \leftarrow$$
    תרשים כוחות עבור $m_3$
    
    $$N_2 \rightarrow$$
    $$\Downarrow$$
    $$F-N_1 = m_1a_1$$
    $$N_1-N_2 = m_2a_2$$
    $$N_2 = m_3a_3$$
    אך נתון שהגופים יושבים זה ליד זה, זאת אומרת העתק שלהם זהה, תנועתם ותאוצתם  

    $$a_1 = a_2 = a_3 = a$$
    $$\Downarrow$$
    $$I.\ \ F-N_1 = m_1a$$
    $$II.\ \ N_1-N_2 = m_2a$$
    $$III.\ \ N_2 = m_3a$$
    $$\Downarrow$$
    $$III.\ \ a = \frac{N_2}{m_3}$$
    $$I.\ \ F-N_1 = m_1 \frac{N_2}{m_3}$$
    $$I.\ \ N_1 = F - m_1 \frac{N_2}{m_3}$$
    $$II.\ \ (F - m_1 \frac{N_2}{m_3})-N_2 = m_2\frac{N_2}{m_3}$$
    $$II.\ \ F = N_2 + m_1 \frac{N_2}{m_3} + m_2\frac{N_2}{m_3}$$
    $$II.\ \ F = N_2(1 + \frac{m_1}{m_3} + \frac{m_2}{m_3})$$
    $$II.\ \ F = N_2(1 + \frac{m_1 + m_2}{m_3})$$
    $$II.\ \ F = N_2\frac{m_1 + m_2 + m_3}{m_3}$$
    $$II.\ \ N_2 = \frac{F}{\frac{m_1 + m_2 + m_3}{m_3}}$$
    $$II.\ \ N_2 = \frac{Fm_3}{m_1 + m_2 + m_3}$$
    $$I.\ \ N_1 = F - m_1 \frac{\frac{Fm_3}{m_1 + m_2 + m_3}}{m_3}$$
    $$I.\ \ N_1 = F -  \frac{Fm_1}{m_1 + m_2 + m_3}$$
    $$I.\ \ N_1 = F(1-\frac{m_1}{m_1 + m_2 + m_3})$$
    $$I.\ \ N_1 = F\frac{m_1 + m_2 + m_3-m_1}{m_1 + m_2 + m_3}$$
    $$I.\ \ N_1 = F\frac{m_2 + m_3}{m_1 + m_2 + m_3}$$

    פתרון:  

    $$N_1 = F\frac{m_2 + m_3}{m_1 + m_2 + m_3}$$
    $$N_2 = F\frac{m_3}{m_1 + m_2 + m_3}$$


9. נתון:  

    $$\vec{a} = -g\hat{r}$$
    פתרון:  

    $$g = \frac{GM}{R^2}$$
    $$G = 6.67742 \cdot 10^{-11}\ \frac{m^3}{s^2kg}$$
    $$M = 5.9736 \cdot 10^{24}\ kg$$
    $$R = 6.37101 \cdot 10^{6}\ m$$
    $$r_{(t)} = R$$
    $$\dot{r}_{(t)} = 0$$
    $$\ddot{r}_{(t)} = 0$$
    נמצא את $\dot{\theta}$ לפי הנתון (תאוצה רדיאלית)

    $$\ddot{\vec{r}} \cdot \hat{r} = -g = -\frac{GM}{R^2}$$
    והנוסחא:  

    $$\ddot{\vec{r}} \cdot \hat{r} = \ddot{r} - r\dot{\theta}^2$$
    $$\Downarrow$$
    $$-\frac{GM}{R^2} = 0 - R\dot{\theta}^2$$
    $$R\dot{\theta}^2 = \frac{GM}{R^2}$$
    $$\dot{\theta}^2 = \frac{GM}{R^3}$$
    $$\dot{\theta} = \sqrt{\frac{GM}{R^3}}$$
    $$\dot{\theta} = \sqrt{0.00000154248 \ \frac{1}{s^2}}$$
    $$\dot{\theta} = 0.00124196679 \ \frac{1}{s}$$

    מש"ל (?)

10.
    נתון

    $$r_{(t=0)} = 0.5 \ m$$
    $$\dot{\theta} = 0.2 \ \frac{rad}{s}$$
    $$r_{(t=3)} = 2 \ m$$
    1. .

        $$r = \frac{t+1}{2}$$
        $$\dot{r} = \frac{1}{2}$$
        $$\ddot{r} = 0$$
        $$\dot{\theta} = 0.2$$
        $$\theta = 0.2t$$
        $$\ddot{\theta} = 0$$
        $$\vec{v} = \dot{r}\hat{r} + r\dot{\theta}\hat{\theta}$$
        $$\Downarrow$$
        $$\vec{v} = (\frac{1}{2})\hat{r} + (\frac{t+1}{2}\cdot 0.2)\hat{\theta}$$
        $$\vec{v} = (\frac{1}{2})\hat{r} + (\frac{t+1}{10})\hat{\theta}$$
        $$\vec{a} = (\ddot{r} - r\dot{\theta}^2)\hat{r} + (2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta}$$
        $$\Downarrow$$
        $$\vec{a} = (0 - \frac{t+1}{2} \cdot 0.2^2)\hat{r} + (2\frac{1}{2} \cdot 0.2 + \frac{t+1}{2} \cdot 0)\hat{\theta}$$
        $$\vec{a} = (-\frac{t+1}{50})\hat{r} + (\frac{1}{5})\hat{\theta}$$

    2. לילד שהולך במהירות קבועה על קרוסלה הנעה גם כן במהירות קבועה יש תאוצה כי כאשר הילד מתקדם תנועתו היחסית **לשאר העולם** משתנה, בנוסף מכיוון שבהליכתו באופן זה משנה את מרחקו ממרכז הקרוסלה, מהירותו הזוויתית גדלה.  
    ככל שמתרחק יותר ממרכז הקרוסלה, מהירותו הזוויתית גדלה, ושינוי זה במהירותו היא למעשה התאוצה שלו.
    3.
11.
    נתון
    
    $$r_{(\theta)} = \frac{R}{1 - \frac{\cos{\theta}}{2}} = \frac{2R}{2 - \cos{\theta}}$$
    $$\theta = \omega t$$
    $$\dot{\theta} = \omega$$
    $$\ddot{\theta} = 0$$

    1.

    $$r_{(t)} = \frac{2R}{2 - \cos{(\omega t)}}$$
    $$\vec{r} = \frac{2R}{2 - \cos{(\omega t)}}\hat{r} + \omega t \hat{\theta}$$
    $$\dot{r} = \frac{\dot{\overline{(2-\cos{(\omega t)})}}\cdot 2R - \dot{\overline{2R}}(2-\cos{(\omega t)})}{(2-\cos{(\omega t)})^2}$$
    $$\dot{r} = \frac{(\omega\sin{(\omega t)})\cdot 2R - 0(2-\cos{(\omega t)})}{(2-\cos{(\omega t)})^2}$$
    $$\dot{r} = \frac{2\omega R\sin{(\omega t)}}{(2-\cos{(\omega t)})^2}$$
    $$\vec{v} = \dot{r}\hat{r} + r\dot{\theta}\hat{\theta}$$
    $$\Downarrow$$
    $$\vec{v} = \frac{2\omega R\sin{(\omega t)}}{(2-\cos{(\omega t)})^2}\hat{r} + \frac{2R}{2 - \cos{(\omega t)}}\omega\hat{\theta}$$
    $$\vec{v} = \frac{2\omega R}{2 - \cos{(\omega t)}}(\frac{\sin{(\omega t)}}{2 - \cos{(\omega t)}}\hat{r} + \hat{\theta})$$

    מסלול החלילית הוא אליפסה, כאשר  
    וקטור העתק שלו הוא 

    $$\vec{r} = \frac{2R}{2 - \cos{(\omega t)}}\hat{r} + \omega t \hat{\theta}$$

    ווקטור המהירות שלה הוא  
    
    $$\vec{v} = \frac{2\omega R}{2 - \cos{(\omega t)}}(\frac{\sin{(\omega t)}}{2 - \cos{(\omega t)}}\hat{r} + \hat{\theta})$$

    2.  גודל המהירות היא רכיב ה $\hat{r}$:  

    $$d_{(t)} =\frac{2\omega R\sin{(\omega t)}}{(2-\cos{(\omega t)})^2}$$
    עבור $\omega t = 0$ ערך $\sin{(\omega t)}$ הוא 0 והביטוי כולו מתאפס, ומהירותו של החללית היא מינימאלית.

