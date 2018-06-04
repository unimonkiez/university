<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>

### מטלה 4 חדו"א - יובל סרף
1. $$f_{(x)} = \{ x^n \cdot \arctan{\frac{1}{x}}|x\neq 0, 0|x=0\}$$

    $$g_{(x)} = x^n \cdot \arctan{\frac{1}{x}}$$
    נבדוק עבור אילו ערכים הפונקציה רציפה קודם כל:  

    $$\lim_{x \rightarrow 0+}g_{(x)} = f_{(x = 0)}$$
    $$\lim_{x \rightarrow 0+}x^n \cdot \arctan{\frac{1}{x}} = 0$$
    $$\lim_{x \rightarrow 0+}x^n \cdot \frac{\pi}{2} = 0$$
    אכן רציפה בנקודה $x=0$ מכיוון ששואפת ל0.  
    כעת נבדוק אם $\lim_{x \rightarrow 0+}g'_{(x)} = 0$  

    $$\lim_{x \rightarrow 0+}g'_{(x)} = 0$$
    $$\lim_{x \rightarrow 0+}nx^{n-1}\cdot \arctan{\frac{1}{x}} + x^n\frac{\frac{-1}{x^2}}{1+\frac{1}{x^2}} = 0$$
    $$\lim_{x \rightarrow 0+}nx^{n-1}\cdot \arctan{\frac{1}{x}} + xx^{n-1}\frac{\frac{-1}{x^2}}{1+\frac{1}{x^2}} = 0$$
    $$\lim_{x \rightarrow 0+}x^{n-1}(n\cdot \arctan{\frac{1}{x}} + x\frac{\frac{-1}{x^2}}{1+\frac{1}{x^2}}) = 0$$
    $$\lim_{x \rightarrow 0+}x^{n-1}(\frac{n\arctan{\frac{1}{x}}+\frac{n}{x^2}\arctan{\frac{1}{x}}+x+\frac{1}{x}-\frac{1}{x^2}}{1+\frac{1}{x^2}}) = 0$$
    $$\Downarrow$$
    כל הביטוי ישאף ל-0 רק כאשר $n\neq 1$, כי אז $\lim_{x \rightarrow 0+}x^0 = 1$, והשבר ישאף גם הוא ל0 רק כאשר $n=0$, אך פתרון זה כבר נכלל במרחב הפתרונות של $n\neq1$
    
2. $$\cos^y{x} + e^{xy} + y = 3$$
    $$\Downarrow$$
    $$(\cos^y{x})'+(xy)'e^{xy}+y'=0$$
    $$(e^{\ln{(\cos^y{x})}})'+(y + xy')e^{xy}+y'=0$$
    $$(e^{y\ln{(\cos{x})}})'+(y + xy')e^{xy}+y'=0$$
    $$(y\ln{(\cos{x})})'e^{y\ln{(\cos{x})}}+(y + xy')e^{xy}+y'=0$$
    $$(y\frac{-\sin{x}}{\cos{x}} + y'\ln{(\cos{x})})e^{y\ln{(\cos{x})}}+(y + xy')e^{xy}+y'=0$$
    $$y\frac{-\sin{x}}{\cos{x}}e^{y\ln{(\cos{x})}}+ye^{xy}=-y'\ln{(\cos{x})}e^{y\ln{(\cos{x})}}-xy'e^{xy}-y'$$
    $$y'\ln{(\cos{x})}e^{y\ln{(\cos{x})}}+xy'e^{xy}+y'=y\frac{\sin{x}}{\cos{x}}e^{y\ln{(\cos{x})}}-ye^{xy}$$
    $$y'(\ln{(\cos{x})}e^{y\ln{(\cos{x})}}+xe^{xy}+1)=y\frac{\sin{x}}{\cos{x}}e^{y\ln{(\cos{x})}}-ye^{xy}$$
    $$y'=\frac{y(\tan{(x)}e^{y\ln{(\cos{x})}}-e^{xy})}{\ln{(\cos{x})}e^{y\ln{(\cos{x})}}+xe^{xy}+1}$$
    $$x=0 \Downarrow f_{(x=0)}$$
    $$\cos^y{x} + e^{xy} + y = 3$$
    $$1 + 1 + y = 3$$
    $$y = 1$$
    כעת נחשב את $y'_{(x=0, y=1)}$ ואז נוכל לחשב את משוואת המשיק -  

    $$y=1 \Downarrow f'_{(y=1)}$$
    $$y'=\frac{0-e^{x}}{\ln{(\cos{x})}e^{\ln{(\cos{x})}}+xe^{x}+1}$$
    $$y'=\frac{\tan{(x)}\cos{x}-e^{x}}{\ln{(\cos{x})}\cos{x}+xe^{x}+1}$$
    $$y'=\frac{\sin{x}-e^{x}}{\ln{(\cos{x})}\cos{x}+xe^{x}+1}$$
    $$x=0 \Downarrow$$
    $$y'=\frac{0-1}{0\cdot 1+0+1} = -1$$
    $$\Downarrow$$
    $$\frac{y-1}{x-0} = -1$$
    $$y=1-x$$

