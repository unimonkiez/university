<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>

### מטלה 2 חדו"א 2 - יובל סרף
1.
    $$f_{n(x)} = (1+\frac{1}{n})x^2$$
    נמצא את פונקציית הגבול:  
    
    $$\forall x \in [0,1]: f_{(x)} = \lim_{n \rightarrow \infty}f_n (x)$$
    $$f_{(x)} = \lim_{n \rightarrow \infty}(1+\frac{1}{n})x^2 = x^2$$
    נבדוק התכנסות במ"ש

    $$\forall x \in [0,1]: |f_{n(x)} - f_{(x)}|<\epsilon$$
    $$|(1+\frac{1}{n})x^2 - x^2|<\epsilon$$
    $$|\frac{1}{n}x^2|<\epsilon$$
    $$\Downarrow$$
    $$\forall x \in [0,1]: |\frac{1}{n}x^2| \leq \frac{1}{n} < \epsilon$$
    ואכן, עבור כל $\epsilon>0$ נוכל לקחת $n_0>\frac{1}{\epsilon}$, ואז לכל $n>n_0$ נקבל את הנדרש.
2.
    $$\sum_{k=1}^{\infty}x^k(1-x)^k$$
3.
    1.
        $$\sum_{n=1}^{\infty}\frac{1}{n\cdot 2^n}x^n$$
        $$a_n = \frac{1}{n\cdot 2^n}$$
        $$R = \frac{1}{\overline{\lim_{n \rightarrow \infty}} \sqrt[n]{|a_n|}}$$
        $$\overline{\lim_{n \rightarrow \infty}} \sqrt[n]{|a_n|}$$
        $$\overline{\lim_{n \rightarrow \infty}} \sqrt[n]{\frac{1}{n\cdot 2^n}}$$
        $$\overline{\lim_{n \rightarrow \infty}} \sqrt[n]{\frac{1}{n}}\cdot \frac{1}{2} = \frac{1}{2}$$
        $$\Downarrow$$
        $$R = 2$$
        נבדוק אם תחום ההתכנסות פתוח או סגור ע"י הצבת $R$: 
        
        $$\sum_{n=1}^{\infty}\frac{1}{n\cdot 2^n}2^n$$
        $$\sum_{n=1}^{\infty}\frac{1}{n}$$
        מתבדר ב$x_0 = 2$.
        כעת נבדוק $x_0 = -2$:  
   
        $$\sum_{n=1}^{\infty}\frac{1}{n\cdot 2^n}(-2)^n$$
        $$\sum_{n=1}^{\infty}\frac{1}{n}(-1)^n$$
        לפי לייבניץ, מתכנס.  
        הטור מכתנס בתחום $[-2,2)$.
    2.
        $$\sum_{n=1}^{\infty}(-1)^n\frac{1}{(n+1)\ln(n+1)}(x-2)^n$$
        $$a_n = \frac{1}{(n+1)\ln(n+1)}$$
        $$R = \frac{1}{\lim_{n \rightarrow \infty} |\frac{a_{n+1}}{a_n}|}$$
        $$\lim_{n \rightarrow \infty} |\frac{a_{n+1}}{a_n}|$$
        $$\lim_{n \rightarrow \infty}\frac{(n+1)\ln(n+1)}{(n+2)\ln(n+2)}$$
        $$\Downarrow \frac{\infty}{\infty}L$$
        $$\lim_{n \rightarrow \infty}\frac{\ln(n+1) + \frac{n+1}{n+1}}{\ln(n+2) + \frac{n+2}{n+2}}$$
        $$\lim_{n \rightarrow \infty}\frac{\ln(n+1) + 1}{\ln(n+2) + 1}$$
        $$\Downarrow \frac{\infty}{\infty}L$$
        $$\lim_{n \rightarrow \infty}\frac{\frac{1}{n+1}}{\frac{1}{n+2}} = 1$$
        $$\Downarrow$$
        $$R = 1$$
        בנוסף $c=2$, לכן הקצוות הם $x = 1,3$ כעת נבדוק אותם: 

        $$x_0 = 3$$
        $$\sum_{n=1}^{\infty}(-1)^n\frac{1}{(n+1)\ln(n+1)}(3-2)^n$$
        $$\sum_{n=1}^{\infty}(-1)^n\frac{1}{(n+1)\ln(n+1)}$$
        כעת נבדוק לפי ליבניץ את הגבול של $a_n = \frac{1}{(n+1)\ln(n+1)}$:  

        $$\lim_{n \rightarrow \infty}\frac{1}{(n+1)\ln(n+1)} = 0$$
        ולכן הטור מתכנס ב-$x_0 = 3$
        
        $$x_0 = 1$$
        $$\sum_{n=1}^{\infty}(-1)^n\frac{1}{(n+1)\ln(n+1)}(1-2)^n$$
        $$\sum_{n=1}^{\infty}\frac{1}{(n+1)\ln(n+1)}\cancel{(-1)^{2n}}$$
        $$\sum_{n=1}^{\infty}\frac{1}{(n+1)\ln(n+1)}$$
        הסדרה חיובית, מוטונית יורדת ורציפה, נשתמש במבחן האינטגרל:  

        $$\Downarrow$$
        $$\int_{1}^{\infty}\frac{\delta x}{(n+1)\ln(n+1)}$$
        $$t = \ln (n+1)$$
        $$\delta t = \frac{1}{n+1}\delta x$$
        $$\delta x = (n+1)\delta t$$
        $$\Downarrow$$
        $$\int_{1}^{\infty}\frac{\cancel{(n+1)}\delta t}{\cancel{(n+1)}t}$$
        $$\int_{1}^{\infty}\frac{\delta t}{t}$$
        $$\ln(t)|_{1}^{\infty}$$
        $$\ln(\ln(n+1))|_{1}^{\infty}$$
        האינטגרל מתבדר, ולכן גם הטור מתבדר בנקודה $x_0 = 1$

        $$\Downarrow$$
        תחום ההתכנסות של הטור המקורי הינו $(1,3]$.
    3.
        $$\sum_{n=1}^{\infty}\frac{1}{2}^{n^2}x^n$$
        $$a_n = \frac{1}{2}^{n^2}$$
        $$R = \frac{1}{\lim_{n \rightarrow \infty} \sqrt[n]{|a_n|}}$$
        $$\lim_{n \rightarrow \infty} \sqrt[n]{|a_n|}$$
        $$\lim_{n \rightarrow \infty} \sqrt[n]{\frac{1}{2}^{n^2}}$$
        $$\lim_{n \rightarrow \infty} \frac{1}{2}^{n} = 0$$
        $$\Downarrow$$
        $$R \Rightarrow \infty$$

        תחום ההתכנסות של הטור הינו $\forall x\in R$.
    4.
        $$\sum_{n=1}^{\infty}2^{n^2}x^n$$
        $$a_n = 2^{n^2}$$
        $$R = \frac{1}{\lim_{n \rightarrow \infty} \sqrt[n]{|a_n|}}$$
        $$\lim_{n \rightarrow \infty} \sqrt[n]{|a_n|}$$
        $$\lim_{n \rightarrow \infty} \sqrt[n]{2^{n^2}}$$
        $$\lim_{n \rightarrow \infty} 2^{n} \Rightarrow \infty$$
        $$\Downarrow$$
        $$R = 0$$
        תחןם ההתכנסות רדיוס 0 סביב הנקודה $x_0 = 0$, נבדוק את הנקודה:  
        
        $$x_0 = 0$$
        $$\sum_{n=1}^{\infty}2^{n^2}0^n = 0$$

        תחום ההתכנסות של הטור הינו $x=0$ בלבד.

        