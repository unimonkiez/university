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
$$a = -2(\frac{21\pi}{30})^2\hat{r}$$
$$F = (-\frac{49\pi^2}{50}\hat{r})m$$
$$F^1 = F^2$$
$$\Downarrow$$
$$(-\frac{49\pi^2}{50}\hat{r})m = m \cdot ((\ddot{r} - r\dot{\theta}^2)\hat{r} + (2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta})$$
$$r = R$$
$$\dot{r} = 0$$
$$\ddot{r} = 0$$
$$\dot{\theta} = x$$
$$\ddot{\theta} = 0$$
$$\Downarrow$$
$$(-\frac{49\pi^2}{50}\hat{r})m = m \cdot ((0 - Rx^2)\hat{r} + (0 + 0)\hat{\theta})$$
$$-\frac{49\pi^2}{50}\hat{r} = (0 - Rx^2)\hat{r} + (0 + 0)\hat{\theta}$$
$$-\frac{49\pi^2}{50}\hat{r} = -Rx^2\hat{r}$$
$$-\frac{49\pi^2}{50} = -Rx^2$$
$$Rx^2 = \frac{49\pi^2}{50}$$
$$x^2 = \frac{49\pi^2}{50}\cdot \frac{1}{R}$$
$$x = \sqrt[]{2}\cdot \frac{21\pi}{30} \cdot \sqrt[]{\frac{1}{R}}$$
$$x = \frac{21\pi}{30} \cdot \sqrt[]{\frac{2}{R}}$$
$$\Downarrow$$
$$f = \frac{x}{2\pi}$$
$$f = \frac{\frac{21\pi}{30} \cdot \sqrt[]{\frac{2}{R}}}{2\pi}$$
$$f = \frac{21\sqrt[]{\frac{2}{R}}}{60}$$

קצב הסיבוב המקסימלי הוא $21\sqrt[]{\frac{2}{R}}$ סל"ד.

3. תחילה נחשב את הכוח הצנטריפיטלי - 

$$a = \frac{v^2}{r} = \frac{v_0^2}{R}$$

נבחר x בכיוון מרכז החרוט, וy בכיוון הנגדי לכוח המשיכה - 

|שם|x|y|
|:---:|:---:|:---:|
|נורמלי|$N\cos{\theta}$|$N\sin{\theta}$|
|כבידה||$-mg$|
|צנטריפיטלי|$-\frac{v_0^2}{R}$||

