

# Class: HttpsIdir.uta.eduSockg-ontology#WindErosionArea




This class occurs 34 times.


URI: [https://idir.uta.edu/sockg-ontology#WindErosionArea](https://idir.uta.edu/sockg-ontology#WindErosionArea)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#WindErosionArea
    click HttpsIdir.uta.eduSockg-ontology#WindErosionArea href "../HttpsIdir.uta.eduSockg-ontology#WindErosionArea"
      HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#WindErosionArea
        click HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement href "../HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement"
      
      HttpsIdir.uta.eduSockg-ontology#WindErosionArea : dct_date
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WindErosionArea --> "0..1" RdfsLiteral : dct_date
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpsIdir.uta.eduSockg-ontology#WindErosionArea : https___idir.uta.edu_sockg_ontology#fromUnit
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WindErosionArea --> "0..1" Any : https___idir.uta.edu_sockg_ontology#fromUnit
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#WindErosionArea : https___idir.uta.edu_sockg_ontology#hasGrowthStage
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WindErosionArea --> "0..1" HttpsIdir.uta.eduSockg-ontology#GrowthStage : https___idir.uta.edu_sockg_ontology#hasGrowthStage
    click HttpsIdir.uta.eduSockg-ontology#GrowthStage href "../HttpsIdir.uta.eduSockg-ontology#GrowthStage"

        
      HttpsIdir.uta.eduSockg-ontology#WindErosionArea : https___idir.uta.edu_sockg_ontology#hasLossesOrDeposition
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WindErosionArea --> "0..1" HttpsIdir.uta.eduSockg-ontology#LossesOrDeposition : https___idir.uta.edu_sockg_ontology#hasLossesOrDeposition
    click HttpsIdir.uta.eduSockg-ontology#LossesOrDeposition href "../HttpsIdir.uta.eduSockg-ontology#LossesOrDeposition"

        
      HttpsIdir.uta.eduSockg-ontology#WindErosionArea : https___idir.uta.edu_sockg_ontology#hasMeasurement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WindErosionArea --> "0..1" HttpsIdir.uta.eduSockg-ontology#Measurement : https___idir.uta.edu_sockg_ontology#hasMeasurement
    click HttpsIdir.uta.eduSockg-ontology#Measurement href "../HttpsIdir.uta.eduSockg-ontology#Measurement"

        
      HttpsIdir.uta.eduSockg-ontology#WindErosionArea : https___idir.uta.edu_sockg_ontology#usesModel
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WindErosionArea --> "0..1" HttpsIdir.uta.eduSockg-ontology#SimulationModel : https___idir.uta.edu_sockg_ontology#usesModel
    click HttpsIdir.uta.eduSockg-ontology#SimulationModel href "../HttpsIdir.uta.eduSockg-ontology#SimulationModel"

        
      HttpsIdir.uta.eduSockg-ontology#WindErosionArea : https___idir.uta.edu_sockg_ontology#usesTreatment
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WindErosionArea --> "0..1" Any : https___idir.uta.edu_sockg_ontology#usesTreatment
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#WindErosionArea : https___idir.uta.edu_sockg_ontology#withStartStopInterval
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WindErosionArea --> "0..1" HttpsIdir.uta.eduSockg-ontology#StartStopInterval : https___idir.uta.edu_sockg_ontology#withStartStopInterval
    click HttpsIdir.uta.eduSockg-ontology#StartStopInterval href "../HttpsIdir.uta.eduSockg-ontology#StartStopInterval"

        
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md)
        * [HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#PossiblySimulatedMeasurement.md)
            * **HttpsIdir.uta.eduSockg-ontology#WindErosionArea**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___idir.uta.edu_sockg_ontology#withStartStopInterval](../slots/https___idir.uta.edu_sockg_ontology#withStartStopInterval.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#StartStopInterval](../classes/HttpsIdir.uta.eduSockg-ontology#StartStopInterval.md) |  <br/>  | direct | 34 |
| [https___idir.uta.edu_sockg_ontology#usesModel](../slots/https___idir.uta.edu_sockg_ontology#usesModel.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#SimulationModel](../classes/HttpsIdir.uta.eduSockg-ontology#SimulationModel.md) |  <br/>  | direct | 14 |
| [https___idir.uta.edu_sockg_ontology#hasLossesOrDeposition](../slots/https___idir.uta.edu_sockg_ontology#hasLossesOrDeposition.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#LossesOrDeposition](../classes/HttpsIdir.uta.eduSockg-ontology#LossesOrDeposition.md) |  <br/>  | direct | 17 |
| [dct_date](../slots/dct_date.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | Date may be used to express temporal information at any level of granularity <br/> description: A point or period of time associated with an event in the lifecycle of the resource. | direct | 34 |
| [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |  <br/>  | direct | 34 |
| [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |  <br/>  | direct | 34 |
| [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#GrowthStage](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStage.md) |  <br/>  | direct | 34 |
| [https___idir.uta.edu_sockg_ontology#hasMeasurement](../slots/https___idir.uta.edu_sockg_ontology#hasMeasurement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Measurement](../classes/HttpsIdir.uta.eduSockg-ontology#Measurement.md) |  <br/>  | direct | 34 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#WindErosionArea
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#PossiblySimulatedMeasurement
slots:
- https___idir.uta.edu_sockg-ontology#withStartStopInterval
- https___idir.uta.edu_sockg-ontology#usesModel
- https___idir.uta.edu_sockg-ontology#hasLossesOrDeposition
- dct_date
- https___idir.uta.edu_sockg-ontology#usesTreatment
- https___idir.uta.edu_sockg-ontology#fromUnit
- https___idir.uta.edu_sockg-ontology#hasGrowthStage
- https___idir.uta.edu_sockg-ontology#hasMeasurement
class_uri: https://idir.uta.edu/sockg-ontology#WindErosionArea

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#WindErosionArea
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#PossiblySimulatedMeasurement
attributes:
  https___idir.uta.edu_sockg-ontology#withStartStopInterval:
    name: https___idir.uta.edu_sockg-ontology#withStartStopInterval
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#QualityMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#withStartStopInterval
    alias: https___idir.uta.edu_sockg_ontology#withStartStopInterval
    owner: https___idir.uta.edu_sockg-ontology#WindErosionArea
    domain_of:
    - https___idir.uta.edu_sockg-ontology#GasNutrientLoss
    - https___idir.uta.edu_sockg-ontology#WaterQualityConcentration
    - https___idir.uta.edu_sockg-ontology#WindErosionArea
    range: https___idir.uta.edu_sockg-ontology#StartStopInterval
  https___idir.uta.edu_sockg-ontology#usesModel:
    name: https___idir.uta.edu_sockg-ontology#usesModel
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#PossiblySimulatedMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#usesModel
    alias: https___idir.uta.edu_sockg_ontology#usesModel
    owner: https___idir.uta.edu_sockg-ontology#WindErosionArea
    domain_of:
    - https___idir.uta.edu_sockg-ontology#GasNutrientLoss
    - https___idir.uta.edu_sockg-ontology#SoilChemicalSample
    - https___idir.uta.edu_sockg-ontology#SoilPhysicalSample
    - https___idir.uta.edu_sockg-ontology#WaterQualityConcentration
    - https___idir.uta.edu_sockg-ontology#WindErosionArea
    range: https___idir.uta.edu_sockg-ontology#SimulationModel
  https___idir.uta.edu_sockg-ontology#hasLossesOrDeposition:
    name: https___idir.uta.edu_sockg-ontology#hasLossesOrDeposition
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#ErosionMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasLossesOrDeposition
    alias: https___idir.uta.edu_sockg_ontology#hasLossesOrDeposition
    owner: https___idir.uta.edu_sockg-ontology#WindErosionArea
    domain_of:
    - https___idir.uta.edu_sockg-ontology#WaterQualityArea
    - https___idir.uta.edu_sockg-ontology#WindErosionArea
    range: https___idir.uta.edu_sockg-ontology#LossesOrDeposition
  dct_date:
    name: dct_date
    description: Date may be used to express temporal information at any level of
      granularity.  Recommended practice is to express the date, date/time, or period
      of time according to ISO 8601-1 [[ISO 8601-1](https://www.iso.org/iso-8601-date-and-time-format.html)]
      or a published profile of the ISO standard, such as the W3C Note on Date and
      Time Formats [[W3CDTF](https://www.w3.org/TR/NOTE-datetime)] or the Extended
      Date/Time Format Specification [[EDTF](http://www.loc.gov/standards/datetime/)].  If
      the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be
      used. Date ranges may be specified using ISO 8601 period of time specification
      in which start and end dates are separated by a '/' (slash) character.  Either
      the start or end date may be missing.
    title: Date
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: A point or period of time associated with an event in the lifecycle
      of the resource.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:date
    alias: dct_date
    owner: https___idir.uta.edu_sockg-ontology#WindErosionArea
    domain_of:
    - https___idir.uta.edu_sockg-ontology#BiomassCarbohydrate
    - https___idir.uta.edu_sockg-ontology#BiomassEnergy
    - https___idir.uta.edu_sockg-ontology#BiomassMineral
    - https___idir.uta.edu_sockg-ontology#GHGFlux
    - https___idir.uta.edu_sockg-ontology#GasNutrientLoss
    - https___idir.uta.edu_sockg-ontology#GrazingPlants
    - https___idir.uta.edu_sockg-ontology#GrowthStageManagement
    - https___idir.uta.edu_sockg-ontology#HarvestFraction
    - https___idir.uta.edu_sockg-ontology#NutrientEfficiency
    - https___idir.uta.edu_sockg-ontology#ResidueMeasurement
    - https___idir.uta.edu_sockg-ontology#SoilBiologicalSample
    - https___idir.uta.edu_sockg-ontology#SoilChemicalSample
    - https___idir.uta.edu_sockg-ontology#SoilCover
    - https___idir.uta.edu_sockg-ontology#SoilPhysicalSample
    - https___idir.uta.edu_sockg-ontology#WaterQualityArea
    - https___idir.uta.edu_sockg-ontology#WaterQualityConcentration
    - https___idir.uta.edu_sockg-ontology#WeatherObservation
    - https___idir.uta.edu_sockg-ontology#WindErosionArea
    - https___idir.uta.edu_sockg-ontology#YieldNutrientUptake
    subproperty_of: dc_date
    range: rdfs_Literal
  https___idir.uta.edu_sockg-ontology#usesTreatment:
    name: https___idir.uta.edu_sockg-ontology#usesTreatment
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Sample
    slot_uri: https://idir.uta.edu/sockg-ontology#usesTreatment
    alias: https___idir.uta.edu_sockg_ontology#usesTreatment
    owner: https___idir.uta.edu_sockg-ontology#WindErosionArea
    domain_of:
    - https___idir.uta.edu_sockg-ontology#BiomassCarbohydrate
    - https___idir.uta.edu_sockg-ontology#BiomassEnergy
    - https___idir.uta.edu_sockg-ontology#BiomassMineral
    - https___idir.uta.edu_sockg-ontology#GHGFlux
    - https___idir.uta.edu_sockg-ontology#GasNutrientLoss
    - https___idir.uta.edu_sockg-ontology#GrazingPlants
    - https___idir.uta.edu_sockg-ontology#HarvestFraction
    - https___idir.uta.edu_sockg-ontology#NutrientEfficiency
    - https___idir.uta.edu_sockg-ontology#ResidueMeasurement
    - https___idir.uta.edu_sockg-ontology#SoilBiologicalSample
    - https___idir.uta.edu_sockg-ontology#SoilChemicalSample
    - https___idir.uta.edu_sockg-ontology#SoilCover
    - https___idir.uta.edu_sockg-ontology#SoilPhysicalSample
    - https___idir.uta.edu_sockg-ontology#WaterQualityArea
    - https___idir.uta.edu_sockg-ontology#WaterQualityConcentration
    - https___idir.uta.edu_sockg-ontology#WeatherObservation
    - https___idir.uta.edu_sockg-ontology#WindErosionArea
    - https___idir.uta.edu_sockg-ontology#YieldNutrientUptake
    range: Any
    any_of:
    - range: uri
    - range: https___idir.uta.edu_sockg-ontology#Treatment
  https___idir.uta.edu_sockg-ontology#fromUnit:
    name: https___idir.uta.edu_sockg-ontology#fromUnit
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Sample
    slot_uri: https://idir.uta.edu/sockg-ontology#fromUnit
    alias: https___idir.uta.edu_sockg_ontology#fromUnit
    owner: https___idir.uta.edu_sockg-ontology#WindErosionArea
    domain_of:
    - https___idir.uta.edu_sockg-ontology#BiomassCarbohydrate
    - https___idir.uta.edu_sockg-ontology#BiomassEnergy
    - https___idir.uta.edu_sockg-ontology#BiomassMineral
    - https___idir.uta.edu_sockg-ontology#GHGFlux
    - https___idir.uta.edu_sockg-ontology#GasNutrientLoss
    - https___idir.uta.edu_sockg-ontology#GrazingPlants
    - https___idir.uta.edu_sockg-ontology#HarvestFraction
    - https___idir.uta.edu_sockg-ontology#NutrientEfficiency
    - https___idir.uta.edu_sockg-ontology#ResidueMeasurement
    - https___idir.uta.edu_sockg-ontology#SoilBiologicalSample
    - https___idir.uta.edu_sockg-ontology#SoilChemicalSample
    - https___idir.uta.edu_sockg-ontology#SoilCover
    - https___idir.uta.edu_sockg-ontology#SoilPhysicalSample
    - https___idir.uta.edu_sockg-ontology#WaterQualityArea
    - https___idir.uta.edu_sockg-ontology#WaterQualityConcentration
    - https___idir.uta.edu_sockg-ontology#WeatherObservation
    - https___idir.uta.edu_sockg-ontology#WindErosionArea
    - https___idir.uta.edu_sockg-ontology#YieldNutrientUptake
    range: Any
    any_of:
    - range: uri
    - range: https___idir.uta.edu_sockg-ontology#ExperimentalUnit
  https___idir.uta.edu_sockg-ontology#hasGrowthStage:
    name: https___idir.uta.edu_sockg-ontology#hasGrowthStage
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#GrowthStageRelatedMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasGrowthStage
    alias: https___idir.uta.edu_sockg_ontology#hasGrowthStage
    owner: https___idir.uta.edu_sockg-ontology#WindErosionArea
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
  https___idir.uta.edu_sockg-ontology#hasMeasurement:
    name: https___idir.uta.edu_sockg-ontology#hasMeasurement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#MeasurableEntity
    slot_uri: https://idir.uta.edu/sockg-ontology#hasMeasurement
    alias: https___idir.uta.edu_sockg_ontology#hasMeasurement
    owner: https___idir.uta.edu_sockg-ontology#WindErosionArea
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
class_uri: https://idir.uta.edu/sockg-ontology#WindErosionArea

```
</details>