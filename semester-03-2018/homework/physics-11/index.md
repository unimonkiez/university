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
1. 
    $$\dot{r} = v_0$$
    $$\ddot{r} = 0_\frac{m}{s^2}$$
    $$\frac{\delta u_{(r)}}{\delta r} = -\overline{F}_{(r)}$$
    $$E = \frac{1}{2}m(\dot{r}^2 + (r\dot{\theta})) + u_{(r)}$$
    $$\Downarrow$$
    $$E = \frac{1}{2}m\dot{r}^2 + \frac{1}{2}\frac{L^2}{r^2m} + u_{(r)}$$
    $$\frac{\delta E}{\delta t} = 0$$
    $$\frac{\delta E}{\delta t} = m\dot{r}\ddot{r} + \frac{1}{2}\frac{L^2}{m}\frac{-2}{r^3} + \frac{\delta u_{(r)}}{\delta t}$$
    $$\frac{\delta E}{\delta t} = \cancel{m\dot{r}\ddot{r}} + \frac{1}{2}\frac{L^2}{m}\frac{-2}{r^3} + \frac{-A}{r^3}$$
    $$\frac{A}{r^3} = $$
2. **להשלים**
3.  
    1. צ"ל $u_{(r)} = ?$

        $$u_{(r)} = -\int F\delta r$$
        $$u_{(r)} = \int kr^4\delta r$$
        $$u_{(r)} = \frac{1}{5}kr^5 + c$$

    2. צ"ל $u_{eff(r)} = ?$

        $$E = \frac{1}{2}m\dot{r}^2 + \frac{1}{2}mr^2(\frac{L}{mr^2})^2 + \frac{kr^5}{5} + c$$
        $$u_{eff(r)} = \frac{1}{2}mr^2(\frac{L}{mr^2})^2 + \frac{kr^5}{5} + c$$
    3.
        $$\dot{r} = 0$$
        $$-kr^4 = m(\ddot{r}-r\dot{\theta}^2)$$
        $$-kr^4 = m(-r\dot{\theta}^2)$$
        $$-kr^4 = -mr(\dot{\theta})^2$$
        $$-kr^4 = -mr(\frac{L}{mr^2})^2$$
        $$r=\sqrt[7]{\frac{L^2}{km}}$$

        בשביל האנרגיה יש פשוט להציב פה:  
        
        $$E = \frac{1}{2}m\dot{r}^2 + \frac{1}{2}mr^2(\frac{L}{mr^2})^2 + \frac{kr^5}{5} + c$$
    4.
        $$E_{(\dot{r} = 0)} = \frac{1}{2}\frac{L^2}{mr^2} + \frac{kr^5}{5} + c$$
        $$\frac{1}{2}\frac{L^2}{mr_0^2} + \frac{kr_0^5}{5} + c = \frac{1}{2}\frac{L^2}{m3^2r_0^2} + \frac{k3^5r_0^5}{5} + c$$
        $$r_0=...$$

    5.  
        בשביל האנרגיה יש פשוט להציב את $r_0$ פה:  
        
        $$E = \frac{1}{2}m\dot{r}^2 + \frac{1}{2}mr^2(\frac{L}{mr^2})^2 + \frac{kr^5}{5} + c$$
4. **להשלים**
5. **להשלים**
6. **להשלים**
7.
    1. צל: $\omega=?, v=?, r=?$  
    משיקולי אנרגיה:  

    $$u=E_0=\frac{1}{2}m\dot{r}^2+\frac{1}{2}m(r\dot{\theta})^2+\frac{1}{2}kr^2$$
    $$\dot{r} = 0 \Downarrow$$
    $$E_0=\frac{1}{2}m(r\dot{\theta})^2+\frac{1}{2}kr^2$$
    $$\dot{\theta} = \omega \Downarrow$$
    $$E_0=\frac{1}{2}m(r\omega)^2+\frac{1}{2}kr^2$$
    משיקולי כוחות:  

    $$ma_r = m(\ddot{r}-r\dot{\theta}^2) = -kr$$
    $$\ddot{r} = 0, \dot{\theta}=\omega \Downarrow$$
    $$m(-r\omega^2) = -kr$$
    $$\omega = \sqrt[]{\frac{k}{m}}$$
    נציב במשוואת האנרגיה:  
    
    $$E_0=\frac{1}{2}m(r\omega)^2+\frac{1}{2}kr^2$$
    $$ר = \sqrt[]{\frac{E_0}{ל}}$$

    $$v = r\dot{\theta}$$
    $$v = r\omega$$
    $$v = \sqrt[]{\frac{E_0}{m}}$$
    2.

    $$E=E_0+\frac{1}{2}mv_1^2$$
    $$L=?$$
    $$\frac{\delta L}{\delta t} = R \otimes F = 0$$
    $$\Downarrow$$
    $$L = mr^2\omega\hat{z}$$
    $$L = mr^2\sqrt[]{\frac{k}{m}}\hat{z}$$
    3.
    
    $$E_0 + \frac{1}{2}mv_1^2 = \frac{1}{2}m\dot{r}^2+\frac{1}{2}mr^2(\frac{L}{mr^2})^2 + \frac{1}{2}kr^2$$
    $\dot{r} = 0$ במרחקים  מקסימלים \ מינימלים

    $$\Downarrow$$
    $$E_0 + \frac{1}{2}mv_1^2 = \frac{1}{2}\frac{L^2}{mr^2} + \frac{1}{2}kr^2$$