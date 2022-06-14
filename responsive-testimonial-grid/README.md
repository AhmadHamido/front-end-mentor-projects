Created with CodeSandbox

# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7)

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Links

- Solution URL: https://github.com/AhmadHamido/testimonials-grid-section-front-end-mentor
- Live Site URL: https://ahmadhamido.github.io/testimonials-grid-section-front-end-mentor/

## My process

### Built with

- Semantic HTML5 markup
- CSS Grid
- Mobile-first workflow

### What I learned

I learned to use as less rows and columns as I could to make my layout work, because in a previous project I had to put so many rows in order to make it wor. However this time I only needed two rows in the grid layout.

You can see a code snippet below:

```html
<div class="testimonial-container">
  . . .
</div>
```

```css
.testimonial-container {
  max-width: 1200px;
  display: grid;
  grid-template: 300px 250px / repeat(3, 25%) 1fr;
  grid-gap: 20px;
}
```

### Continued development

I need to understand more how to size my rows and columns, and how and when to use the auto-fill, auto-fit, and minmax().

### Useful resources

- [Resource-1](https://www.w3schools.com/CSSref/pr_background-position.asp) - This helped me learn how to position the background image.

## Author

- Website - [Ahmad Hamido](https://ahmadhamido.github.io/testimonials-grid-section-front-end-mentor/)
- Frontend Mentor - [@AhmadHamido](https://www.frontendmentor.io/profile/AhmadHamido)
- Twitter - [@thereapermma91](https://www.twitter.com/thereapermma91)
