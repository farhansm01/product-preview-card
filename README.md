# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [Overview](#overview)

  - [The challenge](#the-challenge)

  - [Links](#links)

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Live Site URL: https://farhansm01.github.io/product-preview-card/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Responsive images using <picture>

### What I learned

This challenge helped me understand responsive layouts much better.

- I used to force heights early, but I learned that letting content control the height on mobile makes layouts more stable.

- Instead of using margins to position elements, I now handle centering from the parent container.

-I learned why fixed heights are sometimes necessary on desktop card layouts to keep images and content aligned.

-I also stopped using JavaScript for responsive images and switched to the <picture> element, which is simpler and more reliable.

Example of responsive image handling:

```html
<picture>
  <source media="(min-width: 934px)" srcset="image-product-desktop.jpg" />
  <img src="image-product-mobile.jpg" alt="Product image" />
</picture>
```

This approach keeps the layout clean and avoids unnecessary JS.

### Continued development

Going forward, I want to practice using a mobile-first approach more consistently in my projects. Building this component showed me how much easier layout and responsiveness become when the mobile experience is designed first and desktop styles are added later.

## Author

- Frontend Mentor - [@farhansm01](https://www.frontendmentor.io/profile/farhansm01)
- Twitter - [@farhan_sadiq22](https://x.com/farhan_sadiq22)
- Github - [@farhansm01](https://github.com/farhansm01)
- LinkedIn - https://www.linkedin.com/in/farhan-sadiq19/
