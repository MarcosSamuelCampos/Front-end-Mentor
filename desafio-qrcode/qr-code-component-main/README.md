# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview
    Creating a website using semantic HTML, and training my CSS skills.
### Screenshot

![](./images/qr-code-challenge.jpg)


## My process

  I found it difficult to reduce the QR code to fit inside the other block. I thought that because it was an image, I would have to edit it and make it smaller manually. But, I managed to solve it using CSS.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned to place a box inside another and adjust the inside box using the width to reduce it.

```css

..container{
  ...
  width: 300px /*I managed to adjust the size of the container to later place the qr code image inside the box. */
}
.img{
  ...
  width:100%;  /*adjust the qr-code image inside the container. */
  ...
}
```

### Continued development

I still need to train more on flexbox and box model in CSS.
