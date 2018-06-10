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
        $$\vec{r} = r\hat{r} + 0\hat{\theta} + 0\hat{z}$$
        $$\vec{F} = m(\ddot{r} - r\dot{\theta}^2)\hat{r} + m(2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta} + 0\hat{z}$$
        $$\vec{\tau} = \frac{\delta \vec{L}}{\delta t} = \vec{r} \otimes \vec{F}$$
        $$\Downarrow$$
        $$\frac{\delta \vec{L}}{\delta t} =
        (0 \cdot 0 - 0 \cdot m(2\dot{r}\dot{\theta} + r\ddot{\theta}))\hat{r} +
        (r \cdot 0 - 0 \cdot m(\ddot{r} - r\dot{\theta}^2))\hat{\theta} +
        (r\cdot m(2\dot{r}\dot{\theta} + r\ddot{\theta}) - 0\cdot m(\ddot{r} - r\dot{\theta}^2))\hat{z}
        $$
        $$\frac{\delta \vec{L}}{\delta t} = (r\cdot m(2\dot{r}\dot{\theta} + r\ddot{\theta}))\hat{z}$$
        $$\frac{\delta \vec{L}}{\delta t} = (2mr\dot{r}\dot{\theta} + mr^2\ddot{\theta})\hat{z}$$
    2. צ"ל: $a_{\theta} = 0$  
        כוח מרכזי בכיוון המרכז, ז"א:
        
        $$\vec{F} = x_{(r)}\hat{r}$$
        $$F = m\vec{a}$$
        $$\Downarrow$$
        $$\vec{a} = \frac{1}{m}x_{(r)}\hat{r}$$
        $$a_{\theta} = 0$$
    3.  הוכחנו כי $a_{\theta} = 0$ בכוח משמר, לכן:  
    
        $$\dot{\vec{L}} = mra_{\theta} = 0$$
        $$\vec{L} = \int 0 \cdot \delta x$$
        $$\vec{L} = c$$
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
5. 
    1.
        $$U_{eff(r)} = \frac{L^2}{2mr^2}-\frac{GMm}{r}$$
        $$\Downarrow$$
        $$E = E_{k}+\frac{L^2}{2mr^2}-\frac{GMm}{r}$$
        $$E_{max,min} = E_{k} = 0$$
        $$E(r = r_{<}) = E(r = r_{>})$$
        $$\Downarrow$$
        $$\frac{L^2}{2mr_{<}^2}-\frac{GMm}{r_{<}} = \frac{L^2}{2mr_{>}^2}-\frac{GMm}{r_{>}}$$
        $$\frac{L^2}{2mr_{<}^2}-\frac{L^2}{2mr_{>}^2}=\frac{GMm}{r_{<}}-\frac{GMm}{r_{>}}$$
        $$L^2\frac{1}{2m}(\frac{1}{r_{<}^2}-\frac{1}{r_{>}^2})=GMm(\frac{1}{r_{<}}-\frac{1}{r_{>}})$$
        $$L^2\frac{1}{2m}(\frac{1}{r_{<}}+\frac{1}{r_{>}})\cancel{(\frac{1}{r_{<}}-\frac{1}{r_{>}})}=GMm\cancel{(\frac{1}{r_{<}}-\frac{1}{r_{>}})}$$
        $$L^2\frac{1}{2m}(\frac{1}{r_{<}}+\frac{1}{r_{>}})=GMm$$
        $$L^2(\frac{r_{<}+r_{>}}{r_{<}r_{>}})=2GMm^2$$
        $$L^2=\frac{2GMm^2r_{<}r_{>}}{r_{<}+r_{>}}$$
    2.
        $$r = r_{<} = r_{>}$$
        $$\Downarrow$$
        $$L^2=\frac{2GMm^2r^2}{2r}$$
        $$L^2=GMm^2r$$
        $$L=\sqrt[]{GMm^2r}$$
    3.

6. 
    $$v_0 = (\frac{GM_e}{R_e})^{\frac{1}{2}}$$
    $$E = E_k +U_{eff}$$
    $$E = E_{t=0} = E_{t_0}$$
    $$\Downarrow$$
    $$\frac{1}{2}mv_0^2-\frac{GMm}{R_e}= 0-\frac{GMm}{R_e + h}$$
    $$v_0^2-\frac{2GM}{R_e}=-\frac{2GM}{R_e + h}$$
    $$v_0^2=\frac{2GM(R_e + h)-2GMR_e}{R_e(R_e + h)}$$
    $$v_0^2=\frac{2GM((R_e + h)-R_e)}{R_e(R_e + h)}$$
    $$v_0^2=\frac{2GMh}{R_e(R_e + h)}$$
    $$v_0^2R_e(R_e + h)=2GMh$$
    $$v_0^2R_e^2 + v_0^2R_eh=2GMh$$
    $$2GMh-v_0^2R_eh=v_0^2R_e^2$$
    $$h(2GM-v_0^2R_e)=v_0^2R_e^2$$
    $$h=\frac{v_0^2R_e^2}{2GM-v_0^2R_e}$$
    $$\Downarrow$$
    $$h=\frac{v_0^2R_e^2}{2GM-v_0^2R_e}$$
    $$v_{r_0} = v_0 \cdot \cos{\alpha}$$
    $$\Downarrow$$
    $$h=\frac{(\frac{GM_e}{R_e})\cos^2{\alpha}R_e^2}{2GM-(\frac{GM_e}{R_e})\cos^2{\alpha}R_e}$$
    $$h=\frac{(GM_e)\cos^2{\alpha}R_e}{2GM-(GM_e)\cos^2{\alpha}}$$
    $$h=\frac{(GM_e)\cos^2{\alpha}R_e}{GM(2-\cos^2{\alpha})}$$
    $$h=\frac{\cos^2{\alpha}R_e}{2-\cos^2{\alpha}}$$
    $$\alpha=60\deg \rightarrow \cos{\alpha} = 0.5 \Downarrow$$
    $$h=\frac{0.25R_e}{2-0.25} = \frac{R_e}{7}$$
7. **עשינו בכיתה**
8. להשלים
9. להשלים
