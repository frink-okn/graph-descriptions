

# Class: TODO -- what's a good name for what this class (type) describes? (sockg_GrazingManagementEvent)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:GrazingManagementEvent](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/GrazingManagementEvent)






```mermaid
 classDiagram
    class SockgGrazingManagementEvent
    click SockgGrazingManagementEvent href "../SockgGrazingManagementEvent"
      SockgGrazingManagementEvent : sockg_animalClass
        
          
    
    
    SockgGrazingManagementEvent --> "0..1" Any : sockg_animalClass
    click Any href "../Any"

        
      SockgGrazingManagementEvent : sockg_animalSpecies
        
          
    
    
    SockgGrazingManagementEvent --> "0..1" String : sockg_animalSpecies
    click String href "../String"

        
      SockgGrazingManagementEvent : sockg_burnIntensity
        
          
    
    
    SockgGrazingManagementEvent --> "0..1" Double : sockg_burnIntensity
    click Double href "../Double"

        
      SockgGrazingManagementEvent : sockg_endDate
        
          
    
    
    SockgGrazingManagementEvent --> "0..1" Any : sockg_endDate
    click Any href "../Any"

        
      SockgGrazingManagementEvent : sockg_mgtGrazing_UID
        
          
    
    
    SockgGrazingManagementEvent --> "0..1" String : sockg_mgtGrazing_UID
    click String href "../String"

        
      SockgGrazingManagementEvent : sockg_otherEvents
        
          
    
    
    SockgGrazingManagementEvent --> "0..1" Any : sockg_otherEvents
    click Any href "../Any"

        
      SockgGrazingManagementEvent : sockg_startDate
        
          
    
    
    SockgGrazingManagementEvent --> "0..1" Any : sockg_startDate
    click Any href "../Any"

        
      SockgGrazingManagementEvent : sockg_stockingRate_number_animals_per_ha
        
          
    
    
    SockgGrazingManagementEvent --> "0..1" Double : sockg_stockingRate_number_animals_per_ha
    click Double href "../Double"

        
      SockgGrazingManagementEvent : sockg_treatmentId
        
          
    
    
    SockgGrazingManagementEvent --> "0..1" String : sockg_treatmentId
    click String href "../String"

        
      SockgGrazingManagementEvent : sockg_yearsBetweenBurns
        
          
    
    
    SockgGrazingManagementEvent --> "0..1" Double : sockg_yearsBetweenBurns
    click Double href "../Double"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg_animalSpecies](../slots/sockg_animalSpecies.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_burnIntensity](../slots/sockg_burnIntensity.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_yearsBetweenBurns](../slots/sockg_yearsBetweenBurns.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_treatmentId](../slots/sockg_treatmentId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_otherEvents](../slots/sockg_otherEvents.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_startDate](../slots/sockg_startDate.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_mgtGrazing_UID](../slots/sockg_mgtGrazing_UID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_animalClass](../slots/sockg_animalClass.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_endDate](../slots/sockg_endDate.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_stockingRate_number_animals_per_ha](../slots/sockg_stockingRate_number_animals_per_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | [sockg_hasGrazingManagementEvent](../slots/sockg_hasGrazingManagementEvent.md) | range | [SockgGrazingManagementEvent](../classes/SockgGrazingManagementEvent.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#171579 |

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
| self | sockg:GrazingManagementEvent |
| native | soc-kg/main/:SockgGrazingManagementEvent |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg_GrazingManagementEvent
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 1951 instances of this class.
examples:
- value: neo4j://graph.individuals#171579
from_schema: soc-kg/main
slots:
- sockg_animalSpecies
- sockg_burnIntensity
- sockg_yearsBetweenBurns
- sockg_treatmentId
- sockg_otherEvents
- sockg_startDate
- sockg_mgtGrazing_UID
- sockg_animalClass
- sockg_endDate
- sockg_stockingRate_number_animals_per_ha
class_uri: sockg:GrazingManagementEvent

```
</details>

### Induced

