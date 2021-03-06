<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# הסתברות וסטטיסטיקה
#### 21.10.2018

* לבחור k איברים מתוך קבוצה בת $n$ איברים

    ||עם חזרות|בלי חזרות|
    |:-:|:-:|:-:|
    |סדר חשוב - פרמוטציה|$n^k$|$\frac{n!}{(n-k)!}$|
    |סדר לא חשוב - קומבינציה|$(_{n-1}^{n+k-1})$|$(_k^n) = \frac{n!}{(n-k)!k!}$|
* $$(_0^n) = 1$$
* $$(_1^n) = n$$
* $$(_k^n) = (_{k}^{n-1}) + (_{k-1}^{n-1})$$
#### 22.10.2018 - תרגול
* 
    כמה אפשרויות ישנן לבחור 3 ילדים מתוך 10 לוועד בו כל התפקידים זהים ותלמיד לא יכול לקבל יותר מתפקיד אחד?

    $$(_{3}^{10}) = \frac{10!}{7!3!} = \frac{10\cdot 9\cdot 8}{1\cdot 2\cdot 3} = 120$$
*   מחלקים 3 פרסים זהים ל-10 ילדיןף כל ילד יכול לקבל יותר מפרס אחד.

    $$(_{k}^{n+k-1}) = (_3^{12}) = 220$$
*
    מה הסיכוי לזכות בלוטו, כאשר בטופס יש בחירה של 6 מספרים מתוך 37 מסםרים, ובנוסף מספר חזק בין 1 ל-8?

    $$(_{6}^{37}) = 2324784$$
    $$(_{1}^{8}) = 8$$
    $$\Downarrow$$
    $$\Omega = (_{6}^{37})\cdot (_{1}^{8}) = 18598272$$
*
    שלושה בנים ושלוש בנות מסתדרים לצילום בשורה אחת כך שכל הבנים עומדים זה ליד זה וכל הבנות עומדות זו ליד זו.  
    בכמה אופנים שונים יש לסדר את הבנים והבנות?

    $$3!3!2!$$
     לפי הטבלה לקבוצה אחת:
    
    $$\frac{3!}{(3-3)!}$$

*  
    יש לסדר 7 ילדים בשורה, אך רחל ומירב ברוגז ואינן רוצות לשבת זו על יד זו.  
    * בכמה צורות אפשר לסדר את הילדים?  
    תשובה:  
    סך האפשרויות - $7!$  
    סך האפשרויות בהן רחל ומירב יושבות אח ליד השנייה $6!2!$  
    הסתכלנו על רחל ומירב כאיבר אחד, כפול מספר האפשרויות שאפשר לסדר אותן.  
    תשובה סופית - $7!-6!2!$  
    * אותו הדבר במעגל?
    סך האפשרויות: $\frac{7!}{7} = 6!$  
    תשובה סופית:
    
    $$6!-5!2!$$
*
    בכיסו של סוחר 6 מטבעות נחושת, 4 אלומיניום, 3 זהב.  
    הסוחר מוציא 3 מטבעות מכיסו, מה הן מספר האפשרויות (לא סיכוי) שיוציא מטבעות רק מאותו הסוג?
    
    $$(_{3}^{6}) + (_{3}^{4}) + (_{3}^{3})$$
    מספר האפשרויות שוודאות לא זהים:  

    $$(_{3}^{13}) - ((_{3}^{6}) + (_{3}^{4}) + (_{3}^{3}))$$
#### 29.10.2018 - תרגול
* $$P(A^{c})=1-P(A)$$
* $$A\subseteq B \Downarrow$$
    * $$P(B / A) = P(B)-P(A)$$
    * $$P(A) \leq P(B)$$
* $$P(\empty) = 0$$
* $$\Downarrow$$
    * $$P(A\cup B) = P(A) + P(B) - P(A\cap B)$$
    * $$P(A\cap B) = P(A) + P(B) - P(A\cup B)$$
* מאורעות בלתי תלויים
    * $$P(A \cap B) = P(A)\cdot P(B)$$
#### 05.11.2018 - תרגול
* הסתברות מותנית
    * **הגדרה** - התסברות מותנית היא הסתברות של מאורע כלשהו A, בהינתן שמאורע B קרה.  
    $P(A|B)$ - הסתברות של A בהינתן B.
    * $$P(A|B) = \frac{P(A\cap B)}{P(B)}$$
