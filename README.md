# DCESK8 - Washington DC Electric Skateboarding

<p align="center">
  <img src="images/barbershop/gallery/1.jpg" alt="DCESK8 Community" width="600">
</p>

<p align="center">
  <strong>Shredding The Concrete Jungle Since 2016</strong>
</p>

<p align="center">
  <a href="https://www.meetup.com/dcesk8/">Meetup</a> |
  <a href="https://t.me/dcesk8">Telegram</a> |
  <a href="https://instagram.com/dcesk8">Instagram</a> |
  <a href="https://twitter.com/dcesk8">Twitter</a> |
  <a href="https://teespring.com/stores/dcesk8/">Shop</a>
</p>

---

## About

**DCESK8** is the official website for Washington DC's premier electric skateboarding community. Founded in 2016, we've grown into one of the largest PEV (Personal Electric Vehicle) communities in the United States.

### By The Numbers

| Metric | Count |
|--------|-------|
| Community Members | 834+ |
| Miles Traveled | 64,600+ |
| Supported Brands | 26 |

### Our Mission

We advocate for the safe and legal use of personal electric vehicles while building a welcoming community for riders of all skill levels. Whether you're riding an electric skateboard, onewheel, EUC, or e-bike, you're part of the DCESK8 family.

---

## Features

- **Community Hub** - Central landing page with community stats, gallery, and social links
- **Charge Spot Map** - Interactive Google Maps integration showing charging locations across DC
- **Event Registration** - Signup pages for group rides and community events
- **Merchandise Store** - Official DCESK8 gear via Teespring integration

---

## Tech Stack

### Frontend
| Technology | Purpose |
|------------|---------|
| HTML5 | Semantic structure |
| CSS3 | Styling & animations |
| JavaScript (ES5) | Interactivity |
| jQuery 1.11.2 | DOM manipulation |
| Bootstrap 3 | Responsive grid system |

### Libraries & Plugins
| Library | Purpose |
|---------|---------|
| Owl Carousel | Image sliders |
| Magnific Popup | Lightbox galleries |
| WOW.js | Scroll animations |
| Masonry.js | Grid layouts |
| Parallax.js | Parallax scrolling effects |
| YTPlayer | YouTube video backgrounds |

### APIs & Services
| Service | Purpose |
|---------|---------|
| Google Maps API | Interactive charge spot map |
| Google Analytics | Traffic analytics |
| Google Fonts | Typography (Open Sans, Dosis) |

### Hosting
| Platform | Details |
|----------|---------|
| AWS S3 | Static website hosting |
| Domain | dcesk8.com |

---

## Project Structure

```
DCESK8/
├── index.html          # Main landing page
├── map.html            # Interactive charge spot map
├── signup.html         # Event registration
├── error.html          # 404 error page
│
├── css/                # Stylesheets
│   ├── style.css       # Main styles
│   ├── style-responsive.css
│   ├── bootstrap.min.css
│   └── ...
│
├── js/                 # JavaScript
│   ├── all.js          # Main initialization
│   ├── contact-form.js
│   └── custom/
│       └── map.js      # Google Maps config
│
├── images/             # Image assets
│   ├── barbershop/     # Gallery images
│   ├── clients-logos/  # Brand logos
│   └── icons/          # Map markers
│
├── fonts/              # Web fonts
├── assets/             # Additional assets
└── rs-plugin/          # Revolution Slider
```

---

## Getting Started

### Prerequisites

This is a static website with no build process required. Simply serve the files with any web server.

### Local Development

Using Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Using Node.js:
```bash
npx serve
```

Then visit `http://localhost:8000` in your browser.

### Deployment

The site is configured for AWS S3 static hosting. Upload all files to your S3 bucket configured for static website hosting.

---

## Weekly Rides

| Day | Time | Location |
|-----|------|----------|
| Wednesday | 6:30 PM | Sweet Leaf, Arlington VA |

Join us on [Meetup](https://www.meetup.com/dcesk8/) for the latest ride schedules and special events.

---

## Community Links

- **Telegram**: [t.me/dcesk8](https://t.me/dcesk8) - Main chat group
- **Instagram**: [@dcesk8](https://instagram.com/dcesk8) - Photos & stories
- **Twitter**: [@dcesk8](https://twitter.com/dcesk8) - Updates & news
- **Meetup**: [meetup.com/dcesk8](https://www.meetup.com/dcesk8/) - Event RSVPs
- **Shop**: [Teespring Store](https://teespring.com/stores/dcesk8/) - Official merch

---

## Charge Spot Map

The interactive map at `/map.html` displays community-sourced charging locations around the DC area. Spots are color-coded by type:

| Color | Type |
|-------|------|
| Green | Indoor |
| Yellow | Indoor / 24-hour |
| Orange | Outdoor |
| Blue | Outdoor / 24-hour |

Submit new charge spots via the Telegram bot using the `/chargespot` command.

---

## Contributing

We welcome contributions to improve the DCESK8 website. Please:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

For questions or suggestions, reach out via:
- Email: contact@DCESK8.com
- Telegram: [t.me/dcesk8](https://t.me/dcesk8)

---

## License

This project is maintained by the DCESK8 community.

---

<p align="center">
  <strong>Ride Safe. Ride Together.</strong>
</p>

<p align="center">
  Made with battery power in Washington, DC
</p>
