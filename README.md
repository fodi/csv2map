# CSV2Map
 This webapp turns rows of CSV files into markers on an interactive map. It's just some glue between [PapaParse](https://www.papaparse.com/) and [Leaflet](https://leafletjs.com/), powered by [OpenStreetMap](https://www.openstreetmap.org/).

To get started, just enter the URL of your CSV file (eg. a Google Sheet published in that format). The file must include a **Latitude** and **Longitude** column. Optional columns are **PopupHTML** (if a marker is clicked, this HTML will show up in a popup) and **MarkerColor** (You can specify a HTML color name or hex value like `#ff00ff` if you want a colored circle instead of the default blue marker icon).

## Online version
https://fodi.github.io/csv2map/
