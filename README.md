# Order Grid Heatmap

This repository contains a simple Leaflet demo that draws 1×1 km grid cells only for locations where orders exist. Each cell is colored based on the sum of orders in that cell:

* 0.05–0.5 white
* 0.5–1 green
* 1–2 yellow
* 2–3 orange
* 3–4 pink
* 4+ red

Cells with totals below 0.05 are hidden. Values displayed on each grid are rounded to two decimals and shown with a `%` sign. The sample data includes a single order; add more points in the `orders` array inside `index.html`.
