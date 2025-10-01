

# Slot: Date (dct_date)


_Date may be used to express temporal information at any level of granularity.  Recommended practice is to express the date, date/time, or period of time according to ISO 8601-1 [[ISO 8601-1](https://www.iso.org/iso-8601-date-and-time-format.html)] or a published profile of the ISO standard, such as the W3C Note on Date and Time Formats [[W3CDTF](https://www.w3.org/TR/NOTE-datetime)] or the Extended Date/Time Format Specification [[EDTF](http://www.loc.gov/standards/datetime/)].  If the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used. Date ranges may be specified using ISO 8601 period of time specification in which start and end dates are separated by a '/' (slash) character.  Either the start or end date may be missing._






This slot occurs 443351 times.


URI: [dct:date](http://purl.org/dc/terms/date)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#BiomassEnergy](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassEnergy.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityArea](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityArea.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#WeatherObservation](../classes/HttpsIdir.uta.eduSockg-ontology#WeatherObservation.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency](../classes/HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#GrazingPlants](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingPlants.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss](../classes/HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#WindErosionArea](../classes/HttpsIdir.uta.eduSockg-ontology#WindErosionArea.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#SoilCover](../classes/HttpsIdir.uta.eduSockg-ontology#SoilCover.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#BiomassMineral](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassMineral.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#GHGFlux](../classes/HttpsIdir.uta.eduSockg-ontology#GHGFlux.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake](../classes/HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#HarvestFraction](../classes/HttpsIdir.uta.eduSockg-ontology#HarvestFraction.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample.md) |  |  no  |







## Properties

* Range: [RdfsLiteral](../classes/RdfsLiteral.md)





## Comments

* description: A point or period of time associated with an event in the lifecycle of the resource.



## LinkML Source

<details>

```yaml
name: dct_date
description: Date may be used to express temporal information at any level of granularity.  Recommended
  practice is to express the date, date/time, or period of time according to ISO 8601-1
  [[ISO 8601-1](https://www.iso.org/iso-8601-date-and-time-format.html)] or a published
  profile of the ISO standard, such as the W3C Note on Date and Time Formats [[W3CDTF](https://www.w3.org/TR/NOTE-datetime)]
  or the Extended Date/Time Format Specification [[EDTF](http://www.loc.gov/standards/datetime/)].  If
  the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used.
  Date ranges may be specified using ISO 8601 period of time specification in which
  start and end dates are separated by a '/' (slash) character.  Either the start
  or end date may be missing.
title: Date
notes:
- No occurrences of this slot in the graph.
comments:
- 'description: A point or period of time associated with an event in the lifecycle
  of the resource.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:date
domain_of:
- https___idir.uta.edu_sockg-ontology#BiomassCarbohydrate
- https___idir.uta.edu_sockg-ontology#BiomassEnergy
- https___idir.uta.edu_sockg-ontology#BiomassMineral
- https___idir.uta.edu_sockg-ontology#GHGFlux
- https___idir.uta.edu_sockg-ontology#GasNutrientLoss
- https___idir.uta.edu_sockg-ontology#GrazingPlants
- https___idir.uta.edu_sockg-ontology#GrowthStageManagement
- https___idir.uta.edu_sockg-ontology#HarvestFraction
- https___idir.uta.edu_sockg-ontology#NutrientEfficiency
- https___idir.uta.edu_sockg-ontology#ResidueMeasurement
- https___idir.uta.edu_sockg-ontology#SoilBiologicalSample
- https___idir.uta.edu_sockg-ontology#SoilChemicalSample
- https___idir.uta.edu_sockg-ontology#SoilCover
- https___idir.uta.edu_sockg-ontology#SoilPhysicalSample
- https___idir.uta.edu_sockg-ontology#WaterQualityArea
- https___idir.uta.edu_sockg-ontology#WaterQualityConcentration
- https___idir.uta.edu_sockg-ontology#WeatherObservation
- https___idir.uta.edu_sockg-ontology#WindErosionArea
- https___idir.uta.edu_sockg-ontology#YieldNutrientUptake
subproperty_of: dc_date
range: rdfs_Literal

```
</details>