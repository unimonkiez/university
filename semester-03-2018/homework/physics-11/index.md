<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# ש"ב פיזיקה - תרגיל 11
## יובל סרף
1. **עשינו בכיתה**
2.
    1.
        $$\vec{r} = r\hat{r} + \theta\hat{\theta} + 0\hat{z}$$
        $$\vec{F} = m(\ddot{r} - r\dot{\theta}^2)\hat{r} + m(2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta} + 0\hat{z}$$
        $$\vec{\tau} = \frac{\delta \vec{L}}{\delta t} = \vec{r} \otimes \vec{F}$$
        $$\Downarrow$$
        $$\frac{\delta \vec{L}}{\delta t} =
        (\theta \cdot 0 - 0 \cdot m(2\dot{r}\dot{\theta} + r\ddot{\theta}))\hat{r} +
        (r \cdot 0 - 0 \cdot m(\ddot{r} - r\dot{\theta}^2))\hat{\theta} +
        (r\cdot m(2\dot{r}\dot{\theta} + r\ddot{\theta}) - \theta\cdot m(\ddot{r} - r\dot{\theta}^2))\hat{z}
        $$
        $$\frac{\delta \vec{L}}{\delta t} = (r\cdot m(2\dot{r}\dot{\theta} + r\ddot{\theta}) - \theta\cdot m(\ddot{r} - r\dot{\theta}^2))\hat{z}$$
        $$\frac{\delta \vec{L}}{\delta t} = (2mr\dot{r}\dot{\theta} + mr^2\ddot{\theta} - m\theta\ddot{r} + mr\theta\dot{\theta}^2)\hat{z}$$
3. **עשינו בכיתה**
4. 
    $$U_{(r)} = -Ar^n, A>0$$
    $$\vec{F} = -\frac{U_{(r)}}{\delta r}$$
    $$\vec{F} = -\frac{-Ar^n}{\delta r}$$
    $$\vec{F} = \frac{Ar^n}{\delta r}$$
    $$\vec{F} = nAr^{n-1}$$
    $$\vec{F} = m\vec{\ddot{r}}$$
    $$r = const \Rightarrow \dot{r} = \ddot{r} = 0 \Downarrow$$
    $$\vec{F} = nAr^{n-1} = -mr\dot{\theta}^2$$
    $$\dot{\theta} = \frac{L}{mr^2} \Downarrow$$
    $$nAr^{n-1} = -mr(\frac{L}{mr^2})^2$$
    $$nAr^{n-1} = -mr\frac{L^2}{m^2r^4}$$
    $$r^{n+2} = -\frac{1}{n}\frac{L^2}{Am}$$
    הערך $\frac{L^2}{Am}$ תמיד חיובי, לכן על מנת שהצד הימיני של המשוואה יהיה חיובי $n$ צריך להיות שלילי ($n<0$), לא ניתן להוציא שורשים לערכים שלילים, וגם אם השורש אי זוגי וכן מתאפשר, פיזיקלית הרדיוס לא יכול להיות שלילי.  

    $$n=-1 (?)$$
5. להשלים
6. להשלים
7. **עשינו בכיתה**
8. להשלים
9. להשלים
