<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>

### מטלה 3 חדו"א 2 - יובל סרף
1.
    $$f_{(x,y)} = \{ (x,y) \neq (0,0): \frac{sin (x^2y)}{x^2+y^2}, (x,y) = (0,0): 0\}$$

    1. $$\lim_{(x,y) \rightarrow (0,0)}\frac{sin (x^2y)}{x^2+y^2}$$
    $$\lim_{(x,y) \rightarrow (0,0)}\frac{\cancel{\sin (x^2y)}(x^2y)}{(x^2+y^2)\cancel{(x^2y)}}$$
    $$\lim_{(x,y) \rightarrow (0,0)}\frac{x^2y}{x^2+y^2}$$
    נשתמש בכלל בסנדוויץ'

    $$0\leq |\frac{x^2y}{x^2+y^2}| \leq |\frac{x^2y}{x^2}| \leq |y|$$
    $$\lim_{y \rightarrow 0} |y| = 0 \Rightarrow \lim_{(x,y) \rightarrow (0,0)}\frac{x^2y}{x^2+y^2} = 0$$
    מכיוון שהגבול של הפונקציה שווה לערך הפונקציה בנקודה $x=0$, אז הפונקציה רציפה.

    2. $$f_{x(0,0)} = \lim_{\Delta x \rightarrow 0}\frac{\frac{\sin (\Delta x^2 \cdot 0)}{\Delta x^2 + 0} - 0}{\Delta x}$$
    $$f_{x(0,0)} = \lim_{\Delta x \rightarrow 0}\frac{0}{\Delta x^3} = 0$$

    $$f_{y(0,0)} = \lim_{\Delta y \rightarrow 0}\frac{\frac{\sin (\Delta y \cdot 0)}{\Delta y^2 + 0} - 0}{\Delta y}$$
    $$f_{y(0,0)} = \lim_{\Delta y \rightarrow 0}\frac{0}{\Delta y^3} = 0$$
    3. 


    $$\lim_{(\Delta x,\Delta y) \rightarrow (0,0)}\epsilon(\Delta x,\Delta y)$$
    $$\Delta x = x- 0 = x$$
    $$\Delta y = y- 0 = y$$
    $$\Downarrow$$
    $$\lim_{(x,y) \rightarrow (0,0)}\epsilon(x,y) = \lim_{(x,y) \rightarrow (0,0)}\frac{\frac{\sin{x^2y}}{x^2+y^2} -x \cdot f_{x(0,0)} -y\cdot f_{y(0,0)}}{\sqrt[]{x^2+y^2}}$$
    $$\lim_{(x,y) \rightarrow (0,0)}\epsilon(x,y) = \lim_{(x,y) \rightarrow (0,0)}\frac{\frac{\sin{x^2y}}{x^2+y^2} -x \cdot 0 -y\cdot 0}{\sqrt[]{x^2+y^2}}$$
    $$\lim_{(x,y) \rightarrow (0,0)}\epsilon(x,y) = \lim_{(x,y) \rightarrow (0,0)}\frac{\sin{x^2y}}{(x^2+y^2)^{\frac{3}{2}}} $$
    נשתמש בדסנדוויץ':  

    $$0 \leq |\frac{\sin{x^2y}}{(x^2+y^2)^{\frac{3}{2}}}| \leq |\frac{\sin{x^2y}}{x^2+y^2}|$$
    $$\Downarrow$$
    $$\lim_{(x,y) \rightarrow (0,0)}\epsilon(x,y) = \lim_{(x,y) \rightarrow (0,0)}\frac{\sin{x^2y}}{(x^2+y^2)^{\frac{3}{2}}}  = 0$$
    ולכן הפונקציה דיפרנציאבילית ב-$(0,0)$
