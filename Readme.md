# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![Frontend Mentor _ Recipe page - Google Chrome 13-03-2024 20_19_22](https://github.com/babybhavani/recepiePage/assets/152834101/54448a32-f2e6-4209-b7b0-0c9c853f25a3)

### Links

- Solution URL: [https://github.com/babybhavani/recepiePage.git](https://github.com/babybhavani/recepiePage.git)
- Live Site URL: [https://babybhavani.github.io/recepiePage/](https://babybhavani.github.io/recepiePage/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles
- 
### What I learned

- Alignment of elements
- Different font families
- Flex layouts
- Flex alignments

```html
  <section class="container">
      <section class="card">
        <section class="dish-img-container">
          <img src="assets\images\image-omelette.jpeg" alt="omelette" class="dish-img">
        </section>
        <section class="bottom-section">
          <h1 class="card-heading"> Simple Omelette Recipe
          </h1>
          <p class="description"> An easy and quick dish, perfect for any meal. This classic omelette combines beaten
            eggs
            cooked
            to perfection, optionally filled with your choice of cheese, vegetables, or meats.
          </p>
          <section class="section colored">
            <h1 class="section-heading">Preperation Time</h1>
            <ul class="section-list">
              <li class="section-list-item"> <b>Total:</b> Approximately 10 minutes</li>
              <li class="section-list-item"> <b>Preparation:</b> 5 minutes </li>
              <li class="section-list-item"> <b> Cooking: </b> 5 minutes </li>
            </ul>
          </section>
          <section>
            <h1 class="section-heading">Instructions</h1>
            <ol class="ordered-list">
              <li class="section-list-item">
                <b>Beat the eggs: </b>In a bowl, beat the eggs with a pinch of salt and pepper until they are well
                mixed.
                You can add a tablespoon of water or milk for a fluffier texture.
              </li>
              <li class="section-list-item">
                <b>Heat the pan: </b>Place a non-stick frying pan over medium heat and add butter or oil.
              </li>
              <li class="section-list-item">
                <b>Cook the omelette: </b> Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to
                ensure
                the eggs evenly coat the surface.
              </li>

              <li class="section-list-item">
                <b>Add fillings (optional): </b>When the eggs begin to set at the edges but are still slightly runny in
                the
                middle, sprinkle your chosen fillings over one half of the omelette.
              </li>
              <li class="section-list-item">
                <b>Enjoy: </b> Serve hot, with additional salt and pepper if needed..
              </li>
          </section>
          <hr>
          <section>
            <h1 class="section-heading">Nutrition</h1>
            <p class="about">The table below shows nutritional values per serving without the additional fillings.</p>
            <table>
              <tr>
                <td>Calories</td>
                <td>277 kcal</td>
              </tr>
              <tr>
                <td>Carbs</td>
                <td>0 g</td>
              </tr>
              <tr>
                <td>Protein</td>
                <td>20 g</td>
              </tr>
              <tr>
                <td>Fat</td>
                <td>22 g</td>
              </tr>
            </table>

          </section>

        </section>
      </section>

    </section>
```
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;

}

.card {
    background-color: hsl(0, 0%, 100%);
    max-width: 700px;
    min-width: 200px;
    padding: 40px;
    margin-top: 40px;
    margin-bottom: 40px;
}

```

### Continued development

I want to develop the page boyyom section.

## Author

- Frontend Mentor - [@babybhavani](https://www.frontendmentor.io/profile/babybhavani)
