# qr-code-component

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [What was this project helpful for to me?](#helpful-for)
  - [Questions during executing the project](#questions)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### What was this project helpful for to me?

 1. Training my eye to identify design choices, like colour differences and spacing, more clearly. I value this as a helpful base-line understanding, although I imagine it would be much easier to use more accurate
      specifications from a Figma file (I chose not to get Frontend Mentor's PRO membership for now). For this particular project, I went with the advice given on the Discord forum that testing out my guesses on the
      sizes here might get me close enough to the original.
  2.


### Questions during executing the project

1. How do I name the different objects?
      Specifically, I didn't yet quite understand the subtle differences between ids and classes and which part of the name to pick to target the object in the css file.
      From my current understanding, with divs, it often makes sense to give them classes, especially if there are several that have similar roles. The same value can theoretically be used multiple times here.
      Ids, on the other hand, are specific to one single object. The value of this attribute must be unique within the whole document, and it can help assign identifiers
      to certain objects, like buttons (though this was not used here).
      When setting properties for objects in the CSS file, there are multiple ways to target the objects; using its element name, id, or class all work. From my research,
      one is not necessarily better than the other, although one or the other can be more well-suited depending on the use-case. ........
  2. What is the difference between the different CSS units?
      I used this article as a starting point where all commonly used units are contrasted: https://medium.com/level-up-web/the-difference-between-css-units-px-pt-rem-em-vh-vw-ch-ex-and-the-rest-b2cfdf069230
      For this project particularly, sizes were provided in px in the design file. I now know they should always be converted to rem before using them in code.
      This way, they will scale according to the user's chosen design size. This way, issues of possible overlap can be avoided and, even more importantly, accessibility issues:
      Using px instead of rem might make the text too small to read for many users, as their chosen font settings will not be considered this way.


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Here are some things I'll want to use for future projects.
1. Make use of the option to comment out code and leave notes during development even more often - so helpful to mark lines/segments to come back to.
2. For the style guide, use these guiding questions:
  2.1 Accurate? - compare to desired/original design
  2.2 Responsive? - check different screen sizes
  2.3 Accessible?
    2.3.1 Use alt for images
    2.3.2 Use clear structure, check if possibility to navigate everything with keyboard
    2.3.3 Consider design choices, e.g. high contrast, using rem instead of px for font-size
    2.3.4 Esp. for mobile: elements must be arranged in a way that makes them easy to tap (concerning centering + margins etc.)
3. Adding a modern css reset to the stylesheet is a necessity that I hadn't been aware of before. I have seen this one to be commonly referred to and will use it for future projects also: https://www.joshwcomeau.com/css/custom-css-reset/


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@ylioba-s](https://www.frontendmentor.io/profile/lioba-s)


## Acknowledgments

On the Frontend Mentor Discord, I found many comments by Alex K. Marshall (https://github.com/AlexKMarshall) on the topics I was researching very helpful and motivating. Thank you!
