# Welcome! 👋

This is a solution to the challenge [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q).
of a preview stats card made to test my knowledge in `html` and `css`.

---

## Table of contents
- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge:
Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- [solution URL](https://github.com/MarcoFranca/DesafioFulltureSite.git)
- [live site URL](https://marcofranca.github.io/DesafioFulltureSite/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- desktop-first

### What I learned


I reinforced my CSS knowledge in `position: absolute` , `:hoover`, `@media query` and `overflow`.

---
```css
.firstContainer--img{
    background-image: url("../../assets/image-hero-desktop@2x.png");
    background-size:cover ;
    background-repeat: no-repeat;
    position: absolute;
    top: -150px;
    right: 0;
    width: 720px;
    height: 950px;
}
```

```css
.button--2:hover{
    background-image: linear-gradient(rgba(255, 111, 72, 0.5), rgba(240, 42, 166, 0.5));
}
```

```css

@media screen  and (max-width: 425px){
    main{
        position: relative;
        background-image: linear-gradient(#FFFFFF 50%, rgb(239, 241, 254));
        max-width: 100vw;
        overflow: hidden;
        padding: 0;
    }

}
```


### Continued development

I will dedicate myself to future projects using javascript concepts along with html and css which I am studying and improving myself


## Author

- Linkdin - [Marco Tullio Franca](https://www.linkedin.com/in/marco-franca/)
- Frontend Mentor - [@MarcoFranca](https://www.frontendmentor.io/profile/MarcoFranca)


