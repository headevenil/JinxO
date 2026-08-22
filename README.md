# JinxO

A lightweight, browser-based JinxO game interface built as a standalone HTML page.

## Features

* Fully client-side
* No backend or database required
* Works directly in a modern web browser
* Responsive layout for desktop and mobile devices
* Korean and English language support
* Game state handled in the browser

## Files

```text
.
├── index.html
└── README.md
```

The application is contained entirely within `index.html`.

## Running Locally

No installation or build process is required.

Simply open `index.html` in a modern web browser.

Alternatively, you can serve it with a simple local HTTP server:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Hosting with GitHub Pages

This project can be hosted directly using GitHub Pages.

1. Create a GitHub repository.
2. Upload `index.html` and `README.md`.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the branch containing `index.html` (usually `main`) and the `/ (root)` folder.
6. Save the settings.

GitHub will automatically deploy the site and provide a public URL.

### Repository Structure

Make sure `index.html` is located at the repository root:

```text
repository/
├── index.html
└── README.md
```

Once GitHub Pages finishes deploying, the game can be accessed through the generated GitHub Pages URL.

## Requirements

A modern web browser with JavaScript enabled.

No server-side runtime, package manager, or build tools are required.

## License

All rights reserved unless otherwise specified.
