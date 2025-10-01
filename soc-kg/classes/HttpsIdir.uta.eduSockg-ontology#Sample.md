

# Class: No class (entity type) name specified -- this class is noted as a superclass of another class in this graph but has not itself been defined. (https___idir.uta.edu_sockg-ontology#Sample)





URI: [https://idir.uta.edu/sockg-ontology#Sample](https://idir.uta.edu/sockg-ontology#Sample)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#Sample
    click HttpsIdir.uta.eduSockg-ontology#Sample href "../HttpsIdir.uta.eduSockg-ontology#Sample"
      HttpsIdir.uta.eduSockg-ontology#MeasurableEntity <|-- HttpsIdir.uta.eduSockg-ontology#Sample
        click HttpsIdir.uta.eduSockg-ontology#MeasurableEntity href "../HttpsIdir.uta.eduSockg-ontology#MeasurableEntity"
      

      HttpsIdir.uta.eduSockg-ontology#Sample <|-- HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement
        click HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement href "../HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement"
      HttpsIdir.uta.eduSockg-ontology#Sample <|-- HttpsIdir.uta.eduSockg-ontology#ErosionMeasurement
        click HttpsIdir.uta.eduSockg-ontology#ErosionMeasurement href "../HttpsIdir.uta.eduSockg-ontology#ErosionMeasurement"
      HttpsIdir.uta.eduSockg-ontology#Sample <|-- HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement
        click HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement href "../HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement"
      HttpsIdir.uta.eduSockg-ontology#Sample <|-- HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement
        click HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement href "../HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement"
      HttpsIdir.uta.eduSockg-ontology#Sample <|-- HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement
        click HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement href "../HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement"
      HttpsIdir.uta.eduSockg-ontology#Sample <|-- HttpsIdir.uta.eduSockg-ontology#QualityMeasurement
        click HttpsIdir.uta.eduSockg-ontology#QualityMeasurement href "../HttpsIdir.uta.eduSockg-ontology#QualityMeasurement"
      
      
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * **HttpsIdir.uta.eduSockg-ontology#Sample**
        * [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md)
        * [HttpsIdir.uta.eduSockg-ontology#ErosionMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#ErosionMeasurement.md)
        * [HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageRelatedMeasurement.md)
        * [HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantFractionRelatedMeasurement.md)
        * [HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement.md)
        * [HttpsIdir.uta.eduSockg-ontology#QualityMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#QualityMeasurement.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassEnergy](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassEnergy.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassEnergy](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassEnergy.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassMineral](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassMineral.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassMineral](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassMineral.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#GHGFlux](../classes/HttpsIdir.uta.eduSockg-ontology#GHGFlux.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#GHGFlux](../classes/HttpsIdir.uta.eduSockg-ontology#GHGFlux.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss](../classes/HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss](../classes/HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#GrazingPlants](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingPlants.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#GrazingPlants](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingPlants.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#HarvestFraction](../classes/HttpsIdir.uta.eduSockg-ontology#HarvestFraction.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#HarvestFraction](../classes/HttpsIdir.uta.eduSockg-ontology#HarvestFraction.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency](../classes/HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency](../classes/HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilCover](../classes/HttpsIdir.uta.eduSockg-ontology#SoilCover.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilCover](../classes/HttpsIdir.uta.eduSockg-ontology#SoilCover.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityArea](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityArea.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityArea](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityArea.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#WeatherObservation](../classes/HttpsIdir.uta.eduSockg-ontology#WeatherObservation.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#WeatherObservation](../classes/HttpsIdir.uta.eduSockg-ontology#WeatherObservation.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#WindErosionArea](../classes/HttpsIdir.uta.eduSockg-ontology#WindErosionArea.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#WindErosionArea](../classes/HttpsIdir.uta.eduSockg-ontology#WindErosionArea.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake](../classes/HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |
| [HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake](../classes/HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Sample
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
class_uri: https://idir.uta.edu/sockg-ontology#Sample

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Sample
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
class_uri: https://idir.uta.edu/sockg-ontology#Sample

```
</details>