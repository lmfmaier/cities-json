# cities.json
World cities in json format

## Description

Populated places of the world (towns, cities) with a population of 500 or more, extracted from the GeoNames database dump. With ID (geonamesid), name, country (ISO alpha 2), admin1 (state/province), latitude, longitude, population. Names are extracted from GeoNames' "name" columns (which are probably the official name of the place in English), no alternate or localized names.

Geonames fcodes used: PPL, PPLA*, PPLC. These are all populated places including capitals and administrative seats, but no sections/suburbs (PPLX).

Roughly 150K places.

## Format
```
[
  {
    "id": "5368361",
    "name": "Los Angeles",
    "country": "US",
    "admin1": "California",
    "lat": "34.0522300",
    "lon": "-118.2436800",
    "pop": "3971883"
  }
]
```
## Source
GeoNames Gazetteer extract files: http://download.geonames.org/export/dump/

## License
This work is licensed under a Creative Commons Attribution 4.0 License
https://creativecommons.org/licenses/by/3.0/
