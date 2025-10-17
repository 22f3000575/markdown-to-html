# Markdown Viewer

This is a simple, single-file responsive web application designed to display Markdown content from an `input.md` file, converting it to HTML using [Marked.js](https://marked.js.org/) and styling it with [Tailwind CSS](https://tailwindcss.com/).

## Features

-   **Markdown to HTML Conversion**: Automatically parses `input.md` and renders it as HTML.
-   **Responsive Design**: Utilizes Tailwind CSS for a clean, mobile-first, and responsive layout.
-   **Single File**: All necessary HTML, CSS (via CDN), and JavaScript (via CDN) are contained within `index.html` for easy deployment.

## How to Use

1.  **Save the files**: Ensure `index.html` and `input.md` are in the same directory.
2.  **Open `index.html`**: Simply open `index.html` in any modern web browser.

The application will automatically fetch `input.md`, convert its content to HTML, and display it in the browser.

## Technologies Used

-   **HTML5**: Structure of the web page.
-   **Tailwind CSS (CDN)**: For responsive styling.
-   **Marked.js (CDN)**: For efficient Markdown to HTML conversion.
-   **JavaScript**: To fetch the Markdown file and integrate Marked.js.

## Project Structure

```
.
├── index.html
└── input.md
```

## Contributing

Feel free to fork the repository, make improvements, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](#license) file for details.