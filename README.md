# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
	- [Table of contents](#table-of-contents)
	- [Overview](#overview)
		- [The challenge](#the-challenge)
		- [Screenshot](#screenshot)
		- [Links](#links)
	- [My process](#my-process)
		- [Built with](#built-with)
		- [What I learned](#what-i-learned)
		- [Useful resources](#useful-resources)
	- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop View](https://github.com/BhandarkarPawan/product-preview-card-component/blob/master/results/Desktop.png?raw=true)
### Links

- Solution URL: [Github Repo](https://github.com/BhandarkarPawan/product-preview-card-component)
- Live Site URL: [Netlify App](https://app.netlify.com/sites/bhandarkarpawan-product-preview-card-component/settings/domain)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned
The most interesting challenge I faced in this project was actually deciding which HTML components to use. In the end, I decided to use a `<figure>` element along with `<figcaption>` as it seemed to make the most sense, based on the MDN description for this tag: 

> The `<figure>` HTML element represents self-contained content, potentially with an optional caption, which is specified using the `<figcaption>` element. The figure, its caption, and its contents are referenced as a single unit.

> The `<figcaption>` HTML element represents a caption or legend describing the rest of the contents of its parent `<figure>` element.


Given that in this product preview, we essential have the details "describing" the image on the left and the whole card is expected to be referenced as a single unit, it felt appropriate to use these elements. 

```
<figure class="card">
	<img class="preview" src="images/image-product-desktop.jpg" />
	<figcaption class="details">
		<h4 class="category">Perfume</h4>
		<h1 class="title">Gabrielle Essence Eau De Parfum</h1>
		<p class="description">
			A floral, solar and voluptuous interpretation composed by
			Olivier Polge, Perfumer-Creator for the House of CHANEL.
		</p>
		<div class="pricing">
			<div class="sale-price">$149.99</div>
			<div class="retail-price">$169.99</div>
		</div>
		<button class="add-btn">
			<img class="icon" src="images/icon-cart.svg" />
			Add to Cart
		</button>
	</figcaption>
</figure>
```

### Useful resources

- [CSS For Javascript Developers](https://courses.joshwcomeau.com/css-for-js) - This was my first project after completing the CSS for Javascript Developers course. The course is incredible and taught me everything I currently know about CSS. 
## Author

- LinkedIn - [P Pawan Bhandarkar](https://www.linkedin.com/in/pawan-bhandarkar-b18370137/)
- Frontend Mentor - [@BhandarkarPawan](https://www.frontendmentor.io/profile/BhandarkarPawan)
- Twitter - [@BhandarkarPawan](https://twitter.com/BhandarkarPawan)