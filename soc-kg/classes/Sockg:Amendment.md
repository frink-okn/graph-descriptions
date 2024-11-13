

# Class: TODO -- what's a good name for what this class (type) describes? (sockg:Amendment)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:Amendment](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/Amendment)






```mermaid
 classDiagram
    class Sockg:Amendment
    click Sockg:Amendment href "../Sockg:Amendment"
      Sockg:Amendment : sockg:amendmentPlacement
        
          
    
    
    Sockg:Amendment --> "0..1" Any : sockg:amendmentPlacement
    click Any href "../Any"

        
      Sockg:Amendment : sockg:endDate
        
          
    
    
    Sockg:Amendment --> "0..1" Any : sockg:endDate
    click Any href "../Any"

        
      Sockg:Amendment : sockg:hasPesticide
        
          
    
    
    Sockg:Amendment --> "0..1" Sockg:Pesticide : sockg:hasPesticide
    click Sockg:Pesticide href "../Sockg:Pesticide"

        
      Sockg:Amendment : sockg:irrigationAmount_cm
        
          
    
    
    Sockg:Amendment --> "0..1" Double : sockg:irrigationAmount_cm
    click Double href "../Double"

        
      Sockg:Amendment : sockg:irrigationNitrogen_mg_per_L
        
          
    
    
    Sockg:Amendment --> "0..1" Double : sockg:irrigationNitrogen_mg_per_L
    click Double href "../Double"

        
      Sockg:Amendment : sockg:irrigationType
        
          
    
    
    Sockg:Amendment --> "0..1" Any : sockg:irrigationType
    click Any href "../Any"

        
      Sockg:Amendment : sockg:mgtAmendments_UID
        
          
    
    
    Sockg:Amendment --> "0..1" String : sockg:mgtAmendments_UID
    click String href "../String"

        
      Sockg:Amendment : sockg:startDate
        
          
    
    
    Sockg:Amendment --> "0..1" Any : sockg:startDate
    click Any href "../Any"

        
      Sockg:Amendment : sockg:totalAmendmentAmount_kg_per_ha
        
          
    
    
    Sockg:Amendment --> "0..1" Double : sockg:totalAmendmentAmount_kg_per_ha
    click Double href "../Double"

        
      Sockg:Amendment : sockg:totalNitrogenAmount_kgN_per_ha
        
          
    
    
    Sockg:Amendment --> "0..1" Double : sockg:totalNitrogenAmount_kgN_per_ha
    click Double href "../Double"

        
      Sockg:Amendment : sockg:totalPhosphorusAmount_kgP_per_ha
        
          
    
    
    Sockg:Amendment --> "0..1" Double : sockg:totalPhosphorusAmount_kgP_per_ha
    click Double href "../Double"

        
      Sockg:Amendment : sockg:totalPotassiumAmount_kgK_per_ha
        
          
    
    
    Sockg:Amendment --> "0..1" Double : sockg:totalPotassiumAmount_kgK_per_ha
    click Double href "../Double"

        
      Sockg:Amendment : sockg:treatmentId
        
          
    
    
    Sockg:Amendment --> "0..1" String : sockg:treatmentId
    click String href "../String"

        
      Sockg:Amendment : sockg:type
        
          
    
    
    Sockg:Amendment --> "0..1" Any : sockg:type
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg:hasPesticide](../slots/sockg:hasPesticide.md) | 0..1 <br/> [Sockg:Pesticide](../classes/Sockg:Pesticide.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:irrigationType](../slots/sockg:irrigationType.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:amendmentPlacement](../slots/sockg:amendmentPlacement.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:mgtAmendments_UID](../slots/sockg:mgtAmendments_UID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:totalAmendmentAmount_kg_per_ha](../slots/sockg:totalAmendmentAmount_kg_per_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:startDate](../slots/sockg:startDate.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:irrigationAmount_cm](../slots/sockg:irrigationAmount_cm.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:totalNitrogenAmount_kgN_per_ha](../slots/sockg:totalNitrogenAmount_kgN_per_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:irrigationNitrogen_mg_per_L](../slots/sockg:irrigationNitrogen_mg_per_L.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:type](../slots/sockg:type.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:treatmentId](../slots/sockg:treatmentId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:totalPotassiumAmount_kgK_per_ha](../slots/sockg:totalPotassiumAmount_kgK_per_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:endDate](../slots/sockg:endDate.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:totalPhosphorusAmount_kgP_per_ha](../slots/sockg:totalPhosphorusAmount_kgP_per_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Sockg:ExperimentalUnit](../classes/Sockg:ExperimentalUnit.md) | [sockg:hasAmendment](../slots/sockg:hasAmendment.md) | range | [Sockg:Amendment](../classes/Sockg:Amendment.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#27559 |

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
| self | sockg:Amendment |
| native | soc-kg/main/:Sockg:Amendment |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg:Amendment
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 37796 instances of this class.
examples:
- value: neo4j://graph.individuals#27559
from_schema: soc-kg/main
slots:
- sockg:hasPesticide
- sockg:irrigationType
- sockg:amendmentPlacement
- sockg:mgtAmendments_UID
- sockg:totalAmendmentAmount_kg_per_ha
- sockg:startDate
- sockg:irrigationAmount_cm
- sockg:totalNitrogenAmount_kgN_per_ha
- sockg:irrigationNitrogen_mg_per_L
- sockg:type
- sockg:treatmentId
- sockg:totalPotassiumAmount_kgK_per_ha
- sockg:endDate
- sockg:totalPhosphorusAmount_kgP_per_ha
class_uri: sockg:Amendment

```
</details>

