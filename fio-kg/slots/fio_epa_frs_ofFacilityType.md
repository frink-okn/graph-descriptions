

# Slot: of facility type (fio-epa-frs_ofFacilityType)




This slot occurs 1336346 times.


URI: [fio-epa-frs:ofFacilityType](http://w3id.org/fio/v1/epa-frs#ofFacilityType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[Fio-epa-frsFacilityType](../classes/Fio-epa-frsFacilityType.md)







## LinkML Source

<details>

```yaml
name: fio-epa-frs_ofFacilityType
title: of facility type
from_schema: okns:fiokg
exact_mappings:
- http://w3id.org/fio/v1/epa-frs#ofFacilityType
rank: 1000
slot_uri: fio-epa-frs:ofFacilityType
alias: fio_epa_frs_ofFacilityType
domain_of:
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
union_of:
- owl_Thing
- __node359
- fio-epa-frs_FRS-Facility
- fio_Facility
range: Any
any_of:
- range: owl_Thing
- range: fio-epa-frs_FacilityType

```
</details>