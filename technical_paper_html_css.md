# Technical Paper on HTML & CSS

## Introduction
HTML (HyperText Markup Language) and CSS (Cascading Style Sheets) form the fundamental building blocks of modern web development. HTML provides the structural skeleton of a webpage, while CSS handles its design, layout, and visual appearance.

## Box Model
The CSS Box Model defines how every HTML element is represented as a rectangular box:
- Content
- Padding
- Border
- Margin

## Inline vs Block Elements
### Block Elements
Examples: `div`, `p`, `h1`, `section`

### Inline Elements
Examples: `span`, `a`, `strong`, `img`

## CSS Positioning: Relative & Absolute
- **Relative**: Positioned relative to itself.
- **Absolute**: Positioned relative to nearest positioned ancestor.

## Common CSS Structural Classes
- `.container`
- `.row`
- `.column`
- `.wrapper`

## Common CSS Styling Classes
- `.text-center`
- `.btn`
- `.mt-*`
- `.bg-dark`

## CSS Specificity
Order of priority:
1. Inline
2. IDs
3. Classes
4. Elements

## CSS Responsive Queries
```css
@media (max-width: 768px) {
  .container { padding: 10px; }
}
```

## Flexbox
Key properties: `display:flex`, `justify-content`, `align-items`.

## CSS Grid
Key properties: `display:grid`, `grid-template-columns`, `gap`.

## Common Header Meta Tags
- `<meta charset="UTF-8">`
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`

## References
- https://developer.mozilla.org
- https://www.w3.org/TR/CSS
- https://css-tricks.com
