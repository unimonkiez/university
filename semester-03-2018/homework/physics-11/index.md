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
    $$\vec{L_1} = \vec{L_0}$$
    $$E_1 = E_0$$
    $$\Downarrow$$
    $$1. \ \ \ mr_1v_1 = mRv_0\sin{\alpha}$$
    $$2. \ \ \ \frac{1}{2}mv_1^2 - \frac{GMm}{r_1} = \frac{1}{2}mv_0^2-\frac{GMm}{R}$$
    $$1. \ \ \ r_1v_1 = Rv_0\sin{\alpha}$$
    $$1. \ \ \ v_1 = \frac{Rv_0\sin{\alpha}}{r_1}$$
    $$2. \ \ \ v_1^2 - \frac{2GM}{r_1} = v_0^2-\frac{2GM}{R}$$
    $$v_1 = \frac{Rv_0\sin{\alpha}}{r_1} \Downarrow$$
    $$\frac{R^2v_0^2\sin^2{\alpha}}{r_1^2} - \frac{2GM}{r_1} = v_0^2-\frac{2GM}{R}$$
    $$\frac{R^2v_0^2\sin^2{\alpha}}{r_1^2} - v_0^2=\frac{2GM}{r_1}-\frac{2GM}{R}$$
    $$v_0^2(\frac{R^2\sin^2{\alpha}}{r_1^2} - 1)=2GM(\frac{1}{r_1}-\frac{1}{R})$$
    $$v_0 = (\frac{GM}{R})^{\frac{1}{2}} \Downarrow$$
    $$\frac{GM}{R}(\frac{R^2\sin^2{\alpha}}{r_1^2} - 1)=2GM(\frac{1}{r_1}-\frac{1}{R})$$
    $$\frac{R\sin^2{\alpha}}{r_1^2} -\frac{1}{R}=\frac{2}{r_1}-\frac{2}{R}$$
    $$\frac{R\sin^2{\alpha}}{r_1^2} +\frac{1}{R}-\frac{2}{r_1}=0$$
    $$x = \frac{1}{r_1} \Downarrow$$
    $$R\sin^2{\alpha}x^2-2x +\frac{1}{R}=0$$
    $$x_{1,2} = \frac{2\pm\sqrt[]{4-4\sin^2{\alpha}}}{2R\sin^2{\alpha}}$$
    $$x_{1,2} = \frac{2\pm\sqrt[]{4(1-\sin^2{\alpha})}}{2R\sin^2{\alpha}}$$
    $$x_{1,2} = \frac{2\pm\sqrt[]{4\cos^2{\alpha}}}{2R\sin^2{\alpha}}$$
    $$x_{1,2} = \frac{2\pm2\cos{\alpha}}{2R\sin^2{\alpha}}$$
    $$x_{1,2} = \frac{1\pm\cos{\alpha}}{R\sin^2{\alpha}}$$
    $$r_1 = \frac{1}{x} \Downarrow$$
    $$r_{1_{1,2}} = \frac{R\sin^2{\alpha}}{1\pm\cos{\alpha}}$$
    נבטל את הפיתרון עבורו $r_1 < R$  

    $$r_1 = \frac{R\sin^2{\alpha}}{1-\cos{\alpha}}$$
    נבדוק את הפתרון עבור $\alpha=60\degree$  

    $$\alpha=60\degree \Rightarrow \cos{\alpha} = 0.5, \sin^2{\alpha} = 0.75 \Downarrow$$
    $$r_1 = \frac{0.75R}{1-0.5} = \frac{3}{2}R$$
