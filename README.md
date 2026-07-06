# Netflix Landing Page

A simple responsive landing page inspired by Netflix built with HTML and CSS.

## Project Structure

- `index.html` — main page markup
- `style.css` — styling and responsive layout
- `Images/` — image assets used in the page
- `.hintrc` — accessibility linting configuration

## Features

- Full-screen hero section with Netflix-inspired background
- Responsive navigation bar with logo, language selector, and sign-in button
- Email capture UI for starting membership
- Trending content carousel layout
- Feature cards with icons and promotional content
- Frequently Asked Questions section
- Footer with links and contact information

## Usage

1. Open `index.html` in your browser.
2. Or run a local development server from the project folder.

### Run locally with a simple server

Using Python 3:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Notes

- The page uses Google Fonts for the `Londrina Outline` font.
- Image paths are currently set to `/NetFlix/Images/...`, so ensure the assets folder remains in the project root if testing locally.

## Improvements

- Add mobile-specific navigation tweaks for smaller screens
- Convert the trending list into an interactive carousel
- Fix any broken image path issues if assets are moved
- Improve accessibility for forms and link focus states
