# Sebila Vivian - Profile & Mini-Portfolio

A semantic HTML5 profile and mini-portfolio website created for the Web Technologies course.

## About the Project

This website presents my profile, career goal, skills, and contact information using semantic HTML5 elements.

## AI-Assisted Content & Prompt Log

The AI prompt, raw AI output, edited final version, and reflection are documented in [PROMPT_LOG.md](PROMPT_LOG.md).

## Accessibility Review

A peer reviewer noticed that the original navigation colour was black and could be improved for the design and readability.

### Fix

I changed the navigation colour from black to brown and kept the text white. I also added hover and focus styles to make the navigation easier to use and see.

## Technologies Used

- HTML5
- CSS3

## Author

Sebila Vivian


## Responsive Notes

### Breakpoints Tested

I tested my portfolio using Microsoft Edge Developer Tools and the responsive device toolbar.

- **Mobile (375px):** Checked that the navigation, profile image, text, and other content fit without horizontal scrolling.
- **Tablet (768px):** Checked that the skills list displays in two columns and that the content remains readable.
- **Desktop (1280px):** Checked the portfolio at a wider screen size.

### Flexbox and CSS Grid

- **Flexbox:** Used in the navigation bar to centre links and allow them to wrap on smaller screens. Also used in the Home section to position the profile image and introduction, and in the contact form to arrange fields vertically.
- **CSS Grid:** Used in the Skills section. It displays one column on mobile and two equal-width columns on larger screens. This makes the skills easier to scan.

### Tailwind CSS

Tailwind utility classes are used in these sections:

- **Header:** Controls the background colour, text colour, spacing, alignment, and responsive heading size.
- **Navigation:** Controls layout, spacing, wrapping, colours, and hover effects.
- **Contact form:** Controls the form layout, maximum width, and submit button styling.

### CSS and Tailwind Styling Split

My custom CSS in `profile2.css` controls the general page styles, profile image, section appearance, form fields, skills grid, and responsive media queries. Tailwind utility classes are applied directly to selected HTML elements for the header, navigation, and contact form. This keeps the styling organised while demonstrating both CSS3 and Tailwind CSS.

### Responsive Design Approach

The design uses mobile-first base styles and media queries with `min-width` to adjust the layout for wider screens. I checked the portfolio at 375px, 768px, and 1280px using Microsoft Edge Developer Tools.

