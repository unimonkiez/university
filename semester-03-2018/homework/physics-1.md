<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>

1. 
$$ \bar{a} = (10, 0) $$
$$ \bar{b} = (15 \cdot \cos{25}, 15 \cdot \sin{25}) $$
$$ \bar{a} + \bar{b} = (10 + 15 \cdot \cos{25}) \hat{x} + (15 \cdot \sin{25})\hat{y} $$
$$ |\bar{a} + \bar{b}| = \sqrt{(10 + 15 \cdot \cos{25})^2 + (15 \cdot \sin{25})^2} $$
2.
$$ |\bar{a}| = 11 $$
$$ |\bar{b}| = 12 $$
$$ |\bar{a} + \bar{b}| = 17 $$
$$ \measuredangle \alpha = ? $$

  פתרון:

$$ \bar{a} = (11, 0) $$
$$ \bar{b} = (12 \cdot \cos{\alpha}, 12 \cdot \sin{\alpha}) $$
$$ \bar{a} + \bar{b} = \bar{v} = (11 + 12\cos{\alpha}, 12\sin{\alpha}) $$
$$ \Downarrow $$
$$ |\bar{v}| = \sqrt{(11 + 12\cos{\alpha})^2 + (12\sin{\alpha})^2} = 17 $$
$$ (11 + 12\cos{\alpha})^2 + (12\sin{\alpha})^2 = 17^2 $$
$$ 11^2 + 24\cdot11 \cdot\cos{\alpha} + (12\cos{\alpha})^2 + (12\sin{\alpha})^2 = 17^2 $$
$$ 24\cdot11 \cdot\cos{\alpha} + 144\cos{^2\alpha} + 144\sin{^2\alpha} = 17^2 - 11^2 $$
$$ 24\cdot11 \cdot\cos{\alpha} + 144\cos{^2\alpha} + 144(1 - \cos{^2\alpha}) = 17^2 - 11^2 $$
$$ x = \cos{\alpha} $$
$$ 24\cdot11 \cdot x + 144x^2 + 144(1 - x^2) = 17^2 - 11^2 $$
$$ 12 \cdot 2 \cdot 11 x + 12^2 = 17^2 - 11^2 $$
$$ 22 x = \frac{17^2 - 11^2 - 12^2}{12} $$
$$ x = \frac{17^2 - 11^2 - 12^2}{12 \cdot 22} $$
$$ \alpha \simeq 84.78\degree $$

3.
$$ \alpha = 46 \degree$$
$$ (5\sin{46}, 5\cos{46}) $$

4. $\vec{a} = 5\cdot {m\Big/s^2}$  
    1. $\alpha_y = 30\degree \Rightarrow \alpha_x = 120 \degree$ (המרה לציר X לצורך הנוחות)

    $$ \vec{\alpha} = (5 \cdot \sin{120})\hat{x} + (5 \cdot \cos{120})\hat{y}\Rightarrow 5 (\sin{60}\hat{x} + \cos{60}\hat{y}) $$

    2. $\alpha_y = -90\degree \Rightarrow \alpha_x = 0 \degree$ (המרה לציר X לצורך הנוחות)

    $$ \vec{\alpha} = (5 \cdot \sin{0})\hat{x} + (5 \cdot \cos{0})\hat{y} \Rightarrow 5\hat{y} $$

5.  
    1. $(x_2 - x_1, y_2 - y_1, z_2 - z_1)$
    2.  $\sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2}$
6.  
    1. $(0 - 1, 2 - 2, 2 - 4, -6 - 5)$  
    $\Downarrow$  
    $(-1, 0, -2, -11)$
    2. $\sqrt{1^2 + 0^2 + 2^2 + 11^2}$

7. קודם כל נחשב את הווקטור  

