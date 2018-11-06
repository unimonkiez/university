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