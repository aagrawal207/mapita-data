# Mapita data

Data files for the Mapita app.

The `.guide` and `.pack` files in `v1/` are locked. Only the app can read them, and nothing here is meant for
use outside the app.

The `.basemap` files are open. They are made from [OpenStreetMap](https://www.openstreetmap.org/copyright)
data, © OpenStreetMap contributors, and are available under the
[Open Database License](https://opendatacommons.org/licenses/odbl/). Each one holds the simplified coast, roads,
beaches and green areas of one destination as deflated JSON after a three-byte header.
