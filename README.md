# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

## Overview

### The challenge

![Design preview for the 3-column preview card component coding challenge](./design/desktop-preview.jpg)

Users should be able to

- View the optimal layout depending on their device's screen size

### Links

- Live Site URL: [Stats preview card component](https://guztrillo.github.io/TFM-stats-preview-card-component/)

## My process

### Built with

- HTML5
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- SASS

### What I learned

Second challenge from The Frontend Mentor. Once you know mix-blend-mode you feel unstopable. This time I use it to creat one button for the three categories, feels like magic!

To make the button fully transparent so it can show the background-color, you only need to set text color to black and mix-blend-mode to screen.
```css
.button {
  color: #000,
  mix-blend-mode: screen;
}
```

And when you hover it:

```css
.button:hover{
  background-color: #000
}
```

Also, I find out that when you want to set border-radius to a element that has content within the div, you need to set overflow: hidden. I felt so dumb.

### Useful resources

- ["border-radius not working"](https://stackoverflow.com/questions/10995294/border-radius-not-working)