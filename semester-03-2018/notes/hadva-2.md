<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>

### הגדרות
* הגדרת מספרים K נקראית חסומה מלעיל אם  
$\exists M \in IR | \forall x \in K : x \leq M$

* הגדרת מספרים K נקראית חסומה מלרע אם  
$\exists M \in IR | \forall x \in K : x \geq M$

* קבוצה נקראת __חסומה__ $\Longleftrightarrow$ היא חסומה מלעיל ומלרע
* $M = \sup{K}$ - החסם העליון של K אם הוא החסם מלעיל הקטן ביותר של K.  
אם $\sup{K} \in K$ אז הוא נקרא מקסימום של K ויסומן ע"י $\max{K}$.
* $M = \inf{K}$ - החסם התחתון של K אם הוא החסם מלרע הקטן ביותר של K.  
אם $\inf{K} \in K$ אז הוא נקרא מינימום של K ויסומן ע"י $\min{K}$.
* $\sup{K} = \infty$ - אינה חסומה מלעיל.

#### תרגיל
$A = \{\frac{n-1}{n+1}|n \in N\}$  
$\frac{n-1}{n+1} = \frac{n+1-2}{n+1} = 1 - \frac{2}{n+1}$  
$\Downarrow$  
$\frac{2}{n+1} < 1$  
$\sup{A} = 1$, הקבוצה חסומה מלעיל ע"י 1, $1 \notin A$ לכן לקבוצה אין מקסימום.
$\inf{A} = 0$, הקבוצה חסומה מלרע ע"י 1, $0 \in A$ לכן הוא גם מינימום של הקבוצה.

### גבול של סדרה
##### הגדרה 
מספר ממשי L נקרא גבול של הסדרה a אם:  
$\forall \epsilon > 0 | \exists n_0 \in N | \forall n \geq n_0 : |a_n - L| < \epsilon$ 
