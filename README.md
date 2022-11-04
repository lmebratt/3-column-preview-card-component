# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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
- See hover states for interactive elements

### Screenshot

- Desing preview:

![Desktop design](./design/desktop-preview.jpg)

- Desing preview on mobile:

![Mobile design](./design/mobile-design.jpg)

- Desing preview on desktop:

![Desktop design](./design/desktop-design.jpg)

- Desing preview active on desktop:

![Desktop design](./design/active-states.jpg)

### Links

- Solution URL: [3 Column Preview Card](https://github.com/lmebratt/3-column-preview-card-component)
- Live Site URL: [3 Column Preview Card](https://lmebratt.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
<main class="container">
    <section class="cards-main">
      <div>
        <picture>
          <img src="./images/icon-sedans.svg" alt="sedans">
        </picture>
        <h1>Sedans</h1>
        <p>Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city or on your next road trip.</p>
        <button>Learn More</button>
      </div>

      <div>
        <picture>
          <img src="./images/icon-suvs.svg" alt="suvs">
        </picture>
        <h1>SUVs</h1>
        <p>Take an SUV for its spacious interior, power, and versatility. Perfect for your next family vacation and off-road adventures.</p>
        <button>Learn More</button>
      </div>

      <div>
        <picture>
          <img src="./images/icon-luxury.svg" alt="luxury">
        </picture>
        <h1>Luxury</h1>
        <p>Cruise in the best car brands without the bloated prices. Enjoy the enhanced comfort of a luxury rental and arrive in style.</p>
        <button>Learn More</button>
      </div>
    </section>
```

```css
:root {
    --sedans: #e38826;
    --suvs: #006970;
    --luxury: #004241;
    --paragraphs:#ffffffbf;
    --background-headings-buttons: #f2f2f2;
}
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
html {
    font-size: 62.5%;
}
body {
    font-family: 'Big Shoulders Display', cursive;
    font-family: 'Lexend Deca', sans-serif;
    font-size: 1.5rem;
    background-color: var(--background-headings-buttons);
    margin: 20px 0;
```

### Continued development

This is just the beginning, I will continue to strengthen my knowledge to become a Full Stack Web Developer

## Author

- Website - [Luis M. Ebratt](https://lmebratt.github.io/).
- Frontend Mentor - [@lmebratt](https://www.frontendmentor.io/profile/lmebratt)
- Twitter - [@RazorLm](https://www.twitter.com/RazorLm)