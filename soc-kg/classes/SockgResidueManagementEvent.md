

# Class: TODO -- what's a good name for what this class (type) describes? (sockg_ResidueManagementEvent)


_No type description provided_





URI: [sockg:ResidueManagementEvent](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/ResidueManagementEvent)






```mermaid
 classDiagram
    class SockgResidueManagementEvent
    click SockgResidueManagementEvent href "../SockgResidueManagementEvent"
      SockgResidueManagementEvent : sockg_date
        
          
    
    
    SockgResidueManagementEvent --> "0..1" Any : sockg_date
    click Any href "../Any"

        
      SockgResidueManagementEvent : sockg_equipmentType
        
          
    
    
    SockgResidueManagementEvent --> "0..1" Any : sockg_equipmentType
    click Any href "../Any"

        
      SockgResidueManagementEvent : sockg_mgtResidue_UID
        
          
    
    
    SockgResidueManagementEvent --> "0..1" String : sockg_mgtResidue_UID
    click String href "../String"

        
      SockgResidueManagementEvent : sockg_perennialStandAge_years
        
          
    
    
    SockgResidueManagementEvent --> "0..1" Double : sockg_perennialStandAge_years
    click Double href "../Double"

        
      SockgResidueManagementEvent : sockg_rowsHarvestedPercent
        
          
    
    
    SockgResidueManagementEvent --> "0..1" Integer : sockg_rowsHarvestedPercent
    click Integer href "../Integer"

        
      SockgResidueManagementEvent : sockg_stageAtHarvest
        
          
    
    
    SockgResidueManagementEvent --> "0..1" Any : sockg_stageAtHarvest
    click Any href "../Any"

        
      SockgResidueManagementEvent : sockg_treatmentId
        
          
    
    
    SockgResidueManagementEvent --> "0..1" String : sockg_treatmentId
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg_stageAtHarvest](../slots/sockg_stageAtHarvest.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [sockg_perennialStandAge_years](../slots/sockg_perennialStandAge_years.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [sockg_rowsHarvestedPercent](../slots/sockg_rowsHarvestedPercent.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot description provided | direct |
| [sockg_equipmentType](../slots/sockg_equipmentType.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [sockg_treatmentId](../slots/sockg_treatmentId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [sockg_date](../slots/sockg_date.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [sockg_mgtResidue_UID](../slots/sockg_mgtResidue_UID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | [sockg_hasResidueManagementEvent](../slots/sockg_hasResidueManagementEvent.md) | range | [SockgResidueManagementEvent](../classes/SockgResidueManagementEvent.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#229463 |

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
| self | sockg:ResidueManagementEvent |
| native | soc-kg/main/:SockgResidueManagementEvent |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg_ResidueManagementEvent
description: No type description provided
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 3308 instances of this class.
examples:
- value: neo4j://graph.individuals#229463
from_schema: soc-kg/main
rank: 1000
slots:
- sockg_stageAtHarvest
- sockg_perennialStandAge_years
- sockg_rowsHarvestedPercent
- sockg_equipmentType
- sockg_treatmentId
- sockg_date
- sockg_mgtResidue_UID
class_uri: sockg:ResidueManagementEvent

```
</details>

### Induced