2.
    $$f_{(x,y)} = \{ (x,y)\neq (0,0) : x\sin(y) \frac{x^2-y^2}{x^2+y^2}, (x,y)= (0,0) : 0 \}$$
    1. $$\frac{\delta^2 f}{\delta x \delta y} = \frac{x\sin(y) \frac{x^2-y^2}{x^2+y^2}}{\delta x \delta y}$$
    $$\frac{\delta f}{\delta x} = \frac{\frac{x^3\sin(y)-xy^2\sin(y)}{x^2+y^2}}{\delta x}$$
    $$\frac{\delta f}{\delta x} = \frac{(3x^2\sin(y)-y^2\sin(y))(x^2+y^2) - 2x(x^3\sin(y)-xy^2\sin(y))}{(x^2+y^2)^2}$$
    $$\frac{\delta f}{\delta x} = \frac{\sin(y)(3x^2-y^2)(x^2+y^2) - 2x\sin(y)(x^3-xy^2)}{(x^2+y^2)^2}$$
    $$\frac{\delta f}{\delta x} = \frac{\sin(y)(3x^4-y^4+2x^2y^2) +\sin(y)(-2x^4+2x^2y^2)}{(x^2+y^2)^2}$$
    $$\frac{\delta f}{\delta x} = \frac{\sin(y)(3x^4-y^4+2x^2y^2-2x^4+2x^2y^2)}{(x^2+y^2)^2}$$
    $$\frac{\delta f}{\delta x} = \frac{\sin(y)(x^4+4x^2y^2-y^4)}{(x^2+y^2)^2}$$
    $$\frac{\delta^2 f}{\delta x \delta y} = \frac{\frac{\sin(y)(x^4+4x^2y^2-y^4)}{(x^2+y^2)^2}}{\delta y}$$
    $$\frac{\delta^2 f}{\delta x \delta y} = \cos(y)\frac{(x^4+4x^2y^2-y^4)}{(x^2+y^2)^2} + \sin(y)\frac{\frac{(x^4+4x^2y^2-y^4)}{(x^2+y^2)^2}}{\delta y}$$
    $$\frac{\delta^2 f}{\delta x \delta y} = \cos(y)\frac{(x^4+4x^2y^2-y^4)}{(x^2+y^2)^2} + \sin(y)\frac{(x^2+y^2)^2(8x^2y-4y^3)-(x^4+4x^2y^2-y^4)4y(x^2+y^2)}{(x^2+y^2)^4}$$
    $$\frac{\delta^2 f}{\delta x \delta y} = \cos(y)\frac{(x^4+4x^2y^2-y^4)}{(x^2+y^2)^2} + \sin(y)\frac{(x^2+y^2)(8x^2y-4y^3)-(x^4+4x^2y^2-y^4)4y}{(x^2+y^2)^3}$$
    $$\frac{\delta^2 f}{\delta x \delta y} = \cos(y)\frac{(x^4+4x^2y^2-y^4)}{(x^2+y^2)^2} + \sin(y)\frac{8x^4y-4x^2y^3+8x^2y^3-4y^5-4x^4y-16x^2y^3+4y^5}{(x^2+y^2)^3}$$
    $$\frac{\delta^2 f}{\delta x \delta y} = \cos(y)\frac{(x^4+4x^2y^2-y^4)}{(x^2+y^2)^2} + \sin(y)\frac{4x^4y-12x^2y^3}{(x^2+y^2)^3}$$

    2. $$\frac{\delta^2 f}{\delta y \delta x} = \frac{x\sin(y) \frac{x^2-y^2}{x^2+y^2}}{\delta y \delta x}$$
    $$\frac{\delta^2 f}{\delta y \delta x} = \frac{\sin(y) \frac{x^3-xy^2}{x^2+y^2}}{\delta y \delta x}$$
    $$\frac{\delta f}{\delta y} = \frac{\sin(y) \frac{x^3-xy^2}{x^2+y^2}}{\delta y}$$
    $$\frac{\delta f}{\delta y} = \sin(y) \frac{\frac{x^3-xy^2}{x^2+y^2}}{\delta y}+\cos(y)\frac{x^3-xy^2}{x^2+y^2}$$
    $$\frac{\delta f}{\delta y} = \sin(y) \frac{-2xy(x^2+y^2)-2y(x^3-xy^2)}{(x^2+y^2)^2}+\cos(y)\frac{x^3-xy^2}{x^2+y^2}$$
    $$\frac{\delta f}{\delta y} = \sin(y) \frac{-2y(x^3+xy^2)-2y(x^3-xy^2)}{(x^2+y^2)^2}+\cos(y)\frac{x^3-xy^2}{x^2+y^2}$$
    $$\frac{\delta f}{\delta y} = \sin(y) \frac{-4x^3y}{(x^2+y^2)^2}+\cos(y)\frac{x^3-xy^2}{x^2+y^2}$$
    $$\frac{\delta^2 f}{\delta y \delta x} = \frac{\sin(y) \frac{-4x^3y}{(x^2+y^2)^2}+\cos(y)\frac{x^3-xy^2}{x^2+y^2}}{\delta x}$$
    $$\frac{\delta^2 f}{\delta y \delta x} = \sin(y) \frac{-12x^2y(x^2+y^2)^2+4x^3y(4x(x^2+y^2))}{(x^2+y^2)^4}+\cos(y)\frac{(3x^2-y^2)(x^2+y^2)-2x(x^3-xy^2)}{(x^2+y^2)^2}$$
    $$\frac{\delta^2 f}{\delta y \delta x} = \sin(y) \frac{-12x^2y(x^2+y^2)+16x^4y}{(x^2+y^2)^3}+\cos(y)\frac{3x^4+3x^2y^2-x^2y^2-y^4-2x^4+2x^2y^2}{(x^2+y^2)^2}$$
    $$\frac{\delta^2 f}{\delta y \delta x} = \sin(y) \frac{-12x^4y-12x^2y^3+16x^4y}{(x^2+y^2)^3}+\cos(y)\frac{3x^4+3x^2y^2-x^2y^2-y^4-2x^4+2x^2y^2}{(x^2+y^2)^2}$$
    $$\frac{\delta^2 f}{\delta y \delta x} = \sin(y) \frac{-12x^4y-12x^2y^3+16x^4y}{(x^2+y^2)^3}+\cos(y)\frac{x^4+4x^2y^2-y^4}{(x^2+y^2)^2}$$
