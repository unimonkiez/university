<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>

### מטלה 1 חדו"א

1. בעזרת אינדוקציה מתמטית הוכח שלכל $n\geq 2$ מתקיים:  
$\frac{1}{1 \cdot 2} + \frac{1}{2 \cdot 3} + ...+ \frac{1}{(n-1) \cdot n} = \frac{n-1}{n}$  
  פתרון:  
  בסיס האינדוקציה: עבור $n=2$ 

  $$\frac{1}{1\cdot 2} = \frac{2-1}{2}$$
  $$\Downarrow$$
  $$\frac{1}{2} = \frac{1}{2}$$
  נניח מתקיים עבור $n>2$ כלשהו, כלומר נניח כי:  $\frac{1}{1 \cdot 2} + \frac{1}{2 \cdot 3} + ...+ \frac{1}{(n-1) \cdot n} = \frac{n-1}{n}$  
  נוכיח כי מתקיים עבור $n+1$:  

  $$\frac{1}{1 \cdot 2} + \frac{1}{2 \cdot 3} + ...+ \frac{1}{(n-1) \cdot n}+ \frac{1}{((n+1)-1) \cdot (n+1)} = \frac{(n+1)-1}{n+1}$$
  $$\frac{n-1}{n}+ \frac{1}{((n+1)-1) \cdot (n+1)} = \frac{(n+1)-1}{n+1}$$
  $$\frac{n-1}{n}+ \frac{1}{n \cdot (n+1)} = \frac{n}{n+1}$$
  $$\frac{(n-1)(n+1)+1}{n \cdot (n+1)} = \frac{n}{n+1}$$
  $$\frac{n^2-1+1}{n \cdot (n+1)} = \frac{n}{n+1}$$
  $$\frac{n^2}{n \cdot (n+1)} = \frac{n}{n+1}$$
  $$\frac{n}{n+1} = \frac{n}{n+1}$$
  מש"ל

2. מצא את החסם העליון, החסם התחתון, המקסימום  והמינימום (אם קיימים) עבור הקבוצות הבאות:  
    1. $A=\{1+n\sin{\frac{n \pi}{2}} | n \in N\}$  
    הביטוי $\sin{\frac{n\pi}{2}}$ מקבל את כל אחד מהערכים $\{0, 1, -1\}$ אינסוף פעמים.  
    $n$ שואף לאינסוף כאשר $n \rightarrow \infty$.  
    איברי הקבוצה הולכים וקטנים כאשר $\sin{\frac{n\pi}{2}}=-1$ ו-$n \rightarrow \infty$ ומתקיים כי:  $\inf A = -\infty \notin A$, לכן לקבוצה אין מינימום.  
    מצד שני איברי הקבוצה הולכים וגדלים כאשר $\sin{\frac{n\pi}{2}}=1$ ו-$n \rightarrow \infty$ ומתקיים כי:  $\sup A = \infty \notin A$, לכן לקבוצה אין מקסימום.  

    2. $B=\{(-1)^{n+1}(3+\frac{4}{n}) | n \in N\}$  
    הביטוי $3+\frac{4}{n}$ הוא סדרה יורדת השואפת ל-3, כאשר $n \rightarrow \infty$.  
    לכן הערך המקסימלי מתקבל עבור $n=1$ והוא 7, בנוסף, כאשר $n=1$: $(-1)^{n+1} = 1$ ולכן בסה"כ מתקבל כי $\sup B = \max B = 7$.  
    הערך המינימלי מתקבל כאשר $n=2$, ז"א:  $\inf B = \min B = -1(3 + \frac{4}{2}) = -5$

    3. $C=\{x^2 +3x -4 \leq 0 | x \in R\}$  
    נפתור את המשוואה הריבועית:  

    $$x^2+3x-4\leq 0$$
    $$(x+4)(x-1)\leq 0$$
    המשוואה הריבועית היא בצורת פרבולה "מחייכת", אשר נקודות החיתוך שלה עם ציר ה$x$ הם $-4$ ו$1$, ואיבריה ביניהם.  
    לכן ניתן לרשום את הקבוצה גם בצורה הבאה:  

    $$C=\{-4 \geq x \geq 1 | x \in R\}$$
    $$\Downarrow$$
    $$\sup C = \max C = 1$$
    $$\inf C = \min C = -4$$
    

    4. $D=\{\frac{(-1)^n}{n} | n \in N\}$

    נפשט את נוסחאת הקבוצה:   

    $$D=\{(-1)^n\frac{1}{n} | n \in N\}$$
    הביטוי $(-1)^n$ מקבל כל אחד מהערכים $\{-1, 1\}$ אין סוף פעמים.  
    הביטוי $\frac{1}{n}$ הוא סדרה יורדת השואפת ל-0 כאשר $n \rightarrow \infty$.  
    לכן הערך המינימלי המתקבל עבור $n=1$ הוא $\inf D = \min D = (-1)^2 \cdot \frac{1}{1} = -1$   
    לכן הערך המקסימלי המתקבל עבור $n=2$ הוא $\sup D = \max D = 1^2 \cdot \frac{1}{2} = \frac{1}{2}$

