# Frontend Mentor - Product preview card component solution
![Design preview for the Product preview card component coding challenge](/design/desktop-preview.jpg)

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Final Version (images)](#final-version-images)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

Evidence for the completed project meeting the challenge requirements:

view the image of my solution following the directory below:

![Desktop View - version 1]<br>
<a>
  <image src="/Code/Images/Desktop-imgv2.png" width="300" height="500">
</a>



Mobile View - version 1<br>
<a>
  <image src="/design/Mobile-imgv2.png" width="300" height="500">
</a>

Check the code here:
<!-- Html -->
![](./index.html)
<!-- CSS -->
![](./styles.css)

## My process
-I started the project by first reviewing the design and then reading file that came with this challenge.
  - By looking at the design I can breakdown all the part and visually plan which elements to group together.
    - So that It will be easier to style when I move to the CSS part of the challenge. 
- After i've reviewed the design I then started setting up my files that I need such the HTML and CSS.
- I then imported the checked that the images are in the file accordingly and move the code i needed from the style guide to the css file. 
- After i've finish setting up and checking that my files are working as intended I then started working on the HTML structure. 
  - Working on the desktop view first.
      ![](/MyCode/MyImages/Desktop-img.png)  
    - I added all the necessary tags with classes as needed to be able easily target them when working on the CSS.
    - After completing the structure, I then move to the CSS part and started styling all the element. 
    - Since I already setup the styling before hand I could then, begin with styling the elements and layout of the card.
    - With trial and error  I will try follow the design as close as possible till I'm happy with the way it looks. 
  -Working with Mobile desktop.
      ![](/MyCode/MyImages/Mobile-img.png)   
    - With the desktop completed, I then move on to making the card responsive in other devices. 
    - Which I had some issues with on my first try as I ran to some problems but I choose not to deviate and complete the rest of the component first before looking into the issues as this can take some time to fix(see more on this on [Continued development](#continued-development)section). 
      See screenshot.
      ![](/MyCode/MyImages/Responsive-issue.png)
    - I then style the component based on the mobile phone size design and similar with the desktop view, I try and get as close to the design as possible.
- Once happy with the result, I then move to looking into any issues that I can fix and then try and improve on my code. 

### Final Version Images
<!-- Desktop -->
![](/MyCode/MyImages/Desktop-imgv2.png)

<!-- Mobile -->
![](/MyCode/MyImages/Mobile-imgv2.png)

### Built with
This project was created using: 
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

During this challenge, I ran to a couple of issues mainly with how my css code was structured and making my component responsive.  

So I first tried completing the component all by my self to see how well I can go, I knew that I was lacking the knowledge of structuring my css code as I was running into issues with making it responsive. Using to many max-width and width properties, that were conflicting.
See ![](/MyCode/MyImages/Responsive-issue.png) 

To solve this issue, after trying to complete the project to the best of my abilities, I then tried to look into how other people solved the challenge, to learn how they would structure there code. Luckily Kevin Powell who teaches people how to use css efficiently has also done the front-end mentor challenge. From there I learned, all the things I needed such as how to use global reset before starting a project from Josh Comeau - [https://www.joshwcomeau.com/css/custom-css-reset/].

I also learned during the css styling to store re-useable components that are use through out the code in a root pseudo-class as this will make for cleaner code. This can also be applied when styling global elements and targeting there general styling first before adding any specific properties and values.  

So after learning from how Kevin, tackled the challenged I did my best to combine what I learned from him with my previous code, to make my component work.

```css
/* Sample of the global reset from Josh Comeau */

*, *::before, *::after{
    box-sizing: border-box;
    
}

*{
    margin: 0;
}

img,
picture,
svg{
    display: block;
    max-width: 100%;
}

/* A better structured  CSS pseudo-class */
:root{
    /* Colours */
    --Primary-color: hsl(158, 36%, 37%);
    --Background-color: hsl(30, 38%, 92%);
    /* Neutral */
    --Very-dark-blue: hsl(212, 21%, 14%);
    --Dark-grayish-blue: hsl(228, 12%, 48%);
    --White: hsl(0, 0%, 100%) ;

    /* Fonts */
    --ff-accent: 'Fraunces', sans-serif;
    --ff-base: 'Montserrat', sans-serif;
    /* Weights */
    --fw-reg: 500;
    --fw-bold: 700
}
```
### Continued development

#### Responsive Layout
- After completing the preview card I run into trouble, with how the card was responding with the different devices.
- This will need to be fixed as is not fulfilling the requirement set on this challenge.  
- A good resource I have found is Kevin Powell(https://www.youtube.com/watch?v=B2WL6KkqhLQ), guide on building this project as he dwells in how this issue can be fixed but he also cover many tools and tips on how to setup structure and styling guides for this project. 
  
  

## Author
- Frontend Mentor - [@timothy-joseph-collado](https://www.frontendmentor.io/profile/timothy-joseph-collado)
