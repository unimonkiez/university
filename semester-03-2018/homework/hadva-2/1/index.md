<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>

### מטלה 1 חדו"א 2 - יובל סרף
1.
    1. הטור חיובי, לכן נשתמש במבחן מנה (דלמבר)

    $$\sum_{n=1}^{\infty}\frac{n!}{(n+1)^2 3^n}$$
    $$a_n = \frac{n!}{(n+1)^2 3^n}$$
    $$L = \lim_{n \rightarrow \infty}\frac{a_{n+1}}{a_n}$$
    $$L = \lim_{n \rightarrow \infty}\frac{\frac{(n+1)!}{(n+2)^2+3^{n+1}}}{\frac{n!}{(n+1)^2 3^n}}$$
    $$L = \lim_{n \rightarrow \infty}\frac{(n+1)!(n+1)^2 3^n}{n!(n+2)^2 3^{n+1}}$$
    $$L = \lim_{n \rightarrow \infty}\frac{(n+1)^3}{3(n+2)^2}=\infty$$
    מכיוון ש$L>1$ הטור מתבדר.

    2.
    $$\sum_{n=1}^{\infty}\frac{n-1}{n2^n}$$
    הטור חיובי, לכן נשתמש במבחן מנה (דלמבר)
    
    $$a_n = \frac{n-1}{n2^n}$$
    $$L = \lim_{n \rightarrow \infty}\frac{a_{n+1}}{a_n}$$
    $$L = \lim_{n \rightarrow \infty}\frac{n n 2^n}{(n-1)(n+1)2^{n+1}}$$
    $$L = \lim_{n \rightarrow \infty}\frac{n^2 2^n}{(n^2-1)2^{n+1}}$$
    $$L = \lim_{n \rightarrow \infty}\frac{n^2}{2(n^2-1)} = \frac{1}{2}$$
    מכיוון ש$L<1$ הטור מתכנס.

    3.
    $$\sum_{n=1}^{\infty}\frac{(-1)^n+4^n}{3^n}$$
    הטור חיובי, נבדוק שאיפה של האיבר הכללי.

    $$a_n = \frac{(-1)^n+4^n}{3^n}$$
    $$\lim_{n \rightarrow \infty}\frac{(-1)^n+4^n}{3^n}$$
    $$\lim_{n \rightarrow \infty}(\frac{-1}{3})^n + (\frac{4}{3})^n = 0 + \infty = \infty$$

    מכיון שהטור וחיובי והאיבר הכללי $\lim_{n \rightarrow \infty}a_n \neq 0$ אז הטור מתבדר.

    4.
    $$\sum_{n=2018}^{\infty}\frac{1}{n+2018\sin{(n)}}$$
    הטור חיובי (n מתחיל ב2018 ולכן המכנה תמיד גדול שווה 0).

    $$a_n = \frac{1}{n+2018\sin{(n)}}$$
    $$b_n = \frac{1}{n+2018}$$
    $$0\leq b_n\leq a_n$$

    $$\sum_{n=2019}^{\infty}b_n$$
    $$\sum_{n=2019}^{\infty}\frac{1}{n+2018}$$
    $$\sum_{n=1}^{\infty}\frac{1}{n}$$
    הטור בעל האיבר הכללי $b_n$ מתבדר, ולפי מבחן ההשוואה של טורים גם הטור המקורי מתבדר.

    5.
    $$\sum_{n=1}^{\infty}\frac{2n-1}{(\sqrt[]{2})^n}$$
    הטור חיובי, לכן נשתמש במבחן מנה (דלמבר)

    $$a_n = \frac{2n-1}{(\sqrt[]{2})^n}$$
    $$L = \lim_{n \rightarrow \infty}\frac{a_{n+1}}{a_n}$$
    $$L = \lim_{n \rightarrow \infty}\frac{(2n+1)(\sqrt[]{2})^n}{(2n-1)(\sqrt[]{2})^{n+1}}$$
    $$L = \lim_{n \rightarrow \infty}\frac{2n+1}{(2n-1)\sqrt[]{2}} = \frac{1}{\sqrt[]{2}}$$
    מכיוון ש$L<1$ הטור מתכנס.

    6.
    $$\frac{2}{1}+\frac{2\cdot 5}{1\cdot 5}+\frac{2\cdot 5\cdot 8}{1\cdot 5\cdot 9}+...$$
    הטור חיובי, לכן נשתמש במבחן מנה (דלמבר)

    $$a_n = \frac{2\cdot 5\cdot 8 \cdot\cdot\cdot\cdot (3n-1)}{1\cdot 5\cdot 9 \cdot\cdot\cdot\cdot (4n-3)}$$
    $$L = \lim_{n \rightarrow \infty}\frac{2\cdot 5\cdot 8 \cdot\cdot\cdot\cdot (3n-1)(3n+2)\cdot 1\cdot 5\cdot 9 \cdot\cdot\cdot\cdot (4n-3)}{1\cdot 5\cdot 9 \cdot\cdot\cdot\cdot (4n-3)(4n+1)\cdot 2\cdot 5\cdot 8 \cdot\cdot\cdot\cdot (3n-1)}$$
    $$L = \lim_{n \rightarrow \infty}\frac{(3n+2)}{(4n+1)} = \frac{3}{4}$$
    מכיוון ש$L<1$ הטור מתכנס.