$$\sum F = 0$$
$$\Downarrow$$
$$I. \ \ \ N\cos{\theta} - \frac{v_0^2}{R} = 0$$
$$II. \ \ \ N\sin{\theta} - mg = 0$$
$$II. \ \ \ N\sin{\theta} = mg$$
$$II. \ \ \ N = \frac{mg}{\sin{\theta}}$$
$$I. \ \ \ \frac{mg}{\sin{\theta}}\cos{\theta} - \frac{v_0^2}{R} = 0$$
$$I. \ \ \ \frac{v_0^2}{R} = \frac{\cos{\theta}mg}{\sin{\theta}}$$
$$I. \ \ \ R \cos{\theta}mg = v_0^2 \sin{\theta}$$
$$I. \ \ \ R  = \frac{v_0^2 \sin{\theta}}{\cos{\theta}mg}$$
$$I. \ \ \ R  = \frac{v_0^2 \tan{\theta}}{mg}$$
4. עשינו בכיתה
5. נתון:  

    $$a = -\alpha v -\beta v^2$$
    1.
    
    $$a = -\alpha v -\beta v^2$$
    $$\dot{v} = -\alpha v -\beta v^2$$
    2.
    
    $$v_{(t)} = \frac{\alpha}{C \alpha e^{\alpha t} - \beta}$$
    צ"ל

    $$\dot{v} = -\alpha v -\beta v^2$$
    פתרון:  

    $$\dot{v} = \dot{\overline{(\frac{\alpha}{C \alpha e^{\alpha t} - \beta})}}$$
    $$\dot{v} = \frac{-\alpha \cdot (\dot{\overline{C \alpha e^{\alpha t} - \beta}})}{(C \alpha e^{\alpha t} - \beta)^{2}}$$
    $$\dot{v} = \frac{-\alpha \cdot (C \alpha^2 e^{\alpha t})}{(C \alpha e^{\alpha t} - \beta)^{2}}$$
    $$\dot{v} = \frac{-C \alpha^3 e^{\alpha t}}{(C \alpha e^{\alpha t} - \beta)^{2}}$$
    כעת נבדוק את הצד השני של המשוואה: 

    $$-\alpha v -\beta v^2 = -\alpha(\frac{\alpha}{C \alpha e^{\alpha t} - \beta}) -\beta(\frac{\alpha}{C \alpha e^{\alpha t} - \beta})^2$$
    $$-\alpha v -\beta v^2 = -\frac{\alpha^2}{C \alpha e^{\alpha t} - \beta} -\frac{\alpha^2\beta}{(C \alpha e^{\alpha t} - \beta)^2}$$
    $$-\alpha v -\beta v^2 = -\frac{\alpha^2(C \alpha e^{\alpha t} - \beta)}{(C \alpha e^{\alpha t} - \beta)^2} -\frac{\alpha^2\beta}{(C \alpha e^{\alpha t} - \beta)^2}$$
    $$-\alpha v -\beta v^2 = -\frac{\alpha^2(C \alpha e^{\alpha t} - \beta) + \alpha^2\beta}{(C \alpha e^{\alpha t} - \beta)^2}$$
    $$-\alpha v -\beta v^2 = -\frac{\alpha^2(C \alpha e^{\alpha t} \cancel{-\beta} \cancel{+\beta})}{(C \alpha e^{\alpha t} - \beta)^2}$$
    $$-\alpha v -\beta v^2 = -\frac{C \alpha^3 e^{\alpha t}}{(C \alpha e^{\alpha t} - \beta)^2}$$
    $$\Downarrow$$
    $$\dot{v} = -\alpha v -\beta v^2 = \frac{-C \alpha^3 e^{\alpha t}}{(C \alpha e^{\alpha t} - \beta)^{2}}$$
    3. נתון:  
    
    $$v_{t=t_0} = v_0$$
    צ"ל:  
    
    $$C=?$$
    פתרון:  

    $$v_{(t)} = \frac{\alpha}{C \alpha e^{\alpha t} - \beta}$$
    $$t=t_0$$
    $$\Downarrow$$
    $$v_0 = \frac{\alpha}{C \alpha e^{\alpha t_0} - \beta}$$
    $$v_0(C \alpha e^{\alpha t_0} - \beta) = \alpha$$
    $$C \alpha e^{\alpha t_0} - \beta = \frac{\alpha}{v_0}$$
    $$C \alpha e^{\alpha t_0} = \frac{\alpha}{v_0} + \beta$$
    $$C \alpha e^{\alpha t_0} = \frac{\alpha + v_0\beta}{v_0}$$
    $$C = \frac{\alpha + v_0\beta}{v_0\alpha e^{\alpha t_0}}$$

    4. נתון:  
    
    $$x_{t=t_0} = x_0 = 0$$
    $$\int\frac{\delta x}{r + se^{px}} = \frac{1}{pr}\ln{(\frac{1}{re^{-px} + s})}$$
    צ"ל:  
    
    $$x_{(t)}=?$$
    פתרון:  

    $$\int_{0}^{t}v_{(t)} = x_{(t)} +x_0$$
    $$x_{(t)} = \int_{t_0}^{t}v_{(t)} \cancel{-0}$$
    $$x_{(t)} = \int_{t_0}^{t}\frac{\alpha}{C \alpha e^{\alpha t} - \beta}$$
    $$\int\frac{\delta x}{r + se^{px}} = \frac{1}{pr}\ln{(\frac{1}{re^{-px} + s})}$$
    $$r=-\beta$$
    $$s=C\alpha$$
    $$p=\alpha$$
    $$\Downarrow$$
    $$x_{(t)} = \frac{1}{-\beta \alpha}\ln{(\frac{1}{-\beta e^{-\alpha x} + C\alpha})}$$
    $$C = \frac{\alpha + v_0\beta}{v_0\alpha e^{\alpha t_0}}$$
    $$\Downarrow$$
    $$x_{(t)} = \frac{1}{-\beta \alpha}\ln{(\frac{1}{-\beta e^{-\alpha x} + \frac{\alpha + v_0\beta}{v_0\alpha e^{\alpha t_0}}\alpha})}$$
    $$x_{(t)} = \frac{1}{-\beta \alpha}\ln{(\frac{1}{\frac{\alpha^2 + v_0\alpha\beta-\beta e^{-\alpha x}(v_0\alpha e^{\alpha t_0})}{v_0\alpha e^{\alpha t_0}}})}$$
    $$x_{(t)} = \frac{1}{-\beta \alpha}\ln{(\frac{v_0\alpha e^{\alpha t_0}}{\alpha^2 + v_0\alpha\beta-\beta e^{-\alpha x}(v_0\alpha e^{\alpha t_0})})}$$
    $$x_{(t)} = \frac{1}{-\beta \alpha}\ln{(\frac{v_0\alpha e^{\alpha t_0}}{\alpha^2 + v_0\alpha\beta-v_0\alpha\beta e^{\alpha t_0-\alpha x}})}$$
    $$x_{(t)} = \frac{1}{-\beta \alpha}\ln{(\frac{v_0\alpha e^{\alpha t_0}}{\alpha^2 + v_0\alpha\beta-v_0\alpha\beta e^{\alpha (t_0-x)}})}$$
    $$x_{(t)} = \frac{1}{-\beta \alpha}\ln{(\frac{v_0\alpha e^{\alpha t_0}}{\alpha^2 + v_0\alpha\beta(1 - e^{\alpha (t_0-x)})})}$$
    5. אין מצב שאני מצליח (כנראה טעיתי בסעיף הקודם).
    6. ראה סעיף 5.

