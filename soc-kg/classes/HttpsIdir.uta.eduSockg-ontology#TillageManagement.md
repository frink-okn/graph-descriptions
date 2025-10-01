

# Class: HttpsIdir.uta.eduSockg-ontology#TillageManagement




This class occurs 27450 times.


URI: [https://idir.uta.edu/sockg-ontology#TillageManagement](https://idir.uta.edu/sockg-ontology#TillageManagement)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#TillageManagement
    click HttpsIdir.uta.eduSockg-ontology#TillageManagement href "../HttpsIdir.uta.eduSockg-ontology#TillageManagement"
      HttpsIdir.uta.eduSockg-ontology#MeasurableEntity <|-- HttpsIdir.uta.eduSockg-ontology#TillageManagement
        click HttpsIdir.uta.eduSockg-ontology#MeasurableEntity href "../HttpsIdir.uta.eduSockg-ontology#MeasurableEntity"
      
      HttpsIdir.uta.eduSockg-ontology#TillageManagement : https___idir.uta.edu_sockg_ontology#hasCrop
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#TillageManagement --> "0..1" HttpsLod.nal.usda.govNalt7140 : https___idir.uta.edu_sockg_ontology#hasCrop
    click HttpsLod.nal.usda.govNalt7140 href "../HttpsLod.nal.usda.govNalt7140"

        
      HttpsIdir.uta.eduSockg-ontology#TillageManagement : https___idir.uta.edu_sockg_ontology#hasMeasurement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#TillageManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#Measurement : https___idir.uta.edu_sockg_ontology#hasMeasurement
    click HttpsIdir.uta.eduSockg-ontology#Measurement href "../HttpsIdir.uta.eduSockg-ontology#Measurement"

        
      HttpsIdir.uta.eduSockg-ontology#TillageManagement : https___idir.uta.edu_sockg_ontology#hasTillageEvent
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#TillageManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#TillageEvent : https___idir.uta.edu_sockg_ontology#hasTillageEvent
    click HttpsIdir.uta.eduSockg-ontology#TillageEvent href "../HttpsIdir.uta.eduSockg-ontology#TillageEvent"

        
      HttpsIdir.uta.eduSockg-ontology#TillageManagement : https___idir.uta.edu_sockg_ontology#startDate
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#TillageManagement --> "0..1" Date : https___idir.uta.edu_sockg_ontology#startDate
    click Date href "../Date"

        
      HttpsIdir.uta.eduSockg-ontology#TillageManagement : https___idir.uta.edu_sockg_ontology#usesTillageMethod
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#TillageManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#TillageMethod : https___idir.uta.edu_sockg_ontology#usesTillageMethod
    click HttpsIdir.uta.eduSockg-ontology#TillageMethod href "../HttpsIdir.uta.eduSockg-ontology#TillageMethod"

        
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * **HttpsIdir.uta.eduSockg-ontology#TillageManagement**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___idir.uta.edu_sockg_ontology#hasTillageEvent](../slots/https___idir.uta.edu_sockg_ontology#hasTillageEvent.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#TillageEvent](../classes/HttpsIdir.uta.eduSockg-ontology#TillageEvent.md) |  <br/>  | direct | 27450 |
| [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | 0..1 <br/> [HttpsLod.nal.usda.govNalt7140](../classes/HttpsLod.nal.usda.govNalt7140.md) |  <br/>  | direct | 27432 |
| [https___idir.uta.edu_sockg_ontology#usesTillageMethod](../slots/https___idir.uta.edu_sockg_ontology#usesTillageMethod.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#TillageMethod](../classes/HttpsIdir.uta.eduSockg-ontology#TillageMethod.md) |  <br/>  | direct | 24709 |
| [https___idir.uta.edu_sockg_ontology#hasMeasurement](../slots/https___idir.uta.edu_sockg_ontology#hasMeasurement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Measurement](../classes/HttpsIdir.uta.eduSockg-ontology#Measurement.md) |  <br/>  | direct | 27022 |
| [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 27450 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitHasTillageManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasTillageManagement.md) | range | [HttpsIdir.uta.eduSockg-ontology#TillageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#TillageManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#TillageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#TillageManagement.md) | [https___idir.uta.edu_sockg_ontology#hasTillageEvent](../slots/https___idir.uta.edu_sockg_ontology#hasTillageEvent.md) | domain | [HttpsIdir.uta.eduSockg-ontology#TillageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#TillageManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#TillageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#TillageManagement.md) | [https___idir.uta.edu_sockg_ontology#usesTillageMethod](../slots/https___idir.uta.edu_sockg_ontology#usesTillageMethod.md) | domain | [HttpsIdir.uta.eduSockg-ontology#TillageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#TillageManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#treatmentHasTillageManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasTillageManagement.md) | range | [HttpsIdir.uta.eduSockg-ontology#TillageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#TillageManagement.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#TillageManagement
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
slots:
- https___idir.uta.edu_sockg-ontology#hasTillageEvent
- https___idir.uta.edu_sockg-ontology#hasCrop
- https___idir.uta.edu_sockg-ontology#usesTillageMethod
- https___idir.uta.edu_sockg-ontology#hasMeasurement
- https___idir.uta.edu_sockg-ontology#startDate
class_uri: https://idir.uta.edu/sockg-ontology#TillageManagement

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#TillageManagement
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
attributes:
  https___idir.uta.edu_sockg-ontology#hasTillageEvent:
    name: https___idir.uta.edu_sockg-ontology#hasTillageEvent
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#TillageManagement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasTillageEvent
    alias: https___idir.uta.edu_sockg_ontology#hasTillageEvent
    owner: https___idir.uta.edu_sockg-ontology#TillageManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#TillageManagement
    range: https___idir.uta.edu_sockg-ontology#TillageEvent
  https___idir.uta.edu_sockg-ontology#hasCrop:
    name: https___idir.uta.edu_sockg-ontology#hasCrop
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#CropRelatedMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasCrop
    alias: https___idir.uta.edu_sockg_ontology#hasCrop
    owner: https___idir.uta.edu_sockg-ontology#TillageManagement
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
  https___idir.uta.edu_sockg-ontology#usesTillageMethod:
    name: https___idir.uta.edu_sockg-ontology#usesTillageMethod
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#TillageManagement
    slot_uri: https://idir.uta.edu/sockg-ontology#usesTillageMethod
    alias: https___idir.uta.edu_sockg_ontology#usesTillageMethod
    owner: https___idir.uta.edu_sockg-ontology#TillageManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#TillageManagement
    range: https___idir.uta.edu_sockg-ontology#TillageMethod
  https___idir.uta.edu_sockg-ontology#hasMeasurement:
    name: https___idir.uta.edu_sockg-ontology#hasMeasurement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#MeasurableEntity
    slot_uri: https://idir.uta.edu/sockg-ontology#hasMeasurement
    alias: https___idir.uta.edu_sockg_ontology#hasMeasurement
    owner: https___idir.uta.edu_sockg-ontology#TillageManagement
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
  https___idir.uta.edu_sockg-ontology#startDate:
    name: https___idir.uta.edu_sockg-ontology#startDate
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#startDate
    alias: https___idir.uta.edu_sockg_ontology#startDate
    owner: https___idir.uta.edu_sockg-ontology#TillageManagement
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
class_uri: https://idir.uta.edu/sockg-ontology#TillageManagement

```
</details>