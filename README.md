# B-Tree Visualizer

Interactive browser-based B-Tree insertion and deletion visualizer, using the order-based occupancy rules from the course slides.

## Features
- Select B-Tree order (3–12).
- Enter a custom insertion sequence.
- Choose middle, lower-middle, or upper-middle promotion.
- Step through insertions with First, Previous, Next, Play, Pause, Last, and Reset.
- View the tree, height, node count, insertion order, and split explanation after each step.
- Correct occupancy: maximum `m − 1` keys; minimum `ceil(m / 2) − 1` keys in every non-root node.
- Bottom-up deletion repair for odd orders, so merging an underflowed node never creates an overfull node.
- No backend or API keys required.

## Run locally
Open `index.html` in a modern browser.

## Deploy on Render
Create a Render Static Site connected to this repository. Use branch `main`, leave the build command empty, and set the publish directory to `.`.
