# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Recipe Page with CSS and HTML5](#the-challenge)
  - [Screenshot](#screenshot)
  - [None](#links)
- [My Process](#my-process)
  - [Built with CSS3 and HTML5](#built-with)
  - [Classes, organize, how to use divs and articles](#what-i-learned)
  - [CSS and HTML](#continued-development)
  - [Chat GPT and FreeCodeCamp](#useful-resources)
- [Luciano](#author)
- [None](#acknowledgments)

## Overview

  I already knew a few things of CSS and HTML but i've learned more things about how to use them correctly.
  
### Screenshot

![Screenshot of in full screen](./design/End%20of%20project%20full%20screen.png)
![Screenshot without full screen](./design/Final%20Project.png)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

  Started by organizing the HTML to get better focus, then started by stylizing with CSS, and finally added the image of the omellete.
  I've learned a few things while i was solving it.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

```html
<div class="nutrition">
       <h2>Nutrition</h2>

       <p>The table below shows nutritional values per serving without the additional fillings.</p>

        <article class='item'>
          <p class="rotulo">Calories</p><p class="valor">277kcal</p>
        </article>
        <hr>
        <article class="item">
          <p class="rotulo">Carbs</p><p class="valor">0g</p>
        </article>
        <hr>
        <article class="item">
          <p class="rotulo">Protein</p><p class="valor">20g</p>
        </article>
        <hr>
        <article class="item">
          <p class="rotulo">Fat</p><p class="valor">22g</p>
        </article>
      </div>
```
```css
.item {
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 10px;
  margin-top: 5px;
  margin-bottom: -10px;
  font-size: 16px;
  font-family: "Outfit", sans-serif;
  font-optical-sizing: auto;
  font-weight: 400, 600, 700;
  font-style: normal;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.
 
  Refine CSS: padding, size of texts, widths, heights and borders; 

  HTML: better organaize codes, better use of articles and divs, lists and ordened lists.

### Useful resources

- [Chat GPT](https://chat.openai.com/) - This helped me for CSS reason. I used to learn new things about CSS and organize HTML.
- [Free Code Camp](https://www.freecodecamp.org/) - This helped me for CSS again, to have some base on what i would do.


## Author

- Website - [none]()
- Frontend Mentor - [@CodeCraziness92](https://www.frontendmentor.io/profile/CodeCraziness92)
- Twitter - [none]()

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.