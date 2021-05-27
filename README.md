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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/screenshot#1.jpeg)
![](./images/Screenshot#2.jpeg)
![](./images/'Desktop preview'.jpeg)


### Links

- Solution URL: (https://github.com/Pranav0210/stats-preview-card-component-main.git)
- Live Site URL: (https://pranav0210.github.io/stats-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

This section recaps over a couple of my major learnings while working through this project.

#### 1. ordering flex items
```css
      .stats{
        grid-area: "stats";
        font-weight: 400;
        color: hsla(0, 0%, 100%, 0.6);
        padding-top: 50px;
        font-family: 'Inter';
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
      }
      .stats :nth-child(1) { order: 1; }
      .stats :nth-child(2) { order: 2; }
      .stats :nth-child(3) { order: 3; }
      .stats :nth-child(4) { order: 1; }
      .stats :nth-child(5) { order: 2; }
      .stats :nth-child(6) { order: 3; }
```
#### 2. excluding classes from certain parent attributes
```css
.stats :not(.fact){
  text-transform: uppercase;
}

.stats :not(.undertext){
  font-size: x-large;
}
```


### Useful resources

- [MDN Article](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Ordering_Flex_Items) - This helped me learn how to order flex items.


## Author

- Website - [Pranav Patel]()
- Frontend Mentor - [Pranav0210](https://www.frontendmentor.io/profile/Pranav0210)
- LinkedIn - [Pranav Patel](https://www.linkedin.com/in/pranav-patel-2821b7208)


## Acknowledgments

Thanks [Raj Aryan](https://github.com/SilverGraph). Buddy u've been a great help when I was stuck.