2.
     בעזרת מבחן אינטגרלי מצא את כל הערכים של $p>0$ כך שהטור הבא מתכנס: 
     
     $$\sum_{n=2}^{\infty}\frac{1}{n(\ln(n))^p}$$
     $$f_{(x)} = \frac{1}{x(\ln(x))^p}| x\in [2, \infty]$$
     רציפה כי מורכבת מהרכבת מפונקציות אלמנטריות.  
     הפונקציה חיובית ויורדת מתחום הגדרתה $x\in [2, \infty]$ וגם $p>0$.
     כעת נבדוק את התכנסות האינטגרל של הפונקציה.
     
     $$\int_2^{\infty}f_{(x)}\delta x$$
     $$\int_2^{\infty}\frac{1}{x(\ln(x))^p}\delta x$$
     $$\lim_{b \rightarrow \infty}\int_2^{b}\frac{1}{x(\ln(x))^p}\delta x$$
     $$t = \ln{(x)}$$
     $$\delta t = \frac{1}{x}\delta x$$
     $$\delta x = x\delta t$$
     $$\Downarrow$$
     $$\lim_{b \rightarrow \infty}\int_2^{b}\frac{1}{x(t)^p}x\delta t$$
     $$\lim_{b \rightarrow \infty}\int_2^{b}\frac{1}{t^p}\delta t$$
     $$p>1 \Downarrow$$
     $$\lim_{b \rightarrow \infty}\frac{t^{1-p}}{1-p}|_2^{b}$$
     $$\lim_{b \rightarrow \infty}\frac{ln(x)^{1-p}}{1-p}|_2^{b}$$
     $$\lim_{b \rightarrow \infty}\frac{ln(b)^{1-p}}{1-p} - \frac{ln(2)^{1-p}}{1-p} = const$$
     האינטגרל מתכנס ולכן גם הטור מתכנס.

     $$0<p<1 \Downarrow$$
     $$\lim_{b \rightarrow \infty}\frac{t^{1-p}}{1-p}|_2^{b}$$
     $$\lim_{b \rightarrow \infty}\frac{ln(x)^{1-p}}{1-p}|_2^{b}$$
     $$\lim_{b \rightarrow \infty}\frac{ln(b)^{1-p}}{1-p} - \frac{ln(2)^{1-p}}{1-p} = \infty$$
     האינטגרל מתבדר ולכן גם הטור מתבדר.
            
    $$p=1 \Downarrow$$
     $$\lim_{b \rightarrow \infty}\ln(t)|_2^{b}$$
     $$\lim_{b \rightarrow \infty}\ln(ln(x))|_2^{b}$$
     $$\lim_{b \rightarrow \infty}\ln(ln(b)) - \ln(ln(2)) = \infty$$
     האינטגרל מתבדר ולכן גם הטור מתבדר.

