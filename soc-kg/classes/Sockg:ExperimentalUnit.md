

# Class: TODO -- what's a good name for what this class (type) describes? (sockg:ExperimentalUnit)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:ExperimentalUnit](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/ExperimentalUnit)






```mermaid
 classDiagram
    class Sockg:ExperimentalUnit
    click Sockg:ExperimentalUnit href "../Sockg:ExperimentalUnit"
      Sockg:ExperimentalUnit : sockg:changeInManagement
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Double : sockg:changeInManagement
    click Double href "../Double"

        
      Sockg:ExperimentalUnit : sockg:endDate
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Any : sockg:endDate
    click Any href "../Any"

        
      Sockg:ExperimentalUnit : sockg:expUnit_UID
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" String : sockg:expUnit_UID
    click String href "../String"

        
      Sockg:ExperimentalUnit : sockg:expUnitId
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" String : sockg:expUnitId
    click String href "../String"

        
      Sockg:ExperimentalUnit : sockg:hasAmendment
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:Amendment : sockg:hasAmendment
    click Sockg:Amendment href "../Sockg:Amendment"

        
      Sockg:ExperimentalUnit : sockg:hasBioMassCarbohydrateData
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:BioMassCarbohydrate : sockg:hasBioMassCarbohydrateData
    click Sockg:BioMassCarbohydrate href "../Sockg:BioMassCarbohydrate"

        
      Sockg:ExperimentalUnit : sockg:hasBioMassEnergyData
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:BioMassEnergy : sockg:hasBioMassEnergyData
    click Sockg:BioMassEnergy href "../Sockg:BioMassEnergy"

        
      Sockg:ExperimentalUnit : sockg:hasBioMassMineralData
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:BioMassMineral : sockg:hasBioMassMineralData
    click Sockg:BioMassMineral href "../Sockg:BioMassMineral"

        
      Sockg:ExperimentalUnit : sockg:hasBioSample
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:SoilBiologicalSample : sockg:hasBioSample
    click Sockg:SoilBiologicalSample href "../Sockg:SoilBiologicalSample"

        
      Sockg:ExperimentalUnit : sockg:hasChemSample
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:SoilChemicalSample : sockg:hasChemSample
    click Sockg:SoilChemicalSample href "../Sockg:SoilChemicalSample"

        
      Sockg:ExperimentalUnit : sockg:hasGasSample
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:GasSample : sockg:hasGasSample
    click Sockg:GasSample href "../Sockg:GasSample"

        
      Sockg:ExperimentalUnit : sockg:hasGrazingData
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:Grazing : sockg:hasGrazingData
    click Sockg:Grazing href "../Sockg:Grazing"

        
      Sockg:ExperimentalUnit : sockg:hasGrazingManagementEvent
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:GrazingManagementEvent : sockg:hasGrazingManagementEvent
    click Sockg:GrazingManagementEvent href "../Sockg:GrazingManagementEvent"

        
      Sockg:ExperimentalUnit : sockg:hasHarvestFractionData
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:HarvestFraction : sockg:hasHarvestFractionData
    click Sockg:HarvestFraction href "../Sockg:HarvestFraction"

        
      Sockg:ExperimentalUnit : sockg:hasPhySample
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:SoilPhysicalSample : sockg:hasPhySample
    click Sockg:SoilPhysicalSample href "../Sockg:SoilPhysicalSample"

        
      Sockg:ExperimentalUnit : sockg:hasResidueManagementEvent
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:ResidueManagementEvent : sockg:hasResidueManagementEvent
    click Sockg:ResidueManagementEvent href "../Sockg:ResidueManagementEvent"

        
      Sockg:ExperimentalUnit : sockg:hasTillage
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:Tillage : sockg:hasTillage
    click Sockg:Tillage href "../Sockg:Tillage"

        
      Sockg:ExperimentalUnit : sockg:isHarvested
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:Harvest : sockg:isHarvested
    click Sockg:Harvest href "../Sockg:Harvest"

        
      Sockg:ExperimentalUnit : sockg:locatedInField
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:Field : sockg:locatedInField
    click Sockg:Field href "../Sockg:Field"

        
      Sockg:ExperimentalUnit : sockg:startDate
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Any : sockg:startDate
    click Any href "../Any"

        
      Sockg:ExperimentalUnit : sockg:tracksGrowth
        
          
    
    
    Sockg:ExperimentalUnit --> "0..1" Sockg:CropGrowthStage : sockg:tracksGrowth
    click Sockg:CropGrowthStage href "../Sockg:CropGrowthStage"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg:hasBioSample](../slots/sockg:hasBioSample.md) | 0..1 <br/> [Sockg:SoilBiologicalSample](../classes/Sockg:SoilBiologicalSample.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:hasChemSample](../slots/sockg:hasChemSample.md) | 0..1 <br/> [Sockg:SoilChemicalSample](../classes/Sockg:SoilChemicalSample.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:hasPhySample](../slots/sockg:hasPhySample.md) | 0..1 <br/> [Sockg:SoilPhysicalSample](../classes/Sockg:SoilPhysicalSample.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:hasHarvestFractionData](../slots/sockg:hasHarvestFractionData.md) | 0..1 <br/> [Sockg:HarvestFraction](../classes/Sockg:HarvestFraction.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:hasBioMassMineralData](../slots/sockg:hasBioMassMineralData.md) | 0..1 <br/> [Sockg:BioMassMineral](../classes/Sockg:BioMassMineral.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:hasGasSample](../slots/sockg:hasGasSample.md) | 0..1 <br/> [Sockg:GasSample](../classes/Sockg:GasSample.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:hasGrazingData](../slots/sockg:hasGrazingData.md) | 0..1 <br/> [Sockg:Grazing](../classes/Sockg:Grazing.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:hasTillage](../slots/sockg:hasTillage.md) | 0..1 <br/> [Sockg:Tillage](../classes/Sockg:Tillage.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:hasAmendment](../slots/sockg:hasAmendment.md) | 0..1 <br/> [Sockg:Amendment](../classes/Sockg:Amendment.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:tracksGrowth](../slots/sockg:tracksGrowth.md) | 0..1 <br/> [Sockg:CropGrowthStage](../classes/Sockg:CropGrowthStage.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:hasGrazingManagementEvent](../slots/sockg:hasGrazingManagementEvent.md) | 0..1 <br/> [Sockg:GrazingManagementEvent](../classes/Sockg:GrazingManagementEvent.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:isHarvested](../slots/sockg:isHarvested.md) | 0..1 <br/> [Sockg:Harvest](../classes/Sockg:Harvest.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:locatedInField](../slots/sockg:locatedInField.md) | 0..1 <br/> [Sockg:Field](../classes/Sockg:Field.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:hasBioMassEnergyData](../slots/sockg:hasBioMassEnergyData.md) | 0..1 <br/> [Sockg:BioMassEnergy](../classes/Sockg:BioMassEnergy.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:hasBioMassCarbohydrateData](../slots/sockg:hasBioMassCarbohydrateData.md) | 0..1 <br/> [Sockg:BioMassCarbohydrate](../classes/Sockg:BioMassCarbohydrate.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:hasResidueManagementEvent](../slots/sockg:hasResidueManagementEvent.md) | 0..1 <br/> [Sockg:ResidueManagementEvent](../classes/Sockg:ResidueManagementEvent.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:changeInManagement](../slots/sockg:changeInManagement.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:expUnit_UID](../slots/sockg:expUnit_UID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:expUnitId](../slots/sockg:expUnitId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:endDate](../slots/sockg:endDate.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:startDate](../slots/sockg:startDate.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Sockg:GasNutrientLoss](../classes/Sockg:GasNutrientLoss.md) | [sockg:hasGasNutrientData](../slots/sockg:hasGasNutrientData.md) | range | [Sockg:ExperimentalUnit](../classes/Sockg:ExperimentalUnit.md) |
| [Sockg:PlantingEvent](../classes/Sockg:PlantingEvent.md) | [sockg:plantingAt](../slots/sockg:plantingAt.md) | range | [Sockg:ExperimentalUnit](../classes/Sockg:ExperimentalUnit.md) |
| [Sockg:WaterQualityArea](../classes/Sockg:WaterQualityArea.md) | [sockg:hasWaterQualityAreaData](../slots/sockg:hasWaterQualityAreaData.md) | range | [Sockg:ExperimentalUnit](../classes/Sockg:ExperimentalUnit.md) |
| [Sockg:WaterQualityConc](../classes/Sockg:WaterQualityConc.md) | [sockg:hasWaterQualityConcData](../slots/sockg:hasWaterQualityConcData.md) | range | [Sockg:ExperimentalUnit](../classes/Sockg:ExperimentalUnit.md) |
| [Sockg:WindErosionArea](../classes/Sockg:WindErosionArea.md) | [sockg:hasWindErosionData](../slots/sockg:hasWindErosionData.md) | range | [Sockg:ExperimentalUnit](../classes/Sockg:ExperimentalUnit.md) |
| [Sockg:YieldNutrientUptake](../classes/Sockg:YieldNutrientUptake.md) | [sockg:hasYieldNutrUptakeData](../slots/sockg:hasYieldNutrUptakeData.md) | range | [Sockg:ExperimentalUnit](../classes/Sockg:ExperimentalUnit.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#53969 |

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
| self | sockg:ExperimentalUnit |
| native | soc-kg/main/:Sockg:ExperimentalUnit |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg:ExperimentalUnit
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 3809 instances of this class.
examples:
- value: neo4j://graph.individuals#53969
from_schema: soc-kg/main
slots:
- sockg:hasBioSample
- sockg:hasChemSample
- sockg:hasPhySample
- sockg:hasHarvestFractionData
- sockg:hasBioMassMineralData
- sockg:hasGasSample
- sockg:hasGrazingData
- sockg:hasTillage
- sockg:hasAmendment
- sockg:tracksGrowth
- sockg:hasGrazingManagementEvent
- sockg:isHarvested
- sockg:locatedInField
- sockg:hasBioMassEnergyData
- sockg:hasBioMassCarbohydrateData
- sockg:hasResidueManagementEvent
- sockg:changeInManagement
- sockg:expUnit_UID
- sockg:expUnitId
- sockg:endDate
- sockg:startDate
class_uri: sockg:ExperimentalUnit

```
</details>

