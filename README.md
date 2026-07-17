# Travel Atlas

A living, interactive 3D globe charting every place I've been — and the places I still dream of going. Built with Three.js.

**Live:** https://akversebusiness-beep.github.io/

## Adding a place

1. Add an entry to `content/data.js` (slug, name, region, date, lat/lng, story).
2. Drop photos into `content/places/<slug>/1.jpg`, `2.jpg`, … (jpg, jpeg, png, or webp all work).
3. Commit and push — GitHub Pages redeploys automatically.

## Adding a dream destination

Same as above, but add the entry to the `DREAMS` array in `content/data.js` and drop photos into `content/dreams/<slug>/`.

## Local preview

```
python3 serve.py
```

then open http://127.0.0.1:8000/
