# CalmWait Clinic Dashboard

A static multi-page clinic queue and patient dashboard prototype built with HTML and CSS.

## Open the project

Open `index.html` in a web browser. Use the navigation links on the pages to move between the dashboard, analytics, console, login, notifications, profile, progress, queue, and visit pages.

## Project structure

- `index.html` and `index.css` — dashboard landing page and its page-specific styles.
- `global/global.css` — shared layout, typography, components, hover states, and focus states.
- `anal/` — analytics page and its styles.
- `conn/` — clinic console page and its styles.
- `login/` — patient login page and its styles.
- `notification/` — notifications page and its styles.
- `pro/` — patient profile page and its styles.
- `progress/` — journey progress page and its styles.
- `que/` — queue status page and its styles.
- `visit/` — visit pass page and its styles.
- `assets/` — downloadable PDF files: the waiting pass and patient information summary.

Each page links to `global/global.css` for shared styling and to its own CSS file for page-specific styling.

## Downloads

- The visit page downloads `assets/waiting-pass.pdf`.
- The profile page downloads `assets/patient-info.pdf`.

The QR graphic in the waiting pass is illustrative and is not scannable.

## Notes

This is a front-end prototype. Some controls are visual examples and may not connect to a live clinic system or save data.
