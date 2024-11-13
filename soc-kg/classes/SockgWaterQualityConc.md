

# Class: TODO -- what's a good name for what this class (type) describes? (sockg_WaterQualityConc)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:WaterQualityConc](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/WaterQualityConc)






```mermaid
 classDiagram
    class SockgWaterQualityConc
    click SockgWaterQualityConc href "../SockgWaterQualityConc"
      SockgWaterQualityConc : sockg_crop
        
          
    
    
    SockgWaterQualityConc --> "0..1" Any : sockg_crop
    click Any href "../Any"

        
      SockgWaterQualityConc : sockg_date
        
          
    
    
    SockgWaterQualityConc --> "0..1" Any : sockg_date
    click Any href "../Any"

        
      SockgWaterQualityConc : sockg_electricalConductivity_ms_cm
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_electricalConductivity_ms_cm
    click Double href "../Double"

        
      SockgWaterQualityConc : sockg_electricalConductivityStd_ms_cm
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_electricalConductivityStd_ms_cm
    click Double href "../Double"

        
      SockgWaterQualityConc : sockg_erosionMethod
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_erosionMethod
    click Double href "../Double"

        
      SockgWaterQualityConc : sockg_erosionSediment_kg
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_erosionSediment_kg
    click Double href "../Double"

        
      SockgWaterQualityConc : sockg_erosionSedimentStd_kg
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_erosionSedimentStd_kg
    click Double href "../Double"

        
      SockgWaterQualityConc : sockg_erosionTotalSolids_kg
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_erosionTotalSolids_kg
    click Double href "../Double"

        
      SockgWaterQualityConc : sockg_erosionTotalSolidsStd_kg
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_erosionTotalSolidsStd_kg
    click Double href "../Double"

        
      SockgWaterQualityConc : sockg_erosionTotalSuspendedSolids_kg
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_erosionTotalSuspendedSolids_kg
    click Double href "../Double"

        
      SockgWaterQualityConc : sockg_erosionTotalSuspendedSolidsStd_kg
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_erosionTotalSuspendedSolidsStd_kg
    click Double href "../Double"

        
      SockgWaterQualityConc : sockg_expUnit_UID
        
          
    
    
    SockgWaterQualityConc --> "0..1" String : sockg_expUnit_UID
    click String href "../String"

        
      SockgWaterQualityConc : sockg_expUnitId
        
          
    
    
    SockgWaterQualityConc --> "0..1" String : sockg_expUnitId
    click String href "../String"

        
      SockgWaterQualityConc : sockg_fieldId
        
          
    
    
    SockgWaterQualityConc --> "0..1" String : sockg_fieldId
    click String href "../String"

        
      SockgWaterQualityConc : sockg_growthStage
        
          
    
    
    SockgWaterQualityConc --> "0..1" Any : sockg_growthStage
    click Any href "../Any"

        
      SockgWaterQualityConc : sockg_hasWaterQualityConcData
        
          
    
    
    SockgWaterQualityConc --> "0..1" SockgExperimentalUnit : sockg_hasWaterQualityConcData
    click SockgExperimentalUnit href "../SockgExperimentalUnit"

        
      SockgWaterQualityConc : sockg_measWaterQualityConc_UID
        
          
    
    
    SockgWaterQualityConc --> "0..1" String : sockg_measWaterQualityConc_UID
    click String href "../String"

        
      SockgWaterQualityConc : sockg_modelIfSimulated
        
          
    
    
    SockgWaterQualityConc --> "0..1" Any : sockg_modelIfSimulated
    click Any href "../Any"

        
      SockgWaterQualityConc : sockg_ph
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_ph
    click Double href "../Double"

        
      SockgWaterQualityConc : sockg_phStd
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_phStd
    click Double href "../Double"

        
      SockgWaterQualityConc : sockg_samplingDepth_cm
        
          
    
    
    SockgWaterQualityConc --> "0..1" Integer : sockg_samplingDepth_cm
    click Integer href "../Integer"

        
      SockgWaterQualityConc : sockg_samplingStartStopInterval
        
          
    
    
    SockgWaterQualityConc --> "0..1" Any : sockg_samplingStartStopInterval
    click Any href "../Any"

        
      SockgWaterQualityConc : sockg_surfaceOrLeaching
        
          
    
    
    SockgWaterQualityConc --> "0..1" String : sockg_surfaceOrLeaching
    click String href "../String"

        
      SockgWaterQualityConc : sockg_time
        
          
    
    
    SockgWaterQualityConc --> "0..1" Any : sockg_time
    click Any href "../Any"

        
      SockgWaterQualityConc : sockg_treatmentId
        
          
    
    
    SockgWaterQualityConc --> "0..1" String : sockg_treatmentId
    click String href "../String"

        
      SockgWaterQualityConc : sockg_water_mm
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_water_mm
    click Double href "../Double"

        
      SockgWaterQualityConc : sockg_waterQualityConcDataAt
        
          
    
    
    SockgWaterQualityConc --> "0..1" SockgField : sockg_waterQualityConcDataAt
    click SockgField href "../SockgField"

        
      SockgWaterQualityConc : sockg_waterQualityConcTreatment
        
          
    
    
    SockgWaterQualityConc --> "0..1" SockgTreatment : sockg_waterQualityConcTreatment
    click SockgTreatment href "../SockgTreatment"

        
      SockgWaterQualityConc : sockg_waterStd_mm
        
          
    
    
    SockgWaterQualityConc --> "0..1" Double : sockg_waterStd_mm
    click Double href "../Double"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg_waterQualityConcTreatment](../slots/sockg_waterQualityConcTreatment.md) | 0..1 <br/> [SockgTreatment](../classes/SockgTreatment.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_hasWaterQualityConcData](../slots/sockg_hasWaterQualityConcData.md) | 0..1 <br/> [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_waterQualityConcDataAt](../slots/sockg_waterQualityConcDataAt.md) | 0..1 <br/> [SockgField](../classes/SockgField.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_samplingStartStopInterval](../slots/sockg_samplingStartStopInterval.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_erosionTotalSuspendedSolidsStd_kg](../slots/sockg_erosionTotalSuspendedSolidsStd_kg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_erosionSedimentStd_kg](../slots/sockg_erosionSedimentStd_kg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_measWaterQualityConc_UID](../slots/sockg_measWaterQualityConc_UID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_erosionSediment_kg](../slots/sockg_erosionSediment_kg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_treatmentId](../slots/sockg_treatmentId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_ph](../slots/sockg_ph.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_waterStd_mm](../slots/sockg_waterStd_mm.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_surfaceOrLeaching](../slots/sockg_surfaceOrLeaching.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_phStd](../slots/sockg_phStd.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_date](../slots/sockg_date.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_expUnitId](../slots/sockg_expUnitId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_electricalConductivityStd_ms_cm](../slots/sockg_electricalConductivityStd_ms_cm.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_electricalConductivity_ms_cm](../slots/sockg_electricalConductivity_ms_cm.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_growthStage](../slots/sockg_growthStage.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_water_mm](../slots/sockg_water_mm.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_samplingDepth_cm](../slots/sockg_samplingDepth_cm.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_erosionTotalSolids_kg](../slots/sockg_erosionTotalSolids_kg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_erosionTotalSolidsStd_kg](../slots/sockg_erosionTotalSolidsStd_kg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_expUnit_UID](../slots/sockg_expUnit_UID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_erosionMethod](../slots/sockg_erosionMethod.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_fieldId](../slots/sockg_fieldId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_time](../slots/sockg_time.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_modelIfSimulated](../slots/sockg_modelIfSimulated.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_erosionTotalSuspendedSolids_kg](../slots/sockg_erosionTotalSuspendedSolids_kg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg_crop](../slots/sockg_crop.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |










## Examples

| Value |
| --- |
| neo4j://graph.individuals#361335 |

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
| self | sockg:WaterQualityConc |
| native | soc-kg/main/:SockgWaterQualityConc |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg_WaterQualityConc
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 1479 instances of this class.
examples:
- value: neo4j://graph.individuals#361335
from_schema: soc-kg/main
slots:
- sockg_waterQualityConcTreatment
- sockg_hasWaterQualityConcData
- sockg_waterQualityConcDataAt
- sockg_samplingStartStopInterval
- sockg_erosionTotalSuspendedSolidsStd_kg
- sockg_erosionSedimentStd_kg
- sockg_measWaterQualityConc_UID
- sockg_erosionSediment_kg
- sockg_treatmentId
- sockg_ph
- sockg_waterStd_mm
- sockg_surfaceOrLeaching
- sockg_phStd
- sockg_date
- sockg_expUnitId
- sockg_electricalConductivityStd_ms_cm
- sockg_electricalConductivity_ms_cm
- sockg_growthStage
- sockg_water_mm
- sockg_samplingDepth_cm
- sockg_erosionTotalSolids_kg
- sockg_erosionTotalSolidsStd_kg
- sockg_expUnit_UID
- sockg_erosionMethod
- sockg_fieldId
- sockg_time
- sockg_modelIfSimulated
- sockg_erosionTotalSuspendedSolids_kg
- sockg_crop
class_uri: sockg:WaterQualityConc

```
</details>

