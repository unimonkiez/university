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