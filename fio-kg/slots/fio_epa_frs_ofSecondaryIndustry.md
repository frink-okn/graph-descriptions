

# Slot: of Secondary Industry (fio-epa-frs_ofSecondaryIndustry)




This slot occurs 24317 times.


URI: [fio-epa-frs:ofSecondaryIndustry](http://w3id.org/fio/v1/epa-frs#ofSecondaryIndustry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Fio-epa-frsReportingRecord](../classes/Fio-epa-frsReportingRecord.md) |  |  no  |
| [Fio-epa-frsStateTrackingRecord](../classes/Fio-epa-frsStateTrackingRecord.md) |  |  no  |
| [Fio-epa-frsRegistrationRecord](../classes/Fio-epa-frsRegistrationRecord.md) |  |  no  |
| [Fio-epa-frsPermitRecord](../classes/Fio-epa-frsPermitRecord.md) | A record that tracks a permit or license awarded to the facility |  no  |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies somet... |  no  |
| [Fio-epa-frsEnforcementTrackingRecord](../classes/Fio-epa-frsEnforcementTrackingRecord.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md)&nbsp;or&nbsp;<br />[FioIndustry](../classes/FioIndustry.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)







## LinkML Source

<details>

```yaml
name: fio-epa-frs_ofSecondaryIndustry
title: of Secondary Industry
from_schema: okns:fio-kg
rank: 1000
slot_uri: fio-epa-frs:ofSecondaryIndustry
alias: fio_epa_frs_ofSecondaryIndustry
domain_of:
- fio-epa-frs_EnforcementTrackingRecord
- fio-epa-frs_FRS-Facility
- fio-epa-frs_PermitRecord
- fio-epa-frs_RegistrationRecord
- fio-epa-frs_ReportingRecord
- fio-epa-frs_StateTrackingRecord
- fio-epa-frs_SupplementalRecord
subproperty_of: fio_ofIndustry
range: Any
any_of:
- range: naics_NAICS-IndustryGroup
- range: naics_NAICS-IndustryCode
- range: fio_Industry
- range: naics_NAICS-IndustrySubsector
- range: owl_NamedIndividual
- range: owl_Thing

```
</details>