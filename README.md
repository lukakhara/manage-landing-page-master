# Manage Landing Page

A responsive landing page for **Manage**, a fictional team-productivity product. Built with HTML, Tailwind CSS and vanilla JavaScript as a portfolio project, based on the [Frontend Mentor](https://www.frontendmentor.io) "Manage landing page" challenge.

**[Live site](https://USERNAME.github.io/REPO/)** | **[Source code](https://github.com/USERNAME/REPO)**

![Screenshot of the Manage landing page](./screenshot.png)

## Table of contents

- [Features](#features)
- [Built with](#built-with)
- [Getting started](#getting-started)
- [Deployment](#deployment)
- [What I learned](#what-i-learned)
- [Possible improvements](#possible-improvements)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Features

- Responsive layout that adapts to mobile, tablet and desktop screens
- Mobile navigation menu with a hamburger / close icon toggle
- Hover states on all interactive elements (links, buttons, social icons)
- Testimonial slider on mobile with clickable pagination dots; all testimonials shown side by side on larger screens
- Newsletter sign-up form with validation and error messages when:
  - the email field is empty
  - the email address is not formatted correctly
- Decorative background patterns and an all-in-one footer with social links

## Built with

- Semantic HTML5
- [Tailwind CSS v4](https://tailwindcss.com) (CLI build)
- Custom CSS for reusable components (buttons, hidden states)
- Vanilla JavaScript (menu toggle, testimonial slider, form validation)
- Mobile-first workflow
- [Be Vietnam Pro](https://fonts.google.com/specimen/Be+Vietnam+Pro) via Google Fonts
- [GitHub Pages](https://pages.github.com) for hosting

## Getting started

Clone the repo and install dependencies:

```bash
git clone https://github.com/USERNAME/REPO.git
cd REPO
npm install
```

Build the CSS once:

```bash
npm run build
```

Or rebuild automatically while you work (add this script to `package.json` if you don't have it):

```json
"scripts": {
  "build": "tailwindcss -i ./src/input.css -o ./dist/output.css --minify",
  "dev": "tailwindcss -i ./src/input.css -o ./dist/output.css --watch"
}
```

```bash
npm run dev
```

Then open `index.html` in your browser (or use the VS Code Live Server extension).

## Deployment

The site is deployed with GitHub Pages from the `main` branch.

1. Run `npm run build` so `dist/output.css` is up to date
2. Commit and push, including `dist/` (make sure it is not in `.gitignore`)
3. On GitHub: **Settings → Pages → Deploy from a branch → `main` / root**

All asset paths are relative (`./images/...`) so the site works under the `/REPO/` subpath.

## What I learned

- Setting up the Tailwind v4 CLI and building CSS for a static site
- Building a responsive layout with Tailwind breakpoints and CSS grid / flexbox
- Handling UI state with vanilla JS (toggling classes for the menu and slider)
- Validating forms with `checkValidity()` and showing accessible error messages
- Why absolute paths (`/images/...`) break on GitHub Pages project sites, and how to fix them with relative paths

## Possible improvements

- Swipe gestures for the mobile testimonial slider
- Keyboard and screen-reader support for the slider
- Connect the newsletter form to a real backend or email service
- Add page transitions and scroll animations

## Author

- Name: Luka Kharaishvili
- GitHub: [@lukakhara](https://github.com/lukakhara)
- LinkedIn: [Your name](https://www.linkedin.com/in/luka-kharaishvili-222066289/)

## Acknowledgments

Design and assets by [Frontend Mentor](https://www.frontendmentor.io). This is a practice project and is not affiliated with any real product.
