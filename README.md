# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](/screenshot.png)

### Links

- Solution URL: (https://github.com/Rapha445/fylo-data-storage-component)
- Live Site URL: (https://rapha445.github.io/fylo-data-storage-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM Methodology

### What I learned

- I learned to make an arrow using pseudo elements
- I learned to superpose divs using the position property
- I learned how to use the BEM methodology

```css
.space:after {
    content: '';
    position: absolute;
    bottom: 0;
    left: calc(100% - 0.7rem);
    width: 0;
    height: 0;
    border: 20px solid transparent;
    border-top-color: white;
    border-bottom: 0;
    border-right: 0;
    margin-left: -10px;
    margin-bottom: -20px;
  }
```


### Continued development

- I want to keep working on writing clean code using the BEM methodology.

### Useful resources

- [CSS Bubbly](http://projects.verou.me/bubbly/) - This website helped me to understand how to build triangle in CSS.


## Author

- Frontend Mentor - [@Rapha445](https://www.frontendmentor.io/profile/Rapha445)
