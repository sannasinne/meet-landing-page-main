# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for interactive elements

### Screenshot

![](./screenshot-desktop.jpg)

![](./screenshot-tablet.jpg)

![](./screenshot-mobile.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/sannasinne/meet-landing-page-main)
- Live Site URL: [Add live site URL here](https://sannasinne.github.io/meet-landing-page-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This challenge was great for upgrading my Flexbox skills.

During this project I learned to make a vertical line and position it:

```css
.line {
  border-left: 1px solid rgba(135, 135, 157, .25);
  height: 8.4rem;
  transform: translateX(50%);
}
```

I also learned to make perfect circles around section number using inline-flex:

```css
.circle {
  border: 1px solid rgba(135, 135, 157, .25);
  border-radius: 50%;
  height: 5.6rem;
  width: 5.6rem;
  margin: 0 auto;
  display: inline-flex;
  align-items: center;
  justify-content: center;
}
```

### Continued development

In future projects I want to focus more on Flexbox and positioning of the elements.

### Useful resources

- [w3 schools](https://www.w3schools.com/howto/howto_css_vertical_line.asp) - This helped me with creating a vertical line.
- [mdn](https://developer.mozilla.org/en-US/docs/Web/CSS/transform) - This helped me to position items with transform: translate();

## Author

- Frontend Mentor - [@sannasinne](https://www.frontendmentor.io/profile/sannasinne)
