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
    $$\lim_{x \rightarrow 0}(1+x^2)^{\frac{\cos^2{x}}{\sin^2{x}}}$$ 
    $$\lim_{x \rightarrow 0}[(1+x^2)^{\frac{1}{x^2}}]^{x^2\frac{\cos^2{x}}{\sin^2{x}}}$$ 
    $$\lim_{x \rightarrow 0}e^{x^2\frac{\cos^2{x}}{\sin^2{x}}}$$ 
    $$\lim_{x \rightarrow 0}e^{\frac{x^2}{\sin^2{x}}\cos^2{x}} = e^{1\cdot cos^2{x}} = e$$ 

    6. $$\lim_{x \rightarrow 3}(3x -8)^{\frac{x}{\sin{(x-3)}}}$$
    $$\lim_{x \rightarrow 3}(1+ (3x -8 -1))^{\frac{x}{\sin{(x-3)}}}$$
    $$\lim_{x \rightarrow 3}[(1+ (3x -9))^{\frac{1}{3x-9}}]^{(3x-9)\frac{x}{\sin{(x-3)}}}$$
    $$\lim_{x \rightarrow 3}e^{(3x-9)\frac{x}{\sin{(x-3)}}}$$
    $$\lim_{x \rightarrow 3}e^{3(x-3)\frac{x}{\sin{(x-3)}}}$$
    $$\lim_{x \rightarrow 3}e^{3x\frac{x-3}{\sin{(x-3)}}} = e^{3x\cdot 1} = e^9$$
    
2. $$f_{(x)} = \{ \frac{x^2+bx+c}{x-2}, x \neq 2 \ \ \ | \ \ \ 7, x =2 \}$$
    רציפה לכל $x$.  
    מצא את $b, c$.  
    
    $$\lim_{x \rightarrow 2}f_{(x)} = f_{(2)}$$
    $$\Downarrow$$
    $$\lim_{x \rightarrow 2}\frac{x^2+bx+c}{x-2} = 7$$
    $$\Downarrow$$
    $$\lim_{x \rightarrow 2}x^2+bx+c = 0$$
    $$\lim_{x \rightarrow 2}(x-2)(x-z) = 0$$
    $$\lim_{x \rightarrow 2}\frac{(x-2)(x-z)}{x-2} = 7$$
    $$\lim_{x \rightarrow 2}x-z= 7$$
    $$\lim_{x \rightarrow 2}z= x-7 \Rightarrow  z=-5$$
    $$\Downarrow$$
    $$x^2 + bx + c = (x-2)(x+5)$$
    $$x^2 + bx + c = x^2-3x-10$$
    $$\Downarrow$$
    $$b=-3$$
    $$c=-10$$

3. $$f_{(x)} = \{ \frac{ax^2-b}{x-1}, x > 1 \ \ \ | \ \ \ a+b, x =1 \ \ \ | \ \ \ \frac{\sqrt[]{x} - c}{x^2-1}, 0 \leq x < 1\}$$
    1. עבור אילו $a, b, c$ הפונקציה רציפה ב- $x=1$?  

    $$\lim_{x \rightarrow 1+}f_{(x)} = \lim_{x \rightarrow 1-}f_{(x)} = f_{(1)}$$
    $$\lim_{x \rightarrow 1}\frac{ax^2-b}{x-1} = \lim_{x \rightarrow 1}\frac{\sqrt[]{x} - c}{x^2-1} = a+b$$
    שני הגבולות ישאפו למספר קבוע רק אם שני המונה יתאפסו (אחרת תהיה שאיפה ל-0 או אינסוף)

    $$\Downarrow$$
    $$\lim_{x \rightarrow 1}ax^2-b = 0$$
    $$\lim_{x \rightarrow 1}\sqrt[]{x} - c = 0$$
    $$\Downarrow$$
    $$a-b=0$$
    $$a=b$$
    $$1-c=0$$
    $$c=1$$
    כעת נבדוק כי אכן הגבול התלוי ב$a,b$ שואף ל$f_{(1)}$ - 

    $$\lim_{x \rightarrow 1+}\frac{ax^2-a}{x-1} = 2a$$
    $$\lim_{x \rightarrow 1+}\frac{a(x^2-1)}{x-1} = 2a$$
    $$\lim_{x \rightarrow 1+}\frac{a(x+1)(x-1)}{x-1} = 2a$$
    $$\lim_{x \rightarrow 1+}a(x+1) = 2a \Rightarrow 2a=2a$$
    כעת נחשב את הגבול בכך נמצא את ערכי $a, b$ ע"י הצבת $c=1$ - 

    $$\lim_{x \rightarrow 1-}\frac{\sqrt[]{x} - 1}{x^2-1}$$
    $$\lim_{x \rightarrow 1-}\frac{\sqrt[]{x} - 1}{(x+1)(x-1)}$$
    $$\lim_{x \rightarrow 1-}\frac{\sqrt[]{x} - 1}{(x+1)(\sqrt[]{x}-1)(\sqrt[]{x}+1)}$$
    $$\lim_{x \rightarrow 1-}\frac{1}{(x+1)(\sqrt[]{x}+1)} = \frac{1}{(1+1)(1+1)} = \frac{1}{4}$$
    $$\Downarrow$$
    $$2a = \frac{1}{4}$$
    $$a = \frac{1}{8}$$
    $$\Downarrow$$
    $$a = \frac{1}{8}, b = \frac{1}{8}, c=1$$
    2. עבור אילו $a, b, c$ לפונקציה יש אי-רציפות סליקה ב- $x=1$?  
    על מנת שתהיה אי רציפות סליקה על גבולות הפונקציה משתי צידי הנקודה המבוקשת צריכים להיות ושנים מערך הפוקנציה בנקודה זו, או הפונקציה לא תהיה מוגדרת בנקודה זו.   
    בנקודה $x=1$ עבור כל ערכי $a,b$ הפונקציה מוגדרת.
    הגבולות שווים בנקודה זו כאשר $a = \frac{1}{8}, b = \frac{1}{8}, c=1$ והגבול עצמו הוא $\frac{1}{4}$ לכן על מנת שתהיה סליקה צריך:  
    
    $$a+b \neq \frac{1}{4}$$
    אך לאחר הצבת $a=b=\frac{1}{8}$ אי שיוויון זה תמיד מתקיים לכן אין ערכים עבור $a,b,c$ עבורה לפונקציה יש רי רציפות סליקה.  

    3. עבור אילו $a, b, c$ לפונקציה יש "קפיצה" ב- $x=1$?  
    על מנת שתהיה קפיצה צריך ששתי הגבולות יתכנסו במובן הצר אך תהיה קפיצה.  
    על מנת גבולות הפונקציה בנקודה $x=1$ כבר הוכחנו כי $a=b, c=1$.  
    על מנת שתתרחש קפיצה - 
    
    $$a+b \neq \frac{1}{4}$$
    $$2a \neq \frac{1}{4}$$
    $$a \neq \frac{1}{8}$$
    $$\Downarrow$$
    $$a=b \neq \frac{1}{8}, c=1$$

    4. עבור אילו $a, b, c$ לפונקציה יש אי-רציפות מסוג II ב- $x=1$?  
    כדי שתהיה אי רציפות מסוג II צריך שאחד הגבולות של הפוקנציה לא יתכנס באופן צר.
    עבור צד שמאל $c\neq 1$ ועבור צד ימין $a \neq b$.

