

# Slot: unitCode (sdos_unitCode)


_The unit of measurement given using the UN/CEFACT Common Code (3 characters) or a URL. Other codes than the UN/CEFACT Common Code may be used with a prefix followed by a colon._






This slot occurs 2322992 times.


URI: [sdos:unitCode](https://schema.org/unitCode)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosURL](../classes/SdosURL.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md)







## LinkML Source

<details>

```yaml
name: sdos_unitCode
description: The unit of measurement given using the UN/CEFACT Common Code (3 characters)
  or a URL. Other codes than the UN/CEFACT Common Code may be used with a prefix followed
  by a colon.
title: unitCode
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
contributors:
- https://schema.org/docs/collab/GoodRelationsTerms
slot_uri: sdos:unitCode
union_of:
- sdos_TypeAndQuantityNode
- sdos_QuantitativeValue
- sdos_PropertyValue
- sdos_UnitPriceSpecification
range: Any
any_of:
- range: sdos_URL
- range: sdos_Text

```
</details>