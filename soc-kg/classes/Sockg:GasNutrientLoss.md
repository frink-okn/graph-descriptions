

# Class: TODO -- what's a good name for what this class (type) describes? (sockg:GasNutrientLoss)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:GasNutrientLoss](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/GasNutrientLoss)






```mermaid
 classDiagram
    class Sockg:GasNutrientLoss
    click Sockg:GasNutrientLoss href "../Sockg:GasNutrientLoss"
      Sockg:GasNutrientLoss : sockg:ammoniaNitrogen_kg_ha
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Double : sockg:ammoniaNitrogen_kg_ha
    click Double href "../Double"

        
      Sockg:GasNutrientLoss : sockg:ammoniaNitrogenStd_kg_ha
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Double : sockg:ammoniaNitrogenStd_kg_ha
    click Double href "../Double"

        
      Sockg:GasNutrientLoss : sockg:crop
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Any : sockg:crop
    click Any href "../Any"

        
      Sockg:GasNutrientLoss : sockg:date
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Any : sockg:date
    click Any href "../Any"

        
      Sockg:GasNutrientLoss : sockg:expUnit_UID
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" String : sockg:expUnit_UID
    click String href "../String"

        
      Sockg:GasNutrientLoss : sockg:expUnitId
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" String : sockg:expUnitId
    click String href "../String"

        
      Sockg:GasNutrientLoss : sockg:fieldId
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" String : sockg:fieldId
    click String href "../String"

        
      Sockg:GasNutrientLoss : sockg:growthStage
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Any : sockg:growthStage
    click Any href "../Any"

        
      Sockg:GasNutrientLoss : sockg:hasGasNutrientData
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Sockg:ExperimentalUnit : sockg:hasGasNutrientData
    click Sockg:ExperimentalUnit href "../Sockg:ExperimentalUnit"

        
      Sockg:GasNutrientLoss : sockg:measGasNutrientLoss_UID
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" String : sockg:measGasNutrientLoss_UID
    click String href "../String"

        
      Sockg:GasNutrientLoss : sockg:modelIfSimulated
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Any : sockg:modelIfSimulated
    click Any href "../Any"

        
      Sockg:GasNutrientLoss : sockg:nitrogenGas_g_ha
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Double : sockg:nitrogenGas_g_ha
    click Double href "../Double"

        
      Sockg:GasNutrientLoss : sockg:nitrogenGasStd_g_ha
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Double : sockg:nitrogenGasStd_g_ha
    click Double href "../Double"

        
      Sockg:GasNutrientLoss : sockg:nitrousOxide_g_ha
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Double : sockg:nitrousOxide_g_ha
    click Double href "../Double"

        
      Sockg:GasNutrientLoss : sockg:nitrousOxides_g_ha
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Double : sockg:nitrousOxides_g_ha
    click Double href "../Double"

        
      Sockg:GasNutrientLoss : sockg:nitrousOxidesStd_g_ha
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Double : sockg:nitrousOxidesStd_g_ha
    click Double href "../Double"

        
      Sockg:GasNutrientLoss : sockg:nitrousOxideStd_g_ha
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Double : sockg:nitrousOxideStd_g_ha
    click Double href "../Double"

        
      Sockg:GasNutrientLoss : sockg:samplingStartStopInterval
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Any : sockg:samplingStartStopInterval
    click Any href "../Any"

        
      Sockg:GasNutrientLoss : sockg:time
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" Any : sockg:time
    click Any href "../Any"

        
      Sockg:GasNutrientLoss : sockg:treatmentId
        
          
    
    
    Sockg:GasNutrientLoss --> "0..1" String : sockg:treatmentId
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg:hasGasNutrientData](../slots/sockg:hasGasNutrientData.md) | 0..1 <br/> [Sockg:ExperimentalUnit](../classes/Sockg:ExperimentalUnit.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:nitrousOxideStd_g_ha](../slots/sockg:nitrousOxideStd_g_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:expUnit_UID](../slots/sockg:expUnit_UID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:fieldId](../slots/sockg:fieldId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:expUnitId](../slots/sockg:expUnitId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:measGasNutrientLoss_UID](../slots/sockg:measGasNutrientLoss_UID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:date](../slots/sockg:date.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:ammoniaNitrogenStd_kg_ha](../slots/sockg:ammoniaNitrogenStd_kg_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:nitrousOxides_g_ha](../slots/sockg:nitrousOxides_g_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:modelIfSimulated](../slots/sockg:modelIfSimulated.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:samplingStartStopInterval](../slots/sockg:samplingStartStopInterval.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:nitrogenGasStd_g_ha](../slots/sockg:nitrogenGasStd_g_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:nitrousOxide_g_ha](../slots/sockg:nitrousOxide_g_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:treatmentId](../slots/sockg:treatmentId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:ammoniaNitrogen_kg_ha](../slots/sockg:ammoniaNitrogen_kg_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:nitrogenGas_g_ha](../slots/sockg:nitrogenGas_g_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:time](../slots/sockg:time.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:growthStage](../slots/sockg:growthStage.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:crop](../slots/sockg:crop.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:nitrousOxidesStd_g_ha](../slots/sockg:nitrousOxidesStd_g_ha.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |










## Examples

| Value |
| --- |
| neo4j://graph.individuals#55779 |

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
| self | sockg:GasNutrientLoss |
| native | soc-kg/main/:Sockg:GasNutrientLoss |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg:GasNutrientLoss
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 748 instances of this class.
examples:
- value: neo4j://graph.individuals#55779
from_schema: soc-kg/main
slots:
- sockg:hasGasNutrientData
- sockg:nitrousOxideStd_g_ha
- sockg:expUnit_UID
- sockg:fieldId
- sockg:expUnitId
- sockg:measGasNutrientLoss_UID
- sockg:date
- sockg:ammoniaNitrogenStd_kg_ha
- sockg:nitrousOxides_g_ha
- sockg:modelIfSimulated
- sockg:samplingStartStopInterval
- sockg:nitrogenGasStd_g_ha
- sockg:nitrousOxide_g_ha
- sockg:treatmentId
- sockg:ammoniaNitrogen_kg_ha
- sockg:nitrogenGas_g_ha
- sockg:time
- sockg:growthStage
- sockg:crop
- sockg:nitrousOxidesStd_g_ha
class_uri: sockg:GasNutrientLoss

```
</details>

