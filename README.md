# ServeScott

Volunteer coordination hub for Scott County, Minnesota.

## Local Development

Start a local server to preview the site:

```bash
# Using Python (recommended)
python -m http.server 8000

# Or using Node.js
npx live-server
```

Then open http://localhost:8000 in your browser.

## Deployment

The site is hosted on GitHub Pages with a custom domain.

### To deploy changes:

```bash
git add .
git commit -m "Description of changes"
git push origin main
```

GitHub Pages will automatically deploy changes (usually within 1 minute).

## File Structure

```
rooibos/
├── index.html              # Landing page
├── volunteer.html          # Google Form embed
├── opportunities.html      # All volunteer opportunities
├── resources.html          # Downloads & info
├── css/
│   └── styles.css          # Main stylesheet
├── js/
│   └── main.js             # Mobile nav, minimal interactivity
├── assets/
│   └── downloads/          # Future PDFs, docs for volunteers
├── CNAME                   # Custom domain config
└── README.md               # This file
```

## Adding Resources

To add downloadable resources:

1. Place files in `assets/downloads/`
2. Update `resources.html` to link to them

## Tech Stack

- Plain HTML/CSS/JS (no build step)
- Google Fonts (Nunito, Open Sans)
- GitHub Pages hosting