3. $$g_{(x)} = (1-x^2)f_{(x)}$$
    הפונקציה $g_{(x)}$ גם כן גזירה ורציפה בקטע $[-1, 1]$ מכיוון שהיא הרכבה של 2 פונקציות רציפות (אחת נתון השנייה אלמנטרית).  
    בנוסף:  
    
    $$g(-1) = (1-(-1)^2)f_{(x)} = 0\cdot f_{(x)} = 0$$
    $$g(1) = (1-1^2)f_{(x)} = 0\cdot f_{(x)} = 0$$

    $g_{(1)} = g_{(-1)}$, ולכן, עפ"י משפט רול, קיימת נקודה $c$ כאשר $-1<c<1$ כך ש-$g'(c) = 0$, מש"ל.

4.  
    1. צ"ל: $(a-b)e^{-a}<e^{-b} - e^{-a}<(a-b)e^{-b}$  
        
        נגדיר $f_{(x)} = e^{-x}$, רציפה וגזירה לכל $x$, בפרט בקטע $[a, b]$.  
        לפי משפט לגרנג', אז קיימת נקודה $c$ כך ש-$a<c<b$ וגם $f'_{(c)}=\frac{f_{(b)} - f_{(a)}}{b-a}$

        $$f'_{(c)}=\frac{f_{(b)} - f_{(a)}}{b-a}$$
        $$-e^{-c}=\frac{e^{-b} - e^{-a}}{b-a}$$
        $$e^{-c}=\frac{e^{-b} - e^{-a}}{a-b}$$
        $$a<c<b$$
        $$\Downarrow$$
        $$e^a<e^c<e^b$$
        $$e^{-b}<e^{-c}<e^{-a}$$
        $$\Downarrow$$
        $$e^{-b}<\frac{e^{-b} - e^{-a}}{a-b}<e^{-a}$$
        $$(a-b)e^{-a}<e^{-b} - e^{-a}<(a-b)e^{-b}$$

        מש"ל

    2. צ"ל: $\frac{x}{1+x}<\ln{(1+x)}<x$, לכל $x>0$

        נגדיר $f_{(x)} = ln{(1+x)}$, רציפה וגזירה לכל $x\geq 0$, בפרט בקטע $[1, x]$.  
        לפי משפט לגרנג', אז קיימת נקודה $c$ כך ש-$0<c<x$ וגם $f'_{(c)}=\frac{f_{(x)} - f_{(0)}}{x-0}$

        $$f'_{(c)}=\frac{f_{(x)} - f_{(0)}}{x-0}$$
        $$\frac{1}{1+c}=\frac{\ln{(1+x)} - 0}{x-0}$$
        $$\frac{1}{1+c}=\frac{\ln{(1+x)}}{x}$$
        $$1+c=\frac{x}{\ln{(1+x)}}$$
        $$0<c<x$$
        $$1<1+c<1+x$$
        $$\Downarrow$$
        $$1<\frac{x}{\ln{(1+x)}}<1+x$$
        $$\frac{1}{1+x}<\frac{\ln{(1+x)}}{x}<1$$
        $$\frac{x}{1+x}<\ln{(1+x)}<x$$

        מש"ל
