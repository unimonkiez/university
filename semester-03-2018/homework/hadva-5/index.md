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