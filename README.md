# Frontend Mentor - Testimonials grid section solution
![Screenshot](https://user-images.githubusercontent.com/99641829/188718713-610168ad-1158-4717-b8eb-ee3f85005de1.png)

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [https://github.com/Peteonthebeat/Testimonials-Grid-Section-Main]
- Live Site URL: [https://peteonthebeat.github.io/Testimonials-Grid-Section-Main/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I am glad that I got to exercise my grid skills. I also learned about ccs grid generators that can help in various ways; one is to envision more clearly what the grid should look like. I am also getting increasingly accustomed to SCSS, and its miraculous nesting function, which, although somewhat frustrating at first, keeps my code much more concise and easy to read, also the 'position,' and 'z-index' properties.

````html
<div class="card daniel">
  <img class="quotation" src="/images/bg-pattern-quotation.svg" alt="" />
  <div class="card-content">
    <div class="name-and-verified">
      <img class="photo" src="/images/image-daniel.jpg" alt="daniel" />

      <div class="verified-graduate">
        <span>Daniel Clifford</span>
        <h4>Verified Graduate</h4>
      </div>
    </div>
    <h3>
      I received a job offer mid-course, and the subjects I learned were
      current, if not more so, in the company I joined. I honestly feel I got
      every penny’s worth.
    </h3>
    <p>
      “ I was an EMT for many years before I joined the bootcamp. I’ve been
      looking to make a transition and have heard some people who had an amazing
      experience here. I signed up for the free intro course and found it
      incredibly fun! I enrolled shortly thereafter. The next 12 weeks was the
      best - and most grueling - time of my life. Since completing the course,
      I’ve successfully switched careers, working as a Software Engineer at a VR
      startup. ”
    </p>
  </div>
</div>

```css @media (min-width: 1312px) { body { height: 100vh; padding: 8em; }
.container { display: grid; grid-template-columns: repeat(4, 1fr);
grid-template-rows: repeat(4, 1fr); grid-column-gap: 0px; grid-row-gap: 0px;
gap: 2em; .card { margin: 0; } .daniel { grid-area: 1 / 1 / 3 / 3; } .jonathan {
grid-area: 1 / 3 / 3 / 4; } .jeanette { grid-area: 3 / 1 / 5 / 2; } .patrick {
grid-area: 3 / 2 / 5 / 4; } .kira { grid-area: 1 / 4 / 5 / 5; } } }
````

### Continued development

Delving deeper and deeper into CSS FlexBox, Grid, and SCSS and learning through real applications and challenges like those on the FrontEnd Mentor Website while also taking advantage of FCC's JS curriculum.

### Useful resources

- [https://cssgrid-generator.netlify.app/](https://www.example.com) - This helped me to envision the grid columns and rows a lot more vividly.
- [https://getcssscan.com/css-box-shadow-examples] - A bunch of incredibly useful box-shadow templates.

## Author

- Website - [peteonthebeat.com](https://www.your-site.com)
- Frontend Mentor - [@peteonthebeat](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@peteonthebeat1](https://www.twitter.com/yourusername)

## Acknowledgments

I did this entirely on my own, so shout-outs to myself. Also, shout out to the Frontend Mentor website; it really helps me on my journey of becoming a frontend developer.
