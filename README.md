Recipe Card Page (Task 11)

A single recipe card page showing an image, an ingredients list, and numbered preparation steps. Built as part of my Web Development internship at Veda Technology (Day 11 of 45, Level 1).

Objective

Practice semantic HTML structure and CSS card styling.

Features
Styled recipe card with image, ingredients, and steps
Semantic HTML: <main>, <article>, <header>, <section>, <figure> and <figcaption>
Unordered list (<ul>) for ingredients and ordered list (<ol>) for steps
Card container with consistent spacing, border, border-radius, and shadow
Responsive layout: sections stack on mobile and sit side by side on desktop (media query at 768px)
Tools Used
HTML5
CSS3
Project Structure
Recipe-Card-Page-Task-11/
├── index.html
├── style.css
├── pancakes.svg
└── README.md
How to Run
Download or clone this repository.
Open index.html in any web browser.
Screenshots

Show Image Show Image

What I Learned
Why an ordered list is better than a paragraph for steps: the order matters, and <ol> numbers the steps automatically and makes the sequence clear to browsers and screen readers.
The CSS box model: every element is made of content, padding, border, and margin. Using box-sizing: border-box makes the width include padding and border.
Keeping a card layout consistent across screen sizes: max-width with width: 100%, flexible images (width: 100%; height: auto), a grid layout, and media queries.
Author

Anna Makgabo Thantsha# recipe-card-page
