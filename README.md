# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Screenshot](./Screenshot.png)

### Links

- Solution URL: [Solution URL](https://github.com/Pruthuvi9/3-column-preview-card-component)
- Live Site URL: [Live site URL](https://pruthuvi9.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css
@media screen and (min-width: 600px) {
  body {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    background-color: hsl(0, 0%, 95%);
    padding: 10%;
    margin: auto;
    max-width: 900px;
    /* width: 900px; */
    border-radius: 5px;
  }

  #card-stack-element {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
  }

  .orange-element {
    border-bottom-left-radius: 1em;
  }

  .very-dark-cyan-element {
    border-top-right-radius: 1em;
  }  
}

@media screen and (max-width: 599px) {
  body {
    padding: 10%;
    margin: auto;
  }

  .orange-element {
    border-top-right-radius: 1em;
  }

  .very-dark-cyan-element {
    border-bottom-left-radius: 1em;
  }
}
```

## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/Pruthuvi9]
- Twitter - [https://twitter.com/pruthuvi1995]

