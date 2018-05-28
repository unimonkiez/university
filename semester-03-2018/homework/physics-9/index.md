<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# ש"ב פיזיקה - תרגיל 9
## יובל סרף
1. 
    1.
    
    $$W = \int_0^{\Delta x} -F \delta x$$
    $$W = \int_0^{\Delta x} -kx \delta x$$
    $$W = -\frac{1}{2}k\Delta x ^2$$

    2.

    $$\Delta x < 0$$
    $$h > 0$$
    
    $$E_1 = mgh$$
    $$E_2 = \frac{k}{2}(\Delta x)^2 + mg\Delta x$$
    $$E_1 = E_2$$
    $$\Downarrow$$
    $$E_1 = E_2$$
    $$\Delta x_{1, 2} = \frac{mg}{k}(-1 \pm \sqrt[]{1+\frac{2kh}{mg}})$$
    נבחר את השלילי כי $\Delta x < 0$ (מטעמים פיזיקליים):

    $$\Delta x = \frac{mg}{k}(-1 - \sqrt[]{1+\frac{2kh}{mg}})$$

    3.
        שלבי פתרון:  
        1. $\sum F = m\ddot{x}$
        2. תנאי התחלה
        3. הגדרת $x'$ שיתאים לתבנית $m\ddot{x} = -kx'$, המוכרת והחביבה  
        4. הצבת תנאי תהחלה וחזרה ל-$x$ 

    פתרון:
    
    $$\sum F = m\ddot{x}$$
    $$\sum F = -kx-mg$$
    $$m\ddot{x} = -k(x+\frac{mg}{k})$$
    $$x' = x+\frac{mg}{k}$$
    $$\Downarrow$$
    $$m\ddot{x'} = -kx'$$
    $$x'=A\sin{(\omega t + \phi)}$$
    $$\omega = \sqrt[]{\frac{k}{m}}$$
    נמצא תנאי התחלה בשביל למצוא את 2 הנעלמים:  
    
    $$x_{(t=0)} = 0$$
    $$mgh = \frac{1}{2}mv^2$$
    $$v = \pm \sqrt[]{2gh}$$
    מינוס מסיבה פיזיקלית

    $$v = -\sqrt[]{2gh} = \dot{x'}$$
    $$\Downarrow$$
    $$I.\ \ \ A\sin{(\phi)} = \frac{mg}{k}$$
    $$II.\ \ \ \omega A \cos{(\phi)} = -\sqrt[]{2gh}$$
    $$\tan \phi = -\frac{mg}{k\sqrt[]{2gh}}\sqrt[]{\frac{k}{m}}$$
    $$A = \sqrt[]{(\frac{mg}{k})^2 + \frac{2ghm}{k}}$$
    $$\Downarrow$$
    $$x = \sqrt[]{(\frac{mg}{k})^2 + \frac{2ghm}{k}}\sin{(\omega t + \phi)}-\frac{mg}{k}$$

2. $$E_1 = E_2$$
    $$E_1 = mgh + \int_0^hkx\delta x$$
    $$E_1 = mgh + (k\frac{x^2}{2})|_0^h$$
    $$E_1 = mgh + (k\frac{h^2}{2})$$
    $$E_2 = \frac{mv^2}{2}$$
    $$\Downarrow$$
    $$\frac{mv^2}{2} = mgh + (k\frac{h^2}{2})$$
    $$\frac{v^2}{2} = gh + \frac{kh^2}{2m}$$
    $$v^2 = 2gh + \frac{kh^2}{m}$$
    $$v = \sqrt[]{2gh + \frac{kh^2}{m}}$$
    ללא ערך שלילי כי לא הגדרנו את כיוון המהירות ולכן היא גודל, וגודל תמיד חיובי.
3. $$h>2R$$

    מכיוון שעבור ערך $0<h<2R$ הארנרגיה הפונטציאלית לא עולה על האנרגיה הפונטציאלית כדי לעבור את הלולאה ($E=M2Rg$) והגוף פשוט יתקע בתנועה הרמנונית בין המדרון ללולאה.  
    עבור $h=2R$, מהכיוון שהגוף משוחרר ממנוחה אז יגיע גם כן למנוחה ($v=0$) ולכן יפול ישירות מטה במעלה הלולאה וישאר במקום בתחתית שלה.  
    עבור כל ערך $h>2R$, גם אם לא מספיק כדי להשלים את הלולאה ללא התנתקות, הגוף יגיע עם מהירות גדולה מ-0 ולכן גם אם יפול, בהכרח יגיע לסוף המסילה.  
4.  
    $$\ddot{r} = (\ddot{r} - r\dot{\theta}^2)\hat{r} + (2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta}$$
    1.
    
    $$\sum F_r = N-mg\sin{\theta} = -mr\dot{\theta}^2$$
    $$E_1 = mgR$$
    $$E_2 = \frac{1}{2}mv^2 + mR\sin{\theta}$$
    $$\Downarrow$$
    $$I.\ \ \ g\sin{\theta} = r\dot{\theta}^2$$
    $$II.\ \ \ gR=\frac{1}{2}(R\dot{\theta})^2+gR\sin{\theta}$$
    $$\sin{\theta} = \frac{2}{3}$$

    2.
    $$mgR = \frac{1}{2}mv^2+mgR\sin{\theta}$$
    $$v = R\dot{\theta}$$
    $$\dot{\theta} = \sqrt[]{\frac{2g}{R}(1-\sin{\theta})}$$

    3.
    $$\int_0^t\sqrt[]{\frac{2g}{R}(1-\sin{\theta})}\delta t = \int_{\frac{\pi}{2}}^{\sin^{-1}{\frac{2}{3}}}\delta \theta$$
5. **להשלים**
6. **להשלים**
7. **להשלים**
8. **להשלים**
9. **להשלים**
10.
    $$G = -6.67\cdot 10^{-11}_{\frac{m}{s^2}}$$
    $$M_e = 6\cdot 10^{24}_{kg}$$
    $$M_m = 7\cdot 3\cdot 10^{22}_{kg}$$
    $$R_e = 6.4\cdot 10^6_{m}$$
    $$R_m = 1.7\cdot 10^6_{m}$$
    $$R_{me} = 3.8\cdot 10^{8}_{m}$$
    $$m=50_{kg}$$
    $$\Downarrow$$

    $$u_e = -\frac{GM_em}{R_e}$$
    $$u_m = -\frac{GM_mm}{R_{me}}$$


    $$u_T^E = -G(\frac{M_em}{R_e} + \frac{M_mm}{R_{me}}) = -3.1\cdot 10^9_J$$
    $$u_T^M = -G(\frac{M_em}{R_{me}} + \frac{M_mm}{R_{m}}) = -2\cdot 10^8_J$$
    $$\Delta u = u_T^M - u_T^E = 6.9\cdot 10^9_{J} = 6.9\cdot 10^5_{kal}$$