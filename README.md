# Webflow Mindmap Navigation

Interactive mindmap navigation component for Webflow integration.

## Setup

1. The mindmap is hosted using GitHub Pages
2. Embed the mindmap URL in your Webflow site using an embed element
3. Configure the site structure in the code to match your Webflow pages

## Configuration

Edit the `siteStructure` object in `index.html` to match your Webflow site structure:

```javascript
const siteStructure = {
  id: 'root',
  label: 'Home',
  path: '/', // Replace with your homepage URL
  children: [
    // Add your site pages here
  ]
};
```

## Usage

- Click nodes to navigate
- Use +/- buttons or mouse wheel to zoom
- Click and drag to pan
- Use the Reset View button to return to the initial state
