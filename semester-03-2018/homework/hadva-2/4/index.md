<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>

### מטלה 4 חדו"א 2 - יובל סרף
1.
    $$f_{(x,y)} = x^3+3xy^2-3x^2-3y^2$$
    $$f_{x} = 3x^2+3y^2-6x$$
    $$f_{y} = 6xy-6y$$
    $$\Downarrow$$
    $$I.\ \ \ 3x^2+3y^2-6x = 0$$
    $$II.\ \ \ 6xy-6y = 0$$
    $$I.\ \ \ x^2+y^2-2x = 0$$
    $$II.\ \ \ y(x-1) = 0$$
    $$y=0 \Downarrow$$
    $$I.\ \ \ x^2+0-2x = 0$$
    $$I.\ \ \ x(x-2) = 0$$
    $$(0,0), (2,0)$$
    $$II.\ \ \ y(x-1) = 0$$
    $$x=1 \Downarrow$$
    $$I.\ \ \ 1+y^2-2 = 0$$
    $$I.\ \ \ y^2 = 1$$
    $$I.\ \ \ y = \pm 1$$
    $$(1,1), (1,-1)$$
    כעת יש לנו 4 נקודות חשודות לקיצון: $(0,0), (2,0), (1,1), (1,-1)$, נסווג אותן בעזרת נגזרת שנייה
    
    $$\Delta = f_{xx}f_{yy} - (f_{xy})^2$$
    $$f_{xx} = 6x-6$$
    $$f_{yy} = 6x-6$$
    $$f_{xy} = 6y$$
    $$\Downarrow$$
    $$\Delta = (6x-6)^2 - (6y)^2$$
    1. $$(0,0)$$
        $$\Delta(0,0) = (0-6)^2 - (0)^2 = 36 > 0$$
        $$f_{xx}(0,0) = 0-6 = -6 < 0$$
        $$\Downarrow$$
        $$(0,0) \Rightarrow maximum$$
    2. $$(2,0)$$
        $$\Delta(2,0) = (12-6)^2 - (0)^2 = 36 > 0$$
        $$f_{xx}(2,0) = 12-6 = 6 > 0$$
        $$\Downarrow$$
        $$(2,0) \Rightarrow minimum$$
    3. $$(1,1)$$
        $$\Delta(1,1) = (6-6)^2 - (6)^2 = -36 < 0$$
        $$\Downarrow$$

        $(1,1)$ $\Leftarrow$ אוכף
    4. $$(1,-1)$$
        $$\Delta(1,-1) = (6-6)^2 - (-6)^2 = -36 < 0$$
        $$\Downarrow$$
        
        $(1,-1)$ $\Leftarrow$ אוכף
2.
    $$f_{(x,y)} = x^2+xy+y^2+ax+by+c$$
    $$f_{(2,5)} = 11$$
    $$\Downarrow$$
    $$f_{x} = 2x+y+a$$
    $$f_{y} = 2y+x+b$$
    $$\Downarrow$$
    $$I.\ \ \ 2x+y+a = 0$$
    $$II.\ \ \ 2y+x+b = 0$$
    $$\Downarrow (x,y) = (2,5)$$
    $$I.\ \ \ 4+5+a = 0$$
    $$II.\ \ \ 10+2+b = 0$$
    $$a=-9, b=-12$$
    בדיקה:

    $$\Delta = f_{xx}f_{yy} - (f_{xy})^2$$
    $$f_{xx} = 2$$
    $$f_{yy} = 2$$
    $$f_{xy} = 1$$
    $$\Downarrow$$
    $$\Delta(2,5) = 4-1 = 3 > 0$$
    $$f_{xx}(2,5) = 2 > 0$$
    אכן מינימום מקומי, כעת נמצא את c:
    
    $$f_{(2,5)} = 11$$
    $$a=-9$$
    $$b=-12$$
    $$\Downarrow$$
    $$2^2+2\cdot 5+5^2-9\cdot 2-12\cdot 5+c = 11$$
    $$4+10+25-18-60+c = 11$$
    $$-39+c = 11$$
    $$c = 50$$
