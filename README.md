# Biccas - Landing Page Dashboard.

Biccas is a modern and responsive landing page for a SaaS productivity and task management product. The project is built using only HTML and CSS, with no external framework dependencies.

## Project Features.

- **Modern Design**: Clean and professional interface with a green and dark color scheme.
- **Fully Responsive**: Adaptable to desktop, tablet, and mobile devices.
- **Sections Included**:
  - Header/Navigation with menu and authentication buttons.
  - Hero Section with main call to action.
  - Section with logos of collaborating companies.
  - Support and benefits section.
  - Features with functionality cards.
  - List of benefits with checklist.
  - Complete footer with multiple columns.

## Technologies Used.

- **HTML5**: Semantic document structure.
- **CSS3**: Styles with CSS variables, Flexbox, and Grid Layout.
- **Google Fonts**: ‘Inter’ typography for optimal readability.
- **No Frameworks**: Developed with native CSS for maximum control and learning.

## Color Palette.

| Color | Value | Use |
|-------|-------|-----|
| Primary | `#54BD95` | Main buttons, accents |
| Secondary | `#191A15` | Dark text, backgrounds |
| Text Gray | `#A6A6A6` | Secondary text |
| Background Light | `#F9F9F9` | Section backgrounds |
| Footer Background | `#161C28` | Footer background |

## Responsive Design

The project includes three main breakpoints:

- **Desktop**: ≥ 1024px - Full layout with multiple columns.
- **Tablet**: 768px - 1023px - Adaptation to one column.
- **Mobile**: ≤ 767px - Layout optimized for small screens.

## How to Use.

1. **View the project:**
   - Open the `index.html` file in your preferred web browser.
   - Or drag the file directly to a browser tab.

2. **Edit the project:**
   - Use any code editor (VS Code, Sublime Text, Atom, etc.).
   - Recommended: VS Code with Live Server extensions.

3. **Customize**:
   - Modify `style.css` to change colors, typography, or spacing.
   - Edit `index.html` to modify content or add sections.

## Detailed Sections.

### Header.
Fixed navigation with logo, navigation menu, and Login/Sign Up buttons.

### Hero.
Main title with product description and two CTAs (Try free trial, View Demo).

### Logos.
Logos of well-known companies (Unsplash, Notion, Intercom, Descript, Grammarly) that generate trust.

### Support.
Grid divided with company ratings and valuable features (Publishing, Analytics, Engagement).

### Features.
Three main cards: Collaboration Teams, Cloud Storage, Daily Analytics.

### Benefits.
List of benefits with checkmarks + illustrative image of the workspace.

### Footer.
Four columns with support, help, solutions, and product information.

## Customization.

### Change Colors.
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #54BD95;
    --secondary-color: #191A15;
    /* ... other variables */
}
```

### Add New Sections-
1. Copy the structure of existing sections.
2. Add the corresponding class in CSS.
3. Maintain consistency with the overall design.

## Project Structure.

```
HTML Ds/PTS Biccas/
├── index.html         # Main page
├── style.css          # CSS styles
├── README.md          # Documentation
├── reference.png      # Project preview
└── img/               # Multimedia resources
    ├── biccas-logo.png
    ├── biccas-dashboard.png
    ├── biccas-icon-play.png
    ├── benefits-workspace.png
    ├── feature-analytics.png
    ├── feature-cloud.png
    ├── feature-collaboration.png
    ├── icon-analytics.png
    ├── icon-check.png
    ├── icon-engagement.png
    ├── icon-publishing.png
    ├── logo-descript.png
    ├── logo-grammarly.png
    ├── logo-intercom.png
    ├── logo-notion.png
    ├── logo-unsplash.png
    └── ... (more icons and images)
```