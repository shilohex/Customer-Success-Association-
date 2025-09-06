# Customer-Success-Association-

A responsive dog food landing page showcasing key features, a central circular image with overlays, a call-to-action button, and payment/guarantee logos, built with HTML and CSS using Flexbox.

---

## HTML Overview

- **Header**: `<h1>` displays the main title, centered for visibility.
- **Features Section**: `main-box` has three parts:

  - Left and right columns (`center-food`, `center-food2`) stack feature boxes vertically.
  - Center (`split`) shows main circle image with overlay images.

- **Feature Boxes**: Each `food-box1` contains an icon and text (`h3` + `p`) side by side.
- **CTA Button**: `main-button` centers a button to encourage user action.
- **Guarantee & Payments**: `cards` aligns a guarantee icon, text, and payment logos horizontally.

---

## CSS Overview

- **Global Reset**: `* { margin: 0; padding: 0; }` ensures consistent spacing.
- **Heading**: Flexbox centers the main title with specified font and size.
- **Features Layout**: Flex columns for stacking features, flex rows for icon-text alignment.
- **Circle & Overlays**: `split` container; `img1` main circle; `img2`/`img3` positioned absolutely for overlays.
- **Button**: Centered with padding, color, font, and border-radius.
- **Guarantee & Logos**: Flexbox aligns all elements horizontally, images maintain aspect ratio.

---

**Summary**: Flexbox is used throughout for layout and centering. HTML sections are clearly separated: header, features + circle, and CTA + payment. Overlay images are absolutely positioned around the main circle for visual effect.
