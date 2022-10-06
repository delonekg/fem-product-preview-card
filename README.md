# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/desktop-screenshot.png) 
![](./images/mobile-screenshot.png)

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/product-preview-card-component-nPfse7dkRq)
- Live Site URL: [Live Site URL](https://delonekg-fem-product-preview-card.netlify.app/)

## My process

### Built with

- CSS Custom Properties
- Flexbox Layout

### What I learned

I learned more about utilizing CSS media queries to provide perfect layouts for any screen.

```css
@media only screen and (max-width: 23.5rem) {
    .card {
        flex-direction: column;
    }

    .image {
        width: 21.25rem;
        height: 15rem;
        background-image: url('../images/image-product-mobile.jpg');
        border-radius: 0.625rem 0.625rem 0 0;
    }

    .product-info {
        width: 21.25rem;
        height: 23.125rem;
        padding: 1.875rem 1.5625rem 1.5625rem 1.5625rem;
        border-radius: 0 0 0.625rem 0.625rem;
    }

    h3 {
        margin-bottom: 0.9375rem;
    }

    h1 {
        margin-bottom: 1.25rem;
    }

    .description {
        margin-bottom: 1.25rem;
    }

    .price-info {
        margin-bottom: 0.625rem;
    }
}
```

### Continued development

I would like to continue practicing my frontend skills using this amazing platform!

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org) MDN Web Docs is a great documentation website that you should totally bookmark if you need help remebering a CSS property/JS feature.
- [Stackoverflow](https://www.stackoverflow.com) Stackoverflow is a great place for finding help when you're stuck coding!

## Author

- Frontend Mentor - [@delonekg](https://www.frontendmentor.io/profile/delonekg)
- Twitter - [@Deloneeeee](https://www.twitter.com/Deloneeeee)

## Acknowledgments

Keep trying even if you're stuck! If you're stuck, make sure to get help while also prioritizing your learning!
