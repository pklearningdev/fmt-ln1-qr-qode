# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![QR Code Component](./design/desktop-design.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/pklearningdev/fmt-ln1-qr-qode)
- Live Site URL: [View Live Demo](https://pklearningdev.github.io/fmt-ln1-qr-qode/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (CSS variables)
- Flexbox
- Mobile-first workflow
- Google Fonts (Outfit)
- BEM naming convention for CSS classes

### What I learned

This project helped me practice several important frontend development concepts:

**1. CSS Custom Properties**
I implemented a comprehensive design system using CSS variables for colors, typography, and spacing:

```css
:root{
  /* Colors */
  --slate-900: #1F314F;
  --slate-500: #68778D;
  --slate-300: #D5E1EF;
  --white: #FFF;

  /* Typography */
  --font-family: 'Outfit', sans-serif;
  --font-size-preset1: 22px;
  --font-size-preset2: 15px;
  
  /* Spacing */
  --spacing-500: 40px;
  --spacing-300: 24px;
  --spacing-200: 16px;
}
```

**2. Flexbox Centering**
I used Flexbox to center the card both horizontally and vertically:

```css
.container{
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
```

**3. BEM Methodology**
I applied the BEM (Block Element Modifier) naming convention for better CSS organization:

```html
<div class="card">
  <img class="card__img" />
  <div class="card__text">
    <p class="card__text__preset1"></p>
    <p class="card__text__preset2"></p>
  </div>
</div>
```

**4. Semantic HTML**
I used the `<main>` element to wrap the primary content, improving accessibility and SEO.

## Author

- GitHub - [@pklearningdev](https://github.com/pklearningdev)
- Frontend Mentor - [@pklearningdev](https://www.frontendmentor.io/profile/pklearningdev)
