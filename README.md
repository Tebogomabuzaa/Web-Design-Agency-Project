````markdown
# Creative Design Agency Landing Page

A clean, responsive landing page website for a creative design agency. This project demonstrates a layout containing a hero section, feature cards, and a footer using HTML5 and CSS3.

## 📖 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup & Usage](#setup--usage)

## 🧐 Overview
This project is a static webpage designed to showcase agency services. It utilizes a mixed layout approach, using Flexbox for the main document structure and floats for the desktop card layout. It includes a media query to ensure the design adapts to mobile devices.

## ✨ Features
* **Responsive Design:** The layout adjusts for screens smaller than 680px, stacking cards vertically and adjusting font sizes.
* **Google Fonts Integration:** Uses the "Poppins" font family for modern typography.
* **Card-Based Layout:** Features "Beauty" and "Construction" service sections with image integration.
* **Sticky Footer:** The main content area expands to push the footer to the bottom of the viewport.

## 🛠 Technologies Used
* **HTML5:** Semantic structure (using `<header>`, `<footer>`, `<div class="card">`).
* **CSS3:** Custom styling including:
    * Flexbox (`display: flex`) for body alignment.
    * Float (`float: left/right`) for desktop column layout.
    * Media Queries for mobile responsiveness.

## 📂 Project Structure
To ensure the code runs correctly, your folder structure should look like this based on the file paths in the code:

```text
/project-root
│
├── index.html          # Main HTML structure
├── style.css           # Stylesheet
└── assets/
    └── images/         # Image directory
        ├── logo.png
        ├── beautiful.jpg
        └── construction.jpg
````

## 🚀 Setup & Usage

1.  **Download the files:** Ensure `index.html` and `style.css` are in the same root directory.
2.  **Add Images:** Create an `assets/images/` folder and add the required images (`logo.png`, `beautiful.jpg`, `construction.jpg`) to ensure the `<img>` tags render correctly.
3.  **Run:** Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).

## 🎨 Customization

You can easily change the color scheme in `style.css`:

  * **Background Color:** Modify `background-color: #faf9f6;` in the `body` selector.
  * **Accent Color:** Modify the `.middle-h1` class color (currently `rgb(25, 25, 112)`).

```
