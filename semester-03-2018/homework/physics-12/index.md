<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# ש"ב פיזיקה - תרגיל 12
## יובל סרף
1.
    1. 
        $$T^2 = \frac{4\pi^2}{GM}a^3$$
        $$a=\frac{p}{1-\epsilon^2}$$
        $$r=\frac{p}{1+\epsilon\cos{\theta}}$$
        $$r_{min}=\frac{p}{1+\epsilon}$$
        $$r_{max}=\frac{p}{1-\epsilon}$$
        $$\Downarrow$$
        $$a^3 = \frac{T^2GM}{4\pi^2}$$
        $$a = \sqrt[3]{\frac{T^2GM}{4\pi^2}}$$
        $$\Downarrow$$
        $$\sqrt[3]{\frac{T^2GM}{4\pi^2}} = \frac{p}{1-\epsilon^2}$$
        $$p = (1-\epsilon^2)\sqrt[3]{\frac{T^2GM}{4\pi^2}}$$
        $$T=76, \epsilon=0.967 \Downarrow$$
        $$p \approx 431 \cdot 10^7 \sqrt[3]{G}$$
        $$\Downarrow$$
        $$r_{min}=\frac{431 \cdot 10^7\sqrt[3]{G}}{1+0.967} \approx 22\cdot 10^8 \sqrt[3]{G} _m$$
        $$r_{max}=\frac{431 \cdot 10^7\sqrt[3]{G}}{1-0.967} \approx 13\cdot 10^{10} \sqrt[3]{G} _m$$
    2.
        $$E_1 = \frac{1}{2}mv^2 -\frac{GMm}{r_{min}}$$
        $$E_2 = -\frac{GMm}{r_{max}}$$
        $$E_1=E_2$$
        $$\Downarrow$$
        $$\frac{1}{2}mv^2 -\frac{GMm}{r_{min}} = -\frac{GMm}{r_{max}}$$
        $$\frac{1}{2}mv^2 = \frac{GMm}{r_{min}}-\frac{GMm}{r_{max}}$$
        $$v^2 = 2GM(\frac{1}{r_{min}}-\frac{1}{r_{max}})$$
        $$v^2 = 2GM(\frac{1}{22\cdot 10^8 \sqrt[3]{G}}-\frac{1}{13\cdot 10^{10} \sqrt[3]{G}})$$
        $$v^2 = 2MG^{\frac{2}{3}}(\frac{1}{22\cdot 10^8}-\frac{1}{13\cdot 10^{10}})$$
        $$v \approx 43 \cdot 10^9 G^{\frac{1}{3}}$$
        $$$$
2. **עשינו בכיתה**
3.
    1.
        $$F = \frac{kq_1q_2}{r}$$
        $$E_p = \int F \delta r = kq_1q_2\ln{(r)}$$
        $$E_k = \frac{1}{2}mv^2 = \frac{1}{2}m\dot{r}^2 + \frac{1}{2}mr^2\dot{\theta}^2$$
        $$E_{tot} = E_k + E_p$$
        $$\Downarrow$$
        $$E_{tot} = \frac{1}{2}m\dot{r}^2 + \frac{1}{2}mr^2\dot{\theta}^2 + kq_1q_2\ln{(r)}$$
        $$\Downarrow$$
        $$E_{eff} = \frac{1}{2}mr^2\dot{\theta}^2 + kq_1q_2\ln{(r)}$$
        $$E_{eff} = \frac{L^2}{2mr^2} + kq_1q_2\ln{(r)}$$
        $$k,q_1,q_2,m>0 \Downarrow$$
        $$\forall r : E_{eff} > 0$$

