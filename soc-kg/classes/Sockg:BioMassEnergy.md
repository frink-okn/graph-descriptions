

# Class: TODO -- what's a good name for what this class (type) describes? (sockg:BioMassEnergy)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:BioMassEnergy](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/BioMassEnergy)






```mermaid
 classDiagram
    class Sockg:BioMassEnergy
    click Sockg:BioMassEnergy href "../Sockg:BioMassEnergy"
      Sockg:BioMassEnergy : sockg:crop
        
          
    
    
    Sockg:BioMassEnergy --> "0..1" Any : sockg:crop
    click Any href "../Any"

        
      Sockg:BioMassEnergy : sockg:date
        
          
    
    
    Sockg:BioMassEnergy --> "0..1" Any : sockg:date
    click Any href "../Any"

        
      Sockg:BioMassEnergy : sockg:grossCalorificValue_MJ_per_kg
        
          
    
    
    Sockg:BioMassEnergy --> "0..1" Double : sockg:grossCalorificValue_MJ_per_kg
    click Double href "../Double"

        
      Sockg:BioMassEnergy : sockg:grossCalorificValueStd_MJ_per_kg
        
          
    
    
    Sockg:BioMassEnergy --> "0..1" Double : sockg:grossCalorificValueStd_MJ_per_kg
    click Double href "../Double"

        
      Sockg:BioMassEnergy : sockg:growthStage
        
          
    
    
    Sockg:BioMassEnergy --> "0..1" Any : sockg:growthStage
    click Any href "../Any"

        
      Sockg:BioMassEnergy : sockg:measBiomassEnergy_UID
        
          
    
    
    Sockg:BioMassEnergy --> "0..1" String : sockg:measBiomassEnergy_UID
    click String href "../String"

        
      Sockg:BioMassEnergy : sockg:mineralMatter_g_per_kg
        
          
    
    
    Sockg:BioMassEnergy --> "0..1" Double : sockg:mineralMatter_g_per_kg
    click Double href "../Double"

        
      Sockg:BioMassEnergy : sockg:mineralMatterStd_g_per_kg
        
          
    
    
    Sockg:BioMassEnergy --> "0..1" Double : sockg:mineralMatterStd_g_per_kg
    click Double href "../Double"

        
      Sockg:BioMassEnergy : sockg:plantFraction
        
          
    
    
    Sockg:BioMassEnergy --> "0..1" Any : sockg:plantFraction
    click Any href "../Any"

        
      Sockg:BioMassEnergy : sockg:treatmentId
        
          
    
    
    Sockg:BioMassEnergy --> "0..1" String : sockg:treatmentId
    click String href "../String"

        
      Sockg:BioMassEnergy : sockg:volatileMatter_g_per_kg
        
          
    
    
    Sockg:BioMassEnergy --> "0..1" Double : sockg:volatileMatter_g_per_kg
    click Double href "../Double"

        
      Sockg:BioMassEnergy : sockg:volatileMatterStd_g_per_kg
        
          
    
    
    Sockg:BioMassEnergy --> "0..1" Double : sockg:volatileMatterStd_g_per_kg
    click Double href "../Double"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg:mineralMatter_g_per_kg](../slots/sockg:mineralMatter_g_per_kg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:treatmentId](../slots/sockg:treatmentId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:grossCalorificValueStd_MJ_per_kg](../slots/sockg:grossCalorificValueStd_MJ_per_kg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:grossCalorificValue_MJ_per_kg](../slots/sockg:grossCalorificValue_MJ_per_kg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:measBiomassEnergy_UID](../slots/sockg:measBiomassEnergy_UID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:volatileMatterStd_g_per_kg](../slots/sockg:volatileMatterStd_g_per_kg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:growthStage](../slots/sockg:growthStage.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:volatileMatter_g_per_kg](../slots/sockg:volatileMatter_g_per_kg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:crop](../slots/sockg:crop.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:plantFraction](../slots/sockg:plantFraction.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:mineralMatterStd_g_per_kg](../slots/sockg:mineralMatterStd_g_per_kg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:date](../slots/sockg:date.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Sockg:ExperimentalUnit](../classes/Sockg:ExperimentalUnit.md) | [sockg:hasBioMassEnergyData](../slots/sockg:hasBioMassEnergyData.md) | range | [Sockg:BioMassEnergy](../classes/Sockg:BioMassEnergy.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#39482 |

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
| self | sockg:BioMassEnergy |
| native | soc-kg/main/:Sockg:BioMassEnergy |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg:BioMassEnergy
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 799 instances of this class.
examples:
- value: neo4j://graph.individuals#39482
from_schema: soc-kg/main
slots:
- sockg:mineralMatter_g_per_kg
- sockg:treatmentId
- sockg:grossCalorificValueStd_MJ_per_kg
- sockg:grossCalorificValue_MJ_per_kg
- sockg:measBiomassEnergy_UID
- sockg:volatileMatterStd_g_per_kg
- sockg:growthStage
- sockg:volatileMatter_g_per_kg
- sockg:crop
- sockg:plantFraction
- sockg:mineralMatterStd_g_per_kg
- sockg:date
class_uri: sockg:BioMassEnergy

```
</details>

