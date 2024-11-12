# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![Screenshot of Working Solution at Desktop Resolutions](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/ConnorGaunt/fem-bento-grid)
- Live Site URL: [Add live site URL here](https://fem-bento-grid-cg.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

This is the first time I've attempted this sort of layout before, but when I saw it on Frontend Mentor, I knew I wanted to give it shot! I've seen this becoming more and more of a trend, especially by companies like Apple.

The only way I could think to do such a layout on the web would be using CSS Grid but defining the areas AND the rows, with the middle row being set to a specific size two the two columns are the end could span the rest. Here's an example

```
/** Set the Areas **/
grid-template-areas:
      'create social-ai social-ai post-social'
      'create accounts maintain post-social'
      'ai-content accounts maintain post-social'
      'ai-content growth followers followers'
      'ai-content growth followers followers';

grid-template-columns: repeat(4, 1fr); // Make Sure all the columns are the same width
grid-template-rows: auto auto 250px auto auto; // Set middle row a fixed size so elms on the end can look like they're taking up the space of the others
```

### Continued development

In the future, I think setting up better font scaling styling could have been a better choice - also possibly using container queries.
