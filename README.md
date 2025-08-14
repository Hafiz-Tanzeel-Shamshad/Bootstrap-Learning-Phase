# Bootstrap-Learning-Phase 4
# 📝 Bootstrap Form Demo


This HTML file showcases various Bootstrap 5 form components and layouts.

## 🏗️ Form Components

- **📧 Input Fields**:
  - Email text input ✉️
  - Password input 🔒
  - Address input (small size) 🏠

- **🌆 Dropdown Select**:
  - Large size select box (`form-select-lg`) 📏
  - City options (Mumbai, Delhi, Pune) 🏙️

- **✅ Checkboxes**:
  - Regular checkbox ☑️
  - Bootstrap-styled checkbox (`form-check`) ✅
  - Toggle switch (`form-switch`) 🔄

## 📱 Responsive Layout

- **2-column layout on medium screens**:
  - Email and password fields side-by-side (`col-md-6`) ↔️
  - Stacks vertically on mobile 📲

## 🎨 Styling Features

- Form control sizing:
  - Regular inputs
  - Small address input (`form-control-sm`)
  - Large select (`form-select-lg`)

- Proper spacing with `mb-3` margins 📏

## 💻 Code Snippets

```html
<!-- Responsive 2-column layout -->
<div class="row">
    <div class="col-md-6">
        <label for="email">Email</label>
        <input type="text" class="form-control" placeholder="Email" id="email">
    </div>
    <div class="col-md-6">
        <label for="password">Password</label>
        <input type="password" class="form-control" placeholder="password" id="password">
    </div>
</div>

<!-- Toggle switch example -->
<div class="form-check form-switch">
    <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault">
    <label class="form-check-label" for="flexSwitchCheckDefault">Default switch checkbox input</label>
</div>
```
## 🛠️ Setup & Usage

1. Open `index.html` in any browser 🌐

2. Try all form controls:

   - Fill in text fields ✍️
   - Select from dropdown 🔽
   - Toggle checkboxes and switches ↔️

