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
    $$f_{(x,y)} = \{ (x,y)\neq (0,0) : x\sin(y) \frac{x^2-y^2}{x^2+y^2}, (x,y)= (0,0) : x0 \}$$
    1. $$\frac{\delta^2 f}{\delta x \delta y} = \frac{x\sin(y) \frac{x^2-y^2}{x^2+y^2}}{\delta x \delta y}$$
    $$\frac{\delta f}{\delta x} = \frac{\frac{x^3\sin(y)-xy^2\sin(y)}{x^2+y^2}}{\delta x}$$
    $$\frac{\delta f}{\delta x} = \frac{(3x^2\sin(y)-y^2\sin(y))(x^2+y^2) - 2x(x^3\sin(y)-xy^2\sin(y))}{(x^2+y^2)^2}$$
    $$\frac{\delta f}{\delta x} = \frac{\sin(y)(3x^2-y^2)(x^2+y^2) - 2x\sin(y)(x^3-xy^2)}{(x^2+y^2)^2}$$
    $$\frac{\delta f}{\delta x} = \frac{\sin(y)(3x^4-y^4+2x^2y^2) +\sin(y)(-2x^4+2x^2y^2)}{(x^2+y^2)^2}$$
    $$\frac{\delta f}{\delta x} = \frac{\sin(y)(3x^4-y^4+2x^2y^2-2x^4+2x^2y^2)}{(x^2+y^2)^2}$$
    $$\frac{\delta f}{\delta x} = \frac{\sin(y)(x^4+4x^2y^2-y^4)}{(x^2+y^2)^2}$$

    2. $$\frac{\delta^2 f}{\delta y \delta x} = \frac{\frac{x^3\sin(y)-xy^2\sin(y)}{x^2+y^2}}{\delta y \delta x}$$
    