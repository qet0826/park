# CSS Stylesheets

This folder contains the stylesheet files used by the **Game Finder** mini web project.
Each CSS file is assigned to a different part of the site and helps give each page group its own visual identity.

## Overview

The `css` directory includes three files:

- `H.css` – styles the **home page**
- `M.css` – styles the **category overview pages**
- `G.css` – styles the **genre/detail pages**

## File Descriptions

### `H.css`
Used for the main landing page, `Home.html`.

Main characteristics:
- Clean and simple layout for the first screen
- Center-aligned header and navigation
- Separate hover colors for each game category link
- Light-toned header background and highlighted intro section

This file is intended to make the home page feel like a simple navigation hub for the rest of the project.

### `M.css`
Used for middle-level category pages such as `Shooting.html` and `RPG.html`.

Main characteristics:
- Cyan header styling
- Wood-texture background image
- Table-based layout for category descriptions
- Strong section borders and simple hover effects
- Back button styling through the `.back` class

This stylesheet is designed for menu-style pages that introduce sub-genres before moving to more detailed content.

### `G.css`
Used for detailed genre pages such as `Classic.html`, `AOS.html`, `Bullet.html`, `FPS.html`, `TPS.html`, `MMORPG.html`, and `Rogue-like.html`.

Main characteristics:
- Metal-pattern background image
- White content blocks with colored borders
- Shared default link styles for external game links
- Additional classes such as `.R`, `.M`, `.TH`, and `.TM` for button and link variations
- Larger spacing in the navigation area for image-heavy content pages

This file acts as the shared visual style for pages that list specific games and reference links.

## Folder Structure

```text
css/
├── G.css
├── H.css
└── M.css
```

## Notes

- The project uses **plain HTML and CSS only**.
- Styles are separated by page role rather than combined into a single global stylesheet.
- Background images referenced in these stylesheets are stored in the sibling `img` folder.

## Suggested Improvement

For future maintenance, the project could be refactored into:
- one shared base stylesheet for common layout rules
- one stylesheet for page-specific themes
- more descriptive file names such as `home.css`, `category.css`, and `detail.css`

This would make the structure easier to understand for new contributors.
