

# Slot: has  record (fio-epa-frs_hasRecord)




This slot occurs 1475331 times.


URI: [fio-epa-frs:hasRecord](http://w3id.org/fio/v1/epa-frs#hasRecord)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Node515](../classes/Node515.md) |  |  no  |
| [Node510](../classes/Node510.md) |  |  no  |
| [Node502](../classes/Node502.md) |  |  no  |
| [Node523](../classes/Node523.md) |  |  no  |
| [Node521](../classes/Node521.md) |  |  no  |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies somet... |  no  |
| [Node513](../classes/Node513.md) |  |  no  |
| [Node518](../classes/Node518.md) |  |  no  |
| [Fio-epa-frsRecord](../classes/Fio-epa-frsRecord.md) |  |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Node501](../classes/Node501.md) |  |  no  |
| [Node499](../classes/Node499.md) |  |  no  |
| [Node517](../classes/Node517.md) |  |  no  |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Node502](../classes/Node502.md)&nbsp;or&nbsp;<br />[Node519](../classes/Node519.md)&nbsp;or&nbsp;<br />[Node515](../classes/Node515.md)&nbsp;or&nbsp;<br />[Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md)&nbsp;or&nbsp;<br />[Node517](../classes/Node517.md)&nbsp;or&nbsp;<br />[Node501](../classes/Node501.md)&nbsp;or&nbsp;<br />[Node523](../classes/Node523.md)&nbsp;or&nbsp;<br />[Node521](../classes/Node521.md)&nbsp;or&nbsp;<br />[Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md)&nbsp;or&nbsp;<br />[Node518](../classes/Node518.md)&nbsp;or&nbsp;<br />[Node510](../classes/Node510.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[Node512](../classes/Node512.md)&nbsp;or&nbsp;<br />[Node513](../classes/Node513.md)&nbsp;or&nbsp;<br />[Node359](../classes/Node359.md)&nbsp;or&nbsp;<br />[Node507](../classes/Node507.md)&nbsp;or&nbsp;<br />[Node506](../classes/Node506.md)&nbsp;or&nbsp;<br />[Node508](../classes/Node508.md)&nbsp;or&nbsp;<br />[Node499](../classes/Node499.md)&nbsp;or&nbsp;<br />[Fio-epa-frsRecord](../classes/Fio-epa-frsRecord.md)







## LinkML Source

<details>

```yaml
name: fio-epa-frs_hasRecord
title: has  record
from_schema: okns:fiokg
exact_mappings:
- http://w3id.org/fio/v1/epa-frs#hasRecord
rank: 1000
slot_uri: fio-epa-frs:hasRecord
alias: fio_epa_frs_hasRecord
domain_of:
- __node499
- __node501
- __node502
- __node510
- __node513
- __node515
- __node517
- __node518
- __node521
- __node523
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
- fio-epa-frs_Record
- fio-epa-frs_SupplementalRecord
union_of:
- owl_Thing
- __node359
- fio-epa-frs_FRS-Facility
- fio_Facility
range: Any
any_of:
- range: __node502
- range: __node519
- range: __node515
- range: fio-epa-frs_FRS-Facility
- range: __node517
- range: __node501
- range: __node523
- range: __node521
- range: fio-epa-frs_SupplementalRecord
- range: __node518
- range: __node510
- range: owl_Thing
- range: __node512
- range: __node513
- range: __node359
- range: __node507
- range: __node506
- range: __node508
- range: __node499
- range: fio-epa-frs_Record

```
</details>