<details>
```yaml
name: sockg_GrazingManagementEvent
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 1951 instances of this class.
examples:
- value: neo4j://graph.individuals#171579
from_schema: soc-kg/main
attributes:
  sockg_animalSpecies:
    name: sockg_animalSpecies
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1951 occurrences with subject type sockg:GrazingManagementEvent and object type
      string.
    examples:
    - value: neo4j://graph.individuals#172411 sockg:animalSpecies Beef Cattle
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:animalSpecies
    alias: sockg_animalSpecies
    owner: sockg_GrazingManagementEvent
    domain_of:
    - sockg_GrazingManagementEvent
    range: string
  sockg_burnIntensity:
    name: sockg_burnIntensity
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1951 occurrences with subject type sockg:GrazingManagementEvent and object type
      xsd:double.
    examples:
    - value: neo4j://graph.individuals#171391 sockg:burnIntensity nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:burnIntensity
    alias: sockg_burnIntensity
    owner: sockg_GrazingManagementEvent
    domain_of:
    - sockg_GrazingManagementEvent
    range: double
  sockg_yearsBetweenBurns:
    name: sockg_yearsBetweenBurns
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1951 occurrences with subject type sockg:GrazingManagementEvent and object type
      xsd:double.
    examples:
    - value: neo4j://graph.individuals#171967 sockg:yearsBetweenBurns nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:yearsBetweenBurns
    alias: sockg_yearsBetweenBurns
    owner: sockg_GrazingManagementEvent
    domain_of:
    - sockg_GrazingManagementEvent
    range: double
  sockg_treatmentId:
    name: sockg_treatmentId
    description: TODO -- tell the world what this slot (predicate) describes.
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
    owner: sockg_GrazingManagementEvent
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
  sockg_otherEvents:
    name: sockg_otherEvents
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1947 occurrences with subject type sockg:GrazingManagementEvent and object type
      xsd:double.
    - 4 occurrences with subject type sockg:GrazingManagementEvent and object type
      string.
    examples:
    - value: neo4j://graph.individuals#171317 sockg:otherEvents nan
    - value: neo4j://graph.individuals#172156 sockg:otherEvents fertilizer application
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:otherEvents
    alias: sockg_otherEvents
    owner: sockg_GrazingManagementEvent
    domain_of:
    - sockg_GrazingManagementEvent
    range: Any
    any_of:
    - range: double
    - range: string
  sockg_startDate:
    name: sockg_startDate
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 37796 occurrences with subject type sockg:Amendment and object type string.
    - 3178 occurrences with subject type sockg:ExperimentalUnit and object type string.
    - 1951 occurrences with subject type sockg:GrazingManagementEvent and object type
      string.
    - 631 occurrences with subject type sockg:ExperimentalUnit and object type xsd:double.
    - 55 occurrences with subject type sockg:Experiment and object type string.
    examples:
    - value: neo4j://graph.individuals#6073 sockg:startDate 2010-04-23
    - value: neo4j://graph.individuals#52263 sockg:startDate 2004-04-01
    - value: neo4j://graph.individuals#172393 sockg:startDate 1996-08-15
    - value: neo4j://graph.individuals#54995 sockg:startDate nan
    - value: neo4j://graph.individuals#51687 sockg:startDate 2009-01-01
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:startDate
    alias: sockg_startDate
    owner: sockg_GrazingManagementEvent
    domain_of:
    - sockg_Amendment
    - sockg_Experiment
    - sockg_ExperimentalUnit
    - sockg_GrazingManagementEvent
    range: Any
    any_of:
    - range: string
    - range: double
  sockg_mgtGrazing_UID:
    name: sockg_mgtGrazing_UID
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1951 occurrences with subject type sockg:GrazingManagementEvent and object type
      string.
    examples:
    - value: neo4j://graph.individuals#171813 sockg:mgtGrazing_UID AgCros_GAJPCSR2_B3P109F4H2_2000-10-19_2000-11-16
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:mgtGrazing_UID
    alias: sockg_mgtGrazing_UID
    owner: sockg_GrazingManagementEvent
    domain_of:
    - sockg_GrazingManagementEvent
    range: string
  sockg_animalClass:
    name: sockg_animalClass
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1833 occurrences with subject type sockg:GrazingManagementEvent and object type
      string.
    - 118 occurrences with subject type sockg:GrazingManagementEvent and object type
      xsd:double.
    examples:
    - value: neo4j://graph.individuals#171465 sockg:animalClass Neutered male
    - value: neo4j://graph.individuals#172634 sockg:animalClass nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:animalClass
    alias: sockg_animalClass
    owner: sockg_GrazingManagementEvent
    domain_of:
    - sockg_GrazingManagementEvent
    range: Any
    any_of:
    - range: string
    - range: double
  sockg_endDate:
    name: sockg_endDate
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 37796 occurrences with subject type sockg:Amendment and object type xsd:double.
    - 2026 occurrences with subject type sockg:ExperimentalUnit and object type xsd:double.
    - 1783 occurrences with subject type sockg:ExperimentalUnit and object type string.
    - 1951 occurrences with subject type sockg:GrazingManagementEvent and object type
      string.
    - 55 occurrences with subject type sockg:Experiment and object type string.
    examples:
    - value: neo4j://graph.individuals#11898 sockg:endDate nan
    - value: neo4j://graph.individuals#52943 sockg:endDate nan
    - value: neo4j://graph.individuals#52582 sockg:endDate 2009-11-11
    - value: neo4j://graph.individuals#172114 sockg:endDate 2005-08-08
    - value: neo4j://graph.individuals#51722 sockg:endDate 2011-05-18
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:endDate
    alias: sockg_endDate
    owner: sockg_GrazingManagementEvent
    domain_of:
    - sockg_Amendment
    - sockg_Experiment
    - sockg_ExperimentalUnit
    - sockg_GrazingManagementEvent
    range: Any
    any_of:
    - range: double
    - range: string
  sockg_stockingRate_number_animals_per_ha:
    name: sockg_stockingRate_number_animals_per_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1951 occurrences with subject type sockg:GrazingManagementEvent and object type
      xsd:double.
    examples:
    - value: neo4j://graph.individuals#172456 sockg:stockingRate_number_animals_per_ha
        4.6153846
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:stockingRate_number_animals_per_ha
    alias: sockg_stockingRate_number_animals_per_ha
    owner: sockg_GrazingManagementEvent
    domain_of:
    - sockg_GrazingManagementEvent
    range: double
class_uri: sockg:GrazingManagementEvent

```
</details>