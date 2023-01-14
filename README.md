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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Product Card Frontend](https://stephenlawson.github.io/product_card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Screen readers in mind
- CSS Grid
- Mobile-first workflow


### What I learned

The snippet below was a good way of making something that is intuitive to visually impaired users with screen readers. They would not be able to easily understand the repeated prices with a cross out of the older price without added context.



```html
<span class="visually-hidden">Original Price:</span>
<s>$169.99</s>
```
```css
.visually-hidden:not(:focus):not(:active) {
    clip: rect(0 0 0 0);
    clip-path: inset(50%);
    height: 1px;
    overflow: hidden;
    position: absolute;
    white-space: nowrap;
    width: 1px;
  }
```





### Useful resources

- [CSS reset](https://www.joshwcomeau.com/css/custom-css-reset/) - Useful resource to reset CSS attributes.


## Author

- [My Portfolio Site](https://www.stephen.photography/portfolio)


## Acknowledgments

Kevin Powell was very helpful in setting up CSS attributes.


