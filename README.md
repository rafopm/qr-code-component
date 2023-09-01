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
![image](https://github.com/rafopm/qr-code-component/assets/5562967/bb1dd522-3202-45ae-a436-563cb0f53c99)
![image](https://github.com/rafopm/qr-code-component/assets/5562967/67750ebe-dd28-47f6-9e32-7028e6206c49)



### Links

- Solution URL: (https://github.com/rafopm/qr-code-component))
- Live Site URL: (https://rafopm.github.io/qr-code-component/))

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Place the image inside the div and have the image inherit the rounded corners.

```html
          <div class="barcode">
            <img src="./images/image-qr-code.png" />
          </div>
```
```css

.barcode {
  width: 290px;
  height: 290px;
  border-radius: 10px;
  overflow: hidden;
}

.barcode img {
  max-width: 100%;
  height: auto;
}
```

### Continued development

It is very important for me to keep practicing and learning.

### Useful resources

- [Resource 1](https://developer.mozilla.org/es/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML) - It has information about the treatment of images with html.


## Author

- Website - [Rafael Pampavilca](https://rafopm.netlify.app/)
- Frontend Mentor - [@rafopm](https://www.frontendmentor.io/profile/rafopm)

## Acknowledgments


