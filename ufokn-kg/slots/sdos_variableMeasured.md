

# Slot: variableMeasured (sdos_variableMeasured)


_The variableMeasured property can indicate (repeated as necessary) the  variables that are measured in some dataset, either described as text or as pairs of identifier and description using PropertyValue, or more explicitly as a [[StatisticalVariable]]._






This slot occurs 5927018 times.


URI: [sdos:variableMeasured](https://schema.org/variableMeasured)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosStatisticalVariable](../classes/SdosStatisticalVariable.md)&nbsp;or&nbsp;<br />[SdosPropertyValue](../classes/SdosPropertyValue.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md)&nbsp;or&nbsp;<br />[SdosProperty](../classes/SdosProperty.md)







## LinkML Source

<details>

```yaml
name: sdos_variableMeasured
description: The variableMeasured property can indicate (repeated as necessary) the  variables
  that are measured in some dataset, either described as text or as pairs of identifier
  and description using PropertyValue, or more explicitly as a [[StatisticalVariable]].
title: variableMeasured
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
source: https://github.com/schemaorg/schemaorg/issues/1083
slot_uri: sdos:variableMeasured
union_of:
- sdos_Observation
- sdos_Dataset
range: Any
any_of:
- range: sdos_StatisticalVariable
- range: sdos_PropertyValue
- range: sdos_Text
- range: sdos_Property

```
</details>