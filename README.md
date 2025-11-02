# Crystal UI

Lightweight CSS library for building modern web interfaces with pure HTML and CSS. No React or JavaScript framework required.

**📖 [View Documentation](https://crystal-ui.com/)**

## Installation

Download the `crystal-ui.css` file from this repository and include it in your HTML:

```html
<link rel="stylesheet" href="crystal-ui.css" />
```

## Quick Start

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="crystal-ui.css" />
  </head>
  <body>
    <button class="cui-btn cui-btn--primary">Click me</button>
  </body>
</html>
```

## Features

- ✨ **Pure CSS** - No JavaScript required
- 🎨 **Modern Design** - Beautiful, accessible components
- 📦 **Lightweight** - Single CSS file
- 🌓 **Theming** - Built-in light and dark theme support
- 📱 **Responsive** - Mobile-first design

## Component Examples

Here are some basic examples of Crystal UI components. All styles are included in `crystal-ui.css`.

### Button

```html
<button class="cui-btn cui-btn--primary">Button</button>
<button class="cui-btn cui-btn--outline">Outline</button>
<button class="cui-btn cui-btn--ghost">Ghost</button>
<button class="cui-btn cui-btn--link">Link</button>
```

### Input

```html
<div class="cui-input-field">
  <label class="cui-label" for="email">Email</label>
  <input type="email" id="email" class="cui-input" placeholder="name@example.com" />
</div>
```

### Badge

```html
<div class="cui-badge">Badge</div>
<div class="cui-badge cui-badge--secondary">Secondary</div>
<div class="cui-badge cui-badge--destructive">Destructive</div>
<div class="cui-badge cui-badge--outline">Outline</div>
```

### Switch

```html
<label class="cui-switch-label">
  <input type="checkbox" class="cui-switch-input" />
  <span class="cui-switch">
    <span class="cui-switch-thumb"></span>
  </span>
  <span class="cui-switch-text">Airplane Mode</span>
</label>
```

### Card

```html
<div class="cui-card">
  <div class="cui-card-header">
    <h3 class="cui-card-title">Card Title</h3>
    <p class="cui-card-description">Card description goes here.</p>
  </div>
  <div class="cui-card-content">
    <p>Your content here.</p>
  </div>
  <div class="cui-card-footer">
    <button class="cui-btn cui-btn--primary">Action</button>
  </div>
</div>
```

### Table

```html
<div class="cui-table-container">
  <table class="cui-table-base">
    <thead>
      <tr>
        <th class="cui-table-base-header">Invoice</th>
        <th class="cui-table-base-header">Status</th>
        <th class="cui-table-base-header cui-table-base-header--right">Amount</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="cui-table-base-cell">INV001</td>
        <td class="cui-table-base-cell">Paid</td>
        <td class="cui-table-base-cell cui-table-base-cell--right">$250.00</td>
      </tr>
    </tbody>
  </table>
</div>
```

## Components

- Accordion
- Alert & Alert Dialog
- Badge
- Breadcrumb
- Button & Button Group
- Calendar
- Card
- Checkbox
- Combobox
- Command
- Data Table
- Date Picker
- Dialog
- Empty
- Hover Card
- Input & Input Group & Input OTP
- Item
- Label
- Menubar
- Navigation Menu
- Pagination
- Scroll Area
- Select
- Sonner (Toast)
- Spinner
- Switch
- Table
- Tabs
- Textarea
- Toggle Group
- Typography

## Documentation

To view the complete documentation, examples, and guides:

1. Download the `React-App-Documentation` folder from this repository
2. Navigate to the `React-App-Documentation` directory
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open your browser and visit the local development URL (usually `http://localhost:5173`)

## Browser Support

Modern browsers (Chrome, Firefox, Safari, Edge) with CSS custom properties support.

## License

MIT License

Copyright (c) 2025 Denys Zhodik

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
