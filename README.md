# qgis-demo

## Daten
- Verwaltungsgrenzen: https://data.bev.gv.at/geonetwork/srv/eng/catalog.search#/metadata/2d6ae2c7-af9e-4046-b54c-ee907964ee01
- DLM-Bauten: https://data.bev.gv.at/geonetwork/srv/eng/catalog.search#/metadata/6a5b702d-fc01-4230-9a70-7fccee20d01a

## Demo
1) Erstellen GeoPackage

Rechtsklick auf gewünschtes Verzeichnis > New GeoPackage

<img src="./01_create_gpkg.png" height=500>


### Anzahl der Schulen in den österreichischen Bundesländern
1) Dissolve VGD (anhand BL)
Processing > Processing Toolbox > Dissolve

<img src="./02_dissolve.png" width=500>

2) Join Attributes By Location
Processing > Processing Toolbox > Join Attributes By Location




2) Join Attributes By Location
3) Drop Fields von Join Layer