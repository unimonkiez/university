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
    $$n=3 \Downarrow$$
    $$f_{(x)}\approx x-\frac{x^2}{2}+\frac{x^3}{3} + R_n(x)$$