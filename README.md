# Frontend Mentor - Product preview card component
This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot
![image](https://user-images.githubusercontent.com/113911084/192100392-94d7490f-f058-4eee-b665-fa8f4fa8ab92.png)

### Links

- Solution URL: [https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa/hub/product-preview-card-component-main-1Hc4SXNMAP))]
- Live Site URL: [https://dinaelmasry22.github.io/product-preview-card-component-main/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- picture tag
- [Styled Components](https://styled-components.com/) - For styles

### What I learned
```html
<picture>
      <source media="(min-width: 800px)" srcset="./images/image-product-desktop.jpg">
      <source media="(min-width: 300px)" srcset="./images/image-product-mobile.jpg">
      <img src="./images/image-product-desktop.jpg">
 </picture>
```
```css
/*To import font family*/
    @import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Istok+Web:wght@700&family=Montserrat&family=Nunito+Sans:wght@700;900&family=Open+Sans:wdth,wght@97.2,300;100,500&family=Outfit:wght@300;400;600&family=Rubik+Mono+One&family=Rubik+Moonrocks&family=Rubik+Puddles&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Istok+Web:wght@700&family=Montserrat&family=Nunito+Sans:wght@700;900&family=Open+Sans:wdth,wght@97.2,300;100,500&family=Outfit:wght@300;400;600&family=Rubik+Mono+One&family=Rubik+Moonrocks&display=swap'); 

    body {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      box-sizing: border-box;
      font-family: 'Montserrat', sans-serif;
    }
```

### Useful resources

- [https://www.freecodecamp.org/arabic/news/stlht-tsmy-css-twfr-aalyk-saat-mn-ltshyh/] - This site helped me to name css classes in the correct way. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/dinaElmasry22]
- Twitter - [https://twitter.com/Dina7465?t=zk-rjh7LKaxehwGkNiAvfQ&s=09]

## Acknowledgments
- My friend Zainab  [(https://www.behance.net/zenabmohammed1)]
