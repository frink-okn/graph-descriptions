

# Class: HttpsIdir.uta.eduSockg-ontology#SoilCover




This class occurs 1034 times.


URI: [https://idir.uta.edu/sockg-ontology#SoilCover](https://idir.uta.edu/sockg-ontology#SoilCover)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#SoilCover
    click HttpsIdir.uta.eduSockg-ontology#SoilCover href "../HttpsIdir.uta.eduSockg-ontology#SoilCover"
      HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement <|-- HttpsIdir.uta.eduSockg-ontology#SoilCover
        click HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement href "../HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement"
      
      HttpsIdir.uta.eduSockg-ontology#SoilCover : dct_date
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#SoilCover --> "0..1" RdfsLiteral : dct_date
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpsIdir.uta.eduSockg-ontology#SoilCover : https___idir.uta.edu_sockg_ontology#fromUnit
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#SoilCover --> "0..1" Any : https___idir.uta.edu_sockg_ontology#fromUnit
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#SoilCover : https___idir.uta.edu_sockg_ontology#hasCrop
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#SoilCover --> "0..1" HttpsLod.nal.usda.govNalt7140 : https___idir.uta.edu_sockg_ontology#hasCrop
    click HttpsLod.nal.usda.govNalt7140 href "../HttpsLod.nal.usda.govNalt7140"

        
      HttpsIdir.uta.eduSockg-ontology#SoilCover : https___idir.uta.edu_sockg_ontology#hasTiming
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#SoilCover --> "0..1" HttpsIdir.uta.eduSockg-ontology#Timing : https___idir.uta.edu_sockg_ontology#hasTiming
    click HttpsIdir.uta.eduSockg-ontology#Timing href "../HttpsIdir.uta.eduSockg-ontology#Timing"

        
      HttpsIdir.uta.eduSockg-ontology#SoilCover : https___idir.uta.edu_sockg_ontology#usesTreatment
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#SoilCover --> "0..1" Any : https___idir.uta.edu_sockg_ontology#usesTreatment
    click Any href "../Any"

        
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * [HttpsIdir.uta.eduSockg-ontology#Sample](../classes/HttpsIdir.uta.eduSockg-ontology#Sample.md)
        * [HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#CropRelatedMeasurement.md)
            * **HttpsIdir.uta.eduSockg-ontology#SoilCover**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | 0..1 <br/> [HttpsLod.nal.usda.govNalt7140](../classes/HttpsLod.nal.usda.govNalt7140.md) |  <br/>  | direct | 1034 |
| [https___idir.uta.edu_sockg_ontology#hasTiming](../slots/https___idir.uta.edu_sockg_ontology#hasTiming.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Timing](../classes/HttpsIdir.uta.eduSockg-ontology#Timing.md) |  <br/>  | direct | 1034 |
| [dct_date](../slots/dct_date.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | Date may be used to express temporal information at any level of granularity <br/> description: A point or period of time associated with an event in the lifecycle of the resource. | direct | 1034 |
| [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |  <br/>  | direct | 1034 |
| [https___idir.uta.edu_sockg_ontology#fromUnit](../slots/https___idir.uta.edu_sockg_ontology#fromUnit.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |  <br/>  | direct | 1034 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#SoilCover](../classes/HttpsIdir.uta.eduSockg-ontology#SoilCover.md) | [https___idir.uta.edu_sockg_ontology#hasTiming](../slots/https___idir.uta.edu_sockg_ontology#hasTiming.md) | domain | [HttpsIdir.uta.eduSockg-ontology#SoilCover](../classes/HttpsIdir.uta.eduSockg-ontology#SoilCover.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#SoilCover
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#CropRelatedMeasurement
slots:
- https___idir.uta.edu_sockg-ontology#hasCrop
- https___idir.uta.edu_sockg-ontology#hasTiming
- dct_date
- https___idir.uta.edu_sockg-ontology#usesTreatment
- https___idir.uta.edu_sockg-ontology#fromUnit
class_uri: https://idir.uta.edu/sockg-ontology#SoilCover

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#SoilCover
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#CropRelatedMeasurement
attributes:
  https___idir.uta.edu_sockg-ontology#hasCrop:
    name: https___idir.uta.edu_sockg-ontology#hasCrop
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#CropRelatedMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasCrop
    alias: https___idir.uta.edu_sockg_ontology#hasCrop
    owner: https___idir.uta.edu_sockg-ontology#SoilCover
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
  https___idir.uta.edu_sockg-ontology#hasTiming:
    name: https___idir.uta.edu_sockg-ontology#hasTiming
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#SoilCover
    slot_uri: https://idir.uta.edu/sockg-ontology#hasTiming
    alias: https___idir.uta.edu_sockg_ontology#hasTiming
    owner: https___idir.uta.edu_sockg-ontology#SoilCover
    domain_of:
    - https___idir.uta.edu_sockg-ontology#SoilCover
    range: https___idir.uta.edu_sockg-ontology#Timing
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
    owner: https___idir.uta.edu_sockg-ontology#SoilCover
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
    owner: https___idir.uta.edu_sockg-ontology#SoilCover
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
    owner: https___idir.uta.edu_sockg-ontology#SoilCover
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
class_uri: https://idir.uta.edu/sockg-ontology#SoilCover

```
</details>