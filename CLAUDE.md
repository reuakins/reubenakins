# Reuben Akins Music Website

## Overview
Static website to showcase Reuben Akins' music, performance dates, releases, and related content.

## Project Structure
```
/
├── index.html          # Landing page
├── styles/
│   └── main.css        # Styles (plain CSS with native nesting)
├── assets/
│   ├── bg.png          # Page background (optical pattern)
│   ├── text-bg.jpg     # Content panel background (teal texture)
│   ├── edd.gif         # Landing page graphic
│   └── cat.png         # Landing page graphic
├── pages/
│   ├── about.html      # About me page
│   ├── updates.html    # Updates/news page
│   ├── links.html      # Links page
│   └── photos.html     # Photos page
└── CLAUDE.md           # This file
```

## Design System

### Colors
- Navbar background: `#74211c` (dark red/maroon)
- Navbar text: `#ff751f` (orange)
- Body text: `#ffffff` (white)
- Page background fallback: `#a0a0a0` (gray)
- Content panel fallback: `#4a6670` (muted teal)

### Typography
- System fonts (simple stack)

### Responsive Breakpoints
- Desktop: Side-by-side graphics, full navigation
- Mobile (<768px): Stacked graphics, simplified inline navigation

## Development

No build step required - just edit files and refresh the browser.

To preview locally:
```bash
open index.html
# or use a local server:
npx serve .
```

## Future Plans
- Blog functionality (consider static site generator: Hugo, Jekyll, or 11ty)
- Performance dates calendar
- Music releases/discography
- Custom fonts
