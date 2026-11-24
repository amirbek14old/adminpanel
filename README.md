# Pulse – Blog with Admin Panel

A single-file website with a public blog and a separate admin panel.

## Run
Open `index.html` in any browser. No install or build step needed.

## Pages
- Public site: `index.html` (or `index.html#site`)
- Admin panel: `index.html#admin` (demo password: `admin123`)

## Admin features
Create / edit / delete posts, draft & publish, bulk actions, feature a post,
duplicate, undo delete, live preview editor, dashboard charts, settings,
theme toggle, JSON export/import.

## Notes
- Data is stored in the browser (localStorage), so it is per-device.
- The login is client-side only and is NOT real security. Use a backend
  (Node/Express, Firebase, etc.) for a production site.