### Induced

<details>
```yaml
name: sockg:BioMassEnergy
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 799 instances of this class.
examples:
- value: neo4j://graph.individuals#39482
from_schema: soc-kg/main
attributes:
  sockg:mineralMatter_g_per_kg:
    name: sockg:mineralMatter_g_per_kg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 799 occurrences with subject type sockg:BioMassEnergy and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#39273 sockg:mineralMatter_g_per_kg 49.5
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:mineralMatter_g_per_kg
    alias: sockg:mineralMatter_g_per_kg
    owner: sockg:BioMassEnergy
    domain_of:
    - sockg:BioMassEnergy
    range: double
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
    owner: sockg:BioMassEnergy
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
  sockg:grossCalorificValueStd_MJ_per_kg:
    name: sockg:grossCalorificValueStd_MJ_per_kg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 799 occurrences with subject type sockg:BioMassEnergy and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#39475 sockg:grossCalorificValueStd_MJ_per_kg
        nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:grossCalorificValueStd_MJ_per_kg
    alias: sockg:grossCalorificValueStd_MJ_per_kg
    owner: sockg:BioMassEnergy
    domain_of:
    - sockg:BioMassEnergy
    range: double
  sockg:grossCalorificValue_MJ_per_kg:
    name: sockg:grossCalorificValue_MJ_per_kg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 799 occurrences with subject type sockg:BioMassEnergy and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#39522 sockg:grossCalorificValue_MJ_per_kg 18.4226
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:grossCalorificValue_MJ_per_kg
    alias: sockg:grossCalorificValue_MJ_per_kg
    owner: sockg:BioMassEnergy
    domain_of:
    - sockg:BioMassEnergy
    range: double
  sockg:measBiomassEnergy_UID:
    name: sockg:measBiomassEnergy_UID
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 799 occurrences with subject type sockg:BioMassEnergy and object type string.
    examples:
    - value: neo4j://graph.individuals#39390 sockg:measBiomassEnergy_UID AgCros_SCFLSGI_421_2009-09-01_Zea_mays_Corn_Above_earshank
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:measBiomassEnergy_UID
    alias: sockg:measBiomassEnergy_UID
    owner: sockg:BioMassEnergy
    domain_of:
    - sockg:BioMassEnergy
    range: string
  sockg:volatileMatterStd_g_per_kg:
    name: sockg:volatileMatterStd_g_per_kg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 799 occurrences with subject type sockg:BioMassEnergy and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#39932 sockg:volatileMatterStd_g_per_kg nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:volatileMatterStd_g_per_kg
    alias: sockg:volatileMatterStd_g_per_kg
    owner: sockg:BioMassEnergy
    domain_of:
    - sockg:BioMassEnergy
    range: double
  sockg:growthStage:
    name: sockg:growthStage
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 17240 occurrences with subject type sockg:Harvest and object type string.
    - 6683 occurrences with subject type sockg:Grazing and object type string.
    - 6723 occurrences with subject type sockg:BioMassMineral and object type string.
    - 2791 occurrences with subject type sockg:NutrientEfficiency and object type
      string.
    - 9407 occurrences with subject type sockg:HarvestFraction and object type string.
    - 4896 occurrences with subject type sockg:CropGrowthStage and object type string.
    - 1367 occurrences with subject type sockg:BioMassCarbohydrate and object type
      string.
    - 799 occurrences with subject type sockg:BioMassEnergy and object type string.
    - 1116 occurrences with subject type sockg:Harvest and object type xsd:double.
    - 667 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    - 812 occurrences with subject type sockg:WaterQualityConc and object type string.
    - 684 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
    - 312 occurrences with subject type sockg:Grazing and object type xsd:double.
    - 429 occurrences with subject type sockg:YieldNutrientUptake and object type
      string.
    - 64 occurrences with subject type sockg:GasNutrientLoss and object type string.
    - 15 occurrences with subject type sockg:WindErosionArea and object type string.
    - 63 occurrences with subject type sockg:HarvestFraction and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#179594 sockg:growthStage Maturity
    - value: neo4j://graph.individuals#169328 sockg:growthStage Maturity
    - value: neo4j://graph.individuals#42420 sockg:growthStage Maturity
    - value: neo4j://graph.individuals#201140 sockg:growthStage Maturity
    - value: neo4j://graph.individuals#192092 sockg:growthStage Maturity
    - value: neo4j://graph.individuals#48294 sockg:growthStage V8
    - value: neo4j://graph.individuals#38319 sockg:growthStage Harvest
    - value: neo4j://graph.individuals#39266 sockg:growthStage Harvest
    - value: neo4j://graph.individuals#181402 sockg:growthStage nan
    - value: neo4j://graph.individuals#361570 sockg:growthStage nan
    - value: neo4j://graph.individuals#360617 sockg:growthStage Pre-graze
    - value: neo4j://graph.individuals#55868 sockg:growthStage nan
    - value: neo4j://graph.individuals#360003 sockg:growthStage nan
    - value: neo4j://graph.individuals#170558 sockg:growthStage nan
    - value: neo4j://graph.individuals#509424 sockg:growthStage Harvest
    - value: neo4j://graph.individuals#56329 sockg:growthStage Pre-graze
    - value: neo4j://graph.individuals#509305 sockg:growthStage Pre-graze
    - value: neo4j://graph.individuals#194095 sockg:growthStage nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:growthStage
    alias: sockg:growthStage
    owner: sockg:BioMassEnergy
    domain_of:
    - sockg:BioMassCarbohydrate
    - sockg:BioMassEnergy
    - sockg:BioMassMineral
    - sockg:CropGrowthStage
    - sockg:GasNutrientLoss
    - sockg:Grazing
    - sockg:Harvest
    - sockg:HarvestFraction
    - sockg:NutrientEfficiency
    - sockg:WaterQualityArea
    - sockg:WaterQualityConc
    - sockg:WindErosionArea
    - sockg:YieldNutrientUptake
    range: Any
    any_of:
    - range: string
    - range: double
  sockg:volatileMatter_g_per_kg:
    name: sockg:volatileMatter_g_per_kg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 799 occurrences with subject type sockg:BioMassEnergy and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#39615 sockg:volatileMatter_g_per_kg nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:volatileMatter_g_per_kg
    alias: sockg:volatileMatter_g_per_kg
    owner: sockg:BioMassEnergy
    domain_of:
    - sockg:BioMassEnergy
    range: double
  sockg:crop:
    name: sockg:crop
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 2791 occurrences with subject type sockg:NutrientEfficiency and object type
      string.
    - 105046 occurrences with subject type sockg:GasSample and object type string.
    - 6723 occurrences with subject type sockg:BioMassMineral and object type string.
    - 429 occurrences with subject type sockg:YieldNutrientUptake and object type
      string.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
    - 1367 occurrences with subject type sockg:BioMassCarbohydrate and object type
      string.
    - 799 occurrences with subject type sockg:BioMassEnergy and object type string.
    - 2308 occurrences with subject type sockg:GasSample and object type xsd:double.
    - 553 occurrences with subject type sockg:WaterQualityConc and object type string.
    - 698 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    - 926 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    - 50 occurrences with subject type sockg:GasNutrientLoss and object type string.
    - 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#201065 sockg:crop Zea mays (Corn)
    - value: neo4j://graph.individuals#156219 sockg:crop Zea mays (Corn)
    - value: neo4j://graph.individuals#45025 sockg:crop Zea mays (Corn)
    - value: neo4j://graph.individuals#509340 sockg:crop Secale cereale (Rye)
    - value: neo4j://graph.individuals#360357 sockg:crop nan
    - value: neo4j://graph.individuals#37850 sockg:crop Zea mays (Corn)
    - value: neo4j://graph.individuals#39943 sockg:crop Zea mays (Corn)
    - value: neo4j://graph.individuals#112348 sockg:crop nan
    - value: neo4j://graph.individuals#360717 sockg:crop Glycine max (Soybean)
    - value: neo4j://graph.individuals#56206 sockg:crop nan
    - value: neo4j://graph.individuals#361559 sockg:crop nan
    - value: neo4j://graph.individuals#56324 sockg:crop Secale cereale (Rye)
    - value: neo4j://graph.individuals#509306 sockg:crop nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:crop
    alias: sockg:crop
    owner: sockg:BioMassEnergy
    domain_of:
    - sockg:BioMassCarbohydrate
    - sockg:BioMassEnergy
    - sockg:BioMassMineral
    - sockg:GasNutrientLoss
    - sockg:GasSample
    - sockg:NutrientEfficiency
    - sockg:WaterQualityArea
    - sockg:WaterQualityConc
    - sockg:WindErosionArea
    - sockg:YieldNutrientUptake
    range: Any
    any_of:
    - range: string
    - range: double
  sockg:plantFraction:
    name: sockg:plantFraction
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 9470 occurrences with subject type sockg:HarvestFraction and object type string.
    - 6723 occurrences with subject type sockg:BioMassMineral and object type string.
    - 2683 occurrences with subject type sockg:NutrientEfficiency and object type
      string.
    - 429 occurrences with subject type sockg:YieldNutrientUptake and object type
      string.
    - 1367 occurrences with subject type sockg:BioMassCarbohydrate and object type
      string.
    - 799 occurrences with subject type sockg:BioMassEnergy and object type string.
    - 108 occurrences with subject type sockg:NutrientEfficiency and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#192293 sockg:plantFraction Grain
    - value: neo4j://graph.individuals#44722 sockg:plantFraction Grain
    - value: neo4j://graph.individuals#201773 sockg:plantFraction Grain
    - value: neo4j://graph.individuals#509641 sockg:plantFraction Roots
    - value: neo4j://graph.individuals#37806 sockg:plantFraction Above earshank
    - value: neo4j://graph.individuals#39360 sockg:plantFraction Cobs
    - value: neo4j://graph.individuals#200713 sockg:plantFraction nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:plantFraction
    alias: sockg:plantFraction
    owner: sockg:BioMassEnergy
    domain_of:
    - sockg:BioMassCarbohydrate
    - sockg:BioMassEnergy
    - sockg:BioMassMineral
    - sockg:HarvestFraction
    - sockg:NutrientEfficiency
    - sockg:YieldNutrientUptake
    range: Any
    any_of:
    - range: string
    - range: double
  sockg:mineralMatterStd_g_per_kg:
    name: sockg:mineralMatterStd_g_per_kg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 799 occurrences with subject type sockg:BioMassEnergy and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#39758 sockg:mineralMatterStd_g_per_kg nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:mineralMatterStd_g_per_kg
    alias: sockg:mineralMatterStd_g_per_kg
    owner: sockg:BioMassEnergy
    domain_of:
    - sockg:BioMassEnergy
    range: double
  sockg:date:
    name: sockg:date
    description: TODO -- tell the world what this slot (predicate) describes.
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
    alias: sockg:date
    owner: sockg:BioMassEnergy
    domain_of:
    - sockg:BioMassCarbohydrate
    - sockg:BioMassEnergy
    - sockg:BioMassMineral
    - sockg:CropGrowthStage
    - sockg:GasNutrientLoss
    - sockg:GasSample
    - sockg:Grazing
    - sockg:Harvest
    - sockg:NutrientEfficiency
    - sockg:ResidueManagementEvent
    - sockg:SoilBiologicalSample
    - sockg:SoilChemicalSample
    - sockg:SoilCover
    - sockg:SoilPhysicalSample
    - sockg:WaterQualityArea
    - sockg:WaterQualityConc
    - sockg:WeatherObservation
    - sockg:WindErosionArea
    - sockg:YieldNutrientUptake
    range: Any
    any_of:
    - range: string
    - range: double
class_uri: sockg:BioMassEnergy

```
</details>