### Induced

<details>
```yaml
name: sockg:ExperimentalUnit
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 3809 instances of this class.
examples:
- value: neo4j://graph.individuals#53969
from_schema: soc-kg/main
attributes:
  sockg:hasBioSample:
    name: sockg:hasBioSample
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 16926 occurrences with subject type sockg:ExperimentalUnit and object type sockg:SoilBiologicalSample.
    examples:
    - value: neo4j://graph.individuals#53017 sockg:hasBioSample neo4j://graph.individuals#243735
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasBioSample
    alias: sockg:hasBioSample
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:SoilBiologicalSample
  sockg:hasChemSample:
    name: sockg:hasChemSample
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 52537 occurrences with subject type sockg:ExperimentalUnit and object type sockg:SoilChemicalSample.
    examples:
    - value: neo4j://graph.individuals#53001 sockg:hasChemSample neo4j://graph.individuals#278161
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasChemSample
    alias: sockg:hasChemSample
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:SoilChemicalSample
  sockg:hasPhySample:
    name: sockg:hasPhySample
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 26786 occurrences with subject type sockg:ExperimentalUnit and object type sockg:SoilPhysicalSample.
    examples:
    - value: neo4j://graph.individuals#53109 sockg:hasPhySample neo4j://graph.individuals#310589
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasPhySample
    alias: sockg:hasPhySample
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:SoilPhysicalSample
  sockg:hasHarvestFractionData:
    name: sockg:hasHarvestFractionData
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 9110 occurrences with subject type sockg:ExperimentalUnit and object type sockg:HarvestFraction.
    examples:
    - value: neo4j://graph.individuals#54138 sockg:hasHarvestFractionData neo4j://graph.individuals#194584
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasHarvestFractionData
    alias: sockg:hasHarvestFractionData
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:HarvestFraction
  sockg:hasBioMassMineralData:
    name: sockg:hasBioMassMineralData
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 6723 occurrences with subject type sockg:ExperimentalUnit and object type sockg:BioMassMineral.
    examples:
    - value: neo4j://graph.individuals#54248 sockg:hasBioMassMineralData neo4j://graph.individuals#41240
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasBioMassMineralData
    alias: sockg:hasBioMassMineralData
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:BioMassMineral
  sockg:hasGasSample:
    name: sockg:hasGasSample
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 106447 occurrences with subject type sockg:ExperimentalUnit and object type
      sockg:GasSample.
    examples:
    - value: neo4j://graph.individuals#52490 sockg:hasGasSample neo4j://graph.individuals#101790
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasGasSample
    alias: sockg:hasGasSample
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:GasSample
  sockg:hasGrazingData:
    name: sockg:hasGrazingData
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 6995 occurrences with subject type sockg:ExperimentalUnit and object type sockg:Grazing.
    examples:
    - value: neo4j://graph.individuals#52278 sockg:hasGrazingData neo4j://graph.individuals#168912
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasGrazingData
    alias: sockg:hasGrazingData
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:Grazing
  sockg:hasTillage:
    name: sockg:hasTillage
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 27137 occurrences with subject type sockg:ExperimentalUnit and object type sockg:Tillage.
    examples:
    - value: neo4j://graph.individuals#52027 sockg:hasTillage neo4j://graph.individuals#332758
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasTillage
    alias: sockg:hasTillage
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:Tillage
  sockg:hasAmendment:
    name: sockg:hasAmendment
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 37796 occurrences with subject type sockg:ExperimentalUnit and object type sockg:Amendment.
    examples:
    - value: neo4j://graph.individuals#52089 sockg:hasAmendment neo4j://graph.individuals#13128
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasAmendment
    alias: sockg:hasAmendment
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:Amendment
  sockg:tracksGrowth:
    name: sockg:tracksGrowth
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 4896 occurrences with subject type sockg:ExperimentalUnit and object type sockg:CropGrowthStage.
    examples:
    - value: neo4j://graph.individuals#52319 sockg:tracksGrowth neo4j://graph.individuals#46787
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:tracksGrowth
    alias: sockg:tracksGrowth
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:CropGrowthStage
  sockg:hasGrazingManagementEvent:
    name: sockg:hasGrazingManagementEvent
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1951 occurrences with subject type sockg:ExperimentalUnit and object type sockg:GrazingManagementEvent.
    examples:
    - value: neo4j://graph.individuals#52278 sockg:hasGrazingManagementEvent neo4j://graph.individuals#171983
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasGrazingManagementEvent
    alias: sockg:hasGrazingManagementEvent
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:GrazingManagementEvent
  sockg:isHarvested:
    name: sockg:isHarvested
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 18356 occurrences with subject type sockg:ExperimentalUnit and object type sockg:Harvest.
    examples:
    - value: neo4j://graph.individuals#55477 sockg:isHarvested neo4j://graph.individuals#188250
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:isHarvested
    alias: sockg:isHarvested
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:Harvest
  sockg:locatedInField:
    name: sockg:locatedInField
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 3809 occurrences with subject type sockg:ExperimentalUnit and object type sockg:Field.
    examples:
    - value: neo4j://graph.individuals#52970 sockg:locatedInField neo4j://graph.individuals#55561
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:locatedInField
    alias: sockg:locatedInField
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:Field
  sockg:hasBioMassEnergyData:
    name: sockg:hasBioMassEnergyData
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 799 occurrences with subject type sockg:ExperimentalUnit and object type sockg:BioMassEnergy.
    examples:
    - value: neo4j://graph.individuals#54245 sockg:hasBioMassEnergyData neo4j://graph.individuals#39330
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasBioMassEnergyData
    alias: sockg:hasBioMassEnergyData
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:BioMassEnergy
  sockg:hasBioMassCarbohydrateData:
    name: sockg:hasBioMassCarbohydrateData
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1367 occurrences with subject type sockg:ExperimentalUnit and object type sockg:BioMassCarbohydrate.
    examples:
    - value: neo4j://graph.individuals#54405 sockg:hasBioMassCarbohydrateData neo4j://graph.individuals#38067
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasBioMassCarbohydrateData
    alias: sockg:hasBioMassCarbohydrateData
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:BioMassCarbohydrate
  sockg:hasResidueManagementEvent:
    name: sockg:hasResidueManagementEvent
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 3308 occurrences with subject type sockg:ExperimentalUnit and object type sockg:ResidueManagementEvent.
    examples:
    - value: neo4j://graph.individuals#53264 sockg:hasResidueManagementEvent neo4j://graph.individuals#228485
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasResidueManagementEvent
    alias: sockg:hasResidueManagementEvent
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    range: sockg:ResidueManagementEvent
  sockg:changeInManagement:
    name: sockg:changeInManagement
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 3809 occurrences with subject type sockg:ExperimentalUnit and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#52721 sockg:changeInManagement nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:changeInManagement
    alias: sockg:changeInManagement
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
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
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    - sockg:GasNutrientLoss
    - sockg:NutrientEfficiency
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
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:ExperimentalUnit
    - sockg:GasNutrientLoss
    - sockg:NutrientEfficiency
    - sockg:WaterQualityArea
    - sockg:WaterQualityConc
    - sockg:WindErosionArea
    - sockg:YieldNutrientUptake
    range: string
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
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:Amendment
    - sockg:Experiment
    - sockg:ExperimentalUnit
    - sockg:GrazingManagementEvent
    range: Any
    any_of:
    - range: double
    - range: string
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
    owner: sockg:ExperimentalUnit
    domain_of:
    - sockg:Amendment
    - sockg:Experiment
    - sockg:ExperimentalUnit
    - sockg:GrazingManagementEvent
    range: Any
    any_of:
    - range: string
    - range: double
class_uri: sockg:ExperimentalUnit

```
</details>