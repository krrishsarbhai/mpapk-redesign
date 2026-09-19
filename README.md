# MPAPK Website Redesign

A modern, responsive, and accessible redesign of the Mahatma Phule Apang Prashikshan Kendra (MPAPK) NGO website, developed as a collaborative college project. 

## Problem Statement
The original MPAPK website contained outdated UI/UX elements, non-responsive tables, and exposed Personally Identifiable Information (PII) of its trustees. This project resolves these issues by implementing a clean front-end architecture, modern design principles, and strict data sanitization while preserving the organization's core mission and historical documentation.

## Key Features
*   **Modernized UI/UX:** Replaced legacy HTML tables with responsive CSS Grid and Flexbox layouts.
*   **Structured Information Architecture:** Segmented heavy, monolithic text into dedicated, easy-to-navigate pages (`history.html`, `admissions.html`, `donate.html`, `gallery.html`).
*   **Interactive Components:** Vanilla JavaScript implementations for smooth scrolling and a fully functional photo gallery lightbox.
*   **Privacy & Security:** Sanitized exposed PII (such as PAN numbers and home addresses) from the original site.
*   **Universal Components:** Implemented a consistent navigation bar and a comprehensive 4-column footer across all pages for seamless user routing.

## Tech Stack
*   **HTML5:** Semantic structuring and accessibility.
*   **CSS3:** Custom properties (variables), Grid, Flexbox, and responsive media queries.
*   **Vanilla JavaScript:** Lightweight DOM manipulation.
*   **Version Control:** Git & GitHub.

## Project Structure
```text
mpapk-redesign/
├── index.html           # Landing page with hero, courses, and leadership
├── history.html         # Detailed organizational timeline and mission
├── admissions.html      # Course eligibility and admission details
├── donate.html          # Support info and banking details
├── gallery.html         # Interactive photo gallery
├── README.md            # Project documentation
└── assets/
    ├── css/
    │   └── style.css    # Global stylesheet
    ├── js/
    │   └── main.js      # Interactive scripts (lightbox, etc.)
    └── images/          # Optimized logos, banners, and gallery assets