3.
    $$f_{(x,y)} = x^2+y^2$$
    $$u_{(x,y)} = xy-3$$
    1.
        $$y=\frac{3}{x}$$
        $$g_{(x)} = x^2+(\frac{3}{x})^2$$
        $$g_{(x)} = x^2+\frac{9}{x^2}$$
        $$g'_{(x)} = 2x-\frac{18}{x^3}$$
        $$g'_{(x)} = 2x-\frac{18}{x^3}$$
        $$2x-\frac{18}{x^3} = 0$$
        $$x^4-9 = 0$$
        $$x^4=9$$
        $$x_{1,2} = \pm \sqrt[]{3}$$
        $$g''_{(x)} = x+\frac{54}{x^4}$$
        $$x=\sqrt[]{3} \Downarrow$$
        $$g''_{(x)} = \sqrt[]{3}+\frac{54}{9} > 0$$
        $$x=\sqrt[]{3} \Rightarrow minimum$$
        $$x=-\sqrt[]{3} \Downarrow$$
        $$g''_{(x)} = -\sqrt[]{3}+\frac{54}{9} = 6-\sqrt[]{3} > 0$$
        $$x=-\sqrt[]{3} \Rightarrow minimum$$
    2.
        $$L(x,y,\gamma) = f_{(x,y)} + \gamma u_{(x,y)}$$
        $$L(x,y,\gamma) = x^2+y^2+\gamma (xy-3)$$
        $$\frac{L(x,y,\gamma)}{\delta x} = 2x+\gamma y$$
        $$\frac{L(x,y,\gamma)}{\delta y} = 2y+\gamma x$$
        $$\frac{L(x,y,\gamma)}{\delta \gamma} = xy-3$$
        $$\frac{L(x,y,\gamma)}{\delta \gamma} = \frac{L(x,y,\gamma)}{\delta x} = \frac{L(x,y,\gamma)}{\delta y} = 0 \Downarrow$$
        $$I.\ \ \ 2x+\gamma y = 0$$
        $$II.\ \ \ 2y+\gamma x = 0$$
        $$III.\ \ \ xy-3 = 0$$
        $$III.\ \ \ xy = 3$$
        $$III.\ \ \ y = \frac{3}{x}$$
        $$II.\ \ \ \frac{6}{x}+\gamma x = 0$$
        $$II.\ \ \ 6+\gamma x^2 = 0$$
        $$II.\ \ \ \gamma = \frac{-6}{x^2}$$
        $$I.\ \ \ 2x+\frac{-18}{x^3} = 0$$
        $$I.\ \ \ x+\frac{-9}{x^3} = 0$$
        $$I.\ \ \ x^4-9 = 0$$
        $$x=\pm \sqrt[]{3}$$
        $$y = \frac{3}{\pm \sqrt[]{3}} = \pm \sqrt[]{3}$$
        $$\Downarrow$$
        $$(\sqrt[]{3},\sqrt[]{3}), (-\sqrt[]{3},-\sqrt[]{3}) \Rightarrow minimum$$
4.
    $$u_{(x,y,z)} = x^2-(y-z)^2-1$$
    $$f_{(x,y,z)} = x^2+y^2+z^2$$
    $$\Downarrow$$
    $$L(x,y,z,\gamma) = f_{(x,y,z)} + \gamma u_{(x,y,z)}$$
    $$L(x,y,z,\gamma) = x^2+y^2+z^2+\gamma (x^2-(y-z)^2-1)$$
    $$L(x,y,z,\gamma) = x^2+y^2+z^2+\gamma (x^2-y^2+2yz-z^2-1)$$
    $$\frac{L(x,y,z,\gamma)}{\delta x} = 2x(1+\gamma)$$
    $$\frac{L(x,y,z,\gamma)}{\delta y} = 2y(1-\gamma) + 2\gamma z$$
    $$\frac{L(x,y,z,\gamma)}{\delta z} = \gamma(2y-2z)$$
    $$\frac{L(x,y,z,\gamma)}{\delta \gamma} = x^2-(y-z)^2-1$$
    $$\Downarrow$$
    $$I.\ \ \ 2x(1+\gamma) = 0$$
    $$II.\ \ \ 2y(1-\gamma) + 2\gamma z = 0$$
    $$III.\ \ \ \gamma(2y-2z) = 0$$
    $$IV.\ \ \ x^2-(y-z)^2-1 = 0$$
    $$I.\ \ \ x = 0$$
    $$IV.\ \ \ -(y-z)^2 \neq 1$$
    $$\Downarrow$$
    $$I.\ \ \ \gamma = -1$$
    $$II.\ \ \ 4y-2z = 0$$
    $$II.\ \ \ z = 2y$$
    $$III.\ \ \ (-1)(2y-4y) = 0$$
    $$III.\ \ \ y=0 \Rightarrow z=0$$
    $$IV.\ \ \ x^2-1 = 0$$
    $$IV.\ \ \ x = \pm 1$$
    נקודות מינימום הן: $(1,0,0), (-1,0,0)$, ומרחקן מהראשית הוא
    
    $$d_{(x,y,z)} = \sqrt[]{x^2+y^2+z^2}$$
    $$d_{(\pm 1,0,0)} = \sqrt[]{(\pm 1)^2+0^2+0^2}$$
    $$d_{(\pm 1,0,0)} = 1$$
5.
    1.
        $$\int\int_D xy \delta x \delta y$$
        $$D: 4\leq x^2+y^2\leq 25$$
    2.
        $$\int\int_D x^2 \delta x \delta y$$
        $$D: \frac{x^2}{4}+\frac{y^2}{9}\leq 1$$
    3.
        $$\int\int_D (x+2y) \delta x \delta y$$
        $$D: (2x+3y-1)^2+(3x+4y)^2\leq 16$$
6.  
    $$z=x^2+y^2$$
    $$xy=1$$
    $$xy=2$$
    $$y=2x$$
    $$2y=x$$
    $$x\geq 0$$
    פתרון:
