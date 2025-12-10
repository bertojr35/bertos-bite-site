# Berto's Bite Site

Berto's Bite Site is a personal restaurant and food review journal. It lets me:

- Log restaurants I visit
- Rate them from 1–5 stars
- Track cuisine type, price level, and favorite dish
- Add notes about flavor, service, vibe, etc.
- Tag spots with custom tags like `date night`, `cheap eats`, `spicy`, `gameday`
- See a Top 5 leaderboard of my highest-rated recent spots
- Highlight places with a **🏈 Gameday Approved** badge when tagged `gameday`
- Switch visual themes (Purple Classic, Gold Blast, Night Game)

## How it works

This is a single-page static site built with:

- **HTML** only (no build tools, no backend)
- **Vanilla JavaScript** for:
  - Filtering and searching reviews
  - Tag and cuisine filters
  - Sorting by date, rating, or name
  - Theme switching and localStorage for remembering the chosen theme
- **CSS** for:
  - LSU-inspired purple & gold color schemes
  - Responsive layout
  - Card-style review UI and gameday badge styling

All data is stored in memory in the browser. New reviews persist only while the page is open.
For permanent storage, I can copy the data elsewhere or later connect this UI to a backend.

## Running locally

1. Download or clone this repo.
2. Open `index.html` in any web browser (Chrome, Edge, Firefox, etc.).
3. Start adding reviews using the **“Add New Entry”** panel.

## GitHub Pages deployment

This project is designed to work perfectly on **GitHub Pages**:

1. Commit `index.html` and `README.md` to the default branch (usually `main`).
2. In the repository, go to **Settings → Pages**.
3. Under **Source**, select:
   - **Deploy from branch**
   - Branch: `main`
   - Folder: `/ (root)`
4. Save. After a short build, the site will be available at a URL like:

`https://<your-username>.github.io/<your-repo-name>/`
