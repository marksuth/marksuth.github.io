# marksuth.dev

The source code for [marksuth.dev](https://marksuth.dev/). Built with [Hugo](https://gohugo.io/).

## Prerequisites

To work on this project locally, you will need:

- **Hugo** (Extended version): `v0.154.4` or later recommended.
- **Node.js**: `v24.12.0` or later recommended.
- **Dart Sass**: `v1.97.2` or later recommended (used for processing SCSS).

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/marksuth/marksuth.github.io.git
   cd marksuth.github.io
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   hugo server -D
   ```
   The site will be available at `http://localhost:1313/`.

## Project Structure

- `content/`: Contains the markdown files for the site pages.
- `layouts/`: Custom layouts for the site (if any).
- `themes/marksuth/`: The main theme containing assets, templates, and SCSS.
- `static/`: Static files like images and icons.
- `hugo.toml`: The main configuration file.

## Deployment

The site is automatically built and deployed to GitHub Pages via GitHub Actions whenever changes are pushed to the `live` branch.

- **URL:** [https://marksuth.dev/](https://marksuth.dev/)
- **Workflow:** `.github/workflows/hugo.yaml`
