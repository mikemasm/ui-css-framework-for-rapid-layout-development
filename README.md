# UI Framework for Rapid Layout Development

A lightweight, utility-first CSS framework designed for building modern user interfaces quickly and efficiently. This framework provides a comprehensive set of grid layouts and utility classes that help developers create responsive, maintainable applications with minimal custom CSS.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Features

- 🎯 **Utility-First Approach**: Comprehensive set of utility classes for rapid development
- 📱 **Responsive Grid System**: Flexible layouts from 2 to 5 columns with ratio options
- 🎨 **Extensive Utilities**: Spacing, typography, display, and positioning helpers
- 📦 **Zero Dependencies**: No JavaScript required, pure CSS solution
- 🚀 **Production Ready**: Optimized for performance and scalability
- ♿ **Accessibility Friendly**: Built with accessibility in mind



Include the css stylesheet directly in your HTML:

```html
<link rel="stylesheet" href="ui-css-framework-for-rapid-layout-development.css">
```

## Quick Start

1. Add the framework to your project
2. Start using utility classes in your HTML
3. Build responsive layouts instantly

```html
<div class="container">
  <!-- Basic two-column layout -->
  <div class="column-2">
    <div class="p-20">Column 1</div>
    <div class="p-20">Column 2</div>
  </div>
  
  <!-- Responsive grid with custom ratio -->
  <div class="grid-8-4">
    <div class="p-20">Main Content (66.66%)</div>
    <div class="p-20">Sidebar (33.33%)</div>
  </div>
</div>
```

## Grid System
### Basic Columns

- column-2: Two equal columns
- column-3: Three equal columns
- column-4: Four equal columns
- column-5: Five equal columns

## Ratio-based Grids

- grid-3-9: 25%/75% split
- grid-4-8: 33.33%/66.66% split
- grid-5-7: 41.66%/58.33% split
- grid-7-5: 58.33%/41.66% split
- grid-8-4: 66.66%/33.33% split
- grid-9-3: 75%/25% split

## Responsive Modifiers

```html
<!-- Element visible only on desktop -->
<div class="d-none d-block-d-up">Desktop only</div>

<!-- Center text on mobile -->
<div class="t-center-m">Centered on mobile</div>
```

- -m: Mobile styles
- -t: Tablet styles
- -d-up: Desktop and up
- -t-down: Tablet and down

## Utility Classes
### Spacing
```html
<!-- Margins -->
<div class="m-20">20px margin all around</div>
<div class="mt-20">20px margin top</div>

<!-- Padding -->
<div class="p-20">20px padding all around</div>
<div class="pt-20">20px padding top</div>
```

### Display
```html
<div class="d-none">Hidden</div>
<div class="d-flex">Flex container</div>
<div class="d-grid">Grid container</div>
```

### Typography
```html
<h1 class="h1">Heading 1</h1>
<p class="fw-500">Medium weight text</p>
<div class="t-center">Centered text</div>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License
This project is licensed under the MIT License - see the LICENSE file for details.