![HostCorps](/img/HostCorps.png)

# HostCorps

Website of a fictional hosting provider company. Built with HTML5, CSS3 and vanilla JavaScript. The webApp can be acessed [here](https://nothingnothings.github.io/HostCorps). This version of the app was made without Webpack; the Webpack version, with a GitHub Actions deployment workflow, can be found [here](https://github.com/nothingnothings/HostCorpsWebpackVersion).

## Technologies

Some of the Languages and Libraries employed:

- HTML5
- CSS3 (animations, Flexbox, media queries)
- Vanilla JavaScript (no JavaScript frameworks; usage of `var`, normal functions and common eventListeners)
- Form validation logic (basic input validation, logic for adding and removing "focus" and "invalid" styles, etc)
- Responsive mobile design (sidebar, Flexbox, media queries)

## Project Directory Structure


As seen in the `master` and `gh-pages` branches:

```
.\
│
├── customers\
│   ├── customers.css
│   └── index.html
│
├── fonts\
│   ├── UniSansHeavyCAPS.woff
│   ├── UniSansHeavyCAPS.woff2
│   ├── anonymousPro-Bold.ttf
│   └── anonymousPro-Regular.ttf
│
├── img\
│   ├── HostCorps.png
│   ├── HostCorps.svg
│   ├── customer-1.jpg
│   ├── customer-2.jpg
│   ├── customer-3.jpg
│   └── freedom.jpg
│
├── packages\
│   │
│   ├── images\
│   │   └── plan.jpg
│   │
│   ├── index.html
│   └── packages.css
│
├── start-hosting\
│   ├── index.html
│   ├── start-hosting.css
│   └── start-hosting.js
│
├── .gitignore
├── README.md
├── android-chrome-192x192.png
├── android-chrome-512x512.png
├── apple-touch-icon.png
├── browserconfig.xml
├── favicon-16x16.png
├── favicon-32x32.png
├── favicon.ico
├── index.html
├── mstile-150x150.png
├── safari-pinned-tab.svg
├── shared.css
├── shared.js
├── site.webmanifest
└── style.css
```


## Setup

To use this project, clone it using Git:

1. Run `git clone` to clone the project into your local Git repository
2. Serve the files with the help of a hosting provider (frontend-only)

## Features

- Multiple pages (different HTML pages, normal page serving)
- Form validation logic in the "Start Hosting" page
- Responsive design (mobile and desktop) created with Flexbox and media queries
- Addition/removal of CSS classes ("slide-in" animation) implemented with JavaScript

## Inspiration

Inspired by the "JavaScript - The Complete Guide" course by Maximilian Schwarzmüller.
