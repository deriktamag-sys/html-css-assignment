# HTML & CSS Practical Assignment

## Student Information

- **Student Name:** Derik Tamang
- **Student ID:** 2610412745
- **Module Name:** Web Technologies and Platforms
- **Assignment Title:** Designing a Navigation Bar and Card Components Using HTML & CSS

## Project Description

This project is a basic HTML5 and CSS3 technology-store webpage called **TechNest**. It demonstrates a navigation bar, a single product card, a section containing four product cards, and a complete webpage with a header, main content and footer.

The implementation focuses on fundamental HTML and CSS concepts taught in class. No Flexbox, CSS Grid, Bootstrap, Tailwind CSS, JavaScript or ready-made website template is used.

## Technologies Used

- HTML5
- CSS3

## Project Structure

```text
html-css-assignment/
│
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── laptop.svg
│   ├── headphones.svg
│   ├── keyboard.svg
│   └── ssd.svg
├── screenshots/
│   ├── navigation-bar.png
│   ├── single-card.png
│   ├── multiple-cards.png
│   └── complete-page.png
└── README.md
```

## Task 1 — Navigation Bar

The navigation bar contains:

- Website/brand name
- Home
- About
- Products
- Featured
- Contact

CSS concepts demonstrated:

- Element selectors
- Class selectors
- Colors
- Background colors
- Font properties
- Text properties
- Margin and padding
- Border
- Width/min-height
- `:hover` pseudo-class
- `float` and normal CSS flow

The navigation links use a hover effect so their background, text and bottom border change when the mouse moves over them.

## Task 2 — Single Product Card

The selected theme is a **Product Card**.

The card contains:

- Product image
- Product category
- Product title
- Short description
- Additional information
- Price
- View Product link

The card uses width, height, margin, padding, border, border radius, background color, text styling, image properties, button styling and a hover effect.

## Task 3 — Multiple Cards

The page contains four consistent product cards:

1. TechPro X15 Laptop
2. SoundMax Pro Headphones
3. KeyCraft 75 Keyboard
4. FastCore 1TB NVMe SSD

The cards are arranged using `display: inline-block` and normal CSS flow. Flexbox and CSS Grid are intentionally not used because they are not required for this assignment.

## Task 4 — Complete Webpage

The final webpage combines:

- Header / navigation bar
- Main introduction
- Featured product card
- Four-card product section
- Footer

## Learning Resources

| No. | Resource | Topic Learned | What I Learned | How I Used It |
|---|---|---|---|---|
| 1 | Teacher's Material | CSS selectors and basic styling | I reviewed how selectors target HTML elements and how basic CSS properties style them. | I used element and class selectors throughout the page. |
| 2 | University-provided learning materials | HTML structure | I reviewed how HTML elements provide structure to a webpage. | I used semantic elements such as `header`, `nav`, `main`, `section`, `article` and `footer`. |
| 3 | YouTube — Bro Code, CSS Navigation Bar | Navigation bar | I learned the basic structure and styling approach for a beginner navigation bar and hover states. | I created my own navigation design using similar fundamental concepts without copying a complete project. |
| 4 | MDN Web Docs — CSS Selectors | CSS selectors | I learned that selectors are patterns used to select elements to which CSS rules are applied. | I used element, class and pseudo-class selectors such as `.product-card`, `.nav-links a` and `:hover`. |
| 5 | MDN Web Docs — CSS Box Model | Margin, padding and border | I learned that padding is inside the border, while margin creates space outside the border. | I applied margin, padding and border to the navigation, sections and product cards. |
| 6 | W3Schools — Horizontal Navigation Bar | Navigation links, float and hover | I learned how list items and links can be arranged horizontally using basic CSS techniques and how hover styling changes link appearance. | I used `float`, `display: block`, padding and `:hover` for the navigation bar. |
| 7 | W3Schools — CSS Cards | Card structure and styling | I learned how an image and content container can be combined into a reusable-looking card and styled with borders, padding, rounded corners and hover effects. | I created the product cards with images, content, buttons and consistent styling. |

### Resource Links

- Teacher's Material: Use the class material supplied by the lecturer.
- University-provided material: Use the official material supplied through the university/module.
- YouTube tutorial: https://www.youtube.com/watch?v=f3uCSh6LIY0
- MDN CSS Selectors: https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Selectors
- MDN CSS Box Model: https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Box_model
- W3Schools Horizontal Navigation Bar: https://www.w3schools.com/css/css_navbar_horizontal.asp
- W3Schools CSS Cards: https://www.w3schools.com/HOWTO/howto_css_cards.asp

> Note: The teacher's and university-provided resources should be replaced with the exact links/files supplied by the lecturer if your class has specific URLs.

## Screenshots

After running the webpage in a browser, take the required screenshots and save them using the exact filenames below.

### Navigation Bar

![Navigation Bar](screenshots/navigation-bar.png)

### Single Product Card

![Single Product Card](screenshots/single-card.png)

### Multiple Cards

![Multiple Cards](screenshots/multiple-cards.png)

### Complete Website

![Complete Website](screenshots/complete-page.png)

## What I Learned

- HTML page structure
- Semantic HTML
- CSS selectors
- Colors and background colors
- CSS units such as pixels and percentages
- Typography and text properties
- Image properties
- Width and height
- Margin and padding
- Borders and border radius
- Hover effects
- Basic positioning and alignment
- `float`
- `display: inline-block`
- Organizing a project into HTML, CSS, image and screenshot folders
- Documenting learning resources in a README
- Uploading and presenting a project using GitHub

## Challenges and Solutions

> **Challenge 1:** The product images needed to fit the cards without stretching the design.
>
> **Solution:** I set a fixed image area and used `object-fit: cover` so the image fills the defined area while keeping its proportions.

> **Challenge 2:** The navigation links needed to appear horizontally without using Flexbox or CSS Grid.
>
> **Solution:** I reviewed basic horizontal navigation techniques and used `float` for the brand and navigation list items.

> **Challenge 3:** The four cards needed to have a consistent appearance.
>
> **Solution:** I created one reusable `.product-card` class and applied the same structure and CSS rules to all four cards.

## AI Usage

I used **ChatGPT** as a learning assistant while completing this assignment.

- **What I asked for:** Help analyzing the assignment instructions, planning the HTML/CSS structure, explaining CSS concepts, and checking that the implementation followed the restrictions.
- **What I learned:** I learned how semantic HTML elements, CSS selectors, the box model, hover states, `float`, and `inline-block` can be combined to build the required components.
- **What I implemented/changed myself:** I selected the product-card theme, product content, page structure, visual design, images, class names and final CSS values. I also reviewed and tested the code in the browser.

I understand that I am responsible for explaining the final code during the practical/viva.

## GitHub

Repository link: https://github.com/deriktamag-sys/html-css-assignment.git

## Final Checklist

- [x] Navigation bar created
- [x] Navigation links styled
- [x] Hover effect added
- [x] Single product card created
- [x] At least 4 cards created
- [x] Images included
- [x] Buttons/links included
- [x] CSS styling applied
- [x] HTML properly structured
- [x] No Flexbox used
- [x] No CSS Grid used
- [x] No JavaScript used
- [ ] Navigation screenshot taken
- [ ] Single-card screenshot taken
- [ ] Multiple-card screenshot taken
- [ ] Complete-page screenshot taken
- [x] README created
- [x] Learning resources documented
- [x] What was learned explained
- [x] Challenges and solutions documented
- [x] AI usage disclosed
- [ ] Project uploaded to GitHub
- [ ] GitHub link added
