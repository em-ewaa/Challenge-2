# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshots/screenshot-1.jpeg)
![](./screenshots/screenshot-2.jpeg)

### Links

- Solution URL: (https://github.com/em-ewaa/Challenge-2)
- Live Site URL: (https://em-ewaa.github.io/Challenge-2/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow
- CSS @media Rule

### What I learned

- To use <div> as <img> container and to give automatic height of that image according to current width:

```css
  .img {
    background: no-repeat url("/Challenge-2/images/image-header-mobile.jpg");
    background-size: cover;
    background-color: var(--soft-violet);
    padding-top: 73.5%;
  }
```

- To center the content with viewport units and flexbox:

```css
body {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}
```

- To manage background property and filters:
```css
.img {
  background: no-repeat url("/Challenge-2/images/image-header-desktop.jpg");
  background-size: cover;
  background-position: right top;
  background-color: var(--soft-violet);
  background-blend-mode: multiply;
}
```

### Continued development

I will focus more on developing the layout with flexbox and do more research about different displays avaiable in CSS.

### Useful resources

- [w3schools - Aspect Ratio](https://www.w3schools.com/howto/howto_css_aspect_ratio.asp) - This article showed me how to keep aspect ratio of the <div> element with bacgkround-image.

## Author

- Website - [Ewa Majowska]