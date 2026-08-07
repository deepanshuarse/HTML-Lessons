# CSS Grid

Today I learned about CSS Grid and practiced some basic grid layouts.

## What I learned

- `display: grid` is used to make a grid.
- `grid-template-columns` is used to set the columns.
- We can give columns fixed sizes like `100px`, `200px`, etc.
- `1fr` means one part of the available space.
- `1fr 1fr 1fr` makes 3 equal columns.
- `1fr 2fr` means the second column gets twice the space of the first one.
- `column-gap` gives space between columns.
- `row-gap` gives space between rows.

## Example

```css
display: grid;
grid-template-columns: 100px 1fr 2fr;
column-gap: 20px;
row-gap: 40px;
```

## Practice

I practiced:
- Fixed width columns
- `fr` unit
- Equal columns
- Column and row gaps
- Multiple rows using CSS Grid