$$\vec{\alpha} = (4 - 1, 5, -7 - 4) \Rightarrow (3, 5, -11) $$
$$|\vec{\alpha}| = \sqrt{3^2 + 5^2 + (-11)^2} \Rightarrow \sqrt{9 + 25 + 121} \Rightarrow \sqrt{155} $$

8. נתון  
    * $\vec{v} = (x, y)$
    * $x = 2st$
    * $y = t^2 - s^2$
    * $s, t \in N$

  $$
  |\vec{v}| = \sqrt{x^2 + y^2} \Rightarrow \sqrt{(2st)^2 + (t^2 - s^2)^2} \Rightarrow \sqrt{4s^2t^2 + t^4 -2t^2s^2 + s^4}
  $$  
  $$ \Downarrow $$  
  $$
  \sqrt{2s^2t^2 + t^4 + s^4} = \sqrt{(s^2 + t^2)^2} = s^2 + t^2
  $$
  בגלל שs וt שייכים לקבוצת המספרים הטבעיים אז

  $$ |\vec{v}| = s^2 + t^2 \in N $$ 

9.  נתון
    * $\vec{a} = (0, 0, 1)$
    * $\vec{b} = (1, 0, -2)$

    תשובות
    1.  סכום

    $$ (1, 0, -1) $$
    2. הפרש

    $$ (-1, 0, 3) $$
    3. מכפלה סקלארית

    $$ \bar{a} * \bar{b} = a_x*b_x + a_x*b_x + a_z*b_z \Rightarrow -2 $$
    4. זווית $\alpha\degree$

    $$ \bar{a} * \bar{b} = |\bar{a}| * |\bar{b}| * \cos{\alpha} $$
    $$ -2 = |\bar{a}| * |\bar{b}| * \cos{\alpha} $$
    $$ -2 = 1 * \sqrt{5} * \cos{\alpha} $$
    $$ \cos{\alpha} = \frac{-2}{\sqrt{5}}  $$
    5. מכפלה ווקטורית

    $$\bar{a} \otimes \bar{b} = (a_yb_z-a_zb_y)\hat{x} - (a_xb_z-a_zb_x)\hat{y} + (a_xb_y-a_yb_x)\hat{z}$$
    $$\bar{a} \otimes \bar{b} = (0 \cdot (-2) - ((-1) \cdot 0))\hat{x} - (0 \cdot (-2) - 1 \cdot 1)\hat{y} + (0 \cdot 0 - 0 \cdot 1)\hat{z} = - \hat{y} $$
    כדי למצוא את שתי הוקטורים פשוט נהפוך את ערכי x, y, z, ולכן -

    $$\vec{v}_{12} = \pm1\hat{y}$$

10. נתון
    * $\vec{a} = 2\hat{x} + 3\hat{y} - \hat{z}$
    * $\vec{b} = \hat{x} - 2\hat{y} + \hat{z}$

    תשובות
    1. $\hat{a} + \hat{b}$

    $$(2+1)\hat{x} + (3-2)\hat{y} + (1-1)\hat{z}$$
    $$3\hat{x} + \hat{y}$$
    2. $\hat{a} - \hat{b}$

    $$(1-2)\hat{x} + (-2-3)\hat{y} + (1-(-1))\hat{z}$$
    $$-\hat{x} -5 \hat{y} +2 \hat{z}$$
    3. $\hat{a} \cdot \hat{b}$

    $$(a_x\cdot b_x) + (a_y\cdot b_y) + (a_z \cdot y_z)$$
    $$\Downarrow$$
    $$(1\cdot2) + (-2\cdot(-3)) + (1 \cdot (-1))$$
    $$2 +6  -1 $$
    $$\Downarrow$$
    $$7$$
    4. $\alpha\degree = ?$

    $$\cos\alpha = \frac{\vec{a} \cdot \vec{b}}{ |\vec{a}||\vec{b}| }$$
    $$\Downarrow$$
    $$\cos\alpha = \frac{7}{ \sqrt{2^2+3^2+(-1)^2}\sqrt{1^2+(-2)^2+1^2} }$$
    $$\cos\alpha = \frac{7}{ \sqrt{4+9+1}\sqrt{1+4+1} }$$
    $$\cos\alpha = \frac{7}{ \sqrt{15}\sqrt{61} }$$
    $$ \alpha \simeq 42.27\degree $$
    5. $\hat{a} \otimes \hat{b}$

    $$\bar{a} \otimes \bar{b} = (a_yb_z-a_zb_y)\hat{x} - (a_xb_z-a_zb_x)\hat{y} + (a_xb_y-a_yb_x)\hat{z}$$
    $$\Downarrow$$
    $$\bar{a} \otimes \bar{b} = (3 \cdot 1-(-1) \cdot (-2))\hat{x} - (2 \cdot 1-(-1)\cdot1)\hat{y} + (2\cdot(-2)-3\cdot 1)\hat{z}$$
    $$\bar{a} \otimes \bar{b} = (3-2)\hat{x} - (2+1)\hat{y} + (-4-3)\hat{z}$$
    $$\bar{a} \otimes \bar{b} = \hat{x} -3\hat{y} -7\hat{z}$$

