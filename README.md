# Frontend Mentor - Product preview card component solution

This is my professional solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). 

## Overview

### The challenge

Users should be able to:
- View the optimal layout depending on their device's screen size (Responsive Desktop & Mobile layouts).
- See hover and active states for interactive elements like the "Add to Cart" button.

### Screenshots

| Desktop Design | Mobile Design |
|--- |--- |
| ![Desktop](./design/desktop-design.jpg) | ![Mobile](./design/mobile-design.jpg) |

---

## My Process

### Built with

- **Semantic HTML5** markup
- **CSS Custom Properties** (Variables) for colors and theming
- **CSS Grid** for the main 2-column desktop layout
- **CSS Flexbox** for page centering and button components alignment
- **Media Queries** for fluid responsiveness (break-point at 500px)

### What I learned

During this project, I mastered some advanced layout concepts, especially handling responsive art-direction for images using the semantic `<picture>` tag, which allows swapping desktop and mobile assets seamlessly without layout shifts:

```html
<picture>
  <source media="(max-width: 500px)" srcset="images/image-product-mobile.jpg">
  <img src="images/image-product-desktop.jpg" alt="Product Image">
</picture>
I also refined my skills in aligning text and icon elements cleanly inside dynamic buttons using CSS Flexbox:

CSS
.btn {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
}


Author:

Frontend Mentor - @YaserKoji
GitHub - @YaserKoji