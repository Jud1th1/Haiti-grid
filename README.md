# Haiti-grid
CSS grid practice

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)


## Overview

This exercies involved practicing grid layouts, as well as animations. 


### Links

- Live Site URL: https://updatedhaiti-animationgrid.netlify.app/


## My process

- I worked this through by following along with a the Grid Layout Lessons from Jeff Delaney: https://fireship.io/lessons/three-responsive-css-grid-layouts/. 
- This grid is an explicit grid where each element was placed in a specific area by name inside my grid container(parent). 
- The explicit grid use the grid-template-areas property to specify the positions. 
- From there I assigned each child element a number, added a photo inside their respective element and uploaded the 	base css file provided with the tutorials.  


### Built with

- HTML
- CSS 
- Grid
- Explicit grid
- Animation
- Tutorial used: https://fireship.io/lessons/three-responsive-css-grid-layouts/


### What I learned

- How to make a easy gallery with an explicit grid, that allows a much easier way to place and position items inside of a grid.
- CSS is fun! ha!



 CSS code that I am proud of (Learning how to use the grid-template-areas): 
```css
    grid-template-areas:
    'a  b  c  d'
    'l  🌟 🌟 e'
    'k  🌟 🌟 f'
    'j  i  h  g';

    grid-template-rows: repeat(4, 25%);
    grid-template-columns: 240px auto auto 240px;
```


### Continued development

- Helpful resource if stuck: https://www.w3schools.com/cssref/pr_grid.php
- More practice: https://scrimba.com/learn/cssgrid


