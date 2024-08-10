# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I started with html using the template provided by the community and then moved on to designing css adn responsive design before pushing my code to github.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

My major learning here has to be using flexbox and responsive web design correctly for the first time as I have always struggled with making a page responsive using media query. And also for the first time I also learnt how to add font-family from google using the @import method.

```css
@media (max-width: 767px) {
  .main {
    width: 90%;
    padding: 20px;
  }
  .acknowledgement img {
    height: 35px;
    width: 35px;
  }
  h1 {
    font-size: 1.2em;
  }
}
```

```css
@import url("https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap");
body {
  border-radius: 16px;
  background-color: hsl(217, 54%, 11%);
  font-family: "Outfit", sans-serif;
  font-optical-sizing: auto;
  font-weight: 300, 400, 600;
  font-size: 18px;
  font-style: normal;
}
```

### Continued development

I would still like to continue with more tasks using html , css and flex box and responsive web design for now until I am proficient enough and move from an intermediate level to a more advanced level.

### Useful resources

I have a mentor I interact with that helped me with answers to questions I had on areas I encountered blockers.

## Author

- Frontend Mentor - [@notobd](https://www.frontendmentor.io/profile/notobd)

## Acknowledgments

All thanks to the team at frontendmentor for this platform to learn and develop and to Favour. I already spoke about her in the useful resources section, she has been really helpful and introduced me to this platform.