6. נתון:  

    $$\dot{\theta}_{t=0} = \omega_0$$
    $$r_{t=0} = R_0$$
    $$L_{(t)} = R_0-v_0t$$
    1. צ"ל  

    $$\vec{v_{AB}} = ?\hat{r}$$
    פתרון:  

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
    4. 
    
    $$\dot{\theta} = \frac{B}{(R_0-v_0(t-t_0))^2}$$
    $$\dot{\theta}_{(t=t_0)} = \omega_0$$
    $$\Downarrow$$
    $$\omega_0 = \frac{B}{(R_0-v_0(t_0-t_0))^2}$$
    $$\omega_0 = \frac{B}{R_0^2}$$
    $$B = \omega_0 R_0^2$$

    5.

    $$\dot{\theta} = \frac{B}{(R_0-v_0(t-t_0))^2}$$
    $$B = \omega_0 R_0^2$$
    $$\Downarrow$$
    $$\dot{\theta} = \frac{\omega_0 R_0^2}{(R_0-v_0(t-t_0))^2}$$

    6. לפי הנוסחא ($\dot{\theta} = \frac{\omega_0 R_0^2}{(R_0-v_0(t-t_0))^2}$), המכנה קטן ככל שהזמן גדל, גדילת המכנה מביאה לגדילת ערך המהירות בריבוע, לפי כך ניתן להבין כי המהירות תגדל בקצב מרובע ככך שהזמן יעבור.  
    7. כפי שאמרנו קודם, המהירות גדלה בקצב מרובע לשינוי בזמן, גדילה מרובעת ז"א תאוצה קבועה.  
7. נתון  

$$Ay'_{(x)} + Cy_{(x)}^2 - B = 0 \Rightarrow y_{(x)} = (\frac{B}{C})^{\frac{1}{2}}tanh{[A^{-1}(BC)^{\frac{1}{2}}(x+C_1)]}$$
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
$$mg-kv^2-ma_y = 0$$
$$mg-kv^2-m\dot{v} = 0$$
$$Ay'_{(x)} + Cy_{(x)}^2 - B = 0 \Rightarrow y_{(x)} = (\frac{B}{C})^{\frac{1}{2}}tanh{[A^{-1}(BC)^{\frac{1}{2}}(x+C_1)]}$$
$$A=m$$
$$B=mg$$
$$C=k$$
$$C_1=0$$
$$\Downarrow$$
$$v_{(t)} = (\frac{mg}{k})^{\frac{1}{2}}tanh{[m^{-1}(mgk)^{\frac{1}{2}}(t+0)]}$$
$$v_{(t)} = (\frac{mg}{k})^{\frac{1}{2}}tanh{[(\frac{mgk}{m^2})^{\frac{1}{2}}t]}$$
$$v_{(t)} = (\frac{mg}{k})^{\frac{1}{2}}tanh{[(\frac{gk}{m})^{\frac{1}{2}}t]}$$
$$v_{(t)} = \sqrt[]{\frac{mg}{k}}tanh{[\sqrt[]{\frac{gk}{m}}t]}$$

8. עשינו בכיתה  
9. צ"ל

$$N = mg(cos{\theta} - sin{\theta}(tan{\phi}))$$
פתרון:  

|שם|x|y|
|:---:|:---:|:---:|
|כבידה||$-mg$|
|נורמלי|$N\sin{\theta}$|$N\cos{\theta}$|
|מתיחות|$-T\cos{(\theta+\phi)}$|$T\sin{(\theta+\phi)}$|

נתון מהירות קבועה לגוף, ז"א תאוצה אפסית

