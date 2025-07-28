# fylo-data-storage-component-master
fylo-data-storage-component-master

This is a solution to the [fylo-data-storage-component-master on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

These are my screenshots showing how the project turned out.

- Mobile design:

![design](./assets/images/screenshot-mobile-design.png)

- Desktop design above 1023px:

![design](./assets/images/screenshot-desktop1-design.png)

- Desktop design above 1439px:

![design](./assets/images/screenshot-desktop2-design.png)


### Links

- Solution URL: [My Solution](https://github.com/gillaercio/fylo-data-storage-component-master)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I took advantage of this project to practice using **pseudo-element** and **clamp** with **CSS**:

Pseudo-element

```css
.storage-left::after {
  content: '';
  position: absolute;
  bottom: -18px;
  left: 94%;
  transform: translateX(-50%);
  border-width: 10px;
  border-style: solid;
  border-color: white white transparent transparent;
}
```

Clamp

```css
.storage-used {
  padding-left: 2.7rem;
  font-size: clamp(1.4rem, 1.2rem + 1.666vw, 2rem);
}
  
.storage-values {
  font-size: clamp(1.2rem, 1rem + 1.666vw, 1.5rem);
}
```

### Continued development

I would like to improve the use of the **HTML**, **CSS** and **JavaScript**.

## Author

- Frontend Mentor - [@gillaercio](https://www.frontendmentor.io/profile/gillaercio)
- Github - [My Github](https://github.com/gillaercio)
- LinkedIn - [My LinkedIn](https://www.linkedin.com/in/gildman-la%C3%A9rcio/)