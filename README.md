# Bootstrap-Learning-Phase 3
# 📐 Bootstrap Vertical Alignment 

This HTML file demonstrates Bootstrap 5's vertical alignment utilities for grid columns.

## 🎯 Key Features

- **📏 Vertical Alignment**:
  - `align-items-end` on row (aligns all columns to bottom) ⬇️
  - `align-self-start` on individual column (overrides row alignment) ⬆️
  
- **📱 Responsive Grid**:
  - Equal-width columns using `col` class ↔️
  - Automatic column wrapping 🔄

- **🎨 Visual Indicators**:
  - Color-coded columns (✅ success, ⚠️ warning, ❌ danger)
  - Placeholder text content 📝

## 💻 Code Breakdown

```html
<div class="row align-items-end">
    <div class="col bg-success">...</div>
    <div class="col bg-warning align-self-start">...</div>
    <div class="col bg-success">...</div>
    <div class="col bg-danger">...</div>
</div>
```
## 📦 Dependencies

- **Bootstrap 5.3.2** (loaded via CDN) 🚀

