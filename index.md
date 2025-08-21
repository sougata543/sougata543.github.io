---
layout: default
title: Home
---
<style>
/* Dimmed repeating spiral only on index page */
main::before {
    content: '';
    position: fixed;          /* stays in place */
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('images/background_spiral_1.png');
    background-repeat: repeat;
    background-size: auto;
    background-position: 0 0;
    pointer-events: none;     /* allow interaction */
    z-index: 0;
    opacity: 0.1;             /* dim the spiral */
}

main > * {
    position: relative;
    z-index: 1;               /* content above spiral */
}
</style>

## About Me

I am a second-year MMath student at the [Indian Statistical Institute, Kolkata](https://www.isical.ac.in/).  
I did my Bachelors in Math and Computer Science at [Chennai Mathematical Institute](https://www.cmi.ac.in/).

<!--Test:

Inline: $E = mc^2$ and $\int_0^1 x^2\,dx = \frac13$.

Display:
$$
\sum_{n=1}^\infty \frac{1}{n^2} = \frac{\pi^2}{6}
$$

Inline code in JuliaMono: `x^2 + y^2 = something I dont care`
-->
---

## Contact

- Email:
    - first_name.last_name@outlook.com 
    - sougatap[at]cmi[dot]ac[dot]in  
- GitHub: [sougata543](https://github.com/sougata543)

