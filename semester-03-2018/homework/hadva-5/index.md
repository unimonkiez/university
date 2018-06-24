<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>

### מטלה 5 חדו"א - יובל סרף
1.
    צ"ל
    
    $$x-\frac{x^2}{2}<\ln{(1+x)}<x-\frac{x^2}{2}+\frac{x^3}{3} : x>0$$
    פתרון:  

    
    $$f_{(x)} = \ln{(1+x)}$$
    $$f_{(x)} = p_n(x) + R_n(x)$$
    $$f^{(1)}_{(x)} = \frac{1}{1+x}$$
    $$f^{(2)}_{(x)} = -\frac{1}{(1+x)^2}$$
    $$f^{(3)}_{(x)} = \frac{2}{(1+x)^3}$$
    $$\Downarrow$$
    $$f^{(k)}_{(x)} = (-1)^{k+1}\frac{(k-1)!}{(1+x)^k}$$
    $$f^{(k)}_{(0)} = (-1)^{k+1}\frac{(k-1)!}{(1+0)^k}=(-1)^{k+1}(k-1)!$$
    $$p_n(x) = \sum_{k=0}^n\frac{f^{(k)}(x_0)}{k!}(x-x_0)^k$$
    $$R_n(x) = \frac{f^{(n+1)}(c)}{(n+1)!}(x-x_0)^{n+1}$$
    $$x_0=0\Downarrow$$
    $$p_n(x) = \sum_{k=0}^n(-1)^{k+1}\frac{(k-1)!}{k!}x^k$$
    $$p_n(x) = \sum_{k=0}^n(-1)^{k+1}\frac{x^k}{k}$$
    $$\Downarrow$$
    $$f_{(x)}= \sum_{k=0}^n(-1)^{k+1}\frac{x^k}{k} + R_n(x)$$
    $$n=2 \Downarrow$$
    $$f_{(x)}\approx x-\frac{x^2}{2} + R_n(x)$$
    $$f_{(x)}\approx x-\frac{x^2}{2} + \frac{2x^{3}}{3!(1+c)^3}$$
    $$f_{(x)}\approx x-\frac{x^2}{2} + \frac{x^{3}}{3(1+c)^3}$$
    $$x>0 \wedge x_0 = 0 < c < x \Rightarrow c>0$$
    $$\Downarrow$$
    $$0<\frac{x^{3}}{3(1+c)^3}<\frac{x^3}{3}$$
    $$\Downarrow$$
    $$x-\frac{x^2}{2}<\ln{(1+x)}<x-\frac{x^2}{2}+\frac{x^3}{3}$$
2.
    $$f_{(x)}=\ln{(\frac{1+x}{1-x})}$$
    $$f_{(x)}=\ln{(1+x)} - \ln{(1-x)}$$
    $$y_{(x)}=\ln{(1+x)}$$
    $$g_{(x)}=\ln{(1-x)}$$
    $$\Downarrow$$
    $$p_{y_n}(x) = \sum_{k=0}^n(-1)^{k+1}\frac{x^k}{k}$$
    $$R_{y_n}(x) = (-1)^{n}\frac{c^{n+1}}{n+1}$$
    $$g^{(1)}_{(x)} = -\frac{1}{1-x}$$
    $$g^{(2)}_{(x)} = -\frac{1}{(1-x)^2}$$
    $$g^{(3)}_{(x)} = -\frac{2}{(1-x)^3}$$
    $$\Downarrow$$
    $$g^{(k)}_{(x)} = -\frac{(k-1)!}{(1-x)^k}$$
    $$g^{(k)}_{(0)} = -\frac{(k-1)!}{(1-0)^k}=-(k-1)!$$
    $$p_{g_n}(x) = \sum_{k=0}^n\frac{g^{(k)}(x_0)}{k!}(x-x_0)^k$$
    $$R_{g_n}(x) = \frac{g^{(n+1)}(c)}{(n+1)!}(x-x_0)^{n+1}$$
    $$x_0=0\Downarrow$$
    $$p_{g_n}(x) = \sum_{k=0}^n-\frac{(k-1)!}{k!}x^k$$
    $$p_{g_n}(x) = \sum_{k=0}^n-\frac{x^k}{k}$$
    $$R_{g_n}(x) = \frac{-\frac{n!}{(1-c)^{n+1}}}{(n+1)!}x^{n+1}$$
    $$R_{g_n}(x) = \frac{-\frac{1}{(1-c)^{n+1}}}{n+1}x^{n+1}$$
    $$R_{g_n}(x) = -\frac{x^{n+1}}{(n+1)(1-c)^{n+1}}$$
    $$f_{(x)}=\ln{(1+x)} - \ln{(1-x)} \Downarrow$$
    $$f_{(x)}=\sum_{k=0}^n((-1)^{k+1}\frac{x^k}{k} - (- \frac{x^k}{k})) + R_n(x)$$
    $$f_{(x)}=\sum_{k=0}^{2n}2\frac{x^{2k + 1}}{2k + 1} + R_n(x)$$

    
