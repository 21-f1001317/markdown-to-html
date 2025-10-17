# Markdown to HTML Renderer

This project provides a simple, single-page HTML application designed to render Markdown content (`input.md`) dynamically into a web page using JavaScript and the `marked` library. It's styled with Tailwind CSS for a modern and responsive user interface.

## Features

-   **Dynamic Markdown Rendering**: Fetches `input.md` and converts its content to HTML on the fly.
-   **Responsive Design**: Built with Tailwind CSS, ensuring a consistent look across various devices.
-   **Single-File Application**: All necessary code (HTML, CSS via CDN, JavaScript via CDN) is contained within `index.html` for easy deployment.

## Setup

1.  **Ensure `input.md` exists**: Place your Markdown content in a file named `input.md` in the same directory as `index.html`.
2.  **Open `index.html`**: Simply open the `index.html` file in your web browser.

The page will automatically fetch `input.md`, convert its content to HTML, and display it.

## Technologies Used

-   **HTML5**: Structure of the web page.
-   **Tailwind CSS (CDN)**: For utility-first styling and responsive design.
-   **Marked.js (CDN)**: A JavaScript Markdown parser and compiler for the browser.
-   **JavaScript (ES6+)**: For fetching the Markdown file and handling its rendering.

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.