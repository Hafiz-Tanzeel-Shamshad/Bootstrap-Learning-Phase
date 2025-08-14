# Bootstrap-Learning-Phase 2
# Bootstrap Grid System Example

This project demonstrates Bootstrap 5's responsive grid system with various column layouts and breakpoint behaviors.

## Features

- **Grid Layout Examples**:
  - Basic fixed-width columns (`col-*`)
  - Responsive columns with breakpoints (`col-md-*`, `col-xl-*`)
  - Mixed breakpoint behaviors in the same row
  - Nested grid structure

- **Visual Indicators**:
  - Different background colors for each column
  - Sample Lorem Ipsum text content

## Breakpoints Demonstrated

1. **Extra Small (default)**: 
   - Columns stack vertically
   
2. **Medium (md ≥768px)**:
   - Columns become horizontal
   - 6-column layout for content sections
   
3. **Extra Large (xl ≥1200px)**:
   - 4-column layout for content sections
   - More space utilization on wide screens

## File Structure

- `index.html` - Contains all HTML markup demonstrating grid layouts
- Uses Bootstrap 5.3.2 via CDN

## Code Highlights

```html
<!-- Basic fixed columns -->
<div class="row">
    <div class="col-4 bg-body-secondary">one</div>
    <div class="col-3 bg-warning">one</div>
</div>

<!-- Responsive columns with multiple breakpoints -->
<div class="col-md-6 col-xl-4 bg-success">
    <!-- Content -->
</div>
```
