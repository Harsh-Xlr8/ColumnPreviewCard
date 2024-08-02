## Table of Contents
- [Overview](#overview)
- [The Challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Links](#links)
- [My Process](#my-process)
- [Built With](#built-with)
- [What I Learned](#what-i-learned)
- [Continued Development](#continued-development)
- [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
This project is a simple HTML and CSS design layout. It showcases different car types (Sedan, SUV, and Luxury) in a clean, responsive format. The design focuses on semantic HTML5 markup, CSS custom properties, Flexbox, and a mobile-first workflow.

## The Challenge
Users should be able to:
- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## Screenshot
![Project Screenshot1](./screenshots/Screenshot%202024-08-02%20at%202.50.50%20PM.png)
![Project Screenshot2](./screenshots/Screenshot%202024-08-02%20at%202.50.59%20PM.png)

## Links
- [Live Site URL](https://columnspreview.netlify.app/)

## My Process
### Built With
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### Code Example
Here is a sample of the CSS used in this project:
```css
*{
    padding: 0px;
    margin: 0px;
}

.box {
    height: 400px;
    padding: 0px 50px;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: flex-start; 
}

.sedan {
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    background-color: hsl(31, 77%, 52%);
    color: hsl(0, 0%, 95%);
}

img {
    width: fit-content;
}

button {
    font-weight: bold;
    padding: 13px 35px;
    text-align: center;
    cursor: pointer;
    outline: none;
    background-color: hsl(0, 0%, 95%);
    border: none;
    border-radius: 40px;
}

button:hover {
    background-color: lightgrey;
}

button:active {
    background-color: lightblue;
    transform: translateY(5px);
}

.button1 {
    color: hsl(31, 77%, 52%);
}
```

### What I learned

This project allowed me to reinforce my knowledge of semantic HTML5 and CSS, particularly in using Flexbox for layout and CSS custom properties for theming. I also learned the importance of a mobile-first workflow and how to create responsive designs that adapt well to different screen sizes.

### Continued development

In future projects, I aim to:

Improve my understanding and application of CSS Grid
Experiment with more complex animations and transitions
Further refine my mobile-first design approach

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS) - Comprehensive resource for web development documentation and best practices.

- [CSS Tricks](https://css-tricks.com/) - Great articles and tips for improving CSS skills.

## Author

Harsh Tiwari

## Acknowledgments

Thanks to Gangadhar Sir who provide this project and guided me to successful implemention of this project. 