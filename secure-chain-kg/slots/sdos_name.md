

# Slot: name (sdos_name)


_The name of the item._






This slot occurs 906771 times.


URI: [sdos:name](https://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainHardware](../classes/SecurechainHardware.md) |  |  no  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) |  |  no  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |  no  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |  |  no  |
| [SecurechainLicense](../classes/SecurechainLicense.md) |  |  no  |







## Properties

* Range: [SdosText](../classes/SdosText.md)







## LinkML Source

<details>

```yaml
name: sdos_name
description: The name of the item.
title: name
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
exact_mappings:
- http://purl.org/dc/terms/title
domain: sdos_Thing
slot_uri: sdos:name
domain_of:
- securechain_Hardware
- securechain_License
- securechain_Software
subproperty_of: rdfs_label
range: sdos_Text

```
</details>