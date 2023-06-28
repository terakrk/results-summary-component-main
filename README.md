# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Github](https://github.com/terakrk/results-summary-component-main)
- Live Site URL: [Live site](https://snazzy-profiterole-f9f9c1.netlify.app/)

## My process

I used HTML5 and vanilla CSS. As always, my "process" involved a lot of flailing until things looked decent, though there was a *lot* less flailing this time around.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

I got some practice with CSS Grid, and also used Flexbox to arrange the items in the unordered list. (I needed to "flex" the ul and li tags.)

```css
  ul {
    display: flex;
    flex-flow: column wrap;
    justify-content: space-between;
    align-items: center;

}

li {
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-evenly;
}
```

### Continued development

I will continue to learn Flexbox and Grid; I struggle to line things up correctly and will continue working on that.

### Useful resources

- [Implementing a variable font with fallback web fonts](https://pimpmytype.com/variable-font-fallback/) - This helped me understand how to use variable and static fonts (as fallbacks).


## Author

- Website - [Sweet Perdition](http://www.sweet-perdition.net)
- Frontend Mentor - [@terakrk](https://www.frontendmentor.io/profile/terakrk