3.
    $$f_{(x,y)} = \{ (x,y)\neq (0,0) : x\sin(y) \frac{(x^2+y^2)^{\alpha}}{\ln (x^2+y^2)}, (x,y)= (0,0) : 0 \}, x^2+y^2<1$$
    1. צ"ל:  

    $$\lim_{(x,y) \rightarrow (0,0)}\frac{(x^2+y^2)^{\alpha}}{\ln (x^2+y^2)} = 0$$

    פתרון:  

    $$\lim_{(x,y) \rightarrow (0,0)}\frac{(x^2+y^2)^{\alpha}}{\ln (x^2+y^2)}$$
    $$t = x^2+y^2$$
    $$(x,y) \rightarrow (0,0), t\rightarrow 0+$$
    $$\lim_{t \rightarrow 0+}\frac{t^{\alpha}}{\ln t}$$
    $$\alpha \geq 0 \Rightarrow \lim_{t \rightarrow 0+}\frac{t^{\alpha}}{\ln t} = 0$$
    $$\alpha < 0 \Rightarrow \lim_{t \rightarrow 0+}\frac{t^{\alpha}}{\ln t} = \infty$$
    $$\Downarrow$$
    $$\alpha \geq 0$$
    2. 

    $$\lim_{(\Delta x,\Delta y) \rightarrow (0,0)}\epsilon(\Delta x,\Delta y)$$
    $$\lim_{(\Delta x,\Delta y) \rightarrow (0,0)}\epsilon(\Delta x,\Delta y) = \lim_{(\Delta x,\Delta y) \rightarrow (0,0)}\frac{\frac{(\Delta x^2+\Delta y^2)^{\alpha}}{\ln (\Delta x^2+\Delta y^2)} -\Delta x \cdot f_{x(0,0)} -\Delta y\cdot f_{y(0,0)}}{\sqrt[]{\Delta x^2+\Delta y^2}}$$
    $$\Downarrow$$
    $$f_{x(0,0)} = \lim_{\Delta x \rightarrow 0}\frac{f_{(\Delta x,0)} - f_{(0,0)}}{\Delta x}$$
    $$f_{x(0,0)} = \lim_{\Delta x \rightarrow 0}\frac{\Delta x^{2\alpha - 1}}{\ln (\Delta x^2)}$$
    $$\alpha \geq \frac{1}{2} \Rightarrow f_{x(0,0)} = 0$$
    $$f_{y(0,0)} = \lim_{\Delta y \rightarrow 0}\frac{f_{(\Delta y,0)} - f_{(0,0)}}{\Delta y}$$
    $$f_{y(0,0)} = \lim_{\Delta y \rightarrow 0}\frac{\Delta y^{2\alpha - 1}}{\ln (\Delta y^2)}$$
    $$\alpha \geq \frac{1}{2} \Rightarrow f_{y(0,0)} = 0$$
    $$\alpha \geq \frac{1}{2} \Downarrow$$
    $$\lim_{(\Delta x,\Delta y) \rightarrow (0,0)}\epsilon(\Delta x,\Delta y) = \lim_{(\Delta x,\Delta y) \rightarrow (0,0)}\frac{\frac{(\Delta x^2+\Delta y^2)^{\alpha}}{\ln (\Delta x^2+\Delta y^2)} -\Delta x \cdot 0 -\Delta y\cdot 0}{\sqrt[]{\Delta x^2+\Delta y^2}}$$
    $$\lim_{(\Delta x,\Delta y) \rightarrow (0,0)}\epsilon(\Delta x,\Delta y) = \lim_{(\Delta x,\Delta y) \rightarrow (0,0)}\frac{\frac{(\Delta x^2+\Delta y^2)^{\alpha}}{\ln (\Delta x^2+\Delta y^2)}}{\sqrt[]{\Delta x^2+\Delta y^2}}$$
    $$t = \Delta x^2+\Delta y^2, t \rightarrow 0+$$
    $$\lim_{(\Delta x,\Delta y) \rightarrow (0,0)}\epsilon(\Delta x,\Delta y) = \lim_{t \rightarrow 0+}\frac{\frac{t^{\alpha}}{\ln t}}{\sqrt[]{t}}$$
    $$\lim_{(\Delta x,\Delta y) \rightarrow (0,0)}\epsilon(\Delta x,\Delta y) = \lim_{t \rightarrow 0+}\frac{t^{\alpha - \frac{1}{2}}}{\ln t}$$
    $$\lim_{(\Delta x,\Delta y) \rightarrow (0,0)}\epsilon(\Delta x,\Delta y) \Longleftrightarrow \alpha \geq \frac{1}{2}$$