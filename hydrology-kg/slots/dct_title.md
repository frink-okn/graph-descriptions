

# Slot: Title (dct_title)


_A name given to the resource._






This slot occurs 224283 times.


URI: [dct:title](http://purl.org/dc/terms/title)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [VaemGraphMetaData](../classes/VaemGraphMetaData.md) | "vaem:GraphMetaData" defines basic metadata for the registration and publishi... |  no  |
| [HyfHYEstuary](../classes/HyfHYEstuary.md) |  |  no  |
| [HyfHYCanal](../classes/HyfHYCanal.md) |  |  no  |
| [HyfHYWaterBody](../classes/HyfHYWaterBody.md) |  |  no  |
| [HyfHYLagoon](../classes/HyfHYLagoon.md) |  |  no  |
| [HyfHYRiver](../classes/HyfHYRiver.md) |  |  no  |
| [HyfHYImpoundment](../classes/HyfHYImpoundment.md) |  |  no  |
| [HyfHYLake](../classes/HyfHYLake.md) |  |  no  |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: dct_title
description: A name given to the resource.
title: Title
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:title
domain_of:
- vaem_GraphMetaData
- hyf__HY_ElementaryFlowPath
- hyf__HY_Lake
- hyf__HY_WaterBody
subproperty_of: dc_title
range: Any
any_of:
- range: rdfs_Literal
- range: string

```
</details>