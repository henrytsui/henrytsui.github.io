# Qwen Code Context: Henry Tsui's Personal Website

This directory contains the source code for Henry Tsui's personal website/resume, hosted on GitHub Pages. The site is a static HTML/CSS/JS portfolio/resume template.

## Project Type
This is a **non-code project** in the sense that it is primarily a static website template, not an application with a build process or complex logic. It's used to present a personal resume/porfolio online.

## Key Files and Directories

- **`index.html`**: The main HTML file for the website. Contains the structure and content for the resume, including sections for About, Experience, Projects, and Contact.
- **`index_redirect.html`**: A simple HTML file that redirects to an external IP address (3.13.143.249). This might be used for temporary redirection.
- **`css/`**: Directory containing the stylesheets.
  - `style.css`: The main custom CSS file defining the site's look and feel.
  - `bootstrap.min.css`, `aos.css`, `animate.min.css`: Third-party CSS libraries for styling, animations, and 'Animate On Scroll' effects.
- **`js/`**: Directory containing JavaScript files.
  - `custom.js`: The main custom JavaScript file handling site interactions like navigation, preloader, and modal windows.
  - `jquery.js`, `bootstrap.min.js`, `plugins.js`, `aos.js`, etc.: Third-party JS libraries for DOM manipulation, Bootstrap components, and animations.
- **`img/`**: Directory for image assets (profile picture, project screenshots, signature SVG).
- **`fonts/`**: Directory for font files, specifically Glyphicons Halflings.
- **`ionicons/`**: Directory for Ionicons icon font files.
- **`一念永恒.zip`**: Appears to be a zipped file, possibly unrelated to the website itself.

## Usage

This directory holds the static files for a personal website. The content in `index.html` can be edited directly to update the resume information (name, experience, projects, contact details). Styles can be modified in `css/style.css`. The site is designed to be hosted on a simple static file server like GitHub Pages.

The presence of `index_redirect.html` suggests there might be a mechanism to redirect the root URL, possibly managed outside this repository's direct content (e.g., via GitHub Pages settings or a custom domain configuration pointing to this file).