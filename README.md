# wri-bounds
Country shapefiles and boundaries for WRI

Based off NaturalEarthData.com

**DISCLAIMER** _These files are an attempt to represent country areas and boundaries from several perspectives and may be changed at any time. They do not imply any opinion on the part of the World Resources Institute concerning the legal status or delineation of any country or territory, nor do they imply endorsement of the represented country areas or boundaries._

### Downloads

Data are organized into three perspectives: 'U.S.', 'China', and 'India'. The default version of the files only display some of the more prominent and active disputes. If needed, additional disputed areas can be found on [Natural Earth Data](http://naciscdn.org/naturalearth/10m/cultural/).

Vector files for print layout ([svg](https://github.com/wri/wri-bounds/blob/master/dist/svgs.zip)) and a [csv](https://github.com/wri/wri-bounds/blob/master/countries.csv) of names and other attributes is also available.

U.S. | China | India
---- | ----- | -----
![U.S.](https://cdn.rawgit.com/wri/wri-bounds/master/intl_wintri.svg) | ![China](https://cdn.rawgit.com/wri/wri-bounds/master/cn_wintri.svg) | ![India](https://cdn.rawgit.com/wri/wri-bounds/master/in_wintri.svg)

**GIS Files by Country Perspective**

Data | Description | Shapefile | GeoJSON | Simplified GeoJSON
------ | ------ | ------ | ------ | ------
"Primary" countries | UN member states, sans dependencies | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/all_primary_countries.zip?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_primary_countries.zip?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_primary_countries.zip?raw=true) | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/all_primary_countries.geojson?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_primary_countries.geojson?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_primary_countries.geojson?raw=true) | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/all_primary_countries.min.geojson?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_primary_countries.min.geojson?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_primary_countries.min.geojson?raw=true)
"All" countries | All land area | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/all_countries.zip?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_countries.zip?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_countries.zip?raw=true) | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/all_countries.geojson?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_countries.geojson?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_countries.geojson?raw=true) | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/all_countries.min.geojson?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_countries.min.geojson?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_countries.min.geojson?raw=true)
All boundaries | Cartographic boundaries (see below) | [All](https://github.com/wri/wri-bounds/blob/master/dist/all_bounds.zip?raw=true) | [All](https://github.com/wri/wri-bounds/blob/master/dist/all_bounds.geojson?raw=true) | [All](https://github.com/wri/wri-bounds/blob/master/dist/all_bounds.min.geojson?raw=true)
Non-disputed bounds | Cartographic boundaries | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/intl_country_boundaries.zip?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_country_boundaries.zip?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_country_boundaries.zip?raw=true) | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/intl_country_boundaries.geojson?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_country_boundaries.geojson?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_country_boundaries.geojson?raw=true) | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/intl_country_boundaries.min.geojson?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_country_boundaries.min.geojson?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_country_boundaries.min.geojson?raw=true)
Disputed bounds | Cartographic boundaries | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/intl_disputed_boundaries.zip?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_disputed_boundaries.zip?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_disputed_boundaries.zip?raw=true) | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/intl_disputed_boundaries.geojson?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_disputed_boundaries.geojson?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_disputed_boundaries.geojson?raw=true) | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/intl_disputed_boundaries.min.geojson?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_disputed_boundaries.min.geojson?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_disputed_boundaries.min.geojson?raw=true)
Disputed areas | Disputed areas | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/disputed.zip?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_disputed.zip?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_disputed.zip?raw=true) | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/disputed.geojson?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_disputed.geojson?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_disputed.geojson?raw=true) | [U.S.](https://github.com/wri/wri-bounds/blob/master/dist/disputed.min.geojson?raw=true)/[China](https://github.com/wri/wri-bounds/blob/master/dist/cn_disputed.min.geojson?raw=true)/[India](https://github.com/wri/wri-bounds/blob/master/dist/in_disputed.min.geojson?raw=true)
Land | All land area | [All](https://github.com/wri/wri-bounds/blob/master/dist/land_areas.zip?raw=true) | [All](https://github.com/wri/wri-bounds/blob/master/dist/land_areas.geojson?raw=true) | [All](https://github.com/wri/wri-bounds/blob/master/dist/land_areas.min.geojson?raw=true)

**Key fields**

Countries:"PRIMARY"
- 0:Non UN
- 1:UN Member

Boundaries:"INTL" - 'U.S.' perspective
- 0:Do not show
- 1:Country boundary
- 2:Disputed boundary

Boundaries:"CHN" - 'China' perspective
- 0:Do not show
- 1:Country boundary
- 2:Disputed boundary

Boundaries:"IND" - 'India' perspective
- 0:Do not show
- 1:Country boundary
- 2:Disputed boundary

### Attribute table
[CSV](https://github.com/wri/wri-bounds/blob/master/countries.csv)

Column | Description | Source
------ | ------ | ------
iso_short | ISO Short Name | ISO 3166
name | **Country name** | Natural Earth Data
formal\_name | Full formal country name | Natural Earth Data
short\_name | Short country name | Natural Earth Data
abbrev | Country name abbreviation | Natural Earth Data
un\_ar | UN GEGN Arabic name | UN GEGN
un\_zh | UN GEGN Chinese name | UN GEGN
un\_en | UN GEGN English name | UN GEGN
un\_fr | UN GEGN French name | UN GEGN
un\_ru | UN GEGN Russian name | UN GEGN
un\_es | UN GEGN Spanish name | UN GEGN
adm0\_a3 | Country Code | Natural Earth Data
postal | Postal Code | Natural Earth Data
iso\_a2 | ISO A2 Code | ISO 3166
iso\_a3 | ISO A3 Code | Natural Earth Data
iso\_n3 | ISO N3 Code | Natural Earth Data
un\_n3 | UN N3 Code | Natural Earth Data
wb\_a2 | World Bank A2 code | Natural Earth Data
wb\_a3 | World Bank A3 code | Natural Earth Data
type | Country type |
continent | Continent | Natural Earth Data
un\_region | UN Region | Natural Earth Data
un\_subregion | UN Subregion | Natural Earth Data
wb\_region | World Bank Region | Natural Earth Data

### Build

You can modify the parameters used to generate these boundary sets.

Requires:
 - [GDAL/OGR](http://www.gdal.org/index.html)
 - [node](http://nodejs.org)
 - [mapshaper@0.2.x](http://mapshaper.org)

OS X Macports
```
port install gdal
port install npm
npm install mapshaper@0.2.x
make
```

