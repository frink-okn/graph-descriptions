

# Slot: license (sdos_license)


_A license document that applies to this content, typically indicated by URL._






This slot occurs 5018025 times.


URI: [sdos:license](https://schema.org/license)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosURL](../classes/SdosURL.md)&nbsp;or&nbsp;<br />[SdosCreativeWork](../classes/SdosCreativeWork.md)







## LinkML Source

<details>

```yaml
name: sdos_license
description: A license document that applies to this content, typically indicated
  by URL.
title: license
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
domain: sdos_CreativeWork
slot_uri: sdos:license
domain_of:
- securechain_SoftwareVersion
range: Any
any_of:
- range: sdos_URL
- range: sdos_CreativeWork

```
</details>