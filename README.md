# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview
This is my solution to the frontend mentor challenge which was given to me as a project-assignment  from dyen academy 

### Screenshot
![A preview of my solution ](<my solution/Screenshot 2024-03-02 at 18.13.12.png>)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
  I first created the structure of the page with html with the appropriate html tags and elements 
  then added the right styles with css to give it the same feel as the one shown to me for the challenge 
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I learned about the ::before psuedo selector, I found it dificult to change the color of the bullet points , not until i found out that theres no css code for do that single hardly , its was really interesting and i loved the challenge !!:)


```html
  <ul>
        <li> <b>Total:</b> Approximately 10 minutes</li>
        <li> <b>Preparation:</b> 5 minutes</li>
        <li> <b>Cooking:</b> 5 minutes</li>
  </ul>
```
```css
ul {
    list-style: none;
}
```
```css
ul li::before {
    content: '\2022'; /* Unicode character for a bullet point */
    color: hsl(332, 51%, 32%); /* Change the bullet color */
    display: inline-block;
    width: 1em; /* Adjust the width for spacing */
    margin-left: -1em; /* Adjust margin for spacing */
}
```


### Continued development

would really like to learn more about psuedo selector as well as javascript so i will be well backed on the skill set to build a dynamic website  ,,, I Just want to try out new things 


## Author

- Website - [my github](https://github.com/Mr-oghoski-AB)
- Frontend Mentor - [@Mr-oghoski-AB](https://www.frontendmentor.io/profile/Mr-oghoski-AB)
- Twitter - [@Mroghoski](https://www.twitter.com/Mroghoski)

