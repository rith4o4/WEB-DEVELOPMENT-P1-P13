# P8: Sticky Navbar and Card Overlay Using CSS Positioning

## Aim
To use CSS positioning to create a sticky navigation bar and an overlay on a content card.

## Concepts
`position: sticky` keeps an element within its scrolling container after it reaches a specified offset. Positioned elements and `z-index` can layer an overlay over a card or image.

## Procedure
1. Create a page with a navigation bar and one or more content cards.
2. Apply `position: sticky` and an appropriate `top` value to the navigation bar.
3. Give the card a positioning context, commonly `position: relative`.
4. Position the overlay within the card using absolute positioning.
5. Set suitable dimensions, background or transparency, and stacking order for the overlay.
6. Scroll the page and verify the sticky navigation and card overlay in the browser.

## Example CSS
```css
.navbar {
  position: sticky;
  top: 0;
  z-index: 10;
}

.card {
  position: relative;
}

.card-overlay {
  position: absolute;
  inset: 0;
}
```

## Result
A sticky navbar and a positioned card overlay were implemented using CSS.

## Output Screenshot
See `screenshots/` for the browser output.
