# CSS Fundamentals – Summary

CSS (Cascading Style Sheets) is used to style HTML webpages. While HTML provides the structure and content, CSS controls the appearance, including colors, fonts, spacing, layouts, and animations. Separating design from HTML makes websites easier to maintain and gives them a professional look.

CSS should be linked in the `<head>` section of an HTML document so the browser can load styles before displaying the page. This improves performance and prevents the page from appearing unstyled. Think of it like a painter gathering all the paint before starting the job.

CSS applies styles using **selectors**, which target specific HTML elements. Common selectors include **element selectors** (`p`, `h1`), **class selectors** (`.card`), **ID selectors** (`#header`), **grouping selectors** (`h1, h2`), **universal selectors** (`*`), and more advanced selectors like descendant, child, attribute, pseudo-class, and pseudo-element selectors.

Browsers use the **Document Object Model (DOM)** to locate elements and apply CSS rules. The DOM represents the HTML document as a tree structure, allowing CSS to match selectors with the correct elements.

Developer Tools make it easy to inspect and edit webpages. The **Elements** tab displays the HTML structure, while the **Styles** panel shows all CSS rules applied to the selected element. Developers can also edit CSS live in the browser to test changes before updating their files.

There are **three ways to add CSS**:

* **Inline CSS** – Styles written directly inside an HTML element using the `style` attribute.
* **Internal CSS** – Styles written inside a `<style>` tag in the HTML file.
* **External CSS** – Styles stored in a separate `.css` file and linked to HTML. This is the recommended method because it is reusable, organized, and easy to maintain.

When linking external stylesheets, correct **file paths** are important. Examples include `./style.css` for a file in the same folder, `./css/style.css` for a file inside a CSS folder, and `../style.css` for a file located one folder above.

Understanding these CSS fundamentals provides a strong foundation for building attractive, responsive, and well-organized websites.
