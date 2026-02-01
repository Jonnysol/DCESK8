# DCESK8 - Washington DC Electric Skateboarding 
<p align="center">
  <img src="images/image-1111.png.jpg" alt="DCESK8 Community" width="200">
  <a href="https://www.DCESk8.com/> Visit the Website</a> |
</p>
<p align="center">
  <img src="images/barbershop/gallery/1.jpg" alt="DCESK8 Community" width="600">
</p>

<p align="center">
  <strong>Shredding The Concrete Jungle Since 2016</strong><br>
  <em>The 2nd Largest Electric Mobility Community in the United States</em>
</p>

<p align="center">
  <a href="https://www.meetup.com/dcesk8/">Meetup</a> |
  <a href="https://t.me/dcesk8">Telegram</a> |
  <a href="https://instagram.com/dcesk8">Instagram</a> |
  <a href="https://twitter.com/dcesk8">Twitter</a> |
  <a href="https://teespring.com/stores/dcesk8/">Shop</a>
</p>

---

## Our Story

**What started as 4 friends with electric skateboards became a movement of 5,000+ riders.**

In 2016, five 17-year-olds in Washington DC shared a simple passion: riding electric skateboards through the city. There was no community, no infrastructure, no support—just us, our boards, and the open road. We didn't have a business plan. We had a group chat and a dream.

We built DCESK8 for the love of the game.

The challenges were endless. City regulations didn't account for PEVs. There was nowhere to charge. Riders had no resources to learn maintenance or repairs. The public didn't understand what we were doing. But every obstacle became an opportunity to build something bigger than ourselves.

**By 2023, DCESK8 had grown into the 2nd largest electric mobility community in the United States**—second only to New York City. What began in a garage with 4 people became a thriving ecosystem of over 5,000 riders across the DC metropolitan area.

In 2023, after 6 years of building, the founding team stepped away to focus on school and careers. But the community we built continues to thrive, maintained by the riders who made it what it is.

---

## The Journey (2016-2023)

### From Garage to Movement

| Year | Milestone |
|------|-----------|
| **2016** | 5 founders, ages 17, start weekly rides in DC |
| **2017** | First 100 members join; weekly repair nights begin |
| **2018** | Launch of the Charge Spot Map; 500+ members |
| **2019** | City Hall advocacy begins in Arlington, DC & Alexandria |
| **2020** | 1,000+ members; partnerships with major PEV brands |
| **2021** | Engineering Days established; community hits 2,500 |
| **2022** | 5,000+ members; recognized as 2nd largest US PEV community |
| **2023** | Founders transition out; community continues independently |

### By The Numbers

| Metric | Impact |
|--------|--------|
| Community Members | 5,000+ |
| Riders Helped by Charge Map | 5,000+ |
| Miles Traveled Together | 64,600+ |
| Supported Brands | 26 |
| Years Active | 7 |
| Cities Visited Nationwide | 15+ |

---

## What We Built

### Community-Led City Infrastructure: The Charge Spot Map

One of our proudest achievements was solving a problem the city wouldn't: **where do you charge your board?**

We built a crowdsourced charging infrastructure map that became essential for riders across the DMV. Community members submitted locations—coffee shops, libraries, friendly businesses, public outlets—and we mapped them all.

**Technical Implementation:**
- Custom Google Maps API integration with real-time data
- Community submission system via Telegram bot (`/chargespot` command)
- Backend API serving charge spot data from community submissions
- Color-coded markers for location types (indoor/outdoor, 24-hour access)

The Charge Spot Map helped over **5,000 riders** navigate the city without range anxiety. It proved that when cities don't build infrastructure for emerging mobility, communities will.

**Marker Types:**
| Color | Location Type |
|-------|---------------|
| Green | Indoor |
| Yellow | Indoor / 24-hour |
| Orange | Outdoor |
| Blue | Outdoor / 24-hour |

---

### Repair & Engineering Days

Every week, we opened our doors to teach riders how to build and maintain their vehicles. What started as friends helping friends became a structured program:

- **Battery diagnostics and cell replacement**
- **Motor maintenance and bearing swaps**
- **ESC programming and configuration**
- **Deck building and enclosure design**
- **Tire changes and brake adjustments**
- **Soldering workshops for DIY builders**

We believed that riders who understand their machines are safer riders. Hundreds of community members learned to maintain their own boards, reducing repair costs and building confidence.

---

### Advocacy & Policy Work

We didn't just ride—we fought for the right to ride.

**City Hall Appearances:**
- **Arlington County Board** - Advocated for PEV-friendly trail policies
- **Washington DC Council** - Testified on micromobility regulations
- **Alexandria City Council** - Pushed for legal clarity on electric skateboards

