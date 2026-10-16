# T3C Gardens — Main Website

An independent, responsive information website for T3C Gardens in Lilayi, Lusaka. It is a static HTML, CSS and JavaScript project with no backend, dependencies, package manager or build step.

The digital menu remains a separate project and is linked at <https://t3cgardens.github.io/menu/>. This site does not copy or render menu data.

## Project structure

```text
.
├── index.html
├── css/
│   └── style.css
├── js/
│   └── app.js
├── assets/                # Copies of selected T3C Gardens photos
└── README.md
```

## Run locally

Open `index.html` directly, or start a local static server in this folder:

```powershell
py -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy independently

The project can be published from its own repository or uploaded to any static host. Keep `index.html` at the published root and include the `css/`, `js/` and `assets/` folders. There is no build command. For GitHub Pages, create a separate repository for this folder, push the project files, and select the repository root as the Pages publishing source. The existing menu repository and its deployment settings are not part of this project.

## Content and assets

The top hero uses browser-compatible JPEG versions of `hero-gardens`. Its source is HEIC data stored in the menu project under a `.jpg` filename. The source file is unchanged. The wide crop is selected at viewport widths of 901px and above; the portrait version is used below that breakpoint. The wide version is also the Open Graph preview image.

Photo placements follow the areas shown: `pontoon.JPG` for Lilayi 1, `bliss.jpg` for Bonfire Gardens, `scenes.jpg` for the Main Events Garden, and `views.jpg` for the Main House. The gathering section uses `pontent.JPG`, showing an event tent beside the pond. The food and bar feature uses `bar.jpg`, a lounge photo, rather than a menu food image. The gallery uses `trees.jpg`, `bridge.jpg`, `drinking.jpg` and `events1.jpg`; the drinking photo is top-aligned in its tile to keep guests' faces and glasses in view when cropped. The separate menu project and its other assets are not modified.

Contact and social links match the existing menu's configured business details. Accommodation rates, availability and booking arrangements are intentionally left to direct enquiry. Opening times and event packages are not stated as confirmed facts.

To update the site, edit `index.html` for content, `css/style.css` for appearance and `js/app.js` for the small-screen navigation. Keep the relative file paths intact when publishing.
