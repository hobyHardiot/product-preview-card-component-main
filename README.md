# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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

![](screenshots/desktop-screen.png)
![](screenshots/mobile-screen.png)

### Links
 - Live Site URL: [Live](https://ubiquitous-shortbread-da1a8a.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Sublime text

### What I learned

This is what I learned about the <img> tag with srcset and sizes attributes in HTML: The <img> tag is used to embed images on a webpage. The srcset attribute allows you to specify multiple image sources and their corresponding widths, offering different image options for different screen sizes or resolutions. This helps the browser choose the most appropriate image to display based on the device's capabilities. In the provided code, there are two image options: images/image-product-desktop.jpg with a width of 600 pixels and images/image-product-mobile.jpg with a width of 686 pixels. The sizes attribute defines the image's display area in a CSS-like syntax, indicating the layout width of the image on different screen sizes. In this code, the sizes attribute is set as (max-width: 600px, 300px), meaning that the image's display area is 300 pixels wide when the screen width is 600 pixels or less. When the browser encounters this <img> tag, it evaluates the srcset attribute and selects the image that best fits the user's device screen size and resolution. For instance, if the device screen width is 400 pixels, the browser will choose the images/image-product-mobile.jpg image with a width of 686 pixels, which is larger than the available display area of 300 pixels specified in the sizes attribute. In conclusion, this code snippet demonstrates a responsive image approach, providing different image options for various devices, and the browser intelligently selects the most suitable image for optimal performance and user experience

```html
<img
	srcset="images/image-product-desktop.jpg 600w, images/image-product-mobile.jpg 686w"
	sizes="(max-width: 600px) 686px, 300px"
	src="images/image-product-desktop.jpg"
	alt="A bottle of perfume surrounded by foliage"
>
```

### Useful resources

- [Responsive Images: Reference Guide](https://imagekit.io/responsive-images/) - Extremely comprehensive guide to responsive images
- [Complete guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Great reference to learn Flexbox

## Author

- Frontend Mentor - [@hxbx47](https://www.frontendmentor.io/profile/hxbx47)
- Twitter - [@Hxbx47](https://www.twitter.com/Hxbx47)
- Facebook - [@mihobisoa_hardiot](https://www.facebook.com/hxbx.47)
