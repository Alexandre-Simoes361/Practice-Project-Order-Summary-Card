# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

<img src="Images/Screens/Screenshot Desktop.png" alt="Desktop Screenshot" />
<img src="Images/Screens/Screenshot Mobile.png" alt="Mobile Screenshot" />

### Links

- Solution URL: [Github Repo](https://github.com/Alexandre-Simoes361/Practice-Project-Order-Summary-Card)
- Live Site URL: [Live Site](https://rad-eclair-3bd3b7.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This was the first project where I tried to implement a mobile-first approach, and I feel like it helped me to familiarize myself with the workflow and its advantages. Other than that, I implemented dropshadows for the first time, and troubleshooting why it wasn't working (both its z-index having to be set to be higher than the button under it and assigning a color to it, which I had left blank thinking the color of the shadow would be black) led me to understand better what affects this property. I also learned what had been causing my projects to have scroll bars, and after asking around and tinkering with it a bit I managed to get rid of them for both the Desktop version (easy) and the mobile version (harder). I say the mobile version was harder because I only had to set overflow:hidden on the body to get rid of the scroll bars on the desktop version, but to get rid of them on the mobile version I had to remove the body's default margin (I was unaware of its existence) and change the sizing units of the body from vh to svh to center it afterwards, because so0me of the screen was apparently hiding behind the address bar.

### Continued development

I will try to continue to implement a mobile-first approach in my future projects, as well as keep everything else I learned in this project in mind, especially when it comes to preventing scroll behaviours.

## Author

- Linkedin - [Alexandre Simões](https://www.linkedin.com/in/alexandre-sim%C3%B5es-21198a223/)
- Frontend Mentor - [@Alexandre-Simoes361](https://www.frontendmentor.io/profile/Alexandre-Simoes361)

## Acknowledgments

A big thank you to David Tejada from Frontend Mentor, who helped me understand why the scroll behaviour of my mobile solution wasn't working as intended. Hats off to him, he was a huge help.