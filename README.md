# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Toggle the mobile menu (requires some JavaScript)

### Screenshot

![Screenshot (176)](https://user-images.githubusercontent.com/107123538/200749101-ce0e4d98-c68a-41f0-b670-f803309bbe4d.png)

### Links

- Solution URL: [https://github.com/SahanAbey/Home-Page-of-Blog]
- Live Site URL: [https://sahanabey.github.io/Home-Page-of-Blog/]

## My process

### Built with

- HTML5
- CSS
- Flexbox
- CSS
- [Bootstrap]


### What I learned


To see how you can add code snippets, see below:

```html
 <picture>
            <source
              media="(min-width:800px)"
              srcset="./assets/images/image-web-3-desktop.jpg"
              class="web3PC"
            />
            <source
              media="(min-width: 375px)"
              srcset="./assets/images/image-web-3-mobile.jpg"
            />
            <img
              src="./assets/images/image-web-3-desktop.jpg"
              alt="IfItDoesntMatchAnyMedia"
              width="700px"
            />
          </picture>
```
```css
@media (min-width: 375px) {
    .content {
        display: inline;
        margin: 0;
    }

    .myButton {
        margin: 0;
    }
}
}
```

## Author

- Sahan Roshitha
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/SahanAbey)