7. **עשינו בכיתה**
8. 
    1.
        $$\vec{F} = \frac{kq_1q_2}{r^2}\hat{r}$$
        $$E_{pot} - 0 = \int^{\infty}_r (\vec{F}) \delta r$$
        $$E_{pot} = \int^{\infty}_r (\frac{kq_1q_2}{r^2}) \delta r$$
        $$E_{pot} = -(\frac{kq_1q_2}{r})|^{\infty}_r$$
        $$E_{pot} = -\frac{kq_1q_2}{r}$$
    2.
        מכיוון ש-$\vec{r}, \vec{F}$ מקבילים, זאת אומרת ש-
        
        $$\dot{\vec{L}} = \vec{r}\times \vec{F} = 0$$
        $$\Downarrow$$
        $$\vec{L} = cosnt = \vec{r}\times \vec{v}$$

        וקטור התנע הזוויתי מאונך למישור שמוגדר ע"י $\vec{r},\vec{v}$ ומכיוון שהוא עצמו קבוע, גם מישור זה קבוע
    3.
        $$\vec{L} = mr^2\dot{\theta}\hat{z}$$
        $$|L| = mr^2\dot{\theta}$$
        $$\dot{\theta} = \frac{|L|}{mr^2}$$
    4.
        $$E_{(t=0)} = E_0$$
        $$L_{(t=0)} = L_E$$
        $$\Downarrow$$
        $$E_{(t)} = \frac{1}{2}m\dot{r}^2 + \frac{L^2}{2mr^2}-\frac{kq_1q_2}{r}$$
        כאשר מרחק מקסימלי\מינימלי אז $\dot{r} = 0$

        $$\Downarrow$$
        $$E_{(min, max)} = \frac{L^2}{2mr^2}-\frac{kq_1q_2}{r}$$
        שימור אנרגיה וגם תנע זווויתי, לכן: 
        
        $$E_0 = \frac{L_0^2}{2mr^2}-\frac{kq_1q_2}{r}$$
        $$x = \frac{1}{r}$$
        $$E_0 = \frac{L_0^2}{2m}x^2-kq_1q_2x$$
        $$\frac{L_0^2}{2m}x^2-kq_1q_2x-E_0=0$$
        $$x_{1,2} = \frac{kq_1q_2\pm\sqrt[]{(kq_1q_2)^2-\frac{4E_0L_0^2}{2m}}}{\frac{L_0^2}{2m}}$$
        $$x_{1,2} = \frac{kq_1q_2\pm\sqrt[]{(kq_1q_2)^2-\frac{2E_0L_0^2}{m}}}{\frac{L_0^2}{2m}}$$
        $$x_{1,2} = \frac{2mkq_1q_2\pm\sqrt[]{(2mkq_1q_2)^2-8mE_0L_0^2}}{L_0^2}$$
        $$r=\frac{1}{x} \Downarrow$$
        $$r_{1,2} = \frac{L_0^2}{2mkq_1q_2\pm\sqrt[]{(2mkq_1q_2)^2-8mE_0L_0^2}}$$
9. 
    1.
        $$\vec{L} = \vec{r}\times \vec{p}$$
        $$\vec{L} = \vec{r}\times m\vec{v}$$
        $$\vec{r} = v_0\cos{\theta_0}t\hat{x} + (v_0\cos{\theta_0}t-\frac{1}{2}gt^2)\hat{y}$$
        $$\vec{v} = v_0\cos{\theta_0}\hat{x} + (v_0\cos{\theta_0}-gt)\hat{y}$$
        $$\Downarrow$$
        $$\vec{L} = m(\cancel{v_0^2\cos{\theta_0}\cos{\theta_0}}-gv_0\cos{\theta_0}t^2-\cancel{v_0^2\cos{\theta_0}\cos{\theta_0}}+\frac{1}{2}gv_0\cos{\theta_0}t^2)\hat{z}$$
        $$\vec{L} = m(\frac{1}{2}gv_0\cos{\theta_0}t^2-gv_0\cos{\theta_0}t^2)\hat{z}$$
        $$\vec{L} = -\frac{m}{2}gv_0\cos{\theta_0}t^2\hat{z}$$
    2.
        $$\vec{\tau} = \frac{\delta \vec{L}}{\delta t}$$
        $$\vec{\tau} = -mgv_0\cos{\theta_0}t\hat{z}$$
        
