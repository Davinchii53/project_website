# Project Progress Report

**Date:** June 12, 2026  
**Project:** TPANG The Social Fabriek - Front-End Landing Page  
**Stack:** Vanilla HTML5 / CSS3  
**Deployment Target:** GitHub Pages  

## Milestones Achieved Today

* **Project Scoping:** 
  * Identified a local Bandung venue (TPANG The Social Fabriek) that currently relies on Google Maps, making it an ideal portfolio candidate.
  * Established a dark-themed, industrial, and minimalist design language to match the venue's late-night warehouse aesthetic.
* **Architecture Decisions:** 
  * Chose a single-page layout utilizing smooth-scrolling anchor links for faster, frictionless navigation.
  * Opted for pure HTML and CSS to maintain a clean codebase, bypass framework configuration overhead, and ensure seamless compatibility with static hosting.
* **Codebase Generation:**
  * Drafted `style.css` implementing CSS variables for theme management, a frosted glassmorphism sticky navigation, CSS Grid for typography alignment, and grayscale hover filters for the gallery.
  * Drafted `index.html` combining the Hero, Menu, Space (Gallery), and Footer sections into one continuous page.


# Project Progress Report

**Date:** June 13, 2026  
**Project:** TPANG The Social Fabriek - Front-End Landing Page  
**Stack:** Vanilla HTML5 / CSS3 / Vanilla JavaScript
**Deployment Target:** GitHub Pages  

## Milestones Achieved Today

* **Theme Transformation:** * Successfully migrated the UI to a bright, "kopi susu" (milk coffee) theme.
  * Replaced dark grays with creamy backgrounds, espresso text, and caramel accents using CSS variables.
* **Interactive DOM Manipulation:**
  * Implemented a dynamic menu filtering system using vanilla JavaScript and `data-category` attributes.
* **Form State & Validation:**
  * Built a custom Venue Booking UI featuring interactive space-selection cards and a dynamically generated time slot grid.
  * Wrote custom client-side validation logic to prevent empty submissions.
* **State Management & Checkout Logic:**
  * Developed an Off-Canvas "Order Ahead" Cart that slides in from the screen edge.
  * Managed cart state (adding/removing items, calculating totals) using a JavaScript array.
  * Implemented a real-world, no-backend checkout solution that formats the cart array into a string and redirects the user to a pre-filled WhatsApp message.
* **Custom UI Components:**
  * Designed and built a Live Music & Event Calendar modal system.
  * Used `data-` attributes on event cards to dynamically inject titles, dates, and descriptions into a centralized, reusable modal overlay.

## Current File Structure

```text
/project-folder
├── index.html    (Main content structure, JS logic for filters, forms, cart, and modals)
└── style.css     (Global variables, layout grids, animations, overlays, and responsive queries)