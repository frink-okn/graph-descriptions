

# Slot: address (sdos_address)


_Physical address of the item._






This slot occurs 412720 times.


URI: [sdos:address](https://schema.org/address)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md)&nbsp;or&nbsp;<br />[SdosPostalAddress](../classes/SdosPostalAddress.md)





## Comments

* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: sdos_address
description: Physical address of the item.
title: address
comments:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
slot_uri: sdos:address
domain_of:
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
union_of:
- sdos_Organization
- sdos_GeoShape
- sdos_Person
- sdos_Place
- sdos_GeoCoordinates
range: Any
any_of:
- range: sdos_Text
- range: sdos_PostalAddress

```
</details>