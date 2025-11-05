

# Class: HttpsIdir.uta.eduSockg-ontology#ResidueManagement




This class occurs 3334 times.


URI: [https://idir.uta.edu/sockg-ontology#ResidueManagement](https://idir.uta.edu/sockg-ontology#ResidueManagement)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#ResidueManagement
    click HttpsIdir.uta.eduSockg-ontology#ResidueManagement href "../HttpsIdir.uta.eduSockg-ontology#ResidueManagement"
      HttpsIdir.uta.eduSockg-ontology#MeasurableEntity <|-- HttpsIdir.uta.eduSockg-ontology#ResidueManagement
        click HttpsIdir.uta.eduSockg-ontology#MeasurableEntity href "../HttpsIdir.uta.eduSockg-ontology#MeasurableEntity"
      
      HttpsIdir.uta.eduSockg-ontology#ResidueManagement : https___idir.uta.edu_sockg_ontology#hasCrop
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ResidueManagement --> "0..1" HttpsLod.nal.usda.govNalt7140 : https___idir.uta.edu_sockg_ontology#hasCrop
    click HttpsLod.nal.usda.govNalt7140 href "../HttpsLod.nal.usda.govNalt7140"

        
      HttpsIdir.uta.eduSockg-ontology#ResidueManagement : https___idir.uta.edu_sockg_ontology#hasGrowthStage
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ResidueManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#GrowthStage : https___idir.uta.edu_sockg_ontology#hasGrowthStage
    click HttpsIdir.uta.eduSockg-ontology#GrowthStage href "../HttpsIdir.uta.eduSockg-ontology#GrowthStage"

        
      HttpsIdir.uta.eduSockg-ontology#ResidueManagement : https___idir.uta.edu_sockg_ontology#hasMeasurement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ResidueManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#Measurement : https___idir.uta.edu_sockg_ontology#hasMeasurement
    click HttpsIdir.uta.eduSockg-ontology#Measurement href "../HttpsIdir.uta.eduSockg-ontology#Measurement"

        
      HttpsIdir.uta.eduSockg-ontology#ResidueManagement : https___idir.uta.edu_sockg_ontology#startDate
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ResidueManagement --> "0..1" Date : https___idir.uta.edu_sockg_ontology#startDate
    click Date href "../Date"

        
      HttpsIdir.uta.eduSockg-ontology#ResidueManagement : https___idir.uta.edu_sockg_ontology#usesEquipment
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ResidueManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#Equipment : https___idir.uta.edu_sockg_ontology#usesEquipment
    click HttpsIdir.uta.eduSockg-ontology#Equipment href "../HttpsIdir.uta.eduSockg-ontology#Equipment"

        
      HttpsIdir.uta.eduSockg-ontology#ResidueManagement : https___idir.uta.edu_sockg_ontology#withCuttingHeight
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ResidueManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#CuttingHeight : https___idir.uta.edu_sockg_ontology#withCuttingHeight
    click HttpsIdir.uta.eduSockg-ontology#CuttingHeight href "../HttpsIdir.uta.eduSockg-ontology#CuttingHeight"

        
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * **HttpsIdir.uta.eduSockg-ontology#ResidueManagement**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___idir.uta.edu_sockg_ontology#usesEquipment](../slots/https___idir.uta.edu_sockg_ontology#usesEquipment.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Equipment](../classes/HttpsIdir.uta.eduSockg-ontology#Equipment.md) |  <br/>  | direct | 3070 |
| [https___idir.uta.edu_sockg_ontology#hasMeasurement](../slots/https___idir.uta.edu_sockg_ontology#hasMeasurement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Measurement](../classes/HttpsIdir.uta.eduSockg-ontology#Measurement.md) |  <br/>  | direct | 4161 |
| [https___idir.uta.edu_sockg_ontology#withCuttingHeight](../slots/https___idir.uta.edu_sockg_ontology#withCuttingHeight.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#CuttingHeight](../classes/HttpsIdir.uta.eduSockg-ontology#CuttingHeight.md) |  <br/>  | direct | 2954 |
| [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 3334 |
| [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#GrowthStage](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStage.md) |  <br/>  | direct | 1675 |
| [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | 0..1 <br/> [HttpsLod.nal.usda.govNalt7140](../classes/HttpsLod.nal.usda.govNalt7140.md) |  <br/>  | direct | 3334 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitHasResidueManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasResidueManagement.md) | range | [HttpsIdir.uta.eduSockg-ontology#ResidueManagement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#ResidueManagement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueManagement.md) | [https___idir.uta.edu_sockg_ontology#usesEquipment](../slots/https___idir.uta.edu_sockg_ontology#usesEquipment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#ResidueManagement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#ResidueManagement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueManagement.md) | [https___idir.uta.edu_sockg_ontology#withCuttingHeight](../slots/https___idir.uta.edu_sockg_ontology#withCuttingHeight.md) | domain | [HttpsIdir.uta.eduSockg-ontology#ResidueManagement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#treatmentHasResidueManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasResidueManagement.md) | range | [HttpsIdir.uta.eduSockg-ontology#ResidueManagement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueManagement.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#ResidueManagement
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
slots:
- https___idir.uta.edu_sockg-ontology#usesEquipment
- https___idir.uta.edu_sockg-ontology#hasMeasurement
- https___idir.uta.edu_sockg-ontology#withCuttingHeight
- https___idir.uta.edu_sockg-ontology#startDate
- https___idir.uta.edu_sockg-ontology#hasGrowthStage
- https___idir.uta.edu_sockg-ontology#hasCrop
class_uri: https://idir.uta.edu/sockg-ontology#ResidueManagement

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#ResidueManagement
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
attributes:
  https___idir.uta.edu_sockg-ontology#usesEquipment:
    name: https___idir.uta.edu_sockg-ontology#usesEquipment
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#ResidueManagement
    slot_uri: https://idir.uta.edu/sockg-ontology#usesEquipment
    alias: https___idir.uta.edu_sockg_ontology#usesEquipment
    owner: https___idir.uta.edu_sockg-ontology#ResidueManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ResidueManagement
    range: https___idir.uta.edu_sockg-ontology#Equipment
  https___idir.uta.edu_sockg-ontology#hasMeasurement:
    name: https___idir.uta.edu_sockg-ontology#hasMeasurement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#MeasurableEntity
    slot_uri: https://idir.uta.edu/sockg-ontology#hasMeasurement
    alias: https___idir.uta.edu_sockg_ontology#hasMeasurement
    owner: https___idir.uta.edu_sockg-ontology#ResidueManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Amendment
    - https___idir.uta.edu_sockg-ontology#BiomassCarbohydrate
    - https___idir.uta.edu_sockg-ontology#BiomassEnergy
    - https___idir.uta.edu_sockg-ontology#BiomassMineral
    - https___idir.uta.edu_sockg-ontology#GHGFlux
    - https___idir.uta.edu_sockg-ontology#GasNutrientLoss
    - https___idir.uta.edu_sockg-ontology#GrazingManagement
    - https___idir.uta.edu_sockg-ontology#GrazingPlants
    - https___idir.uta.edu_sockg-ontology#HarvestFraction
    - https___idir.uta.edu_sockg-ontology#NutrientEfficiency
    - https___idir.uta.edu_sockg-ontology#PlantingManagement
    - https___idir.uta.edu_sockg-ontology#ResidueManagement
    - https___idir.uta.edu_sockg-ontology#ResidueMeasurement
    - https___idir.uta.edu_sockg-ontology#SoilBiologicalSample
    - https___idir.uta.edu_sockg-ontology#SoilChemicalSample
    - https___idir.uta.edu_sockg-ontology#SoilPhysicalSample
    - https___idir.uta.edu_sockg-ontology#TillageManagement
    - https___idir.uta.edu_sockg-ontology#WaterQualityArea
    - https___idir.uta.edu_sockg-ontology#WaterQualityConcentration
    - https___idir.uta.edu_sockg-ontology#WeatherObservation
    - https___idir.uta.edu_sockg-ontology#WindErosionArea
    - https___idir.uta.edu_sockg-ontology#YieldNutrientUptake
    range: https___idir.uta.edu_sockg-ontology#Measurement
  https___idir.uta.edu_sockg-ontology#withCuttingHeight:
    name: https___idir.uta.edu_sockg-ontology#withCuttingHeight
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#ResidueManagement
    slot_uri: https://idir.uta.edu/sockg-ontology#withCuttingHeight
    alias: https___idir.uta.edu_sockg_ontology#withCuttingHeight
    owner: https___idir.uta.edu_sockg-ontology#ResidueManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ResidueManagement
    range: https___idir.uta.edu_sockg-ontology#CuttingHeight
  https___idir.uta.edu_sockg-ontology#startDate:
    name: https___idir.uta.edu_sockg-ontology#startDate
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#startDate
    alias: https___idir.uta.edu_sockg_ontology#startDate
    owner: https___idir.uta.edu_sockg-ontology#ResidueManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Amendment
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#GrazingManagement
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#PlantingManagement
    - https___idir.uta.edu_sockg-ontology#ResidueManagement
    - https___idir.uta.edu_sockg-ontology#TillageManagement
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: date
  https___idir.uta.edu_sockg-ontology#hasGrowthStage:
    name: https___idir.uta.edu_sockg-ontology#hasGrowthStage
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#GrowthStageRelatedMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasGrowthStage
    alias: https___idir.uta.edu_sockg_ontology#hasGrowthStage
    owner: https___idir.uta.edu_sockg-ontology#ResidueManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#BiomassCarbohydrate
    - https___idir.uta.edu_sockg-ontology#BiomassEnergy
    - https___idir.uta.edu_sockg-ontology#BiomassMineral
    - https___idir.uta.edu_sockg-ontology#GasNutrientLoss
    - https___idir.uta.edu_sockg-ontology#GrazingPlants
    - https___idir.uta.edu_sockg-ontology#GrowthStageManagement
    - https___idir.uta.edu_sockg-ontology#HarvestFraction
    - https___idir.uta.edu_sockg-ontology#NutrientEfficiency
    - https___idir.uta.edu_sockg-ontology#ResidueManagement
    - https___idir.uta.edu_sockg-ontology#ResidueMeasurement
    - https___idir.uta.edu_sockg-ontology#WaterQualityConcentration
    - https___idir.uta.edu_sockg-ontology#WindErosionArea
    - https___idir.uta.edu_sockg-ontology#YieldNutrientUptake
    range: https___idir.uta.edu_sockg-ontology#GrowthStage
  https___idir.uta.edu_sockg-ontology#hasCrop:
    name: https___idir.uta.edu_sockg-ontology#hasCrop
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#CropRelatedMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasCrop
    alias: https___idir.uta.edu_sockg_ontology#hasCrop
    owner: https___idir.uta.edu_sockg-ontology#ResidueManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Amendment
    - https___idir.uta.edu_sockg-ontology#BiomassCarbohydrate
    - https___idir.uta.edu_sockg-ontology#BiomassEnergy
    - https___idir.uta.edu_sockg-ontology#BiomassMineral
    - https___idir.uta.edu_sockg-ontology#GHGFlux
    - https___idir.uta.edu_sockg-ontology#GasNutrientLoss
    - https___idir.uta.edu_sockg-ontology#GrowthStageManagement
    - https___idir.uta.edu_sockg-ontology#HarvestFraction
    - https___idir.uta.edu_sockg-ontology#NutrientEfficiency
    - https___idir.uta.edu_sockg-ontology#PlantingManagement
    - https___idir.uta.edu_sockg-ontology#ResidueManagement
    - https___idir.uta.edu_sockg-ontology#ResidueMeasurement
    - https___idir.uta.edu_sockg-ontology#SoilCover
    - https___idir.uta.edu_sockg-ontology#TillageManagement
    - https___idir.uta.edu_sockg-ontology#WaterQualityConcentration
    - https___idir.uta.edu_sockg-ontology#YieldNutrientUptake
    range: https___lod.nal.usda.gov_nalt_7140
class_uri: https://idir.uta.edu/sockg-ontology#ResidueManagement

```
</details>