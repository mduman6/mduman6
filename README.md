# Milestone 2 Project Documentation

## 1. Accessibility Fixes (WAVE Reports)
* **First-Level Heading:** I added a clear `<h1>` tag to the top of each page so screen reader users immediately know what the page content is about.
* **Table Caption:** I added a `<caption>` element right after the opening `<table>` tag so assistive tools can describe what the data represents before reading it aloud.
* **Empty Links:** I added descriptive text inside my icon links so blind users know exactly where the buttons will redirect them.
* **Color Contrast:** I checked my theme with the WebAIM Contrast Checker and darkened my text color against the white background to hit a clear WCAG AA score.

## 2. Visual Design & Gestalt Principles
* **Proximity:** I used proximity to group my related project info cards tightly together inside one layout block, proving to the user's brain that they belong to the same family.
* **Similarity:** I used similarity by making every action button share the exact same rounded border shapes, sizing, and color styling so my layout feels cohesive and predictable.
* **Consistent Palette:** I used an identical color scheme across all three pages to ensure the entire website behaves like a matching set.

## 3. Accessible Form Implementation
* I constructed a secure contact form using explicit matching `<label>` elements for inputs, wrapped similar inputs inside a structured `<fieldset>` container with a defining `<legend>` header, and included `aria-describedby` warning badges for active live error states.
