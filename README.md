# Study Group & Peer Tutoring Hub

For students who want to organize study sessions, find peer tutors, and showcase their academic projects,
this is a multi-page website built with HTML, CSS, and vanilla JavaScript.

## How to Run

Open `index.html` directly in any web browser, or view the live version on GitHub Pages:
https://plesa14anastasia.github.io/StudyHub-Project/

## Requirements Map

- Portfolio / CV Page: created `cv.html`, linked in the navigation bar across all pages, and styled with `style.css` and `cv.css` to match the existing site
- Accessible Form: wrapped in `<fieldset>` and `<legend>` with 6 different input types (`text`, `url`, `select`, `date`, `file`, `textarea`), explicit `<label>` elements, and `aria-describedby` linked to error messages
- JavaScript Validation: implemented in `main.js` to prevent submission on errors (`e.preventDefault()`), display clear accessible error messages next to each field, and clear errors on form reset
- Projects Table: dynamically inserts validated project entries into an accessible table with `<caption>`, `<th scope="col">`, and a `.table-wrapper` (`overflow-x: auto`) for smaller screens
- Responsive Layout: works on mobile, tablet, and desktop layouts with responsive grids, full-width mobile forms, and scrollable tables
- Visual Enhancements & Originality: persistent Dark Mode using `localStorage`, scroll-reveal animations with `IntersectionObserver`, a pure CSS logo, and an interactive chatbot (`chatbot.html`)
- Accessibility & Performance: includes a skip-to-main-content link, semantic heading hierarchy, keyboard navigation with visible focus states, `loading="lazy"` on images, and consolidated scripts in `main.js`
- Validation: HTML and CSS checked with the W3C Nu Html Checker with no errors or warnings, and published on GitHub Pages
