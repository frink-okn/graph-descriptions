

# Slot: description (sdos_description)


_A description of the item._






This slot occurs 12679976 times.


URI: [sdos:description](https://schema.org/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Kwgos#S2Cell](../classes/Kwgos#S2Cell.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosTextObject](../classes/SdosTextObject.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md)







## LinkML Source

<details>

```yaml
name: sdos_description
description: A description of the item.
title: description
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
exact_mappings:
- http://purl.org/dc/terms/description
domain: sdos_Thing
slot_uri: sdos:description
domain_of:
- kwgos_#S2Cell
range: Any
any_of:
- range: sdos_TextObject
- range: sdos_Text

```
</details>