### Induced

<details>
```yaml
name: sockg_WaterQualityConc
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 1479 instances of this class.
examples:
- value: neo4j://graph.individuals#361335
from_schema: soc-kg/main
attributes:
  sockg_waterQualityConcTreatment:
    name: sockg_waterQualityConcTreatment
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type sockg:Treatment.
    examples:
    - value: neo4j://graph.individuals#361059 sockg:waterQualityConcTreatment neo4j://graph.individuals#359696
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:waterQualityConcTreatment
    alias: sockg_waterQualityConcTreatment
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityConc
    range: sockg_Treatment
  sockg_hasWaterQualityConcData:
    name: sockg_hasWaterQualityConcData
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type sockg:ExperimentalUnit.
    examples:
    - value: neo4j://graph.individuals#360883 sockg:hasWaterQualityConcData neo4j://graph.individuals#54882
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasWaterQualityConcData
    alias: sockg_hasWaterQualityConcData
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityConc
    range: sockg_ExperimentalUnit
  sockg_waterQualityConcDataAt:
    name: sockg_waterQualityConcDataAt
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type sockg:Field.
    examples:
    - value: neo4j://graph.individuals#361944 sockg:waterQualityConcDataAt neo4j://graph.individuals#55596
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:waterQualityConcDataAt
    alias: sockg_waterQualityConcDataAt
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityConc
    range: sockg_Field
  sockg_samplingStartStopInterval:
    name: sockg_samplingStartStopInterval
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
    alias: sockg_samplingStartStopInterval
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_GasNutrientLoss
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    range: Any
    any_of:
    - range: double
    - range: string
  sockg_erosionTotalSuspendedSolidsStd_kg:
    name: sockg_erosionTotalSuspendedSolidsStd_kg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#360957 sockg:erosionTotalSuspendedSolidsStd_kg
        nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:erosionTotalSuspendedSolidsStd_kg
    alias: sockg_erosionTotalSuspendedSolidsStd_kg
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityConc
    range: double
  sockg_erosionSedimentStd_kg:
    name: sockg_erosionSedimentStd_kg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#361291 sockg:erosionSedimentStd_kg nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:erosionSedimentStd_kg
    alias: sockg_erosionSedimentStd_kg
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityConc
    range: double
  sockg_measWaterQualityConc_UID:
    name: sockg_measWaterQualityConc_UID
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
    examples:
    - value: neo4j://graph.individuals#360947 sockg:measWaterQualityConc_UID AgCros_IAAMKELL_116_2005-04-16
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:measWaterQualityConc_UID
    alias: sockg_measWaterQualityConc_UID
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityConc
    range: string
  sockg_erosionSediment_kg:
    name: sockg_erosionSediment_kg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#361394 sockg:erosionSediment_kg nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:erosionSediment_kg
    alias: sockg_erosionSediment_kg
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityConc
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
    owner: sockg_WaterQualityConc
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
  sockg_ph:
    name: sockg_ph
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 53833 occurrences with subject type sockg:SoilChemicalSample and object type
      xsd:double.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    - 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#272323 sockg:ph nan
    - value: neo4j://graph.individuals#360143 sockg:ph nan
    - value: neo4j://graph.individuals#360790 sockg:ph nan
    - value: neo4j://graph.individuals#509304 sockg:ph nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:ph
    alias: sockg_ph
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_SoilChemicalSample
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    range: double
  sockg_waterStd_mm:
    name: sockg_waterStd_mm
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#361263 sockg:waterStd_mm nan
    - value: neo4j://graph.individuals#359881 sockg:waterStd_mm nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:waterStd_mm
    alias: sockg_waterStd_mm
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    range: double
  sockg_surfaceOrLeaching:
    name: sockg_surfaceOrLeaching
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type string.
    examples:
    - value: neo4j://graph.individuals#361259 sockg:surfaceOrLeaching Leaching
    - value: neo4j://graph.individuals#360315 sockg:surfaceOrLeaching Leaching
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:surfaceOrLeaching
    alias: sockg_surfaceOrLeaching
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    range: string
  sockg_phStd:
    name: sockg_phStd
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
    - 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#360695 sockg:phStd nan
    - value: neo4j://graph.individuals#359965 sockg:phStd nan
    - value: neo4j://graph.individuals#509304 sockg:phStd nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:phStd
    alias: sockg_phStd
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    range: double
  sockg_date:
    name: sockg_date
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
    alias: sockg_date
    owner: sockg_WaterQualityConc
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
  sockg_expUnitId:
    name: sockg_expUnitId
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
    alias: sockg_expUnitId
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_ExperimentalUnit
    - sockg_GasNutrientLoss
    - sockg_NutrientEfficiency
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    - sockg_YieldNutrientUptake
    range: string
  sockg_electricalConductivityStd_ms_cm:
    name: sockg_electricalConductivityStd_ms_cm
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
    - 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#360855 sockg:electricalConductivityStd_ms_cm
        nan
    - value: neo4j://graph.individuals#360494 sockg:electricalConductivityStd_ms_cm
        nan
    - value: neo4j://graph.individuals#509304 sockg:electricalConductivityStd_ms_cm
        nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:electricalConductivityStd_ms_cm
    alias: sockg_electricalConductivityStd_ms_cm
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    range: double
  sockg_electricalConductivity_ms_cm:
    name: sockg_electricalConductivity_ms_cm
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    - 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#361630 sockg:electricalConductivity_ms_cm nan
    - value: neo4j://graph.individuals#509308 sockg:electricalConductivity_ms_cm nan
    - value: neo4j://graph.individuals#359870 sockg:electricalConductivity_ms_cm nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:electricalConductivity_ms_cm
    alias: sockg_electricalConductivity_ms_cm
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    range: double
  sockg_growthStage:
    name: sockg_growthStage
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
    alias: sockg_growthStage
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_BioMassCarbohydrate
    - sockg_BioMassEnergy
    - sockg_BioMassMineral
    - sockg_CropGrowthStage
    - sockg_GasNutrientLoss
    - sockg_Grazing
    - sockg_Harvest
    - sockg_HarvestFraction
    - sockg_NutrientEfficiency
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    - sockg_YieldNutrientUptake
    range: Any
    any_of:
    - range: string
    - range: double
  sockg_water_mm:
    name: sockg_water_mm
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#361456 sockg:water_mm 126.36006
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:water_mm
    alias: sockg_water_mm
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityConc
    range: double
  sockg_samplingDepth_cm:
    name: sockg_samplingDepth_cm
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:long.
    examples:
    - value: neo4j://graph.individuals#361456 sockg:samplingDepth_cm 110
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:samplingDepth_cm
    alias: sockg_samplingDepth_cm
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityConc
    range: integer
  sockg_erosionTotalSolids_kg:
    name: sockg_erosionTotalSolids_kg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#361894 sockg:erosionTotalSolids_kg nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:erosionTotalSolids_kg
    alias: sockg_erosionTotalSolids_kg
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityConc
    range: double
  sockg_erosionTotalSolidsStd_kg:
    name: sockg_erosionTotalSolidsStd_kg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#361455 sockg:erosionTotalSolidsStd_kg nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:erosionTotalSolidsStd_kg
    alias: sockg_erosionTotalSolidsStd_kg
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityConc
    range: double
  sockg_expUnit_UID:
    name: sockg_expUnit_UID
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
    alias: sockg_expUnit_UID
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_ExperimentalUnit
    - sockg_GasNutrientLoss
    - sockg_NutrientEfficiency
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    - sockg_YieldNutrientUptake
    range: string
  sockg_erosionMethod:
    name: sockg_erosionMethod
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
    - 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#361342 sockg:erosionMethod nan
    - value: neo4j://graph.individuals#360282 sockg:erosionMethod nan
    - value: neo4j://graph.individuals#509302 sockg:erosionMethod nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:erosionMethod
    alias: sockg_erosionMethod
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    range: double
  sockg_fieldId:
    name: sockg_fieldId
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
    alias: sockg_fieldId
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_Field
    - sockg_GasNutrientLoss
    - sockg_NutrientEfficiency
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    - sockg_YieldNutrientUptake
    range: string
  sockg_time:
    name: sockg_time
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
    alias: sockg_time
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_GasNutrientLoss
    - sockg_GasSample
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    range: Any
    any_of:
    - range: double
    - range: string
  sockg_modelIfSimulated:
    name: sockg_modelIfSimulated
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
    alias: sockg_modelIfSimulated
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_GasNutrientLoss
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    - sockg_YieldNutrientUptake
    range: Any
    any_of:
    - range: double
    - range: string
  sockg_erosionTotalSuspendedSolids_kg:
    name: sockg_erosionTotalSuspendedSolids_kg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#361956 sockg:erosionTotalSuspendedSolids_kg
        nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:erosionTotalSuspendedSolids_kg
    alias: sockg_erosionTotalSuspendedSolids_kg
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_WaterQualityConc
    range: double
  sockg_crop:
    name: sockg_crop
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
    alias: sockg_crop
    owner: sockg_WaterQualityConc
    domain_of:
    - sockg_BioMassCarbohydrate
    - sockg_BioMassEnergy
    - sockg_BioMassMineral
    - sockg_GasNutrientLoss
    - sockg_GasSample
    - sockg_NutrientEfficiency
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WindErosionArea
    - sockg_YieldNutrientUptake
    range: Any
    any_of:
    - range: string
    - range: double
class_uri: sockg:WaterQualityConc

```
</details>