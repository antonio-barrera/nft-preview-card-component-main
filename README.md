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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Webpage screenshot](images/screenshoot.jpeg)

### Links

- Solution URL: (https://github.com/antonio-barrera/nft-preview-card-component-main.git)
- Live Site URL: (https://antonio-barrera.github.io/nft-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

One of the main things I'd like to highlight on this project is the continuos implementation of flex layouts in order to get well positioned and centered elements within the card.

```html
<div class="token-info">
    <div class="price"><img src="images/icon-ethereum.svg" alt=""><span>0.041 ETH</span></div>
    <div class="time"><img src="images/icon-clock.svg" alt=""><span>3 days left</span></div>
</div>
```
```css
.token-info {
    display: flex;
    justify-content: space-between;
    font-size: 1.6rem;
}
.token-info div {
    width: 10rem;
    padding: 0 0 1rem;
    display: flex;
    justify-content: space-around;
}
```

### Useful resources

- [Basi HTML and CSS styles](https://www.example.com) - This is a short and simple tutorial that helped me to learn the basic HTML structure of a card and others similar shapes.
- [Overlay Hover Effects](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - This is the article which helped me to finally learn how to make overlay hover effects on images.

## Author

- Frontend Mentor - [@antonio-barrera](https://www.frontendmentor.io/profile/antonio-barrera)
- Twitter - [@soyantoniob](https://www.twitter.com/soyantoniob)
