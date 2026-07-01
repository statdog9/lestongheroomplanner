# Le Stonghe — Room Assignment Planner

An interactive seating/room planner for the **Le Stonghe** wedding at the Le Stonghe Estate in Fossombrone, Le Marche, Italy. It lets you assign guests to bedrooms across the estate's three properties — the **Palazzo**, the **Country House**, and the **City Apartment** — directly on top of each apartment's floor plan.

The entire app is a single self-contained `index.html` file. All styling, logic, and floor-plan images are embedded, so there is nothing to build or install — just open it in a browser.

## Features

- **Drag-and-drop or tap** guests from the unassigned list onto bedrooms on each floor plan.
- **Mobile-friendly:** tap a bedroom to pick a guest, tap a placed guest to move / unassign / delete, and use the header menu to jump between estates.
- **Shared rooms:** two single guests can share one bedroom; couples take a room to themselves.
- **Live counts:** each apartment shows rooms filled plus adults and kids, and each estate shows its totals.
- **Guest management:** add guests (solo or couple) with their children's names, organize them into family groups, and remove anyone with a tap.
- **Floor-plan zoom:** click any plan to see it full-size.
- **Copy plan:** export the full assignment list to your clipboard.

## Usage

Open `index.html` in any modern web browser (Chrome, Safari, Firefox, Edge). No internet connection is required after the first load — the floor-plan images are embedded in the file, and only the display fonts load from the web.

## Deploying with GitHub Pages

1. Create a new repository on GitHub and upload this folder's contents (or push it with git).
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set the source to **Deploy from a branch**, choose your `main` branch and the `/ (root)` folder, and save.
4. After a minute or two, your planner will be live at `https://<your-username>.github.io/<repo-name>/`.

Because the file is named `index.html`, GitHub Pages serves it automatically as the homepage.

## Notes

- The planner's design intentionally mirrors the wedding website (aleandjayitaly.wedding) — the same fonts, colors, and styling.
- Assignments live only in the open browser tab; reloading the page resets to the starting plan. To save a particular arrangement, use **Copy Plan to Clipboard** and paste it somewhere safe.