### Induced

<details>
```yaml
name: sockg:GasNutrientLoss
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 748 instances of this class.
examples:
- value: neo4j://graph.individuals#55779
from_schema: soc-kg/main
attributes:
  sockg:hasGasNutrientData:
    name: sockg:hasGasNutrientData
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type sockg:ExperimentalUnit.
    examples:
    - value: neo4j://graph.individuals#55935 sockg:hasGasNutrientData neo4j://graph.individuals#55116
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasGasNutrientData
    alias: sockg:hasGasNutrientData
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
    range: sockg:ExperimentalUnit
  sockg:nitrousOxideStd_g_ha:
    name: sockg:nitrousOxideStd_g_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#55846 sockg:nitrousOxideStd_g_ha nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:nitrousOxideStd_g_ha
    alias: sockg:nitrousOxideStd_g_ha
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
    range: double
  sockg:expUnit_UID:
    name: sockg:expUnit_UID
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 3809 occurrences with subject type sockg:ExperimentalUnit and object type string.
    - 2791 occurrences with subject type sockg:NutrientEfficiency and object type
      string.
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
    - 429 occurrences with subject type sockg:YieldNutrientUptake and object type
      string.
    - 15 occurrences with subject type sockg:WindErosionArea and object type string.
    examples:
    - value: neo4j://graph.individuals#52433 sockg:expUnit_UID AgCros_TXLULIB1_26
    - value: neo4j://graph.individuals#201925 sockg:expUnit_UID AgCros_NELITCSE_201
    - value: neo4j://graph.individuals#55653 sockg:expUnit_UID AgCros_WIPDBARN_1
    - value: neo4j://graph.individuals#360941 sockg:expUnit_UID AgCros_IAAMKELL_120
    - value: neo4j://graph.individuals#509548 sockg:expUnit_UID AgCros_MNMOCAM_678
    - value: neo4j://graph.individuals#509309 sockg:expUnit_UID AgCros_TXBSWEWC_COMP3
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:expUnit_UID
    alias: sockg:expUnit_UID
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:ExperimentalUnit
    - sockg:GasNutrientLoss
    - sockg:NutrientEfficiency
    - sockg:WaterQualityConc
    - sockg:WindErosionArea
    - sockg:YieldNutrientUptake
    range: string
  sockg:fieldId:
    name: sockg:fieldId
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 2791 occurrences with subject type sockg:NutrientEfficiency and object type
      string.
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type string.
    - 429 occurrences with subject type sockg:YieldNutrientUptake and object type
      string.
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
    - 15 occurrences with subject type sockg:WindErosionArea and object type string.
    - 58 occurrences with subject type sockg:Field and object type string.
    examples:
    - value: neo4j://graph.individuals#201298 sockg:fieldId NELITCSE
    - value: neo4j://graph.individuals#55677 sockg:fieldId WIPDBARN
    - value: neo4j://graph.individuals#360040 sockg:fieldId WIPDBARN
    - value: neo4j://graph.individuals#509384 sockg:fieldId ALAURye
    - value: neo4j://graph.individuals#361395 sockg:fieldId WIPDBARN
    - value: neo4j://graph.individuals#509301 sockg:fieldId TXBSWEWC
    - value: neo4j://graph.individuals#55606 sockg:fieldId NELITCSE
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:fieldId
    alias: sockg:fieldId
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:Field
    - sockg:GasNutrientLoss
    - sockg:NutrientEfficiency
    - sockg:WaterQualityArea
    - sockg:WaterQualityConc
    - sockg:WindErosionArea
    - sockg:YieldNutrientUptake
    range: string
  sockg:expUnitId:
    name: sockg:expUnitId
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 3809 occurrences with subject type sockg:ExperimentalUnit and object type string.
    - 2791 occurrences with subject type sockg:NutrientEfficiency and object type
      string.
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type string.
    - 429 occurrences with subject type sockg:YieldNutrientUptake and object type
      string.
    - 15 occurrences with subject type sockg:WindErosionArea and object type string.
    examples:
    - value: neo4j://graph.individuals#52840 sockg:expUnitId GAJPCSR1_B2P102F1H1X600Y90
    - value: neo4j://graph.individuals#201638 sockg:expUnitId NELITCSE_509
    - value: neo4j://graph.individuals#55654 sockg:expUnitId WIPDBARN_3
    - value: neo4j://graph.individuals#360565 sockg:expUnitId IAAMKELL__120
    - value: neo4j://graph.individuals#359954 sockg:expUnitId WIPDBARN_1
    - value: neo4j://graph.individuals#509440 sockg:expUnitId ALAURye_410
    - value: neo4j://graph.individuals#509305 sockg:expUnitId TXBSWEWC_COMP5
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:expUnitId
    alias: sockg:expUnitId
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:ExperimentalUnit
    - sockg:GasNutrientLoss
    - sockg:NutrientEfficiency
    - sockg:WaterQualityArea
    - sockg:WaterQualityConc
    - sockg:WindErosionArea
    - sockg:YieldNutrientUptake
    range: string
  sockg:measGasNutrientLoss_UID:
    name: sockg:measGasNutrientLoss_UID
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
    examples:
    - value: neo4j://graph.individuals#55732 sockg:measGasNutrientLoss_UID AgCros_WIPDBARN_7_2012-10-25
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:measGasNutrientLoss_UID
    alias: sockg:measGasNutrientLoss_UID
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
    range: string
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
    owner: sockg:GasNutrientLoss
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
  sockg:ammoniaNitrogenStd_kg_ha:
    name: sockg:ammoniaNitrogenStd_kg_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#55767 sockg:ammoniaNitrogenStd_kg_ha nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:ammoniaNitrogenStd_kg_ha
    alias: sockg:ammoniaNitrogenStd_kg_ha
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
    range: double
  sockg:nitrousOxides_g_ha:
    name: sockg:nitrousOxides_g_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#55756 sockg:nitrousOxides_g_ha nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:nitrousOxides_g_ha
    alias: sockg:nitrousOxides_g_ha
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
    range: double
  sockg:modelIfSimulated:
    name: sockg:modelIfSimulated
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 429 occurrences with subject type sockg:YieldNutrientUptake and object type
      xsd:double.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
    - 692 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    - 1466 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    - 56 occurrences with subject type sockg:GasNutrientLoss and object type string.
    - 13 occurrences with subject type sockg:WaterQualityConc and object type string.
    - 4 occurrences with subject type sockg:WindErosionArea and object type string.
    - 11 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#509423 sockg:modelIfSimulated nan
    - value: neo4j://graph.individuals#360133 sockg:modelIfSimulated nan
    - value: neo4j://graph.individuals#56071 sockg:modelIfSimulated nan
    - value: neo4j://graph.individuals#361440 sockg:modelIfSimulated nan
    - value: neo4j://graph.individuals#55638 sockg:modelIfSimulated RZWQM
    - value: neo4j://graph.individuals#361269 sockg:modelIfSimulated RZWQM
    - value: neo4j://graph.individuals#509307 sockg:modelIfSimulated Linear Proportional
        with particle size correction factor
    - value: neo4j://graph.individuals#509303 sockg:modelIfSimulated nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:modelIfSimulated
    alias: sockg:modelIfSimulated
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
    - sockg:WaterQualityArea
    - sockg:WaterQualityConc
    - sockg:WindErosionArea
    - sockg:YieldNutrientUptake
    range: Any
    any_of:
    - range: double
    - range: string
  sockg:samplingStartStopInterval:
    name: sockg:samplingStartStopInterval
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 667 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    - 684 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
    - 812 occurrences with subject type sockg:WaterQualityConc and object type string.
    - 15 occurrences with subject type sockg:WindErosionArea and object type string.
    - 64 occurrences with subject type sockg:GasNutrientLoss and object type string.
    examples:
    - value: neo4j://graph.individuals#361366 sockg:samplingStartStopInterval nan
    - value: neo4j://graph.individuals#56298 sockg:samplingStartStopInterval nan
    - value: neo4j://graph.individuals#360222 sockg:samplingStartStopInterval nan
    - value: neo4j://graph.individuals#360975 sockg:samplingStartStopInterval Stop-Start
    - value: neo4j://graph.individuals#509301 sockg:samplingStartStopInterval Stop
    - value: neo4j://graph.individuals#56333 sockg:samplingStartStopInterval Stop-Start
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:samplingStartStopInterval
    alias: sockg:samplingStartStopInterval
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
    - sockg:WaterQualityArea
    - sockg:WaterQualityConc
    - sockg:WindErosionArea
    range: Any
    any_of:
    - range: double
    - range: string
  sockg:nitrogenGasStd_g_ha:
    name: sockg:nitrogenGasStd_g_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#56324 sockg:nitrogenGasStd_g_ha nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:nitrogenGasStd_g_ha
    alias: sockg:nitrogenGasStd_g_ha
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
    range: double
  sockg:nitrousOxide_g_ha:
    name: sockg:nitrousOxide_g_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#56155 sockg:nitrousOxide_g_ha 14.806486
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:nitrousOxide_g_ha
    alias: sockg:nitrousOxide_g_ha
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
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
    owner: sockg:GasNutrientLoss
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
  sockg:ammoniaNitrogen_kg_ha:
    name: sockg:ammoniaNitrogen_kg_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#55723 sockg:ammoniaNitrogen_kg_ha 0.0
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:ammoniaNitrogen_kg_ha
    alias: sockg:ammoniaNitrogen_kg_ha
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
    range: double
  sockg:nitrogenGas_g_ha:
    name: sockg:nitrogenGas_g_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#56224 sockg:nitrogenGas_g_ha nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:nitrogenGas_g_ha
    alias: sockg:nitrogenGas_g_ha
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
    range: double
  sockg:time:
    name: sockg:time
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 101883 occurrences with subject type sockg:GasSample and object type xsd:double.
    - 5471 occurrences with subject type sockg:GasSample and object type string.
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
    - 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#97100 sockg:time nan
    - value: neo4j://graph.individuals#160382 sockg:time 11:09:00
    - value: neo4j://graph.individuals#361705 sockg:time nan
    - value: neo4j://graph.individuals#55832 sockg:time nan
    - value: neo4j://graph.individuals#360324 sockg:time nan
    - value: neo4j://graph.individuals#509313 sockg:time nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:time
    alias: sockg:time
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
    - sockg:GasSample
    - sockg:WaterQualityArea
    - sockg:WaterQualityConc
    - sockg:WindErosionArea
    range: Any
    any_of:
    - range: double
    - range: string
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
    owner: sockg:GasNutrientLoss
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
    owner: sockg:GasNutrientLoss
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
  sockg:nitrousOxidesStd_g_ha:
    name: sockg:nitrousOxidesStd_g_ha
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#56101 sockg:nitrousOxidesStd_g_ha nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:nitrousOxidesStd_g_ha
    alias: sockg:nitrousOxidesStd_g_ha
    owner: sockg:GasNutrientLoss
    domain_of:
    - sockg:GasNutrientLoss
    range: double
class_uri: sockg:GasNutrientLoss

```
</details>