11. להוכיח
    * $\frac{a}{\sin{\alpha}}=\frac{b}{\sin{\beta}}=\frac{c}{\sin{\gamma}}$

    תשובה  
    משפט הסינוסים (חישוב שטח המקבילית), כאשר ${\gamma}$ היא הזווית בין הווקטורים:

    $$\vec{a}\otimes\vec{b} = |\vec{a}||\vec{b}|\sin{\gamma}$$

    שטח המקבילית זהה גם עבור שאר הוקטורים במשולש, מכיוון ששטח המשולש הוא למעשה שטח המקבילית חלקי 2, ושטח המשולש תמיד שווה לעצמו

    $$\frac{\vec{a}\otimes\vec{b}}{2} = \frac{ab\sin{\gamma}}{2} = \frac{bc\sin{\alpha}}{2} = \frac{ca\sin{\beta}}{2}$$
    $$\frac{ab\sin{\gamma}}{2} = \frac{bc\sin{\alpha}}{2} = \frac{ca\sin{\beta}}{2}$$
    $$ab\sin{\gamma} = bc\sin{\alpha} = ca\sin{\beta}$$
    $$\Downarrow$$
    $$ab\sin{\gamma} = bc\sin{\alpha} \Rightarrow a\sin{\gamma} = c\sin{\alpha}\Rightarrow \frac{a}{\sin{\alpha}} = \frac{c}{\sin{\gamma}}$$
    $$ab\sin{\gamma} = ca\sin{\beta} \Rightarrow b\sin{\gamma} = c\sin{\beta}\Rightarrow \frac{b}{\sin{\beta}} = \frac{c}{\sin{\gamma}}$$

    $$\Downarrow$$
    $$\frac{a}{\sin{\alpha}}=\frac{b}{\sin{\beta}}=\frac{c}{\sin{\gamma}}$$

11. קובייה בגודל 1x1x1  
    * $\vec{v_1} = \hat{x} + \hat{y} + \hat{z}$
    * $\vec{v_2}$ -  
    מנקודה $(\hat{y} + \hat{z})$ לנקודה $(\hat{x})$  
    $\vec{v_2} = \hat{x} - \hat{y} - \hat{z}$

    $$\cos\alpha = \frac{\vec{a} \cdot \vec{b}}{ |\vec{a}||\vec{b}| }$$
    $$\Downarrow$$
    $$\cos\alpha = \frac{(1\cdot1)+(1\cdot(-1))+(1\cdot(-1))}{ \sqrt{1+1+1}\sqrt{1+1+1} }$$
    $$\cos\alpha = \frac{-1}{ \sqrt{3}\sqrt{3} }$$
    $$\cos\alpha = -\frac{1}{3}$$
    $$\cos\alpha = 70.52\degree$$
