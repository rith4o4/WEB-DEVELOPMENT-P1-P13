# P11: Newspaper-Style Three-Column Layout with CSS Grid

## Aim
To create a newspaper-style page with a three-column layout using CSS Grid.

## Concepts
CSS Grid is a two-dimensional layout system. `grid-template-columns` defines columns, `gap` creates spacing, and grid placement properties control where items appear.

## Procedure
1. Create the page regions, such as a masthead, main story, secondary stories and side content.
2. Define a grid container using `display: grid`.
3. Set up three columns using `grid-template-columns` and add suitable gaps.
4. Place articles in the intended columns or spans.
5. Use media queries to simplify the layout on narrower screens if required.
6. Open the page in a browser and verify the three-column arrangement.

## Example CSS
```css
.news-layout {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
}
```

## Result
A newspaper-style three-column layout was created using CSS Grid.

## Output Screenshot
See `screenshots/` for the browser output.
