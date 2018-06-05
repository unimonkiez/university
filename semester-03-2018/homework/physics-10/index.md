<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# ש"ב פיזיקה - תרגיל 10
## יובל סרף
1. 
    1.  
        $$v_1 = v_0\hat{x}$$
        $$v_2 = 0$$
        $$v_{cm} = \frac{Mv_0\hat{x}}{M+M} = \frac{v_0}{2}\hat{x}$$
        $$|\vec{P_{1_{cm}}}| = |\vec{P'_{1_{cm}}}| \Rightarrow |\vec{v_{1_{cm}}}| = |\vec{v'_{1_{cm}}}|$$
        $$v_{1_{cm}} = \frac{v_0}{2}\hat{x}$$
        $$v_{2_{cm}} = -\frac{v_0}{2}\hat{x}$$
        $$v'_{1_{cm}} = \frac{v_0}{2}(\cos{\theta}\hat{x} + \sin{\theta}\hat{y})$$
        $$v'_{1} = \frac{v_0}{2}(\cos{\theta}\hat{x} + \sin{\theta}\hat{y}) + \frac{v_0}{2}\hat{x}$$
        $$v'_{1} = \frac{v_0}{2}((\cos{\theta} + 1)\hat{x} + \sin{\theta}\hat{y})$$
        $$v'_{2_{cm}} = -\frac{v_0}{2}(\cos{\theta}\hat{x} + \sin{\theta}\hat{y})$$
        $$v'_{2} = -\frac{v_0}{2}(\cos{\theta}\hat{x} + \sin{\theta}\hat{y})+ \frac{v_0}{2}\hat{x}$$
        $$v'_{2} = -\frac{v_0}{2}((\cos{\theta} - 1)\hat{x} + \sin{\theta}\hat{y})$$

    2.
        $$v'_{1}=v'_{2} = v'$$
        $$v'_{cm} = \frac{Mv'_{1} + Mv'_{2}}{M+M}$$
        $$v_{cm} = \frac{v_0}{2}\hat{x}$$
        $$v_{cm} = v'_{cm}$$
        $$\Downarrow$$
        $$\frac{Mv'_{1} + Mv'_{2}}{M+M} = \frac{v_0}{2}\hat{x}$$
        $$\frac{2v'}{2} = \frac{v_0}{2}\hat{x}$$
        $$v' = \frac{v_0}{2}\hat{x}$$
2.  צ"ל: $M=?$  

    $$E_{1_k} = \frac{1}{2}mv_0^2$$
    $$E'_{1_k} = E_{1_k}\cdot \frac{4}{9}$$
    $$\frac{1}{2}mv'^2_0 = \frac{1}{2}mv_0^2\cdot \frac{4}{9}$$
    $$v'^2_0 = v_0^2\cdot \frac{4}{9}$$
    $$v'_0 = \frac{2v_0}{3}$$
    שימור תנע:  
    
    $$mv_0 = mv'_0 + Mv_1$$
    $$mv_0 = m\frac{2v_0}{3} + Mv_1$$
    $$Mv_1 = mv_0(1-\frac{2}{3})$$
    $$v_1 = \frac{m}{M}\frac{v_0}{3}$$

    שימור אנרגיה:  
    
    $$\frac{1}{2}mv^2_0 = \frac{1}{2}mv'_0 + \frac{1}{2}Mv_1^2$$
    $$\Downarrow$$
    $$\frac{1}{2}mv^2_0 = \frac{1}{2}mv_0^2\cdot \frac{4}{9} + \frac{1}{2}M(\frac{m}{M}\frac{v_0}{3})^2$$
    $$\frac{1}{2}mv^2_0 = \frac{1}{2}mv_0^2\cdot \frac{4}{9} + \frac{1}{2}M\frac{m^2}{M^2}\frac{v_0^2}{9}$$
    $$\frac{1}{2}mv^2_0 = \frac{1}{2}mv_0^2\cdot \frac{4}{9} + \frac{1}{2}\frac{m^2}{M}\frac{v_0^2}{9}$$
    $$1 = \frac{4}{9} + \frac{m}{M}\frac{1}{9}$$
    $$\frac{5}{9} = \frac{m}{M}\frac{1}{9}$$
    $$\frac{m}{M}\frac{1}{9}=\frac{5}{9} $$
    $$\frac{m}{M}=5$$
3.
    שימור תנע:  

    $$P = m_1v_1 + m_2v_2 = m_1u_1 + m_2u_2 = P'$$
    $$v_{cm} = u_{cm} = v = \frac{m_1v_1+m_2v_2}{m_1+m_2}$$
    $$v_{1_{cm}} = v_1 - v_{cm}$$
    $$v_{1_{cm}} = \frac{m_2(v_1-v_2)}{m_1+m_2}$$
    $$v_{2_{cm}} = \frac{m_1(v_2-v_1)}{m_1+m_2}$$
    $$m_1v_{1_{cm}} + m_2v_{2_{cm}} = 0$$
    $$p_{1_{cm}}=-p_{2_{cm}}$$
4.
    $$E_{1_k}= \frac{1}{2}mv^2$$
    $$E_{2_k}=\frac{1}{2}3mu^2$$
    $$mv = 3mu$$
    $$u=\frac{v}{3}$$
    $$E_H=E_{1_k} - E_{2_k}$$
    $$\Downarrow$$
    $$E_H = \frac{1}{2}mv^2 - \frac{1}{2}3m(\frac{v}{3})^2$$
    $$E_H = \frac{1}{2}mv^2 - \frac{1}{2}3m\frac{v^2}{9}$$
    $$E_H = \frac{1}{2}mv^2 - \frac{1}{6}mv^2$$
    $$E_H = \frac{1}{3}mv^2$$
    $$\Downarrow$$
    $$_{lost}=\frac{E_H}{E_{1_k}}$$
    $$_{lost}=\frac{\frac{1}{3}mv^2}{\frac{1}{2}mv^2}$$
    $$_{lost}=\frac{\frac{1}{3}}{\frac{1}{2}}$$
    $$_{lost}=\frac{2}{3}$$
5.
    $$v_{cm} = \frac{M2v\hat{y}+Mv\hat{x}}{M+M}$$
    $$v_{cm} = \frac{2v\hat{y}+v\hat{x}}{2}$$
    $$v_{cm} = \frac{1}{2}v\hat{x} + v\hat{y}$$
    $$E_k = \frac{1}{2}2Mv_{cm}^2$$
    $$\Downarrow$$
    $$E_k = \frac{1}{2}2M(\frac{1}{2}v + v)^2$$
    $$E_k = M(\frac{3}{2}v)^2$$
    $$E_k = \frac{9Mv^2}{4}$$
6. עשינו בכיתה.
7. בלתי אפשרי.  
8. אין כוחות בציר $\hat{x}, \hat{z}$ מכיוון שהטיל שוגר למעלה, זאת אומרת התבצע שימור תנע בכיוונים אלו:  

    $$mv_{1_x} + mv_{2_x} + mv_{3_x} = 0$$
    $$mv_{1_z} + mv_{2_z} + mv_{3_z} = 0$$
    $$v_{1_x} + v_{2_x} + v_{3_x} = 0$$
    $$v_{1_z} + v_{2_z} + v_{3_z} = 0$$
    $$\Downarrow$$
    $$100 -10 + v_{3_x} = 0 \Rightarrow v_{3_x}=-90$$
    $$0 + 20 + v_{3_z} = 0 \Rightarrow v_{3_z}=-20$$
    כדי לחשב את המהירות בכיוון $\hat{y}$ נחשב את השינוי בתנע משיא הגובה עד לרגע ההתפוצצות:  

    $$P_y = 3mv_t\hat{y}$$
    $$v_t = 0$$
    $$P_y = 0$$
    $$P_{y_{\Delta t}} = 3mv_{y_{\Delta t}}\hat{y}$$
    $$\Delta P = P_{y_{\Delta t}} - P_y$$
    $$\Delta P = F \Delta t$$
    $$\Downarrow$$
    $$3mv_{y_{\Delta t}}\hat{y} = 3mg\Delta t$$
    $$v_{y_{\Delta t}} = g\Delta t\hat{y}$$
    $$v_{y_{\Delta t}} = 4.9\hat{y}$$
    $$v_{1_y} + v_{2_y} + v_{3_y} = 3\cdot 4.9$$
    $$0 + 30 + v_{3_y} = 3\cdot 4.9$$
    $$v_{3_y} = -15.3$$
    $$\Downarrow$$
    $$v_3 = -90\hat{x}-15.3\hat{x}-20\hat{x}$$
9. עשינו בכיתה
10.
    $$\vec{v_1} = -\vec{v_2} = v$$
    $$v_{cm} = \frac{m_1\vec{v_1}+m_2\vec{v_2}}{m_1+m_2}$$
    $$v_{cm} = \frac{m_1\vec{v}-m_2\vec{v}}{m_1+m_2}$$
    $$v_{cm} = \frac{\vec{v}(m_1-m_2)}{m_1+m_2}$$
    $$v_{1_{cm}} = \vec{v} - \frac{\vec{v}(m_1-m_2)}{m_1+m_2}$$
    $$v_{1_{cm}} = \frac{\vec{v}(m_1+m_2-m_1+m_2)}{m_1+m_2}$$
    $$v_{1_{cm}} = \frac{2\vec{v}m_2}{m_1+m_2}$$
    $$v_{2_{cm}} = -\vec{v} - \frac{\vec{v}(m_1-m_2)}{m_1+m_2}$$
    $$v_{2_{cm}} = \frac{-2\vec{v}m_1}{m_1+m_2}$$
    $$|\vec{P_{1_{cm}}}| = |\vec{P'_{1_{cm}}}| \Rightarrow |\vec{v_{1_{cm}}}| = |\vec{v'_{1_{cm}}}|$$
    $$\Downarrow$$
    $$v'_{1_{cm}} = \frac{2vm_2}{m_1+m_2}(\cos{\theta}\hat{x} + \sin{\theta}\hat{y})$$
    $$v'_{1} = v'_{1_{cm}} + v_{cm}$$
    $$v'_{1} = \frac{2vm_2}{m_1+m_2}(\cos{\theta}\hat{x} + \sin{\theta}\hat{y}) + \frac{v(m_1-m_2)}{m_1+m_2}(\hat{x}+\hat{y})$$
    $$v'_{1} = \frac{v}{m_1+m_2}(2m_2(\cos{\theta}\hat{x} + \sin{\theta}\hat{y}) + (m_1-m_2)(\hat{x}+\hat{y}))$$
    $$v'_{1} = \frac{v}{m_1+m_2}((m_2(2\cos{\theta}-1)+m_1)\hat{x} + (m_2(2\sin{\theta}-1)+m_1)\hat{y})$$
    $$\Downarrow$$
    $$v'_{2} = \frac{-v}{m_1+m_2}((m_1(2\cos{\theta}+1)+m_2)\hat{x} + (m_1(2\sin{\theta}+1)+m_2)\hat{y})$$