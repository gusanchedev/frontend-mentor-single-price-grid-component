# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./desktop-peview.jpg)

### Links

- Solution URL: [@GitHub](https://github.com/gustavosanchezgalarza/frontend-mentor-single-price-grid-component)
- Live Site URL: [@Vercel live site URL here](https://frontend-mentor-single-price-grid-component-gusanchedev.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
 <link rel="stylesheet" href="./css/mobile.css" />
    <link
      rel="stylesheet"
      href="./css/tablet.css"
      media="screen and (min-width: 480px) and (max-width:1023px)"
    />
    <link
      rel="stylesheet"
      href="./css/desktop.css"
      media="screen and (min-width:1024px)"
    />
    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Karla:wght@400;700&display=swap"
      rel="stylesheet"
    />
```
```css
main {
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 0.7fr 1fr;
    ...
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Media Queries for Standard Devices](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)

## Author

- Website - [gusande.dev](https://www.gusanche.dev)
- Frontend Mentor - [@gustavosanchezgalarza](https://www.frontendmentor.io/profile/gustavosanchezgalarza)
- Twitter - [@gusanchedev](https://twitter.com/gusanchedev)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
