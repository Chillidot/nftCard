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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](04_images/screenshot.jpg)

### Links

- Solution URL: https://github.com/Chillidot/nftCard
- Live Site URL: https://chillidot.github.io/nftCard/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

Change image on hover

```html
      <div class="image">
        <img src="04_images/image-equilibrium.jpg" alt="Equilibrium">
        <img src="04_images/icon-view.svg" alt="View Equilibrium" class="img-top">
      </div>
```
```css
.image{
    position: relative;
    display: inline-block;
}

.image img{
    max-width: 100%;
    height: auto;
    border-radius: 0.5rem;
}

.img-top{
    padding: 106px;
    border-radius: 0.5rem;
    background-color: rgba(0, 255, 247, 0.4);
}

.image .img-top{
    display: none;
    position: absolute;
    top: 0;
    left: 0;
    z-index: 99;
}

.image:hover .img-top{
    display: inline-block;
    cursor: pointer;
}
```

### Useful resources

- [Example resource 1](https://www.tutorialrepublic.com/faq/how-to-change-image-on-hover-with-css.php) This helped me to change images on hover
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally 

## Author

- Frontend Mentor - [@chillidot](https://www.frontendmentor.io/profile/Chillidot)