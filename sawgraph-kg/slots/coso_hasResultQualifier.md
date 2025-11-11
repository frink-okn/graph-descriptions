

# Slot: has result qualifier (coso_hasResultQualifier)


_A relation between measured result and metadata that qualifies the result._






This slot occurs 170567 times.


URI: [coso:hasResultQualifier](http://w3id.org/coso/v1/contaminoso#hasResultQualifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[CosoResultQualifier](../classes/CosoResultQualifier.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#InstrumentDetectionLevel](../classes/HttpW3id.orgSawgraphV1Us-wqp#InstrumentDetectionLevel.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#ResultMeasureQualifier](../classes/HttpW3id.orgSawgraphV1Us-wqp#ResultMeasureQualifier.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit](../classes/HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#LowerReportingLimit](../classes/HttpW3id.orgSawgraphV1Us-wqp#LowerReportingLimit.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#LaboratoryReportingLevel](../classes/HttpW3id.orgSawgraphV1Us-wqp#LaboratoryReportingLevel.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#LowerQuantitationLimit](../classes/HttpW3id.orgSawgraphV1Us-wqp#LowerQuantitationLimit.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#MethodDetectionLevel](../classes/HttpW3id.orgSawgraphV1Us-wqp#MethodDetectionLevel.md)







## LinkML Source

<details>

```yaml
name: coso_hasResultQualifier
description: A relation between measured result and metadata that qualifies the result.
title: has result qualifier
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:hasResultQualifier
alias: coso_hasResultQualifier
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

```
</details>