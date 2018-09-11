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
        $$x\leq 0$$
        $$y\leq 0$$
        פתרון:

        נעבור לקורדינטות פולאריות

        $$x=r\cos(\theta)$$
        $$y=r\sin(\theta)$$
        $$\Downarrow$$
        $$2 \leq r \leq 5$$
        $$\pi \leq \theta \leq \frac{3}{2}\pi$$
        $$J = \frac{u(x,y)}{u(r,\theta)} = |\frac{\frac{u_x}{u_r}}{\frac{u_y}{u_r}} \frac{\frac{u_x}{u_{\theta}}}{\frac{u_y}{u_{\theta}}}|$$
        $$J = |\frac{\frac{r \cos(\theta)}{u_r}}{\frac{r \sin(\theta)}{u_r}} \frac{\frac{r \cos(\theta)}{u_{\theta}}}{\frac{r \sin(\theta)}{u_{\theta}}}|$$
        $$J = |\frac{\cos(\theta)}{\sin(\theta)} \frac{-r \sin(\theta)}{r \cos(\theta)}|$$
        $$J = r\cos^2(\theta) + r\sin^2(\theta) = r(\cos^2(\theta)+\sin^2(\theta)) = r$$
        $$\Downarrow$$
        $$\int_{\pi}^{\frac{3}{2}\pi}\int_2^5 r\cos(\theta) \cdot r\sin(\theta) J \delta r \delta \theta$$
        $$\int_{\pi}^{\frac{3}{2}\pi}\int_2^5 r^3\cos(\theta)\sin(\theta) \delta r \delta \theta$$
        $$\int_{\pi}^{\frac{3}{2}\pi} \cos(\theta)\sin(\theta) \delta \theta \int_2^5 r^3 \delta r$$
        $$\int \cos(x)\sin(x)\delta x$$
        $$t= \sin(x) \rightarrow \delta t = \cos(x)\delta x \Downarrow$$
        $$\int t \delta t$$
        $$\frac{1}{2}t^2 \rightarrow \frac{1}{2}\sin^2(x)$$
        $$\Downarrow$$
        $$(\frac{1}{2}\sin^2(\theta)|_{\pi}^{\frac{3}{2}\pi}) (\frac{1}{4}r^4|_2^5) $$
        $$(\frac{1}{2}) (\frac{5^4}{4}-\frac{2^4}{4})$$
        $$(\frac{1}{2}) (\frac{5^4}{4}-\frac{2^4}{4})$$
        $$76.125$$


    2.
        $$\int\int_D x^2 \delta x \delta y$$
        $$D: \frac{x^2}{4}+\frac{y^2}{9}\leq 1$$
        פתרון:

        נעבור קורדינטות 

        $$x=2u$$
        $$y=3v$$
        $$\Downarrow$$
        $$u^2+v^2\leq 1$$
        נעבור לקורדינטות פולאריות

        $$u=r\cos(\theta)\rightarrow x = 2r\cos(\theta)$$
        $$v=r\sin(\theta)\rightarrow y = 3r\sin(\theta)$$
        $$\Downarrow$$
        $$0 \leq r \leq 1$$
        $$0 \leq \theta \leq 2\pi$$
        $$J = |\frac{2\cos(\theta)}{3\sin(\theta)} \frac{-2r\sin(\theta)}{3r\cos(\theta)}|$$
        $$J = 6r\cos^2(\theta)+6r\sin^2(\theta) = 6r$$
        $$\Downarrow$$
        $$\int_{0}^{2\pi}\int_0^1 4r^2\cos^2(\theta) 6r \delta r \delta \theta$$
        $$24\int_{0}^{2\pi} \cos^2(\theta) \delta \theta \int_0^1 r^3 \delta r$$
        $$24 (\frac{\sin(\theta)\cos(\theta) + x}{2}|_{0}^{2\pi}) (\frac{1}{4}r^4|_0^1)$$
        $$24 (\frac{\sin(\theta)\cos(\theta) + x}{2}|_{0}^{2\pi}) (\frac{1}{4}r^4|_0^1)$$
        $$24 (\pi) (\frac{1}{4})$$
        $$6\pi$$
        
    3.
        $$\int\int_D (x+2y) \delta x \delta y$$
        $$D: (2x+3y-1)^2+(3x+4y)^2\leq 16$$
         פתרון:

        נעבור קורדינטות 

        $$u=2x+3y-1$$
        $$v=3x+4y$$
        $$\Downarrow$$
        $$x=\frac{v-4y}{3}$$
        $$u=\frac{2v-8y}{3}+3y-1$$
        $$3u=2v-8y+9y-3$$
        $$3u=2v+y-3$$
        $$y=3u-2v+3$$
        $$x=\frac{v-12u+8v-12}{3} = \frac{-12u+9v-12}{3} = 3v-4u-4$$
        $$\Downarrow$$
        $$u^2+v^2\leq 16$$
        נעבור לקורדינטות פולאריות

        $$u=r\cos(\theta)$$
        $$v=r\sin(\theta)$$
        $$\Downarrow$$
        $$x = 3r\sin(\theta)-4r\cos(\theta)-4$$
        $$y = 3r\cos(\theta)-2r\sin(\theta)+3$$
        $$0\leq r \leq 4$$
        $$0 \leq \theta \leq 2\pi$$
        $$J = |\frac{3\sin(\theta)-4\cos(\theta)}{3\cos(\theta)-2\sin(\theta)} \frac{3r\cos(\theta)+4r\sin(\theta)}{-3r\sin(\theta)-2r\cos(\theta)}|$$
        $$J = (3\sin(\theta)-4\cos(\theta))(-3r\sin(\theta)-2r\cos(\theta))-(3r\cos(\theta)+4r\sin(\theta))(3\cos(\theta)-2\sin(\theta))$$
        $$J = -r[(3\sin(\theta)-4\cos(\theta))(3\sin(\theta)+2\cos(\theta))+(3\cos(\theta)+4\sin(\theta))(3\cos(\theta)-2\sin(\theta))]$$
        $$J = -r(9sin^2(\theta)+6\sin(\theta)\cos(\theta)-12\sin(\theta)\cos(\theta)-8\cos^2(\theta)+9\cos^2(\theta)-6\sin(\theta)\cos(\theta)+12\sin(\theta)\cos(\theta)-8\sin^2(\theta))$$
        $$J = -r(sin^2(\theta)+\cos^2(\theta))$$
        $$J = -r$$
        $$|J| = r$$
        $$\Downarrow$$
        $$\int_0^{2\pi}\int_0^{4} (3r\sin(\theta)-4r\cos(\theta)-4+6r\cos(\theta)-4r\sin(\theta)+6) r \delta r \delta \theta$$
        $$\int_0^{2\pi}\int_0^{4} (-r\sin(\theta)+2r\cos(\theta)+2) r \delta r \delta \theta$$
        $$\int_0^{2\pi}\int_0^{4} (-r^2\sin(\theta)+2r^2\cos(\theta)+2r \delta r)  \delta \theta$$
        $$\int_0^{2\pi} (-\frac{1}{3}r^3\sin(\theta)+\frac{2}{3}r^3\cos(\theta)+r^2 |_0^{4})  \delta \theta$$
        $$\int_0^{2\pi} (-\frac{64}{3}\sin(\theta)+\frac{2\cdot 64}{3}\cos(\theta)+16)  \delta \theta$$
        $$(\frac{64}{3}\cos(\theta)+\frac{2\cdot 64}{3}\sin(\theta)+16\theta|_0^{2\pi})$$
        $$(\frac{64}{3}\cos(\theta)+\frac{2\cdot 64}{3}\sin(\theta)+16\theta|_0^{2\pi})$$
        $$32\pi$$
