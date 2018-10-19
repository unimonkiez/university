<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# ש"ב פיזיקה - תרגיל 7
## יובל סרף
1. **עשינו בכיתה**
2. 
    1.  

    $$R_{cm} = \frac{1}{M}(\int_0^L x \delta m_x)\hat{x} + \frac{1}{M}(\int_0^a y \delta m_y)\hat{y} + \frac{1}{M}(\int_0^a z \delta m_z)\hat{z}$$
    $$\delta m_x = \rho a^2 \delta x$$
    $$\delta m_y = \rho aL \delta y$$
    $$\delta m_z = \rho aL \delta z$$
    $$R_{cm} = \frac{1}{M}(\int_0^L x \rho a^2 \delta x)\hat{x} + \frac{1}{M}(\int_0^a y \rho  aL \delta y)\hat{y} + \frac{1}{M}(\int_0^a z \rho  aL \delta z)\hat{z}$$
    $$R_{cm} = \frac{\rho a^2}{M}(\int_0^L x \delta x)\hat{x} + \frac{\rho  aL }{M}(\int_0^a y \delta y)\hat{y} + \frac{\rho  aL}{M}(\int_0^a z \delta z)\hat{z}$$
    $$R_{cm} = \frac{\rho a^2}{M}(\frac{x^2}{2}|_0^L)\hat{x} + \frac{\rho  aL }{M}(\frac{y^2}{2}|_0^a)\hat{y} + \frac{\rho  aL}{M}(\frac{z^2}{2}|_0^a)\hat{z}$$
    $$R_{cm} = \frac{\rho a^2}{M}(\frac{L^2}{2})\hat{x} + \frac{\rho  aL }{M}(\frac{a^2}{2})\hat{y} + \frac{\rho  aL}{M}(\frac{a^2}{2})\hat{z}$$
    $$R_{cm} = \frac{\rho a^2L^2}{2M}\hat{x} + \frac{\rho  a^3L }{2M}\hat{y} + \frac{\rho  a^3L}{2M}\hat{z}$$
    $$M = \rho \cdot a^2L$$
    $$\Downarrow$$
    $$R_{cm} = \frac{\rho a^2L^2}{2\rho \cdot a^2L}\hat{x} + \frac{\rho  a^3L }{2\rho \cdot a^2L}\hat{y} + \frac{\rho  a^3L}{2\rho \cdot a^2L}\hat{z}$$
    $$R_{cm} = \frac{L}{2}\hat{x} + \frac{a}{2}\hat{y} + \frac{a}{2}\hat{z}$$



    2.
    $$R_{cm} = \frac{1}{M}(\int_0^L x \delta m)$$
    $$\delta m = \rho_{(x)} \cdot \delta x$$
    $$M = \int_0^L \rho_{(x)} \delta x$$
    $$R_{cm} = \frac{\int_0^L x \rho_{(x)} \delta x}{\int_0^L \rho_{(x)} \delta x}$$
    $$\rho_{(x)} = \frac{\rho_0x^2}{L^2}$$
    $$\Downarrow$$
    $$R_{cm} = \frac{\int_0^L x \frac{\rho_0x^2}{L^2} \delta x}{\int_0^L \frac{\rho_0x^2}{L^2} \delta x}$$
    $$R_{cm} = \frac{\int_0^L x \frac{\rho_0x^2}{L^2} \delta x}{\int_0^L \frac{\rho_0x^2}{L^2} \delta x}$$
    $$R_{cm} = \frac{\int_0^L \frac{\rho_0}{L^2}x^3 \delta x}{\int_0^L \frac{\rho_0}{L^2}x^2 \delta x}$$
    $$R_{cm} = \frac{\frac{\rho_0}{L^2}\int_0^L x^3 \delta x}{\frac{\rho_0}{L^2}\int_0^L x^2 \delta x}$$
    $$R_{cm} = \frac{\int_0^L x^3 \delta x}{\int_0^L x^2 \delta x}$$
    $$R_{cm} = \frac{\frac{x^4}{4}|_0^L}{\frac{x^3}{3}|_0^L}$$
    $$R_{cm} = \frac{\frac{L^4}{4}}{\frac{L^3}{3}}$$
    $$R_{cm} = \frac{\frac{L}{4}}{\frac{1}{3}}$$
    $$R_{cm} = \frac{3L}{4}$$
3. **עשינו בכיתה**
4.  
    $$M = 50_{kg}$$
    $$h = 80_{cm} = 0.8_{m}$$
    $$\vec{J} = \vec{F} \Delta t$$
    $$\vec{F} = Mg$$
    $$\vec{J} = Mg \Delta t$$
    $$x_{(t)} = x_0 + v_0 t + at^2$$
    $$x_0 = 0, v_0 = 0, a = g, x = 0.8$$
    $$0.8 = gt^2$$
    $$t^2 = \frac{0.8}{g}$$
    $$t = \sqrt[]{\frac{0.8}{g}}$$
    $$\vec{J} = Mg \sqrt[]{\frac{0.8}{g}}$$
    $$\vec{J} = M \sqrt[]{\frac{0.8g^2}{g}}$$
    $$\vec{J} = M \sqrt[]{0.8g}$$
    $$M = 80_{kg}, g=9.8_{\frac{m}{s^2}}$$
    $$\vec{J} = 80 \sqrt[]{0.8\cdot 9.8}$$
    $$\vec{J} = 80 \sqrt[]{0.8\cdot 9.8} = 224_{N}$$

