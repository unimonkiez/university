<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# ש"ב פיזיקה - תרגיל 2
## יובל סרף

1.  נתון

    $$x_0 = 0$$
    $$v_{x0} = v_0 \cos{(\theta)}$$
    $$y_0 = 0$$
    $$v_{y0} = v_0 \sin{(\theta)}$$
    $$a_x=0$$
    $$a_y=-g$$
    העתק בתאוצה קבועה:  
    $\ddot{x_{(t)}} = b$  
    $x_{(t)}= \frac{1}{2}bt^2 + v_0t + x_{o}$

    1. נציב בנוסחאת התאוצה הקבוצה:  
    
    $$x_{(t)} = v_0\cos{(\theta)}t$$
    $$y_{(t)} = v_0\sin{(\theta)}t-\frac{1}{2}gt^2$$
    2.  

    $$y_{(x)}=v_0\sin{(\theta)}\frac{x}{v_0\cos{(\theta)}}-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\theta)}}$$
    $$y_{(x)}=\tan{(\theta)}x-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\theta)}}$$
    3.  נמצא את נקודת הקיצון של הנגזרת של $y_{(t)}$

    $$y_{(t)} = v_0\sin{(\theta)}t-\frac{1}{2}gt^2$$
    $$\dot{y_{(t)}} = v_0\sin{(\theta)}-gt$$
    $$v_0\sin{(\theta)}-gt=0$$
    $$gt=v_0\sin{(\theta)}$$
    $$t=\frac{v_0\sin{(\theta)}}{g}$$
    גובה מקסימלי:  

    $$y = v_0\sin{(\theta)}\frac{v_0\sin{(\theta)}}{g}-\frac{1}{2}g(\frac{v_0\sin{(\theta)}}{g})^2$$
    $$y = \frac{v_0^2\sin^2{(\theta)}}{g}-\frac{1}{2}g\frac{v_0^2\sin^2{(\theta)}}{g^2}$$
    $$y = \frac{v_0^2\sin^2{(\theta)}}{g}-\frac{1}{2}\frac{v_0^2\sin^2{(\theta)}}{g}$$
    $$y = \frac{v_0^2\sin^2{(\theta)}}{2g}$$
    מרחק מקסימלי:  

    $$x = v_0\cos{(\theta)}\frac{v_0\sin{(\theta)}}{g}$$
    $$x = \frac{v_0^2\sin{(\theta)}\cos{(\theta)}}{g}$$

    4.  הנקודה בה $y_{(x)}=0$


    $$y_{(x)}=\tan{(\theta)}x-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\theta)}}$$
    $$\tan{(\theta)}x-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\theta)}}=0$$
    $$\frac{\sin{(\theta)}x}{\cos{(\theta)}}-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\theta)}}=0$$
    $$\frac{\sin{(\theta)}x}{\cos{(\theta)}}-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\theta)}}=0$$
    $$\sin{(\theta)}x-\frac{gx^2}{2v_0^2\cos{(\theta)}}=0$$
    $$\frac{\sin{(\theta)}x(2v_0^2\cos{(\theta)})-gx^2}{2v_0^2\cos{(\theta)}}=0$$
    $$\frac{x((2v_0^2\sin{(\theta)}\cos{(\theta)})-gx)}{2v_0^2\cos{(\theta)}}=0$$
    נגיעה ראשונה כש $x=0$, שזו נקודת ההתחלה, נקודה שנייה כש:  
    
    $$(2v_0^2\sin{(\theta)}\cos{(\theta)})-gx = 0$$
    $$gx= 2v_0^2\sin{(\theta)}\cos{(\theta)}$$
    $$x= \frac{2v_0^2\sin{(\theta)}\cos{(\theta)}}{g}$$
    $$x= \frac{v_0^2\sin{(2\theta)}}{g}$$

    5. על מנת למצוא $\theta$ שיתן $x$ מקסימלי, נגזור את $x_{(\theta)}$
    
    $$x_{(\theta)}=\frac{\sin{(2\theta)}v_0^2}{g}$$
    $$\dot{x_{(\theta)}}=\frac{2\cos{(2\theta)}v_0^2}{g}$$
    $$\frac{2\cos{(2\theta)}v_0^2}{g}=0$$
    $$2\theta=\frac{\pi}{2}+n\pi$$
    $$\theta=\frac{\pi}{4}+\frac{n\pi}{2}$$
    $$\theta=45\degree$$