3.
    $$\sum_{n=3}^{\infty}5\frac{2^{1-2n}}{3^n}$$
    הטור חיובי, לכן נשתמש במבחן מנה (דלמבר)

    $$a_n = 5\frac{2^{1-2n}}{3^n}$$
    $$L = \lim_{n \rightarrow \infty}\frac{a_{n+1}}{a_n}$$
    $$L = \lim_{n \rightarrow \infty}\frac{2^{-1-2n}3^n}{2^{1-2n}3^{n+1}}$$
    $$L = \lim_{n \rightarrow \infty}\frac{1}{2^{2}3} = \frac{1}{12}$$
    מכיוון ש$L<1$ הטור מתכנס.

    כעת נבדוק את הסכום:

    $$\sum_{n=3}^{\infty}5\frac{2\cdot 2^{-2n}}{3^n}$$
    $$\sum_{n=3}^{\infty}10\frac{2^{-2n}}{3^n}$$
    $$\sum_{n=3}^{\infty}10(\frac{2^{-2}}{3})^n$$
    $$\sum_{n=3}^{\infty}10(\frac{1}{12})^n$$
    $$10\sum_{n=3}^{\infty}(\frac{1}{12})^n$$
    $$10(\sum_{n=3}^{\infty}(\frac{1}{12})^n -\sum_{n=0}^{2}(\frac{1}{12})^n)$$
    $$10(\sum_{n=0}^{\infty}(\frac{1}{12})^n -1- \frac{1}{12} - \frac{1}{12^2})$$
    $$\sum_{n=0}^{\infty}q^n = \frac{1}{1-q} : |q|< 1$$
    $$\Downarrow$$
    $$10(\frac{1}{1-\frac{1}{12}} -1- \frac{1}{12} - \frac{1}{12^2})$$
    $$10(\frac{1}{\frac{11}{12}} -1- \frac{1}{12} - \frac{1}{12^2})$$
    $$10(\frac{12}{11} -1- \frac{1}{12} - \frac{1}{12^2})$$
    $$10(\frac{1}{11}-\frac{13}{12^2})$$
    
4. הוכח או הפרך

    1.
    $$\sum_1^{\infty}a_n = const \Rightarrow \sum_1^{\infty}a_n^2 = const$$
    נכון, בגלל שהטור $\sum_1^{\infty}a_n$ מתכנס אז 
    
    $$\lim_{n \rightarrow \infty}a_n = 0$$
    זאת אומרת :
    
    $$\exists\epsilon>0 \in N|n_0>n|a_n<\epsilon$$
    בפרט עבור $\epsilon = 1$, $a_{n_0}<1$
    
    כעת נגדיר טור נוסף

    $$\sum_{n_0}^{\infty}b_n = \sum_{n_0}^{\infty}a_n^2$$
    אך ידוע כי $0\leq b_n \leq a_n$ בקטע $[n_0, \infty]$ ולכן לפי מבחן ההשוואה בין טורים, אם $\sum_1^{\infty}a_n$ מתכנס אז גם $\sum_{n_0}^{\infty}b_n$ מתכנס.

    $$\sum_1^{\infty}a_n^2 = \sum_1^{n_0 - 1}a_n^2 + \sum_{n_0}^{\infty}b_n$$
    אך ידוע כי שינוי במספר **סופי** של איברים אינו משפיע על ההתכנסות או ההתבדרות של טור, לכן גם $\sum_1^{\infty}a_n^2$ מתכנס.

    2.
    $$\sum_1^{\infty}a_n^2 = const \Rightarrow \sum_1^{\infty}a_n = const$$
    לא נכון, לדוגמא: 
    
    $$a_n = \frac{1}{x} = \infty$$
    $$a_n^2 = \frac{1}{x^2} = const$$