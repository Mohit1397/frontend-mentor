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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

Built a QR Code Card layout using HTML & CSS to start my Web Development Journey. I have tried to build it as close as possible to screenshot shared by Frontend Mentor.  

### Screenshot

![Desktop Design](screenshot/desktop-view.jpg)
![Mobile Design](screenshot/mobile-view.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://mohit1397.github.io/qr-code-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

The mobile layout wasn't responsive as per the design, and after surfing almost about everything I finally learned about the @media rule which basically means that we can apply different styles for different media types/devices.

Here's the code snippet for media query which I have used

```css

@media screen and (max-width: 450px) {
    .qr-code-background {
        padding: 4%;
        width: 80%;
        margin: 10% auto 25%;
    }
    
    h3 {
        font-family: 'Outfit', sans-serif;
        font-weight: 700;
        font-size: 1.5rem;
    }

    .description {
        font-family: 'Outfit', sans-serif;
        font-weight: 400;
        font-size: 1.15rem;
    }
}

```

### Continued development

I want to try and apply different scripts once I have learned JS. 

### Useful resources

- [@media rule](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp) - This helped me to apply different rules for different devices.

## Author

- Website - [Mohit Pandey](https://mohit1397.github.io/resume/)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Mohit1397)
- Twitter - [@yourusername](https://twitter.com/mohitpandey1397)

