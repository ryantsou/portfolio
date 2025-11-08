# Music Producer Portfolio

Personal website showcasing my work as a music producer and artist. Built from scratch with PHP, HTML, CSS and vanilla JavaScript.

## What's Inside

The site has these main sections:

**Hero landing** - Animated intro with my name and tagline

**About** - Quick intro about being a producer/artist/musician from Madagascar, plus my main genres with skill bars:
- Progressive House (70%)
- Future Bass (55%)
- Future Pop (64%)
- Future House (40%)
- Tropical House (60%)

**My Work** - Grid gallery displaying track artwork for projects like "I Fall Apart", "KIT", "Last Year", "Without You", "As Long As U're", and "Mine"

**Contact** - Form that submits to `process.php` for handling messages

## Structure

```
src/
├── css/           # Custom styles (main.css, animation.css, bulma framework)
├── image/         # Project artwork and assets
├── js/            # Client-side interactions
└── others/        # Bootstrap, fonts, FontAwesome icons
index.html         # Static version
index.php          # Main entry point
process.php        # Contact form backend
```

## Running Locally

Since it uses PHP for the contact form, you'll need a local server:

```bash
php -S localhost:8000
```

Then open `http://localhost:8000/index.php` in your browser.

For just viewing the layout without form functionality, `index.html` works standalone.

## Tech Details

- No framework dependencies for the main layout - just vanilla JS and CSS
- Bulma CSS for the grid system and responsive design
- Bootstrap components for some UI elements
- FontAwesome for icons
- Smooth scroll animations using AOS (animate on scroll)
- Contact form validation and submission with PHP

The design uses fade animations triggered as you scroll down through sections.
