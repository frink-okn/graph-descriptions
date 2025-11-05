

# Class: HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit




This class occurs 3863 times.


URI: [https://idir.uta.edu/sockg-ontology#ExperimentalUnit](https://idir.uta.edu/sockg-ontology#ExperimentalUnit)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit
    click HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit href "../HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit"
      GeoFeature <|-- HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit
        click GeoFeature href "../GeoFeature"
      
      HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit : dct_identifier
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit --> "0..1" RdfsLiteral : dct_identifier
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit : https___idir.uta.edu_sockg_ontology#endDate
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit --> "0..1" Date : https___idir.uta.edu_sockg_ontology#endDate
    click Date href "../Date"

        
      HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit : https___idir.uta.edu_sockg_ontology#inferred
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit --> "0..1" Boolean : https___idir.uta.edu_sockg_ontology#inferred
    click Boolean href "../Boolean"

        
      HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit : https___idir.uta.edu_sockg_ontology#startDate
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit --> "0..1" Date : https___idir.uta.edu_sockg_ontology#startDate
    click Date href "../Date"

        
      HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit : https___idir.uta.edu_sockg_ontology#unitHasAmendment
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit --> "0..1" HttpsIdir.uta.eduSockg-ontology#Amendment : https___idir.uta.edu_sockg_ontology#unitHasAmendment
    click HttpsIdir.uta.eduSockg-ontology#Amendment href "../HttpsIdir.uta.eduSockg-ontology#Amendment"

        
      HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit : https___idir.uta.edu_sockg_ontology#unitHasGrazingManagement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit --> "0..1" HttpsIdir.uta.eduSockg-ontology#GrazingManagement : https___idir.uta.edu_sockg_ontology#unitHasGrazingManagement
    click HttpsIdir.uta.eduSockg-ontology#GrazingManagement href "../HttpsIdir.uta.eduSockg-ontology#GrazingManagement"

        
      HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit : https___idir.uta.edu_sockg_ontology#unitHasGrowthStageManagement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit --> "0..1" HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement : https___idir.uta.edu_sockg_ontology#unitHasGrowthStageManagement
    click HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement href "../HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement"

        
      HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit : https___idir.uta.edu_sockg_ontology#unitHasPlantingManagement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit --> "0..1" HttpsIdir.uta.eduSockg-ontology#PlantingManagement : https___idir.uta.edu_sockg_ontology#unitHasPlantingManagement
    click HttpsIdir.uta.eduSockg-ontology#PlantingManagement href "../HttpsIdir.uta.eduSockg-ontology#PlantingManagement"

        
      HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit : https___idir.uta.edu_sockg_ontology#unitHasResidueManagement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit --> "0..1" HttpsIdir.uta.eduSockg-ontology#ResidueManagement : https___idir.uta.edu_sockg_ontology#unitHasResidueManagement
    click HttpsIdir.uta.eduSockg-ontology#ResidueManagement href "../HttpsIdir.uta.eduSockg-ontology#ResidueManagement"

        
      HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit : https___idir.uta.edu_sockg_ontology#unitHasTillageManagement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit --> "0..1" HttpsIdir.uta.eduSockg-ontology#TillageManagement : https___idir.uta.edu_sockg_ontology#unitHasTillageManagement
    click HttpsIdir.uta.eduSockg-ontology#TillageManagement href "../HttpsIdir.uta.eduSockg-ontology#TillageManagement"

        
      HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit : https___idir.uta.edu_sockg_ontology#unitUrl
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit --> "0..1" Uri : https___idir.uta.edu_sockg_ontology#unitUrl
    click Uri href "../Uri"

        
      HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit : kwgo_sfWithin
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit --> "0..1" Any : kwgo_sfWithin
    click Any href "../Any"

        
      
```





## Inheritance
* [GeoSpatialObject](../classes/GeoSpatialObject.md)
    * [GeoFeature](../classes/GeoFeature.md)
        * **HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___idir.uta.edu_sockg_ontology#unitHasAmendment](../slots/https___idir.uta.edu_sockg_ontology#unitHasAmendment.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) |  <br/>  | direct | 47106 |
| [https___idir.uta.edu_sockg_ontology#unitHasGrowthStageManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasGrowthStageManagement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement.md) |  <br/>  | direct | 5148 |
| [https___idir.uta.edu_sockg_ontology#unitHasGrazingManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasGrazingManagement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#GrazingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingManagement.md) |  <br/>  | direct | 1951 |
| [dct_identifier](../slots/dct_identifier.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | Recommended practice is to identify the resource by means of a string conform... <br/> description: An unambiguous reference to the resource within a given context. | direct | 3863 |
| [https___idir.uta.edu_sockg_ontology#endDate](../slots/https___idir.uta.edu_sockg_ontology#endDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 1965 |
| [https___idir.uta.edu_sockg_ontology#unitHasPlantingManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasPlantingManagement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#PlantingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantingManagement.md) |  <br/>  | direct | 23728 |
| [https___idir.uta.edu_sockg_ontology#inferred](../slots/https___idir.uta.edu_sockg_ontology#inferred.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) |  <br/>  | direct | 3863 |
| [https___idir.uta.edu_sockg_ontology#unitUrl](../slots/https___idir.uta.edu_sockg_ontology#unitUrl.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) |  <br/>  | direct | 23 |
| [kwgo_sfWithin](../slots/kwgo_sfWithin.md) | 0..1 <br/> [Any](../classes/Any.md) | KWG's spatial within relation <br/>  | direct | 7699 |
| [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 3362 |
| [https___idir.uta.edu_sockg_ontology#unitHasTillageManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasTillageManagement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#TillageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#TillageManagement.md) |  <br/>  | direct | 27449 |
| [https___idir.uta.edu_sockg_ontology#unitHasResidueManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasResidueManagement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#ResidueManagement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueManagement.md) |  <br/>  | direct | 3334 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassEnergy](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassEnergy.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassMineral](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassMineral.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitHasAmendment](../slots/https___idir.uta.edu_sockg_ontology#unitHasAmendment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitHasGrowthStageManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasGrowthStageManagement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitHasGrazingManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasGrazingManagement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitHasPlantingManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasPlantingManagement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#inferred](../slots/https___idir.uta.edu_sockg_ontology#inferred.md) | domain | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitUrl](../slots/https___idir.uta.edu_sockg_ontology#unitUrl.md) | domain | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitHasTillageManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasTillageManagement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitHasResidueManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasResidueManagement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#GHGFlux](../classes/HttpsIdir.uta.eduSockg-ontology#GHGFlux.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss](../classes/HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#GrazingPlants](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingPlants.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#HarvestFraction](../classes/HttpsIdir.uta.eduSockg-ontology#HarvestFraction.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency](../classes/HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilCover](../classes/HttpsIdir.uta.eduSockg-ontology#SoilCover.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityArea](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityArea.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#WeatherObservation](../classes/HttpsIdir.uta.eduSockg-ontology#WeatherObservation.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#WindErosionArea](../classes/HttpsIdir.uta.eduSockg-ontology#WindErosionArea.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |
| [HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake](../classes/HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake.md) | [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
from_schema: okns:soc-kg
rank: 1000
is_a: geo_Feature
slots:
- https___idir.uta.edu_sockg-ontology#unitHasAmendment
- https___idir.uta.edu_sockg-ontology#unitHasGrowthStageManagement
- https___idir.uta.edu_sockg-ontology#unitHasGrazingManagement
- dct_identifier
- https___idir.uta.edu_sockg-ontology#endDate
- https___idir.uta.edu_sockg-ontology#unitHasPlantingManagement
- https___idir.uta.edu_sockg-ontology#inferred
- https___idir.uta.edu_sockg-ontology#unitUrl
- kwgo_sfWithin
- https___idir.uta.edu_sockg-ontology#startDate
- https___idir.uta.edu_sockg-ontology#unitHasTillageManagement
- https___idir.uta.edu_sockg-ontology#unitHasResidueManagement
class_uri: https://idir.uta.edu/sockg-ontology#ExperimentalUnit

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
from_schema: okns:soc-kg
rank: 1000
is_a: geo_Feature
attributes:
  https___idir.uta.edu_sockg-ontology#unitHasAmendment:
    name: https___idir.uta.edu_sockg-ontology#unitHasAmendment
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    slot_uri: https://idir.uta.edu/sockg-ontology#unitHasAmendment
    alias: https___idir.uta.edu_sockg_ontology#unitHasAmendment
    owner: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    range: https___idir.uta.edu_sockg-ontology#Amendment
  https___idir.uta.edu_sockg-ontology#unitHasGrowthStageManagement:
    name: https___idir.uta.edu_sockg-ontology#unitHasGrowthStageManagement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    slot_uri: https://idir.uta.edu/sockg-ontology#unitHasGrowthStageManagement
    alias: https___idir.uta.edu_sockg_ontology#unitHasGrowthStageManagement
    owner: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    range: https___idir.uta.edu_sockg-ontology#GrowthStageManagement
  https___idir.uta.edu_sockg-ontology#unitHasGrazingManagement:
    name: https___idir.uta.edu_sockg-ontology#unitHasGrazingManagement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    slot_uri: https://idir.uta.edu/sockg-ontology#unitHasGrazingManagement
    alias: https___idir.uta.edu_sockg_ontology#unitHasGrazingManagement
    owner: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    range: https___idir.uta.edu_sockg-ontology#GrazingManagement
  dct_identifier:
    name: dct_identifier
    description: Recommended practice is to identify the resource by means of a string
      conforming to an identification system. Examples include International Standard
      Book Number (ISBN), Digital Object Identifier (DOI), and Uniform Resource Name
      (URN).  Persistent identifiers should be provided as HTTP URIs.
    title: Identifier
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: An unambiguous reference to the resource within a given context.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:identifier
    alias: dct_identifier
    owner: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Site
    - https___idir.uta.edu_sockg-ontology#Treatment
    subproperty_of: dc_identifier
    range: rdfs_Literal
  https___idir.uta.edu_sockg-ontology#endDate:
    name: https___idir.uta.edu_sockg-ontology#endDate
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#endDate
    alias: https___idir.uta.edu_sockg_ontology#endDate
    owner: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#GrazingManagement
    - https___idir.uta.edu_sockg-ontology#Location
    range: date
  https___idir.uta.edu_sockg-ontology#unitHasPlantingManagement:
    name: https___idir.uta.edu_sockg-ontology#unitHasPlantingManagement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    slot_uri: https://idir.uta.edu/sockg-ontology#unitHasPlantingManagement
    alias: https___idir.uta.edu_sockg_ontology#unitHasPlantingManagement
    owner: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    range: https___idir.uta.edu_sockg-ontology#PlantingManagement
  https___idir.uta.edu_sockg-ontology#inferred:
    name: https___idir.uta.edu_sockg-ontology#inferred
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    slot_uri: https://idir.uta.edu/sockg-ontology#inferred
    alias: https___idir.uta.edu_sockg_ontology#inferred
    owner: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    range: boolean
  https___idir.uta.edu_sockg-ontology#unitUrl:
    name: https___idir.uta.edu_sockg-ontology#unitUrl
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    slot_uri: https://idir.uta.edu/sockg-ontology#unitUrl
    alias: https___idir.uta.edu_sockg_ontology#unitUrl
    owner: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    range: uri
  kwgo_sfWithin:
    name: kwgo_sfWithin
    description: KWG's spatial within relation
    title: within (simple feature)
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:kwg
    slot_uri: kwgo:sfWithin
    alias: kwgo_sfWithin
    owner: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Site
    - kwgo_S2Cell_Level13
    subproperty_of: kwgo_spatialRelation
    range: Any
  https___idir.uta.edu_sockg-ontology#startDate:
    name: https___idir.uta.edu_sockg-ontology#startDate
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#startDate
    alias: https___idir.uta.edu_sockg_ontology#startDate
    owner: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
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
  https___idir.uta.edu_sockg-ontology#unitHasTillageManagement:
    name: https___idir.uta.edu_sockg-ontology#unitHasTillageManagement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    slot_uri: https://idir.uta.edu/sockg-ontology#unitHasTillageManagement
    alias: https___idir.uta.edu_sockg_ontology#unitHasTillageManagement
    owner: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    range: https___idir.uta.edu_sockg-ontology#TillageManagement
  https___idir.uta.edu_sockg-ontology#unitHasResidueManagement:
    name: https___idir.uta.edu_sockg-ontology#unitHasResidueManagement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    slot_uri: https://idir.uta.edu/sockg-ontology#unitHasResidueManagement
    alias: https___idir.uta.edu_sockg_ontology#unitHasResidueManagement
    owner: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    range: https___idir.uta.edu_sockg-ontology#ResidueManagement
class_uri: https://idir.uta.edu/sockg-ontology#ExperimentalUnit

```
</details>