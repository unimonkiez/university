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

12. קובייה בגודל 1x1x1  
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

13.
    1. להוכיח  
    $|A + B|^2 + |A - B|^2 = 2(|A|^2+|B|^2)$  
    תשובה  

    $$|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}$$
    $$\Downarrow$$
    $$\sqrt{(A+B)_x^2 + (A+B)_y^2 + (A+B)_z^2}^2 + \sqrt{(A-B)_x^2 + (A-B)_y^2 + (A-B)_z^2}^2 = 2 \cdot (\sqrt{A_x^2 + A_y^2 + A_z^2}^2 + \sqrt{B_x^2 + B_y^2 + B_z^2}^2)$$
    $$(A+B)_x^2 + (A+B)_y^2 + (A+B)_z^2 + (A-B)_x^2 + (A-B)_y^2 + (A-B)_z^2 = 2 \cdot (A_x^2 + A_y^2 + A_z^2 + B_x^2 + B_y^2 + B_z^2)$$
    $$A_x^2 \xcancel{+2A_xB_x} + B_x^2 + A_y^2 \xcancel{+2A_yB_y} + B_y^2 + A_z^2 \xcancel{+2A_zB_z} + B_z^2 + A_x^2 \xcancel{-2A_xB_X} + B_x^2 + A_y^2 \xcancel{-2A_yB_y} + B_y^2 + A_z^2 \xcancel{-2A_zB_z} + B_z^2 = 2 \cdot (A_x^2 + A_y^2 + A_z^2 + B_x^2 + B_y^2 + B_z^2)$$
    $$A_x^2 + B_x^2 + A_y^2 + B_y^2 + A_z^2 + B_z^2 + A_x^2 + B_x^2 + A_y^2 + B_y^2 + A_z^2 + B_z^2 = 2 \cdot (A_x^2 + A_y^2 + A_z^2 + B_x^2 + B_y^2 + B_z^2)$$
    $$2A_x^2 + 2B_x^2 + 2A_y^2 + 2B_y^2 + 2A_z^2 + 2B_z^2 = 2 \cdot (A_x^2 + A_y^2 + A_z^2 + B_x^2 + B_y^2 + B_z^2)$$
    $$2 \cdot (A_x^2 + A_y^2 + A_z^2 + B_x^2 + B_y^2 + B_z^2) = 2 \cdot (A_x^2 + A_y^2 + A_z^2 + B_x^2 + B_y^2 + B_z^2)$$
    **מש"ל**  

    2. כלל המקבילית הוא משפט בגאומטריה אוקלידית, הקובע כי סכום ריבועי ארבע צלעות המקבילית שווה לסכום ריבועי האלכסונים. במקרה שהמקבילית היא מלבן, האלכסונים שווים ומתקבל משפט פיתגורס.

