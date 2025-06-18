# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive element
- see the overlay on the image

### Screenshot

![Project Screenshot](/Assets/bento-ss.png)


### Links

- Live Site URL: (https://wizdev0.github.io/NFT.com/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Position
- Media Quaries

### What I learned

I learnt how to make an overlay color on an image.

```css
.mobile{
       position: relative;
       width: 90%;
        margin: 0 auto;
    }

    .mobile::after{
        content:"";
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: hsl(277, 64%, 61%);
        mix-blend-mode: multiply;
        opacity: 0.8;
        pointer-events: none;
       

    }

    .background-image{
        display: none;
    }
    
    .bm{
        display: inline-block;
        width: 100%;
        overflow: hidden;
        margin-top: 10%;
        border-top-right-radius: 5px;
        border-top-left-radius: 5px;
        
        
    }
```


### Continued development
In the future am still going to learn more about transitions, Positioning, animations, flexbox and grid.

### Useful resources

- [ChatGpt](https://chat.openai.com) - This AI model really helped me a lot when I was on the project, it helped me to Write the code in an orderly manner and also helped me to remember certain things I can recall.
- [Google font](https://fonts.google.com) - Google fonts really helped me with the font required for the project and also the boldness of the font.


## Author

- Frontend Mentor - [@Wizdev0](https://www.frontendmentor.io/profile/Wizdev0)
- Twitter - [@otutech](https://www.twitter.com/otutech)

