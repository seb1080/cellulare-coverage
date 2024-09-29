# Cellphone coverage

SCRS: [NAD83](https://webapp.csrs-scrs.nrcan-rncan.gc.ca/geod/tools-outils/nad83-docs.php?locale=fr)

Projection: EPSG:32198 - NAD83 / Quebec Lambert

EPSG: [Quebec Lambert](https://epsg.io/32198)

Spatial Reference: [Quebec Lambert](https://spatialreference.org/ref/epsg/32198/)

Area of study the province of quebec around the National Parc of the Mauricie.

## Rectangle of Canada and Quebec

Rectangle of Canada:

Limit Est: 47.525295, -52.6217498
Limit West: 60.30628, -141.00200

Limit South: 41.67658, -82.65224
Limit North: 83.09551, -74.23158

Rectangle of Quebec:

## Geometry du parc national de la Mauricie

Numéro de zonage: H-9509

## Data sources

- [OpenCellId raw data](https://opencellid.org/downloads.php?token=pk.1da23ffb013861e4a1f48013212eadc0)
- [Data dictionary](https://wiki.opencellid.org/wiki/API#Filtering_of_data)
- [database-schema.md](https://github.com/edipermadi/opencellid-importer/blob/master/doc/database-schema.md)

- [Répertoire des municipalités](https://www.donneesquebec.ca/recherche/dataset/repertoire-des-municipalites-du-quebec)

## Open Cell Id dataset column titles

Radio: The generation of broadband cellular network technology
MCC: Mobile Country Code
Net: Mobile Network Code
Area: Location Area Code (LAC)
Cell: Cell tower code (CID)
lat, long: Approx coordinates of the cell tower
range: Approximate area within which the cell could be. (radius in meters)
samples: No of measures processed to get this data
changeble:

1 = The location is determined by processing samples
0 = We got the location directly from the telecom firm
created: When the cell was first added to database (UNIX timestamp)
updated: When the cell was last seen (UNIX timestamp)


## Useful references

- [Carte couverture cellulaire](https://www.planhub.ca/fr/planhub/coverage-map)