# P12: Portfolio Projects Grid with Advanced CSS Grid

## Aim
To display portfolio projects in a structured grid using advanced CSS Grid features.

## Concepts
CSS Grid supports flexible tracks, `repeat()`, `minmax()`, `auto-fit` or `auto-fill`, and item spanning. These features help create adaptable project galleries.

## Procedure
1. Create a projects section containing project cards.
2. Set the projects container to `display: grid`.
3. Define responsive columns using suitable grid track functions.
4. Set row and column gaps for consistent spacing.
5. Use grid placement or spanning where the design requires a card to occupy additional tracks.
6. Test the grid at different viewport widths.

## Example CSS
```css
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.25rem;
}
```

## Result
A portfolio projects gallery was arranged using advanced CSS Grid techniques.

## Output Screenshot
See `screenshots/` for the browser output.
