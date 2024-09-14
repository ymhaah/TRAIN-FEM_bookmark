# Frontend Mentor - Bookmark landing page solution

> Start at: May 25, 2022

## Project Description
This is a solution to the [Bookmark landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bookmark-landing-page-5d0b588a9edda32581d29158). FrontendMentor is a platform where developers can improve their front-end skills by building real projects and receiving feedback from the community.

### the project
Your Simple Bookmark Solution! Effortlessly organize your favorite websites with QuickMarks, offering a streamlined and user-friendly bookmark management experience. Swiftly categorize and retrieve your bookmarks, ensuring easy access to your go-to sites. Simplify your online life with QuickMarks – the essential tool for efficient web navigation.


### Screenshot
![hero of the page](https://github.com/ymhaah/TRAIN-FEM_bookmark/assets/77534098/24e85215-1ccc-4392-8e89-e767364f1d00)


### Links

-   [Live Site URL](https://ymhaah.github.io/TRAIN-FEM_bookmark/)
-   [frontEndMentor Solution URL](https://www.frontendmentor.io/solutions/bookmark-LI23Ip8fpS)


### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow

### What I learned

```html
<form action="">
	<input
		type="email"
		placeholder="Enter your Email"
		required
		minlength="5"
		maxlength="100"
		inputFiled
	/>
	<button type="submit" button class="redButton">Contact Us</button>
</form>
```

```css
:root {
	--big-font: calc(2.8rem + 1.5vw);
	--medium-font: calc(2rem + 1.3vw);
	--small-font: calc(0.8rem + 1.2vw);
}
```

```scss
@mixin flex($direction, $justify, $align) {
	display: flex;

	// for flex direction
	@if $direction == "r" {
		flex-direction: row;
	} @else if $direction == "rr" {
		flex-direction: row-reverse;
	} @else if $direction == "c" {
		flex-direction: column;
	} @else if $direction == "cr" {
		flex-direction: column-reverse;
	} @else {
	}

	// for justify
	@if $justify == "c" {
		justify-content: center;
	} @else if $justify == "fs" {
		justify-content: flex-start;
	} @else if $justify == "fe" {
		justify-content: flex-end;
	} @else if $justify == "sa" {
		justify-content: space-around;
	} @else if $justify == "sb" {
		justify-content: space-between;
	} @else if $justify == "se" {
		justify-content: space-evenly;
	} @else {
	}

	// for align
	@if $align == "c" {
		align-items: center;
	} @else if $align == "fs" {
		align-items: flex-start;
	} @else if $align == "fe" {
		align-items: flex-end;
	} @else {
	}
}
```

```js
let lines = [...document.querySelectorAll(".line")];
let content = [...document.querySelectorAll(".artc")];
let special = "";

lines.forEach(function (ele) {
	ele.onclick = function () {
		special = ele;
		for (let i = 0; i < lines.length; i++) {
			if (lines[i] == special) {
				lines[i].classList.add("act");
				content[i].classList.add("vis");
			} else if (lines[i] != special) {
				lines[i].classList.remove("act");
				content[i].classList.remove("vis");
			}
		}
	};
});
```

### Continued development

-   html seo
-   scss mixin
-   js general skills

### Useful resources

Check out my latest previous articles:

-   [how to make an Indestructible button?](https://dev.to/ymhaah/how-to-make-an-indestructible-button-3f2h)
-   [Top 5 Icon websites for devs and designers!!!](https://dev.to/ymhaah/top-5-icon-websites-for-devs-and-designers-53mh)
-   [30-Day React Learning Journey!](https://dev.to/ymhaah/series/20473)

## Author
-   professional links:
    - [Twitter / X](https://twitter.com/hafanwy)
    - [LinkedIn](https://www.linkedin.com/in/youssef-hafnawy/)
    - [Newsletter](https://hefnawystudio.substack.com/?utm_source=navbar&utm_medium=web&r=31jf6o)
-   Hire me:
    -   [UpWork](https://www.upwork.com/freelancers/~01acd8e5370e5646aa)
-   Blog:
    -   [Medium](https://medium.com/@ymhaah250)
    -   [Dev.to](https://dev.to/ymhaah)

### Free Services
- [Free Website performance Optimization](https://tally.so/r/nPzKaB)   
- [Free Website Accessibility Optimization](https://tally.so/r/3lr2bp) 
