# Frontend Mentor - Blog Preview Card Solution

This is my solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot of Blog Preview Card](preview.jpg)

This is a screenshot of my solution to the Blog Preview Card challenge.

### Links

- Solution URL: [Solution on GitHub](https://github.com/V0000DY/blog-preview-card)
- Live Site URL: [Live Site](https://v0000dy.github.io/blog-preview-card/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I Learned

This project provided valuable experience in the following areas:

1.  **Semantic HTML**:

    - Utilized semantic elements such as `<main>`, `<article>`, `<time>`, and `<span>` to improve the structure and accessibility of the HTML.

    ```html
    <body>
      <main>
        <article class="card">
          <div class="card__content">
            <div class="card__info"></div>
          </div>
        </article>
      </main>
    </body>
    ```

2.  **Mobile-First Workflow**:

    - Practiced developing the layout starting with mobile devices and then scaling up for larger screens using media queries.

3.  **Improved `alt` Text**:

    - Learned the importance of descriptive `alt` text for accessibility and SEO:

    ```html
    <img
      src="assets/images/illustration-article.svg"
      alt="Illustration of article"
      class="card__image"
    />
    ```

4.  **CSS Refactoring**:
    - Refactored CSS to reduce redundancy and improve maintainability.
    - Applied styles directly to HTML elements instead of using unnecessary classes.

### Continued Development

In future projects, I aim to:

- Enhance my understanding of CSS Grid for more complex layouts.
- Focus on creating more accessible web components.
- Practice more advanced CSS techniques like animations and transitions.

### Useful Resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - Comprehensive documentation for HTML, CSS, and JavaScript.
- [CSS-Tricks](https://css-tricks.com/) - Great resource for CSS tips, tricks, and techniques.

## Author

- **Vitaly Rubtsov**
- Frontend Mentor: [@V0000DY](https://www.frontendmentor.io/profile/V0000DY)

## Acknowledgments

Special thanks to the Frontend Mentor community for providing the challenge and the resources to help improve my coding skills.
