

# Class: WQP - Single PFAS Concentration (http___w3id.org_sawgraph_v1_us-wqp#Single-PFAS-Concentration)




This class occurs 128674 times.


URI: [http://w3id.org/sawgraph/v1/us-wqp#Single-PFAS-Concentration](http://w3id.org/sawgraph/v1/us-wqp#Single-PFAS-Concentration)






```mermaid
 classDiagram
    class HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration
    click HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration href "../HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration"
      CosoSingleContaminantMeasurement <|-- HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration
        click CosoSingleContaminantMeasurement href "../CosoSingleContaminantMeasurement"
      
      HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration : coso_hasResultQualifier
        
          
    
    
    HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration --> "0..1" Any : coso_hasResultQualifier
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration : qudt_quantityValue
        
          
    
    
    HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration --> "0..1" QudtQuantityValue : qudt_quantityValue
    click QudtQuantityValue href "../QudtQuantityValue"

        
      
```





## Inheritance
* [SosaResult](../classes/SosaResult.md)
    * [CosoSingleContaminantMeasurement](../classes/CosoSingleContaminantMeasurement.md)
        * **HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [coso_hasResultQualifier](../slots/coso_hasResultQualifier.md) | 0..1 <br/> [CosoResultQualifier](../classes/CosoResultQualifier.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#InstrumentDetectionLevel](../classes/HttpW3id.orgSawgraphV1Us-wqp#InstrumentDetectionLevel.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#ResultMeasureQualifier](../classes/HttpW3id.orgSawgraphV1Us-wqp#ResultMeasureQualifier.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit](../classes/HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#LowerReportingLimit](../classes/HttpW3id.orgSawgraphV1Us-wqp#LowerReportingLimit.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#LaboratoryReportingLevel](../classes/HttpW3id.orgSawgraphV1Us-wqp#LaboratoryReportingLevel.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#LowerQuantitationLimit](../classes/HttpW3id.orgSawgraphV1Us-wqp#LowerQuantitationLimit.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#MethodDetectionLevel](../classes/HttpW3id.orgSawgraphV1Us-wqp#MethodDetectionLevel.md) | A relation between measured result and metadata that qualifies the result <br/>  | direct | 170567 |
| [qudt_quantityValue](../slots/qudt_quantityValue.md) | 0..1 <br/> [QudtQuantityValue](../classes/QudtQuantityValue.md) |  <br/>  | direct | 128674 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_hasResult](../slots/coso_hasResult.md) | any_of[range] | [HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) | [coso_hasResult](../slots/coso_hasResult.md) | any_of[range] | [HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_hasResult](../slots/coso_hasResult.md) | any_of[range] | [HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___w3id.org_sawgraph_v1_us-wqp#Single-PFAS-Concentration
title: WQP - Single PFAS Concentration
from_schema: okns:sawgraph-kg
rank: 1000
is_a: coso_SingleContaminantMeasurement
slots:
- coso_hasResultQualifier
- qudt_quantityValue
class_uri: http://w3id.org/sawgraph/v1/us-wqp#Single-PFAS-Concentration

```
</details>

### Induced

<details>

```yaml
name: http___w3id.org_sawgraph_v1_us-wqp#Single-PFAS-Concentration
title: WQP - Single PFAS Concentration
from_schema: okns:sawgraph-kg
rank: 1000
is_a: coso_SingleContaminantMeasurement
attributes:
  coso_hasResultQualifier:
    name: coso_hasResultQualifier
    description: A relation between measured result and metadata that qualifies the
      result.
    title: has result qualifier
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: coso:hasResultQualifier
    alias: coso_hasResultQualifier
    owner: http___w3id.org_sawgraph_v1_us-wqp#Single-PFAS-Concentration
    domain_of:
    - http___w3id.org_sawgraph_v1_us-wqp#Single-PFAS-Concentration
    subproperty_of: coso_resultAnnotation
    union_of:
    - sosa_Result
    - coso_ContaminantMeasurement
    - owl_Thing
    - qudt_Quantifiable
    - qudt_Quantity
    - qudt_Concept
    - stad_Datapoint
    range: Any
    any_of:
    - range: coso_ResultQualifier
    - range: http___w3id.org_sawgraph_v1_us-wqp#InstrumentDetectionLevel
    - range: uri
    - range: http___w3id.org_sawgraph_v1_us-wqp#ResultMeasureQualifier
    - range: http___w3id.org_sawgraph_v1_us-wqp#Sample-SpecificQuantitationLimit
    - range: http___w3id.org_sawgraph_v1_us-wqp#LowerReportingLimit
    - range: owl_Thing
    - range: http___w3id.org_sawgraph_v1_us-wqp#LaboratoryReportingLevel
    - range: http___w3id.org_sawgraph_v1_us-wqp#LowerQuantitationLimit
    - range: http___w3id.org_sawgraph_v1_us-wqp#MethodDetectionLevel
  qudt_quantityValue:
    name: qudt_quantityValue
    title: quantity value
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:qudt
    source: http://qudt.org/schema/qudt
    slot_uri: qudt:quantityValue
    alias: qudt_quantityValue
    owner: http___w3id.org_sawgraph_v1_us-wqp#Single-PFAS-Concentration
    domain_of:
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    - http___w3id.org_sawgraph_v1_us-wqp#Single-PFAS-Concentration
    - me_egad_EGAD-AggregatePFAS-Concentration
    - me_egad_EGAD-SinglePFAS-Concentration
    range: qudt_QuantityValue
class_uri: http://w3id.org/sawgraph/v1/us-wqp#Single-PFAS-Concentration

```
</details>