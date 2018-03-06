<style>
    html {
        direction: rtl;
    }
    eqn {
        direction: ltr;
    }
</style>
# תרגול 6.3.2018 
* חיבור וקטורים

  $$\bar{a} + \bar{b} = (a_x + b_x)\hat{x} + (a_y + b_y)\hat{y}$$
* מכפלה סקלרית

$$\bar{a} * \bar{b} = |\bar{a}| * |\bar{b}| * \cos{\alpha}$$

* מכפלה וקטורית  
יש להחליף לסירוגין בין (+) ו (-) כשמתחילים ב (+)

$$\bar{a} \otimes \bar{b} = (a_yb_z-a_zb_y)\hat{x} - (a_xb_z-a_zb_x)\hat{y} + (x_yb_y-a_yb_x)\hat{z}$$

## פתרון תרגיל בית 1

$$ \bar{a} = (10, 0) $$
$$ \bar{b} = (15 * \cos{25}, 15 * \sin{25}) $$
$$ \bar{a} + \bar{b} = (10 + 15 * \cos{25}) \hat{x} + (15 * \sin{25})\hat{y} $$
$$ |\bar{a} + \bar{b}| = \sqrt{(10 + 15 * \cos{25})^2 + (15 * \sin{25})^2} $$

## פתרון תרגיל בית 3

$$ (5\sin{46}, 5\cos{46}) $$

## פתרון תרגיל בית 5
* א

$$ (x_2 - x_1, y_2 - y_1, z_2 - z_1) $$
* ב

$$ \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2} $$

## פתרון תרגיל בית 6
* א

$$ (0 - 1, 2 - 2, 2 - 4, -6 - 5) $$
$$ (-1, 0, -2, -11) $$
* ב

$$ \sqrt{1^2 + 0^2 + 2^2 + 11^2} $$

## פתרון תרגיל בית 9
* א

$$ (1, 0, -1) $$
* ב

$$ (-1, 0, 3) $$
* ג

$$ \bar{a} * \bar{b} = a_x*b_x + a_x*b_x + a_z*b_z \Rightarrow -2 $$
* ד

$$ \bar{a} * \bar{b} = |\bar{a}| * |\bar{b}| * \cos{\alpha} $$
$$ -2 = |\bar{a}| * |\bar{b}| * \cos{\alpha} $$
$$ -2 = 1 * \sqrt{5} * \cos{\alpha} $$
$$ \cos{\alpha} = \frac{-2}{\sqrt{5}}  $$
* ה

$$ \pm1\hat{y}$$

* זמן למהירות

$$\dot{x}(t) = \frac{\delta x}{\delta t} = \frac{x(t + \Delta t) - x(\Delta t)}{\Delta t}$$

## פתרון תרגיל בית 15
נתון

$$x(t) = 5\epsilon^{-\gamma t} \cos {\omega t}$$
* א

$$ \dot{x}(t) = 5 \epsilon^{-\gamma t} (-\gamma) \cos{\omega t} + 5 \epsilon^{-\gamma t} (-\sin{\omega t})\omega $$
* ג

$$ [\omega] = \frac{1}{t}$$
$$ [\gamma] = \frac{1}{t}$$