### Induced

<details>
```yaml
name: sockg:Amendment
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 37796 instances of this class.
examples:
- value: neo4j://graph.individuals#27559
from_schema: soc-kg/main
attributes:
  sockg:hasPesticide:
    name: sockg:hasPesticide
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 42545 occurrences with subject type sockg:Amendment and object type sockg:Pesticide.
    examples:
    - value: neo4j://graph.individuals#6566 sockg:hasPesticide neo4j://graph.individuals#203394
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasPesticide
    alias: sockg:hasPesticide
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    range: sockg:Pesticide
  sockg:irrigationType:
    name: sockg:irrigationType
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 33571 occurrences with subject type sockg:Amendment and object type xsd:double.
    - 4225 occurrences with subject type sockg:Amendment and object type string.
    examples:
    - value: neo4j://graph.individuals#16031 sockg:irrigationType nan
    - value: neo4j://graph.individuals#19703 sockg:irrigationType Linear Move Sprinkler
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:irrigationType
    alias: sockg:irrigationType
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    range: Any
    any_of:
    - range: double
    - range: string
  sockg:amendmentPlacement:
    name: sockg:amendmentPlacement
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 22264 occurrences with subject type sockg:Amendment and object type string.
    - 15532 occurrences with subject type sockg:Amendment and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#13919 sockg:amendmentPlacement Broadcast Surface
    - value: neo4j://graph.individuals#23486 sockg:amendmentPlacement nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:amendmentPlacement
    alias: sockg:amendmentPlacement
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    range: Any
    any_of:
    - range: string
    - range: double
  sockg:mgtAmendments_UID:
    name: sockg:mgtAmendments_UID
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 37796 occurrences with subject type sockg:Amendment and object type string.
    examples:
    - value: neo4j://graph.individuals#11252 sockg:mgtAmendments_UID AgCros_NEMLTCRS_214M_2015-05-13_Avena_sativa_Oats_80_Melilotus_officinalis_and_20_Trifolium_pratense_Clover_
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:mgtAmendments_UID
    alias: sockg:mgtAmendments_UID
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    range: string
  sockg:totalAmendmentAmount_kg_per_ha:
    name: sockg:totalAmendmentAmount_kg_per_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 37796 occurrences with subject type sockg:Amendment and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#25053 sockg:totalAmendmentAmount_kg_per_ha
        78.4
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:totalAmendmentAmount_kg_per_ha
    alias: sockg:totalAmendmentAmount_kg_per_ha
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    range: double
  sockg:startDate:
    name: sockg:startDate
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
    alias: sockg:startDate
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    - sockg:Experiment
    - sockg:ExperimentalUnit
    - sockg:GrazingManagementEvent
    range: Any
    any_of:
    - range: string
    - range: double
  sockg:irrigationAmount_cm:
    name: sockg:irrigationAmount_cm
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 37796 occurrences with subject type sockg:Amendment and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#393 sockg:irrigationAmount_cm nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:irrigationAmount_cm
    alias: sockg:irrigationAmount_cm
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    range: double
  sockg:totalNitrogenAmount_kgN_per_ha:
    name: sockg:totalNitrogenAmount_kgN_per_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 37796 occurrences with subject type sockg:Amendment and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#1491 sockg:totalNitrogenAmount_kgN_per_ha 89.998
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:totalNitrogenAmount_kgN_per_ha
    alias: sockg:totalNitrogenAmount_kgN_per_ha
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    range: double
  sockg:irrigationNitrogen_mg_per_L:
    name: sockg:irrigationNitrogen_mg_per_L
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 37796 occurrences with subject type sockg:Amendment and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#33235 sockg:irrigationNitrogen_mg_per_L nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:irrigationNitrogen_mg_per_L
    alias: sockg:irrigationNitrogen_mg_per_L
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    range: double
  sockg:type:
    name: sockg:type
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 22884 occurrences with subject type sockg:Amendment and object type string.
    - 14912 occurrences with subject type sockg:Amendment and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#22483 sockg:type Ammonium Sulfate
    - value: neo4j://graph.individuals#18536 sockg:type nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:type
    alias: sockg:type
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    range: Any
    any_of:
    - range: string
    - range: double
  sockg:treatmentId:
    name: sockg:treatmentId
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
    alias: sockg:treatmentId
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    - sockg:BioMassCarbohydrate
    - sockg:BioMassEnergy
    - sockg:BioMassMineral
    - sockg:CropGrowthStage
    - sockg:GasNutrientLoss
    - sockg:GasSample
    - sockg:Grazing
    - sockg:GrazingManagementEvent
    - sockg:Harvest
    - sockg:HarvestFraction
    - sockg:NutrientEfficiency
    - sockg:ResidueManagementEvent
    - sockg:SoilBiologicalSample
    - sockg:SoilChemicalSample
    - sockg:SoilPhysicalSample
    - sockg:Treatment
    - sockg:WaterQualityArea
    - sockg:WaterQualityConc
    - sockg:WindErosionArea
    - sockg:YieldNutrientUptake
    range: string
  sockg:totalPotassiumAmount_kgK_per_ha:
    name: sockg:totalPotassiumAmount_kgK_per_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 37796 occurrences with subject type sockg:Amendment and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#3835 sockg:totalPotassiumAmount_kgK_per_ha
        nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:totalPotassiumAmount_kgK_per_ha
    alias: sockg:totalPotassiumAmount_kgK_per_ha
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    range: double
  sockg:endDate:
    name: sockg:endDate
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
    alias: sockg:endDate
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    - sockg:Experiment
    - sockg:ExperimentalUnit
    - sockg:GrazingManagementEvent
    range: Any
    any_of:
    - range: double
    - range: string
  sockg:totalPhosphorusAmount_kgP_per_ha:
    name: sockg:totalPhosphorusAmount_kgP_per_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 37796 occurrences with subject type sockg:Amendment and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#13560 sockg:totalPhosphorusAmount_kgP_per_ha
        nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:totalPhosphorusAmount_kgP_per_ha
    alias: sockg:totalPhosphorusAmount_kgP_per_ha
    owner: sockg:Amendment
    domain_of:
    - sockg:Amendment
    range: double
class_uri: sockg:Amendment

```
</details>