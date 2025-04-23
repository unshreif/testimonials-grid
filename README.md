# Frontend Mentor - Testimonials Grid Section

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Desktop Design](./desktop-design.jpg)

### Links

- Solution URL: https://github.com/yourusername/testimonials-grid-section
- Live Site URL: https://yourusername.github.io/testimonials-grid-section

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Flexbox
- Mobile-first workflow
- Tailwind CSS

### What I learned

Using CSS Grid with named template areas provides a clean and maintainable way to create complex layouts. The combination of Grid for the overall structure and Flexbox for component-level alignment resulted in a responsive design that adapts seamlessly across different screen sizes.

```html
<article id="daniel">
    <div class="flex">
        <img class="rounded-full" src="image-daniel.jpg" alt="Daniel Clifford">
        <div class="profile-info">
            <h2 class="text-white">Daniel Clifford</h2>
            <p class="text-white">Verified Graduate</p>
        </div>
    </div>
</article>
```

```css
#conup {
    display: grid;
    gap: 1.5rem;
    grid-template-columns: repeat(4, 1fr);
    grid-template-areas:
        "daniel daniel john kira"
        "jean patrick patrick kira";
}
```

### Useful resources

- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername) 