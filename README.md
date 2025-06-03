# CSS Basics – ALX Frontend Project - alx_html_css

This project introduces basic concepts of **CSS (Cascading Style Sheets)**. It builds upon the HTML structure from the previous project [[`html_basic`](https://github.com/ArchieK9/My_First_Portfolio)] and applies styling to improve the appearance of the web pages.

---

## Tasks Completed

### ✅ 1. Create a New Directory

- Created a new directory named `css_basic` inside the `alx_html_css` repository.

### ✅ 2. Copy Existing HTML Files

- Copied `index.html` and `tweets.html` from the `html_basic` directory into the newly created `css_basic` directory.

### ✅ 3. Create CSS Files

- Created two CSS files:
  - `styles.css` (empty file for custom styles)
  - `base.css` (contains base CSS rules for general styling)

### ✅ 4. Link CSS Files in HTML

- Added the following lines inside the `<head>` tag of both `index.html` and `tweets.html`:

```html
<link href="base.css" rel="stylesheet">
<link href="styles.css" rel="stylesheet">


# CSS Flexbox Layout – ALX Frontend Project

This part of the project focuses on using **CSS Flexbox** to organize HTML page structure effectively. It enhances the visual layout of the webpage by arranging content using flexible containers and directional flows.

---

## ✅ Task Overview

The following HTML structure was targeted for styling:

- `<body>` is the outermost container which holds all content, including:
  - `<header>`
  - `<main>` (which itself contains `<article>` and `<aside>`)
  - `<footer>`

---

# CSS Basic Layout and Styling Project

This project is part of the **ALX Frontend** curriculum. The goal is to apply fundamental CSS concepts, including Flexbox layout and basic styling.

---

## ✅ Tasks Completed

### 1. Layout Structure Using Flexbox

- Used `<body>` and `<main>` as Flexbox containers.
- Applied the following rules in `styles.css`:
  - `display: flex` on `<body>` and `<main>`.
  - `flex-direction: column` on `<body>` to stack `<header>`, `<main>`, and `<footer>`.
  - `flex-direction: row` on `<main>` to align `<article>` and `<aside>` side-by-side.
  - `flex: auto` on `<main>` to allow it to grow and shrink as needed.
  - `flex: 2` on `<article>` and `flex: 1` on `<aside>` to control width ratio (2:1).
  - `overflow-y: auto` on both `<article>` and `<aside>` to enable scrolling.

---

### 2. Styling and Customization

- Created and edited `styles.css` to include custom non-positioning styles such as:
  - Backgrounds
  - Colors
  - Borders
- Applied custom styles specifically within the `<article>` tag as permitted.

---

### 3. Logo Addition

- Added a Unicode character as a **logo** to the top-left of the page.
  - Inserted it as the **first list item** in the `<header>`.
  - Used a character from [Unicode Symbol Table](https://symbl.cc/en/unicode-table/).
  - Applied the `class="logo"` to style it larger and distinct.

---

## 🚫 Restrictions Followed

- Did **not** change the Flexbox layout logic.
- Did **not** use absolute or fixed positioning outside of the `<article>`.
- Focused only on customizing styles within the allowed scope.

---
