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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

## Desktop View

![](./assets/screenshots/desktop_04.png)

## Mobile View

![](./assets/screenshots/mobile_04.png)

### Links

- Solution URL: [https://github.com/SauravFrontendDev/Product_preview_card_component](https://github.com/SauravFrontendDev/Product_preview_card_component)
- Live Site URL: [https://fem-saurav-product-preview.netlify.app/](https://fem-saurav-product-preview.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Vite
- bem

### What I learned

Through the project focused on responsive images ( as there were differrent images for different screen sizes), I gained valuable insights into implementing techniques that optimize image display based on device types. By utilizing strategies like the <picture> element and responsive image attributes, I learned to ensure that the most appropriate image is downloaded for each device, enhancing both performance and user experience. This experience underscored the importance of catering to diverse screen sizes and resolutions, highlighting how thoughtful image handling positively impacts a project's overall performance and load times.

To see how you can add code snippets, see below:

```html
<picture class="product__image--box">
  <source
    media="(max-width: 768px)"
    srcset="./assets/images/image-product-mobile.jpg"
  />
  <img src="./assets/images/image-product-desktop.jpg" alt="product preview" />
</picture>
```

### Useful resources

- [Web Dev Simplified Blog](https://blog.webdevsimplified.com/2023-05/responsive-images/) - How To Speed Up Page Load With Responsive Images.
  I learned about multiple responsive image attributes, and to ensure that the most appropriate image is downloaded for each device, enhancing both performance and user experience.

## Author

- Github - [/SauravFrontendDev](https://github.com/SauravFrontendDev)
- Linkedin - [/in/saurav-k-verma/](https://www.linkedin.com/in/saurav-k-verma/)
- Frontend Mentor - [@Saurav-98](https://www.frontendmentor.io/profile/Saurav-98)
- Twitter - [@SauravKverma22](https://twitter.com/SauravKverma22)