6.  
    $$z=x^2+y^2$$
    $$xy=1$$
    $$xy=2$$
    $$y=2x$$
    $$2y=x$$
    $$x\geq 0$$
    פתרון:

    $$\int\int_D (x^2+y^2) \delta x \delta y$$
    $$D: \{1\leq xy\leq 2, 0\leq \frac{1}{2}x\leq y\leq 2x\}$$

    נעבור קורדינטות 

    $$u=xy \rightarrow$$
    $$v=\frac{y}{x}$$
    $$x=\frac{u}{y}$$
    $$y=vx$$
    $$x=\frac{u}{vx}$$
    $$x=\sqrt[]{\frac{u}{v}} = u^{\frac{1}{2}}v^{-\frac{1}{2}}$$
    $$y=v\sqrt[]{\frac{u}{v}} = u^{\frac{1}{2}}v^{\frac{1}{2}}$$
    $$J = |\frac{\frac{1}{2}u^{-\frac{1}{2}}v^{-\frac{1}{2}}}{\frac{1}{2}u^{-\frac{1}{2}}v^{\frac{1}{2}}} \frac{-\frac{1}{2}u^{\frac{1}{2}}v^{-\frac{3}{2}}}{\frac{1}{2}u^{\frac{1}{2}}v^{-\frac{1}{2}}}|$$
    $$J = (\frac{1}{2}u^{-\frac{1}{2}}v^{-\frac{1}{2}})(\frac{1}{2}u^{\frac{1}{2}}v^{-\frac{1}{2}})-(-\frac{1}{2}u^{\frac{1}{2}}v^{-\frac{3}{2}})(\frac{1}{2}u^{-\frac{1}{2}}v^{\frac{1}{2}})$$
    $$J = \frac{1}{4}v^{-1}+\frac{1}{4}v^{-1}$$
    $$J = \frac{1}{2}v^{-1}$$
    $$1\leq u\leq 2$$
    $$\frac{1}{2}\leq v\leq 2$$
    $$\Downarrow$$
    $$\int_{\frac{1}{2}}^{2}\int_{1}^{2} (uv^{-1}+uv) \frac{1}{2}v^{-1}\delta u \delta v$$
    $$\frac{1}{2}\int_{\frac{1}{2}}^{2}\int_{1}^{2} (uv^{-2}+u)\delta u \delta v$$
    $$\frac{1}{2}\int_{\frac{1}{2}}^{2}(\frac{1}{2}u^2v^{-2}+\frac{1}{2}u^2|_{1}^{2}) \delta v$$
    $$\frac{1}{2}\int_{\frac{1}{2}}^{2}(2v^{-2}+2-\frac{1}{2}v^{-2}-\frac{1}{2}) \delta v$$
    $$\frac{1}{2}\int_{\frac{1}{2}}^{2}(\frac{3}{2}v^{-2}+\frac{3}{2}) \delta v$$
    $$\frac{1}{2}(-\frac{3}{2}v^{-1}+\frac{3}{2}v|_{\frac{1}{2}}^{2})$$
    $$\frac{3}{4}(-v^{-1}+v|_{\frac{1}{2}}^{2})$$
    $$\frac{3}{4}(-\frac{1}{2}+2+2-\frac{1}{2})$$
    $$\frac{3}{4}(3)$$
    $$\frac{9}{4}$$
