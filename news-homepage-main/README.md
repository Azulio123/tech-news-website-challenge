## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Toggle the mobile menu (requires some JavaScript)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

1. Marking up everything with the appropriate tags
2. Working down by sections 
    a. Some sections needed to be pieced together, so this part of the process was ongoing and sometimes frustrating!
3. Implementing rows and columns using bootstrap (ongoing fiddling)
4. Applying the most superficial styles (fonts, colors, etc.)
5. Fine-tuning aspects
6. Continually fiddling to fit the eye-balled parameters of the project
7. Troubleshooting the offcanvas drawer navbar menu (I DID NOT have to use javascript)

### Built with

- Bootstrap
- HTML
- CSS
- Mobile First in practice (Although, sometimes I focused more on the desktop design despite knowing better)


### What I learned

```html
<div class="proud-of-html">
<h1>Some HTML code I'm proud of</h1>
<div class="container-fluid">
<nav class="navbar navbar-expand-lg navbar-light">
      <a class="navbar-brand" href="">W.</a> 
      <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
      </button>
      <div class="offcanvas offcanvas-right" tabindex="-1" id="offcanvasRight" aria-labelledby="offcanvasRightLabel">
        <div class="offcanvas-header">
          <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
        </div>

      <ul id="drawer-list" class="navbar-nav ms-auto">
         
        <li class="nav-item">
            <a id="drawer-link" class="nav-link" href="#home">Home</a>
        </li>
        <li class="nav-item">
            <a id="drawer-link" class="nav-link" href="#new">New</a>
        </li>
        <li class="nav-item">
            <a id="drawer-link" class="nav-link" href="#home">Popular</a>
        </li>
        <li class="nav-item">
          <a id="drawer-link" class="nav-link" href="#trending">Trending</a>
      </li>
      <li class="nav-item">
        <a id="drawer-link" class="nav-link" href="#categories">Categories</a>
    </li>
    </ul>
      </div>
  </nav>
</div>
```html
.proud-of-html {
  color: lightgray;
```css
.proud-of-this-css {
  color: papayawhip;
}


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.



### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
