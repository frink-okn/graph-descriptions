

# Slot: value for quantity (qudt_valueQuantity)




This slot occurs 1153526 times.


URI: [qudt:valueQuantity](http://qudt.org/schema/qudt/valueQuantity)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [CosoNonDetectQuantityValue](../classes/CosoNonDetectQuantityValue.md) | A Quantity Value that represents a non-detection of the contaminant |  no  |
| [CosoDetectQuantityValue](../classes/CosoDetectQuantityValue.md) | A Quantity Value that represents a detection of the contaminant |  no  |







## Properties

* Range: [Any](../classes/Any.md)







## LinkML Source

<details>

```yaml
name: qudt_valueQuantity
title: value for quantity
notes:
- No occurrences of this slot in the graph.
from_schema: okns:qudt
source: http://qudt.org/schema/qudt
slot_uri: qudt:valueQuantity
domain_of:
- coso_DetectQuantityValue
- coso_NonDetectQuantityValue
inverse: qudt_quantityValue
range: Any

```
</details>