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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Screenshot%202023-10-03%20at%2017-10-57%20Frontend%20Mentor%20Product%20preview%20card%20component.pngscreenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

Learned how to use "display: inline-flex" while styling buttons, in order to flexibly display elements inside of the button. In this case, the button content and icon.

```.btn {
    border: none;
    outline: none;
    border-radius: .45rem;
    padding: .5em 1.5em;
    cursor: pointer;

    font-family: var(--ff-montserrat);
    font-weight: var(--fw-bold);
    background-color: var(--clr-primary-dark-cyan);
    color: var(--clr-neutral-white);

    display: inline-flex;
    justify-content: center;
    align-items: center;
    gap: .5rem;
}
```

Got a better understanding of how to use grid in media queries, to add responsiveness while switching between the mobile and desktop design of the layout.

```.product {
    display: grid;
    margin: 1rem;
    background-color: var(--clr-neutral-white);
    border-radius: .75rem;

    max-width: 650px;
}

@media (min-width: 600px) {
    .product {
        grid-template-columns: repeat(2, 1fr);
    }
}

```


### Useful resources

- [Example resource 1](https://www.joshwcomeau.com/css/custom-css-reset/) - This is a helpful CSS Reset cheat sheet.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/bfjamisse09)
