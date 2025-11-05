

# Class: No class (entity type) name specified -- this class is noted as a superclass of another class in this graph but has not itself been defined. (https___idir.uta.edu_sockg-ontology#PlantFractionRelatedMeasurement)





URI: [https://idir.uta.edu/sockg-ontology#PlantFractionRelatedMeasurement](https://idir.uta.edu/sockg-ontology#PlantFractionRelatedMeasurement)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement
    click HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement href "../HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement"
      HttpsIdir.uta.eduSockg-ontology#Sample <|-- HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement
        click HttpsIdir.uta.eduSockg-ontology#Sample href "../HttpsIdir.uta.eduSockg-ontology#Sample"
      

      HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#BiomassAnalysis
        click HttpsIdir.uta.eduSockg-ontology#BiomassAnalysis href "../HttpsIdir.uta.eduSockg-ontology#BiomassAnalysis"
      HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#HarvestFraction
        click HttpsIdir.uta.eduSockg-ontology#HarvestFraction href "../HttpsIdir.uta.eduSockg-ontology#HarvestFraction"
      HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency
        click HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency href "../HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency"
      
      
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md)
        * **HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement**
            * [HttpsIdir.uta.eduSockg-ontology#BiomassAnalysis](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassAnalysis.md)
            * [HttpsIdir.uta.eduSockg-ontology#HarvestFraction](../classes/HttpsIdir.uta.eduSockg-ontology#HarvestFraction.md)
            * [HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency](../classes/HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate.md) | [https___idir.uta.edu_sockg_ontology#hasPlantFraction](../slots/https___idir.uta.edu_sockg_ontology#hasPlantFraction.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassEnergy](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassEnergy.md) | [https___idir.uta.edu_sockg_ontology#hasPlantFraction](../slots/https___idir.uta.edu_sockg_ontology#hasPlantFraction.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassMineral](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassMineral.md) | [https___idir.uta.edu_sockg_ontology#hasPlantFraction](../slots/https___idir.uta.edu_sockg_ontology#hasPlantFraction.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#HarvestFraction](../classes/HttpsIdir.uta.eduSockg-ontology#HarvestFraction.md) | [https___idir.uta.edu_sockg_ontology#hasPlantFraction](../slots/https___idir.uta.edu_sockg_ontology#hasPlantFraction.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency](../classes/HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency.md) | [https___idir.uta.edu_sockg_ontology#hasPlantFraction](../slots/https___idir.uta.edu_sockg_ontology#hasPlantFraction.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake](../classes/HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake.md) | [https___idir.uta.edu_sockg_ontology#hasPlantFraction](../slots/https___idir.uta.edu_sockg_ontology#hasPlantFraction.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#PlantFractionRelatedMeasurement
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#Sample
class_uri: https://idir.uta.edu/sockg-ontology#PlantFractionRelatedMeasurement

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#PlantFractionRelatedMeasurement
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#Sample
class_uri: https://idir.uta.edu/sockg-ontology#PlantFractionRelatedMeasurement

```
</details>