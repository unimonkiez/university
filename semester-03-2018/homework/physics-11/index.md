<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
# ש"ב פיזיקה - תרגיל 11
## יובל סרף
1. **עשינו בכיתה**
2.
    1.
        $$\vec{r} = r\hat{r} + \theta\hat{\theta} + 0\hat{z}$$
        $$\vec{F} = m(\ddot{r} - r\dot{\theta}^2)\hat{r} + m(2\dot{r}\dot{\theta} + r\ddot{\theta})\hat{\theta} + 0\hat{z}$$
        $$\vec{\tau} = \frac{\delta \vec{L}}{\delta t} = \vec{r} \otimes \vec{F}$$
        $$\Downarrow$$
        $$\frac{\delta \vec{L}}{\delta t} =
        (\theta \cdot 0 - 0 \cdot m(2\dot{r}\dot{\theta} + r\ddot{\theta}))\hat{r} +
        (r \cdot 0 - 0 \cdot m(\ddot{r} - r\dot{\theta}^2))\hat{\theta} +
        (r\cdot m(2\dot{r}\dot{\theta} + r\ddot{\theta}) - \theta\cdot m(\ddot{r} - r\dot{\theta}^2))\hat{z}
        $$
        $$\frac{\delta \vec{L}}{\delta t} = (r\cdot m(2\dot{r}\dot{\theta} + r\ddot{\theta}) - \theta\cdot m(\ddot{r} - r\dot{\theta}^2))\hat{z}$$
        $$\frac{\delta \vec{L}}{\delta t} = (2mr\dot{r}\dot{\theta} + mr^2\ddot{\theta} - m\theta\ddot{r} + mr\theta\dot{\theta}^2)\hat{z}$$