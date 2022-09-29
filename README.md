# React-ott-app/ React-movies

This is a solution to the ott based movie platform.

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

- View the optimal layout for each of the website's pages depending on their device's screen size
- See hover states for all interactive elements on the page
- Users could get infinite right scrolling as in Netflix
- Hovering effect for each movie poster
- Could add favirote in ther local storage

### Links

- Solution URL: [https://github.com/Soaphub/React-ott-app]
- Live Site URL: [https://soaphub.github.io/React-ott-app/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library

### What I learned

Learned to clone images for infinite scrolling effect.

```js
if(intialposters===20 && cssImagePerSreen>=5) {
			const forwardPoster= [...document.querySelectorAll(".movie-posters"+props.id)];
			if(section === (totalSection-1)){
				forwardPoster.forEach(poster => {
					let clone =poster.cloneNode(true);
					movieLists.appendChild(clone);
				});
			}
		}
```

### Useful resources

- [https://www.youtube.com/c/TheNetNinja) - Learned  about React hooks.
- [https://www.youtube.com/c/ChrisBlakely] - Learned about saving data in local stoarage.
- [https://www.youtube.com/c/WebDevSimplified] - Learned about Netflix interface scrolling.

## Author

- Website - [Ambadi](https://soaphub.github.io/React-ott-app/)

## Acknowledgments

The udemdy coarse by Angela helped a lot in completing the project.
