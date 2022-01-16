# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](preview-screenshot.png)


### Links

- [Solution URL](https://github.com/claurey/stats-preview-card-component)
- [Live Site URL](https://claurey.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I learned to use the following properties:
- **mix-blend-mode: multiply** , for stylized the image.
```css
.card__image{
    
    background-color: rgb(185, 89, 230);
    width: 57%;
    border-radius: 0 8px 8px 0;
}
.image{
    background-image: url(../images/image-header-desktop.jpg);
    background-repeat: no-repeat;
    background-size:cover;
    background-position: center;
    mix-blend-mode: multiply;
    height: 100%;
}
```
- **text-transform: uppercase**

```css
.card__footer p{
    text-transform: uppercase;
    font-size: 0.8rem;
    color: var(--neutral-slightly-transparent-white-stat);
}
```

### Useful resources

- [What Does “width: 100%” Do in CSS?](https://www.impressivewebs.com/width-100-percent-css/) - This is an amazing article which helped me finally understand to use **100% width**. I'd recommend it to anyone still learning this concept.


## Author

- Website - [https://github.com/claurey](https://github.com/claurey)
- Frontend Mentor - [@claurey](https://www.frontendmentor.io/profile/claurey)
- Twitter - [@claurey591](https://www.twitter.com/claurey591)

