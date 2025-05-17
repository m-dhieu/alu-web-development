# CSS Advanced Project

## Overview

This project builds upon the previous HTML Advanced project by focusing on adding **CSS styling** to the webpage. Your goal is to apply styles that match the provided Figma design, using only HTML, CSS, and JavaScript without external libraries or frameworks.

---

## Learning Objectives

By the end of this project, you will be able to:

- Understand what CSS is and how it styles HTML elements.
- Add styles to elements using selectors and classes.
- Explain what a CSS class is and how it differs from IDs and element selectors.
- Understand CSS specificity and how the browser determines which styles apply.
- Calculate CSS specificity values manually and understand the hierarchy of selectors.
- Understand the box model properties in CSS (margin, border, padding, content).
- Understand how browsers load webpages and apply CSS rules.
- Write clean, W3C-compliant CSS code that validates successfully.

---

## Project Requirements

- All files must end with a newline.
- A `README.md` file is mandatory at the root of the project folder.
- No external libraries or frameworks (e.g., Bootstrap, React, Vue) are allowed.
- The project must use only HTML, CSS, and JavaScript.
- Your CSS must be W3C-compliant and pass validation.
- You should copy the `index.html` file from the HTML Advanced project as the base.
- Follow the Figma design closely for styling details.
- If your computer lacks fonts used in the design, download **Source Sans Pro** and **Spin Cycle OT**.
- Round floating-point values from the design as needed for practicality.

---

## Important Notes on CSS Specificity

CSS specificity determines which style rules apply when multiple rules target the same element. It is calculated based on the types of selectors used:

| Selector Type                         | Specificity Value |
|-------------------------------------|-------------------|
| Inline styles (`style=""`)           | 1000              |
| ID selectors (`#id`)                 | 100               |
| Classes, attributes, pseudo-classes | 10                |
| Element selectors, pseudo-elements  | 1                 |

- Inline styles have the highest priority.
- ID selectors override class selectors.
- Classes override element selectors.
- When specificity is equal, the last declared rule wins.
- Avoid overusing `!important`; use specificity wisely.
- Doubling class selectors (e.g., `.button.button`) increases specificity.

---

## Resources

- [Learn to Code HTML & CSS (until “Creating Lists” included)](https://learn.shayhowe.com/html-css/)
- [MDN CSS Specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_cascade/Specificity)
- [CSS Specificity - W3Schools](https://www.w3schools.com/css/css_specificity.asp)
- [CSS Specificity Calculator](https://specificity.keegan.st)
- Fonts: [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro), [Spin Cycle OT](https://www.fonts.com/font/linotype/spin-cycle)

---

## How to Use This Project

1. Clone the repository.
2. Copy the `index.html` from the HTML Advanced project.
3. Add your CSS styles in the provided CSS files.
4. Follow the Figma design for colors, fonts, spacing, and layout.
5. Test your CSS specificity understanding by writing clear, conflict-free styles.
6. Validate your CSS and HTML with W3C validators.

---

## Author

Made by **MONICA DHIEU**

---

## License

This project is open source and available under the MIT License.
