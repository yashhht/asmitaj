# Updated Model Portfolio UI

Includes Western, Traditional, and Brand Shoot (Malabar Jewellery) sections. Each section shows a three-image collage preview and opens a four-image gallery with thumbnails and previous/next arrows. Framer Motion scroll reveals, hover effects, and spring mobile menu remain.

## Run
`npm install` then `npm run dev`.

## Images
Put files in `public/images/` using these exact filenames:
- `hero.jpg` — unique hero image, not reused elsewhere
- `about.jpg` — About portrait
- `western-1.jpg` through `western-4.jpg` — Western collection
- `traditional-1.jpg` through `traditional-4.jpg` — Traditional collection
- `malabar-1.jpg` through `malabar-4.jpg` — Brand Shoot / Malabar Jewellery
- `bottom.jpg` — separate bottom background, not reused elsewhere
- `footer-1.jpg`, `footer-2.jpg`, `footer-3.jpg` — footer thumbnails

For each collection, image 1 is the main cover and images 2–4 are the collage previews. All four appear in the click-open gallery. Code expects .jpg; update filenames in `src/main.jsx` if your real files are .png or .webp. Replace the Instagram URL and @yournamehere in `src/main.jsx` with the model's real profile.
