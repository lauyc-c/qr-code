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
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](images\qr-code-finished-page.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Throughout this project, techniques for applying styles to elements were used, particularly the use of element sizing and flexbox. Some of the notable code include:

```css
body {
    background-color: #d6eaf8;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    min-width: 100vw;
}

div {
    background-color: #ffffff;
    text-align: center;
    width: 20%;
    border-radius: 5%;
    padding: 20px;
    margin: auto;
    display: flex;
    flex-direction: column;
    align-self: center;
}
```

### Continued development

Currently, the QR code is not displayed in full when the window is shrunk to a certain size, while the background of the body element is still shown. Specific code on flexbox will have to be further acquired and applied in order to allow the main contents to take up a minimun size of the whole window.

### Useful resources

- [The Web Developer Bootcamp 2023](https://www.udemy.com/course/the-web-developer-bootcamp/) - This taught me basic HTML and CSS for me to complete this project. The Pricing Panel Code-along helped me familiarise with the concepts of flexbox.

## Author

- Website - [Cappi Lau](https://github.com/lauyc-c)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
