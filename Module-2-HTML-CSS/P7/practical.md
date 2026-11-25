# P7: Design Tokens and Typography System in CSS

## Aim
To define reusable design tokens and establish a consistent typography system using CSS.

## Concepts
CSS custom properties store reusable values such as colours, spacing, font families and font sizes. Typography rules establish a consistent visual hierarchy for headings and body text.

## Procedure
1. Link an external stylesheet to the HTML page.
2. Define reusable CSS custom properties in `:root`.
3. Set the base font family, size, line height and text colour on the page.
4. Define consistent styles for headings, paragraphs, links and other text elements.
5. Reuse the custom properties throughout the stylesheet rather than repeating literal values.
6. Open the page in a browser and inspect the typography and consistency.

## Example CSS
```css
:root {
  --color-text: #222;
  --color-primary: #3157a4;
  --space-unit: 1rem;
  --font-body: Arial, sans-serif;
}

body {
  font-family: var(--font-body);
  color: var(--color-text);
  line-height: 1.6;
}
```

## Result
Reusable design tokens and a consistent CSS typography system were implemented.

## Output Screenshot
See `screenshots/` for the browser output.
