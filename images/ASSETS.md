Available image/icon filenames and where to place your custom files

- bg.svg (or bg.jpg/png): page background image — replace `images/bg.svg` with your background image; transparency controlled in `styles.css` via `--bg-opacity`.
- caspam.svg: CASPAM logo (used in header and corner-left)
- bzu.svg: BZU logo (used in corner-right)
- home.svg, about.svg, faculty.svg, courses.svg, labs.svg, contact.svg, gallery.svg: icons for the navigation links — place matching SVG/PNG files here.
- icon-left.svg, icon-right.svg: small decorative icons used near Advanced--- line.
- lab1.jpg, lab2.jpg, event.jpg: sample photos used in labs/gallery — replace with your real photos.

HTML snippet for nav (use inside `.main-nav`):

<a class="link-button" href="index.html"><img src="images/home.svg" class="nav-icon" alt="Home">Home</a>

Notes:
- To change background image opacity, edit `--bg-opacity` in `styles.css` (0 = fully transparent, 1 = fully opaque). The current setting is 0.3 (70% transparent).
- Prefer SVG for crisp icons; PNG/JPG is fine for photos.

