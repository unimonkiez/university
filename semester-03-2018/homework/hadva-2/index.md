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
    $$\lim_{n \rightarrow \infty}\frac{3^n(2018 \cdot \frac{2^n}{3^n} - 5)}{3^n(18 + 6 \cdot \frac{2^n}{3^n})}$$
    $$\lim_{n \rightarrow \infty}\frac{2018 \cdot \frac{2}{3}^n - 5}{18 + 6 \cdot \frac{2}{3}^n}$$
    $$\lim_{n \rightarrow \infty}\frac{2018 \cdot 0 - 5}{18 + 6 \cdot 0} = \frac{-5}{18}$$

    4. $$\lim_{n \rightarrow \infty}\sqrt[n]{\frac{(2n)!}{n^{2n}}}$$
    פתרון: 
       
    $$an = \sqrt[n]{b_n}$$
    $=\frac{b_n + 1}{b_n}$ מנת העוקבים היא גם הגבול של הסדרה עצמה (במקרה של $\sqrt[n]{b_n}$)

    $$\Downarrow$$
    $$\lim_{n \rightarrow \infty}b_n = \frac{(2n)!}{n^{2n}}$$
    $$\lim_{n \rightarrow \infty}\frac{b_n + 1}{b_n}=\frac{ \frac{(2(n+1))!}{(n+1)^{2(n+1)}}}{\frac{(2n)!}{n^{2n}}}$$
    $$\lim_{n \rightarrow \infty}\frac{ \frac{(2n+2)!}{(n+1)^{2n+2}}}{\frac{(2n)!}{n^{2n}}}$$
    $$\lim_{n \rightarrow \infty}\frac{(2n+2)! \cdot n^{2n}}{(2n)! \cdot (n+1)^{2n+2}}$$
    $$\lim_{n \rightarrow \infty}\frac{\cancel{(2n)!}(2n+1)(2n+2) \cdot n^{2n}}{\cancel{(2n)!} \cdot (n+1)^{2n+2}}$$
    $$\lim_{n \rightarrow \infty}\frac{(2n+1)(2n+2) \cdot n^{2n}}{(n+1)^2(n+1)^{2n}}$$
    $$\lim_{n \rightarrow \infty}\frac{(2n+1)(2n+2)}{(n+1)^2} \cdot (\frac{n}{n+1})^{2n}$$
    $$\lim_{n \rightarrow \infty}\frac{4n^2 + 6n + 2}{n^2 + 2n + 1} \cdot (\frac{n}{n+1})^{2n}$$
    $$\lim_{n \rightarrow \infty}\frac{n^2(4 + \frac{6}{n} + \frac{4}{n^2})}{n^2(1 + \frac{2}{n} + \frac{1}{n^2})} \cdot (\frac{n(1)}{n(1+\frac{1}{n})})^{2n}$$
    $$\lim_{n \rightarrow \infty}\frac{4 + \frac{6}{n} + \frac{4}{n^2}}{1 + \frac{2}{n} + \frac{1}{n^2}} \cdot (\frac{1}{1+\frac{1}{n}})^{2n}$$
    $$\lim_{n \rightarrow \infty}\frac{4 + 0 + 0}{1 + 0 + 0} \cdot 1 = 4$$
    

    5. $$\lim_{n \rightarrow \infty}(5n - \sqrt[]{25n^2 + 6n - 8})$$
    פתרון: 

    $$\lim_{n \rightarrow \infty}(5n - \sqrt[]{25n^2 + 6n - 8})$$
    $$\lim_{n \rightarrow \infty}n(5 - \sqrt[]{25 + \frac{6}{n} - \frac{8}{n^2}})$$
    $$\lim_{n \rightarrow \infty}n(5 - \sqrt[]{25})$$
    $$\lim_{n \rightarrow \infty}n(0) = 0$$
    
    6. $$\lim_{n \rightarrow \infty}(3 + \frac{1}{\sqrt[]{n}})^{\frac{2}{3}n}$$
    פתרון: 

    $$\lim_{n \rightarrow \infty}(3(1 + \frac{1}{3\sqrt[]{n}}))^{\frac{2n}{3}}$$
    $$\lim_{n \rightarrow \infty}(3(1 + \frac{1}{3\sqrt[]{n}})^{3\sqrt[]{n} \cdot \frac{1}{3\sqrt[]{n}}})^{\frac{2n}{3}}$$
    $$\lim_{n \rightarrow \infty}(3e^{\frac{1}{3\sqrt[]{n}}})^{\frac{2n}{3}}$$
    $$\lim_{n \rightarrow \infty}3^{\frac{2n}{3}}e^{\frac{1}{3\sqrt[]{n}} \cdot \frac{2n}{3}}$$
    $$\lim_{n \rightarrow \infty}3^{\frac{2n}{3}}e^{\frac{2n}{9\sqrt[]{n}}}$$
    $$\lim_{n \rightarrow \infty}3^{\frac{2n}{3}}e^{\frac{2\sqrt[]{n}\sqrt[]{n}}{9\sqrt[]{n}}}$$
    $$\lim_{n \rightarrow \infty}3^{\frac{2n}{3}}e^{\frac{2\sqrt[]{n}}{9}} = \infty$$

    7. $$\lim_{n \rightarrow \infty}(\frac{1}{1 \cdot 4} + \frac{1}{4 \cdot 7} + ... + \frac{1}{(3n-2) \cdot (3n+1)})$$
    פתרון: 

    $$\lim_{n \rightarrow \infty}((\frac{1}{3} - \frac{1}{3 \cdot 4}) + (\frac{1}{3 \cdot 4} - \frac{1}{3 \cdot 7}) + ... + (\frac{1}{3(3n - 5)} - \frac{1}{3(3n - 2)}) + (\frac{1}{3(3n - 2)} - \frac{1}{3(3n + 1)}))$$
    $$\lim_{n \rightarrow \infty}(\frac{1}{3}  - \frac{1}{3(3n + 1)})$$
    $$\lim_{n \rightarrow \infty}\frac{(3n + 1)-1}{3(3n + 1)}$$
    $$\lim_{n \rightarrow \infty}\frac{3n}{3(3n + 1)}$$
    $$\lim_{n \rightarrow \infty}\frac{n}{3n + 1}$$
    $$\lim_{n \rightarrow \infty}\frac{n \cdot 1}{n (3 + \frac{1}{n})}$$
    $$\lim_{n \rightarrow \infty}\frac{1}{3 + \frac{1}{n}} = \frac{1}{3+0} = \frac{1}{3}$$
    
