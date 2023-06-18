# CSV2Map
This webapp turns rows of CSV files into markers on an interactive map. It's just some glue between [PapaParse](https://www.papaparse.com/) and [Leaflet](https://leafletjs.com/), powered by [OpenStreetMap](https://www.openstreetmap.org/).

To get started, just enter the URL of your CSV file (eg. a Google Sheet published in that format). The file must include a **Latitude** and **Longitude** column. Optional columns are **PopupHTML** (if a marker is clicked, this HTML will show up in a popup) and **MarkerColor** (You can specify a HTML color name or hex value like `#ff00ff` if you want a colored circle instead of the default blue marker icon).

## Example
[Google Sheet](https://docs.google.com/spreadsheets/d/1dski_07gHa9LGK2491SN4-FepTHpsiaSQU9aY1CRoPc) ➡️ [Published as CSV](https://docs.google.com/spreadsheets/d/e/2PACX-1vTrTyLnsl1Z8d48GBXT2fy-PbNEeo1AGa4U_-q9E3opt_gcvq73JVrWXoAAR4wrCqlOUZHO61rHVZVL/pub?single=true&output=csv) ➡️ [This](https://fodi.github.io/csv2map/?csv_url=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2Fe%2F2PACX-1vTrTyLnsl1Z8d48GBXT2fy-PbNEeo1AGa4U_-q9E3opt_gcvq73JVrWXoAAR4wrCqlOUZHO61rHVZVL%2Fpub%3Fsingle%3Dtrue%26output%3Dcsv)

## Online version
https://fodi.github.io/csv2map/