5. **עשינו בכיתה**
6.  קבועים: 

    $$M_0, m, \frac{\delta m}{\delta t},F$$
    צ"ל:

    $$v_{t}$$
    פתרון: 
    
    $$\vec{J} =  \Delta P = F\Delta t$$
    $$\Delta P = P_1 - P_0$$
    $$P_0 = M_{(t)}v_{(t)}$$
    $$P_1 = (M_{(t)} - \Delta m)v_{(t + \Delta t)} + \Delta mv_{(t)}$$
    $$\Downarrow$$
    $$(M_{(t)} - \Delta m)v_{(t + \Delta t)} + \Delta mv_{(t)} - M_{(t)}v_{(t)} = F\Delta t$$
    $$M_{(t)}(v_{(t + \Delta t)} - v_{(t)}) - \Delta m(v_{(t + \Delta t)} - v_{(t)}) = F\Delta t$$
    $$M_{(t)}(v_{(t + \Delta t)} - v_{(t)}) \cancel{- \Delta m(\frac{\delta v}{\delta t} \Delta t)} = F\Delta t$$
    $$M_{(t)}(\frac{\delta v}{\delta t} \Delta t) = F\Delta t$$
    $$M_{(t)}(\frac{\delta v}{\delta t}) = F$$
    $$\frac{\delta v}{\delta t} = \frac{F}{M_{(t)}}$$
    $$\delta v = \frac{F}{M_{(t)}} \delta t$$
    $$\delta v = \frac{F}{M_0 - \frac{\delta m}{\delta t} t}$$
    $$\delta v = \int_0^t \frac{F}{M_0 - \frac{\delta m}{\delta t} t}$$
    $$\delta v = F\int_0^t \frac{1}{M_0 - \frac{\delta m}{\delta t} t}$$
    $$\delta v = F\cdot |_0^t\ln{(M_0 - \frac{\delta m}{\delta t} t)}$$
    $$\delta v = F\cdot |_0^t\ln{(M_0 - \frac{\delta m}{\delta t} t) - \ln{(M_0)}}$$
    $$\delta v = v_{(t)} - v_0 = F\frac{\delta t}{\delta m} |_0^t\ln{(\frac{M_0 - \frac{\delta m}{\delta t} t}{M_0})} = F\frac{\delta t}{\delta m}\ln{(\frac{M_0}{M_0-\frac{\delta m}{\delta t}t})}$$
    
7. 
    1.
    $$P_1 = F\Delta t$$
    $$v = F\Delta t$$
    $$v = \frac{F\Delta t}{M+m}$$

    2.
    $$N = 100N, M = 500kg, b=20_{\frac{kg}{s}}, m=200kg$$
    $$\Delta t = \frac{m}{b} = \frac{200}{20} = 10_s$$
    $$v = \frac{F\Delta t}{M+m}$$
    $$\Downarrow$$
    $$v = \frac{100 \cdot 10}{500+200} = \frac{1000}{700} = \frac{10}{7}_{\frac{m}{s}}$$
8. 
    $$\Delta p = F\Delta t$$
    $$P_0 = \Delta mu + M_{(t)}v_{(t)}$$
    $$P_1 = (M_{(t)} + \Delta m)v_{(t + \Delta t)}$$
    $$-\Delta mu - M_{(t)}v_{(t)} + (M_{(t)} + \Delta m)v_{(t + \Delta t)} = F\Delta t$$
    $$-\Delta mu - M_{(t)}v_{(t)} + (M_{(t)} + \Delta m)(v_{(t)} + \frac{\delta v}{\delta t}\Delta t) = F\Delta t$$
    $$-\Delta mu - M_{(t)}v_{(t)} - M_{(t)}v_{(t)} + M_{(t)}\frac{\delta v}{\delta t}\Delta t + \Delta mv_{(t)} \cancel{+ \Delta m\frac{\delta v}{\delta t}\Delta t}= F\Delta t$$
    $$-\Delta mu + M_{(t)}\frac{\delta v}{\delta t}\Delta t + \Delta mv_{(t)}= F\Delta t$$
    $$\Delta m(v-u) + M_{(t)}\frac{\delta v}{\delta t}\Delta t= F\Delta t$$
    $$M\frac{\delta v}{\delta t}\Delta t= F\Delta t - \Delta m(v-u)$$
    $$M\frac{\delta v}{\delta t}\Delta t= F\Delta t + \Delta m(u-v)$$
    $$\frac{\delta v}{\delta t}= \frac{F\Delta t + \Delta m(u-v)}{M\Delta t}$$
    $$\frac{\delta v}{\delta t}= \frac{F\Delta t + B\Delta t(u-v)}{M\Delta t}$$
    $$\frac{\delta v}{\delta t}= \frac{F + B(u-v)}{M}$$
9. **עשינו בכיתה**
10. **להשלים**
