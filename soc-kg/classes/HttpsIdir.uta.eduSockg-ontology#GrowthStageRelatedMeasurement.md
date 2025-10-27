

# Class: No class (entity type) name specified -- this class is noted as a superclass of another class in this graph but has not itself been defined. (https___idir.uta.edu_sockg-ontology#GrowthStageRelatedMeasurement)





URI: [https://idir.uta.edu/sockg-ontology#GrowthStageRelatedMeasurement](https://idir.uta.edu/sockg-ontology#GrowthStageRelatedMeasurement)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement
    click HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement href "../HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement"
      HttpsIdir.uta.eduSockg-ontology#Sample <|-- HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement
        click HttpsIdir.uta.eduSockg-ontology#Sample href "../HttpsIdir.uta.eduSockg-ontology#Sample"
      

      HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#GrazingPlants
        click HttpsIdir.uta.eduSockg-ontology#GrazingPlants href "../HttpsIdir.uta.eduSockg-ontology#GrazingPlants"
      HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement
        click HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement href "../HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement"
      
      
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md)
        * **HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement**
            * [HttpsIdir.uta.eduSockg-ontology#GrazingPlants](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingPlants.md)
            * [HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassEnergy](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassEnergy.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassMineral](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassMineral.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss](../classes/HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#GrazingPlants](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingPlants.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#HarvestFraction](../classes/HttpsIdir.uta.eduSockg-ontology#HarvestFraction.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency](../classes/HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#ResidueManagement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueManagement.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#WindErosionArea](../classes/HttpsIdir.uta.eduSockg-ontology#WindErosionArea.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |
| [HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake](../classes/HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake.md) | [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#GrowthStageRelatedMeasurement
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#Sample
class_uri: https://idir.uta.edu/sockg-ontology#GrowthStageRelatedMeasurement

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#GrowthStageRelatedMeasurement
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#Sample
class_uri: https://idir.uta.edu/sockg-ontology#GrowthStageRelatedMeasurement

```
</details>