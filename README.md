# PawMate – Pet Care Marketplace (clickable prototype)

A front-end prototype of a mobile marketplace for dog walking, grooming, home visits and boarding.
Plain HTML, CSS and JavaScript. No build step, no dependencies. All data is demo data.

## What you can try
**Dog owner:** home dashboard, live walk map, upcoming bookings, find a pawmate, dates and time pickers,
provider profiles, review and pay, chat, walk details with comments and tips, PawMate Plus membership.
**Service provider:** earnings, accept or decline requests, availability calendar, services and prices, chat.

## Run it locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder.

## Put it on GitHub Pages
1. Create a new repository on GitHub and upload everything in this folder (keep the `css` and `js` folders).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute the site is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## Structure
- `index.html` – page shell and phone frame
- `css/style.css` – colours (CSS variables at the top), layout and components
- `js/app.js` – screens, demo data and navigation

## Not included yet
Real GPS and maps, payments, push notifications, user accounts and the admin dashboard.
Emoji stand in for photos; replace them with real images in `js/app.js`.