14.
    1. $\vec{A}\otimes(\vec{B}\otimes\vec{C}) = (\vec{A}\cdot\vec{C})\vec{B}-(\vec{A}\cdot\vec{B})\vec{C}$

    נחשב את צד שמאל

    $$\vec{A}\otimes(\vec{B}\otimes\vec{C})$$
    <div style="font-size: 14px;">

    $$\vec{A}\otimes[
    (B_yC_z-B_zC_y)\hat{x}+
    (B_zC_x-B_xC_z)\hat{y}+
    (B_xC_y-B_yC_x)\hat{z}
    ]$$
    $$
    (A_y(B_xC_y-B_yC_x)-A_z(B_zC_x-B_xC_z))\hat{x}+
    (A_z(B_yC_z-B_zC_y)-A_x(B_xC_y-B_yC_x))\hat{y}+
    (A_x(B_zC_x-B_xC_z)-A_y(B_yC_z-B_zC_y))\hat{z}
    $$
    $$
    (A_yB_xC_y-A_yB_yC_x-A_zB_zC_x+A_zB_xC_z)\hat{x}+
    (A_zB_yC_z-A_zB_zC_y-A_xB_xC_y+A_xB_yC_x)\hat{y}+
    (A_xB_zC_x-A_xB_xC_z-A_yB_yC_z-A_yB_zC_y)\hat{z}
    $$
    $$
    (A_yB_xC_y+A_zB_xC_z)\hat{x}+
    (A_zB_yC_z+A_xB_yC_x)\hat{y}+
    (A_xB_zC_x+A_yB_zC_y)\hat{z}
    -(
    (A_yB_yC_x-A_zB_zC_x)\hat{x}+
    (A_zB_zC_y-A_xB_xC_y)\hat{y}+
    (A_xB_xC_z-A_yB_yC_z)\hat{z}
    )
    $$
    $$
    (B_x(A_yC_y+A_zC_z))\hat{x}+
    (B_y(A_zC_z+A_xC_x))\hat{y}+
    (B_z(A_xC_x+A_yC_y))\hat{z}
    -(
    (C_x(A_yB_y+A_zB_z))\hat{x}+
    (C_y(A_zB_z+A_xB_x))\hat{y}+
    (C_z(A_xB_x+A_yB_y))\hat{z}
    )
    $$
    נוסיף $A_xB_xC_x\hat{x}+A_yB_yC_y\hat{y}+A_zB_zC_z\hat{z}$ לשני האגפים כך שיבטלו אחד את השני

    $$
    (B_x(A_yC_y+A_zC_z)+A_xB_xC_x)\hat{x}+
    (B_y(A_zC_z+A_xC_x)+A_yB_yC_y)\hat{y}+
    (B_z(A_xC_x+A_yC_y)+A_zB_zC_z)\hat{z}
    -(
    (C_x(A_yB_y+A_zB_z)+A_xB_xC_x)\hat{x}+
    (C_y(A_zB_z+A_xB_x)+A_yB_yC_y)\hat{y}+
    (C_z(A_xB_x+A_yB_y)+A_zB_zC_z)\hat{z}
    )
    $$
    $$
    (B_x(A_xC_x+A_yC_y+A_zC_z))\hat{x}+
    (B_y(A_xC_x+A_yC_y+A_zC_z))\hat{y}+
    (B_z(A_xC_x+A_yC_y+A_zC_z))\hat{z}
    -(
    (C_x(A_xB_x+A_yB_y+A_zB_z))\hat{x}+
    (C_y(A_xB_x+A_yB_y+A_zB_z))\hat{y}+
    (C_z(A_xB_x+A_yB_y+A_zB_z))\hat{z}
    )
    $$
    $$
    (B_x(\vec{A}\cdot\vec{C}))\hat{x}+
    (B_y(\vec{A}\cdot\vec{C}))\hat{y}+
    (B_z(\vec{A}\cdot\vec{C}))\hat{z}
    -(
    (C_x(\vec{A}\cdot\vec{B}))\hat{x}+
    (C_y(\vec{A}\cdot\vec{B}))\hat{y}+
    (C_z(\vec{A}\cdot\vec{B}))\hat{z}
    )
    $$
    $$
    (B_x\hat{x}+B_y\hat{y}+B_z\hat{z})(\vec{A}\cdot\vec{C})
    -
    (C_x\hat{x}+C_y\hat{y}+C_z\hat{z})(\vec{A}\cdot\vec{B})
    $$
    $$
    LHS=\vec{B}(\vec{A}\cdot\vec{C})
    -
    \vec{C}(\vec{A}\cdot\vec{B})=RHS
    $$
    
    </div>

    2. $\vec{A}\otimes(\vec{B}\otimes\vec{C})+\vec{C}\otimes(\vec{A}\otimes\vec{B})+\vec{B}\otimes(\vec{C}\otimes\vec{A})=0$
    נציב בנוסחא מסעיף קודם: $\vec{A}\otimes(\vec{B}\otimes\vec{C}) = (\vec{A}\cdot\vec{C})\vec{B}-(\vec{A}\cdot\vec{B})\vec{C}$  

    $$
    (\vec{A}\cdot\vec{C})\vec{B}-(\vec{A}\cdot\vec{B})\vec{C} +
    (\vec{C}\cdot\vec{B})\vec{A}-(\vec{C}\cdot\vec{A})\vec{B}
    (\vec{B}\cdot\vec{A})\vec{C}-(\vec{B}\cdot\vec{C})\vec{A}
    =\vec{0}
    $$
    $$
    \vec{A}(\vec{C}\cdot\vec{B}-\vec{B}\cdot\vec{C}))+
    \vec{B}(\vec{A}\cdot\vec{C}-\vec{C}\cdot\vec{A}))+
    \vec{C}(\vec{A}\cdot\vec{B}-\vec{B}\cdot\vec{A}))
    =\vec{0}
    $$
    $$\vec{v_1}\cdot\vec{v_2}=\vec{v_2}\cdot\vec{v_1}$$
    $$\Downarrow$$
    $$
    0\vec{A}+
    0\vec{B}+
    0\vec{C}
    =\vec{0}
    $$
    **מש"ל**

    3. תנאי ל-$\vec{A}\otimes(\vec{B}\otimes\vec{C})=(\vec{A}\otimes\vec{B})\otimes\vec{C}$  

    $$\vec{A}\otimes(\vec{B}\otimes\vec{C})=(\vec{A}\otimes\vec{B})\otimes\vec{C}$$
    $$
    \vec{A}\otimes(\vec{B}\otimes\vec{C})=-\vec{C}\otimes(\vec{A}\otimes\vec{B})
    $$
    $$
    \cancel{\vec{B}(\vec{A}\cdot\vec{C})}
    \cancel{-}\vec{C}(\vec{A}\cdot\vec{B})
    =
    \cancel{-}\vec{A}(\vec{B}\cdot\vec{C})
    \cancel{+\vec{B}(\vec{A}\cdot\vec{C})}
    $$
    $$
    \vec{C}(\vec{A}\cdot\vec{B})
    =
    \vec{A}(\vec{B}\cdot\vec{C})
    $$
    $$\Downarrow$$
    B תמיד במכפלה סקלארית, ולכן רק כש$\vec{A}$ ו$\vec{C}$ שווים אז המשוואה נכונה.

    4. $(\vec{A}\otimes\vec{B})\cdot(\vec{C}\otimes\vec{D})=(\vec{A}\cdot\vec{C})(\vec{B}\cdot\vec{D})-(\vec{A}\cdot\vec{D})(\vec{B}\cdot\vec{C})$

    $$RHS=(\vec{A}\cdot\vec{C})(\vec{B}\cdot\vec{D})-(\vec{A}\cdot\vec{D})(\vec{B}\cdot\vec{C})$$
    $$LHS=(\vec{A}\otimes\vec{B})\cdot(\vec{C}\otimes\vec{D})$$
    <div style="font-size: 9px;">

    $$LHS=(
    (A_yB_z-A_zB_y)\hat{x}+
    (A_zB_x-A_xB_z)\hat{y}+
    (A_xB_y-A_yB_x)\hat{z}
    )\cdot(
    (C_yD_z-C_zD_y)\hat{x}+
    (C_zD_x-C_xD_z)\hat{y}+
    (C_xD_y-C_yD_x)\hat{z}
    )$$
    $$LHS=
    (A_yB_z-A_zB_y)(C_yD_z-C_zD_y)+
    (A_zB_x-A_xB_z)(C_zD_x-C_xD_z)+
    (A_xB_y-A_yB_x)(C_xD_y-C_yD_x)
    $$
    $$LHS=
    A_yB_zC_yD_z-A_yB_zC_zD_y-A_zB_yC_yD_z+A_zB_yC_zD_y+
    A_zB_xC_zD_x-A_zB_xC_xD_z-A_xB_zC_zD_x+A_xB_zC_xD_z+
    A_xB_yC_xD_y-A_xB_yC_yD_x-A_yB_xC_xD_y+A_yB_xC_yD_x
    $$
    $$LHS=
    (
    A_yB_zC_yD_z+A_zB_yC_zD_y+A_zB_xC_zD_x+A_xB_zC_xD_z+A_xB_yC_xD_y+A_yB_xC_yD_x
    )
    -(
    A_yB_zC_zD_y+A_zB_yC_yD+A_zB_xC_xD_z+A_xB_zC_zD_x+A_xB_yC_yD_x+A_yB_xC_xD_y
    )
    $$
    נוסיף $A_xB_xC_xD_x+A_yB_yC_yD_y+A_zB_zC_zD_z$ לשני האגפים

    $$LHS=
    (
    A_yB_zC_yD_z+A_zB_yC_zD_y+A_zB_xC_zD_x+A_xB_zC_xD_z+A_xB_yC_xD_y+A_yB_xC_yD_x
    +A_xB_xC_xD_x+A_yB_yC_yD_y+A_zB_zC_zD_z
    )
    -(
    A_yB_zC_zD_y+A_zB_yC_yD+A_zB_xC_xD_z+A_xB_zC_zD_x+A_xB_yC_yD_x+A_yB_xC_xD_y
    +A_xB_xC_xD_x+A_yB_yC_yD_y+A_zB_zC_zD_z
    )
    $$
    $$LHS=
    (
    (A_xC_x+A_yC_y+A_zC_z)
    (B_xD_x+B_yD_y+B_zD_z)
    )
    -(
    (A_xD_x+A_yD_y+A_zD_z)
    (B_xC_x+B_yC_y+B_zC_z)
    )
    $$
    </div>

    $$LHS=(\vec{A}\cdot\vec{C})(\vec{B}\cdot\vec{D})-(\vec{A}\cdot\vec{D})(\vec{B}\cdot\vec{C})=RHS$$
    

