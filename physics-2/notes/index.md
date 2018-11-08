<!-- <!DOCTYPE html> -->
<!-- <script src="https://cdn.jsdelivr.net/npm/texme@0.5.0"></script> -->
<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex, annotation {
        direction: ltr;
    }
</style>
<!-- <textarea> -->

### הרצאה 3
#### שטף חשמלי - electric flux

$$\delta \phi = \vec{E}\cdot \hat{n} \cdot \delta A = \vec{E}\cdot \vec{\delta A}$$

#### תרגול 2
* במערכת SI

    $$k = 8.99\cdot 10^{9}[\frac{Nm^2}{c^2}]$$
    $$\epsilon_0 = 8.95\cdot 10^{-12}[\frac{c^2}{Nm^2}]$$
* במערכת CGS

    $$k = 1$$
    $$\epsilon_0 = \frac{1}{4\pi}$$

#### שדה חשמלי
* נקודתי 

    $$\vec{E}_{(\vec{r})} = \frac{kq}{r^2}\hat{r}$$

חשבו את השדה על ציר הסימטריה של טבעת טעונה בעלת רדיוס a וצפיפות מטען $\lambda$.  

מסימטריה הגלילית ברור כי השדה יהיה רק בציר $z$ ולכן ניקח רק את רכיב $z$ של השדה.

$$\delta E_{z} = k\frac{\delta q}{r^2}\sin \alpha$$
$$\delta q = \frac{\lambda a}{r^3}\delta u$$
$$\delta q = \frac{\lambda a z}{(a^2+z^2)^{\frac{3}{2}}}$$
$$E_{z} = \frac{ka \lambda z}{(a^2+z^2)^{\frac{3}{2}}}\int \delta u$$
$$E_{z} = \frac{2\pi ka \lambda z}{(a^2+z^2)^{\frac{3}{2}}}$$
## 06.11.2018
#### הקשר בין שדה חשמלי ופונטציאל חשמלי

$$\phi_{A\ \ \ [v]} = \int_A^{\infty}\vec{E}\cdot \vec{\delta r}$$
$$\phi_B = \int_B^{\infty}\vec{E}\cdot \vec{\delta r}$$
$$\phi_A - \phi_B = \int_A^{B}\vec{E}\cdot \vec{\delta r}$$
* עבודה

    * $$W_{[J]} = \phi \cdot q$$
    * מטען חיובי ישאף לנוע מפוטנציאל חשמלי גבוה לנמוך
    * מטען שלילי ישאף לנוע מפוטנציאל חשמלי נמוך לגבוה
* אם יש שימור אנרגיה

    $$W_A - W_B = q (\phi_A - \phi_B) = q \Delta \phi = E_{kB} - E_{kA}$$
* שדה קבוע
    * $$\Delta \phi = -\int_A^B \vec{E}\cdot \vec{\delta s} = E \cdot d$$
    * $$E = \frac{\Delta \phi}{d}$$
## 07.11.2018
* 
    שדה דרוש לטיול אלקטרונים באוויר (בקירוב)
    
    $$E_{c} = 30000_{[\frac{V}{cm}]}$$
### שיעור 7 - חוק גאוס הדיפרנציאלי

* $$\oint \vec{E}\cdot \vec{\delta A} = \frac{1}{\epsilon_0}\sum Q_{in} = \frac{1}{\epsilon_0} \int_v \sigma \delta v$$
* $$div \vec{F} = \lim_{V_{i} \rightarrow 0}\frac{1}{V_{i}} \oint_{S_{i}}\vec{F}\vec{\delta a_{i}}$$
* משפט גאוס \ משפט הדיברגנס  
    אם ידועה הפונקציה הסקלרית 
    
    $$div \vec{F}$$
    אז אפשר לקבל את האינטגרל המשטחי על משטח גדול יותר

    * $$\oint \vec{F}\cdot \delta \vec{A} = \sum_{i=1}^N \oint_{S_i} \vec{F} \cdot \delta \vec{a_i} = \sum_{i=1}^N V_i \frac{\oint_{S_i} \vec{F}\cdot \delta \vec{a_i}}{V_i}$$
    * $$\oint \vec{F}\cdot \delta \vec{A} = \int_V div \vec{F}$$
    * שימוש בשדה חשמלי
    
        $$\oint \vec{E}\cdot \delta \vec{A} = \int_V div \vec{E}\delta  v$$
    * 
        חוק גאוס הדיפנרציאלי

        $$div \vec{E} = \frac{\sigma}{\epsilon_0}$$
*
    דיברגנס בקורדינטות קרטזיות  
    נתון שדה וקטורי הכיוון $\hat{x}$, $\hat{y}$ ו-$\hat{z}$ בכל נקודה במרחב :
    
    $$F_{z}(x,y,z)$$
    $$F_{y}(x,y,z)$$
    $$F_{x}(x,y,z)$$
    $$div \vec{F} = \frac{\delta F_x}{\delta x} + \frac{\delta F_y}{\delta y}+ \frac{\delta F_z}{\delta z}$$
* דוגמא 
    גליל אינסופי עם צפיפות מטען $\rho$, צריך למצוא את השדה
    * מבחוץ

        $$E \cdot 2\pi r L = \frac{1}{\epsilon_0}\rho \cdot \pi R^2 L$$
        $$E = \frac{\rho R^2}{2\epsilon_0}\frac{1}{r}$$
    * מבפנים

        $$E \cdot 2\pi r L = \frac{1}{\epsilon_0}\rho \cdot \pi r^2 L$$
        $$E = \frac{\rho R^2}{2\epsilon_0}r$$
