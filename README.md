# Flight to plotter

Browser tools that turn flights and FAA airport diagrams into drawings for a pen plotter. Everything runs in the browser; nothing is uploaded anywhere.

- **index.html (Flight to plotter):** drop in a KML or GPX track (ForeFlight, Garmin Pilot, CloudAhoy, a GPS) and get a print with the flight path, stops, altitude profile, caption, and optional towns, highways and water from OpenStreetMap. Add the FAA airport diagram PDF and the airfield is lined up under the track automatically.
- **chart.html (Chart to plotter):** turn an FAA airport diagram PDF into a framed print, with Classic, Milestone and Minimal templates.

Both export DXF (millimetres, plot at 100%) and SVG. With two pens, the map and the flight are separate layers: plot layer 1, swap pens, then plot layer 2.

## Data and credits

- Map details: © OpenStreetMap contributors (ODbL), downloaded through the Overpass API when you add a track. A credit line is added to the print.
- Airport diagrams: FAA, public domain. Prints are decorative and not for navigation.
- PDF reading: pdf.js. Polygon clipping: Clipper.
