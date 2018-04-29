<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# ש"ב פיזיקה - תרגיל 6
## יובל סרף
1. **עשינו בכיתה**
2. נתון  

    $$l_1$$
    $$k_1$$
    $$l_2$$
    $$k_2$$
    $$m$$
    1. צ"ל $\Delta l_1, \Delta l_2$:  
    
    $$I.\ \ \ \Delta l_1 k_1 = \Delta l_2 k_2$$
    $$II.\ \ \ -\Delta l_2 k_2 = mg$$
    $$\Downarrow$$
    $$\Delta l_2 = -\frac{mg}{k_2}$$
    $$\Delta l_1 = \frac{mg}{k_1}$$  
    מינוס בגלל שהם נמתחים בכיוונים שונים.  

    2. צ"ל $T$:  

    $$I.\ \ \ T = \frac{2 \pi}{\omega}$$
    $$II.\ \ \ a = \omega^2x$$
    $$III.\ \ \ a = g$$
    $$IV.\ \ \ \Delta l_1 k_1 = mg = -\Delta l_2 k_2$$
    $$V.\ \ \ \Delta l_1 = x_1$$
    $$V.\ \ \ \Delta l_2 = x_2$$
    $$\Downarrow$$
    $$IV.\ \ \ x k_2 = mg$$
    $$IV.\ \ \ g  = \frac{k_2}{m}x$$
    $$II.\ \ \ g = \omega^2x$$
    $$II.\ \ \ \omega^2 = \frac{k_2}{m}$$
    $$II.\ \ \ \omega = \frac{\sqrt[]{k_2}}{\sqrt[]{m}}$$
    $$I.\ \ \ T = \frac{2 \pi\sqrt[]{m}}{\sqrt[]{k_2}}$$
    $$\Downarrow$$
    $$T = \frac{2 \pi\sqrt[]{m}}{\sqrt[]{k_2}}$$

    3. $y_{(t)} = ?$:  
    נוסחאת מיקום תנועה הרמונית פשוטה:  
    
    $$y_{(t)} = A\cos{\omega t}$$
    $$\Downarrow$$
    $$y_{(t)} = l_1 + A_1\cos{(\omega t)} + l_2 + A_2\cos{(\omega t)}$$
    $$y_{(t)} = l_1 + l_2 + (A_1 + A_2)\cos{(\omega t)}$$
    $$A_1 = \Delta l_1 = -\frac{mg}{k_1}$$
    $$A_2 = \Delta l_2 = -\frac{mg}{k_2}$$
    $$\omega = \frac{\sqrt[]{k_2}}{\sqrt[]{m}}$$
    $$\Downarrow$$
    $$y_{(t)} = l_1 + l_2 - \frac{2mg}{k_1}\cos{(\frac{\sqrt[]{k_2}}{\sqrt[]{m}} t)}$$
3. **עשינו בכיתה**
4. נתון:  

    $$M$$
    $$L$$
    $$k$$
    $$\alpha_0$$
    1. צ"ל $\alpha$

    $$I.\ \ \ \tan{\alpha} = \frac{\Delta x}{L}$$
    $$II.\ \ \ \tan{\alpha_0} = \frac{\Delta x_0}{L}$$
    $$III.\ \ \ \Delta x_0k = A$$
    $$IV.\ \ \ \omega = \frac{\sqrt[]{k}}{\sqrt[]{m}}$$
    $$V.\ \ \ x_{(t)} = l_0 + A\cos{(\omega t)}$$
    $$\Downarrow$$
    $$II.\ \ \ \Delta x_0 = L\tan{\alpha_0}$$
    $$III.\ \ \ A = Lk\tan{\alpha_0}$$
    $$V.\ \ \ x_{(t)} = l_0 + Lk\tan{\alpha_0}\cos{(\frac{\sqrt[]{k}}{\sqrt[]{m}} t)}$$
    $$I.\ \ \ \tan{\alpha} = \frac{x - l_0}{L}$$
    $$I.\ \ \ L\tan{\alpha} = x - l_0$$
    $$I.\ \ \ x = L\tan{\alpha} + l_0$$
    $$V.\ \ \ \cancel{L}\tan{\alpha} + \cancel{l_0} = \cancel{l_0} + \cancel{L}k\tan{\alpha_0}\cos{(\frac{\sqrt[]{k}}{\sqrt[]{m}} t)}$$
    $$V.\ \ \ \tan{\alpha} = k\tan{\alpha_0}\cos{(\frac{\sqrt[]{k}}{\sqrt[]{m}} t)}$$
    $$\alpha_{(t)} = \arctan{(k\tan{(\alpha_0)}\cos{(\frac{\sqrt[]{k}}{\sqrt[]{m}} t)})}$$
    2. המתיחות במוט מושפעת מהכוחות המופעלים על המסה בכיוון המוט, המצב אנכי מופעל כוח הכבידה על המסה, וגם כן כוח צנטירפיטאלי.
    נחשב את הכוח הצנטרפיטאלי על מנת לחברו לכוח המשיכה ובכך נמצא את מתיחות החוט:  
    
    $$r = L$$
    $$\dot{r} = 0$$
    $$\ddot{r} = 0$$
    $$\theta_{(t)} = \arctan{(k\tan{(\alpha_0)}\cos{(\frac{\sqrt[]{k}}{\sqrt[]{m}} t)})}$$
