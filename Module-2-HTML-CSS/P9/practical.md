# P9: Responsive Navbar and Card Grid Using Flexbox

## Aim
To create a responsive navigation bar and card layout using CSS Flexbox.

## Concepts
Flexbox arranges items along a main axis and supports alignment, spacing and wrapping. Media queries can adjust the layout at different viewport widths.

## Procedure
1. Create the navigation links and a group of content cards in HTML.
2. Set the navbar container to `display: flex` and use alignment and spacing properties.
3. Set the card container to Flexbox and allow cards to wrap onto additional rows.
4. Give cards flexible widths or a suitable flex basis.
5. Add media queries to adjust navigation and card sizing on narrower screens, as appropriate.
6. Test the page at wide and narrow browser widths.

## Example CSS
```css
.navbar,
.card-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}

.navbar {
  align-items: center;
  justify-content: space-between;
}
```

## Result
A responsive navbar and wrapping card grid were created using Flexbox.

## Output Screenshot
See `screenshots/` for the browser output.