3.
    צ"ל:

    $$e^{(-\frac{1}{2})} = ? (10^{-3})$$
    פתרון:

    $$f_{(x)}=e^x$$
    $$x=-\frac{1}{2}$$
    $$x_0=0$$
    $$f_{(x)}^{(k)} = e^x$$
    $$f_{(0)}^{(k)} = 1$$
    $$p_{n}(x)=\sum_{k=0}^n\frac{f_{(0)}^{(k)}}{k!}x^k=1+x+\frac{x^2}{2}+...+\frac{x^n}{n!}$$
    $$R_n(x)=\frac{f^{(n+1)}(c)}{(n+1)!}x^{n+1} = \frac{e^c}{(n+1)!}x^{n+1}$$
    $$-\frac{1}{2}<c<0$$
    $$R_n(x)>\frac{e^{(-\frac{1}{2})}}{(n+1)!}(-\frac{1}{2})^{n+1}$$
    $$R_n(x)>\frac{1}{e^{\frac{1}{2}}2^{n+1}(n+1)!}(-1)^{n+1}>\frac{1}{3^{\frac{1}{2}}2^{n+1}(n+1)!}$$
    $$\Downarrow$$
    $$\frac{1}{3^{\frac{1}{2}}2^{n+1}(n+1)!}<10^{-3}$$
    $$n=4 \Downarrow$$
    $$\frac{1}{6650}<10^{-3}$$
    $$\Downarrow$$
    $$p_4(x) = 1+x+\frac{x^2}{2!}+\frac{x^3}{3!}+\frac{x^4}{4!}$$
    $$x=-\frac{1}{2} \Downarrow$$
    $$p_4(x) = 1-\frac{1}{2}+\frac{1}{4\cdot 2!}-\frac{1}{8\cdot 3!}+\frac{1}{16\cdot 4!}$$
    $$e^{-\frac{1}{2}}\approx \underline{0.606}770833$$
    $$e^{-\frac{1}{2}}=\underline{0.606}53065971$$

