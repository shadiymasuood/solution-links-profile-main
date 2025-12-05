
# solution-links-profile-main
 This repository contains my solution for the **Social Links Profile** challenge from Frontend Mentor. The project is built using **HTML &amp; CSS only** and aims to match the provided design (mobile &amp; desktop) as closely as possible.

# Social Links Profile — Frontend Mentor Solution

**Project:** Social Links Profile (Frontend Mentor)

**Author:** Shadiy Masuood

---

## Overview

This repository contains my solution for the **Social Links Profile** challenge from Frontend Mentor. The project is built using **HTML & CSS only** and aims to match the provided design (mobile & desktop) as closely as possible.


## Table of contents

* [Overview](#overview)
* [Built with](#built-with)
* [Getting started](#getting-started)
* [How to run](#how-to-run)
* [Features](#features)
* [What I changed / Suggestions applied](#what-i-changed--suggestions-applied)
* [Known issues & To do](#known-issues--to-do)
* [Author](#author)
* [License](#license)

---

## Built with

* HTML5
* CSS3 (Flexbox & Grid)
* Google Fonts (Outfit / Inter / Figtree)

---

## Getting started

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

2. Open the project folder in your preferred code editor.

---

## How to run

* Open `index.html` in your browser.
* (Optional) Use a live-server extension (e.g. VS Code Live Server) for hot reload while developing.

---

## Features

* Responsive layout for mobile and desktop.
* Hover and focus states for interactive elements (buttons/links).
* Semantic HTML structure (`main`, `article`, `header`, `ul`).


---

## What I changed / Suggestions applied

During the review and while preparing this README I applied (or recommend) the following changes to improve accessibility, semantics and responsiveness:



1. **Add meaningful alt text** to the avatar image:

```html
<img class="imag-header" src="assets/images/avatar-jessica.jpeg" alt="Jessica Randall — avatar">
```

3. **Fix meta typos** in `index.html`: change `monter` → `mentor` in the `description` and `keywords` meta tags.
```

4. **Font import**: the Google Fonts query in the original code included a compact range syntax — use a stable import that lists only the weights you need. Example for `Outfit` + `Inter`:

```html
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;700&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
```

8. **Use CSS variables consistently** (use `--grey-700` naming style or keep your current scheme consistent) and avoid hard-coded HSL colors sprinkled across the stylesheet.

9. **Accessibility:** ensure that the link text is descriptive (e.g. `Visit Jessica's GitHub` for screen readers) or use `aria-label` on icons/links.

10. **Small HTML cleanup:** remove extra spaces between tag text content (e.g. `<h2>Jessica Randall</h2>`) and add `lang="en"` on the `<html>` tag (already present).

---

## Known issues & To do

* Add proper live demo link.
* Consider adding small animations and subtle shadows to better match the design.
* Add unit tests / visual regression checks if you want long-term maintenance.

---

## Author

Shadiy Masuood

* GitHub: [https://github.com/shadiymasuood](https://github.com/shadiymasuood)
* Frontend Mentor: [https://www.frontendmentor.io/profile/shadiymasuood](https://www.frontendmentor.io/profile/shadiymasuood)

---

## License

This project is licensed under the MIT License — see the `LICENSE` file for details.

---

## ترجمة سريعة (عربي)

هذا المشروع هو حل تحدّي "Social Links Profile" على Frontend Mentor. مبني بـ HTML و CSS فقط. README هذا يتضمن تعليمات التشغيل، التحسينات المقترحة، ونِقاط الوصول السريعة.
