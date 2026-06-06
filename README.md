# Discover Jackson County WV

An independent editorial tourism guide to **Jackson County, West Virginia** — covering both **Ripley** (the county seat) and **Ravenswood** (on the Ohio River).

🌐 **Live site:** https://discoverjacksoncountywv.com

## About

A privately operated guide to what there is to see, do, eat, and where to stay across Jackson County — from Cedar Lakes and America's largest small-town Independence Day to the Ohio River, craft moonshine, and miles of trails and water.

This is an independent project. It is not affiliated with any government agency, convention & visitors bureau, or county office.

## Tech

- Single self-contained `index.html` — all CSS and JavaScript inline
- Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces) + [Outfit](https://fonts.google.com/specimen/Outfit) via Google Fonts
- Interactive map: [Leaflet](https://leafletjs.com/) with CartoDB tiles (lazy-loaded)
- Structured data: schema.org JSON-LD (TouristDestination, Event, LodgingBusiness)
- No frameworks, no build step, no tracking networks

## Local development

Open `index.html` directly in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Hosted on **GitHub Pages** from the `main` branch. Pushing to `main` publishes the site. The custom domain is configured in the repository's **Settings → Pages**.

## License

© Discover Jackson County WV. All rights reserved.
