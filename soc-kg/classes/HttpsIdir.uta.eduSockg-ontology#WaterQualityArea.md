

# Class: HttpsIdir.uta.eduSockg-ontology#WaterQualityArea




This class occurs 681 times.


URI: [https://idir.uta.edu/sockg-ontology#WaterQualityArea](https://idir.uta.edu/sockg-ontology#WaterQualityArea)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#WaterQualityArea
    click HttpsIdir.uta.eduSockg-ontology#WaterQualityArea href "../HttpsIdir.uta.eduSockg-ontology#WaterQualityArea"
      HttpsIdir.uta.eduSockg-ontology#QualityMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#WaterQualityArea
        click HttpsIdir.uta.eduSockg-ontology#QualityMeasurement href "../HttpsIdir.uta.eduSockg-ontology#QualityMeasurement"
      
      HttpsIdir.uta.eduSockg-ontology#WaterQualityArea : dct_date
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WaterQualityArea --> "0..1" RdfsLiteral : dct_date
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpsIdir.uta.eduSockg-ontology#WaterQualityArea : https___idir.uta.edu_sockg_ontology#fromUnit
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WaterQualityArea --> "0..1" Any : https___idir.uta.edu_sockg_ontology#fromUnit
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#WaterQualityArea : https___idir.uta.edu_sockg_ontology#hasLossesOrDeposition
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WaterQualityArea --> "0..1" HttpsIdir.uta.eduSockg-ontology#LossesOrDeposition : https___idir.uta.edu_sockg_ontology#hasLossesOrDeposition
    click HttpsIdir.uta.eduSockg-ontology#LossesOrDeposition href "../HttpsIdir.uta.eduSockg-ontology#LossesOrDeposition"

        
      HttpsIdir.uta.eduSockg-ontology#WaterQualityArea : https___idir.uta.edu_sockg_ontology#hasMeasurement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WaterQualityArea --> "0..1" HttpsIdir.uta.eduSockg-ontology#Measurement : https___idir.uta.edu_sockg_ontology#hasMeasurement
    click HttpsIdir.uta.eduSockg-ontology#Measurement href "../HttpsIdir.uta.eduSockg-ontology#Measurement"

        
      HttpsIdir.uta.eduSockg-ontology#WaterQualityArea : https___idir.uta.edu_sockg_ontology#hasSurfaceOrLeaching
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WaterQualityArea --> "0..1" HttpsIdir.uta.eduSockg-ontology#SurfaceOrLeaching : https___idir.uta.edu_sockg_ontology#hasSurfaceOrLeaching
    click HttpsIdir.uta.eduSockg-ontology#SurfaceOrLeaching href "../HttpsIdir.uta.eduSockg-ontology#SurfaceOrLeaching"

        
      HttpsIdir.uta.eduSockg-ontology#WaterQualityArea : https___idir.uta.edu_sockg_ontology#usesTreatment
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#WaterQualityArea --> "0..1" Any : https___idir.uta.edu_sockg_ontology#usesTreatment
    click Any href "../Any"

        
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md)
        * [HttpsIdir.uta.eduSockg-ontology#QualityMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#QualityMeasurement.md)
            * **HttpsIdir.uta.eduSockg-ontology#WaterQualityArea**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___idir.uta.edu_sockg_ontology#hasSurfaceOrLeaching](../slots/https___idir.uta.edu_sockg_ontology#hasSurfaceOrLeaching.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#SurfaceOrLeaching](../classes/HttpsIdir.uta.eduSockg-ontology#SurfaceOrLeaching.md) |  <br/>  | direct | 681 |
| [dct_date](../slots/dct_date.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | Date may be used to express temporal information at any level of granularity <br/> description: A point or period of time associated with an event in the lifecycle of the resource. | direct | 681 |
| [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |  <br/>  | direct | 681 |
| [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |  <br/>  | direct | 681 |
| [https___idir.uta.edu_sockg_ontology#hasLossesOrDeposition](../slots/https___idir.uta.edu_sockg_ontology#hasLossesOrDeposition.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#LossesOrDeposition](../classes/HttpsIdir.uta.eduSockg-ontology#LossesOrDeposition.md) |  <br/>  | direct | 132 |
| [https___idir.uta.edu_sockg_ontology#hasMeasurement](../slots/https___idir.uta.edu_sockg_ontology#hasMeasurement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Measurement](../classes/HttpsIdir.uta.eduSockg-ontology#Measurement.md) |  <br/>  | direct | 5316 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#WaterQualityArea
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#QualityMeasurement
slots:
- https___idir.uta.edu_sockg-ontology#hasSurfaceOrLeaching
- dct_date
- https___idir.uta.edu_sockg-ontology#usesTreatment
- https___idir.uta.edu_sockg-ontology#fromUnit
- https___idir.uta.edu_sockg-ontology#hasLossesOrDeposition
- https___idir.uta.edu_sockg-ontology#hasMeasurement
class_uri: https://idir.uta.edu/sockg-ontology#WaterQualityArea

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#WaterQualityArea
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#QualityMeasurement
attributes:
  https___idir.uta.edu_sockg-ontology#hasSurfaceOrLeaching:
    name: https___idir.uta.edu_sockg-ontology#hasSurfaceOrLeaching
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#QualityMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasSurfaceOrLeaching
    alias: https___idir.uta.edu_sockg_ontology#hasSurfaceOrLeaching
    owner: https___idir.uta.edu_sockg-ontology#WaterQualityArea
    domain_of:
    - https___idir.uta.edu_sockg-ontology#WaterQualityArea
    - https___idir.uta.edu_sockg-ontology#WaterQualityConcentration
    range: https___idir.uta.edu_sockg-ontology#SurfaceOrLeaching
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
    owner: https___idir.uta.edu_sockg-ontology#WaterQualityArea
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
    owner: https___idir.uta.edu_sockg-ontology#WaterQualityArea
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
    owner: https___idir.uta.edu_sockg-ontology#WaterQualityArea
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
  https___idir.uta.edu_sockg-ontology#hasLossesOrDeposition:
    name: https___idir.uta.edu_sockg-ontology#hasLossesOrDeposition
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#ErosionMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasLossesOrDeposition
    alias: https___idir.uta.edu_sockg_ontology#hasLossesOrDeposition
    owner: https___idir.uta.edu_sockg-ontology#WaterQualityArea
    domain_of:
    - https___idir.uta.edu_sockg-ontology#WaterQualityArea
    - https___idir.uta.edu_sockg-ontology#WindErosionArea
    range: https___idir.uta.edu_sockg-ontology#LossesOrDeposition
  https___idir.uta.edu_sockg-ontology#hasMeasurement:
    name: https___idir.uta.edu_sockg-ontology#hasMeasurement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#MeasurableEntity
    slot_uri: https://idir.uta.edu/sockg-ontology#hasMeasurement
    alias: https___idir.uta.edu_sockg_ontology#hasMeasurement
    owner: https___idir.uta.edu_sockg-ontology#WaterQualityArea
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
class_uri: https://idir.uta.edu/sockg-ontology#WaterQualityArea

```
</details>