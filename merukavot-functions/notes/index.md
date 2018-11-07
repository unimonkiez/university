<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex, annotation {
        direction: ltr;
    }
</style>
# פונקציות מרוכבות
#### 21.10.2018
* $$L = X+ iY$$
    * $$\lim_{t \rightarrow t_0} f(t) = L$$
    * $$\lim_{t \rightarrow t_0} x(t) = X$$
    * $$\lim_{t \rightarrow t_0} y(t) = Y$$
    * $$\lim_{t \rightarrow t_0} |f(t) - L| = 0$$
2. $f$ פונקציה מ-R ל-C היא רציפה ב-$t_0$ אם $\lim_{t \rightarrow t_0}f(t) = f(t_0)$
3. הדברים הבאים שקולים:
    * $f(t)$ רציפה
    * $x(t), y(t)$ רציפות
3. $f$ פונקציה מ-R ל-C היא גזירה ב$t_0$ , והנגזרת שלה M אם $\lim_{t \rightarrow t_0}\frac{f(t)-f(t_0)}{t-t_0}$ קיים ושווה M.  
$f'(t_0) = M$
5. $$f'(t_0) = x'(t_0) +iy'(t_0)$$
##### פונקציות מ-C ל-C
$$f(z) = u(x,y) +iv(x,y)$$
6. *משוואות קושי ריימן* - אם $f(z)$ גזירה ב$z_0$ אז הנגזרות החלקיות של $u$ ו-$v$ ביחס ל-$x$ ו-$y$ קיימות ב $(x_0, y_0)$ ו

$$\frac{\delta u}{\delta x} = \frac{\delta v}{\delta y}, \frac{\delta u}{\delta y} = \frac{\delta v}{\delta x}$$

#### 4.11.2018
##### פונקציות אלמנטריות
* פונקציות טרינוגומטריות
    * $$\cos z = \frac{e^{iz} + e^{-iz}}{2}$$
    * $$\sin z = \frac{e^{iz} - e^{-iz}}{2i}$$
* פונקציות היפורביליות
    * $$\cosh z = \frac{e^{z} + e^{-z}}{2}$$
    * $$\sinh z = \frac{e^{z} - e^{-z}}{2}$$
    * $$\cosh^2 z - \sinh^2 z = 1$$
    * $$\sinh' z = \cosh z$$
    * $$\cosh' z = \sinh z$$
* חזקות
    * $$z^{\alpha} = e^{\alpha \log(z)} \ \ \ \ \alpha,z \in C$$
##### אינטגרציה

*  $$R \longrightarrow C$$
    $$z_{(t)} = x_{(t)} +iy_{(t)}$$
    $$\int z_{(t)}\delta t = \int x_{(t)}\delta t +i\int y_{(t)}\delta t$$
*  $$C \longrightarrow C$$
    <!-- $$\int z_{(t)}\delta t = \int x_{(t)}\delta t +i\int y_{(t)}\delta t$$ -->
#### 7.11.2018
* $$\log (z) = \ln (|z|) + i (\theta +2\pi k)$$
* $$-i = \frac{1}{i}$$
*
    תרגיל

    $$\sin (z) = -2i$$
    $$\frac{e^{iz} - e^{-iz}}{2i} = -2i$$
    $$e^{iz} - e^{-iz} = 4$$
    $$t = e^{iz}$$
    $$\Downarrow$$
    $$t -\frac{1}{t} = 4$$
    $$t^2 -4t - 1 =0$$
    $$t_{1,2} = \frac{4\pm \sqrt[]{16 - 4}}{2}$$
    $$t_{1,2} = 2\pm \sqrt[]{5}$$
    $$e^{iz} = 2\pm \sqrt[]{5}\ \ \ /\log ()$$
    $$iz = \log (2\pm \sqrt[]{5})$$
    נפצל למקרים:
    
    *  
        $$iz = \ln (2+\sqrt[]{5}) + i(0+2\pi k) \ \ \ :k\in Z$$
        $$iz = \ln (2+\sqrt[]{5}) + i2\pi k$$
        $$z_{(k)} = 2\pi k -i\ln (2+\sqrt[]{5})$$
    *  
        $$iz = \ln (|2-\sqrt[]{5}|) + i(\pi+2\pi k) \ \ \ :k\in Z$$
        $$iz = \ln (\sqrt[]{5}-2) + i(\pi+2\pi k)$$
        $$iz = \pi +2\pi k -i \ln (\sqrt[]{5} - 2)$$
*
    תרגיל

    $$e^{e^{z}} = 1$$
    $$e^{e^{z}} = e^{2\pi k i}$$
    $$e^{z} = 2\pi k i\ \ \ /\log ()$$
    $$z = \log (2\pi k i) \ \ \ :k\neq 0$$
    נפצל למקרים:
    
    * 
        $$k>0$$
        $$z = \ln|2\pi k i| + i(\frac{\pi}{2} + 2\pi n) \ \ \ :n\in Z$$
        $$|2\pi k i| = 2\pi k |i| = 2\pi k|0+i| = 2\pi k \sqrt[]{0^2+1^2} = 2\pi k$$
        $$\Downarrow$$
        $$z = \ln(2\pi k) + i(\frac{\pi}{2} + 2\pi n)$$
    * 
        $$k<0$$
        $$z = \ln|2\pi k i| + i(-\frac{\pi}{2} + 2\pi n) \ \ \ :n\in Z$$
        $$z = \ln(2\pi |k|) + i(-\frac{\pi}{2} + 2\pi n)$$
* $$log(z) \Rightarrow -\pi \leq \theta \leq \pi$$
* $$Log(z) \Rightarrow 0 \leq \theta \leq 2\pi$$
* $$z_{(t)} = e^{it}\ \ \ :0\leq t \leq 2\pi$$
* $$z_{(t)} = e^{it} = r\cos(t) + ir\sin(t)$$
*
    פרמריזציה של הקו הישר שמחבר בין 
    
    $$z_0 = 0$$
    $$z_1 = 2+i$$
    $$\Downarrow$$
    $$z_{(t)} = t(2+i)\ \ \ :0\leq t \leq 1$$
*
    פרמריזציה של פרבולה
    
    $$y=x^2$$
    $$t = x \Rightarrow y=t^2$$
    $$\Downarrow$$
    $$z_{(t)} = t+it^2$$
*
    פרמריזציה של רבע מעגל היחידה ברביע הרביעי נגד כיוון השעון
    
    $$y=x^2$$
    $$t = x \Rightarrow y=t^2$$
    $$\Downarrow$$
    $$z_{(t)} = e^{it}\ \ \ :-\frac{\pi}{2}\leq t 0$$