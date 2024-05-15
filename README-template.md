# TIMzine: intégration du design

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Links

- Live Site URL: [TIMzine](https://arianebo.github.io/integration2_p2/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Animations CSS
- Mobile-first workflow

### What I learned

J'ai beaucoup appris comment travailler avec les grilles CSS puisqu'on ne les avait pas vraiment pratiquées avant.

Je suis fière de cet extrait de mes CSS car j'ai pensé à faire un flex à l'intérieur du flex pour les items de mon footer qui restaient ensemble lors de la redimension de la page.
```css
.footer__div {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding-bottom: 2rem;
    width: 70%;

    @media (min-width: 600px) {
        flex-direction: row;
        align-items: center;
        justify-content: center;
        padding-bottom: 0;
    }

    @media (min-width: 900px) {
        justify-content: space-around;
        padding-bottom: 0;
    }
}
```

### Continued development

Je voudrais continuer à améliorer mes connaissances avec les grilles CSS car je voudrais pouvoir les utiliser avec plus d'aisance.