15. $x_{(t)} = 5\epsilon^{-\gamma t} \cos {\omega t}$  
    1.  

    $$ f_x = x\sin{y} \Rightarrow \dot{f}_x = x'\sin{y} + x\cos{y}\cdot y' $$
    $$ f_x = x\cos{y} \Rightarrow \dot{f}_x = x'\cos{y} - x\sin{y}\cdot y' $$
    $$ \Downarrow $$
    $$x'_{(t)} = 5(-\gamma)\epsilon^{-\gamma t} \cos {\omega t}-5\epsilon^{-\gamma t}\sin{\omega t}\cdot \omega$$
    $$ x'_{(t)} = -5 (\gamma\epsilon^{-\gamma t}\cos{\omega t}+\omega\epsilon^{-\gamma t} \sin{\omega t}) $$
    2.  

    $$x''_{(t)} = (-5 (\gamma\epsilon^{-\gamma t}\cos{\omega t}+\omega\epsilon^{-\gamma t} \sin{\omega t}))' $$
    לצורך נוחות: $z=\epsilon^{-\gamma t}$, $z'=-\gamma\epsilon^{-\gamma t}=-\gamma z$ 

    $$x''_{(t)} = (-5 (\gamma z\cos{\omega t}+\omega z \sin{\omega t}))' $$
    $$x''_{(t)} = (-5\gamma z\cos{\omega t}-5\omega z \sin{\omega t}))' $$
    $$x''_{(t)} = (-5\gamma z'\cos{\omega t} - (-5\gamma\omega z\sin{\omega t}))-(5\omega z' \sin{\omega t} + 5\omega^2 z\cos{\omega t}) $$
    $$x''_{(t)} = 5(-\gamma z'\cos{\omega t}+\gamma\omega z\sin{\omega t}-\omega z' \sin{\omega t}-\omega^2 z\cos{\omega t}) $$
    $$x''_{(t)} = 5(-\gamma(-\gamma) z\cos{\omega t}+\gamma\omega z\sin{\omega t}-\omega(-\gamma)z \sin{\omega t}-\omega^2 z\cos{\omega t}) $$
    $$x''_{(t)} = 5(\gamma^2 z\cos{\omega t}+\gamma\omega z\sin{\omega t}+\omega\gamma z \sin{\omega t}-\omega^2 z\cos{\omega t}) $$
    $$x''_{(t)} = 5z(\gamma^2 \cos{\omega t}+\gamma\omega \sin{\omega t}+\omega\gamma\sin{\omega t}-\omega^2\cos{\omega t}) $$
    $$x''_{(t)} = 5z((\gamma^2-\omega^2)\cos{\omega t}+(2\gamma\omega)\sin{\omega t}) $$
    $$x''_{(t)} = 5\epsilon^{-\gamma t}((\gamma^2-\omega^2)\cos{\omega t}+(2\gamma\omega)\sin{\omega t}) $$
    3.  כדי לאזן את t יש לשים לב לפעולה המתמטית שבין משתנים אלו לt, ולכן:

    $$ [\omega] = t^{-1}$$
    $$ [\gamma] = t^{-1}$$
    4. תמונות: 
