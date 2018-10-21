<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex, annotation {
        direction: ltr;
    }
</style>
# פונקציות מרוכבות
#### 21.10.2018
* $$L = X+ iY$$
    * $$\lim_{t \rightarrow t_0} f(t) = L$$
    * $$\lim_{t \rightarrow t_0} x(t) = X$$
    * $$\lim_{t \rightarrow t_0} y(t) = Y$$
    * $$\lim_{t \rightarrow t_0} |f(t) - L| = 0$$
2. $f$ פונקציה מ-R ל-C היא רציפה ב-$t_0$ אם $\lim_{t \rightarrow t_0}f(t) = f(t_0)$
3. הדברים הבאים שקולים:
    * $f(t)$ רציפה
    * $x(t), y(t)$ רציפות
3. $f$ פונקציה מ-R ל-C היא גזירה ב$t_0$ , והנגזרת שלה M אם $\lim_{t \rightarrow t_0}\frac{f(t)-f(t_0)}{t-t_0}$ קיים ושווה M.  
$f'(t_0) = M$
5. $$f'(t_0) = x'(t_0) +iy'(t_0)$$
##### פונקציות מ-C ל-C
$$f(z) = u(x,y) +iv(x,y)$$
6. *משוואות קושי ריימן* - אם $f(z)$ גזירה ב$z_0$ אז הנגזרות החלקיות של $u$ ו-$v$ ביחס ל-$x$ ו-$y$ קיימות ב $(x_0, y_0)$ ו

$$\frac{\delta u}{\delta x} = \frac{\delta v}{\delta y}, \frac{\delta u}{\delta y} = \frac{\delta v}{\delta x}$$
