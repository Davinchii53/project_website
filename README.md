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

## 🎯 Milestones Achieved Today

* **Theme Transformation:** * Successfully migrated the UI from a dark, industrial aesthetic to a bright, "kopi susu" (milk coffee) theme based on stakeholder feedback.
  * Replaced dark grays with creamy backgrounds, espresso text, and caramel accents using CSS variables for a seamless transition.
  * Updated hero image overlay and gallery filters (swapped grayscale for warm sepia) to match the new lighting and mood.
* **Interactive DOM Manipulation:**
  * Implemented a dynamic menu filtering system using vanilla JavaScript, proving capability in state management without a framework.
  * Tagged HTML elements using `data-category` attributes for logical grouping.
  * Created CSS keyframe animations (`fadeInSlide`) for smooth state transitions when categories are toggled.

## 🗂️ Current File Structure

```text
/project-folder
├── index.html    (Main content structure, section anchors, and JS filter logic)
└── style.css     (Global variables, layout grids, animations, and responsive queries)