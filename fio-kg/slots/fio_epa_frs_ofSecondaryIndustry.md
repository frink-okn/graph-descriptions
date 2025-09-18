

# Slot: of Secondary Industry (fio-epa-frs_ofSecondaryIndustry)




This slot occurs 24317 times.


URI: [fio-epa-frs:ofSecondaryIndustry](http://w3id.org/fio/v1/epa-frs#ofSecondaryIndustry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [B51b8d66516b28a1c54f8d745ede947b9](../classes/B51b8d66516b28a1c54f8d745ede947b9.md) |  |  no  |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies somet... |  no  |
| [B671ac9cd6796151f919e5affbe3cc5f9](../classes/B671ac9cd6796151f919e5affbe3cc5f9.md) |  |  no  |
| [B5debef6666ba27aa225105865fd22d6c](../classes/B5debef6666ba27aa225105865fd22d6c.md) |  |  no  |
| [B912c2f2722265f457d11b52388b1def0](../classes/B912c2f2722265f457d11b52388b1def0.md) |  |  no  |
| [Bf0c649c8d760a3559d3d5e5b1f68a59f](../classes/Bf0c649c8d760a3559d3d5e5b1f68a59f.md) |  |  no  |
| [B43f2153f8fa51cc860da104aa4b996c7](../classes/B43f2153f8fa51cc860da104aa4b996c7.md) |  |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Bdbdbfbd4ef20ffc37226553d96831226](../classes/Bdbdbfbd4ef20ffc37226553d96831226.md) |  |  no  |
| [Ba0ffbf1a7a548fac1e61d3eceada03dd](../classes/Ba0ffbf1a7a548fac1e61d3eceada03dd.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md)&nbsp;or&nbsp;<br />[FioIndustry](../classes/FioIndustry.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)







## LinkML Source

<details>

```yaml
name: fio-epa-frs_ofSecondaryIndustry
title: of Secondary Industry
from_schema: okns:fio-kg
exact_mappings:
- http://w3id.org/fio/v1/epa-frs#ofSecondaryIndustry
rank: 1000
slot_uri: fio-epa-frs:ofSecondaryIndustry
alias: fio_epa_frs_ofSecondaryIndustry
domain_of:
- __B43f2153f8fa51cc860da104aa4b996c7
- __B51b8d66516b28a1c54f8d745ede947b9
- __B5debef6666ba27aa225105865fd22d6c
- __B671ac9cd6796151f919e5affbe3cc5f9
- __B912c2f2722265f457d11b52388b1def0
- __Ba0ffbf1a7a548fac1e61d3eceada03dd
- __Bdbdbfbd4ef20ffc37226553d96831226
- __Bf0c649c8d760a3559d3d5e5b1f68a59f
- fio-epa-frs_FRS-Facility
- fio-epa-frs_SupplementalRecord
subproperty_of: fio_ofIndustry
range: Any
any_of:
- range: naics_NAICS-IndustryGroup
- range: owl_Thing
- range: naics_NAICS-IndustrySubsector
- range: naics_NAICS-IndustryCode
- range: fio_Industry
- range: owl_NamedIndividual

```
</details>