# NETLIX-FRONT-END-PROJECT
A static Netflix landing page clone built using HTML and CSS. Includes hero section, email signup, trending movies, feature cards, FAQ section, and a clean dark UI. Layout is fully custom-designed with positioned elements and styled sections to recreate the Netflix homepage look.
Features

Dark-themed hero banner with large Netflix-style title and tagline.

Top controls: language selector and Sign In button.

Email signup call-to-action in hero and at page bottom.

"Trending Now" thumbnails section.

"More reasons to join" feature cards highlighting:

Watch on TV and devices

Download to watch offline

Watch everywhere on multiple devices

Kids profiles

Frequently Asked Questions (FAQ) style boxes.

Pure HTML and CSS (no frameworks, no JS).

Files / Project Structure
/netflix-clone/
├─ index.html        # Main HTML file (the code you provided)
├─ styles.css?       # (Optional) Extract inline styles into this file if you prefer
├─ front img.jpg     # Hero background image
├─ Screenshot 2025-10-31 145810.png  # Trending thumbnail (example)
├─ img1.png
├─ img2.png


Accessibility & Improvements (Suggested)

The current file is a visual prototype — to improve accessibility, responsiveness, and maintainability consider these changes:

Replace visual-only elements with semantic HTML

Use <header>, <nav>, <main>, <section>, <footer>.

Replace <p> used as buttons/inputs with real <button>, <input> and <form> elements.

Make it responsive

Remove absolute positioning for large sections; use Flexbox / CSS Grid.

Add media queries for mobile/tablet breakpoints.

Use relative units (em, rem, %) instead of fixed pixel/rem-based top positioning.

Accessibility

Provide meaningful alt text for images.

Ensure color contrast (text on dark backgrounds) meets WCAG.

Add aria-* attributes for interactive elements and keyboard focus styles.

Performance

Optimize images (resize/compress) and use modern formats (webp) where possible.

Lazy-load non-critical images with loading="lazy".

Interactivity

Add JavaScript for dynamic FAQ expand/collapse, sliders, and real email form handling.
├─ img3.png
├─ img4.png
└─ README.md
