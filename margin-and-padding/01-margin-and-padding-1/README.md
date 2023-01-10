# The Odin Project - Margin and Padding 1

This is a solution to the [Margin and Padding exercise No. 1 of Foundations](https://github.com/TheOdinProject/css-exercises).

## Table of contents

- [Overview](#overview)
  - [Outcome](#outcome)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Outcome

![Margin and Padding 1 outcome](./desired-outcome.png "Margin and Padding 1")

### Links

- Solution URL: [Margin and Padding 1 solution](https://github.com/jugglingdev/css-exercises/tree/main/margin-and-padding/01-margin-and-padding-1)

## My process

### Built with

- HTML5
- CSS

### What I learned

In this exercise, index.html was already complete and I only needed to change the margin and padding in styles.css.  The process was simple, but I liked that Odin avoided using jargon so you had to think about whether the "space between" was referring to `margin` or `padding`.

The one spot that got me on this one was `margin-left: auto` for right-alignment of the last `div`.  My first thought was to use `margin-right: 0` instead, which did nothing for me.

In some fairly brief research, I found 2 things:

1. In margins, `auto` can mean either 0 px OR take up the available space.  I didn't realize the latter and was therefore stumped at why `margin-left: auto` resulted in right-alignment.

2. I now have a glimpse of the meaning behind all the CSS memes.

### Continued development

While this exercise was simple, I'm curious to see what comes next in the wild world of CSS.

To be continued in the next exercise...

### Useful resources

- [Hongkiat CSS Margin Auto](https://www.hongkiat.com/blog/css-margin-auto/) - This article cleared up that "auto" in margins could mean either 0 px OR take up the available space.  This cleared up the last step of this exercise.

## Author

- GitHub - [@jugglingdev](https://github.com/jugglingdev)

- freeCodeCamp - [@jugglingdev](https://www.freecodecamp.org/jugglingdev)

- Frontend Mentor - [@jugglingdev](https://www.frontendmentor.io/profile/jugglingdev)

- LinkedIn - [Kayla Paden](https://www.linkedin.com/in/kayla-marie-paden)

## Acknowledgments

Shoutout to The Odin Project and all the contributors for their awesome work in building a solid curriculum for backend development.