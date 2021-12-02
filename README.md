# Frontend Mentor - Loopstudios landing page solution

This is a solution to the [Loopstudios landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/loopstudios-landing-page-N88J5Onjw). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot


![](design/desktop.PNG)
![](design/mobile.PNG)

### Links

- Solution URL: https://github.com/GMSTER22/loopstudios-challenge
- Live Site URL: https://gmster22.github.io/loopstudios-challenge/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

-I learned a really valuable lesson about planning the project before starting, in order to grasp the whole project and organize it to make my workflow better. I wasted some time because I didn't take the time to really analyze the mobile design of the website which led me not to include some elements into my grid for the galery, unfortunalety that was the kind of mistake that comes back to bite. 
-Used SASS mixins to group some properties that help not to repeat them in every single grid cell.
-I learned a little bit more about the use of css grid when it comes to size like "auto" or "mixmax". 

I am proud of making my own menu icon and the animation on click.

```css
& > .menu {   
                position: relative; 
                z-index: 11;                      

                & > .menu_button {
                    background-color: white;
                    transition: transform .15s linear;
                    margin-bottom: 0;
        
                    &:first-of-type {
                        background-color: white;
                        transform: translateY(0.7rem) rotate(45deg);
                    }
        
                    &:nth-of-type(2) {
                        display: none;
                    }
        
                    &:last-of-type {
                        background-color: white;
                        transform: translateY(.4rem) rotate(-45deg);
                    }
                }
            }
```

### Continued development

I want to focus more on the grid, I can learn more when it comes to using the properties for the dimension if the grid.

### Useful resources

- [Stackoverflow](ttps://stackoverflow.com/) - This helped me for making my website responsive because I had a hard time with the behaviour of the toggle device emulation on the chrome dev tool to check how the website look like on differenct dimension.

## Author

- Frontend Mentor - [@GMSTER22](https://www.frontendmentor.io/profile/GMSTER22)
- Twitter - [@YoungGael92](https://www.twitter.com/YoungGael92)