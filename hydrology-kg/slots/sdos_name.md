

# Slot: name (sdos_name)


_The name of the item._






This slot occurs 224283 times.


URI: [sdos:name](https://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HyfHYEstuary](../classes/HyfHYEstuary.md) |  |  no  |
| [HyfHYCanal](../classes/HyfHYCanal.md) |  |  no  |
| [HyfHYWaterBody](../classes/HyfHYWaterBody.md) |  |  no  |
| [HyfHYLagoon](../classes/HyfHYLagoon.md) |  |  no  |
| [HyfHYRiver](../classes/HyfHYRiver.md) |  |  no  |
| [HyfHYImpoundment](../classes/HyfHYImpoundment.md) |  |  no  |
| [HyfHYLake](../classes/HyfHYLake.md) |  |  no  |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |  |  no  |







## Properties

* Range: [SdosText](../classes/SdosText.md)





## Comments

* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: sdos_name
description: The name of the item.
title: name
comments:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
exact_mappings:
- http://purl.org/dc/terms/title
domain: sdos_Thing
slot_uri: sdos:name
domain_of:
- hyf__HY_ElementaryFlowPath
- hyf__HY_Lake
- hyf__HY_WaterBody
subproperty_of: rdfs_label
range: sdos_Text

```
</details>