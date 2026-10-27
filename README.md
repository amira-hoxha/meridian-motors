# Meridian Motors — source code

Static dealership prototype. Includes HTML, CSS, JavaScript and local hero images.

## Run locally

From this folder, run:

    python3 -m http.server 8000

Then open http://localhost:8000 in your browser. Use a local server because page links start at the site root.

## Files

- index.html — homepage and interactive sample inventory
- sell-or-trade.html — trade-in page and demo form
- financing.html — payment calculator and financing information
- our-approach.html — dealership concept page
- assets/ — local hero photographs

CSS and JavaScript are embedded in each HTML file. No build tools or dependencies are required.

Use the Palette control to switch between Forest and Graphite. The choice and saved vehicles persist in browser localStorage.

Google Fonts and the sample inventory photos require internet access. Photography is sourced from Unsplash; verify applicable usage requirements before production use.

All inventory is illustrative. Forms do not send requests; there is no backend, credit application or real dealership integration.
