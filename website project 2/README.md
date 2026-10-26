# Student Portal — Multi-Page HTML Project

## Pages
- `index.html` — Home page with hero section and links to the main pages.
- `about.html` — Project overview and learning goals.
- `registration.html` — Student registration form.
- `contact.html` — Contact information and sample contact form.
- `style.css` — Shared responsive styling and reusable CSS design tokens.

## Design choices
- **Colour palette:** deep navy (`#172033`) provides strong text contrast; blue (`#3156d9`) highlights links and actions; pale grey (`#f5f7fb`) keeps the page background calm; white surfaces make content easy to scan.
- **Typography:** Arial/Helvetica is used for readable, familiar body text and consistent rendering without external font downloads.
- **Layout:** consistent header/navigation, centered content width, card-like sections, and generous spacing create a clear visual hierarchy.
- **Responsive design:** media queries adapt navigation, cards, and forms for smaller screens.
- **Reusable tokens:** colours are stored as CSS custom properties in `:root`, so the palette can be updated in one place.
- **Accessibility basics:** semantic HTML, labelled form controls, visible focus styling, and descriptive page metadata are included.

## How to run
1. Extract the ZIP file.
2. Open the `multi_page_html_project` folder in VS Code.
3. Open `index.html` and select **Open with Live Server** (if installed), or open the file directly in a browser.
4. Use the navigation links to visit Home, About, Registration, and Contact.

## Note
This is a front-end educational demo. Registration and contact forms do not send or store submissions because no backend is connected. Replace placeholder contact details before using the pages publicly.