## 08.11.2018
* $$k = \frac{1}{4\pi \epsilon_0}$$
*
    שאלה כדורים קונדטריים  
    בחלל בין שני כדורים קונדטריים ברדיוס   

    $$a<b$$
    מצוי מטען בצפיפות נפחית
    
    $$\rho_{(r)} = \frac{A}{r}$$
    המרכז המערכת נמצא מטען נקודתי $Q$.

    1.
        מהו A אם נתון שהשדה בתחום בין שני הכדורים קבוע בגודלו?

        פתרון  
        נחשב את השדה בין הכדורים ומתוכו נסיק את A.  
        נשתמש במשטח גאוס כדורי ברדיוס 

        $$a<r<b$$
        משום שברור שמטעמי סימטריה לשדה יש רק רכיב רדיאלי.  
        
        $$\vec{E}\cdot 4\pi r^2 = \frac{Q_{enclosed}}{\epsilon_0}$$
        $$Q_{enclosed} = Q + \int_a^r \delta  r (4 \pi r^2 \cdot \frac{A}{r})$$
        $$Q_{enclosed} = Q + 4\pi A\int_a^r \delta  r (r)$$
        $$Q_{enclosed} = Q + 2\pi A (r^2 - a^2)$$
        $$\Downarrow$$
        $$\vec{E}\cdot 4\pi r^2 = \frac{Q + 2\pi A (r^2 - a^2)}{\epsilon_0}$$
        $$\vec{E} = \frac{Q + 2\pi A (r^2 - a^2)}{4\pi r^2\epsilon_0}$$
        $$\vec{E} = \frac{Q}{4\pi \epsilon_0 r^2} + \frac{A}{2\epsilon_0} - \frac{Aa^2}{2\epsilon_0 r^2}$$
        $$\frac{A}{2\epsilon_0} \longrightarrow const$$

        על מנת ש$\vec{E}$ יהיה קבוע שני האיברים שתלויים ב$\frac{1}{r^2}$ צריכים להתאפס (אם רוצים להיות מדויקים אז באמת צריך לגזור את $\vec{E}$ ולהשוות ל-0).
        
        $$\frac{Q}{4\pi \epsilon_0 r^2} = \frac{Aa^2}{2\epsilon_0 r^2}$$
        $$A = \frac{Q}{2\pi a^2}$$
    2.
        מהו השדה עבור 
        
        $$r>b$$
        במצב זה?  
        פתרון  

        $$\vec{E}\cdot 4\pi r^2 = \frac{1}{\epsilon_0} (Q+\frac{Q}{a^2}(b^2 - a^2)) $$
        $$\vec{E}_{(\vec{r})} = \frac{Q}{4 \pi r^2 \epsilon_0}\frac{b^2}{r^2}\hat{r}$$

    3.
        מהו הפוטנציאל בכל נק' במרחב?  
        פתרון  
        כאשר מעוניינים למצוא פונטציאל אלקטרוסטטי הכי נוח זה להתחיל עם מקומות שאנחנו יודעים לחשב (בדרך כלל זה ב"חוץ" בגלל תנאי השפה באינסוף) ובסוף לתפור את הפתרונות בפנים בגלל **רציפות של הפוטנציאל**.

        במקרה שלנו: מסעיף ב' ניתן לראות שהמטען הכולל הוא:

        $$Q_{tot} = Q\frac{b^2}{r^2}$$
        מאחר והפונטציאל של מטען נקודתי היוא 
        
        $$\phi = \frac{kq}{r}$$
        אז:
        
        $$\phi_{(r>b)} = \frac{kQb^2}{a^2}\frac{1}{r}$$
        בין שתי הקליפות:
        
        $$\phi_{(r)} - \phi_{(b)} = -\int_b^r \vec{E}\cdot \delta \vec{l}$$
        $$\phi_{(r)} - \phi_{(b)} = -\int_b^r \vec{E}\cdot \delta r$$
        $$\phi_{(r)} - \phi_{(b)} = -\int_b^r \frac{kQ}{a^2}\cdot \delta r$$
        $$\phi_{(r)} - \phi_{(b)} = \frac{kQ}{a^2} (b-r)$$
        $$\phi_{(a<r<b)} = \phi_{(b)} + \frac{kQ}{a^2} (b-r)$$
        $$\phi_{(a<r<b)} = \frac{kQb}{a^2} + \frac{kQ(b-r)}{a^2}$$
        $$\phi_{(a<r<b)} = \frac{2kQb}{a^2} - \frac{kQr}{a^2}$$
        התחום האחרון 

        $$r<a$$
        :
        
        $$\phi_{(r)} - \phi_{(a)} = \int_r^a \vec{E}\cdot \delta r$$
        $$\phi_{(r)} - \phi_{(a)} = \int_r^a \frac{kQ}{r^2} \delta r$$
        $$\phi_{(r)} - \phi_{(a)} = kQ\frac{1}{r}|_r^a$$
        $$\phi_{(r)} - \phi_{(a)} = -kQ (\frac{1}{a} - \frac{1}{r})$$
        $$\phi_{(r)} - \phi_{(a)} = \frac{kQ}{r} - \frac{kQ}{a}$$
        $$\phi_{(r<a)} = \phi_{(a)} + \frac{kQ}{r} - \frac{kQ}{a}$$
        $$\phi_{(r<a)} = 2kQ\frac{b-a}{a^2} + \frac{kQ}{r}$$