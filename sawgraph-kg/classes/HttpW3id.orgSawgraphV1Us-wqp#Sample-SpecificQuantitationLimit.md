

# Class: HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit




This class occurs 155 times.


URI: [http://w3id.org/sawgraph/v1/us-wqp#Sample-SpecificQuantitationLimit](http://w3id.org/sawgraph/v1/us-wqp#Sample-SpecificQuantitationLimit)






```mermaid
 classDiagram
    class HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit
    click HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit href "../HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit"
      HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit : qudt_hasUnit
        
          
    
    
    HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit --> "0..1" Any : qudt_hasUnit
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit : qudt_numericValue
        
          
    
    
    HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit --> "0..1" QudtNumericUnion : qudt_numericValue
    click QudtNumericUnion href "../QudtNumericUnion"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [qudt_hasUnit](../slots/qudt_hasUnit.md) | 0..1 <br/> [QudtUnit](../classes/QudtUnit.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[QudtContextualUnit](../classes/QudtContextualUnit.md)&nbsp;or&nbsp;<br />[QudtLogarithmicUnit](../classes/QudtLogarithmicUnit.md)&nbsp;or&nbsp;<br />[QudtCurrencyUnit](../classes/QudtCurrencyUnit.md)&nbsp;or&nbsp;<br />[QudtDerivedUnit](../classes/QudtDerivedUnit.md)&nbsp;or&nbsp;<br />[QudtCountingUnit](../classes/QudtCountingUnit.md) | This property relates a factor unit its unit <br/> description: This property relates a factor unit to its unit or a system of units with a unit of measure that is either a) defined by the system, or b) accepted for use by the system and is convertible to a unit of equivalent dimension that is defined by the system. Systems of units may distinguish between base and derived units. Base units are the units which measure the base quantities for the corresponding system of quantities. The base units are used to define units for all other quantities as products of powers of the base units. Such units are called derived units for the system.<br/>title: hasUnit | direct | 310 |
| [qudt_numericValue](../slots/qudt_numericValue.md) | 0..1 <br/> [QudtNumericUnion](../types/QudtNumericUnion.md) |  <br/>  | direct | 155 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration.md) | [coso_hasResultQualifier](../slots/coso_hasResultQualifier.md) | any_of[range] | [HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit](../classes/HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___w3id.org_sawgraph_v1_us-wqp#Sample-SpecificQuantitationLimit
from_schema: okns:sawgraph-kg
rank: 1000
slots:
- qudt_hasUnit
- qudt_numericValue
class_uri: http://w3id.org/sawgraph/v1/us-wqp#Sample-SpecificQuantitationLimit

```
</details>

### Induced

<details>

```yaml
name: http___w3id.org_sawgraph_v1_us-wqp#Sample-SpecificQuantitationLimit
from_schema: okns:sawgraph-kg
rank: 1000
attributes:
  qudt_hasUnit:
    name: qudt_hasUnit
    description: This property relates a factor unit its unit
    title: has unit
    comments:
    - 'description: This property relates a factor unit to its unit or a system of
      units with a unit of measure that is either a) defined by the system, or b)
      accepted for use by the system and is convertible to a unit of equivalent dimension
      that is defined by the system. Systems of units may distinguish between base
      and derived units. Base units are the units which measure the base quantities
      for the corresponding system of quantities. The base units are used to define
      units for all other quantities as products of powers of the base units. Such
      units are called derived units for the system.'
    - 'title: hasUnit'
    from_schema: okns:qudt
    source: http://qudt.org/schema/qudt
    slot_uri: qudt:hasUnit
    alias: qudt_hasUnit
    owner: http___w3id.org_sawgraph_v1_us-wqp#Sample-SpecificQuantitationLimit
    domain_of:
    - coso_DetectQuantityValue
    - coso_NonDetectQuantityValue
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-MethodDetectionLimit
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
    - http___w3id.org_sawgraph_v1_us-wqp#InstrumentDetectionLevel
    - http___w3id.org_sawgraph_v1_us-wqp#LaboratoryReportingLevel
    - http___w3id.org_sawgraph_v1_us-wqp#LowerQuantitationLimit
    - http___w3id.org_sawgraph_v1_us-wqp#LowerReportingLimit
    - http___w3id.org_sawgraph_v1_us-wqp#MethodDetectionLevel
    - http___w3id.org_sawgraph_v1_us-wqp#Sample-SpecificQuantitationLimit
    - me_egad_EGAD-MethodDetectionLimit
    - me_egad_EGAD-ReportingLimit
    range: Any
    any_of:
    - range: qudt_Unit
    - range: uri
    - range: qudt_ContextualUnit
    - range: qudt_LogarithmicUnit
    - range: qudt_CurrencyUnit
    - range: qudt_DerivedUnit
    - range: qudt_CountingUnit
  qudt_numericValue:
    name: qudt_numericValue
    title: numeric value
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:qudt
    source: http://qudt.org/schema/qudt
    slot_uri: qudt:numericValue
    alias: qudt_numericValue
    owner: http___w3id.org_sawgraph_v1_us-wqp#Sample-SpecificQuantitationLimit
    domain_of:
    - coso_DetectQuantityValue
    - coso_NonDetectQuantityValue
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-MethodDetectionLimit
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
    - http___w3id.org_sawgraph_v1_us-wqp#InstrumentDetectionLevel
    - http___w3id.org_sawgraph_v1_us-wqp#LaboratoryReportingLevel
    - http___w3id.org_sawgraph_v1_us-wqp#LowerQuantitationLimit
    - http___w3id.org_sawgraph_v1_us-wqp#LowerReportingLimit
    - http___w3id.org_sawgraph_v1_us-wqp#MethodDetectionLevel
    - http___w3id.org_sawgraph_v1_us-wqp#Sample-SpecificQuantitationLimit
    - me_egad_EGAD-MethodDetectionLimit
    - me_egad_EGAD-ReportingLimit
    range: qudt_NumericUnion
class_uri: http://w3id.org/sawgraph/v1/us-wqp#Sample-SpecificQuantitationLimit

```
</details>