2.  נתון

    $$x_0 = 0$$
    $$v_{x0} = v_0 \cos{(\alpha)}$$
    $$y_0 = 0$$
    $$v_{y0} = v_0 \sin{(\alpha)}$$
    $$a_x=0$$
    $$a_y=-g$$
    $$x_{(t)} = v_0\cos{(\alpha)}t$$
    $$y_{(t)} = v_0\sin{(\alpha)}t-\frac{1}{2}gt^2$$
    $$y_{(x)}=\tan{(\alpha)}x-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\alpha)}}$$
    נמצא את פונקציית המהירות ההתחלתית ($fv_0$)

    $$y=\tan{(\alpha)}x-\frac{gx^2}{2v_0^2\cos^2{(\alpha)}}$$
    $$\frac{gx^2}{2v_0^2\cos^2{(\alpha)}}=\tan{(\alpha)}x-y$$
    $$2v_0^2\cos^2{(\alpha)}=\frac{gx^2}{\tan{(\alpha)}x-y}$$
    $$v_0^2=\frac{gx^2}{2\cos^2{(\alpha)}(\tan{(\alpha)}x-y)}$$
    $$v_0^2=\frac{gx^2}{\sin{(2\alpha)}x-2\cos^2{(\alpha)}y}$$
    $$v_0=\sqrt{\frac{gx^2}{\sin{(2\alpha)}x-2\cos^2{(\alpha)}y}}$$
    נציב $x=L$, $y=-h$ (כי מדדנו את ציר Y לכיוון למעלה)


    $$v_0=\sqrt{\frac{gL^2}{\sin{(2\alpha)}L+2\cos^2{(\alpha)}h}}$$

3. עשינו בכיתה
4. נתון

    $$a=-kv+F$$

    1.  

    $$\dot{v} = -kv+\frac{F}{m}$$

    2.  $U=v-\frac{F}{km}$  

    $$\Downarrow$$
    $$v=U+\frac{F}{km}$$
    $$\dot{U} = -k(U+\frac{F}{km})+\frac{F}{m}$$
    $$\dot{U} = -kU\cancel{-\frac{F}{m}}\cancel{+\frac{F}{m}}$$
    $$\dot{U} = -kU$$

    3.  $U=A e^{-Bt}$  

    $$U=A e^{-Bt}$$
    $$\dot{U}=-BA e^{-Bt}$$
    $$\Downarrow$$
    $$-BA e^{-Bt}=-k(A e^{-Bt})$$
    $$B=\frac{k(A e^{-Bt})}{A e^{-Bt}}$$
    $$B=k$$
    4. $v_{0(t=0)} = 0$  
    
    $$U_{(t)}=A e^{-Bt}$$
    $$t=0$$
    $$\Downarrow$$
    $$U_{(t=0)}=A$$
    $$v_0=0$$
    $$U_{(v)}=v-\frac{F}{km}$$
    $$\Downarrow$$
    $$0-\frac{F}{km}=A$$
    $$A=-\frac{F}{km}$$

    5.  

    $$U_{(t)}=A e^{-Bt}$$
    $$U_{(v)}=v-\frac{F}{km}$$
    $$\Downarrow$$
    $$v_{(t)}=A e^{-Bt}+\frac{F}{km}$$
    $$x_{(t)}=\int v_{(t)}$$
    $$x_{(t)}=\frac{A e^{-Bt}}{-B}+\frac{F}{km}t+x_0$$

    נתון: $t=0 \rightarrow x=0$  
    
    $$0=\frac{A e^{-B 0}}{-B}+\frac{F}{km}0+x_0$$
    $$0=-\frac{A}{B}+x_0$$
    $$x_0=\frac{A}{B}$$
    6.  
    
