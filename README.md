# Order Grid Heatmap

This repository contains a simple Leaflet demo that draws 1×1 km grid cells only for locations where orders exist. Each cell is colored according to the sum of orders that fall inside it:

* 0–1 green
* 1–2 yellow
* 2–3 orange
* 3–4 pink
* 4+ red

The sample data includes a single order; add more points in the `orders` array inside `index.html`. Grid values are shown with two decimal places and a `%` sign.
