# Changes

## 2026-11-03

### Added Pixelfront project
- New Projects card for Pixelfront (https://github.com/grrarrgh/pixelfront), a pixel-art desert RTS for Windows written in Python with pygame-ce.
- Covers derrick capture and base building, the unit design screen (armour/weapon/speed trade-offs), and infantry suppression, taken from the repo README.
- The repo has no icon (its art is all procedural), so the card uses a new hand-drawn 16×16 pixel-art tank, `assets/pixelfront.svg`, rendered with crisp pixels.
- The two project cards now sit in the same spaced grid as the experience cards.

## 2026-10-26 (deploy)

### deploy to git pages
- Added a `CNAME` file (`www.joeyng.net`) so GitHub Pages serves the site on the custom domain.
- DNS checked: `www` is a CNAME to `grrarrgh.github.io`, the bare domain has GitHub's four A records and redirects to `www`, and HTTPS works.

## 2026-10-26

### Rebuilt portfolio page
- Replaced the earlier draft of `index.html` with a new single-page portfolio based on the 2026 CV.
- Sections: intro, experience, projects, skills & tools, education & certification, contact.
- Light-hearted touches (mock bug report in the intro, "All tests passing" skills list); no inspirational quotes.
- Layout works on desktop and phone widths.

### Privacy
- No phone number, email address, location or referee details on the page.
- Contact section says details are available on request.

### Company logos and links
- Added local logo images in `assets/` for Kialo, Immersive Technologies, Murdoch University and ISTQB.
- Each company name and logo links to its website.
- Landsberry & James uses an "L&J" badge (no usable logo found), linked to https://www.lj-oz.com/.

### Experience
- Kialo role now covers both Kialo.com and Kialo-edu.com, the education version with teacher features and LMS integrations.

### Stats row
- Removed "8 simulator releases" and "50+ simulated machines"; kept "15+ years testing" and "3 companies".

### GitHub and projects
- Added a GitHub link (https://github.com/grrarrgh) to the menu and the contact section.
- New Projects section featuring Solo Clocktower (https://github.com/grrarrgh/solobotc), a single-player browser version of Blood on the Clocktower.
- The live game site is not linked yet, because https://www.solobotc.com does not currently load over https.

### Live game link
- https://www.solobotc.com is now live, so the Solo Clocktower project links to it ("Play it at solobotc.com") next to the GitHub link.
- The project logo is now Solo Clocktower's own icon (copied locally to `assets/solobotc.svg`) and links to the live game instead of GitHub.