5.  רשות
6.  
    1. $\vec{X}_{(t)}=bt\hat{x}-ct^2\hat{y}$
    
    $$\dot{\vec{X}_{(t)}}=\vec{V}_{(t)}$$
    $$\vec{V}_{(t)}=b\hat{x}-2ct\hat{y}$$
    $$\dot{\vec{V}_{(t)}}=\vec{A}_{(t)}$$
    $$\vec{A}_{(t)}=-2c\hat{y}$$

    2.  
    $$\vec{X}_{(t)}=bt\hat{x}+\alpha \cos{(\omega t)}\hat{y}$$
    $$\dot{\vec{X}_{(t)}}=\vec{V}_{(t)}$$
    $$\vec{V}_{(t)}=b\hat{x}-\omega \alpha \sin{(\omega t)}\hat{y}$$
    $$\dot{\vec{V}_{(t)}}=\vec{A}_{(t)}$$
    $$\vec{A}_{(t)}=-\omega^2 \alpha \cos{(\omega t)}\hat{y}$$

    3.  

    $$\vec{X}_{(t)}=\alpha\cos{(ct^2)}\hat{x}+b\sin{(ct^2)}\hat{y}$$
    $$\dot{\vec{X}_{(t)}}=\vec{V}_{(t)}$$
    $$\Downarrow$$
    $$\vec{V}_{(t)}=-2ct \alpha \sin{(ct^2)}\hat{x} + 2ctb\cos{(ct^2)}\hat{y}$$

    $$\dot{\vec{V}_{(t)}}=\vec{A}_{(t)}$$
    $$\Downarrow$$
    $$\vec{A}_{(t)}=(-2c \alpha \sin{(ct^2)} -4c^2t^2 \alpha \cos{(ct^2)})\hat{x} +(2cb\cos{(ct^2)} - 4c^2t^2b\sin{(ct^2)})\hat{y}$$
    $$\vec{A}_{(t)}=2c((- \alpha \sin{(ct^2)} -2ct^2 \alpha \cos{(ct^2)})\hat{x} +(b\cos{(ct^2)} - 2ct^2b\sin{(ct^2)})\hat{y})$$

7.  
    1. $\dot{\overline{(\vec{A}+\vec{B})}} = \dot{\vec{A}} + \dot{\vec{B}}$  
    
    $$\dot{\overline{(\vec{A}+\vec{B})}} = \dot{\overline{(A_x+B_x)\hat{x} + (A_y+B_y)\hat{y} + (A_z+B_z)\hat{z}}}$$
    $$\dot{\overline{(\vec{A}+\vec{B})}} = \dot{\overline{A_x\hat{x} + A_y\hat{y} + A_z\hat{z} + B_x\hat{x} + B_y\hat{y} + B_z\hat{z}}}$$
    $$\dot{\overline{(\vec{A}+\vec{B})}} = \dot{\overline{A_x\hat{x} + A_y\hat{y} + A_z\hat{z}}} + \dot{\overline{B_x\hat{x} + B_y\hat{y} + B_z\hat{z}}}$$
    $$\Downarrow$$
    $$\dot{\overline{(\vec{A}+\vec{B})}} = \dot{\vec{A}} + \dot{\vec{B}}$$

    2. עשינו בכיתה
    3.  $\dot{\overline{(\vec{A}\cdot \vec{B})}} = \dot{\vec{A}} \cdot \vec{B} + \vec{A} \cdot \dot{\vec{B}}$

    $$\dot{\overline{(\vec{A}\cdot \vec{B})}} = \dot{\overline{(A_xB_x + A_yB_y + A_zB_z)}}$$
    $$\dot{\overline{(\vec{A}\cdot \vec{B})}} = \dot{\overline{A_xB_x}} + \dot{\overline{A_yB_y}} + \dot{\overline{A_zB_z}}$$
    $$\dot{\overline{(\vec{A}\cdot \vec{B})}} = \dot{A_x}B_x + \dot{B_x}A_x + \dot{A_y}B_y + \dot{B_y}A_y + \dot{A_z}B_z + \dot{B_z}A_z$$
    $$\dot{\overline{(\vec{A}\cdot \vec{B})}} = (\dot{A_x}B_x + \dot{A_y}B_y + \dot{A_z}B_z) + (\dot{B_x}A_x + \dot{B_y}A_y + \dot{B_z}A_z)$$
    $$\Downarrow$$
    $$\dot{\overline{(\vec{A}\cdot \vec{B})}} = \dot{\vec{A}} \cdot \vec{B} + \vec{A} \cdot \dot{\vec{B}}$$
    4. אחר כך

