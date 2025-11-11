

# Slot: numeric value (qudt_numericValue)




This slot occurs 447627 times.


URI: [qudt:numericValue](http://qudt.org/schema/qudt/numericValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Us-wqp#InstrumentDetectionLevel](../classes/HttpW3id.orgSawgraphV1Us-wqp#InstrumentDetectionLevel.md) |  |  no  |
| [MeEgadEGAD-ReportingLimit](../classes/MeEgadEGAD-ReportingLimit.md) |  |  no  |
| [CosoDetectQuantityValue](../classes/CosoDetectQuantityValue.md) | A Quantity Value that represents a detection of the contaminant |  no  |
| [HttpW3id.orgSawgraphV1Us-wqp#LowerQuantitationLimit](../classes/HttpW3id.orgSawgraphV1Us-wqp#LowerQuantitationLimit.md) |  |  no  |
| [CosoNonDetectQuantityValue](../classes/CosoNonDetectQuantityValue.md) | A Quantity Value that represents a non-detection of the contaminant |  no  |
| [MeEgadEGAD-MethodDetectionLimit](../classes/MeEgadEGAD-MethodDetectionLimit.md) | Areas with land use activities which are potential and/or actual sources of c... |  no  |
| [HttpW3id.orgSawgraphV1Us-wqp#LaboratoryReportingLevel](../classes/HttpW3id.orgSawgraphV1Us-wqp#LaboratoryReportingLevel.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit](../classes/HttpW3id.orgSawgraphV1Us-wqp#Sample-SpecificQuantitationLimit.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit.md) | Areas with land use activities which are potential and/or actual sources of c... |  no  |
| [HttpW3id.orgSawgraphV1Us-wqp#MethodDetectionLevel](../classes/HttpW3id.orgSawgraphV1Us-wqp#MethodDetectionLevel.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Us-wqp#LowerReportingLimit](../classes/HttpW3id.orgSawgraphV1Us-wqp#LowerReportingLimit.md) |  |  no  |







## Properties

* Range: [QudtNumericUnion](../types/QudtNumericUnion.md)







## LinkML Source

<details>

```yaml
name: qudt_numericValue
title: numeric value
notes:
- No occurrences of this slot in the graph.
from_schema: okns:qudt
source: http://qudt.org/schema/qudt
slot_uri: qudt:numericValue
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

```
</details>