3. תהי $\{a_n\}$ סדרה מתכנסת לגבול סופי ו-$\{b_n\}$ סדרה חסומה.  
הוכח או הפרך את הטענות הבאות:  
    1. הסדרה $\{a_n\}$ חסומה.  
    הוכחה:  
    נתון $\lim_{n \rightarrow \infty}a_n = L$, כלומר:  

    $$\forall \epsilon>0 \exists n_0 \in N|\forall n \geq n_0: |a_n-L|<\epsilon$$
    $$\Updownarrow$$
    $$\forall \epsilon>0 \exists n_0 \in N|\forall n \geq n_0: L-\epsilon<a_n<L+\epsilon$$
    מכאן, לכל בחירה של $\epsilon>0$ נקבל חסימות של הסדרה $a_n$

    2. הסדרה $\{a_n\cdot b_n\}$ מתכנסת.  
    הפרכה:  
    ניקח למשל $a_n = 1+\frac{1}{n}$, סדרה מתכנסת לגבול סופי 1, $b_n = (-1)^n$, סדרה חסומה.  
    אבל $a_b \cdot b_n = (-1)^n \cdot (2+\frac{1}{n})$, סדרה מתבדרת ואינה מתכנסת.

4. הוכח שלכל $x,y \in R$ מתקיים:  
    1. $|x| - |y| \leq |x-y|$ 

    $$|x| = |(x-y)+y|$$
    $$|(x-y)+y| \leq |x-y|+|y|$$
    $$|(x-y)+y| - |y| \leq |x-y|$$
    $$\Downarrow$$
    $$|x| - |y| \leq |x-y|$$
    2. $||x| - |y|| \leq |x-y|$  

    $$|x| = |(x-y)+y|$$
    $$|(x-y)+y| \leq |x-y|+|y|\Rightarrow|x|-|y|\leq |x-y|$$
    $$|y| = |(y-x)+x|$$
    $$|(y-x)+x| \leq |y-x|+|x|\Rightarrow|x|-|y|\geq -|x-y|$$
    $$\Downarrow$$
    $$-|x-y|\leq |x|-|y| \leq |x-y|$$
    $$\Downarrow$$
    $$||x|-|y|| \leq |x-y|$$

5. הוכח או הפרך:  
    1. אם $\lim_{n \rightarrow \infty}a_n =L$ אז $\lim_{n \rightarrow \infty}|a_n|=|L|$  
    הוכחה:  
    נתון: 

    $$\forall \epsilon > 0 \exists n_0 \in N|\forall n \geq n_0: |a_n-L| < \epsilon$$
    צ"ל:  

    $$\forall \epsilon > 0 \exists n_0 \in N|\forall n \geq n_0: ||a_n|-|L|| < \epsilon$$

    $$\Downarrow$$

    $$|a_n-L| < \epsilon$$
    $$||x| - |y|| \leq |x-y|$$
    $$\Downarrow$$
    $$||a_n| - |L|| \leq |a_n-L| < \epsilon$$
    $$||a_n| - |L|| < \epsilon$$
    מש"ל

    2. אם $\lim_{n \rightarrow \infty}|a_n| =|L|$ אז $\lim_{n \rightarrow \infty}a_n=L$  
    הפרכה:  
    
    $$a_n= (-1)^n$$
    $$\lim_{n \rightarrow \infty}|a_n| = |(-1)^n| = 1$$
    אך לא (סדרה ללא גבול, מתבדרת)

    $$\lim_{n \rightarrow \infty}a_n = \lim_{n \rightarrow \infty}(-1)^n \neq 1$$


6. הוכח לפי ההגדרה כי:  
    1.  $\lim_{n \rightarrow \infty} \frac{8n+5}{3-4n}=-2$  
    צ"ל:  

    $$\forall \epsilon > 0 \exists n_0 \in N|\forall n \geq n_0: |\frac{8n+5}{3-4n}+2|< \epsilon$$
    $$|\frac{8n+5}{3-4n}+2|<\epsilon$$
    $$|\frac{8n+5+2(3-4n)}{3-4n}|<\epsilon$$
    $$|\frac{8n+5+6-8n}{3-4n}|<\epsilon$$
    $$|\frac{11}{3-4n}|<\epsilon$$
    $$\forall n \in N|3-4n < 0$$
    $$\Downarrow$$
    $$\frac{11}{3-4n}>\epsilon$$
    $$3-4n<\frac{11}{\epsilon}$$
    $$-4n<\frac{11}{\epsilon}-3$$
    $$n>\frac{3}{4}-\frac{11}{4\epsilon}$$  
    כלומר אם ניקח $n_0 > \frac{3}{4}-\frac{11}{4\epsilon}$, ז"א $n_0 = [\frac{3}{4}-\frac{11}{4\epsilon}]+1$ אז לכל $n \geq n_0$ יתקיים $|\frac{8n+5}{3-4n}+2|< \epsilon$

    2. יהיה $\epsilon = 0.01$, מצא מספר איברי הסדרה שנמצאים מחוץ לסביבה $(-2-\epsilon, -2+\epsilon)$.

    נציב $\epsilon = 0.01$:  

    $$n_0 = |[\frac{3}{4}-\frac{11}{4\cdot 0.01}]|+1$$
    $$n_0 = |[\frac{3}{4}-\frac{11}{0.04}]|+1$$
    $$n_0 = |[\frac{3}{4}-275]|+1$$
    $$n_0 = |[-(274+\frac{1}{4})]|+1$$
    $$n_0 = |-275|+1$$
    $$n_0 = 275+1$$
    $$n_0 = 276$$
    ז"א, שהאיבר מספר 276 הוא הראשון הנמצא בתוך הסביבה $(-2-\epsilon, -2+\epsilon)$, ולכן מספר איברי הסדרה הנמצאים מחוץ לסביבה זו הוא 275.