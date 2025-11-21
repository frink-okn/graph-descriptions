

# Slot: address (sdos_address)


_Physical address of the item._






This slot occurs 693695 times.


URI: [sdos:address](https://schema.org/address)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosPostalAddress](../classes/SdosPostalAddress.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md)







## LinkML Source

<details>

```yaml
name: sdos_address
description: Physical address of the item.
title: address
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
slot_uri: sdos:address
domain_of:
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
union_of:
- sdos_Place
- sdos_Person
- sdos_Organization
- sdos_GeoShape
- sdos_GeoCoordinates
range: Any
any_of:
- range: sdos_PostalAddress
- range: sdos_Text

```
</details>