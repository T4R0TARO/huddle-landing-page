# Frontend Mentor - Huddle Landing Page solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

DESKTOP:
![image](https://user-images.githubusercontent.com/76195521/174686757-f5de3ef5-961b-421b-b0bc-7a4b046c0f7d.png)
TABLET:
![image](https://user-images.githubusercontent.com/76195521/174686811-49104704-da2e-4b14-9667-5d93bfdb5260.png)
MOBILE:
![image](https://user-images.githubusercontent.com/76195521/174686844-6d7bf8b6-318e-4e4f-a020-968fe8e50f8f.png)

### Links

- Solution URL: [Git Repo](https://github.com/T4R0TARO/huddle-landing-page)
- Live Site URL: [Git Pages](https://t4r0taro.github.io/huddle-landing-page/)

## My process

- HTML Layout
- Mobile Styles
- Desktop Styles
- Layout Padding + Margin Touch Ups
- Active-State Styles

### Built with

- Semantic HTML5 markup
- SASS/SCSS
- Flexbox
- CSS Grid
- Mobile-first workflow
- BEM Class Naming

### What I learned

```css
// ABSOLUTE CARD
//CENTER AN ABSOLUTE DIV
.about__card-absolute {
  position: absolute;
  transform: translateY(30%);
  max-width: 56.25rem;
  left: 0;
  right: 0;
  margin-left: auto;
  margin-right: auto;
  padding: 6.25rem 1rem 0px 1rem;
  border-radius: 1.5625rem;
  background: $white;
  box-shadow: 0px 0px 10px #888888;
}
```

Centering an absolute div with `margin-left: auto` and `margin-right: auto`

```css
.header__get-started-button-bottom {
  padding: 0.9375rem 1.5625rem;
  font-weight: 700;
  font-size: 1.125rem;
  border-radius: 2.8125rem;
  background: $pink;
  color: $white;
  box-shadow: 0px 0px 10px #888888;
  margin-bottom: 6.25rem;
}
```

Shadows on all four sides evenly with ` box-shadow: 0px 0px 10px #888888`

```css
footer .top-header__logo {
  filter: brightness(0) invert(1);
}
```

Apply filter on img to change color to WHITE `filter: brightness(0) invert(1)`

## Author

- Website - [Joshua Manansala](https://github.com/T4R0TARO)
- Frontend Mentor - [@T4R0TARO](https://www.frontendmentor.io/profile/T4R0TARO)
- Twitter - [@taro_code](https://twitter.com/taro_code)