$$\sum{\vec{F}} = 0$$
$$\Downarrow$$
$$I. \ \ \ N\sin{\theta} - T\cos{(\theta+\phi)} = 0$$
$$II. \ \ \ -mg + N\cos{\theta} + T\sin{(\theta+\phi)} = 0$$
$$\sin{(\alpha \pm \beta)} = \sin{\alpha}\cos{\beta} \pm \cos{\alpha}\sin{\beta}$$
$$\cos{(\alpha \pm \beta)} = \cos{\alpha}\cos{\beta} \mp \sin{\alpha}\sin{\beta}$$
$$\Downarrow$$
$$I. \ \ \ N\sin{\theta} - T(\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}) = 0$$
$$II. \ \ \ -mg + N\cos{\theta} + T(\sin{\theta}\cos{\phi} + \cos{\theta}\sin{\phi}) = 0$$
$$I. \ \ \ T(\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}) = N\sin{\theta}$$
$$I. \ \ \ T = \frac{N\sin{\theta}}{\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}}$$
$$II. \ \ \ -mg + N\cos{\theta} + \frac{N\sin{\theta}(\sin{\theta}\cos{\phi} + \cos{\theta}\sin{\phi})}{\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}} = 0$$
$$II. \ \ \ N\cos{\theta} + \frac{N\sin{\theta}(\sin{\theta}\cos{\phi} + \cos{\theta}\sin{\phi})}{\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}} = mg$$
$$II. \ \ \ N(\cos{\theta} + \frac{\sin{\theta}(\sin{\theta}\cos{\phi} + \cos{\theta}\sin{\phi})}{\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}}) = mg$$
$$II. \ \ \ N(\frac{\sin{\theta}(\sin{\theta}\cos{\phi} + \cos{\theta}\sin{\phi}) + \cos{\theta}(\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi})}{\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}}) = mg$$
$$II. \ \ \ N = mg\frac{1}{\frac{\sin{\theta}(\sin{\theta}\cos{\phi} + \cos{\theta}\sin{\phi}) + \cos{\theta}(\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi})}{\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}}}$$
$$II. \ \ \ N = mg\frac{\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}}{\sin{\theta}(\sin{\theta}\cos{\phi} + \cos{\theta}\sin{\phi}) + \cos{\theta}(\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi})}$$
$$II. \ \ \ N = mg\frac{\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}}{\sin^2{\theta}\cos{\phi} + \cancel{\sin{\theta}\cos{\theta}\sin{\phi}} + \cos^2{\theta}\cos{\phi} - \cancel{\cos{\theta}\sin{\theta}\sin{\phi}}}$$
$$II. \ \ \ N = mg\frac{\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}}{\sin^2{\theta}\cos{\phi} + \cos^2{\theta}\cos{\phi}}$$
$$II. \ \ \ N = mg\frac{\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}}{\cos{\phi}(\sin^2{\theta} + \cos^2{\theta})}$$
$$\cos^2{\alpha} + \sin^2{\alpha} = 1$$
$$II. \ \ \ N = mg\frac{\cos{\theta}\cos{\phi} - \sin{\theta}\sin{\phi}}{\cos{\phi}\cancel{(1)}}$$
$$II. \ \ \ N = mg(\cos{\theta} - \sin{\theta}\tan{\phi})$$


10. נתון:  

$$N = mg(\cos{\theta} - \sin{\theta}\tan{\phi})$$
$$\theta + \phi = 90\degree \Longrightarrow \theta = 90\degree - \phi$$
צ"ל  

$$N = 0$$
פתרון 

$$N = mg(\cos{(90\degree - \phi)} - \sin{(90\degree - \phi)}\tan{\phi})$$
$$\sin{(\alpha \pm \beta)} = \sin{\alpha}\cos{\beta} \pm \cos{\alpha}\sin{\beta}$$
$$\cos{(\alpha \pm \beta)} = \cos{\alpha}\cos{\beta} \mp \sin{\alpha}\sin{\beta}$$
$$\Downarrow$$
$$N = mg((\cos{90\degree}\cos{\phi} + \sin{90\degree}\sin{\phi}) - \tan{\phi}(\sin{90\degree}\cos{\phi} - \cos{90\degree}\sin{\phi}))$$
$$\sin{90\degree} = 1$$
$$\cos{90\degree} = 0$$
$$\Downarrow$$
$$N = mg(\sin{\phi} - \tan{\phi}\cos{\phi})$$
$$N = mg(\sin{\phi} - \frac{\sin{\phi}}{\cos{\phi}}\cos{\phi})$$
$$N = mg(\sin{\phi} - \sin{\phi})$$
$$N = mg \cdot 0 = 0$$
מש"ל.  
דבר זה קורה מכיוון שאם 2 הזוויות שוות $90\degree$, ז"א שהחוט מקביל לכוח המשיכה.  
בגלל שנתון תנועה קבועה בכיוון החוט, ז"א שהמגלשה מרחפת למעלה ולא נוגעת בתריס, ולכן הכוח הנורמלי מתאפס.  