# Sandwich Lab

An illustrated, detailed field guide to making a sandwich. Buildless HTML, CSS and JavaScript, with original SVG illustrations. No external assets, dependencies, analytics or API keys.

## Features

- Original classic turkey-and-cheddar recipe and vegetarian avocado variation.
- Ingredient quantities for 1–4 sandwiches.
- Interactive eight-layer exploded diagram with layer explanations and assembly slider.
- Six detailed preparation steps, each with an illustration and completion checkbox.
- Ingredient-weight bar chart, derived from this guide's approximate recipe quantities.
- Clearly labelled estimated eight-minute preparation timeline for one sandwich.
- Troubleshooting, linked cooking references, printable layout, keyboard controls, mobile layouts and reduced-motion support.

The recipe quantities and timings are original estimates, not nutritional measurements or experimentally established cooking times. General construction and moisture tips are informed by the two linked sources on the page. The recipe uses ready-to-eat turkey and requires no cooking.

## Run locally

Run `python3 -m http.server 8000` in this folder and open `http://localhost:8000`.

## Publish

In GitHub **Settings → Pages**, select **Deploy from a branch → main → /(root)** and save. The relative asset paths support both a GitHub Pages project URL and a custom domain. Configure any custom domain in Pages and at your DNS provider. No domain is hardcoded.

## Verification

JavaScript syntax, HTML IDs, local asset references, diagram output and recipe calculations were checked. Browser visual QA was unavailable in the authoring environment; check desktop/mobile rendering after publication.
