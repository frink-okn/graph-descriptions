

# Class: TODO -- what's a good name for what this class (type) describes? (sockg_SoilCover)


_No type description provided_





URI: [sockg:SoilCover](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/SoilCover)






```mermaid
 classDiagram
    class SockgSoilCover
    click SockgSoilCover href "../SockgSoilCover"
      SockgSoilCover : sockg_date
        
          
    
    
    SockgSoilCover --> "0..1" Any : sockg_date
    click Any href "../Any"

        
      SockgSoilCover : sockg_measSoilCover_UID
        
          
    
    
    SockgSoilCover --> "0..1" String : sockg_measSoilCover_UID
    click String href "../String"

        
      SockgSoilCover : sockg_soilWithResidueCoverPercent
        
          
    
    
    SockgSoilCover --> "0..1" Double : sockg_soilWithResidueCoverPercent
    click Double href "../Double"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg_soilWithResidueCoverPercent](../slots/sockg_soilWithResidueCoverPercent.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [sockg_measSoilCover_UID](../slots/sockg_measSoilCover_UID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [sockg_date](../slots/sockg_date.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |










## Examples

| Value |
| --- |
| neo4j://graph.individuals#303209 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: soc-kg/main




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sockg:SoilCover |
| native | soc-kg/main/:SockgSoilCover |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg_SoilCover
description: No type description provided
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 1034 instances of this class.
examples:
- value: neo4j://graph.individuals#303209
from_schema: soc-kg/main
rank: 1000
slots:
- sockg_soilWithResidueCoverPercent
- sockg_measSoilCover_UID
- sockg_date
class_uri: sockg:SoilCover

```
</details>

### Induced

<details>
```yaml
name: sockg_SoilCover
description: No type description provided
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 1034 instances of this class.
examples:
- value: neo4j://graph.individuals#303209
from_schema: soc-kg/main
rank: 1000
attributes:
  sockg_soilWithResidueCoverPercent:
    name: sockg_soilWithResidueCoverPercent
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1034 occurrences with subject type sockg:SoilCover and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#303083 sockg:soilWithResidueCoverPercent nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:soilWithResidueCoverPercent
    alias: sockg_soilWithResidueCoverPercent
    owner: sockg_SoilCover
    domain_of:
    - sockg_SoilCover
    range: double
  sockg_measSoilCover_UID:
    name: sockg_measSoilCover_UID
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1034 occurrences with subject type sockg:SoilCover and object type string.
    examples:
    - value: neo4j://graph.individuals#303051 sockg:measSoilCover_UID AgCros_PAUP_305_2008-11-04_Zea_mays_Corn_
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:measSoilCover_UID
    alias: sockg_measSoilCover_UID
    owner: sockg_SoilCover
    domain_of:
    - sockg_SoilCover
    range: string
  sockg_date:
    name: sockg_date
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 53833 occurrences with subject type sockg:SoilChemicalSample and object type
      string.
    - 147304 occurrences with subject type sockg:WeatherObservation and object type
      string.
    - 107354 occurrences with subject type sockg:GasSample and object type string.
    - 28082 occurrences with subject type sockg:SoilPhysicalSample and object type
      string.
    - 6995 occurrences with subject type sockg:Grazing and object type string.
    - 4896 occurrences with subject type sockg:CropGrowthStage and object type string.
    - 18222 occurrences with subject type sockg:SoilBiologicalSample and object type
      string.
    - 18304 occurrences with subject type sockg:Harvest and object type string.
    - 6723 occurrences with subject type sockg:BioMassMineral and object type string.
    - 3308 occurrences with subject type sockg:ResidueManagementEvent and object type
      string.
    - 2791 occurrences with subject type sockg:NutrientEfficiency and object type
      string.
    - 1367 occurrences with subject type sockg:BioMassCarbohydrate and object type
      string.
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
    - 1034 occurrences with subject type sockg:SoilCover and object type string.
    - 429 occurrences with subject type sockg:YieldNutrientUptake and object type
      string.
    - 52 occurrences with subject type sockg:Harvest and object type xsd:double.
    - 799 occurrences with subject type sockg:BioMassEnergy and object type string.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type string.
    - 15 occurrences with subject type sockg:WindErosionArea and object type string.
    - 1 occurrences with subject type sockg:WeatherObservation and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#294621 sockg:date 2008-11-19
    - value: neo4j://graph.individuals#488503 sockg:date 2009-05-27
    - value: neo4j://graph.individuals#85292 sockg:date 2011-07-01
    - value: neo4j://graph.individuals#309598 sockg:date 1996-04-17
    - value: neo4j://graph.individuals#165161 sockg:date 1994-07-12
    - value: neo4j://graph.individuals#48449 sockg:date 2008-08-08
    - value: neo4j://graph.individuals#243645 sockg:date 2001-01-24
    - value: neo4j://graph.individuals#175155 sockg:date 1987-09-24
    - value: neo4j://graph.individuals#41902 sockg:date 2008-10-16
    - value: neo4j://graph.individuals#228638 sockg:date 2009-11-11
    - value: neo4j://graph.individuals#203067 sockg:date 2004-09-17
    - value: neo4j://graph.individuals#38588 sockg:date 2011-08-31
    - value: neo4j://graph.individuals#361436 sockg:date 2012-04-23
    - value: neo4j://graph.individuals#56011 sockg:date 2014-08-29
    - value: neo4j://graph.individuals#303276 sockg:date 2013-04-02
    - value: neo4j://graph.individuals#509459 sockg:date 2008-04-21
    - value: neo4j://graph.individuals#178323 sockg:date nan
    - value: neo4j://graph.individuals#39935 sockg:date 2008-09-04
    - value: neo4j://graph.individuals#359964 sockg:date 2010-11-02
    - value: neo4j://graph.individuals#509303 sockg:date 1993-03-15
    - value: neo4j://graph.individuals#377442 sockg:date nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:date
    alias: sockg_date
    owner: sockg_SoilCover
    domain_of:
    - sockg_BioMassCarbohydrate
    - sockg_BioMassEnergy
    - sockg_BioMassMineral
    - sockg_CropGrowthStage
    - sockg_GasNutrientLoss
    - sockg_GasSample
    - sockg_Grazing
    - sockg_Harvest
    - sockg_NutrientEfficiency
    - sockg_ResidueManagementEvent
    - sockg_SoilBiologicalSample
    - sockg_SoilChemicalSample
    - sockg_SoilCover
    - sockg_SoilPhysicalSample
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WeatherObservation
    - sockg_WindErosionArea
    - sockg_YieldNutrientUptake
    range: Any
    any_of:
    - range: string
    - range: double
class_uri: sockg:SoilCover

```
</details>