<details>
```yaml
name: sockg_ResidueManagementEvent
description: No type description provided
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 3308 instances of this class.
examples:
- value: neo4j://graph.individuals#229463
from_schema: soc-kg/main
rank: 1000
attributes:
  sockg_stageAtHarvest:
    name: sockg_stageAtHarvest
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1650 occurrences with subject type sockg:ResidueManagementEvent and object type
      string.
    - 1658 occurrences with subject type sockg:ResidueManagementEvent and object type
      xsd:double.
    examples:
    - value: neo4j://graph.individuals#228839 sockg:stageAtHarvest Maturity
    - value: neo4j://graph.individuals#227698 sockg:stageAtHarvest nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:stageAtHarvest
    alias: sockg_stageAtHarvest
    owner: sockg_ResidueManagementEvent
    domain_of:
    - sockg_ResidueManagementEvent
    range: Any
    any_of:
    - range: string
    - range: double
  sockg_perennialStandAge_years:
    name: sockg_perennialStandAge_years
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 3308 occurrences with subject type sockg:ResidueManagementEvent and object type
      xsd:double.
    examples:
    - value: neo4j://graph.individuals#227669 sockg:perennialStandAge_years 1.0
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:perennialStandAge_years
    alias: sockg_perennialStandAge_years
    owner: sockg_ResidueManagementEvent
    domain_of:
    - sockg_ResidueManagementEvent
    range: double
  sockg_rowsHarvestedPercent:
    name: sockg_rowsHarvestedPercent
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 3308 occurrences with subject type sockg:ResidueManagementEvent and object type
      xsd:long.
    examples:
    - value: neo4j://graph.individuals#227548 sockg:rowsHarvestedPercent 0
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:rowsHarvestedPercent
    alias: sockg_rowsHarvestedPercent
    owner: sockg_ResidueManagementEvent
    domain_of:
    - sockg_ResidueManagementEvent
    range: integer
  sockg_equipmentType:
    name: sockg_equipmentType
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 3044 occurrences with subject type sockg:ResidueManagementEvent and object type
      string.
    - 264 occurrences with subject type sockg:ResidueManagementEvent and object type
      xsd:double.
    examples:
    - value: neo4j://graph.individuals#230492 sockg:equipmentType diaper
    - value: neo4j://graph.individuals#228275 sockg:equipmentType nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:equipmentType
    alias: sockg_equipmentType
    owner: sockg_ResidueManagementEvent
    domain_of:
    - sockg_ResidueManagementEvent
    range: Any
    any_of:
    - range: string
    - range: double
  sockg_treatmentId:
    name: sockg_treatmentId
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 6723 occurrences with subject type sockg:BioMassMineral and object type string.
    - 107354 occurrences with subject type sockg:GasSample and object type string.
    - 53833 occurrences with subject type sockg:SoilChemicalSample and object type
      string.
    - 37796 occurrences with subject type sockg:Amendment and object type string.
    - 9470 occurrences with subject type sockg:HarvestFraction and object type string.
    - 28082 occurrences with subject type sockg:SoilPhysicalSample and object type
      string.
    - 18222 occurrences with subject type sockg:SoilBiologicalSample and object type
      string.
    - 4896 occurrences with subject type sockg:CropGrowthStage and object type string.
    - 6995 occurrences with subject type sockg:Grazing and object type string.
    - 1951 occurrences with subject type sockg:GrazingManagementEvent and object type
      string.
    - 799 occurrences with subject type sockg:BioMassEnergy and object type string.
    - 18356 occurrences with subject type sockg:Harvest and object type string.
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
    - 3308 occurrences with subject type sockg:ResidueManagementEvent and object type
      string.
    - 1367 occurrences with subject type sockg:BioMassCarbohydrate and object type
      string.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type string.
    - 2791 occurrences with subject type sockg:NutrientEfficiency and object type
      string.
    - 429 occurrences with subject type sockg:YieldNutrientUptake and object type
      string.
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
    - 769 occurrences with subject type sockg:Treatment and object type string.
    - 15 occurrences with subject type sockg:WindErosionArea and object type string.
    examples:
    - value: neo4j://graph.individuals#43961 sockg:treatmentId PAUP_8
    - value: neo4j://graph.individuals#147269 sockg:treatmentId KYBGGHG_1
    - value: neo4j://graph.individuals#296284 sockg:treatmentId PAUP_15
    - value: neo4j://graph.individuals#13960 sockg:treatmentId NEMLTCRS_ROT62
    - value: neo4j://graph.individuals#200120 sockg:treatmentId ECUAlumbreP2_MtNocrhZf
    - value: neo4j://graph.individuals#311219 sockg:treatmentId GAJPCSR1_F3H1
    - value: neo4j://graph.individuals#248000 sockg:treatmentId MNMOBRR_N005C
    - value: neo4j://graph.individuals#47857 sockg:treatmentId INWLTPAC_NP
    - value: neo4j://graph.individuals#170669 sockg:treatmentId NDMAGWP_HG
    - value: neo4j://graph.individuals#171511 sockg:treatmentId GAJPCSR2_F5H2
    - value: neo4j://graph.individuals#39242 sockg:treatmentId SCFLSGI_50R
    - value: neo4j://graph.individuals#181825 sockg:treatmentId PAHAW_RCG1
    - value: neo4j://graph.individuals#361841 sockg:treatmentId WIPDBARN_SAND
    - value: neo4j://graph.individuals#227864 sockg:treatmentId PAHAW_ROT8
    - value: neo4j://graph.individuals#38229 sockg:treatmentId MNSPReap_ST000
    - value: neo4j://graph.individuals#360342 sockg:treatmentId WIPDBARN_SAND
    - value: neo4j://graph.individuals#203268 sockg:treatmentId COFOARD4_DM
    - value: neo4j://graph.individuals#509719 sockg:treatmentId MNSP4R_U-S100
    - value: neo4j://graph.individuals#56012 sockg:treatmentId WIPDBARN_SOIL
    - value: neo4j://graph.individuals#359420 sockg:treatmentId MNMOBRR_N010S
    - value: neo4j://graph.individuals#509310 sockg:treatmentId TXBSWEWC_ERODE
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:treatmentId
    alias: sockg_treatmentId
    owner: sockg_ResidueManagementEvent
    domain_of:
    - sockg_Amendment
    - sockg_BioMassCarbohydrate
    - sockg_BioMassEnergy
    - sockg_BioMassMineral
    - sockg_CropGrowthStage
    - sockg_GasNutrientLoss
    - sockg_GasSample
    - sockg_Grazing
    - sockg_GrazingManagementEvent
    - sockg_Harvest
    - sockg_HarvestFraction
    - sockg_NutrientEfficiency
    - sockg_ResidueManagementEvent
    - sockg_SoilBiologicalSample
    - sockg_SoilChemicalSample
    - sockg_SoilPhysicalSample
    - sockg_Treatment
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    - sockg_YieldNutrientUptake
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
    owner: sockg_ResidueManagementEvent
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
  sockg_mgtResidue_UID:
    name: sockg_mgtResidue_UID
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 3308 occurrences with subject type sockg:ResidueManagementEvent and object type
      string.
    examples:
    - value: neo4j://graph.individuals#227311 sockg:mgtResidue_UID AgCros_PAHAW_409_2011-09-29_Glycine_max_Soybean_
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:mgtResidue_UID
    alias: sockg_mgtResidue_UID
    owner: sockg_ResidueManagementEvent
    domain_of:
    - sockg_ResidueManagementEvent
    range: string
class_uri: sockg:ResidueManagementEvent

```
</details>