4.
    1.
        $$\lim_{x \rightarrow 0}\frac{e^x \sin(x) -x(1+x)}{x^3}$$
        $$f_{(x)} = e^x = 1+ x + \frac{x^2}{2!} + R_{f_{(x)}}(x)$$
        $$g_{(x)} = \sin(x) = x - \frac{x^3}{3!} + R_{g_{(x)}}(x)$$
        $$\Downarrow$$
        $$\lim_{x \rightarrow 0}\frac{(1+ x + \frac{x^2}{2!} + R_{f_{(x)}}(x))(x - \frac{x^3}{3!} + R_{g_{(x)}}(x)) -x(1+x)}{x^3}$$
        $$\lim_{x \rightarrow 0}\frac{x - \frac{x^3}{6} + R_{g_{(x)}}(x) + x^2 - \frac{x^4}{6} + xR_{g_{(x)}}(x) + \frac{x^3}{2} - \frac{x^5}{12} +\frac{x^2}{2}R_{g_{(x)}}(x) xR_{f_{(x)}}(x) -\frac{x^3}{6}R_{f_{(x)}}(x) +R_{f_{(x)}}(x)R_{g_{(x)}}(x) -x-x^2}{x^3}$$
        $$\lim_{x \rightarrow 0}-\frac{1}{6} \cancel{-\frac{x}{6}} + \frac{1}{2} \cancel{-\frac{x^2}{12}}$$
        $$\lim_{x \rightarrow 0}\frac{1}{2}-\frac{1}{6} = \frac{1}{3}$$
    2.
        $$\lim_{n \rightarrow \infty}n^3(\ln(1+\frac{1}{n}) -\frac{1}{n} + \frac{1}{2n^2})$$
        $$f_{(x)} = \ln(1+x)$$
        $$f_{(x)} = x-\frac{x^2}{2}+\frac{x^3}{3}+R_n(x)$$
        $$\Downarrow x=\frac{1}{n}$$
        $$\lim_{n \rightarrow \infty}n^3(\frac{1}{n} -\frac{1}{2n^2} + \frac{1}{6n^3} + R_n(\frac{1}{n})  -\frac{1}{n} + \frac{1}{2n^2})$$
        $$\lim_{n \rightarrow \infty}n^3(\frac{1}{3n^3} + R_n(\frac{1}{n}))$$
        $$\lim_{n \rightarrow \infty}\frac{1}{3} + n^3 R_n(\frac{1}{n})$$
        המעלה של $R_n(\frac{1}{n})$ נמוכה מ $-4$ ולכן הביטוי $n^3 R_n(\frac{1}{n})$ שואף ל-0.

        $$\Downarrow$$
        $$\lim_{n \rightarrow \infty}\frac{1}{3} + \cancel{n^3 R_n(\frac{1}{n})} = \frac{1}{3}$$
5.
    $$f_{(x)} = \frac{(x-1)^3}{(x+1)^2}$$
    $$f_{(x)}^{(1)} = \frac{3(x-1)^2(x+1)^2 - 2(x-1)^3(x+1)}{(x+1)^4}$$
    $$f_{(x)}^{(1)} = \frac{3(x-1)^2(x+1) - 2(x-1)^3}{(x+1)^3}$$
    $$f_{(x)}^{(1)} = \frac{(x-1)^2(3(x+1) - 2(x-1))}{(x+1)^3}$$
    $$f_{(x)}^{(1)} = \frac{(x-1)^2(x+5)}{(x+1)^3}$$

    $$f_{(x)}^{(1)} = 0 \Rightarrow x=1,\ x=-5$$
    נקודות חשודות לנקודות קיצון: $x=1,\ x=-5$, נבדוק אם אכן מינימום\מקסימום אזורי אם הנגזרת השנייה עולה או יורדת בנקודות אלו:  

    $$f_{(x)}^{(2)} = \frac{(x-1)(2(x+5) + (x-1))(x+1)^3 - 3(x-1)^2(x+5)(x+1)^2}{(x+1)^6}$$
    $$f_{(x)}^{(2)} = \frac{(x-1)(3x+9)(x+1) - 3(x-1)^2(x+5)}{(x+1)^4}$$
    $$f_{(x)}^{(2)} = \frac{3(x-1)(x+3)(x+1) - 3(x-1)^2(x+5)}{(x+1)^4}$$
    $$f_{(x)}^{(2)} = \frac{3(x-1)((x+3)(x+1) - (x-1)(x+5))}{(x+1)^4}$$
    $$f_{(x)}^{(2)} = \frac{3(x-1)(x^2+4x+3 -x^2-4x+5)}{(x+1)^4}$$
    $$f_{(x)}^{(2)} = \frac{24(x-1)}{(x+1)^4}$$
    $$\Downarrow$$
    $$f_{(x=1)}^{(2)} = \frac{24(1-1)}{(1+1)^4} = 0$$
    $$f_{(x=-5)}^{(2)} = \frac{24(-5-1)}{(-5+1)^4} = \frac{-24 \cdot 6}{4^4} = -0.5625 < 0$$
    
    ז"א $x=-5$ זו נקודת מקסימום מקומי, $x=1$ זו נקודת פיתול

    כעת נמצא נקודות אי רציפות וצורתה:  

    $$f_{(x)} = \frac{(x-1)^3}{(x+1)^2}$$
    $$x=-1$$
    $$\Downarrow$$
    $$\lim_{x \rightarrow -1} \frac{(x-1)^3}{(x+1)^2}$$
    $$z = x+1 \Rightarrow z \rightarrow 0 \Downarrow$$
    $$\lim_{z \rightarrow 0} \frac{(z-2)^3}{z^2}$$
    $$\lim_{z \rightarrow 0} \frac{(z-2)(z^2-4z+4)}{z^2}$$
    $$\lim_{z \rightarrow 0} \frac{z^3-4z^2+4z -2z^2+8z-8}{z^2}$$
    $$\lim_{z \rightarrow 0} \frac{\cancel{z^3-6z^2+12z}-8}{z^2} = -\infty$$
    אסימפטוטה אנכית ב$x=-1$ כאשר הפונקציה שואפת ל$-\infty$ משני צידיה.

    כעת נמצא אסימפטוטה אופקית מהצורה
    
    $$y=ax-b$$
    $$a = \lim_{x \rightarrow \infty \pm}\frac{f_{(x)}}{x}$$
    $$a = \lim_{x \rightarrow \infty \pm}\frac{(x-1)^3}{x(x+1)^2}$$
    $$a = \lim_{x \rightarrow \infty \pm}\frac{x^3 \cancel{+ ...}}{x^3 \cancel{+ ...}} = 1$$
    $$b = \lim_{x \rightarrow \infty \pm}f_{(x)} - x$$
    $$b = \lim_{x \rightarrow \infty \pm}\frac{(x-1)^3}{(x+1)^2} - x$$
    $$b = \lim_{x \rightarrow \infty \pm}\frac{(x-1)^3-x(x+1)^2}{(x+1)^2}$$
    $$b = \lim_{x \rightarrow \infty \pm}\frac{(x-1)(x^2-2x+1)-x(x^2+2x+1)}{(x+1)^2}$$
    $$b = \lim_{x \rightarrow \infty \pm}\frac{x^3-2x^2+x -x^2+2x-1-x^3-2x^2-x}{(x+1)^2}$$
    $$b = \lim_{x \rightarrow \infty \pm}\frac{-2x^2+x -x^2+2x-1-2x^2-x}{(x+1)^2}$$
    $$b = \lim_{x \rightarrow \infty \pm}\frac{-5x^2+2x-1}{(x+1)^2} = -5$$
    
    אסימפטוטה אופקית ב$y=x-5$.

