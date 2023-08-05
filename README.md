# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Challange screenshot](#Challange-screenshot)
  - [Solution links](#Solution-links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

###  Challange screenshot

ACTIVE STATUS ![](/design/active-states.jpg)

DESKTOP VIEW ![](/design/desktop-design.jpg)

MOBILE VIEW ![](/design/mobile-design.jpg)


### Solution links

- Solution URL: [Add solution URL here](https://github.com/Nazmul-Karim-Tanvir/product-preview-card-component-main#table-of-contents)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5 
- CSS



### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:


 - Some HTML code I'm proud of    


```html
<picture class="product__img">
        <source srcset="images/image-product-desktop.jpg" media="(min-width:600px)">
        <img src="images/image-product-mobile.jpg" alt=" A floral, solar and voluptuous interpretation composed by Olivier Polge,
        Perfumer-Creator for the House of CHANEL.">
      </picture>
```
**In this section , The `picture` tag is used to specify multiple sources for an image, allowing the browser to choose the most appropriate source based on the device's screen size and resolution. The `source` tag specifies the image source for desktop devices with a minimum width of 600px, while the `img` tag specifies the image source for mobile devices. The `alt` attribute provides a description of the image. This code allows for responsive design and improved user experience.**
<hr>

```html
<div class="flex-group">
          <p class="product__price">
            <span class="visually-hidden"> Current price:</span>
            $149.99
          </p>
          <p class="product__original-price">
            <span class="visually-hidden"> Old price:</span>
            <s>$169.99</s>
          </p>
        </div>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author


- LinkedIn - [@yourusername](https://www.twitter.com/yourusername)
- GitHub - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.