16. $r_{(t)} = B(t + \tau)^{-2}\epsilon^{-3}\cos{(at^3)}$  
    1.  כדי לאזן את t יש לשים לב לפעולה המתמטית שבין משתנים אלו לt, ולכן:

    $$ [a] = t^{-3}$$
    $$ [\tau] = t$$
    2. לצורך נוחות: $\tau = c$, $B = b$

    $$r'_{(t)} = (b(t + c)^{-2}\epsilon^{-3}\cos{(at^3)})'$$
    $$r'_{(t)} = (b(t + c)^{-2}\epsilon^{-3})'\cos{(at^3)}-(b(t + c)^{-2}\epsilon^{-3})\sin{(at^3)}(at^3)'$$
    $$r'_{(t)} = -2b(t + c)^{-3}\epsilon^{-3}\cos{(at^3)}-(b(t + c)^{-2}\epsilon^{-3})\sin{(at^3)}3at^2$$
    $$r'_{(t)} = -b\epsilon^{-3}(2(t+c)^{-3}\cos{(at^3)}+2a^2(t+c)^{-2}\sin{(at^3)}) = velocity$$
    $$r''_{(t)} = -b\epsilon^{-3}[2(t+c)^{-3}\cos{(at^3)}+2a^2(t+c)^{-2}\sin{(at^3)}]'$$
    $$r''_{(t)} =-b\epsilon^{-3}[
    -6(t+c)^{-4}\cos{(at^3)}
    -2(t+c)^{-3}3at^2\sin{(at^3)}
    -4a^2(t+c)^{-3}\sin{(at^3)}
    +4a^4(t+c)^{-2}\cos{(at^3)}
    ]
    $$
    $$r''_{(t)} =2b\epsilon^{-3}[
    3(t+c)^{-4}\cos{(at^3)}
    +(t+c)^{-3}3at^2\sin{(at^3)}
    +2a^2(t+c)^{-3}\sin{(at^3)}
    -2a^4(t+c)^{-2}\cos{(at^3)}
    ]
    $$
    $$r''_{(t)} =2b\epsilon^{-3}[
    (3(t+c)^{-4}-2a^4(t+c)^{-2})\cos{(at^3)}
    +((t+c)^{-3}3at^2+2a^2(t+c)^{-3})\sin{(at^3)}
    ]
    $$
    $$r''_{(t)} =2b\epsilon^{-3}[
    (t+c)^{-2}(3(t+c)^{-2}-2a^4)\cos{(at^3)}
    +(t+c)^{-3}a(3t^2+2a)\sin{(at^3)}
    ] = acceleration
    $$

    