5.  
6. 
    1. $$\lim_{x \rightarrow 0}\frac{\ln{(\cos{(\arcsin{x})})}}{x\cdot\cos{x}\cdot e^x}$$
    $$(\frac{0}{0}) \Downarrow (Lupital)$$
    $$\lim_{x \rightarrow 0}\frac{\frac{-\sin{(\arcsin{x})}\frac{1}{\sqrt[]{1-x^2}}}{\cos{(\arcsin{x})}}}{\cos{x}\cdot e^x-x\sin{x}e^x+x\cos{x}e^x}$$
    $$\lim_{x \rightarrow 0}\frac{\frac{\frac{-x}{\sqrt[]{1-x^2}}}{\cos{(\arcsin{x})}}}{e^x(\cos{x}-x\sin{x}+x\cos{x})}$$
    $$\lim_{x \rightarrow 0}\frac{-x}{\sqrt[]{1-x^2}\cos{(\arcsin{x})}e^x(\cos{x}-x\sin{x}+x\cos{x})} = \frac{0}{1 \cdot 1 \cdot 1(1 - 0 + 0)} = 0$$
    
    2. $$\lim_{x \rightarrow 0^+}x^{\sin{x}}$$
    $$\lim_{x \rightarrow 0^+}e^{\ln{(x^{\sin{x}})}}$$
    $$e^{\lim_{x \rightarrow 0^+}\ln{(x^{\sin{x}})}}$$
    $$\Downarrow$$
    $$\lim_{x \rightarrow 0^+}\ln{(x^{\sin{x}})}$$
    $$\lim_{x \rightarrow 0^+}\sin{x}\cdot \ln{x}$$
    $$\lim_{x \rightarrow 0^+}\frac{\ln{x}}{\frac{1}{\sin{x}}}$$
    $$(\frac{0}{0}) \Downarrow (Lupital)$$
    $$\lim_{x \rightarrow 0^+}\frac{\frac{1}{x}}{\frac{-\cos{x}}{\sin^2{x}}}$$
    $$\lim_{x \rightarrow 0^+}\frac{\sin^2{x}}{-x\cos{x}}$$
    $$\lim_{x \rightarrow 0^+}\cancel{\frac{\sin{x}}{x}}\frac{\sin{x}}{-\cos{x}} = 0$$
    $$\Downarrow$$
    $$\lim_{x \rightarrow 0^+}x^{\sin{x}} = e^0 = 1$$

    3. $$\lim_{x \rightarrow \infty}(e^{3x}-5x)^{\frac{1}{x}}$$
    $$\lim_{x \rightarrow \infty}e^{\ln{(e^{3x}-5x)^{\frac{1}{x}}}}$$
    $$\lim_{x \rightarrow \infty}e^{\frac{1}{x}\ln{(e^{3x}-5x)}}$$
    $$\lim_{x \rightarrow \infty}e^{\frac{\ln{(e^{3x}-5x)}}{x}} = e^{\lim_{x \rightarrow \infty}\frac{\ln{(e^{3x}-5x)}}{x}}$$
    $$\Downarrow$$
    $$\lim_{x \rightarrow \infty}\frac{\ln{(e^{3x}-5x)}}{x}$$
    $$(\frac{\infty}{\infty}) \Downarrow (Lupital)$$
    $$\lim_{x \rightarrow \infty}\frac{3e^{3x}-5}{e^{3x}-5x}$$
    $$\lim_{x \rightarrow \infty}\frac{e^{3x}(3-\frac{5}{e^{3x}})}{e^{3x}(1-\frac{5x}{e^{3x}})} = 3$$
    $$\Downarrow$$
    $$\lim_{x \rightarrow \infty}(e^{3x}-5x)^{\frac{1}{x}} = e^3$$

    4. $$\lim_{x \rightarrow \frac{\pi}{4}}\frac{\sqrt[3]{\tan{x}} - 1}{2\sin^2{x} - 1}$$
    $$(\frac{0}{0}) \Downarrow (Lupital)$$
    $$\lim_{x \rightarrow \frac{\pi}{4}}\frac{(\tan^{\frac{1}{3}}{x})'}{(2\sin^2{x})'}$$
    $$\lim_{x \rightarrow \frac{\pi}{4}}\frac{\frac{1}{3tan^{\frac{2}{3}}{x}\cos^2{x}}}{4\sin{x}\cos{x}}$$
    $$\lim_{x \rightarrow \frac{\pi}{4}}\frac{1}{3tan^{\frac{2}{3}}{x}\cos^2{x}4\sin{x}\cos{x}}$$
    $$\lim_{x \rightarrow \frac{\pi}{4}}\frac{1}{12tan^{\frac{2}{3}}{x}\cos^3{x}\sin{x}}$$
    $$\lim_{x \rightarrow \frac{\pi}{4}}\frac{1}{12\cos^{\frac{7}{3}}{x}\sin^{\frac{5}{3}}{x}}$$
    $$\lim_{x \rightarrow \frac{\pi}{4}}(\frac{1}{12^3\cos^7{x}\sin^5{x}})^{\frac{1}{3}}$$
    $$\lim_{x \rightarrow \frac{\pi}{4}}(\frac{1}{2^{\frac{1}{5}}12^3\cos^2{x}(2\cos{x}\sin{x})^5})^{\frac{1}{3}}$$
    $$2\cos{x}\sin{x} = \sin{(2x)}$$
    $$\Downarrow$$
    $$\lim_{x \rightarrow \frac{\pi}{4}}(\frac{1}{2^{\frac{1}{5}}12^3\cos^2{x}\sin^5{(2x)}})^{\frac{1}{3}}$$
    $$\lim_{x \rightarrow \frac{\pi}{4}}\frac{1}{2^{\frac{1}{15}}12\cos^{\frac{2}{3}}{x}\sin^{\frac{5}{3}}{(2x)}}$$
    $$\lim_{x \rightarrow \frac{\pi}{4}}\frac{1}{2^{\frac{1}{15}}\cdot 12\cdot 1^{\frac{2}{3}}\cdot 1^{\frac{5}{3}}}=\frac{1}{12\cdot 2^{\frac{1}{15}}}$$
    