# geographysite
It's geography site that I am making it's one of my first projects

## Preview
Open `index.html` in your browser to see the new blue & white theme, the improved design, the interactive map, and the embedded second page.

### How it works
 - A small sticky navigation bar appears at the top of the page; it includes `Home` and `About` links that jump to sections on the page.
 - The navigation is styled simply and becomes compact on small screens.
 - The site includes an interactive map (Map section) using Leaflet + OpenStreetMap tiles. Pan, zoom, and click the marker to open a popup.
 - The responsive navigation includes `Home`, `About` and `Map` links; the previous Page 2 nav link has been removed. `page2.html` can still be opened directly if you prefer a standalone view.
 - The responsive navigation includes `Home`, `About` (links to the embedded 'Page 2' section) and `Map`.
 - The map includes a layer switcher (top-right on the map) so you can switch between CartoDB Positron (light) and OpenStreetMap tiles.
 - Site colors: the accent color is a modern blue (used for CTAs and highlights).
 - The background uses a gently animated blue gradient to give a subtle 'moving sea' effect. If you find it too active, I can slow it down further or remove it.
 - The background uses two animated gradient layers that change slowly and randomly (angles, color shades, speed) to create a dynamic 'living sea' feeling. If you'd like it even more lively (or slower), tell me which you'd prefer.

### Try it locally
If you'd like the down arrow to link to a separate HTML page instead of the second section, to add a hamburger menu for the nav on mobile, or to make the nav highlight the active section, tell me and I can implement that.

### Map
- The Map uses Leaflet via CDN. No extra dependencies are required; it will automatically request map tiles from OpenStreetMap.
- If your browser blocks scripts from running when opening a file via file://, run the server option in the preview section to host the site locally and avoid any issues.
```
# Open the index directly:
ii .\index.html

# Or serve the folder and browse to http://localhost:8000
python -m http.server 8000
```

If you'd like the down arrow to link to a separate HTML page instead of the second section, or to add a floating nav, tell me and I can implement that.