4.
    1.
        $$\vec{F}_{(r)} = -\frac{GMm}{r^4}\hat{r}$$
        $$\vec{U_p}_{(r)} = -\int \vec{F}_{(r)}$$
        $$\vec{U_p}_{(r)} = -\frac{GMm}{3r^3}\hat{r}$$
    2.
        1.
            $$E_{tot} = E_k + {U_p}_{(r)}$$
            $$E_{tot} = \frac{1}{2}mv^2 -\frac{GMm}{3r^3}\hat{r}$$
            $$E_{tot} = \frac{1}{2}m\dot{r}^2 + \frac{1}{2}mr^2\dot{\theta}^2 -\frac{GMm}{3r^3}\hat{r}$$
            $$E_{tot} = \frac{1}{2}m\dot{r}^2 + \frac{L^2}{2mr^2} -\frac{GMm}{3r^3}\hat{r}$$
            $$E_{eff} = \frac{L^2}{2mr^2} -\frac{GMm}{3r^3}\hat{r}$$
        2.
            <img src="https://upload.wikimedia.org/wikipedia/he/2/24/Kepler_problem_orbits_2.png" width="400px">
        3. עמנואל אמר לא לעשות
        4. עמנואל אמר לא לעשות
        5. עמנואל אמר לא לעשות

5. **עשינו בכיתה**
6.
    $$I = \sum_{i=1}^{N}m_ir_i^2$$

    1. 
        $$I = MR^2$$

    2. נחלק את הדיסקה לעיגולים ברוחב $\Delta r$
    
        $$M = p \cdot \pi R^2$$
        $$p =  \frac{M}{\pi R^2}$$
        $$m = p \cdot \pi (r_i + \Delta r)^2 - p \cdot \pi (r_i)^2$$
        $$m = p \cdot \pi (r_i^2 + 2r_i\Delta r + \cancel{\Delta r^2}) - p \cdot \pi r_i^2$$
        $$m = 2\pi p r_i\Delta r$$
        $$m = 2\pi r_i\Delta r \cdot  \frac{M}{\pi R^2}$$
        $$m = \frac{2 M r_i\Delta r}{R^2}$$
        $$I = \sum_{i=1}^{N}m_ir_i^2$$
        $$\Downarrow$$
        $$I = \int_0^R \frac{2 M r_i\Delta r}{R^2}r_i^2$$
        $$I = \int_0^R \frac{2 M r_i^3}{R^2}\Delta r$$
        $$I = \frac{2 M r_i^4}{4R^2} |_0^R$$
        $$I = \frac{2 M R^4}{4R^2}$$
        $$I = \frac{1}{2}M R^2$$
    3. **עשינו בכיתה**
    4. **עשינו בכיתה**
    5. **עשינו בכיתה**
    6.
        נחלק את הלבנה לפרוסות שטוחות בגובה $\Delta L$

        $$M = p HWL$$
        $$p = \frac{M}{HWL}$$
        $$m = p HW\Delta L$$
        $$m = \frac{M}{HWL} HW\Delta L$$
        $$m = \frac{M\Delta L}{L} $$
        $$I = \sum_{i=1}^{N}m_ir_i^2$$
        $$r_i = \sqrt[]{x^2 + y^2} \Downarrow$$
        $$I = \int_0^{\frac{H}{2}} \int_0^{\frac{W}{2}} \int_0^{\frac{L}{2}} (\frac{M\Delta L}{L})[(x^2 + y^2)\Delta x \Delta y]$$
        $$I = M\int_0^{\frac{H}{2}} \int_0^{\frac{W}{2}} [(x^2 + y^2)\Delta x \Delta y] (\int_0^{\frac{L}{2}} \frac{1}{L}\Delta L)$$
        $$I = M\int_0^{\frac{H}{2}} \int_0^{\frac{W}{2}} [(x^2 + y^2)\Delta x \Delta y] (\frac{L}{L}|_0^{\frac{L}{2}})$$
        $$I = M\int_0^{\frac{H}{2}} \int_0^{\frac{W}{2}} [(x^2 + y^2)\Delta x \Delta y]$$
        $$I = M\int_0^{\frac{H}{2}} [(\frac{1}{3}x^3 + y^2x |_0^{\frac{W}{2}}) \Delta y]$$
        $$I = M\int_0^{\frac{H}{2}} [(\frac{W^3}{24} + \frac{Wy^2}{2}) \Delta y]$$
        $$I = M[(\frac{W^3y}{24} + \frac{Wy^3}{6}) |_0^{\frac{H}{2}}]$$
        $$I = M(\frac{W^3H}{48} + \frac{WH^3}{48})$$
        $$I = \frac{MWH}{48}(W^2 + H^2)$$
        
        
