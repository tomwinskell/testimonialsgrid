# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![screenshot-desktop](https://raw.githubusercontent.com/tomwinskell/testimonialsgrid/refs/heads/main/screenshot-desktop.png)
![screenshot-sm-desktop](https://raw.githubusercontent.com/tomwinskell/testimonialsgrid/refs/heads/main/screenshot-sm-desktop.png)
![screenshot-tablet](https://raw.githubusercontent.com/tomwinskell/testimonialsgrid/refs/heads/main/screenshot-tablet.png)
![screenshot-mobile](https://raw.githubusercontent.com/tomwinskell/testimonialsgrid/refs/heads/main/screenshot-mobile.png)

### Links

- Solution URL: [https://github.com/tomwinskell/testimonialsgrid](https://github.com/tomwinskell/testimonialsgrid)
- Live Site URL: [https://tomwinskell.github.io/testimonialsgrid](https://tomwinskell.github.io/testimonialsgrid)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- BEM

### What I learned

- Read articles about BEM to name CSS classes. It makes a lot of sense to me. I felt a little lost when it came to naming conventions for CSS classes. I hadn't read or seen anything that made a lot of sense to me before. I'm not sure BEM is perfect and I'm sure I didn't do a perfect job. However, I'm going to keep working on it. I think the CSS classes I've used make a lot of sense and could be easily followed by another dev which feels like the ultimate aim.

To see how you can add code snippets, see below:

```html
          <div class="card__header">
            <div class="card__header__leftcol">
              <img
                class="card__image border--light-violet"
                src="./assets/images/image-daniel.jpg"
                alt="Daniel Clifford"
              />
            </div>

            <div class="card__header__rightcol">
              <h1 class="card__name">Daniel Clifford</h1>
              <p class="card__title">Verified Graduate</p>
            </div>
          </div>
```
```css
/* card__header structure */
.card__header
{
  display: flex;
  flex-direction: row;
}

.card__header__leftcol
{
  display: flex;
  flex-direction: column;
  align-content: center;
  justify-content: flex-start;
}

.card__header__rightcol
{
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  gap: .4rem;
}
```

### Continued development

- BEM
- CSS Grid
- [OOCSS](https://github.com/stubbornella/oocss/wiki)
- Bootstrap

### Useful resources

- [MindBEMding – getting your head ’round BEM syntax](https://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/)
- [About HTML semantics and front-end architecture](https://nicolasgallagher.com/about-html-semantics-front-end-architecture/)
- [BEM — is a methodology that helps you to create reusable components and code sharing in front‑end development](https://getbem.com/)
- [CSS Grid Layout Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
