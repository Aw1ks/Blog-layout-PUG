# Blog-layout-PUG
This project is a blog website template built using Pug (formerly Jade) for templating. It features a dynamic header, customizable post cards, and a clean, modern design.
## Project Structure
The project is organized with Pug files for templating the HTML structure. Here's a breakdown of the key files:
*   **`html/head.pug`**:
    *   This file serves as the base template for all pages.
    *   It defines the basic HTML structure (`doctype`, `html`, `head`, `body`).
    *   Includes meta tags for character set, viewport, and compatibility.
    *   Links the main stylesheet (`../../css/style.css`).
    *   Sets the title of the page to "ABOBAS".
    *   Includes the `header.pug` and `main.pug` files.
*   **`html/header.pug`**:
    *   Defines the website's header section.
    *   Uses Pug mixins (`select-item`, `custom-select`) to create reusable components for dropdown menus.
    *   Includes a burger menu, logo, search bar, and navigation links.
    *   The header is divided into a top section (`header__top`) and a bottom section (`header__bottom`).
    *   The top section contains the burger menu, logo, search field, and search button.
    *   The bottom section contains multiple custom select dropdowns for "Demos," "Post," "Features," "Categories," and "Shop," along with a "Buy Now" link.
*   **`html/main.pug`**:
    *   Defines the main content area of the website.
    *   Uses a Pug mixin (`topic-card`) to create reusable post card components.
    *   Each post card displays an image, post type, topic, author, date, view count, and a brief description.
    *   The `main` section contains nine example post cards, each with placeholder data.
## Getting Started
1.  **Dependencies:** This project likely requires a Pug compiler to convert the `.pug` files into `.html` files. You'll also need a CSS file (`../../css/style.css`) to style the website.
2.  **Compilation:** Use a Pug compiler (e.g., `pug-cli`) to compile the `.pug` files into `.html` files.
3.  **Styling:** Create or modify the `../../css/style.css` file to style the website.
4.  **Images:** Place the images used in the project (e.g., `../../media/png/1.png`, `../../media/svg/Logotype.svg`) in the appropriate directories.
5. **Run:** Open the generated HTML files in your browser.
