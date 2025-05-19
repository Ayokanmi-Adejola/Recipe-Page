# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](./preview.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Custom fonts (Young Serif and Outfit)
- Responsive design for multiple screen sizes

### What I learned

This project helped me strengthen my understanding of responsive design principles and CSS layout techniques. I particularly focused on creating a clean, readable recipe page that works well across different device sizes.

Some key learnings:

- Using CSS custom properties (variables) for consistent color theming:

```css
:root {
  --white: hsl(0, 0%, 100%);
  --stone-100: hsl(30, 54%, 90%);
  --stone-150: hsl(30, 18%, 87%);
  --stone-600: hsl(30, 10%, 34%);
  --stone-900: hsl(24, 5%, 18%);
  --brown-800: hsl(14, 45%, 36%);
  --rose-800: hsl(332, 51%, 32%);
  --rose-50: hsl(330, 100%, 98%);
}
```

- Implementing responsive design with media queries for different screen sizes:

```css
@media (max-width: 375px) {
  body {
    padding: 1.5rem 1rem;
  }

  h1 {
    font-size: 2rem;
    padding: 0 1.5rem;
    margin: 1.25rem 0;
  }
}
```

- Using local fonts with @font-face for better performance and consistent typography:

```css
@font-face {
  font-family: 'Young Serif';
  src: url('./assets/fonts/young-serif/YoungSerif-Regular.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
}
```

### Continued development

In future projects, I want to focus on:

- Improving my CSS Grid skills for more complex layouts
- Implementing accessibility features more thoroughly
- Adding JavaScript functionality to enhance user interaction
- Exploring CSS animations for subtle UI improvements

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - Comprehensive reference for HTML and CSS
- [CSS-Tricks](https://css-tricks.com/) - Great articles on CSS techniques and best practices
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me understand Flexbox layout better

## Author

- Frontend Mentor - [@Ayokanmi Adejola](https://www.frontendmentor.io/profile/Ayokanmi-Adejola)
