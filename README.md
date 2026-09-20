# Week 1 Day 2 Assignment — CSS Fundamentals

Styling and responsive layout practice: a styled business card (from Day 1) and a
brand-new Flexbox pricing section, both fully mobile-responsive.

## 📁 Files

| File | Purpose |
|---|---|
| `business-card.html` | Business card from Day 1, now styled with an external stylesheet |
| `pricing.html` | Three-card pricing section built with Flexbox |
| `styles.css` | Combined stylesheet for both pages |

## 🚀 Live Demo (GitHub Pages)

- **Business Card:** https://OtienoMartha.github.io/week-1-day-2-assignment/business-card.html
- **Pricing Section:** https://OtienoMartha.github.io/week-1-day-2-assignment/pricing.html

## 📸 Screenshots

### Business Card — Desktop

![Business card desktop view](screenshots/business-card-desktop.png)

### Business Card — Mobile

![Business card mobile view](screenshots/business-card-mobile.png)

### Pricing Section — Desktop

![Pricing desktop view](screenshots/pricing-desktop.png)

### Pricing Section — Mobile

![Pricing mobile view](screenshots/pricing-mobile.png)

## 🎨 What I Built

### Task 1 — Styled Business Card

The Day 1 business card, restyled with an external CSS file:

- Subtle off-white page background (`#f5f5f5`)
- Centred card container (`max-width: 400px`), white background, rounded corners,
  soft box-shadow, and internal padding
- **Inter** font from Google Fonts
- Brand-coloured 4px left border on the card (`#4a6cf7`)
- Consistent spacing on contact and location sections
- Links styled without underlines, in the brand colour, with a hover colour change
- Social links styled as pill-shaped buttons with a filled hover state

### Task 2 — Pricing Cards with Flexbox

Three plan cards laid out horizontally using Flexbox:

- **Free Plan** — KES 0/month
- **Pro Plan** — KES 1,500/month *(highlighted with a "Most Popular" badge,
  different background colour, border, and a slight scale-up)*
- **Enterprise Plan** — KES 5,000/month

Each card contains a plan name, price, feature list with checkmark bullets, and a
styled "Choose Plan" button.

### Task 3 — Responsive Layout

A single media query at `768px` makes the layout responsive:

- **Wider than 768px:** three cards side by side, each with `max-width: 350px`
- **768px or narrower:** cards stack vertically and take full width
- Page padding adjusts on mobile so content never touches the edges
- No horizontal scrollbar at any viewport width

### Bonus — Hover Effects

- Cards scale up slightly on hover (`transform: scale(1.05)`)
- Box shadow deepens on hover
- Buttons darken on hover
- All transitions are smooth (`transition: all 0.3s ease`)

## 🧠 What I Practiced

- CSS selectors, specificity, and the cascade
- The box model: `margin`, `padding`, `border`, `box-sizing`
- Colour and typography: hex colours, `font-family`, Google Fonts
- Layout with **Flexbox**: `display: flex`, `justify-content`, `align-items`, `gap`
- Responsive design with **media queries**
- Hover states and CSS transitions

## 🛠️ How to View Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/OtienoMartha/week-1-day-2-assignment.git