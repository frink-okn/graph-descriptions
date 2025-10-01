

# Class: HttpsIdir.uta.eduSockg-ontology#GrazingManagement




This class occurs 1951 times.


URI: [https://idir.uta.edu/sockg-ontology#GrazingManagement](https://idir.uta.edu/sockg-ontology#GrazingManagement)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#GrazingManagement
    click HttpsIdir.uta.eduSockg-ontology#GrazingManagement href "../HttpsIdir.uta.eduSockg-ontology#GrazingManagement"
      HttpsIdir.uta.eduSockg-ontology#MeasurableEntity <|-- HttpsIdir.uta.eduSockg-ontology#GrazingManagement
        click HttpsIdir.uta.eduSockg-ontology#MeasurableEntity href "../HttpsIdir.uta.eduSockg-ontology#MeasurableEntity"
      
      HttpsIdir.uta.eduSockg-ontology#GrazingManagement : https___idir.uta.edu_sockg_ontology#endDate
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#GrazingManagement --> "0..1" Date : https___idir.uta.edu_sockg_ontology#endDate
    click Date href "../Date"

        
      HttpsIdir.uta.eduSockg-ontology#GrazingManagement : https___idir.uta.edu_sockg_ontology#hasAnimalClass
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#GrazingManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#AnimalClass : https___idir.uta.edu_sockg_ontology#hasAnimalClass
    click HttpsIdir.uta.eduSockg-ontology#AnimalClass href "../HttpsIdir.uta.eduSockg-ontology#AnimalClass"

        
      HttpsIdir.uta.eduSockg-ontology#GrazingManagement : https___idir.uta.edu_sockg_ontology#hasAnimalSpecies
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#GrazingManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#AnimalSpecies : https___idir.uta.edu_sockg_ontology#hasAnimalSpecies
    click HttpsIdir.uta.eduSockg-ontology#AnimalSpecies href "../HttpsIdir.uta.eduSockg-ontology#AnimalSpecies"

        
      HttpsIdir.uta.eduSockg-ontology#GrazingManagement : https___idir.uta.edu_sockg_ontology#hasMeasurement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#GrazingManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#Measurement : https___idir.uta.edu_sockg_ontology#hasMeasurement
    click HttpsIdir.uta.eduSockg-ontology#Measurement href "../HttpsIdir.uta.eduSockg-ontology#Measurement"

        
      HttpsIdir.uta.eduSockg-ontology#GrazingManagement : https___idir.uta.edu_sockg_ontology#hasOtherEvents
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#GrazingManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#OtherEvents : https___idir.uta.edu_sockg_ontology#hasOtherEvents
    click HttpsIdir.uta.eduSockg-ontology#OtherEvents href "../HttpsIdir.uta.eduSockg-ontology#OtherEvents"

        
      HttpsIdir.uta.eduSockg-ontology#GrazingManagement : https___idir.uta.edu_sockg_ontology#startDate
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#GrazingManagement --> "0..1" Date : https___idir.uta.edu_sockg_ontology#startDate
    click Date href "../Date"

        
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * **HttpsIdir.uta.eduSockg-ontology#GrazingManagement**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___idir.uta.edu_sockg_ontology#hasOtherEvents](../slots/https___idir.uta.edu_sockg_ontology#hasOtherEvents.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#OtherEvents](../classes/HttpsIdir.uta.eduSockg-ontology#OtherEvents.md) |  <br/>  | direct | 4 |
| [https___idir.uta.edu_sockg_ontology#hasAnimalClass](../slots/https___idir.uta.edu_sockg_ontology#hasAnimalClass.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#AnimalClass](../classes/HttpsIdir.uta.eduSockg-ontology#AnimalClass.md) |  <br/>  | direct | 1833 |
| [https___idir.uta.edu_sockg_ontology#hasAnimalSpecies](../slots/https___idir.uta.edu_sockg_ontology#hasAnimalSpecies.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#AnimalSpecies](../classes/HttpsIdir.uta.eduSockg-ontology#AnimalSpecies.md) |  <br/>  | direct | 1951 |
| [https___idir.uta.edu_sockg_ontology#hasMeasurement](../slots/https___idir.uta.edu_sockg_ontology#hasMeasurement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Measurement](../classes/HttpsIdir.uta.eduSockg-ontology#Measurement.md) |  <br/>  | direct | 1951 |
| [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 1951 |
| [https___idir.uta.edu_sockg_ontology#endDate](../slots/https___idir.uta.edu_sockg_ontology#endDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 1951 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitHasGrazingManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasGrazingManagement.md) | range | [HttpsIdir.uta.eduSockg-ontology#GrazingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#GrazingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingManagement.md) | [https___idir.uta.edu_sockg_ontology#hasOtherEvents](../slots/https___idir.uta.edu_sockg_ontology#hasOtherEvents.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrazingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#GrazingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingManagement.md) | [https___idir.uta.edu_sockg_ontology#hasAnimalClass](../slots/https___idir.uta.edu_sockg_ontology#hasAnimalClass.md) | domain | [HttpsIdir.uta.eduSockg-ontology#GrazingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#treatmentHasGrazingManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasGrazingManagement.md) | range | [HttpsIdir.uta.eduSockg-ontology#GrazingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingManagement.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#GrazingManagement
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
slots:
- https___idir.uta.edu_sockg-ontology#hasOtherEvents
- https___idir.uta.edu_sockg-ontology#hasAnimalClass
- https___idir.uta.edu_sockg-ontology#hasAnimalSpecies
- https___idir.uta.edu_sockg-ontology#hasMeasurement
- https___idir.uta.edu_sockg-ontology#startDate
- https___idir.uta.edu_sockg-ontology#endDate
class_uri: https://idir.uta.edu/sockg-ontology#GrazingManagement

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#GrazingManagement
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
attributes:
  https___idir.uta.edu_sockg-ontology#hasOtherEvents:
    name: https___idir.uta.edu_sockg-ontology#hasOtherEvents
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#GrazingManagement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasOtherEvents
    alias: https___idir.uta.edu_sockg_ontology#hasOtherEvents
    owner: https___idir.uta.edu_sockg-ontology#GrazingManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#GrazingManagement
    range: https___idir.uta.edu_sockg-ontology#OtherEvents
  https___idir.uta.edu_sockg-ontology#hasAnimalClass:
    name: https___idir.uta.edu_sockg-ontology#hasAnimalClass
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#GrazingManagement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasAnimalClass
    alias: https___idir.uta.edu_sockg_ontology#hasAnimalClass
    owner: https___idir.uta.edu_sockg-ontology#GrazingManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#GrazingManagement
    range: https___idir.uta.edu_sockg-ontology#AnimalClass
  https___idir.uta.edu_sockg-ontology#hasAnimalSpecies:
    name: https___idir.uta.edu_sockg-ontology#hasAnimalSpecies
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#hasAnimalSpecies
    alias: https___idir.uta.edu_sockg_ontology#hasAnimalSpecies
    owner: https___idir.uta.edu_sockg-ontology#GrazingManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#GrazingManagement
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#AnimalSpecies
  https___idir.uta.edu_sockg-ontology#hasMeasurement:
    name: https___idir.uta.edu_sockg-ontology#hasMeasurement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#MeasurableEntity
    slot_uri: https://idir.uta.edu/sockg-ontology#hasMeasurement
    alias: https___idir.uta.edu_sockg_ontology#hasMeasurement
    owner: https___idir.uta.edu_sockg-ontology#GrazingManagement
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
    owner: https___idir.uta.edu_sockg-ontology#GrazingManagement
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
  https___idir.uta.edu_sockg-ontology#endDate:
    name: https___idir.uta.edu_sockg-ontology#endDate
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#endDate
    alias: https___idir.uta.edu_sockg_ontology#endDate
    owner: https___idir.uta.edu_sockg-ontology#GrazingManagement
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#GrazingManagement
    - https___idir.uta.edu_sockg-ontology#Location
    range: date
class_uri: https://idir.uta.edu/sockg-ontology#GrazingManagement

```
</details>