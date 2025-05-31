# CSS-alignment

This repository demonstrates various methods for aligning elements using CSS. It showcases both classic CSS2 positioning techniques and modern CSS3 Flexbox solutions to center and align content within containers.

## Demo

You can view a live demo of this project here:  
**[Live demo](https://itg-software-front-end-internship.github.io/CSS-alignment/)**

## Features

- **CSS2 Solution:** Uses absolute positioning and transforms to align content vertically within a container.
- **CSS3 Solution:** Uses Flexbox for easy and responsive content alignment.
- Example HTML structure provided in `index.html`.
- Solution styles are organized in the `solutions/` directory.
- Main stylesheet (`styles.css`) demonstrates how to import and switch between different alignment solutions.

## File Structure

- `index.html` &mdash; Demo page with content to be aligned.
- `styles.css` &mdash; Main stylesheet, imports a selected solution.
- `solutions/positioning-solution.css` &mdash; CSS2 (position/transform) alignment example.
- `solutions/flex-solution.css` &mdash; CSS3 (Flexbox) alignment example.

## How to Use

1. Open `index.html` in your browser.
2. The page imports `styles.css`, which by default imports the CSS2 positioning solution.
3. To try the Flexbox solution, change the import in `styles.css` to:
   ```css
   @import url("/solutions/flex-solution.css");
   ```
4. Refresh the page to see the effect of the different alignment techniques.

## Purpose

This project is intended for learning and experimenting with different CSS alignment strategies. It is ideal for beginners exploring the differences between traditional CSS positioning and modern Flexbox layouts.

---

_Created with CodeSandbox_
