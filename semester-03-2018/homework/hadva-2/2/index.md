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

4.
    1.
        $$f_{(x)} = \int_0^x e^{-t^2}\delta t$$
        $$f_{(x)}^{(1)} = e^{-x^2}$$
        $$f_{(x)}^{(2)} = -2x\cdot e^{-x^2}$$
    2.
        $$f_{(x)} = \frac{1}{4-x^2}$$
5.
    1.
        $$f_{(x)} = \ln (x+1)$$
        $$f_{(x)}^{(1)} = \frac{1}{x+1}$$
        $$f_{(x)}^{(2)} = -\frac{1}{(x+1)^2}$$
        $$f_{(x)}^{(3)} = \frac{2}{(x+1)^3}$$
        $$f_{(x)}^{(4)} = \frac{2\cdot 3}{(x+1)^4}$$
        $$\Downarrow$$
        $$f_{(x)}^{(k)} = (-1)^{k+1}\frac{(k-1)!}{(x+1)^k}$$
        $$f_{(x)} = \sum_{n=0}^{\infty}\frac{f^{(n)}_{(x_0)}}{n!}(x-x_0)^{n}$$
        $$\Downarrow$$
        $$\ln(x+1) = \cancel{\ln(1)}+\sum_{n=1}^{\infty}\frac{(-1)^{n+1}\frac{(n-1)!}{(x_0+1)^n}}{n!}(x-x_0)^{n}$$
        $$\ln(x+1) = \sum_{n=1}^{\infty}(-1)^{n+1}\frac{1}{n(x_0+1)^n}(x-x_0)^{n}$$
        $$\Downarrow x_0 = 0$$
        $$\ln(x+1) = \sum_{n=1}^{\infty}(-1)^{n+1}\frac{1}{n(1)^n}x^{n}$$
        $$\ln(x+1) = \sum_{n=1}^{\infty}(-1)^{n+1}\frac{1}{n}x^{n}$$
        כעת מכיוון שמדובר בטור חזקות, נחשב את רדיוס ההתכנסות: 

        $$a_n = (-1)^{n+1}\frac{1}{n}$$
        $$R = \frac{1}{\lim_{n \rightarrow \infty} |\frac{a_{n+1}}{a_{n}}|}$$
        $$\lim_{n \rightarrow \infty} |\frac{a_{n+1}}{a_{n}}|$$
        $$\lim_{n \rightarrow \infty} \frac{\frac{1}{n+1}}{\frac{1}{n}} = 1$$
        רדיוס ההתכנסות הוא 1 סביב הנקודה 0, כעת נבדוק הת ככנסות בקצוות התחום $[-1, 1]$:  
        
        $$x_0=1$$
        $$\sum_{n=1}^{\infty}(-1)^{n+1}\frac{1}{n}1^{n}$$
        $$\sum_{n=1}^{\infty}(-1)^{n+1}\frac{1}{n}$$
        ידוע כי מתכנס (לייבניץ).

        $$x_0=-1$$
        $$\sum_{n=1}^{\infty}(-1)^{n+1}\frac{1}{n}(-1)^{n}$$
        $$\sum_{n=1}^{\infty}(-1)^{2n+1}\frac{1}{n}$$
        $$\sum_{n=1}^{\infty}-\frac{1}{n}$$
        $$-\sum_{n=1}^{\infty}\frac{1}{n}$$
        ידוע כי מתבדר.  
        לכן תחום ההתכנסות של הטור הינו $(-1,1]$.
    2.
        $$f_{(x)} = \ln(\frac{x+1}{1-x})$$
        $$f_{(x)} = \ln(x+1) - \ln(1-x)$$
        $$g_{(x)} = \ln(1-x)$$
        $$g_{(x)}^{(1)} = -\frac{1}{1-x}$$
        $$g_{(x)}^{(2)} = -\frac{1}{(1-x)^2}$$
        $$g_{(x)}^{(3)} = -\frac{2}{(1-x)^3}$$
        $$g_{(x)}^{(4)} = \frac{2\cdot 3}{(1-x)^4}$$
        $$\Downarrow$$
        $$g_{(x)}^{(k)} = -\frac{(k-1)!}{(1-x)^k}$$
        $$g_{(x)} = \sum_{n=0}^{\infty}\frac{g^{(n)}_{(x_0)}}{n!}(x-x_0)^{n}$$
        
        $$g_{(x)} = \sum_{n=0}^{\infty}\frac{g^{(n)}_{(x_0)}}{n!}(x-x_0)^{n}$$
        $$\Downarrow$$
        $$\ln(1-x) = \cancel{\ln(1)}+\sum_{n=1}^{\infty}\frac{-\frac{(n-1)!}{(1-x_0)^n}}{n!}(x-x_0)^{n}$$
        $$\ln(1-x) = \sum_{n=1}^{\infty}-\frac{1}{n(1-x_0)^n}(x-x_0)^{n}$$
        $$\Downarrow x_0 = 0$$
        $$\ln(1-x) = \sum_{n=1}^{\infty}-\frac{1}{n(1)^n}x^{n}$$
        $$\ln(1-x) = \sum_{n=1}^{\infty}-\frac{1}{n}x^{n}$$
        נחזור לפונקציה המקורית:  
        
        $$f_{(x)} = \ln(x+1) - \ln(1-x)$$
        $$f_{(x)} = \sum_{n=1}^{\infty}(-1)^{n+1}\frac{1}{n}x^{n} - \sum_{n=1}^{\infty}-\frac{1}{n}x^{n}$$
        $$f_{(x)} = \sum_{n=1}^{\infty}(-1)^{n+1}\frac{1}{n}x^{n} +\frac{1}{n}x^{n}$$
        $$f_{(x)} = \sum_{n=1}^{\infty}((-1)^{n+1}+1)\frac{1}{n}x^{n}$$
         כעת מכיוון שמדובר בטור חזקות, נחשב את רדיוס ההתכנסות: 

        $$a_n = ((-1)^{n+1}+1)\frac{1}{n}$$
        $$R = \frac{1}{\lim_{n \rightarrow \infty} |\frac{a_{n+1}}{a_{n}}|}$$
        $$\lim_{n \rightarrow \infty} |\frac{a_{n+1}}{a_{n}}|$$
        $$\lim_{n \rightarrow \infty} \frac{((-1)^{n+2}+1)\frac{1}{n+1}}{((-1)^{n+1}+1)\frac{1}{n}}$$
        $$\lim_{n \rightarrow \infty} \frac{(-1)^{n+2}n}{(-1)^{n+1}(n+1)} + \frac{n}{n+1}$$
        $$\lim_{n \rightarrow \infty} -\frac{n}{n+1} + \frac{n}{n+1} = -1+1 = 0$$
        רדיוס ההתכנסות הוא 0 סביב הנקודה 0, כעת נבדוק הת ככנסות בנקודה עצמה
        
        $$x_0=0$$
        $$\sum_{n=1}^{\infty}((-1)^{n+1}+1)\frac{1}{n}0^{n} = 0$$
        הטור מתכנס ב-$x=0$ בלבד.
