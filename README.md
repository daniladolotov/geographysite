# geographysite
It's geography site that I am making it's one of my first projects

## Preview
Open `index.html` in your browser to see the title, the improved design, the interactive map, and the second page.

### How it works
 - A small sticky navigation bar appears at the top of the page; it includes `Home` and `About` links that jump to sections on the page.
 - The navigation is styled simply and becomes compact on small screens.
 - The site includes an interactive map (Map section) using Leaflet + OpenStreetMap tiles. Pan, zoom, and click the marker to open a popup.
 - The site includes an interactive map (Map section) using Leaflet + OpenStreetMap tiles. Pan, zoom, and click the marker to open a popup.
 - The responsive navigation includes a 'Next page' CTA that links to `page2.html`.
 - The map includes a layer switcher (top-right on the map) so you can switch between CartoDB Positron (light) and OpenStreetMap tiles.
 - Site colors: the accent color is a modern blue (used for CTAs and highlights).

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
