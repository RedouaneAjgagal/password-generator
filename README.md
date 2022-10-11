# password-generator

This is Password Generator challenge on Frontend Mentor

## Table of contents

- [Overview](#overview)
  - [The Project](#the-project)
  - [Screenshots](#screenshots)
    -[Large screen](#large-screen)
    -[Small Screen](#small-screen)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Challenges](#challenges)
- [Author](#author)

## Overview

### The Project

Password Generator is a Challenge on [Frontendmentor](https://www.frontendmentor.io/challenges/password-generator-app-Mr8CLycqjh)

Users should be able to:

- View the optimal layout for the section depending on their device's screen size
- Select any type of passwords (UpperCase - LowerCase - Numbers - Symbols) or mixed them all for a strong password
- Have control on password length
- Button for a quick copy (disbaled when no box is checked)
- Strength chart for the password (From weaker to strong)
- Dark and Light mode availible for the user

### Screenshots

#### Large Screen

![Password-generator-desktop](https://user-images.githubusercontent.com/98456832/195217424-5191dbe7-e198-49f6-9abe-534c6659b9d0.png)


#### Small Screen

![Password-generator-mobile](https://user-images.githubusercontent.com/98456832/195215620-dd2703c7-f548-4dfc-a86b-2fe203c73249.png)


### Links

- Source: [GitHub Repository](https://github.com/RedouaneAjgagal/password-generator)
- Live: [Live Site](https://redouaneajgagal.github.io/password-generator/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media Queries
- JS

### Challenges

- `checkBoxes:` Well this was my main problem, how to apply each box that is selected whitch making bunch of functions for each box, i found a way to do so by using the same name of each box as the functions, and then i picked up those names in js and changed them to a function using `eval`, this way each box is selected will automatically become a function that i already made with the same name.
- `strength boxes:` This was little hard too to find the best for it to work properly, so i used took the length of checked boxes and based on that i made the logice, so basically each input is checked means +1, if only one is checked then it will give one red chart means its too weak. and if the password length below 6 chars it will also give one red chart.
- `Dark/Light mode:` Well i have never done this before, i searched online but i dint find any easier way than the one i used, im not sure if its the correct way but it worked well. basically changed the css var colors to the opposite ones and toggle between them.

## Author

- GitHub - [@RedouaneAjgagal](https://github.com/RedouaneAjgagal)
- Frontend Mentor - [@RedouaneAjgagal](https://www.frontendmentor.io/profile/RedouaneAjgagal)
