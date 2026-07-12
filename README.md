# ozmacalafiasystem.org Website Build

The internet-anchor for THE_&#91;SYSTEM&#93;_ARCHIVE core text.


## Repository Composition
* `index.html` - Root interface.
* `THE_[SYSTEM]_ARCHIVE.V1.A4.PORTRAIT.pdf` - Core text payload (standard portrait format).
* `THE_[SYSTEM]_ARCHIVE.V1.A4.BOOKLET.pdf` - Core text payload (foldable booklet format).
* `page_1.jpg` through `page_27.jpg` - Document page images.
* `a4-front-cover.jpg` & `a4-back-cover.jpg` - Cover art.


## Getting Started

**Step 1: Clone the repository**
```bash
git clone https://github.com/OzmaCalafia/ozmacalafiasystem.org-website-build.git
```

**Step 2: Enter the directory**
```bash
cd ozmacalafiasystem.org-website-build
```

### Execution Protocol

Ensure your terminal is currently operating inside the cloned directory before proceeding.

**method a: direct file validation**
Render the site locally without a network environment.
* Open your computer's file manager, navigate to the cloned folder, and open `index.html` in your browser.

**method b: local server validation**
Simulate a live hosting environment to test network routing.

Step 1: Execute the server command in your terminal:
```bash
python3 -m http.server 8000
```

Step 2: Open your web browser and navigate to this local address:
`http://localhost:8000`

Step 3: Terminate the server when testing is complete:
Press `Ctrl + C` in your terminal to shut down the server and free up the port.


## Visual Assets
* `animated-sigil.svg` , `animated-sigil.gif` & `sigil-white-on-transparent.png` - &#91;SIGIL&#93; media.
* `oc-logo-black.png` & `oc-logo-white.png` - Ozma Calafia---&#91;OC&#93;---brand signatures.
* `favicon.ico` - &#91;SIGIL&#93; smart-contrast favicon for browser interfaces.
