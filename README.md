# Equality4All Hub

A small evidence-first argument hub for topics involving racism, Palestine, occupation, rights, and global injustice.

This repository is the **main hub site**, not the original Netlify racism site. The racism page is kept separate because the Netlify version contains the working “ask me questions” form.

## Live Pages

Main hub:

```text
https://yanxii15.github.io/equality4all-hub/
```

Palestine arguments page:

```text
https://yanxii15.github.io/equality4all-hub/palestine.html
```

Racism argument page with working Netlify form:

```text
https://equality4all.netlify.app/
```

If the GitHub repo name changes, the GitHub Pages links will also change.

## Purpose

The aim of this project is to organise arguments clearly instead of leaving them scattered across messages, debates, or notes.

The site is built around one standard:

> If a principle only works when it protects one side, it is not a principle. It is decoration.

The pages are written to be readable, structured, and easy to reference. They are not meant to be noise, slogans, or rage-posting. They are meant to make arguments easier to inspect.

## Pages

### `index.html`

The main hub page.

Features:

* Realistic rotating globe using map data.
* Pulsing location markers for Palestine, Myanmar, Congo, and racism/global injustice.
* Light and dark mode toggle.
* OpenDyslexic base font for easier reading.
* Links to the Netlify racism page and the Palestine page.

### `palestine.html`

A structured Palestine argument page.

It covers:

* Palestinian self-determination.
* Occupation.
* Settlements.
* Gaza.
* Civilian harm.
* Common counterarguments.
* The difference between criticism of Israel and antisemitism.
* Why legal and moral standards should be applied consistently.

### External racism page

The racism page is currently hosted separately on Netlify:

```text
https://equality4all.netlify.app/
```

That page is intentionally kept outside this repo because it contains the working Netlify contact/question form.

Do not replace that Netlify-connected repo unless you are intentionally changing the racism site.

## Tech Used

This project uses:

* HTML
* CSS
* JavaScript
* D3.js for the globe projection
* TopoJSON / world-atlas map data
* OpenDyslexic font
* GitHub Pages for hosting

Useful references:

* D3 Geo: https://d3js.org/d3-geo
* world-atlas: https://github.com/topojson/world-atlas
* Natural Earth map data: https://www.naturalearthdata.com/
* GitHub Pages: https://docs.github.com/en/pages
* OpenDyslexic: https://opendyslexic.org/

## File Structure

```text
equality4all-hub/
├── index.html
├── palestine.html
└── README.md
```

Optional future structure:

```text
equality4all-hub/
├── index.html
├── palestine.html
├── topics/
│   ├── congo.html
│   ├── myanmar.html
│   └── colonialism.html
├── assets/
│   ├── images/
│   └── fonts/
└── README.md
```

## Deployment

This site is intended to be hosted with GitHub Pages.

To deploy:

1. Create a new public GitHub repository.
2. Upload `index.html`, `palestine.html`, and `README.md`.
3. Go to the repository settings.
4. Open **Pages**.
5. Set the source to **Deploy from branch**.
6. Choose the `main` branch.
7. Choose `/root`.
8. Save.

After deployment, GitHub Pages should publish the site at:

```text
https://your-username.github.io/repo-name/
```

For example:

```text
https://yanxii15.github.io/equality4all-hub/
```

## Important Netlify Warning

The Netlify racism page is separate.

Do not upload this hub over the old `equality4all` repo if that repo is still connected to Netlify.

Recommended setup:

```text
Repo 1:
equality4all
Purpose: racism page + working Netlify form

Repo 2:
equality4all-hub
Purpose: globe homepage + Palestine page
```

This prevents the Netlify form from breaking.

## Content Approach

The project tries to follow these rules:

* Define terms before arguing.
* Separate law, history, morality, and rhetoric.
* Use sources where possible.
* Avoid emotional shortcuts when the evidence is enough.
* Apply standards consistently, even when inconvenient.
* Make arguments readable for people who are not already familiar with the issue.

## Accessibility

Current accessibility choices:

* Light/dark mode toggle.
* OpenDyslexic base font.
* High-contrast colours.
* Large buttons.
* Clear page structure.
* Reduced visual clutter compared with normal debate-post formats.

Future improvements could include:

* Reduced-motion toggle.
* More keyboard navigation testing.
* Better mobile globe scaling.
* Source list section at the bottom of each topic page.
* Printable/reference version of each argument page.

## License

Copyright © 2026  GatesOfJoy. All rights reserved.

This repository contains two categories of material:

1. Website source code, design, layout, CSS, JavaScript, and structure.
2. Written arguments, essays, debate notes, explanations, and original commentary.

### Website Code

No license is granted for the website source code, design, layout, CSS, JavaScript, or structure.

You may not copy, modify, redistribute, sublicense, sell, or use this code in another project without written permission from the copyright holder.

### Written Content

The written arguments, essays, debate notes, explanations, and original commentary are licensed under:

**Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International
CC BY-NC-ND 4.0**

You may share or reference the written content if:

* You give clear credit to  GatesOfJoy.
* You link back to the original website or repository where possible.
* You do not use it for commercial purposes.
* You do not distribute modified, remixed, or rewritten versions as if they are your own.

Sources, quotations, citations, map data, libraries, and external references remain the property of their respective owners.

## Credits

Created by  GatesOfJoy

Map rendering uses D3.js and public world map data derived from Natural Earth through the world-atlas project.
