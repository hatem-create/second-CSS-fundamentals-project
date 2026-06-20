# second-CSS-fundamentals-project
# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMTo9vPnAs). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size (Achieved through foundational layout positioning).

### Screenshot

<img width="1400" height="1050" alt="image" src="https://github.com/user-attachments/assets/2477e22a-1a4f-4012-a02a-c389e17036b1" />




## My process

### Built with

- Semantic HTML5 markup
- CSS Custom Properties & Typography
- Advanced CSS Positioning (`position: relative` / `absolute`)
- Negative Margin Layout manipulation (Restricted constraints challenge)

### What I learned

This project was built under a specific architectural constraint: **No CSS Grid or Flexbox allowed**. The core objective of this approach was to strictly master the fundamentals of CSS document flow, block/inline behavior, and advanced positioning mechanisms.

Solving a complex modern "Bento Grid" layout using only basic fundamentals drastically improved my problem-solving and deep layout debugging skills. 

For instance, managing vertical and horizontal alignments forced me to heavily calculate elements boundaries manually:

```css
.content-manage-help {
    position: relative;
    background-color: hsl(31, 66%, 93%);
    margin-right: 960px;
    margin-left: 149px;
    margin-top: -2027px; /* Handling precise structural offsets manually */
}
