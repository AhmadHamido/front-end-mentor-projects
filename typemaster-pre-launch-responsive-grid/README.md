# Frontend Mentor - Typemaster pre-launch landing page solution

This is a solution to the [Typemaster pre-launch landing page challenge on Frontend Mentor]().

## Table of contents

- [Frontend Mentor - Typemaster pre-launch landing page solution](#frontend-mentor---typemaster-pre-launch-landing-page-solution)
  - [Table of contents](#table-of-contents)
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

- View three responsive layouts: mobile, tablet, and desktop

### Links

- Solution URL: [https://github.com/AhmadHamido/front-end-mentor-projects/tree/main/typemaster-pre-launch-responsive-grid]
- Live Site URL: [https://ahmadhamido.github.io/typemaster-pre-launch-responsive-grid/]

## My process

### Built with

- Semantic HTML5 markup
- CSS Grid
- Mobile-first workflow

### What I learned

-Learned how to use CSS grid without using "margin: 0 auto;"
-Learned how to use minmax properly

To see how you can add code snippets, see below:

```html
<header>
  <div class="container container-header">
    <img
      class="header-logo"
      src="images/shared/logo.svg"
      alt="typemaster logo of the capital letters TM"
    />
    <a class="btn header-btn" href="#">PRE-ORDER NOW</a>
  </div>
</header>
```

```css
.container-header {
  grid-template-columns:
    minmax(2rem, 1fr)
    repeat(2, minmax(auto, 267.5px))
    minmax(2rem, 1fr);
}
```

### Continued development

Using CSS grid for the layout without margin: 0 auto for the first time was a bit difficult, so I will practice more on it in the future.

### Useful resources

- [Resource 1](https://codeconvey.com/css-flip-background-image/) - This helped me how to flip an image 180 degrees.
- [Resource 2](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - This is where I learned to use different images for different layouts before I found out a better solution for this layout(using an empty div with a background in it)
- [Resource 2](https://mastery.games/post/article-grid-layout/) - This was the most helpful resource, which inspired me to and how use the minmax()

## Author

- Website - [Ahmad Hamido](https://www.your-site.com)
- Frontend Mentor - [@AhmadHamido](https://www.frontendmentor.io/profile/AhmadHamido)
- Twitter - [@thereapermma91](https://twitter.com/thereapermma91)
