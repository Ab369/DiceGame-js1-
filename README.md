# Dice game using Js
This is a basic dice game project.

## Table of contents
- [Dice game using Js](#dice-game-using-js)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview
- The game involves a webpage showing two dices and a start button. On pressing the start button both dices genrates random output and winner name decided on basis of this output.
- This project is made as a part of learning frontend web develpoement.

### Links
- Live Site URL: [Add live site URL here](https://dice-game-js1.vercel.app/)

## My process
- Firstly I made the html structure which is quite simple.
- then i designed it using CSS
- Finally added javascript and got required fuctionalities in the webpage.
  
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Javascript

### What I learned
This project taught me a number of things -
- Using Math.floor and Math.random function to get integer in given range.
*code:var n1=Math.floor(Math.random()*6)+1;*

- Using function in JS and returning value

- selecting elements by- **document.getElementById** and **document.querySelector**

- changing html attributes using javascript
*code:var element=document.getElementById("dice2");*
*element.src=ChangeImg(n2); OR element.setAttribute("src",ChangeImg(n1));*

- using element.textContent to change text of html element
- We can also use element.innerHTML but  it's important to be cautious when using innerHTML as it can introduce security risks if the content is not properly sanitized.

- Adding Audio using HTML **new Audio() **constructor and **audio.play();**
*code: var audio1=new Audio('p1.mp3');*
*audio1.play();*

- adding refresh button using **location.reload()**

### Continued development
I would Continue to learn frontend web developement and HTML,CSS,JS. Further I would learn various JS frameworks.

## Author

- Linkedin: URL[www.linkedin.com/in/9abhinav](www.linkedin.com/in/9abhinav)
- Twitter - [twitter.com/Abhinav43358626](twitter.com/Abhinav43358626)

## Acknowledgments
- The Complete 2023 Web Development Bootcamp by Angela Yu