6.
    1.
        $$\int\frac{1}{e^{2x} + e^x}\delta x$$
        $$t = e^x$$
        $$\delta t = \delta x\ e^x = \delta x\ t \Rightarrow \delta x = \delta t \frac{1}{t}$$
        $$\Downarrow$$
        $$\int\frac{1}{t^2 + t}\delta t \frac{1}{t}$$
        $$\int\frac{1}{t^2(t + 1)}\delta t$$
        $$\frac{1}{t^2(t + 1)} = \frac{A}{t} + \frac{B}{t^2} + \frac{C}{t+1}$$
        $$\Downarrow$$
        $$1 = At^2(t+1)+B(t+1)+Ct^2$$
        $$t=0 \Rightarrow B = 1$$
        $$t=-1 \Rightarrow C = 1$$
        $$t=1 \Rightarrow 1 = 2A+2B+C \Rightarrow A= -1$$
        $$\Downarrow$$
        $$\int-\frac{1}{t}+\int\frac{1}{t^2}+\int\frac{1}{t+1} + C$$
        $$-\ln(t)-\frac{1}{t}+\ln(t+1) + C$$
        $$t=e^x \Downarrow$$
        $$\ln(e^x+1)-x-\frac{1}{e^x} + C$$
    2.
        $$\int \sin x \cdot \ln (\cos x + 1) \delta x$$
        $$t = \cos x + 1 \rightarrow \delta t  = -\sin{x} \delta x$$
        $$-\int \ln (t) \delta t$$
        $$u\delta v = uv -\int \delta u v$$
        $$u = \ln (t)$$
        $$\delta u = \frac{1}{t} \delta t$$
        $$v = t$$
        $$\delta v = \delta t$$
        $$\Downarrow$$
        $$-t\ln (t)+\int\frac{1}{t}t \delta t$$
        $$-t\ln (t)+t +C$$
        $$t(1-\ln (t))+C$$
        $$t = \cos x + 1 \Downarrow$$
        $$(\cos x + 1)(1-\ln (\cos x + 1))+C$$
    3.
        $$\int \frac{1}{x^2} \arctan (x) \delta x$$
        $$u=\arctan x$$
        $$\delta u=\frac{1}{x^2 + 1} \delta x$$
        $$\delta v=\frac{1}{x^2} \delta x$$
        $$v=-\frac{1}{x}$$
        $$\Downarrow$$
        $$-\frac{\arctan x}{x}+\int\frac{1}{x}\frac{1}{x^2 + 1} \delta x$$
        $$-\frac{\arctan x}{x}+\int\frac{1}{x}\frac{1}{x^2 + 1} \delta x$$
        $$\frac{1}{x}\frac{1}{x^2 + 1} = \frac{A}{x} + \frac{Bx+C}{x^2+1}$$
        $$\Downarrow$$
        $$A(x^2+1)+x(Bx+C) = 1$$
        $$x=0 \rightarrow A=1$$
        $$x=1 \rightarrow 2+B+C=1$$
        $$x=-1 \rightarrow 2+B-C=1$$
        $$C=0$$
        $$B=-1$$
        $$\Downarrow$$
        $$-\frac{\arctan x}{x}+\int\frac{1}{x}\delta x + \int\frac{-x}{x^2+1} \delta x +C$$
        $$-\frac{\arctan x}{x}+\int\frac{1}{x}\delta x -\frac{1}{2} \int\frac{2x}{x^2+1} \delta x +C$$
        $$-\frac{\arctan x}{x}+\ln|x| -\frac{1}{2} \ln|x^2+1| +C$$
        $$-\frac{\arctan x}{x}+\ln|\frac{x}{\sqrt[]{x^2+1}}|+C$$
    4.
        $$\int \frac{e^{\sqrt[4]{x}}}{\sqrt[]{x}}\delta x$$
        $$x=t^4 \rightarrow \delta x = 4t^3 \delta t$$
        $$\int 4t^3\frac{e^t}{t^2}\delta t$$
        $$\int 4t e^t \delta t$$
        $$4\int t e^t \delta t$$
        $$u=t$$
        $$\delta u=\delta t$$
        $$v=e^t$$
        $$\delta v=e^t \delta t$$
        $$\Downarrow$$
        $$4(te^t-\int e^t \delta t)+ C$$
        $$4(te^t-e^t)+ C$$
        $$4e^t(t-1)+ C$$
        $$x=t^4 \rightarrow t= \sqrt[4]{x}$$
        $$4e^{\sqrt[4]{x}}(\sqrt[4]{x}-1)+ C$$
    5.
        $$\int \tan^3(x) \delta x$$
        $$\int \frac{\sin^3(x)}{\cos^3(x)} \delta x$$
        $$t=\cos{x} \rightarrow \delta t = -\sin (x) \delta x$$
        $$\int -\frac{\sin^3(x)}{t^3 \sin (x)} \delta t$$
        $$\int -\frac{\sin^2(x)}{t^3} \delta t$$
        $$\int -\frac{1-\cos^2(x)}{t^3} \delta t$$
        $$\int -\frac{1-t^2}{t^3} \delta t$$
        $$\int \frac{t^2-1}{t^3} \delta t$$
        $$\int \frac{t^2-1}{t^3} \delta t$$
        $$\int (\frac{1}{t} \delta t) -\int (\frac{1}{t^3} \delta t)$$
        $$\ln|t| +\frac{1}{2t^2} +C$$
        $$t=\cos{x} \Downarrow$$
        $$\ln|\cos{x}| +\frac{1}{2\cos^2{x}}+C$$
        
    6.
        $$\int \frac{x}{1+\sqrt[]{x}}\delta x$$
        $$x = t^2 \rightarrow \delta x = 2t\delta t$$
        $$\int \frac{t^2}{1+t}2t\delta t$$
        $$2\int \frac{t^3}{1+t}\delta t$$