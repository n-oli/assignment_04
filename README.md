# CSC 235 Bootstrap Components Assignment

This project is based on the [CSC235 sample](https://github.com/connorj4/CSC235-sample) and uses Bootstrap 5.3. I added two Bootstrap components to the sample lecture page.

## 1. Accordion

I used an Accordion to organize the lecture topics. A student can click a lecture title to show or hide its description. This keeps the page simple and prevents all the lecture information from taking up space at the same time.

## 2. Modal

I used a Modal to display additional course information. It allows the student to read the information without leaving the lecture page. The student can close the Modal and continue using the same page.

## JavaScript

The Accordion and Modal require the Bootstrap JavaScript bundle to open and close. I did not write custom JavaScript to control those components because Bootstrap handles their behavior through `data-bs-` attributes in the HTML.

The custom `scripts/main.js` file is only used to update the current time in the footer.

## Project Files

- `index.html` contains the page structure, detailed comments, and the two Bootstrap components.
- `styles/style.css` contains the small amount of custom styling used by the page.
- `scripts/main.js` updates the current time in the footer.

## How to View the Project

Open `index.html` in a web browser. An internet connection is required because Bootstrap is loaded from a CDN.
