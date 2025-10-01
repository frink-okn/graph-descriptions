

# Class: HttpsIdir.uta.eduSockg-ontology#PlantingManagement




This class occurs 23728 times.


URI: [https://idir.uta.edu/sockg-ontology#PlantingManagement](https://idir.uta.edu/sockg-ontology#PlantingManagement)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#PlantingManagement
    click HttpsIdir.uta.eduSockg-ontology#PlantingManagement href "../HttpsIdir.uta.eduSockg-ontology#PlantingManagement"
      HttpsIdir.uta.eduSockg-ontology#MeasurableEntity <|-- HttpsIdir.uta.eduSockg-ontology#PlantingManagement
        click HttpsIdir.uta.eduSockg-ontology#MeasurableEntity href "../HttpsIdir.uta.eduSockg-ontology#MeasurableEntity"
      
      HttpsIdir.uta.eduSockg-ontology#PlantingManagement : https___idir.uta.edu_sockg_ontology#hasCrop
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#PlantingManagement --> "0..1" HttpsLod.nal.usda.govNalt7140 : https___idir.uta.edu_sockg_ontology#hasCrop
    click HttpsLod.nal.usda.govNalt7140 href "../HttpsLod.nal.usda.govNalt7140"

        
      HttpsIdir.uta.eduSockg-ontology#PlantingManagement : https___idir.uta.edu_sockg_ontology#hasCultivar
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#PlantingManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#Cultivar : https___idir.uta.edu_sockg_ontology#hasCultivar
    click HttpsIdir.uta.eduSockg-ontology#Cultivar href "../HttpsIdir.uta.eduSockg-ontology#Cultivar"

        
      HttpsIdir.uta.eduSockg-ontology#PlantingManagement : https___idir.uta.edu_sockg_ontology#hasMeasurement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#PlantingManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#Measurement : https___idir.uta.edu_sockg_ontology#hasMeasurement
    click HttpsIdir.uta.eduSockg-ontology#Measurement href "../HttpsIdir.uta.eduSockg-ontology#Measurement"

        
      HttpsIdir.uta.eduSockg-ontology#PlantingManagement : https___idir.uta.edu_sockg_ontology#startDate
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#PlantingManagement --> "0..1" Date : https___idir.uta.edu_sockg_ontology#startDate
    click Date href "../Date"

        
      HttpsIdir.uta.eduSockg-ontology#PlantingManagement : https___idir.uta.edu_sockg_ontology#usesPlantingMethod
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#PlantingManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#PlantingMethod : https___idir.uta.edu_sockg_ontology#usesPlantingMethod
    click HttpsIdir.uta.eduSockg-ontology#PlantingMethod href "../HttpsIdir.uta.eduSockg-ontology#PlantingMethod"

        
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * **HttpsIdir.uta.eduSockg-ontology#PlantingManagement**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | 0..1 <br/> [HttpsLod.nal.usda.govNalt7140](../classes/HttpsLod.nal.usda.govNalt7140.md) |  <br/>  | direct | 23728 |
| [https___idir.uta.edu_sockg_ontology#hasMeasurement](../slots/https___idir.uta.edu_sockg_ontology#hasMeasurement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Measurement](../classes/HttpsIdir.uta.eduSockg-ontology#Measurement.md) |  <br/>  | direct | 84758 |
| [https___idir.uta.edu_sockg_ontology#hasCultivar](../slots/https___idir.uta.edu_sockg_ontology#hasCultivar.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Cultivar](../classes/HttpsIdir.uta.eduSockg-ontology#Cultivar.md) |  <br/>  | direct | 20926 |
| [https___idir.uta.edu_sockg_ontology#usesPlantingMethod](../slots/https___idir.uta.edu_sockg_ontology#usesPlantingMethod.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#PlantingMethod](../classes/HttpsIdir.uta.eduSockg-ontology#PlantingMethod.md) |  <br/>  | direct | 22592 |
| [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 23728 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitHasPlantingManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasPlantingManagement.md) | range | [HttpsIdir.uta.eduSockg-ontology#PlantingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantingManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#PlantingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantingManagement.md) | [https___idir.uta.edu_sockg_ontology#hasCultivar](../slots/https___idir.uta.edu_sockg_ontology#hasCultivar.md) | domain | [HttpsIdir.uta.eduSockg-ontology#PlantingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantingManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#PlantingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantingManagement.md) | [https___idir.uta.edu_sockg_ontology#usesPlantingMethod](../slots/https___idir.uta.edu_sockg_ontology#usesPlantingMethod.md) | domain | [HttpsIdir.uta.eduSockg-ontology#PlantingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantingManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#treatmentHasPlantingManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasPlantingManagement.md) | range | [HttpsIdir.uta.eduSockg-ontology#PlantingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantingManagement.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#PlantingManagement
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
slots:
- https___idir.uta.edu_sockg-ontology#hasCrop
- https___idir.uta.edu_sockg-ontology#hasMeasurement
- https___idir.uta.edu_sockg-ontology#hasCultivar
- https___idir.uta.edu_sockg-ontology#usesPlantingMethod
- https___idir.uta.edu_sockg-ontology#startDate
class_uri: https://idir.uta.edu/sockg-ontology#PlantingManagement

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#PlantingManagement
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
attributes:
  https___idir.uta.edu_sockg-ontology#hasCrop:
    name: https___idir.uta.edu_sockg-ontology#hasCrop
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#CropRelatedMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasCrop
    alias: https___idir.uta.edu_sockg_ontology#hasCrop
    owner: https___idir.uta.edu_sockg-ontology#PlantingManagement
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
  https___idir.uta.edu_sockg-ontology#hasMeasurement:
    name: https___idir.uta.edu_sockg-ontology#hasMeasurement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#MeasurableEntity
    slot_uri: https://idir.uta.edu/sockg-ontology#hasMeasurement
    alias: https___idir.uta.edu_sockg_ontology#hasMeasurement
    owner: https___idir.uta.edu_sockg-ontology#PlantingManagement
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
  https___idir.uta.edu_sockg-ontology#hasCultivar:
    name: https___idir.uta.edu_sockg-ontology#hasCultivar
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#PlantingManagement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasCultivar
    alias: https___idir.uta.edu_sockg_ontology#hasCultivar
    owner: https___idir.uta.edu_sockg-ontology#PlantingManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#PlantingManagement
    range: https___idir.uta.edu_sockg-ontology#Cultivar
  https___idir.uta.edu_sockg-ontology#usesPlantingMethod:
    name: https___idir.uta.edu_sockg-ontology#usesPlantingMethod
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#PlantingManagement
    slot_uri: https://idir.uta.edu/sockg-ontology#usesPlantingMethod
    alias: https___idir.uta.edu_sockg_ontology#usesPlantingMethod
    owner: https___idir.uta.edu_sockg-ontology#PlantingManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#PlantingManagement
    range: https___idir.uta.edu_sockg-ontology#PlantingMethod
  https___idir.uta.edu_sockg-ontology#startDate:
    name: https___idir.uta.edu_sockg-ontology#startDate
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#startDate
    alias: https___idir.uta.edu_sockg_ontology#startDate
    owner: https___idir.uta.edu_sockg-ontology#PlantingManagement
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
class_uri: https://idir.uta.edu/sockg-ontology#PlantingManagement

```
</details>