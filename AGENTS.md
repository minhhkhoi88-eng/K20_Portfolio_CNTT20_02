# Repository Guidance

## Project Structure
- This is a static Vietnamese portfolio site. `index.html` is the main page and `ket-qua.html` is the contact-form result page.
- Shared styles live in `css/style.css`; static images and other media live in `assets/`.
- There is no build system or package manager. Keep the site runnable by opening the HTML pages directly in a browser.

## Editing Conventions
- Preserve the Vietnamese content and `lang="vi"` document language.
- Use relative, forward-slash paths for local stylesheets, links, and assets so the pages work from this project directory.
- Keep shared visual changes in `css/style.css` and maintain consistent header and footer behavior across both pages.
- Use semantic HTML and retain accessible labels, alternative text, and visible keyboard focus styles.
- Keep the contact form as a client-side HTML exercise unless a backend is explicitly requested; it currently submits by GET to `ket-qua.html` and does not send or store data.

## Validation
- For HTML or CSS changes, open the affected page(s) in a browser and check desktop and narrow/mobile layouts.
- Verify local links, stylesheet loading, and referenced assets. There are currently no automated test or build commands.