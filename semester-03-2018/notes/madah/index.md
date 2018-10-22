<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
## 22.10.2018 - תרגול
$$F_{(x,y)}$$
$$x = x_{(t)}$$
$$y = y_{(t)}$$
$$G_{(t)} = F_{(x_{(t)}, y_{(t)})}$$
$$G'_{(t)} = \frac{\delta F}{\delta t} = \frac{\delta F}{\delta x}\cdot \frac{\delta x}{\delta t}+\frac{\delta F}{\delta y}\cdot \frac{\delta y}{\delta t}$$
#### תרגיל
תהיי 

$$f_{(u,v)}:R^2\rightarrow R$$

נתון

$$\frac{\delta f}{\delta u}(7,1) = 2$$
$$\frac{\delta f}{\delta v}(7,1) = 3$$
נגדיר:

$$u_{(x,y)} = 2x+3y$$
$$v_{(x,y)} = x-y$$
והרכבה

$$z_{(x,y)} = f_{(u_{(x,y)}, v_{(x,y)})}$$
חשבו את 

$$\frac{\delta z}{\delta x}(2,1)$$
$$\frac{\delta z}{\delta y}(2,1)$$
פתרון:  
נשים לב כי הנקודה 

$$u=7,v=1$$
במישור $uv$ עוברת לנקודה 

$$x=2,y=1$$ במישור $xy$

$$u=2x+3y=7$$
$$u=x-y=1$$
$$\frac{\delta u}{\delta x} = 2$$
$$\frac{\delta v}{\delta x} = 1$$
$$\frac{\delta u}{\delta y} = 3$$
$$\frac{\delta v}{\delta y} = -1$$
$$\Downarrow$$
$$\frac{\delta z}{\delta x} = \frac{\delta f}{\delta u} \cdot \frac{\delta u}{\delta x} + \frac{\delta f}{\delta v}\cdot \frac{\delta v}{\delta x}$$
$$\frac{\delta z}{\delta y} = \frac{\delta f}{\delta u} \cdot \frac{\delta u}{\delta y} + \frac{\delta f}{\delta v}\cdot \frac{\delta v}{\delta y}$$
$$\Downarrow$$
$$\frac{\delta z}{\delta x}(2,1) = 7$$
$$\frac{\delta z}{\delta y}(2,1) = 3$$
