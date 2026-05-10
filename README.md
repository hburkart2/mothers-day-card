# Mother's Day Tribute | Digital Edition

An elegantly curated, single-page web experience designed as a professional digital tribute. This project prioritizes sophisticated typography, subtle motion design, and a minimalist aesthetic to create a premium greeting experience.

## Design Overview

The application utilizes a refined color palette of Deep Madder and Muted Gold, set against a Natural Cream parchment background.

- **Typography:** Leverages the high-contrast serifs of Playfair Display for headings and the clean, modern geometric lines of Lato for body text.
- **Vector Graphics:** Replaces standard iconography with custom SVG paths to ensure crisp rendering on high-density displays.
- **Atmospheric Motion:** A custom JavaScript-driven animation engine simulates falling floral petals using lightweight SVG elements, maintaining 60fps performance across mobile and desktop devices.

## Deployment Instructions

The project is architected as a self-contained, single-file application (`mothers-day-card.html`) for seamless deployment.

### Automated Deployment via GitHub Pages:

1.  **Repository Setup:** Commit `mothers-day-card.html` to a new or existing GitHub repository.
2.  **Naming Convention:** For a root-level URL, it is recommended to rename the file to `index.html`.
3.  **Activation:**
    - Navigate to `Settings` > `Pages` in your repository.
    - Under "Build and deployment," select the `main` branch.
    - Your tribute will be accessible at `https://[your-username].github.io/[repo-name]/`.

## Technical Specifications

- **File Format:** Standard HTML5 / CSS3 / Vanilla JavaScript.
- **Dependencies:** Zero external libraries; utilizes Google Fonts API for typography.
- **Responsive Engine:** Employs CSS Grid and Flexbox with a mobile-first approach to ensure compatibility with iOS and Android devices.

## Configuration

To modify the content or aesthetic, locate the following sections within `mothers-day-card.html`:

- **Visual Variables:** CSS Custom Properties located in the `:root` pseudo-class.
- **Message Content:** Text nodes within the `main-message` and `mini-card-message` classes.
- **Motion Timing:** The `CONFIG` object within the `<script>` block at the bottom of the document.

---
*Developed with precision for a sophisticated Mother's Day presentation.*
