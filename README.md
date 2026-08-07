
Readme · MD
# 📌 Tea Cozy Project
 
## 📖 1. Project Overview
 
This project is part of the Codecademy *Front-End Career Path*. Its aim was to recreate the homepage of a company called Tea Cozy with **HTML** and **CSS**. More specifically, I had to follow precise guidelines from a design spec sheet provided by the Codecademy platform and recreate as faithful a copy as possible of the homepage shown on that spec sheet.
 
The **Tea Cozy Project** was created to hone the following concepts:
- HTML properties and logical organization of the HTML file;
- Use of class properties to build and organize containers to allow for efficient use of Flexbox properties;
- CSS properties and logical organization of the CSS file;
- Flexbox containers linked between the HTML and CSS files to allow the correct application of Flexbox properties and organization;
- Flexbox properties coded and applied in the CSS file.

---
 
## 🔗 2. Live Demo & Repository
 
### 🌐 Live Demo (GitHub Pages)
 
**GitHub Page:** You can view the live version of this project on its dedicated 👉 [GitHub Page](https://nfavre82.github.io/tea_cozy_project).
 
### 📁 Repository
 
**Source Code:** You can consult the source code of this project on its dedicated 👉 [GitHub repository](https://github.com/nfavre82/tea_cozy_project).
 
---
 
## 🧠 3. What I Practiced
 
- Writing and organizing both **HTML** and **CSS** files logically for better structure and readability;
- Including class containers within the HTML file to link them to Flexbox display properties;
- Practicing and honing the following intermediate CSS concepts: Flexbox layouts and related properties, relative units;
- Preferring padding and Flexbox properties over extensive margins, allowing for more flexible layouts within the box model;
- Building and organizing Flexbox layouts throughout the project.

---
 
## 📚 4. What I Learned
 
- How to use more flexible and powerful CSS layouts: Flexbox displays and properties;
- How to apply more advanced styling to a CSS stylesheet;
- How to apply subtle Flexbox adjustments to render the visual style of the project as a
faithful recreation of the design specified on the Codecademy design spec sheet.

---
 
## 🧱 5. HTML Structure
 
- **Semantic skeleton:** the page is organized into a `header`, a `main` element containing three `section`s (Mission, Featured Tea, Locations), and a `footer`, keeping the document outline readable at a glance;
- **Anchor navigation:** the header menu links (`#mission`, `#featured-tea`, `#locations`) point to matching `id` attributes placed directly on the section headings, enabling in-page jump navigation;
- **Flexbox-ready containers:** each visual block (`header-container`, `menu-container`, `mission-container` / `banner-container`, `flexbox-grid-featured-teas`, `locations-container` / `flexbox-grid-locations`, `contact-container`) is wrapped in its own class specifically so it can be targeted independently in the CSS with `display: flex`;
- **Repeating card patterns:** the Featured Tea and Locations sections each reuse a consistent nested structure (an image/card wrapper containing a heading and supporting text) so the same CSS rule can style every card identically;
- **Heading hierarchy for visual rhythm:** `h2`, `h3`, and `h4` elements are used less for strict document semantics and more to establish consistent vertical spacing and font-weight contrast across sections.

---
 
## 🎨 6. CSS Styling
 
- **Global reset:** a universal `box-sizing: border-box` rule on `*`, `*::before`, and `*::after` ensures padding and borders don't distort the width calculations used throughout the Flexbox layouts;
- **Flexbox as the primary layout tool:** `display: flex` combined with `flex-flow: row wrap` or `column wrap` drives the header navigation, the mission banner centering, the featured-tea grid, the locations grid, and the footer stack — with `justify-content` and `align-items` handling centering instead of manual margins;
- **`calc()` for a responsive three-column grid:** the featured-tea cards use `flex: 0 0 calc(33.333% - 0.33em)` so three cards sit evenly per row while accounting for gaps between them;
- **Background imagery with controlled framing:** the Mission and Locations sections use `background-image` alongside `background-size: cover` and `background-position` to keep the artwork properly cropped and anchored within fixed-height containers;
- **Mixed units by purpose:** relative units (`em`) are used for spacing and gaps that should scale with typography, while fixed units (`px`) control image dimensions and container widths that need to stay pixel-precise;
- **Consistent theming through opacity:** a shared black-and-seashell color palette is unified with `opacity` adjustments on the body and select containers to create a soft, translucent visual layer over the background images.

---
 
## 🛠️ 7. Workflow & Tools
 
- **Editor:** Visual Studio Code
- **Browser:** Chrome DevTools
- **Terminal:** Windows Shell / Git Bash
- **Version Control:** Git & GitHub

---
 
## 👩‍💻 8. Author
 
**NF Web Development Studio**
© 2026