4. תהיה $f_{(x)}$ רציפה בקטע $[0, 1]$ ונתון כי $f_{(x)}\in[0, 1]$ לכל $x\in [0, 1]$.  
הוכח כי קיימת נקודה $x_0\in [0, 1]$ כך ש: $2x_0+1 = e^{f_{(x_0)}}$.
פתרון:

    נגדיר שתי פונקציות חדשות:  
    
    $$g_{(x)} = 2x+1 , 0 \geq x \geq 1$$
    $$h_{(y)} = e^y , 0 \geq y \geq 1$$
    הפונציה $h_{(x)}$ רציפה מכיוון שהיא פונקציה אלמנטרית, בנוסף, הקלטים שלה ($f_{(x)}$) נתונים כרציפים ולכן ניתן להגדיר פונקציה חדשה זו.  
    צ"ל להוכיח:  
    קיים $x_0$ כך ש:
    
    $$g_{(x_0)} = h_{(x_0)}$$

    שתי הפונקציות רציפות וגם עולות מונוטונית **ממש**, ולכן נבדוק את ערכן בקצוות:  

    $$g_{(0)} = 1$$
    $$g_{(1)} = 3$$
    $$f_{(0)} = 1$$
    $$g_{(1)} = e$$

    לפיכך קיימת נקודה אחת לפחות $x_0$ בה

    $$g_{(x_0)} = h_{(x_0)}$$

    מש"ל

5. יהיו $f_{(x)}$ ו-$g_{(x)}$ שתי פונקציות רציפות בקטע $[0, 1]$ המקיימות:  

    $$f_{(0)} = 2, g_{(0)} = -1, f_{(1)} = 3, g_{(1)} = -4$$
    הוכח שלמשוואה - $f^2_{(x)}=g^2_{(x)}$ יש לפחות פתרון אחד ב-$(0,1)$.

    פתרון: 
    נגדיר פונקציות חדשות:  

    $$F_{(x)} = f^2_{(x)}$$
    $$G_{(x)} = g^2_{(x)}$$

    ידוע כי $F_{(x)},G_{(x)}$ גם כן רציפות (הרכבה של פונקציה אלמנטרית חזקה עם פונקציה רציפה).
    כעת נבדוק את ערכי הגבולות $0, 1$ עבור שני הפונקציות:  
    
    $$F_{(0)} = f^2_{(0)} = 2^2 = 4$$
    $$F_{(1)} = f^2_{(1)} = 3^2 = 9$$
    $$G_{(0)} = g^2_{(1)} = (-1)^2 = 1$$
    $$G_{(0)} = g^2_{(1)} = (-4)^2 = 16$$

    מכיוון שרציפות ז"א שקיימת נקודה אחת לפחות $x_0$ אשר:  
    
    $$F_{(x_0)} = G_{(x_0)}$$
    $$\Downarrow$$
    $$f^2_{(x_0)} = g^2_{(x_0)}$$
    מש"ל.

6. הוכח שלמשוואה $x^7+2x^3+\frac{x}{5}-e^{1-x} = 0$ קיים בדיוק פתרון ממשי אחד.  
פתרון:  

$$f_{(x)} = x^7+2x^3+\frac{x}{5}-e^{1-x}$$
$$f'_{(x)} = 7x^6+6x^2+\frac{1}{5}+e^{1-x}$$
הפונקציה $f'_{(x)}$ חיובית לכל $x$, ומכיוון ש$f_{(x)}$ רציפה (הרכבת פונקציות אלמנטריות) אז הפונקציה עולה ממש, בנוסף בגלל ש-

$$f_{(-1)} = -1 -2-\frac{1}{5}-e^2 = -(3.5+e^2)$$
$$f_{(1)} = 1+2+\frac{1}{5}+1 = 4.5$$
ז"א לפי משפט ערך הביניים קיים $-1<c<1$ כך ש-$f_{(c)} = 0$ והוא יחיד כי הפונקציה עולה ממש.  
מש"ל.