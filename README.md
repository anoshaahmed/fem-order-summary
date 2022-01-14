# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj)


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
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

- See hover states for interactive elements

### Screenshots

- Preview of my solution on a desktop screen [Desktop](solution-screenshots/desktop-solution.png)
- Preview of my solution on a mobile screen [Mobile](solution-screenshots/mobile-solution.png)

### Links
- Solution URL: [FrontEnd Mentor: My Solution](https://www.frontendmentor.io/solutions/order-summary-component-using-flexbox-and-css-grid-UP1iy9-xG)
- Live Site URL: [GitHub Page: Order Summary](https://anoshaahmed.github.io/fem02-order-summary/)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

I could not get the background picture to stay in its place. And then I learned of the "background-size" property
```css
body {
    font-family: 'Red Hat Display', sans-serif;
    font-size: 16px;
    background-image: url(images/pattern-background-desktop.svg);
    background-color: var(--pale-blue);
    background-repeat: no-repeat;
    background-size: contain; !!!!!!!!!!!!!!!!!!
}
```

### Continued development

I tried being better than my last project on organizing my HTML, however I aim to perfect it. I want to start integrating a better template layout, such as
```html
<body>
  <header></header>
  <nav></nav>
  <main>
    <section></section>
    <article></article>
    <aside></aside>
  </main>
  <footer></footer>
</body>
```

### Useful resources

- [Image Color Picker](https://www.imagecolorpicker.com) - I love using this site to pick a color out from a screenshot.

## Author

- Website - [Anosha Ahmed](https://www.anoshaahmed.com) - This is my website. There's nothing there at the moment but in the future there will.
- Frontend Mentor - [@anoshaahmed](https://www.frontendmentor.io/profile/anoshaahmed)
- GitHub - [@anoshaahmed](https://www.github.com/anoshaahmed)
- Twitter - [@anosha1ahmed](https://www.twitter.com/anosha1ahmed)
