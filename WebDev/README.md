# KithyaSite - Personal Portfolio Website

**KithyaSite** is a responsive, modern personal portfolio website designed to showcase Kithya Tes’s background, skills, projects, education, achievements, and hobbies. Built using HTML and CSS, this project demonstrates proficiency in web development fundamentals, including layout techniques, responsive design, and interactivity.

---

## Project Overview

This portfolio serves as a digital resume, highlighting Kithya Tes’s journey as a Software Development student at the American University of Phnom Penh. Each page is crafted with specific design goals, leveraging CSS Grid, Flexbox, and responsive techniques to ensure accessibility across devices.

---

## Features by Page

### 1. Home Page
- **Purpose**: Welcomes visitors with an overview of Kithya’s profile.
- **Layout**: CSS Grid divides the page into navigation, main content (hero + features), and footer.
- **Hero Section**: Features a responsive `<picture>` element with an absolutely positioned overlay for text.
- **Interactivity**: Navigation links use `:hover` and `:focus` for visual feedback.
- **Responsiveness**: Media queries adjust layout and font sizes at 1280px, 800px, and below.
- **Mobile**: Includes viewport meta tag for compatibility.

### 2. About Page
- **Purpose**: Shares Kithya’s bio and goals in a clean format.
- **Layout**: Assumed two-column design using Flexbox (based on prior sample, not fully detailed here).
- **Positioning**: Lacks `position: fixed` for a sticky bio/image (to be added).
- **Stacking**: No explicit `z-index` usage in provided files; could enhance with overlays.
- **Responsiveness**: Uses Grid/Flexbox with media queries (assumed from prior context).

### 3. Projects Page
- **Purpose**: Displays Kithya’s projects in an interactive grid.
- **Layout**: CSS Grid with `repeat(auto-fit, minmax(650px, 1fr))` for responsive columns.
- **Images**: Responsive `<picture>` elements with `srcset` for project visuals.
- **Interactivity**: Project buttons use `:hover`, `:focus`, and `:active` for effects.
- **Positioning**: Absolute `project-tag` labels enhance visual hierarchy.
- **Effects**: Hover transforms cards and scales images.

### 4. Skills Page
- **Purpose**: Visualizes technical and soft skills with progress bars.
- **Layout**: Flexbox organizes skills into two columns within `skill-box` containers.
- **Icons**: CSS sprites (`skill-sprites-svg.svg`) for Python, Java, etc.
- **Responsiveness**: Collapses to single-column at 800px via media queries.
- **Interactivity**: Hover effects on progress bars reveal percentages.

### 5. Contact Page
- **Purpose**: Offers a form and contact details for outreach.
- **Layout**: Flexbox aligns form and footer content (based on prior sample).
- **Positioning**: Relative positioning manages form field spacing.
- **Styling**: Links use `:hover` for underlines; buttons assumed styled similarly.
- **Responsiveness**: Media queries adjust layout at 800px.
- **Print**: Assumed `@media print` styles for clean output (from prior context).

### 6. Education & Certifications Page
- **Purpose**: Lists academic and certification achievements.
- **Layout**: Grid with `repeat(auto-fit, minmax(300px, 1fr))` for side-by-side sections.
- **Icons**: CSS sprites (`sprite-image-svg.svg`) for education and certificates.
- **Timeline**: Flexbox positions degree/certification details.
- **Responsiveness**: Single-column layout at 800px via media queries.
- **Positioning**: `section-tag` uses `position: absolute` for decoration.

### 7. Achievements & Awards Page
- **Purpose**: Highlights milestones with a polished layout.
- **Layout**: Assumed Grid/Flexbox (based on prior sample, not fully detailed here).
- **Positioning**: Relative/absolute positioning assumed for visual impact.
- **Interactivity**: Links use `:hover` (assumed from prior context).
- **Print**: Assumed print-friendly styles with `@media print`.
- **Responsiveness**: Media queries assumed for adaptability.

### 8. Hobbies & Interests Page
- **Purpose**: Showcases personal interests with creative design.
- **Layout**: Grid with `repeat(auto-fill, minmax(320px, 1fr))` for hobby cards.
- **Images**: Responsive `<picture>` elements with `srcset` for hobby visuals.
- **Icons**: CSS sprites (`hobby-sprites.svg`) for science, gaming, etc.
- **Positioning**: `hobby-icon` uses `position: absolute` with `z-index` for overlays.
- **Interactivity**: Hover effects rotate icons and scale images.

---

## Technical Details

- **Languages**: HTML5, CSS3.
- **Frameworks/Libraries**: Font Awesome 6.0.0 for icons (via CDN).
- **Techniques**:
  - **CSS Grid**: Structural layout for all pages.
  - **Flexbox**: Alignment and spacing within sections.
  - **CSS Sprites**: Efficient icon management (e.g., `skill-sprites-svg.svg`, `hobby-sprites.svg`).
  - **Pseudo-Classes**: `:hover`, `:focus`, `:active` for interactivity.
  - **Media Queries**: Breakpoints at 1280px, 800px, and 480px for responsive design.
  - **Positioning**: Relative, absolute, and fixed (where specified).
- **Assets**: Images in `picture/` and `images/` directories; sprite SVGs for icons.

---

### Prerequisites
- A web browser (e.g., Chrome, Firefox).
- Git (installed and configured).
- Internet connection (for Font Awesome CDN).