We worked with local government to educate officials on the difference between responsible PEV riders and reckless operators. Our advocacy helped shape policies that recognized electric skateboards as legitimate transportation.

---

### Brand Collaborations

As the community grew, so did industry recognition. We partnered with leading PEV manufacturers and retailers:

- **Boosted Boards** - Demo days and community events
- **Evolve Skateboards** - Group buy programs
- **Onewheel** - Cross-community rides
- **Meepo & Backfire** - Affordable board accessibility initiatives
- **Loaded Boards** - Deck customization workshops
- **Local bike shops** - Repair partnerships and parts sourcing

These collaborations brought discounts to members, demo opportunities for new riders, and legitimacy to the movement.

---

### Traveling the Country

DCESK8 wasn't just local. We hit the road:

- **NYC Group Rides** - Joint events with the #1 community
- **Philadelphia PEV Meetups** - East coast corridor connections
- **Boston Electric Riders** - New England expansion
- **National ESK8 Conferences** - Representing DC nationwide
- **Cross-country road trips** - Taking our boards from coast to coast

We proved that the PEV community wasn't just a DC thing—it was a national movement.

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
| Owl Carousel | Brand logo sliders |
| Magnific Popup | Gallery lightbox |
| WOW.js | Scroll-triggered animations |
| Masonry.js | Grid layouts |
| Parallax.js | Scrolling effects |
| YTPlayer | YouTube video backgrounds |

### APIs & Integrations
| Service | Purpose |
|---------|---------|
| Google Maps API | Charge Spot Map |
| Custom Charge Spot API | Community-sourced locations |
| Google Analytics | Traffic insights |
| Telegram Bot API | Charge spot submissions |
| Elfsight | Instagram feed widget |

### Hosting & Infrastructure
| Platform | Details |
|----------|---------|
| AWS S3 | Static website hosting |
| Heroku | Charge Spot API backend |
| Domain | dcesk8.com |

---

## Project Structure

```
DCESK8/
├── index.html          # Main landing page
├── map.html            # Charge Spot Map (community infrastructure)
├── signup.html         # Event registration
├── error.html          # 404 error page
│
├── css/
│   ├── style.css       # Main stylesheet
│   ├── style-responsive.css
│   ├── custom.css      # Map and component styles
│   └── bootstrap.min.css
│
├── js/
│   ├── all.js          # Core initialization
│   ├── contact-form.js # Form handling
│   └── custom/
│       └── map.js      # Google Maps + Charge Spot API
│
├── images/
│   ├── barbershop/gallery/  # Community photos
│   ├── clients-logos/       # Brand partner logos
│   └── icons/               # Map markers
│
├── fonts/              # Web fonts (FontAwesome, Et-Line)
└── assets/             # Additional resources
```

---

## Running Locally

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve

# Then visit http://localhost:8000
```

---

## Weekly Community Events

| Event | Day | Time | Location |
|-------|-----|------|----------|
| Group Ride | Wednesday | 6:30 PM | Sweet Leaf, Arlington VA |
| Repair Night | Saturday | 2:00 PM | Rotating locations |

Check [Meetup](https://www.meetup.com/dcesk8/) for the current schedule.

---

## Connect With The Community

| Platform | Link | Purpose |
|----------|------|---------|
| Telegram | [t.me/dcesk8](https://t.me/dcesk8) | Daily chat & ride coordination |
| Instagram | [@dcesk8](https://instagram.com/dcesk8) | Photos & stories |
| Twitter | [@dcesk8](https://twitter.com/dcesk8) | News & updates |
| Meetup | [meetup.com/dcesk8](https://www.meetup.com/dcesk8/) | Event RSVPs |
| Shop | [Teespring](https://teespring.com/stores/dcesk8/) | Official merchandise |
| Email | contact@DCESK8.com | Partnerships & inquiries |

---

## Contributing

The community keeps this project alive. To contribute:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

For charge spot submissions, use the `/chargespot` command in Telegram.

---

## Legacy

DCESK8 was never about us—it was about building something that would outlast us.

We started as teenagers who just wanted to ride. We became advocates, engineers, event organizers, and community builders. We proved that grassroots movements can create real infrastructure, influence policy, and bring thousands of people together.

The founding team has moved on, but the roads we mapped, the skills we taught, and the community we built continue to grow.

**To everyone who ever showed up to a Wednesday night ride, submitted a charge spot, fixed a board at repair night, or testified at city hall—thank you. DCESK8 belongs to you.**

---

<p align="center">
  <strong>4 friends. 5,000+ riders. Infinite miles ahead.</strong>
</p>

<p align="center">
  <em>Founded 2016 | Washington, DC</em>
</p>

<p align="center">
  Ride Safe. Ride Together. Ride Forever.
</p>
