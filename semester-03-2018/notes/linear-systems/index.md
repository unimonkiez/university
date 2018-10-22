<style>
    html {
        direction: rtl;
    }
    eqn, table, .katex {
        direction: ltr;
    }
</style>
### 16.10.2018
* אנרגיה כוללת  
    רציף

    $$E_{t_1t_2} = \int_{t_1}^{t_2}|x_{(t)}^2|\frac{1}{t_2 - t_1} \delta t$$

    בדיד

    $$E_{n_1n_2} = \sum_{n_1}^{n_2}|x_{[n]}^2|\frac{1}{n_2 - n_1 + 1}$$
* לאורך כל תחום ההגדרה
    רציף

    $$E_{\infty} = \int_{-\infty}^{\infty}|x_{(t)}^2| \delta t$$

    בדיד

    $$E_{n_1n_2} = \sum_{-\infty}^{\infty}|x_{[n]}^2|$$
* הספק ממוצע
    רציף

    $$P_{\infty} = \lim_{T \rightarrow \infty} \frac{1}{2T}\int_{-T}^{T}|x_{(t)}^2| \delta t$$

    בדיד

    $$P_{\infty} = \lim_{N \rightarrow \infty} \frac{1}{2N+1}\int_{-N}^{N}|x_{[n]}^2|$$
* כל אות יכול להיות מפורק לסכום של שני אותות, אחד זוגי והשני אי זוגי
    * $$even_{(x_{(t)})} = \frac{1}{2}(x_{(t)}+x_{(-t)})$$
    * $$odd_{(x_{(t)})} = \frac{1}{2}(x_{(t)}-x_{(-t)})$$
### 22.10.2018

*
    $$\delta_{\Delta}(t) = \{ \frac{1}{\Delta} : |t|\leq \frac{\Delta}{2}, 0: |t|> \frac{\Delta}{2}\}$$
*   תמיד אותו שטח:

    $$\Delta \cdot \frac{1}{\Delta} = 1$$
*
    $$f_{(t)}\cdot \delta'_{(t)} = f_{(0)}\delta'_{(t)}-f'_{(0)}\delta_{(t)}$$