8. עשינו בכיתה
9.  נתון:  

    $$x_0 = 0$$
    $$v_{x0} = v_0 \cos{(\alpha)}$$
    $$y_0 = 0$$
    $$v_{y0} = v_0 \sin{(\alpha)}$$
    $$a_x=0$$
    $$a_y=-g$$
    העתק בתאוצה קבועה:  
    $\ddot{x_{(t)}} = b$  
    $x_{(t)}= \frac{1}{2}bt^2 + v_0t + x_{o}$

    1. נציב בנוסחאת התאוצה הקבוצה:  
    
    $$x_{(t)} = v_0\cos{(\alpha)}t$$
    $$y_{(t)} = v_0\sin{(\alpha)}t-\frac{1}{2}gt^2$$
    $$y_{(x)}=v_0\sin{(\alpha)}\frac{x}{v_0\cos{(\alpha)}}-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\alpha)}}$$
    $$y_{(x)}=\tan{(\alpha)}x-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\alpha)}}$$

    2.  פונקציית גובה למרחק עבור השיפוע (נתון שיפוע ישר m)  

    $$y_{(x)} = mx$$

    הנקודה בה $y_{(x)}=mx$


    $$y_{(x)}=\tan{(\alpha)}x-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\alpha)}}=mx$$
    $$\tan{(\alpha)}x-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\alpha)}}=mx$$
    $$\frac{\sin{(\alpha)}x}{\cos{(\alpha)}}-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\alpha)}}=mx$$
    $$\frac{\sin{(\alpha)}x}{\cos{(\alpha)}}-\frac{1}{2}g\frac{x^2}{v_0^2\cos^2{(\alpha)}}=mx$$
    $$\sin{(\alpha)}x-\frac{gx^2}{2v_0^2\cos{(\alpha)}}=mx\cos{(\alpha)}$$
    $$\frac{\sin{(\alpha)}x(2v_0^2\cos{(\alpha)})-gx^2}{2v_0^2\cos{(\alpha)}}=mx\cos{(\alpha)}$$
    $$\frac{x((2v_0^2\sin{(\alpha)}\cos{(\alpha)})-gx)}{2v_0^2\cos{(\alpha)}}=mx\cos{(\alpha)}$$
    נגיעה ראשונה כש $x=0$, שזו נקודת ההתחלה, נקודה שנייה כש:  
    
    $$\frac{(2v_0^2\sin{(\alpha)}\cos{(\alpha)})-gx}{2v_0^2\cos{(\alpha)}}= m\cos{(\alpha)}$$
    $$\frac{gx}{2v_0^2\cos{(\alpha)}}=\frac{(2v_0^2\sin{(\alpha)}\cos{(\alpha)})-m(2v_0^2\cos^2{(\alpha)})}{2v_0^2\cos{(\alpha)}}$$
    $$gx=(2v_0^2\sin{(\alpha)}\cos{(\alpha)})-m(2v_0^2\cos^2{(\alpha)})$$
    $$gx=2v_0^2\cos{\alpha}(\sin{\alpha}-m\cos{(\alpha)})$$
    $$x=\frac{2v_0^2\cos{\alpha}(\sin{\alpha}-m\cos{(\alpha)})}{g}$$

    על מנת למצוא $\alpha$ שיתן $x$ מקסימלי, נגזור את $x_{(\alpha)}$
    
    $$x_{(\alpha)}=\frac{2v_0^2\cos{\alpha}(\sin{\alpha}-m\cos{(\alpha)})}{g}$$
    $$x_{(\alpha)}=\frac{2v_0^2(\sin{\alpha}\cos{\alpha}-m\cos^2{\alpha})}{g}$$
    $$\dot{x_{(\alpha)}}=\frac{2v_0^2(\cos^2{\alpha}-\sin^2{\alpha}+2m\cos{(\alpha)}\sin{\alpha})}{g}$$
    $$\dot{x_{(\alpha)}}=\frac{2v_0^2(1-2\sin^2{\alpha}+2m\cos{(\alpha)}\sin{(\alpha)})}{g}$$
    $$\dot{x_{(\alpha)}}=\frac{2v_0^2(1-2\sin^2{\alpha}+m\sin{(2\alpha)})}{g}$$

    נמצא נקודת קיצון:  


    $$\frac{2v_0^2(1-2\sin^2{\alpha}+m\sin{2\alpha})}{g}=0$$

    
    $$1-2\sin^2{\alpha}+m\sin{2\alpha}=0$$

    $$\alpha=\frac{\pi}{4}+\frac{n\pi}{2}$$
    $$\alpha=45\degree$$