5. נתון

    $$m$$
    $$F_{(x)} = -A(e^{ax} - e^{-ax})$$
    1. $x=0$, צ"ל $F = 0$:  
    
    $$F = -A(e^{0} - e^{0})$$
    $$F = -A(1 - 1)$$
    $$F = -A\cdot 0$$
    $$F = 0$$

    2. צ"ל $T$
    
    $$I.\ \ \ T = \frac{2 \pi}{\omega}$$
    $$II.\ \ \ e^x = 1+x$$
    $$III.\ \ \ F = m\omega^2x$$
    $$IV.\ \ \ F = -A(e^{ax} - e^{-ax})$$
    $$\Downarrow$$
    $$m\omega^2x = -A(e^{ax} - e^{-ax})$$
    $$m\omega^2x = -A(1 + ax - (1 - ax))$$
    $$m\omega^2\cancel{x} = -A(2a\cancel{x})$$
    $$\omega^2 = \frac{2Aa}{m}$$
    $$\omega = \frac{\sqrt[]{2Aa}}{\sqrt[]{m}}$$
    $$T = \frac{2 \pi}{\omega}$$
    $$T = \frac{2 \pi\sqrt[]{m}}{\sqrt[]{2Aa}}$$
6. **עשינו בכיתה**
7. **להשלים**
8. **עשינו בכיתה**
9. 

תנע התחלתי: $p_0 = 0$  

תנע בתחילת ההליכה (לפני תזוזת העגלה): $p_1 = (M+m)v_{1_{cart}} + mv_{1_{man}}$ 

$$p_0 = p_1$$
$$v_{1_{man}} = v_R$$
$$0 = (M+m)v_{_{cart}} + mv_R$$
$$(M+m)v_{_{cart}} = -mv_R$$
$$v_{_{cart}} = -\frac{mv_R}{M+m}$$
$$v_{_{man}} = v_{1_{man}} + v_{_{cart}}$$
$$v_{_{man}} = v_R -\frac{mv_R}{M+m}$$
$$v_{_{man}} = v_R(1-\frac{m}{M+m})$$
$$v_{_{man}} = v_R(\frac{M+m-m}{M+m})$$
$$v_{_{man}} = \frac{Mv_R}{M+m}$$
10. תחילה נחשב את פונקציה מהירות קרונית כזריקת האבנים.

    $$p_0 = 0$$
    $$p_1 = (M-m)v_{1_{cart}} + mv_{1_{stone}}$$
    $$v_{1_{stone}} = v_0$$
    $$p_1 = p_0 = 0$$
    $$0 = (M-m)v_{1_{cart}} + mv_0$$
    $$(M-m)v_{1_{cart}} = -mv_0$$
    $$v_{1_{cart}} = -\frac{m}{M-m}v_0$$
    $$p_2 = (M-2m)v_{2_{cart}} + mv_{2_{stone}}$$
    $$v_{2_{stone}} = v_0 -\frac{m}{M-m}v_0 = v_0 (1-\frac{m}{M-m})=v_0\frac{M-2m}{M-m}$$
    $$p_2 = p_1 = p_0 = 0$$
    $$0 = (M-2m)v_{2_{cart}} + mv_0\frac{M-2m}{M-m}$$
    $$(M-2m)v_{2_{cart}} =-mv_0\frac{M-2m}{M-m}$$
    $$v_{2_{cart}} =-\frac{m}{M-2m}v_0\frac{M-2m}{M-m}$$
    $$v_{2_{cart}} =-\frac{m}{M-m}v_0$$
    $$\Downarrow$$
    $$v_{_{cart}} =-\frac{m}{M-m}v_0$$
    קיבלנו שלאחר הזריקה הראשונה, מהירות העגלה לא מושפעת מזריקות נוספות.  
    כעת נחשב את מהירות העגלה אם נזרוק בו זמנית $n$ אבנים.  

    $$p_{tot} = (M- nm)v_{_{cart}} + nmv_{_{stone}}$$
    $$v_{_{stone}} = v_0$$
    $$p_{tot} = 0$$
    $$0 = (M- nm)v_{_{cart}} + nmv_0$$
    $$(M- nm)v_{_{cart}} = - nmv_0$$
    $$v_{_{cart}} = -\frac{nm}{M- nm} v_0$$
    1. בזריקת אבן בודדת:  

    $$v_{_{cart}} =-\frac{m}{M-m}v_0$$
    בזריקת מספר אבנים בו זמנית:   

    $$v_{(n)_{cart}} = -\frac{nm}{M- nm} v_0$$
    2. מהירות הקרונית תהיה גבוהה יותר כאשר נזרוק מספר אבנים בו זמנית, זאת מיכוון שעבור $n>1$ אז:  $\frac{m}{M-m}v_0 < \frac{nm}{M- nm} v_0$