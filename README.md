# FEM - Subscription Page

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/chucksterv/fem-subscription-page-grid-component]
- Live Site URL: [https://subscription-page.projects.deshand.com/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- Realized that spacing with padding will create issues with the background color of the child elements if it isn't set to white. Workaround would be to manipulate the child element instead of the parent element.
- Used Utility classes for the different colors throughout the project which was more efficeint and provided a better design architechture than styling the elements themselves.

```css
@media (min-width: 600px) {
  .subscription {
    grid-template-columns: 1fr 1fr;
  }
  .pitch {
    grid-column: 1 / 3;
  }
  .card-section {
    padding: 2.5rem;
  }
}
```