* $$P(A|B)\cdot P(B) = P(A\cap B) = P(B|A)\cdot P(A)$$
*   נוסחאת ההסתברות השלמה
    
    $$P(B) = \sum_{i=1}^{\infty}P(B|A_i)\cdot P(A_i)$$
*   נוסחאת בייס
    
    $$P(A|B) = \frac{P(A \cap B)}{P(B)} = \frac{P(B|A)\cdot P(A)}{\sum_{i=1}^{\infty}P(B|A_i)\cdot P(A_i)}$$
* שאלה:  
    בניסוי הנערך על חיזור של נשים פנויות לגברים פנויים התגלה ש:
    1. ב-60% מהמקרים הגבר חשב שהבחורה התנהגה בצורה נחמדה.
    2. מתוך המקרים שבהם הגבר חשב שהבחורה התנהגה נחמד התגלה שהיא הייתה מעוניינת בו ב-40% מהמקרים.
    3. מתוך המקרים שבהם הגבר חשב שהבחורה לא התנהגה נחמד התגלה שהיא מעוניינת בו ב-15% המקרים.  

    חשב את הסכוי שאם בחורה מעוניינת בגבר, הגבר יחשוב שהיא נחמדה.

    פתרון:  
    A - גבר חשב שהבחורה מתנהגת נחמד  
    B - הבחורה מעוניינת בגבר


    $$P(A) = 0.6$$
    $$P(A^c) = 0.4$$
    $$P(B|A) = 0.4$$
    $$P(B|A^c) = 0.15$$
    $$\Downarrow$$
    $$P(A|B) = 0.8$$
#### 12.11.2018 - תרגול
*
    הטלת שתי קוביות 
    
    $$\Omega = \{ (i,j) | i,k\in \{1,2,3,4,5,6\} \}$$

    *
        אז נגדיר משתנה מקרי סכום של הקוביות

        $$x_{(a,b)} = a+b$$

        לכן מתקיים
        
        *    $$x_{(1,2)} = 3$$
        *    $$x_{(3,2)} = 5$$
        *
            $$x^{-1}_{(3)} = \{(1,2), (2,1)\}$$
        *
            $$x^{-1}_{([-\infty, 3])} = \{(1,2), (2,1), (1,1)\}$$
        *
            $$x^{-1}_{(0)} = \empty$$
        *
            $$x^{-1}_{((-8,14))} = \Omega$$
*
    מטילים מטבע 0,1 שלוש פעמים אז 

    $$\Omega = \{(0,0,0),(0,0,1),(0,1,0),(1,0,0),(1,1,0),(1,0,1),(0,1,1),(1,1,1)\}$$
    $$|\Omega| = 2^3 = 8$$

    * x משתנה מקרי המטא את מספר הפעמים שהתקבל 1
    * y משתנה מקרי המטא את מספר הפעמים שהתקבל 0
    
    * $$P_{(x=2)} = P(\{(1,1,0),(1,0,1),(0,1,1)\}) = \frac{3}{8}$$
    *
        האם x וy שווים?
        
        $$A = \{(1,1,1)\}$$
        $$x_{(A)} = 3$$
        $$y_{(A)} = 0$$

        לכן x,y משתנים מקריים שאינם שווים כי הם מוגדרים שונה.  
    *
        האם x וy שווי התפלגות?

        $$P_{(x=t)} = \{
            t=0 \Rightarrow \frac{1}{8},
            t=1 \Rightarrow \frac{3}{8},
            t=2 \Rightarrow \frac{3}{8},
            t=3 \Rightarrow \frac{1}{8}
            \}$$
        $$P_{(y=t)} = \{
            t=0 \Rightarrow \frac{1}{8},
            t=1 \Rightarrow \frac{3}{8},
            t=2 \Rightarrow \frac{3}{8},
            t=3 \Rightarrow \frac{1}{8}
            \}$$
        מכיוון שהיחסים שווים **עבור אותם ערכי t** לכן
        
        $$P_{(x=t)} = P_{(y=t)}$$
        שיווי התפלגות
    *
        תוחלת
        
        $$E_{(x)} = \sum t\cdot P_{x(t)}$$
        $$\Downarrow$$
        $$E_{(x)} = 0 \cdot \frac{1}{8} + 1 \cdot \frac{3}{8} + 2 \cdot \frac{3}{8} + 3 \cdot \frac{1}{8}$$
        $$E_{(x)} = \frac{3}{2}$$