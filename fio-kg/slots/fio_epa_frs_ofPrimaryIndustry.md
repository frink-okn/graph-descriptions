

# Slot: of Primary Industry (fio-epa-frs_ofPrimaryIndustry)




This slot occurs 270322 times.


URI: [fio-epa-frs:ofPrimaryIndustry](http://w3id.org/fio/v1/epa-frs#ofPrimaryIndustry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies somet... |  no  |
| [Fio-epa-frsRegistrationRecord](../classes/Fio-epa-frsRegistrationRecord.md) |  |  no  |
| [Fio-epa-frsSiteRecord](../classes/Fio-epa-frsSiteRecord.md) | A record that monitors a site, beyond specific ownership of one organization ... |  no  |
| [Fio-epa-frsReportingRecord](../classes/Fio-epa-frsReportingRecord.md) |  |  no  |
| [Fio-epa-frsRecord](../classes/Fio-epa-frsRecord.md) |  |  no  |
| [Fio-epa-frsEnforcementActivity](../classes/Fio-epa-frsEnforcementActivity.md) | A record that tracks a specific legal, corrective or assistance action taken ... |  no  |
| [Fio-epa-frsEnforcementTrackingRecord](../classes/Fio-epa-frsEnforcementTrackingRecord.md) |  |  no  |
| [Fio-epa-frsStateTrackingRecord](../classes/Fio-epa-frsStateTrackingRecord.md) |  |  no  |
| [Fio-epa-frsComplianceRecord](../classes/Fio-epa-frsComplianceRecord.md) |  |  no  |
| [Fio-epa-frsPermitRecord](../classes/Fio-epa-frsPermitRecord.md) | A record that tracks a permit or license awarded to the facility |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[FioIndustry](../classes/FioIndustry.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md)







## LinkML Source

<details>

```yaml
name: fio-epa-frs_ofPrimaryIndustry
title: of Primary Industry
from_schema: okns:fio-kg
rank: 1000
slot_uri: fio-epa-frs:ofPrimaryIndustry
alias: fio_epa_frs_ofPrimaryIndustry
domain_of:
- fio-epa-frs_ComplianceRecord
- fio-epa-frs_EnforcementActivity
- fio-epa-frs_EnforcementTrackingRecord
- fio-epa-frs_FRS-Facility
- fio-epa-frs_PermitRecord
- fio-epa-frs_Record
- fio-epa-frs_RegistrationRecord
- fio-epa-frs_ReportingRecord
- fio-epa-frs_SiteRecord
- fio-epa-frs_StateTrackingRecord
- fio-epa-frs_SupplementalRecord
subproperty_of: fio_ofIndustry
range: Any
any_of:
- range: naics_NAICS-IndustryGroup
- range: rdfs_Resource
- range: naics_NAICS-IndustrySector
- range: owl_NamedIndividual
- range: naics_NAICS-IndustryCode
- range: owl_Thing
- range: fio_Industry
- range: naics_NAICS-IndustrySubsector

```
</details>