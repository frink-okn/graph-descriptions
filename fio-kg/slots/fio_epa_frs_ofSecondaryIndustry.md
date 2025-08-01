

# Slot: of Secondary Industry (fio-epa-frs_ofSecondaryIndustry)




This slot occurs 24317 times.


URI: [fio-epa-frs:ofSecondaryIndustry](http://w3id.org/fio/v1/epa-frs#ofSecondaryIndustry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Node510](../classes/Node510.md) |  |  no  |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies somet... |  no  |
| [Node512](../classes/Node512.md) |  |  no  |
| [Node513](../classes/Node513.md) |  |  no  |
| [Node518](../classes/Node518.md) |  |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Node501](../classes/Node501.md) |  |  no  |
| [Node359](../classes/Node359.md) |  |  no  |
| [Node499](../classes/Node499.md) |  |  no  |
| [Node517](../classes/Node517.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md)&nbsp;or&nbsp;<br />[FioIndustry](../classes/FioIndustry.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md)







## LinkML Source

<details>

```yaml
name: fio-epa-frs_ofSecondaryIndustry
title: of Secondary Industry
from_schema: okns:fiokg
exact_mappings:
- http://w3id.org/fio/v1/epa-frs#ofSecondaryIndustry
rank: 1000
slot_uri: fio-epa-frs:ofSecondaryIndustry
alias: fio_epa_frs_ofSecondaryIndustry
domain_of:
- __node359
- __node499
- __node501
- __node510
- __node512
- __node513
- __node517
- __node518
- fio-epa-frs_FRS-Facility
- fio-epa-frs_SupplementalRecord
subproperty_of: fio_ofIndustry
range: Any
any_of:
- range: owl_NamedIndividual
- range: owl_Thing
- range: naics_NAICS-IndustryGroup
- range: fio_Industry
- range: naics_NAICS-IndustryCode
- range: naics_NAICS-IndustrySubsector

```
</details>