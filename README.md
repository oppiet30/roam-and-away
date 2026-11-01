# Roam & Away

A responsive travel agency concept built with plain HTML, CSS, and JavaScript.

## Run locally

```bash
git clone https://github.com/oppiet30/roam-and-away.git
cd roam-and-away
python3 -m http.server 8080 --directory dist
```

Open http://localhost:8080. PHP also works: `php -S localhost:8080 -t dist`.

## Features

- Responsive destination showcase with region and travel style filters
- Saved journeys stored locally in your browser
- Expandable sample itineraries
- Trip planner with departure date, traveler count, and budget
- Downloadable plain-text trip brief

## Editing

The complete page is in `dist/index.html`. No dependencies or build step are required. Serve `dist/` using Apache or any static web host.

## Scope

This is a travel agency concept. Packages and prices are illustrative. It does not create bookings, accept payments, or send inquiries. Saved journeys stay in the current browser; trip briefs download to the visitor's device. Photography loads from Unsplash and fonts load from Google Fonts, so those assets require internet access.

The ChatGPT Sites publication is managed separately; GitHub pushes do not automatically deploy it.
