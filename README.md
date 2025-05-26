This project is a **Fancy Project Structure Viewer** that allows you to upload a `.zip` file of your project and visualize its directory structure. It then generates a copyable text representation of that structure.

---

## Features

* **Upload Zip Files:** Easily upload your project as a `.zip` archive.
* **Interactive Tree View:** Visualizes the project structure in an interactive, collapsible tree format directly in the browser.
* **Copyable Text Output:** Generates a plain text representation of the project structure, ready to be copied to your clipboard.
* **Stylish Interface:** A clean and modern user interface for a pleasant experience.

---

## How to Use

1.  **Save the Files:** Save the provided `index.html` file to your computer.
2.  **Open in Browser:** Open the `index.html` file using your web browser.
3.  **Upload Zip:** Click the "Upload Your Project (.zip)" button and select your project's `.zip` file.
4.  **View Structure:** The application will display the project's file and folder structure.
5.  **Copy Text:** Below the visual tree, you'll find a copyable text version of the structure. Click the "Copy to Clipboard" button to copy it.

---

## Technical Details

This project is a client-side web application built with:

* **HTML:** Provides the basic structure of the page.
* **CSS:** Styles the application, including the tree view and the overall layout. It uses the `Inter` font from Google Fonts for a modern look.
* **JavaScript:** Handles the core logic, including:
    * Reading and processing the uploaded `.zip` file using the **JSZip library**.
    * Building a hierarchical data structure representing the project.
    * Dynamically rendering the interactive tree view.
    * Generating the plain text output of the project structure.
    * Implementing the copy-to-clipboard functionality.

---

## Project Structure

```
.
└── index.html
```
*Note: This project consists of a single HTML file that includes all the necessary CSS and JavaScript inline or via CDN for simplicity.*
