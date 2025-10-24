# Tailwind CSS Components Documentation

A comprehensive collection of reusable UI components built with Tailwind CSS.

## Setup Instructions

### 1. Install Dependencies

```bash
npm install
```


### 2. Build CSS

For development (with watch mode):
```bash
npm run dev
```

For production (minified):
```bash
npm run build
```

### 3. Open the Documentation

Open `components.html` in your browser after building the CSS.

## Components Included

- **Layouts** - Container, Grid, Flexbox
- **Buttons** - Primary, Outline, Sizes, Groups
- **Cards** - Basic, Image, Profile, Pricing
- **Forms** - Inputs, Select, Textarea, Checkboxes, Radio
- **Navigation** - Horizontal nav, Breadcrumbs, Tabs, Pagination
- **Modals** - Interactive dialogs
- **Alerts** - Success, Info, Warning, Error
- **Badges** - Various styles and pill badges
- **Spinners** - Loading animations
- **Progress Bars** - Different sizes
- **Tables** - Styled data tables

## File Structure

```
PPW-Docs/
├── components.html       # Main documentation file
├── package.json          # Node.js dependencies
├── tailwind.config.js    # Tailwind configuration
├── src/
│   └── input.css         # Source CSS with Tailwind directives
└── dist/
    └── output.css        # Generated CSS (created after build)
```

## License

ISC
