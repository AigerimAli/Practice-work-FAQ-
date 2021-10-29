# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Our process](#our-process)
  - [Built with](#built-with)
  - [What We learned](#what-we-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
In this project work, we did the FAQ card using three basic programming languages such as HTML,CSS,JAVASCRIPT. HTML used for "skeleton" of the project, with help of CSS we did closer design to the original project and JavaScript used for downward menu part. We tried to do as close as possible design of the project.

### The challenge
The main components that we should be able to:
- Properly choosed colors and font styles. 
- Closest design.
- Clear code.
- Properly using of active,hover states.
- Ability to hide/show the answer.

### Screenshot

![Our Work](./images/Unknown.jpeg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## Our process

First of all, we created the skeleton of the project. We used HTML and created different divs for certain using. For example, imgs div for images used in that challenge and container1,2 for the main content. Secondly, according to our HTML we created CSS part. On CSS part we used given fonts, colors and sizes. In addition, we used JavaScript for 'moving' part of our project - downward menu of questions/answers. 

### Built with

- HTML elements
- CSS custom properties
- Flexbox
- JavaScript

### What We learned

The main thing that we learned using JavaScript for our accordion. 

```js
 
  let accord = document.getElementsByClassName("container2");

        for (let i = 0; i < accord.length; i++) {
          accord[i].addEventListener("click", function() {
            this.classList.toggle("active");
            let answer = this.lastElementChild;
            let question = this.firstElementChild;
            let arrow = this.children[0].children[1];
            if (answer.style.display === "block") {
              answer.style.display = "none";
              arrow.style.transform = "rotate(0deg)";
            }
            else {
              answer.style.display = "block";
              arrow.style.transform = "rotate(180deg)";
            }
          });
        }
```
### Continued development

We are just started to learn JavaScript language. We think that to the end of our course we will know more than now. In future, we believe that our knowledge will be enough to create modern sites with challenging algorhitms.

### Useful resources

- (https://www.w3schools.com/howto/howto_js_accordion.asp) - This helped us to JavaScript reason. We really liked this pattern and will use it going forward.
- https://www.w3schools.com/js/default.asp - JavaScript Tutorial
- https://www.w3schools.com/html/default.asp - HTML Tutorial
- https://www.w3schools.com/css/default.asp - CSS Tutorial

## Author

- Instagram - [Bauyrzhan Dias] - (https://www.instagram.com/diasbauyrzhann/)
- Instagram - [Aliyeva Aigerim] - (https://www.instagram.com/aiger.ali/)

