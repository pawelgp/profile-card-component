# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/pawelgp/profile-card-component](https://github.com/pawelgp/profile-card-component)
- Live Site URL: [https://pawelgp.github.io/profile-card-component/](https://pawelgp.github.io/profile-card-component/)

## My process

### Built with

- HTML5,
- SASS (Dart),
- BEM,
- DRY.

### What I have learnt

To include and position svg files as background elements using pseudo elements.
```css
.wrapper__card {
  &::before {
    content: '';
    background-image: url(./images/bg-pattern-top.svg);
    background-repeat: no-repeat;
    background-position-x: 100%;
    background-position-y: 100%;
    background-size: auto;
    position: absolute;
    top: 0;
    left: 0;
    bottom: 34%;
    right: 52%;
  }
  ...
}
```
## Author

- Website - [over40.pl](https://over40.pl)
- Twitter - [@pgpasich](https://www.twitter.com/pgpasich)
