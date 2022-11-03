# qr-component


# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Links

- Solution URL: [Repository](https://github.com/ingrafaelmartinez/qr-component)
- Live Site URL: [Live Demo](https://ingrafaelmartinez.github.io/qr-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

My greatest learning during the development of this challenge was to be able to put into practice knowledge that I thought was difficult to achieve. The positioning of HTML elements through the use of CSS properties, as well as the implementation of Flexbox for a better development of it.

```html
<article class="card">
            <figure class="card__img">
                <img src="./assets/img/image-qr-code.png" alt="Código QR con link a FrontEnd Mentor">
            </figure>
            <h3 class="card__title">Improve your front-end skills by building projects</h3>
            <p class="card__description">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
        </article>
```
```css
.card {
    width: 320px;
    padding: 16px;
    margin: 15px auto;
    border-radius: 19px;
    background-color: var(--white);
    box-shadow: 0px 3px 15px rgba(0, 0, 0, 0.2);

}

.card__img img {
    width: 100%;
    border-radius: 10px;
}

.card__title {
    padding: 10px;
    font-size: 22rem;
    text-align: center;
    color: var(--dark-blue);
}
```

## Author

- Frontend Mentor - [@ingrafaelmartinez](https://www.frontendmentor.io/profile/ingrafaelmartinez)
- Twitter - [@ingrafamartinez](https://twitter.com/ingrafamartinez)
- LinkedIn - [Rafael Martínez Rodríguez](www.linkedin.com/in/rafael-martínez-rodríguez-2b266a30)


