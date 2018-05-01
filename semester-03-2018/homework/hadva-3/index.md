<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>

### מטלה 3 חדו"א - יובל סרף
1. חשב את הגבולות הבאים:  
    1. $$\lim_{x \rightarrow -8}\frac{\sqrt[]{1 - x} - 3}{2+\sqrt[3]{x}}$$  
    פתרון:  

    $$x = t^3$$
    $$x \rightarrow -8 = t \rightarrow -2$$
    $$\lim_{t \rightarrow -2}\frac{\sqrt[]{1 - t^3} - 3}{2+\sqrt[3]{t^3}}$$  
    $$\lim_{t \rightarrow -2}\frac{\sqrt[]{1 - t^3} - 3}{2+t}$$  
    $$\lim_{t \rightarrow -2}\frac{(\sqrt[]{1 - t^3} - 3)(\sqrt[]{1 - t^3} + 3)}{(2+t)(\sqrt[]{1 - t^3} + 3)}$$  
    $$\lim_{t \rightarrow -2}\frac{1-t^3-9}{(2+t)(\sqrt[]{1 - t^3} + 3)}$$  
    $$\lim_{t \rightarrow -2}\frac{-t^3-8}{(2+t)(\sqrt[]{1 - t^3} + 3)}$$  
    $$\lim_{t \rightarrow -2}\frac{-(t^3+8)}{(2+t)(\sqrt[]{1 - t^3} + 3)}$$  
    $$\lim_{t \rightarrow -2}\frac{-(t+2)(t^2-2t+4)}{(2+t)(\sqrt[]{1 - t^3} + 3)}$$  
    $$\lim_{t \rightarrow -2}\frac{-t^2+2t-4}{\sqrt[]{1 - t^3} + 3} = \frac{-4-4-4}{\sqrt[]{1+8}+3} = \frac{-12}{6} = -2$$  

    2. $$\lim_{x \rightarrow 5}\frac{x^3-10x^2+25x}{x^4-50x^2+625}$$ 
    $$\lim_{x \rightarrow 5}\frac{x(x^2-10x+25)}{(x^2-25)^2}$$ 
    $$\lim_{x \rightarrow 5}\frac{x(x-5)^2}{((x+5)(x-5))^2}$$ 
    $$\lim_{x \rightarrow 5}\frac{x(x-5)^2}{(x+5)^2(x-5)^2}$$ 
    $$\lim_{x \rightarrow 5}\frac{x}{(x+5)^2} = \frac{5}{10^2} = \frac{1}{20}$$ 

    3. $$\lim_{x \rightarrow \frac{\pi}{4}}\frac{cos{x}-\sin{x}}{\cos{2x}}$$
    $$\lim_{x \rightarrow \frac{\pi}{4}}\frac{cos{x}-\sin{x}}{\cos^2{x}-\sin^2{x}}$$  
    $$\lim_{x \rightarrow \frac{\pi}{4}}\frac{cos{x}-\sin{x}}{(\cos{x}-\sin{x})(\cos{x}+\sin{x})}$$  
    $$\lim_{x \rightarrow \frac{\pi}{4}}\frac{1}{\cos{x}+\sin{x}}=\sqrt[]{\frac{1}{2}}$$

    4. $$\lim_{x \rightarrow \infty}\frac{\ln(1+\sqrt[]{x}+\sqrt[3]{x})}{\ln(1+\sqrt[4]{x}+\sqrt[3]{x})}$$
    $$\lim_{x \rightarrow \infty}\frac{\ln(\sqrt[]{x}(1+\frac{1}{\sqrt[]{x}}+\frac{\sqrt[3]{x}}{\sqrt[]{x}}))}{\ln(\sqrt[3]{x}(1+\frac{1}{\sqrt[3]{x}}+\frac{\sqrt[4]{x}}{\sqrt[3]{x}}))}$$
    $$\lim_{x \rightarrow \infty}\frac{\ln(x^{\frac{1}{2}}(1+x^{-\frac{1}{2}}+x^{-\frac{1}{6}}))}{\ln(x^{\frac{1}{3}}(1+x^{-\frac{1}{3}}+x^{-\frac{1}{12}}))}$$
    $$\lim_{x \rightarrow \infty}\frac{\ln{(x^{\frac{1}{2}})}+\ln(1+x^{-\frac{1}{2}}+x^{-\frac{1}{6}})}{\ln{(x^{\frac{1}{3}})}+\ln(1+x^{-\frac{1}{3}}+x^{-\frac{1}{12}})}$$
    $$\lim_{x \rightarrow \infty}\frac{\frac{1}{2}\ln{(x)}+\ln(1+x^{-\frac{1}{2}}+x^{-\frac{1}{6}})}{\frac{1}{3}\ln{(x)}+\ln(1+x^{-\frac{1}{3}}+x^{-\frac{1}{12}})} =
    \frac{\frac{1}{2}\ln{(x)}+\ln(1+0+0)}{\frac{1}{3}\ln{(x)}+\ln(1+0+0)}=
    \frac{\frac{1}{2}\ln{(x)}+0}{\frac{1}{3}\ln{(x)}+0}= \frac{\frac{1}{2}}{\frac{1}{3}} = \frac{3}{2}
    $$

    5. $$\lim_{x \rightarrow 0}(1+x^2)^{\cot^2{x}}$$  

    6. $$\lim_{x \rightarrow 3}(3x -8)^{\frac{x}{\sin{(3x-8)}}}$$  
2. $$f_{(x)} = \{ \frac{x^2+bx+c}{x-2}, x \neq 2 \ \ \ | \ \ \ 7, x =2 \}$$
    רציפה לכל $x$.  
    מצא את $b, c$.  

3. $$f_{(x)} = \{ \frac{ax^2-b}{x-1}, x > 1 \ \ \ | \ \ \ a+b, x =1 \ \ \ | \ \ \ \frac{\sqrt[]{x} - c}{x^2-1}, 0 \leq x < 1\}$$
    1. עבור אילו $a, b, c$ הפונקציה רציפה ב- $x=1$?
    2. עבור אילו $a, b, c$ לפונקציה יש אי-רציפות סליקה ב- $x=1$?
    3. עבור אילו $a, b, c$ לפונקציה יש "קפיצה" ב- $x=1$?
    4. עבור אילו $a, b, c$ לפונקציה יש אי-רציפות מסוג II ב- $x=1$?

4. תהיה $f_{(x)}$ רציפה בקטע $[0, 1]$ ונתון כי $f_{(x)}\in[0, 1]$ לכל $x\in [0, 1]$.  
הוכח כי קיימת נקודה $x_0\in [0, 1]$ כך ש: $2x_0+1 = e^{f_{(x)}}$.

5. יהיו $f_{(x)}$ ו-$g_{(x)}$ שתי פונקציות רציפות בקטע $[0, 1]$ המקיימות:  

    $$f_{(0)} = 2, g_{(0)} = -1, f_{(1)} = 3, g_{(1)} = -4$$
    הוכח שלמשוואה - $f^2_{(x)}=g^2_{(x)}$ יש לפחות פתרון אחד ב-$(0,1)$.

6. הוכח שלמשוואה $x^7+2x^3+\frac{x}{5}-e^{1-x} = 0$ קיים בדיוק פתרון ממשי אחד.