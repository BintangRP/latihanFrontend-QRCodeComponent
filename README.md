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

## Overview

### Screenshot

![Screenshot QR Code](https://github.com/BintangRP/latihanFrontend-QRCodeComponent/blob/main/FireShot%20Capture%20001%20-%20Frontend%20Mentor%20-%20QR%20code%20component%20-%20Bintang%20Rizqi%20Pasha%20-%20.png)

### Links

- Solution URL: [latihanFrontend-QRCodeComponent](https://github.com/BintangRP/latihanFrontend-QRCodeComponent)
- Live Site URL: [latihanFrontend-QRCodeComponent/](https://bintangrp.github.io/latihanFrontend-QRCodeComponent/)

## My process


### Built with

- Semantic HTML5 markup
- Flexbox



### What I learned

```html
<div class="container center">
  <div class="card">
    <div class="card-header">
      <img src="./images/image-qr-code.png" alt="QR Code" />
    </div>
    <div class="card-body">
      <h3>
        Improve your front-end skills by building projects
      </h3>
      <small>
        Scan the QR code to visit Frontend Mentor and take
        your coding skills to the next level
      </small>
    </div>
  </div>
</div>
```
Cara membuat card dengan card-header dan card-body dengan mencontoh dari [Bootstrap](https://getbootstrap.com/docs/5.2/components/card/)
<br> How to make a card with a card-header and card-body by following the example from [Bootstrap](https://getbootstrap.com/docs/5.2/components/card/)

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: auto;
  width: 300px;
  margin: 50px auto;
  background-color: white;
  border-radius: 20px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}
```
Belajar membuat container menggunakan flexbox | Learn to create containers using flexbox 
[A Complete Guide to Flexbox | CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)<br>
mengetahui fungsi dari border-radius | know the function of the border-radius
<br>
mengetahui cara membuat box-shadow | know how to make a box-shadow
<br>
mengetahui cara membuat margin | know how to use margin
<br>
mengetahui cara membuat padding | know how to use padding
<br>

### Continued development

section css best practice and how to handle floating item cause i dont know the best practice to writing this css and just code it. :)
<br>
i hope in the future, i can learn the best practice of HTML/CSS
```
.card {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%;
  text-align: center;
  padding-bottom: 30px;
}
.card img {
  margin-top: 20px;
  width: 85%;
  border-radius: 10px;
  object-fit: contain;
}
.card-body {
  color: rgb(18, 18, 53);
  font-size: 0.9rem;
  margin: 20px 40px;
}
.card-body h3 {
  margin-bottom: 10px;
  font-weight: bolder;
}
.card-body small {
  opacity: 0.6;
}
```

### Useful resources

- [A Guide To Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me for learning this flexbox things. I really liked the description of flexbox.
- [Bootstrap](https://getbootstrap.com/docs/5.2/getting-started/introduction/) - This bootstrap can boost your code especially in writing css, really like it too. And im gonna use this for future challenge.

## Author

- Website - [Bintang Rizqi Pasha](https://bintangrp.github.io/)
- Frontend Mentor - [@BintangRP](https://www.frontendmentor.io/profile/BintangRP)
- Twitter - [@btgrzqi2](https://www.twitter.com/btgrzqi2)
