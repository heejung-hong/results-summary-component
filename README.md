# Frontend Mentor - Results summary component solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

#### Desktop View

![Screenshot 2024-03-27 at 4 19 10 PM](https://github.com/heejung-hong/results-summary-component/assets/133067265/cba22d63-c574-444c-b260-3a960e8e7768)

#### Mobile View

![Screenshot 2024-03-27 at 4 19 25 PM](https://github.com/heejung-hong/results-summary-component/assets/133067265/01051ad8-857a-455d-aae3-82d504f56aa8)

### Links

- [Solution URL](https://github.com/heejung-hong/results-summary-component)
- [Live Site URL](https://heejung-hong.github.io/results-summary-component/)

## My process

### Built with

- HTML
- CSS
- Flexbox


### What I learned

Adding the corner accents was the most challenging part of this project.

To see how you can add code snippets, see below:

```html
<div class="reaction">
  <div class="curveBL curveR"></div>
  <div class="curveTL curveR"></div>
  <div class="curveTR curveR"></div>
  <div class="curveBR curveR"></div>  
</div>
```
```css
.curveTR {
  right: 0;
  top: 0;
  rotate: 315deg;
}

.curveTL {
  top: 0;
  rotate: 225deg;
}

.curveBL {
  bottom: 0;
  rotate: 135deg;
}

.curveBR {
  bottom: 0;
  right: 0;
  rotate: 45deg;
}


.curveR, .curveM, .curveVe, .curveVi {
  position: absolute;
  z-index: -1;
  width: 16px;
  height: 16px;
}

.curveR {
  border: solid hsla(0, 100%, 67%, 0.15);
  border-radius: 7px;
  border-width: 0 2px 0 0;
}
```

### Useful resources

- [RWD - Media Queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) - This create a responsive web design without using CSS framwork.

## Author

- Website - [Portfolio](https://heejung-hong.github.io/Portfolio/)
- Frontend Mentor - [@heejung-hong](https://www.frontendmentor.io/profile/heejung-hong)
- LinkedIn - [heejung-hong](https://www.linkedin.com/in/heejung-hong/)


