

# Class: No class (entity type) name specified -- this class is noted as a superclass of another class in this graph but has not itself been defined. (https___idir.uta.edu_sockg-ontology#SoilSample)





URI: [https://idir.uta.edu/sockg-ontology#SoilSample](https://idir.uta.edu/sockg-ontology#SoilSample)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#SoilSample
    click HttpsIdir.uta.eduSockg-ontology#SoilSample href "../HttpsIdir.uta.eduSockg-ontology#SoilSample"
      HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#SoilSample
        click HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement href "../HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement"
      

      HttpsIdir.uta.eduSockg-ontology#SoilSample <|-- HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample
        click HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample href "../HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample"
      HttpsIdir.uta.eduSockg-ontology#SoilSample <|-- HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample
        click HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample href "../HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample"
      HttpsIdir.uta.eduSockg-ontology#SoilSample <|-- HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample
        click HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample href "../HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample"
      
      
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md)
        * [HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement.md)
            * **HttpsIdir.uta.eduSockg-ontology#SoilSample**
                * [HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample.md)
                * [HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample.md)
                * [HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample.md) | [https___idir.uta.edu_sockg_ontology#upperDepth](../slots/https___idir.uta.edu_sockg_ontology#upperDepth.md) | domain | [HttpsIdir.uta.eduSockg-ontology#SoilSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilSample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample.md) | [https___idir.uta.edu_sockg_ontology#lowerDepth](../slots/https___idir.uta.edu_sockg_ontology#lowerDepth.md) | domain | [HttpsIdir.uta.eduSockg-ontology#SoilSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilSample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample.md) | [https___idir.uta.edu_sockg_ontology#upperDepth](../slots/https___idir.uta.edu_sockg_ontology#upperDepth.md) | domain | [HttpsIdir.uta.eduSockg-ontology#SoilSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilSample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample.md) | [https___idir.uta.edu_sockg_ontology#lowerDepth](../slots/https___idir.uta.edu_sockg_ontology#lowerDepth.md) | domain | [HttpsIdir.uta.eduSockg-ontology#SoilSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilSample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample.md) | [https___idir.uta.edu_sockg_ontology#upperDepth](../slots/https___idir.uta.edu_sockg_ontology#upperDepth.md) | domain | [HttpsIdir.uta.eduSockg-ontology#SoilSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilSample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample.md) | [https___idir.uta.edu_sockg_ontology#lowerDepth](../slots/https___idir.uta.edu_sockg_ontology#lowerDepth.md) | domain | [HttpsIdir.uta.eduSockg-ontology#SoilSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilSample.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#SoilSample
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#PossiblySimulatedMeasurement
class_uri: https://idir.uta.edu/sockg-ontology#SoilSample

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#SoilSample
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#PossiblySimulatedMeasurement
class_uri: https://idir.uta.edu/sockg-ontology#SoilSample

```
</details>