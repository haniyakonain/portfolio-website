# Portfolio Website

A minimal static personal academic website, written in plain HTML and one CSS file. It doesn't use JavaScript or frameworks and has no build step.

Live site: https://haniyakonain.github.io/portfolio-website/

## Files

- `index.html`: home page
- `publications.html`: publications grouped by year
- `teaching.html`: courses taught
- `code.html`: code repositories
- `style.css`: all styling

## Run locally

1. Clone the repository:
   ```
   git clone https://github.com/haniyakonain/portfolio-website.git
   cd portfolio-website
   ```
2. Start a local web server:
   ```
   python3 -m http.server 8000
   ```
3. Open http://localhost:8000 in your browser.

You can also open `index.html` directly in a browser without a server.

## Editing

All content is placeholder text. Edit the HTML files to put in your own information. The sidebar is repeated in every page, so a change to it has to be made in all four files.

To add a profile photo, put `photo.jpg` in the folder. Then, in each page, replace `<div class="photo">Photo</div>` with `<img class="photo" src="photo.jpg" alt="Your Name">`.

## Deploy

The site is hosted on GitHub Pages from the `main` branch. Every push to `main` updates the live site automatically.
