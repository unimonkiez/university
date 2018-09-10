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
    1. $$\frac{\delta^2 f}{\delta y \delta x} (0,0) = \frac{\delta}{\delta y}(\frac{\delta f}{\delta x})(0,0) = \lim_{\Delta y \rightarrow 0}\frac{\frac{\delta f}{\delta x}(0,\Delta y) - \frac{\delta f}{\delta x}(0,0)}{\Delta y}$$
    $$\frac{\delta f}{\delta x}(0,0) = \lim_{\Delta x \rightarrow 0}\frac{f(\Delta x, 0) - f(0,0)}{\Delta x} = 0$$
    $$\frac{\delta f}{\delta x}(0,\Delta y) = \lim_{\Delta x \rightarrow 0}\frac{f(\Delta x, \Delta y) - f(0,\Delta y)}{\Delta x} = \lim_{\Delta x \rightarrow 0}\frac{\Delta x \cdot \sin(\Delta y)}{\Delta x}\frac{(\Delta x)^2 - (\Delta y)^2}{(\Delta x)^2 + (\Delta y)^2} = \lim_{\Delta x \rightarrow 0}\sin(\Delta y)\frac{0 - (\Delta y)^2}{0 + (\Delta y)^2} = -\sin(\Delta y)$$
    $$\Downarrow$$
    $$\frac{\delta^2 f}{\delta y \delta x} (0,0) = \lim_{\Delta y \rightarrow 0}\frac{-\sin(\Delta y) - 0}{\Delta y} = -1$$
    

    2. $$\frac{\delta^2 f}{\delta x \delta y} (0,0) = \frac{\delta}{\delta x}(\frac{\delta f}{\delta y})(0,0) = \lim_{\Delta x \rightarrow 0}\frac{\frac{\delta f}{\delta y}(\Delta x,0) - \frac{\delta f}{\delta y}(0,0)}{\Delta x}$$
    $$\frac{\delta f}{\delta y}(0,0) = \lim_{\Delta y \rightarrow 0}\frac{f(0,\Delta y) - f(0,0)}{\Delta y} = 0$$
    $$\frac{\delta f}{\delta y}(\Delta x,0) = \lim_{\Delta y \rightarrow 0}\frac{f(\Delta x, \Delta y) - f(\Delta x,0)}{\Delta y}$$
    $$\frac{\delta f}{\delta y}(\Delta x,0) = \lim_{\Delta y \rightarrow 0}\frac{\Delta x \cdot \sin(\Delta y)}{\Delta y}\frac{(\Delta x)^2 - (\Delta y)^2}{(\Delta x)^2 + (\Delta y)^2} - \frac{0 \cdot \sin(\Delta y)}{\Delta y}\frac{(0)^2 - (\Delta y)^2}{(0)^2 + (\Delta y)^2}$$
    $$\frac{\delta f}{\delta y}(\Delta x,0) = \lim_{\Delta y \rightarrow 0}\Delta x\frac{(\Delta x)^2}{(\Delta x)^2} - 0 = \Delta x$$
    $$\Downarrow$$
    $$\frac{\delta^2 f}{\delta x \delta y} (0,0) =\lim_{\Delta x \rightarrow 0}\frac{\Delta x - 0}{\Delta x} = 1$$
    
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

4.
    $$f_{(x,y,z)} = axy^2+byz+cx^3z^2$$
    הפונקציה פולינום ולכן דפרינציאבלית, כעת נחשב את הוקטור:
    
    $$\vec{v} = (f_x, f_y, f_z)$$
    $$\vec{v}_{(x,y,z)} = (ay^2+3cx^2z^2, 2axy+bz, by+2cx^3z)$$
    $$\vec{v}_{(1,2,-1)} = (4a+3c, 4a-b, 2b-2c)$$

    מקביל לציר $z$ ז"א $x,y=0$, ואורך 64 ז"א $z=64$

    $$I. \ \ 4a+3c = 0$$
    $$II. \ \ 4a-b = 0$$
    $$III. \ \ 2b-2c = 64$$

    $$II. \ \ b= 4a$$
    $$I. \ \ c = -\frac{4}{3}a$$
    $$III. \ \ 8a+2\cdot \frac{4}{3}a = 64$$
    $$III. \ \ 8a+\frac{8}{3}a = 64$$
    $$III. \ \ a+\frac{1}{3}a = 8$$
    $$III. \ \ \frac{4}{3}a = 8$$
    $$III. \ \ \frac{1}{3}a = 2$$
    $$a = 6$$
    $$b= 24$$
    $$c = -8$$
    