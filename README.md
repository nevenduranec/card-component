# Frontend Mentor - Stats preview card component

This is a solution to the [Stats preview card component](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
-   [Author](#author)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

-   [Solution URL - Github](https://github.com/nevenduranec/card-component)
-   [Live Site URL](https://world-countries-iota.vercel.app/)

## My process

### Built with

-   CSS vars
-   Min/max for font size (`min(max(20px, 4vw), 22px);`)
-   PostCSS - [postcss-nested](https://github.com/postcss/postcss-nested), [postcss-pxtorem](https://github.com/cuth/postcss-pxtorem), [autoprefixer](https://github.com/postcss/autoprefixer)
-   Webpack

### What I learned

Animating text decoration with CSS Houdini

```css
@property --offset {
    syntax: '<length>';
    inherits: false;
    initial-value: 0;
}
```

Find out more about this on the [CSS in Real Life blog post](https://css-irl.info/animating-underlines/)

## Author

-   Website - [Neven Đuranec](https://digitalbits.hr/)
-   Frontend Mentor - [@nevenduranec](https://www.frontendmentor.io/profile/nevenduranec)
-   Twitter - [@nevenduranec](https://www.twitter.com/nevenduranec)
