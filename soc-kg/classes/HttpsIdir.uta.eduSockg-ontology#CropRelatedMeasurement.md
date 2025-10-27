

# Class: No class (entity type) name specified -- this class is noted as a superclass of another class in this graph but has not itself been defined. (https___idir.uta.edu_sockg-ontology#CropRelatedMeasurement)





URI: [https://idir.uta.edu/sockg-ontology#CropRelatedMeasurement](https://idir.uta.edu/sockg-ontology#CropRelatedMeasurement)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement
    click HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement href "../HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement"
      HttpsIdir.uta.eduSockg-ontology#Sample <|-- HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement
        click HttpsIdir.uta.eduSockg-ontology#Sample href "../HttpsIdir.uta.eduSockg-ontology#Sample"
      

      HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#GHGFlux
        click HttpsIdir.uta.eduSockg-ontology#GHGFlux href "../HttpsIdir.uta.eduSockg-ontology#GHGFlux"
      HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#SoilCover
        click HttpsIdir.uta.eduSockg-ontology#SoilCover href "../HttpsIdir.uta.eduSockg-ontology#SoilCover"
      
      
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md)
        * **HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement**
            * [HttpsIdir.uta.eduSockg-ontology#GHGFlux](../classes/HttpsIdir.uta.eduSockg-ontology#GHGFlux.md)
            * [HttpsIdir.uta.eduSockg-ontology#SoilCover](../classes/HttpsIdir.uta.eduSockg-ontology#SoilCover.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassEnergy](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassEnergy.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassMineral](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassMineral.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#GHGFlux](../classes/HttpsIdir.uta.eduSockg-ontology#GHGFlux.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss](../classes/HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#HarvestFraction](../classes/HttpsIdir.uta.eduSockg-ontology#HarvestFraction.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency](../classes/HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#PlantingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantingManagement.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#ResidueManagement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueManagement.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilCover](../classes/HttpsIdir.uta.eduSockg-ontology#SoilCover.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#TillageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#TillageManagement.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake](../classes/HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake.md) | [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#CropRelatedMeasurement
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#Sample
class_uri: https://idir.uta.edu/sockg-ontology#CropRelatedMeasurement

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#CropRelatedMeasurement
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#Sample
class_uri: https://idir.uta.edu/sockg-ontology#CropRelatedMeasurement

```
</details>