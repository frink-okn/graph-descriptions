

# Class: No class (entity type) name specified -- this class is noted as a superclass of another class in this graph but has not itself been defined. (https___idir.uta.edu_sockg-ontology#PossiblySimulatedMeasurement)





URI: [https://idir.uta.edu/sockg-ontology#PossiblySimulatedMeasurement](https://idir.uta.edu/sockg-ontology#PossiblySimulatedMeasurement)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement
    click HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement href "../HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement"
      HttpsIdir.uta.eduSockg-ontology#Sample <|-- HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement
        click HttpsIdir.uta.eduSockg-ontology#Sample href "../HttpsIdir.uta.eduSockg-ontology#Sample"
      

      HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#SoilSample
        click HttpsIdir.uta.eduSockg-ontology#SoilSample href "../HttpsIdir.uta.eduSockg-ontology#SoilSample"
      HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#WindErosionArea
        click HttpsIdir.uta.eduSockg-ontology#WindErosionArea href "../HttpsIdir.uta.eduSockg-ontology#WindErosionArea"
      HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake
        click HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake href "../HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake"
      
      
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md)
        * **HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement**
            * [HttpsIdir.uta.eduSockg-ontology#SoilSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilSample.md)
            * [HttpsIdir.uta.eduSockg-ontology#WindErosionArea](../classes/HttpsIdir.uta.eduSockg-ontology#WindErosionArea.md)
            * [HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake](../classes/HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss](../classes/HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss.md) | [https___idir.uta.edu_sockg_ontology#usesModel](../slots/https___idir.uta.edu_sockg_ontology#usesModel.md) | domain | [HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample.md) | [https___idir.uta.edu_sockg_ontology#usesModel](../slots/https___idir.uta.edu_sockg_ontology#usesModel.md) | domain | [HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample.md) | [https___idir.uta.edu_sockg_ontology#usesModel](../slots/https___idir.uta.edu_sockg_ontology#usesModel.md) | domain | [HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration.md) | [https___idir.uta.edu_sockg_ontology#usesModel](../slots/https___idir.uta.edu_sockg_ontology#usesModel.md) | domain | [HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#WindErosionArea](../classes/HttpsIdir.uta.eduSockg-ontology#WindErosionArea.md) | [https___idir.uta.edu_sockg_ontology#usesModel](../slots/https___idir.uta.edu_sockg_ontology#usesModel.md) | domain | [HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#PossiblySimulatedMeasurement
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#Sample
class_uri: https://idir.uta.edu/sockg-ontology#PossiblySimulatedMeasurement

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#PossiblySimulatedMeasurement
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#Sample
class_uri: https://idir.uta.edu/sockg-ontology#PossiblySimulatedMeasurement

```
</details>