2. מצא עבור אילו ערכים $a, b$ מתקיים:  

$$\lim_{n \rightarrow \infty}(\frac{n^2 + 1}{n+1} - an - b) = 0$$
פתרון: 

$$\lim_{n \rightarrow \infty}\frac{n^2 + 1 -an (n+1) - b(n+1)}{n+1} = 0$$
$$\lim_{n \rightarrow \infty}\frac{n^2 + 1 -an^2 - an -bn -b}{n+1} = 0$$
$$\lim_{n \rightarrow \infty}\frac{n^2(1-a) + n(-a-b) + 1 -b}{n+1} = 0$$
$$\lim_{n \rightarrow \infty}\frac{n(n(1-a) + (-a-b) + \frac{1 -b}{n})}{n(1+\frac{1}{n})} = 0$$
$$\lim_{n \rightarrow \infty}\frac{n(1-a) + (-a-b) + \frac{1 -b}{n}}{1+\frac{1}{n}} = 0$$
$$\Downarrow$$
$$I. \ \ n(1-a) = 0$$
$$II. \ \ -a-b = 0$$
$$\Downarrow$$
$$I. \ \ 1-a = 0$$
$$I. \ \ a = 1$$
$$II. \ \ -1-b = 0$$
$$II. \ \ b = -1$$

