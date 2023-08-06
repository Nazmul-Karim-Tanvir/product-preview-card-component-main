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

- Solution URL: [Github](https://github.com/Nazmul-Karim-Tanvir/product-preview-card-component-main)
- Live Site URL: [](https://your-live-site-url.com)

## My process

### Built with

- HTML5 
- CSS



### What I learned

In this project, I developed a website that features a shopping product card using HTML5 and CSS. I did not use any framework, but instead relied on my own knowledge and creativity to design and implement the layout, style, and functionality of the website. I learned how to center a component in the website using the flexbox model, how to use semantic variable naming system using root, and how to use images properly in the website and make them responsive. This project helped me improve my web development skills and gain more confidence in creating attractive and user-friendly websites.



 - Some HTML code I'm proud of    


```html
      <picture class="product__img">
        <source srcset="images/image-product-desktop.jpg" media="(min-width:600px)">
        <img src="images/image-product-mobile.jpg" alt=" A floral, solar and voluptuous interpretation composed by Olivier Polge,
        Perfumer-Creator for the House of CHANEL.">
      </picture>
```
**In this html section , The `picture` tag is used to specify multiple sources for an image, allowing the browser to choose the most appropriate source based on the device's screen size and resolution. The `source` tag specifies the image source for desktop devices with a minimum width of 600px, while the `img` tag specifies the image source for mobile devices. The `alt` attribute provides a description of the image. This code allows for responsive design and improved user experience.**
```css
    @media (min-width:600px) {
      .product{
        --content-padding: 2rem;
        grid-template-columns: 1fr 1fr;
      } 
    }
```
**This css part is used for dividing the content into two part when device become larger then 600px**

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
``` css
    .flex-group{
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
      align-items: center;

    }

    .visually-hidden:not(:focus):not(:active) {
      clip: rect(0 0 0 0);
      clip-path: inset(50%);
      height: 1px;
      overflow: hidden;
      position: absolute;
      white-space: nowrap;
      width: 1px;
    }
```

**In this section, I added the product price based on the requirement and used CSS to display the new price and the old price in the same line. I also used the visually-hidden class to hide the span element that contains the text "New" and "Old". This way, the screen reader will be able to read the document and inform the blind users which price is new and which one is old, but visually, the users will only see the prices. This technique improves the accessibility and usability of the website for people with visual impairments.**


### Continued development

The shopping card displays the product image, name, category, price, and a button to add the product to the cart. The card also uses some CSS techniques to enhance the appearance and functionality of the card, such as border-radius, box-shadow, flexbox, and hover effects. The card is responsive and adapts to different screen sizes and devices.That is why this project can use as reference for a shopping website. 


### Useful resources

- [Kevin Powell](https://www.youtube.com/watch?v=B2WL6KkqhLQ) - His youtube tutorial helped me a lot to complete this project and learn new topics.


## Author


- LinkedIn - [@nazmul-karim-tanvir-795563159](https://www.linkedin.com/feed/)
- GitHub - [Nazmul-Karim-Tanvir ](https://github.com/Nazmul-Karim-Tanvir)
- Frontend Mentor - [@Nazmul-Karim-Tanvir](https://www.frontendmentor.io/profile/Nazmul-Karim-Tanvir)


## Acknowledgments

- [Kevin Powell](https://www.youtube.com/watch?v=B2WL6KkqhLQ) - His youtube tutorial helped me a lot to complete this project and learn new topics.
- [Bohubrihi](https://bohubrihi.com/) - It helped me a lot learning the fundamentals of HTML and CSS


