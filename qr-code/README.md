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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

A screenshot of the final project is shown below;
![screenshot of final design](https://drive.google.com/thumbnail?id=1TdGomHGhijZAnAr4VSyQmFXCJ4fg_0I2)

### Links

- Solution URL: The project solution can be found [here](https://github.com/saogiji/personal-projects/tree/main/qr-code)
- Live Site URL: The Live Site solution can be found [here](https://codepen.io/saogiji/full/abYJRLp)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

How to position elements using css property `position`
For example, the code below will center the element with class of inner vertically and horizontally.

```html
<div class="container">
  <div class="inner"></div>
</div>
```

```css
.container {
  width: 350px;
  height: 200px;
  outline: dashed 1px black;
  position: relative;
}
.inner {
  width: 50px;
  height: 50px;
  background-color: red;
  /* Center vertically and horizontally */
  position: absolute;
  top: 50%;
  left: 50%;
  /* Apply negative top and left margins to truly center the element */
  margin: -25px 0 0 -25px;
}
```

### Continued development

How to use other methods such as gridbox and flexbox to achieve same result

### Useful resources

- [FreeCodeCamp](https://www.freecodecamp.org/news/how-to-center-anything-with-css-align-a-div-text-and-more/) - This helped me to center the html elements vertically and horizontally.

## Author

- Website - [Simon Adanu Ogiji](https://github.com/saogiji)
- Frontend Mentor - [@saogiji](https://www.frontendmentor.io/profile/saogiji)
- Twitter - [@OgijiSimon](https://twitter.com/OgijiSimon)
- CodePen - [@saogiji](https://codepen.io/saogiji)

## Acknowledgments

I am grateful for the resources at [FreeCodeCamp](https://www.freecodecamp.org/news) which I used to learn the skills to be able to complete this project.
