# The Odin Project - Margin and Padding 2

This is a solution to the [Margin and Padding exercise No. 2 of Foundations](https://github.com/TheOdinProject/css-exercises).

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

![Margin and Padding 2 outcome](./desired-outcome.png "Margin and Padding 2")

### Links

- Solution URL: [Margin and Padding 2 solution](https://github.com/jugglingdev/css-exercises/tree/main/margin-and-padding/02-margin-and-padding-2)

## My process

### Built with

- HTML5
- CSS

### What I learned

This exercise was a step up from Margin and Padding 1.  In it, I had to change the padding and margin of different elements as well as use `text-align: center` and `display: block`. 

A few margins had to be side specific, utilizing `margin-top` and `margin-bottom`, for example.  This was because the padding of the `card <div>` would get added to the margin of the inside elements if you weren't careful (totally missed that at first).  There's margin collapse, but not padding-margin collapse.

For the `button-container`, I actually first used a `<br>` to kick the button to the next line.  The solution set the button to `display: block` instead.  In context, that does make more sense.

### Continued development

In future projects, I'd like more experience changing inline elements to block elements.  It will be interesting to see all the cases where this attribute change is needed.

### Useful resources

- [MDN Display](https://developer.mozilla.org/en-US/docs/Web/CSS/display) - Quick demonstration of different `display` types.

## Author

- GitHub - [@jugglingdev](https://github.com/jugglingdev)

- freeCodeCamp - [@jugglingdev](https://www.freecodecamp.org/jugglingdev)

- Frontend Mentor - [@jugglingdev](https://www.frontendmentor.io/profile/jugglingdev)

- LinkedIn - [Kayla Paden](https://www.linkedin.com/in/kayla-marie-paden)

## Acknowledgments

Shoutout to The Odin Project and all the contributors for their awesome work in building a solid curriculum for backend development.