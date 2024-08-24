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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./images/Frontend%20Mentor%20_%20QR%20code%20component.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

1.  First I added the necessary elements along with the images to form a meaningfull markup.
1.  Then in CSS,
    1.  I added the local styles and variables from the Figma Design files
    1.  Neutralized the browser default styles such as margin and padding and borderbox
    1.  Next, addedd necessary styles for each element.

### Built with

    HTML and CSS

### What I learned

The QR-Code image is wrapped inside a div called qr-code-container.Firstly, I was doing to tightly wrap the div along the image so that there is no space left and there is margin 16px between the image div and card div.

Although, left and right margins were applied , top margin was being calculated from the viewport(wierd)

So, I made the container div's width as the size of card div and added margin to image , margin =16px

#### How to center a div

```css
.parent {
  display: flex;
  align-items: center;
  justify-content: center;
  /* This will only make 'child' horizontally aligned till now */
  min-height: 100vh;
  /* After this 'child' will be vertically aligned as well
  credits - @bradtraversy 20vanilla JS Course */
}
```

### Continued development

I need more understanding of :

1.  usual design choices(e.g- why image is wrapped inside a div?)
1.  inhertable and non-inheritable properties
1.  how to center a div (both horizontally and vertially)
1.  how to make responsiv,adaptive and fluid development
1.  how make an efficient and swift workflow
1.  better css class naming conventions with BEM

## Author

- Frontend Mentor - [@krkfpo](https://www.frontendmentor.io/profile/krkfpo)

## Acknowledgments

Thanks to Frontendmentor for such lovely challenges.
