# Project References

This document maps the dependencies and relationships between files in the CMSC UI Stock Summit 2025 website project.

## HTML Files

- `index.html`: Main entry point for the website
  - References: 
    - `styles.css`: Global styles
    - `app.js`: Main React application
    - All component files through script tags

## CSS Files

- `styles.css`: Global styles for the entire website
  - Referenced by: `index.html`

## JavaScript Files

- `app.js`: Main React application component
  - Referenced by: `index.html`
  - References:
    - `Header.js`
    - `Hero.js`
    - `About.js`
    - `Competition.js`
    - `Timeline.js`
    - `PrizesJury.js`
    - `Registration.js`
    - `Referral.js`
    - `FAQ.js`
    - `Contact.js`
    - `Footer.js`

## Component Files

- `components/Header.js`: Navigation header component
  - Referenced by: `app.js`

- `components/Hero.js`: Hero section with main event title
  - Referenced by: `app.js`

- `components/About.js`: About CMSC UI organization section
  - Referenced by: `app.js`

- `components/Competition.js`: Competition details section
  - Referenced by: `app.js`

- `components/Timeline.js`: Event timeline section
  - Referenced by: `app.js`

- `components/PrizesJury.js`: Prizes and jury members section
  - Referenced by: `app.js`

- `components/Registration.js`: Registration form section
  - Referenced by: `app.js`

- `components/Referral.js`: Referral program section
  - Referenced by: `app.js`

- `components/FAQ.js`: Frequently asked questions section
  - Referenced by: `app.js`

- `components/Contact.js`: Contact information and form section
  - Referenced by: `app.js`

- `components/Footer.js`: Website footer with links and info
  - Referenced by: `app.js`