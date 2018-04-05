<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>

### מטלה 2 חדו"א
1. חשב את הגבולות הבאים:  
    1. $$\lim_{n \rightarrow \infty}\sum^{2n}_{k=1} \frac{n+1}{n^2+k}$$  
    פתרון:  

    $$\lim_{n \rightarrow \infty}\sum^{2n} \frac{n+1}{n^2+1} < \lim_{n \rightarrow \infty}\sum^{2n}_{k=1} \frac{n+1}{n^2+k} < \lim_{n \rightarrow \infty}\sum^{2n} \frac{n+1}{n^2+2n}$$
    $$\Downarrow$$
    $$\lim_{n \rightarrow \infty}\sum^{2n} \frac{n+1}{n^2+1}$$
    $$\lim_{n \rightarrow \infty}\frac{(n+1)(2n)}{n^2+1}$$
    $$\lim_{n \rightarrow \infty}\frac{2n^2 + 2n}{n^2+1}$$
    $$\lim_{n \rightarrow \infty}\frac{2 + \frac{2}{n}}{1+\frac{1}{n^2}} = \lim_{n \rightarrow \infty}\frac{2}{1} = 2$$

    $$\lim_{n \rightarrow \infty}\sum^{2n} \frac{n+1}{n^2+2n}$$
    $$\lim_{n \rightarrow \infty}\frac{(n+1)(2n)}{n^2+2n}$$
    $$\lim_{n \rightarrow \infty}\frac{2n^2 + 2n}{n^2+2n}$$
    $$\lim_{n \rightarrow \infty}\frac{2 + \frac{2}{n}}{1+\frac{2}{n}} = \lim_{n \rightarrow \infty}\frac{2}{1} = 2$$
    $\Downarrow$ (כלל הסנדוויץ')  

    $$\lim_{n \rightarrow \infty}\sum^{2n}_{k=1} \frac{n+1}{n^2+k} = 2$$

    2. $$\lim_{n \rightarrow \infty}\frac{\sqrt[]{n} + a \cos{(bn)} - b \sin{an}}{\sqrt[]{n} - a \cos{(bn)} + b \sin{an}}$$
    פתרון: 


    $$\lim_{n \rightarrow \infty}\frac{1 + \frac{a \cos{(bn)}}{\sqrt[]{n}} - \frac{b \sin{an}}{\sqrt[]{n}}}{1 - \frac{a \cos{(bn)}}{\sqrt[]{n}} + \frac{b \sin{an}}{\sqrt[]{n}}}$$
    $$\lim_{n \rightarrow \infty}\frac{1 + 0 - 0}{1 - 0 + 0} = 1$$
    3. $$\lim_{n \rightarrow \infty}\frac{2018 \cdot 2^n - 5 \cdot 3^n }{6 \cdot 3^{n+1} + 6 \cdot 2^n}$$
    פתרון: 

    $$\lim_{n \rightarrow \infty}\frac{2018 \cdot 2^n - 5 \cdot 3^n }{18 \cdot 3^n + 6 \cdot 2^n}$$

    4. $$\lim_{n \rightarrow \infty}\sqrt[n]{\frac{(2n)!}{n^{2n}}}$$
    5. $$\lim_{n \rightarrow \infty}(5n - \sqrt[]{25n^2 + 6n - 8})$$
    פתרון: 

    $$\lim_{n \rightarrow \infty}(5n - \sqrt[]{25n^2 + 6n - 8})$$
    $$\lim_{n \rightarrow \infty}n(5 - \sqrt[]{25 + \frac{6}{n} - \frac{8}{n^2}})$$
    $$\lim_{n \rightarrow \infty}n(5 - \sqrt[]{25})$$
    $$\lim_{n \rightarrow \infty}n(0) = 0$$
    
    6. $$\lim_{n \rightarrow \infty}(3 + \frac{1}{\sqrt[]{n}})^{\frac{2}{3}n}$$
    7. $$\lim_{n \rightarrow \infty}(\frac{1}{1 \cdot 4} + \frac{1}{4 \cdot 7} + ... + \frac{1}{(3n-2) \cdot (3n+1)})$$
2. מצא עבור אילו ערכים $a, b$ מתקיים:  

$$\lim_{n \rightarrow \infty}(\frac{n^2 + 1}{n+1} - an - b) = 0$$

3. בדוק אם הסדרה שמוגדרת ע"י כלל נסיגה: $a_{n+1} = \frac{a_n^2 + 3}{4}$ מתכנסת ואם כן מצא את גבולה בשני המקרים הבאים:
    1. $$a_1= 2$$
    2. $$a_1= 4$$

4. בתרגול הוכחנו שאם סדרת מספרים $\{a_n\}$ מתכנסת לגבול $L$ אזי שהממוצע החשבוני של $n$ האיברים הראשונים: $u_n = \frac{a_1 + a_2 + ... + a_n}{n}$ גם מתכנסת לאותו גבול, ז"א: $\lim_{n \rightarrow \infty}u_n = L$.  
האם ההפך נכון? כלומר, אם $\lim_{n \rightarrow \infty}u_n = L$ אזי גם $\lim_{n \rightarrow \infty}a_n = L$? נמק!