

# Class: HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement




This class occurs 5148 times.


URI: [https://idir.uta.edu/sockg-ontology#GrowthStageManagement](https://idir.uta.edu/sockg-ontology#GrowthStageManagement)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement
    click HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement href "../HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement"
      HttpsIdir.uta.eduSockg-ontology#MeasurableEntity <|-- HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement
        click HttpsIdir.uta.eduSockg-ontology#MeasurableEntity href "../HttpsIdir.uta.eduSockg-ontology#MeasurableEntity"
      
      HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement : dct_date
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement --> "0..1" RdfsLiteral : dct_date
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement : https___idir.uta.edu_sockg_ontology#hasCrop
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement --> "0..1" HttpsLod.nal.usda.govNalt7140 : https___idir.uta.edu_sockg_ontology#hasCrop
    click HttpsLod.nal.usda.govNalt7140 href "../HttpsLod.nal.usda.govNalt7140"

        
      HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement : https___idir.uta.edu_sockg_ontology#hasGrowthStage
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement --> "0..1" HttpsIdir.uta.eduSockg-ontology#GrowthStage : https___idir.uta.edu_sockg_ontology#hasGrowthStage
    click HttpsIdir.uta.eduSockg-ontology#GrowthStage href "../HttpsIdir.uta.eduSockg-ontology#GrowthStage"

        
      
```





## Inheritance
* [HttpsIdir.uta.eduSockg-ontology#MeasurableEntity](../classes/HttpsIdir.uta.eduSockg-ontology#MeasurableEntity.md)
    * **HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___idir.uta.edu_sockg_ontology#hasGrowthStage](../slots/https___idir.uta.edu_sockg_ontology#hasGrowthStage.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#GrowthStage](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStage.md) |  <br/>  | direct | 5148 |
| [dct_date](../slots/dct_date.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | Date may be used to express temporal information at any level of granularity <br/> description: A point or period of time associated with an event in the lifecycle of the resource. | direct | 5148 |
| [https___idir.uta.edu_sockg_ontology#hasCrop](../slots/https___idir.uta.edu_sockg_ontology#hasCrop.md) | 0..1 <br/> [HttpsLod.nal.usda.govNalt7140](../classes/HttpsLod.nal.usda.govNalt7140.md) |  <br/>  | direct | 5148 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#unitHasGrowthStageManagement](../slots/https___idir.uta.edu_sockg_ontology#unitHasGrowthStageManagement.md) | range | [HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#treatmentHasGrowthStageManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasGrowthStageManagement.md) | range | [HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#GrowthStageManagement
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
slots:
- https___idir.uta.edu_sockg-ontology#hasGrowthStage
- dct_date
- https___idir.uta.edu_sockg-ontology#hasCrop
class_uri: https://idir.uta.edu/sockg-ontology#GrowthStageManagement

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#GrowthStageManagement
from_schema: okns:soc-kg
rank: 1000
is_a: https___idir.uta.edu_sockg-ontology#MeasurableEntity
attributes:
  https___idir.uta.edu_sockg-ontology#hasGrowthStage:
    name: https___idir.uta.edu_sockg-ontology#hasGrowthStage
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#GrowthStageRelatedMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasGrowthStage
    alias: https___idir.uta.edu_sockg_ontology#hasGrowthStage
    owner: https___idir.uta.edu_sockg-ontology#GrowthStageManagement
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
    owner: https___idir.uta.edu_sockg-ontology#GrowthStageManagement
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
  https___idir.uta.edu_sockg-ontology#hasCrop:
    name: https___idir.uta.edu_sockg-ontology#hasCrop
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#CropRelatedMeasurement
    slot_uri: https://idir.uta.edu/sockg-ontology#hasCrop
    alias: https___idir.uta.edu_sockg_ontology#hasCrop
    owner: https___idir.uta.edu_sockg-ontology#GrowthStageManagement
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
class_uri: https://idir.uta.edu/sockg-ontology#GrowthStageManagement

```
</details>