# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

- Mobile: [https://github.com/rogeriobautz/3-column-preview/blob/master/screenshots/mobile.png]
- Desktop: [https://github.com/rogeriobautz/3-column-preview/blob/master/screenshots/desktop.png]

### Links

- Solution URL: [https://github.com/rogeriobautz/3-column-preview/]
- Live Site URL: [https://rogeriobautz.github.io/3-column-preview/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned that the hover property needs an equal or higher specificity than others peace of codes below in the code even if this last one did not specify hover:

```css
a: hover {
  background: white;
}
main a {
  background: red;
}

/*The background in HOVER state will be red.*/

maina: hover {
  background: white;
}
main a {
  background: red;
}

/*The background in HOVER state will be white.*/
```

### Useful resources

- [Stack Overflow](https://stackoverflow.com/questions/16967118/ahover-color-is-not-working/16967193) - Helped with hover problem.

## Author

- [Rogério Bautz](https://github.com/rogeriobautz)
- Frontend Mentor - [@rogeriobautz](https://www.frontendmentor.io/profile/rogeriobautz)
- Instagram - [@rogerio.bautz](https://www.instagram.com/rogerio.bautz)