3. בדוק אם הסדרה שמוגדרת ע"י כלל נסיגה: $a_{n+1} = \frac{a_n^2 + 3}{4}$ מתכנסת ואם כן מצא את גבולה בשני המקרים הבאים:
    1. $$a_1= 2$$
    פתרון:  
    תחילה נוכיח שהסדרה חסומה מלרע ע"י 1. באינדוקציה:  
    בסיס האינדוקציה $a_1 = 2 > 1$.  
    נניח נכונות עבור $a_n > 1$ ונראה נכונות עבור $a_{n+1} > 1$.  
    צ"ל:  
    
    $$\frac{a_n^2 + 3}{4} > 1$$
    $$a_n^2 + 3 > 4$$
    $$a_n^2 > 1$$
    נובע מהנחת האינדוקציה.  
    כעת עבור להוכחת מונוטונית יורדת.  
    נחשב את מנת העוקבים, ואם היא מתחת ל1 אז הסדרה יורדת:  
    צ"ל:  

    $$\frac{a_{n+1}}{a_n} < 1$$
    $$\frac{\frac{a_n^2 + 3}{4}}{a_n} < 1$$
    $$\frac{a_n^2 + 3}{4a_n} < 1$$
    $$a_n^2 + 3 < 4a_n \ \ \ \ \ / (1 < a_n \leq 2)$$
    $$a_n^2 - 4a_n + 3 < 0$$
    $$(a_n - 1)(a_n - 3) < 0$$
    $$1<a_n<3$$
    האי שיוויון נכון עבור $1 < a_n \leq 2$.
    הסדרה מונוטונית יורדת וחסומה מלרע ולכן מתכנסת.  
    נמצא את הגבול שלה:    
    $\lim_{n \rightarrow \infty}a_{n+1}=\lim_{n \rightarrow \infty}a_{n} = L$ ומאריתמטיקה של גבולות (והשיוויון הנתון $a_{n+1} = \frac{a_n^2 + 3}{4}$) נקבל  

    $$L = \frac{L^2+3}{4}$$
    $$4L = L^2+3$$
    $$L^2-4L+3=0$$
    $$(L-1)(L-3) = 0$$
    $$L_1 = 1$$
    $$\cancel{L_2 = 3}$$
    מכיוון שהסדרה יורדת החל האיבר הראשון (2).  
    גבול הסדרה הוא 1.  

    2. $$a_1= 4$$
    פתרון:  
    תחילה נוכיח שהסדרה מונוטונית עולה:  
    בסיס האינדוקציה $a_{(n+1)} > a_n$
    
    $$\frac{4^2 + 3}{4}>4$$
    $$\frac{16 + 3}{4}>4$$
    $$4+ \frac{3}{4}>4$$
    $$\frac{3}{4}>0$$
    בסיס האינדוצקציה נכון.  
    כעת צ"ל להוכיח עבור $n+1$
    
    $$a_{n+2} > a_{a+1}$$
    $$\frac{(a_{n+1})^2 + 3}{4} > \frac{a_n^2 + 3}{4}$$
    $$(a_{n+1})^2 + 3 > a_n^2 + 3$$
    $$(a_{n+1})^2 > a_n^2$$
    האי שיוויון נכון מהנחת האינדוקציה.  
    כעת נוכיח בשלילה כי אין לסדרה גבול והינה שואפת לאינסוף:  
    נניח כי אכן חסומה מלעיל, ומכיוון שהוכחנו כי הסדרה מונוטונית עולה אז היא גם מתכנסת לגבול L.  
    נמצא את הגבול שלה:    
    $\lim_{n \rightarrow \infty}a_{n+1}=\lim_{n \rightarrow \infty}a_{n} = L$ ומאריתמטיקה של גבולות (והשיוויון הנתון $a_{n+1} = \frac{a_n^2 + 3}{4}$) נקבל  

    $$L = \frac{L^2+3}{4}$$
    $$4L = L^2+3$$
    $$L^2-4L+3=0$$
    $$(L-1)(L-3) = 0$$
    $$\cancel{L_2 = 1}$$
    $$\cancel{L_2 = 3}$$
    שני הגבולות האופציונליים מתבטלים מכיוון שכבר הוכחנו שהסדרה עולה החל מהאיבר הראשון (4).  
    הסדרה המונוטונית עולה אינה חסומה מלעיל ולכן שואפת ל-$\infty$.

4. בתרגול הוכחנו שאם סדרת מספרים $\{a_n\}$ מתכנסת לגבול $L$ אזי שהממוצע החשבוני של $n$ האיברים הראשונים: $u_n = \frac{a_1 + a_2 + ... + a_n}{n}$ גם מתכנסת לאותו גבול, ז"א: $\lim_{n \rightarrow \infty}u_n = L$.  
האם ההפך נכון? כלומר, אם $\lim_{n \rightarrow \infty}u_n = L$ אזי גם $\lim_{n \rightarrow \infty}a_n = L$? נמק!  
פתרון  
**ההפך לא נכון**, לדוגמא

$$a_n = (-1)^n$$
לסדרה אין גבול מכיוון שמתבדרת (עבור $n$ זוגי היא 1, עבור $n$ אי זוגי היא $-1$).  
סכום הסדרה היא הוא 0 או 1 לסירוגין, וגבול הסדרות ממוצעים בשתי המקרים שואפות ל0:  

$$\lim_{n \rightarrow \infty}\frac{0}{n} = 0$$
$$\lim_{n \rightarrow \infty}\frac{1}{n} = 0$$

לכן הטענה כי אם הסכום החשבוני של הסדרה מתכנס לגבול אז הסדרה עצמה גם כן מתכנסת לאותו הגבול **אינו נכון**.