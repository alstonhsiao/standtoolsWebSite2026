# Stand Tools Official Website 2026

Official website for **Stand Tools Enterprise Co., Ltd.** — Manufacturer of Ideas since 1988.

## About

Stand Tools is a pioneer in digital torque wrench technology, integrating semiconductor, IC design, and mechanical engineering into precision hand tools. This website showcases the company's history, technology, products (DG®-II Digital Torque Wrench), and contact information.

## Pages

- **Home** - Brand overview, hero slider, product preview
- **About Us** - Company history, founding team, timeline, core values
- **Technology** - Semiconductor tech, IC design, mechanics, TAF-accredited calibration lab
- **Function** - DG®-II features, applications, specifications
- **Contact Us** - Contact form, phone/email/WeChat info, FAQ

## Tech Stack

- HTML5
- CSS3 (Custom properties, Grid, Flexbox, Animations)
- Vanilla JavaScript (Intersection Observer for scroll animations, hero slider)
- Font Awesome Icons
- Google Fonts (Montserrat)

## Deployment

This is a static website designed to be deployed on **Zeabur**.

### Deploy to Zeabur

1. Push to GitHub
2. Connect your Zeabur account to GitHub
3. Import this repository
4. Zeabur will automatically detect it as a static site and deploy

### Local Development

Simply open `index.html` in a browser, or use a local server:

```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx serve .
```

## Project Structure

```
standtoolsWebSite2026/
├── index.html          # Home page
├── about.html          # About Us
├── technology.html     # Technology
├── function.html       # Function / Products
├── contact.html        # Contact Us
├── css/
│   └── style.css       # Global stylesheet
├── js/
│   └── main.js         # Global JavaScript
├── images/             # Local images (if needed)
├── zbpack.json         # Zeabur deployment config
└── README.md
```

## License

© 2026 Stand Tools Enterprise Co., Ltd. All rights reserved.
