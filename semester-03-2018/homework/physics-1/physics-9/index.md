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
1. **עשינו בכיתה**
2. $$E_1 = E_2$$
    $$E_1 = 2mgR + \int_0^{2R}kx\delta x$$
    $$E_1 = 2mgR + (k\frac{x^2}{2})|_0^{2R}$$
    $$E_1 = 2mgR + (k\frac{4R^2}{2})$$
    $$E_1 = 2mgR + 2kR^2$$
    $$E_2 = \frac{mv^2}{2}$$
    $$\Downarrow$$
    $$\frac{mv^2}{2} = 2mgR + 2kR^2$$
    $$v^2 = 4gR + \frac{4kR^2}{m}$$
    $$v^2 = 4(gR+\frac{kR^2}{m})$$
    $$v = 2\sqrt[]{gR+\frac{kR^2}{m}}$$
    ללא ערך שלילי כי לא הגדרנו את כיוון המהירות ולכן היא גודל, וגודל תמיד חיובי.
3. $$E_1 = E_2$$
    $$\Downarrow$$
    $$mgh= 2mgR + mv^2\frac{1}{2}$$
    $$ma\hat{r} = -mg$$
    $$a = -g = \frac{v^2}{r}$$
    $$v^2 = -gR$$
    $$\Downarrow$$
    $$mgh= 2mgR - mgR\frac{1}{2}$$
    $$h= 2R - R\frac{1}{2}$$
    $$h= \frac{3}{2}R$$
4. **עשינו בכיתה**
5. 1.
    נבנה טבלת כוחות:  
    |שם|$\hat{r}$|$\hat{\theta}$|
    |:-:|:-:|:-:|
    |משיכה|$-mg\sin{\theta}$|$mg\cos{\theta}$|
    |נורמלי|$N$||
    |חיכוך||$-N\mu$|
    $$\sum F = (N-mg\sin{\theta})\hat{r} + (-N\mu + mg\cos{\theta})\hat{\theta}$$
    2. גודלו של $N$ בעת ההתנתקות חייב להיות $0$, מכיוון שהכוח צנטריפטאלי עולה על כוח המשיכה בכיוון $\hat{r}$ ולכן גורם לו להתנתק, ואין יותר מגע בינו לבין המשטח.

6. **להשלים**
7. 1.
    $$\dot{\theta}_1 = \omega_1$$
    $$r_1 = l_1$$
    $$r_2 = l_2$$
    $$\dot{\theta}_2 = ?$$
    $$\Downarrow$$
    $$\vec{F}_1 = T_1 = ma_1$$
    $$\vec{F}_2 = T_2 = ma_2$$
    $$\Downarrow$$
    $$a_1 = (0 - l_1\omega_1^2)\hat{r} + 0\hat{\theta}$$
    $$a_2 = (0 - l_2\dot{\theta}_2^2)\hat{r} + 0\hat{\theta}$$
    $$\Downarrow$$
    $$-l_1\omega_1^2 = -l_2\dot{\theta}_2^2$$
    $$\dot{\theta}_2^2=\frac{l_1}{l_2}\omega_1^2$$
    $$\dot{\theta}_2=\sqrt{\frac{l_1}{l_2}}\omega_1$$
    2.
    $$E_{k_1} = \frac{1}{2}mv_1^2 = \frac{1}{2}m(\omega_1l_1)^2 = \frac{1}{2}ml_1^2\omega_1^2$$
    $$E_{k_2} = \frac{1}{2}mv_2^2 = \frac{1}{2}m(\sqrt{\frac{l_1}{l_2}}\omega_1l_2)^2 = \frac{1}{2}ml_1l_2\omega_1^2$$
    $$\Delta E_k = E_{k_2}-E_{k_1}$$
    $$\Downarrow$$
    $$\Delta E_k = \frac{1}{2}ml_1l_2\omega_1^2 - \frac{1}{2}ml_1^2\omega_1^2$$
    $$\Delta E_k = \frac{1}{2}ml_1\omega_1^2(l_2 - l_1)$$
    חישבנו את השינוי באנרגיה הקינטית, כעת נחשב את העבודה שנעשתה במשיכה ונקווה שהם זהים.  
    מכיוון שהחוט נמשך במהירות זהה, אז תאוצתו אפסית, ולכן המתיחות שלו בהתחלה שווה למתיחות שלו בסוף (לא מופעלים כוחות נוספים).


    $$T_1 = m((0 - l_1\omega_1^2)\hat{r} + 0\hat{\theta}) = -ml_1\omega_1^2$$
    $$W = \int_{l_1}^{l_2}\sum F_{(r)}$$
    $$\sum F_{(r)} = T_{(r)} = T_1$$
    $$\Downarrow$$
    $$W = \int_{l_1}^{l_2}-ml_1\omega_1^2 \delta x$$
    $$W =-ml_1\omega_1^2x |_{l_1}^{l_2}$$
    $$W =-ml_1\omega_1^2(l_2 - l_1)$$

8. **עשינו בכיתה**
9. 
    $$E_1 = mg(-6L+3L) = -3mgL$$
    $$E_2 = -9mgL + \frac{1}{2}mv^2$$
    $$E_1 = E_2$$
    $$\Downarrow$$
    $$-3mgL = -9mgL + \frac{1}{2}mv^2$$
    $$\frac{1}{2}mv^2=6mgL$$
    $$mv^2=12mgL$$
    $$v^2=12gL$$
    $$|v|=\sqrt{12gL}$$
10. **עשינו בכיתה**