6.
    1.
        $$\sum_{n=0}^{\infty}\frac{n}{4^n}$$
        $$\sum_{n=0}^{\infty}n(\frac{1}{4})^n$$
        $$\frac{\frac{1}{4}}{(1-\frac{1}{4})^2}$$
        $$\frac{\frac{1}{4}}{\frac{3}{4}^2}$$
        $$\frac{\frac{1}{4}}{\frac{9}{16}}$$
        $$\frac{1}{4}\cdot \frac{16}{9}$$
        $$\sum_{n=0}^{\infty}\frac{n}{4^n} = \frac{4}{9}$$
    2.
        $$\sum_{n=0}^{\infty}\frac{n^2}{2^n}$$
        $$\sum_{n=0}^{\infty}n^2(\frac{1}{2})^n$$
        $$\sum_{n=0}^{\infty}x^n = \frac{1}{1-x} \ \ / ()'$$
        $$\sum_{n=0}^{\infty}nx^{n-1} = \frac{1}{(1-x)^2} \ \ / \cdot x$$
        $$\sum_{n=0}^{\infty}nx^n = \frac{x}{(1-x)^2} \ \ / ()'$$
        $$\sum_{n=0}^{\infty}n^2x^{n-1} = \frac{x+1}{(1-x)^3} \ \ / \cdot x$$
        $$\sum_{n=0}^{\infty}n^2x^n = \frac{x^2+x}{(1-x)^3}$$
        $$\sum_{n=0}^{\infty}n^2x^n = \frac{x^2+x}{(1-x)^3}$$
        $$\sum_{n=0}^{\infty}n^2x^n = \frac{x^2+x}{(1-x)^3}$$
        $$\downarrow x= \frac{1}{2}$$
        $$\sum_{n=0}^{\infty}n^2(\frac{1}{2})^n = \frac{\frac{1}{2}^2+\frac{1}{2}}{(1-\frac{1}{2})^3}$$
        $$\sum_{n=0}^{\infty}n^2(\frac{1}{2})^n = \frac{\frac{3}{4}}{\frac{1}{2}^3}$$
        $$\sum_{n=0}^{\infty}n^2(\frac{1}{2})^n = \frac{\frac{3}{4}}{\frac{1}{8}}$$
        $$\sum_{n=0}^{\infty}n^2(\frac{1}{2})^n = 8 \cdot \frac{3}{4} = 6$$