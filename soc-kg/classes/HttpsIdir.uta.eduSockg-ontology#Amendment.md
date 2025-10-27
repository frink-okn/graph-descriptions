

# Class: HttpsIdir.uta.eduSockg-ontology#Amendment




This class occurs 47106 times.


URI: [https://idir.uta.edu/sockg-ontology#Amendment](https://idir.uta.edu/sockg-ontology#Amendment)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#Amendment
    click HttpsIdir.uta.eduSockg-ontology#Amendment href "../HttpsIdir.uta.eduSockg-ontology#Amendment"
      HttpsIdir.uta.eduSockg-ontology#MeasurableEntity <|-- HttpsIdir.uta.eduSockg-ontology#Amendment
        click HttpsIdir.uta.eduSockg-ontology#MeasurableEntity href "../HttpsIdir.uta.eduSockg-ontology#MeasurableEntity"
      
      HttpsIdir.uta.eduSockg-ontology#Amendment : https___idir.uta.edu_sockg_ontology#hasAmendmentType
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Amendment --> "0..1" HttpsIdir.uta.eduSockg-ontology#AmendmentType : https___idir.uta.edu_sockg_ontology#hasAmendmentType
    click HttpsIdir.uta.eduSockg-ontology#AmendmentType href "../HttpsIdir.uta.eduSockg-ontology#AmendmentType"

        
      HttpsIdir.uta.eduSockg-ontology#Amendment : https___idir.uta.edu_sockg_ontology#hasCrop
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Amendment --> "0..1" HttpsLod.nal.usda.govNalt7140 : https___idir.uta.edu_sockg_ontology#hasCrop
    click HttpsLod.nal.usda.govNalt7140 href "../HttpsLod.nal.usda.govNalt7140"

        
      HttpsIdir.uta.eduSockg-ontology#Amendment : https___idir.uta.edu_sockg_ontology#hasMeasurement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Amendment --> "0..1" HttpsIdir.uta.eduSockg-ontology#Measurement : https___idir.uta.edu_sockg_ontology#hasMeasurement
    click HttpsIdir.uta.eduSockg-ontology#Measurement href "../HttpsIdir.uta.eduSockg-ontology#Measurement"

        
      HttpsIdir.uta.eduSockg-ontology#Amendment : https___idir.uta.edu_sockg_ontology#hasPesticideActiveIngredient
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Amendment --> "0..1" HttpsIdir.uta.eduSockg-ontology#ActiveIngredient : https___idir.uta.edu_sockg_ontology#hasPesticideActiveIngredient
    click HttpsIdir.uta.eduSockg-ontology#ActiveIngredient href "../HttpsIdir.uta.eduSockg-ontology#ActiveIngredient"

        
      HttpsIdir.uta.eduSockg-ontology#Amendment : https___idir.uta.edu_sockg_ontology#hasPesticideTarget
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Amendment --> "0..1" HttpsIdir.uta.eduSockg-ontology#PesticideTarget : https___idir.uta.edu_sockg_ontology#hasPesticideTarget
    click HttpsIdir.uta.eduSockg-ontology#PesticideTarget href "../HttpsIdir.uta.eduSockg-ontology#PesticideTarget"

        
      HttpsIdir.uta.eduSockg-ontology#Amendment : https___idir.uta.edu_sockg_ontology#startDate
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Amendment --> "0..1" Date : https___idir.uta.edu_sockg_ontology#startDate
    click Date href "../Date"

        
      HttpsIdir.uta.eduSockg-ontology#Amendment : https___idir.uta.edu_sockg_ontology#usesIrrigation
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Amendment --> "0..1" HttpsIdir.uta.eduSockg-ontology#Irrigation : https___idir.uta.edu_sockg_ontology#usesIrrigation
    click HttpsIdir.uta.eduSockg-ontology#Irrigation href "../HttpsIdir.uta.eduSockg-ontology#Irrigation"

        
      HttpsIdir.uta.eduSockg-ontology#Amendment : https___idir.uta.edu_sockg_ontology#withPesticidePlacement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Amendment --> "0..1" HttpsIdir.uta.eduSockg-ontology#PesticidePlacement : https___idir.uta.edu_sockg_ontology#withPesticidePlacement
    click HttpsIdir.uta.eduSockg-ontology#PesticidePlacement href "../HttpsIdir.uta.eduSockg-ontology#PesticidePlacement"

        
      HttpsIdir.uta.eduSockg-ontology#Amendment : https___idir.uta.edu_sockg_ontology#withPlacement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Amendment --> "0..1" HttpsIdir.uta.eduSockg-ontology#AmendmentPlacement : https___idir.uta.edu_sockg_ontology#withPlacement
    click HttpsIdir.uta.eduSockg-ontology#AmendmentPlacement href "../HttpsIdir.uta.eduSockg-ontology#AmendmentPlacement"

        
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * **HttpsIdir.uta.eduSockg-ontology#Amendment**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___idir.uta.edu_sockg_ontology#withPlacement](../slots/https___idir.uta.edu_sockg_ontology#withPlacement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#AmendmentPlacement](../classes/HttpsIdir.uta.eduSockg-ontology#AmendmentPlacement.md) |  <br/>  | direct | 24794 |
| [https___idir.uta.edu_sockg_ontology#hasPesticideTarget](../slots/https___idir.uta.edu_sockg_ontology#hasPesticideTarget.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#PesticideTarget](../classes/HttpsIdir.uta.eduSockg-ontology#PesticideTarget.md) |  <br/>  | direct | 12841 |
| [https___idir.uta.edu_sockg_ontology#hasMeasurement](../slots/https___idir.uta.edu_sockg_ontology#hasMeasurement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Measurement](../classes/HttpsIdir.uta.eduSockg-ontology#Measurement.md) |  <br/>  | direct | 122893 |
| [https___idir.uta.edu_sockg_ontology#hasPesticideActiveIngredient](../slots/https___idir.uta.edu_sockg_ontology#hasPesticideActiveIngredient.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#ActiveIngredient](../classes/HttpsIdir.uta.eduSockg-ontology#ActiveIngredient.md) |  <br/>  | direct | 16104 |
| [https___idir.uta.edu_sockg_ontology#withPesticidePlacement](../slots/https___idir.uta.edu_sockg_ontology#withPesticidePlacement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#PesticidePlacement](../classes/HttpsIdir.uta.eduSockg-ontology#PesticidePlacement.md) |  <br/>  | direct | 9498 |
| [https___idir.uta.edu_sockg_ontology#usesIrrigation](../slots/https___idir.uta.edu_sockg_ontology#usesIrrigation.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Irrigation](../classes/HttpsIdir.uta.eduSockg-ontology#Irrigation.md) |  <br/>  | direct | 6063 |
| [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 47106 |
| [https___idir.uta.edu_sockg_ontology#hasAmendmentType](../slots/https___idir.uta.edu_sockg_ontology#hasAmendmentType.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#AmendmentType](../classes/HttpsIdir.uta.eduSockg-ontology#AmendmentType.md) |  <br/>  | direct | 25357 |
| [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | 0..1 <br/> [HttpsLod.nal.usda.govNalt7140](../classes/HttpsLod.nal.usda.govNalt7140.md) |  <br/>  | direct | 45261 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) | [https___idir.uta.edu_sockg_ontology#withPlacement](../slots/https___idir.uta.edu_sockg_ontology#withPlacement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) | [https___idir.uta.edu_sockg_ontology#hasPesticideTarget](../slots/https___idir.uta.edu_sockg_ontology#hasPesticideTarget.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) | [https___idir.uta.edu_sockg_ontology#hasPesticideActiveIngredient](../slots/https___idir.uta.edu_sockg_ontology#hasPesticideActiveIngredient.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) | [https___idir.uta.edu_sockg_ontology#withPesticidePlacement](../slots/https___idir.uta.edu_sockg_ontology#withPesticidePlacement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) | [https___idir.uta.edu_sockg_ontology#usesIrrigation](../slots/https___idir.uta.edu_sockg_ontology#usesIrrigation.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitHasAmendment](../slots/https___idir.uta.edu_sockg_ontology#unitHasAmendment.md) | range | [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#treatmentHasAmendment](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasAmendment.md) | range | [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Amendment
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
slots:
- https___idir.uta.edu_sockg-ontology#withPlacement
- https___idir.uta.edu_sockg-ontology#hasPesticideTarget
- https___idir.uta.edu_sockg-ontology#hasMeasurement
- https___idir.uta.edu_sockg-ontology#hasPesticideActiveIngredient
- https___idir.uta.edu_sockg-ontology#withPesticidePlacement
- https___idir.uta.edu_sockg-ontology#usesIrrigation
- https___idir.uta.edu_sockg-ontology#startDate
- https___idir.uta.edu_sockg-ontology#hasAmendmentType
- https___idir.uta.edu_sockg-ontology#hasCrop
class_uri: https://idir.uta.edu/sockg-ontology#Amendment

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Amendment
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
attributes:
  https___idir.uta.edu_sockg-ontology#withPlacement:
    name: https___idir.uta.edu_sockg-ontology#withPlacement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Amendment
    slot_uri: https://idir.uta.edu/sockg-ontology#withPlacement
    alias: https___idir.uta.edu_sockg_ontology#withPlacement
    owner: https___idir.uta.edu_sockg-ontology#Amendment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Amendment
    range: https___idir.uta.edu_sockg-ontology#AmendmentPlacement
  https___idir.uta.edu_sockg-ontology#hasPesticideTarget:
    name: https___idir.uta.edu_sockg-ontology#hasPesticideTarget
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Amendment
    slot_uri: https://idir.uta.edu/sockg-ontology#hasPesticideTarget
    alias: https___idir.uta.edu_sockg_ontology#hasPesticideTarget
    owner: https___idir.uta.edu_sockg-ontology#Amendment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Amendment
    range: https___idir.uta.edu_sockg-ontology#PesticideTarget
  https___idir.uta.edu_sockg-ontology#hasMeasurement:
    name: https___idir.uta.edu_sockg-ontology#hasMeasurement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#MeasurableEntity
    slot_uri: https://idir.uta.edu/sockg-ontology#hasMeasurement
    alias: https___idir.uta.edu_sockg_ontology#hasMeasurement
    owner: https___idir.uta.edu_sockg-ontology#Amendment
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
  https___idir.uta.edu_sockg-ontology#hasPesticideActiveIngredient:
    name: https___idir.uta.edu_sockg-ontology#hasPesticideActiveIngredient
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Amendment
    slot_uri: https://idir.uta.edu/sockg-ontology#hasPesticideActiveIngredient
    alias: https___idir.uta.edu_sockg_ontology#hasPesticideActiveIngredient
    owner: https___idir.uta.edu_sockg-ontology#Amendment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Amendment
    range: https___idir.uta.edu_sockg-ontology#ActiveIngredient
  https___idir.uta.edu_sockg-ontology#withPesticidePlacement:
    name: https___idir.uta.edu_sockg-ontology#withPesticidePlacement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Amendment
    slot_uri: https://idir.uta.edu/sockg-ontology#withPesticidePlacement
    alias: https___idir.uta.edu_sockg_ontology#withPesticidePlacement
    owner: https___idir.uta.edu_sockg-ontology#Amendment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Amendment
    range: https___idir.uta.edu_sockg-ontology#PesticidePlacement
  https___idir.uta.edu_sockg-ontology#usesIrrigation:
    name: https___idir.uta.edu_sockg-ontology#usesIrrigation
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Amendment
    slot_uri: https://idir.uta.edu/sockg-ontology#usesIrrigation
    alias: https___idir.uta.edu_sockg_ontology#usesIrrigation
    owner: https___idir.uta.edu_sockg-ontology#Amendment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Amendment
    range: https___idir.uta.edu_sockg-ontology#Irrigation
  https___idir.uta.edu_sockg-ontology#startDate:
    name: https___idir.uta.edu_sockg-ontology#startDate
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#startDate
    alias: https___idir.uta.edu_sockg_ontology#startDate
    owner: https___idir.uta.edu_sockg-ontology#Amendment
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
  https___idir.uta.edu_sockg-ontology#hasAmendmentType:
    name: https___idir.uta.edu_sockg-ontology#hasAmendmentType
    from_schema: okns:soc-kg
    rank: 1000
    slot_uri: https://idir.uta.edu/sockg-ontology#hasAmendmentType
    alias: https___idir.uta.edu_sockg_ontology#hasAmendmentType
    owner: https___idir.uta.edu_sockg-ontology#Amendment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Amendment
    range: https___idir.uta.edu_sockg-ontology#AmendmentType
  https___idir.uta.edu_sockg-ontology#hasCrop:
    name: https___idir.uta.edu_sockg-ontology#hasCrop
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#CropRelatedMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasCrop
    alias: https___idir.uta.edu_sockg_ontology#hasCrop
    owner: https___idir.uta.edu_sockg-ontology#Amendment
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
class_uri: https://idir.uta.edu/sockg-ontology#Amendment

```
</details>