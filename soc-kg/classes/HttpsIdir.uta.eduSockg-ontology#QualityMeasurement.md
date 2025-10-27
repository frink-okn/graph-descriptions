

# Class: No class (entity type) name specified -- this class is noted as a superclass of another class in this graph but has not itself been defined. (https___idir.uta.edu_sockg-ontology#QualityMeasurement)





URI: [https://idir.uta.edu/sockg-ontology#QualityMeasurement](https://idir.uta.edu/sockg-ontology#QualityMeasurement)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#QualityMeasurement
    click HttpsIdir.uta.eduSockg-ontology#QualityMeasurement href "../HttpsIdir.uta.eduSockg-ontology#QualityMeasurement"
      HttpsIdir.uta.eduSockg-ontology#Sample <|-- HttpsIdir.uta.eduSockg-ontology#QualityMeasurement
        click HttpsIdir.uta.eduSockg-ontology#Sample href "../HttpsIdir.uta.eduSockg-ontology#Sample"
      

      HttpsIdir.uta.eduSockg-ontology#QualityMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss
        click HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss href "../HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss"
      HttpsIdir.uta.eduSockg-ontology#QualityMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#WaterQualityArea
        click HttpsIdir.uta.eduSockg-ontology#WaterQualityArea href "../HttpsIdir.uta.eduSockg-ontology#WaterQualityArea"
      HttpsIdir.uta.eduSockg-ontology#QualityMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration
        click HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration href "../HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration"
      
      
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md)
        * **HttpsIdir.uta.eduSockg-ontology#QualityMeasurement**
            * [HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss](../classes/HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss.md)
            * [HttpsIdir.uta.eduSockg-ontology#WaterQualityArea](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityArea.md)
            * [HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss](../classes/HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss.md) | [https___idir.uta.edu_sockg_ontology#withStartStopInterval](../slots/https___idir.uta.edu_sockg_ontology#withStartStopInterval.md) | domain | [HttpsIdir.uta.eduSockg-ontology#QualityMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#QualityMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityArea](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityArea.md) | [https___idir.uta.edu_sockg_ontology#hasSurfaceOrLeaching](../slots/https___idir.uta.edu_sockg_ontology#hasSurfaceOrLeaching.md) | domain | [HttpsIdir.uta.eduSockg-ontology#QualityMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#QualityMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration.md) | [https___idir.uta.edu_sockg_ontology#hasSurfaceOrLeaching](../slots/https___idir.uta.edu_sockg_ontology#hasSurfaceOrLeaching.md) | domain | [HttpsIdir.uta.eduSockg-ontology#QualityMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#QualityMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration.md) | [https___idir.uta.edu_sockg_ontology#withStartStopInterval](../slots/https___idir.uta.edu_sockg_ontology#withStartStopInterval.md) | domain | [HttpsIdir.uta.eduSockg-ontology#QualityMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#QualityMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#WindErosionArea](../classes/HttpsIdir.uta.eduSockg-ontology#WindErosionArea.md) | [https___idir.uta.edu_sockg_ontology#withStartStopInterval](../slots/https___idir.uta.edu_sockg_ontology#withStartStopInterval.md) | domain | [HttpsIdir.uta.eduSockg-ontology#QualityMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#QualityMeasurement.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#QualityMeasurement
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#Sample
class_uri: https://idir.uta.edu/sockg-ontology#QualityMeasurement

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#QualityMeasurement
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#Sample
class_uri: https://idir.uta.edu/sockg-ontology#QualityMeasurement

```
</details>