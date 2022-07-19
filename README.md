# 4-FEP-X-Portfolio-Sidebar

![4° Front-End](https://user-images.githubusercontent.com/105513033/179640341-ade71a89-e9ed-4859-b140-aa828267d031.png)

<span>
  <img src="https://img.shields.io/badge/STATUS-FINISHED-success" alt="Status: Finished">
  <img src="https://img.shields.io/badge/RELEASE_DATA-JULY%202022-informational" alt="Release Data: July 2022">
  <img src="https://img.shields.io/badge/LICENCE-MIT-important" alt="Licence: MIT">
</span>

&nbsp;

This is a challenge given by <a href="https://github.com/HenriqueSSan/" target="_blank">HenriqueSSan</a> to test my knowledges in HTML + CSS.

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

&nbsp;

## Overview

### The challenge

The challenge main objectives are:

- Follow the design

#### 🖥️ Desktop
![Desktop Design](https://user-images.githubusercontent.com/105513033/179641380-d04907ca-4bb3-4032-919b-07f1b26cdeeb.png)

#### 📱 Mobile
![Mobile Design](https://user-images.githubusercontent.com/105513033/179641426-2cd5eb1a-c2ff-4187-bef9-50f1e3b7f280.png)


- Must use the recommended recommendations
```css
<!--Recommendations-->

<style>
/*Use this as defalt*/
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

/*===================================*/
.father{
  display:grid;
  grid-template-columns: 1fr auto;
}

@media screen and (max-width: 769px){
  .father{
    grid-template-columns: 1fr;  
  }
  .content{
    display:none;
  }
}

</style>

<body>
  <div class="father">
    <div class="sidebar">
    <div class="content">
  </div>
</body>
```
- Must use the ```display:grid``` property of css
- Must be responsive

Side-objectives follows:

- Have animations in the links

There is also exceptions:

- No need to use BEM, OOCSS, CUBE, SMACSS, etc architecture, but it would be a bonus
- It doesn't need to have animations, although it would be another bonus
- Using ```display:flex``` property is no problem, even though needs to have at least one ```display:grid``` property

&nbsp;

### Screenshot

#### 🖥️ Desktop
![4° F.E.P. - Desktop Screenshot](https://user-images.githubusercontent.com/105513033/179636183-827e4693-efe7-4ebd-aa56-6eea4f68e45c.png)

#### 📱 Mobile
![4° F.E.P. - Mobile Screenshot](https://user-images.githubusercontent.com/105513033/179636199-4108afa4-ab9e-4467-91c1-d22fdd389f98.png)

&nbsp;

### Links

- Solution URL: [Solution in Github](https://github.com/EliveltonSilvaCordeiro/4-FEP-X-Portfolio-Sidebar/)
- Live Site URL: [Live site by Vercel](https://4-fep-x-portfolio-sidebar.vercel.app/)

&nbsp;

## My process

### Built with

- Semantic HTML5 markup
- CSS Grid
- Mobile-first workflow

&nbsp;

### What I learned

The CSS pre-processor is not called Syntactically Awesome Style Sheets by nothing, with it I can not only import rules defined, while also I can use the ```@mixings```, with this rule I can significantly shorter the code.

```scss
@mixin griding {
    display: grid;
    justify-content: center;
    align-content: flex-start;
    text-align: center;
}
```

```scss
main__container {
    @include griding;
    background-color: var(--black);
    color: var(--baby-powder);
}
```
&nbsp;

### Continued development

My plans are:
- keep improving my knowledge about the **display** and **position** properties
- learn more about animations
- learn **JavaScript**

&nbsp;

### Useful resources

- [Learn CSS Grid in 20 Minutes](https://youtu.be/0-DY8J_skZ0) - This helped me for understanding the grid propriets being direct to the point.

&nbsp;

## Author
- Github - [EliveltonSilvaCoredeiro](https://github.com/EliveltonSilvaCordeiro/)
- Frontend Mentor - [@EliveltonSilvaCordeiro](https://www.frontendmentor.io/profile/EliveltonSilvaCordeiro)

&nbsp;

# Challenge given by HenriqueSSan  <a href="https://github.com/HenriqueSSan/" target="_blank">![GitHub-Mark-Light-32px](https://user-images.githubusercontent.com/105513033/179639051-38ef3b87-09b7-4cea-88c2-8e9dedf6e05c.png)
</a>
