# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

(./project-screenshot.png)


### Links

- Solution URL: [https://github.com/lioba-s/qr-code-component/tree/main](https://github.com/lioba-s/qr-code-component/tree/main)
- Live Site URL: [https://lioba-s.github.io/qr-code-component/](https://lioba-s.github.io/qr-code-component/)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

Training my eye to identify design choices, like colour differences and spacing, more clearly. I value this as a helpful base-line understanding, although I imagine it would be much easier to use more accurate specifications from a Figma file (I chose not to get Frontend Mentor's PRO membership for now). For this particular project, I went with the advice given on the Discord forum that testing out my guesses on the sizes here might get me close enough to the original.
What is the difference between the different CSS units? I used this article as a starting point where all commonly used units are contrasted: https://medium.com/level-up-web/the-difference-between-css-units-px-pt-rem-em-vh-vw-ch-ex-and-the-rest-b2cfdf069230 For this project particularly, sizes were provided in px in the design file. I now know they should always be converted to rem before using them in code. This way, they will scale according to the user's chosen design size. This way, issues of possible overlap can be avoided and, even more importantly, accessibility issues: Using px instead of rem might make the text too small to read for many users, as their chosen font settings will not be considered this way.
How do I make the footer stay in place and avoid overlapping text on the page? I referenced this guide to answer this question: https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/
Which heights and widths do I need to set for which element exactly? Specifically, I was confused with the differences between setting the height/width for the html and for the body. I found answers here: https://www.freecodecamp.org/news/html-page-width-height/


### Continued development

Here are some things I'll want to use for future projects.

1. Making use of the option to comment out code and leave notes during development even more often - so helpful to mark lines/segments to come back to.
2. For the style guide, use these guiding questions:
   Accurate? - compare to desired/original design 
   Responsive? - check different screen sizes 
   Accessible? 
    - Use alt for images 
    - Use clear structure, check if possibility to navigate everything with keyboard 
    - Consider design choices, e.g. high contrast, using rem instead of px for font-size 
    - Esp. for mobile: elements must be arranged in a way that makes them easy to tap (concerning centering + margins etc.)
    - This is a huge topic and I'm actively collecting more points along the way!
3. Adding a modern css reset to the stylesheet is a necessity that I hadn't been aware of before. I have seen this one to be commonly referred to and will use it for future projects also: https://www.joshwcomeau.com/css/custom-css-reset/


## Author

- LinkedIn - [Lioba Schneider](https://www.linkedin.com/in/lioba-schneider-baa13b273/)
- Frontend Mentor - [@lioba-s](https://www.frontendmentor.io/profile/lioba-s)
- freeCodeCamp - [@lioba](https://www.freecodecamp.org/lioba)


## Acknowledgments

To learn the basics, I used freeCodeCamp and was so happy with that. I found Frontend Mentor a great way to test and deepen my knowledge.
On the Frontend Mentor Discord, I found many comments by Alex K. Marshall (https://github.com/AlexKMarshall) on the topics I was researching - specifically for this challenge - very helpful and motivating. Thank you!




[#built-with]: #built-with
