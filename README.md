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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop Layout](/desktop_version.png)
![Mobile Layout](/mobile_version.png)

### Links

- Solution URL: (https://github.com/samsdivstudios/Product-preview-card-component/tree/main)
- Live Site URL: (https://samsdivstudios.github.io/Product-preview-card-component/)

## My process

### Built with

- Semantic HTML markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Creating this card helped me learn how to use picture tag and adding a svg icon in a button. I also learned how to start with mobile design first and why it's important to do so.

```html
<picture class="product_image">
        <source srcset="images/image-product-desktop.jpg" media="(min-width: 600px)">
        <img src="/images/image-product-mobile.jpg" alt="Gabrielle Essence Eau De Parfum bottle lying down on a white table with green leafs around it ">
      </picture>
```
```css
button[data-icon="shopping-cart"]::before {
  content: "";
  background-image: url(/images/icon-cart.svg);
  width: 15px;
  height: 16px;
}
```

### Continued development
After creating this design I now relise I need to learn more about, units, styling text as mine ain't 100% accurate.

### Useful resources

- [Kevin Powell, CSS expert](https://www.youtube.com/watch?v=B2WL6KkqhLQ) - This video helped me understand abit about picture tag and adding svgs to a button.

- [Josh Comeau](https://www.joshwcomeau.com/css/custom-css-reset/) - This is an amazing article which helped me understand a new way to a CSS reset.

## Author
- Frontend Mentor - [@samsdivstudios](www.frontendmentor.io/profile/samsdivstudios)
