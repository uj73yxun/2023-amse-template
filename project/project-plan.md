# Project Plan

## Summary

<!-- Describe your data science project in max. 5 sentences. -->
This projects analyzes the density of public Electric Vehicle Supply Equipment (EVSE) in comparison with the population density.

## Rationale

<!-- Outline the impact of the analysis, e.g. which pains it solves. -->
The analysis helps to get an overview of the coverage of EVSEs in Germany and if they fit the market need. The assumption is that the need for EVSEs is higher in either densly populated areas or along highly used traffic routes. In effect, the resulting map can be used to assess where the EV-friendly areas in Germany are and where it might be worth for a charge point operator to install new EVSEs.

## Datasources

<!-- Describe each datasources you plan to use in a section. Use the prefic "DatasourceX" where X is the id of the datasource. -->

### Datasource1: Map of all EVSEs in Germany
* Metadata URL: [https://mobilithek.info/offers/-2989425250318611078](https://mobilithek.info/offers/-2989425250318611078)
* Data URL: [https://opendata.rhein-kreis-neuss.de/api/v2/catalog/datasets/rhein-kreis-neuss-ladesaulen-in-deutschland/exports/csv](https://opendata.rhein-kreis-neuss.de/api/v2/catalog/datasets/rhein-kreis-neuss-ladesaulen-in-deutschland/exports/csv)
* Data Type: CSV

This is a list of all public EVSEs in Germany. It contains the capacity of the EVSE, the operating company and the location.

### Datasource2: List of administrative disctricts in Germany
* Metadata URL: [https://www.govdata.de/web/guest/suchen/-/details/gemeindeverzeichnis-kreisfreie-stadte-und-landkreise](https://www.govdata.de/web/guest/suchen/-/details/gemeindeverzeichnis-kreisfreie-stadte-und-landkreise)
* Data URL: [https://www.destatis.de/DE/Themen/Laender-Regionen/Regionales/Gemeindeverzeichnis/Administrativ/04-kreise.xlsx?__blob=publicationFile](https://www.destatis.de/DE/Themen/Laender-Regionen/Regionales/Gemeindeverzeichnis/Administrativ/04-kreise.xlsx?__blob=publicationFile)
* Data Type: CSV

The list of districts contains an area code, the assigned area size and population count.

## Work Packages

<!-- List of work packages ordered sequentially, each pointing to an issue with more details. -->

1. [Adding more description to raw CSV data sources](https://github.com/uj73yxun/2023-amse-template/issues/1)
2. [Normalizing CSV datasets in the repository](https://github.com/uj73yxun/2023-amse-template/issues/2)
3. [Creating an Automated Data Pipeline for CSV to SQLite Conversion](https://github.com/uj73yxun/2023-amse-template/issues/3)
4. [Creating Automated Testing for the Data Pipeline](https://github.com/uj73yxun/2023-amse-template/issues/4)
5. [Packaging the Data Pipeline into a Continuous Integration System](https://github.com/uj73yxun/2023-amse-template/issues/5)
6. [Evaluate data and publish results to GitHub pages](https://github.com/uj73yxun/2023-amse-template/issues/6)

[i1]: https://github.com/jvalue/2023-amse-template/issues/1
