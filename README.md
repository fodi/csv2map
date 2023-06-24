# CSV2Map
This webapp turns rows of CSV files into markers on an interactive map. It's just some glue between [PapaParse](https://www.papaparse.com/) and [Leaflet](https://leafletjs.com/), base map is provided by [OpenStreetMap](https://www.openstreetmap.org/). External libraries are loaded via UNPKG, everything else is contained in `index.html`.

## Usage
See `index.html` or try the [online version](https://fodi.github.io/csv2map/).

## Example
[Google Sheet](https://docs.google.com/spreadsheets/d/1dski_07gHa9LGK2491SN4-FepTHpsiaSQU9aY1CRoPc) ➡️ [Published as CSV](https://docs.google.com/spreadsheets/d/e/2PACX-1vTrTyLnsl1Z8d48GBXT2fy-PbNEeo1AGa4U_-q9E3opt_gcvq73JVrWXoAAR4wrCqlOUZHO61rHVZVL/pub?single=true&output=csv) ➡️ [This](https://fodi.github.io/csv2map/?csv_url=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2Fe%2F2PACX-1vTrTyLnsl1Z8d48GBXT2fy-PbNEeo1AGa4U_-q9E3opt_gcvq73JVrWXoAAR4wrCqlOUZHO61rHVZVL%2Fpub%3Fsingle%3Dtrue%26output%3Dcsv)
