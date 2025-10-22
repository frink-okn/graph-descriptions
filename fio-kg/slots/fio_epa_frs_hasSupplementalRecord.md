

# Slot: has supplemental record (fio-epa-frs_hasSupplementalRecord)




This slot occurs 244147 times.


URI: [fio-epa-frs:hasSupplementalRecord](http://w3id.org/fio/v1/epa-frs#hasSupplementalRecord)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsRecord](../classes/Fio-epa-frsRecord.md) |  |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Fio-epa-frsReportingRecord](../classes/Fio-epa-frsReportingRecord.md) |  |  no  |
| [Fio-epa-frsStateTrackingRecord](../classes/Fio-epa-frsStateTrackingRecord.md) |  |  no  |
| [Fio-epa-frsEnforcementActivity](../classes/Fio-epa-frsEnforcementActivity.md) | A record that tracks a specific legal, corrective or assistance action taken ... |  no  |
| [Fio-epa-frsSiteRecord](../classes/Fio-epa-frsSiteRecord.md) | A record that monitors a site, beyond specific ownership of one organization ... |  no  |
| [Fio-epa-frsRegistrationRecord](../classes/Fio-epa-frsRegistrationRecord.md) |  |  no  |
| [Fio-epa-frsPermitRecord](../classes/Fio-epa-frsPermitRecord.md) | A record that tracks a permit or license awarded to the facility |  no  |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies somet... |  no  |
| [Fio-epa-frsEnforcementTrackingRecord](../classes/Fio-epa-frsEnforcementTrackingRecord.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Fio-epa-frsPermitRecord](../classes/Fio-epa-frsPermitRecord.md)&nbsp;or&nbsp;<br />[Fio-epa-frsRiskPlanRecord](../classes/Fio-epa-frsRiskPlanRecord.md)&nbsp;or&nbsp;<br />[Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md)&nbsp;or&nbsp;<br />[Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md)&nbsp;or&nbsp;<br />[Fio-epa-frsRecord](../classes/Fio-epa-frsRecord.md)&nbsp;or&nbsp;<br />[Fio-epa-frsEnforcementTrackingRecord](../classes/Fio-epa-frsEnforcementTrackingRecord.md)&nbsp;or&nbsp;<br />[Fio-epa-frsSiteRecord](../classes/Fio-epa-frsSiteRecord.md)&nbsp;or&nbsp;<br />[Fio-epa-frsReportingRecord](../classes/Fio-epa-frsReportingRecord.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[Fio-epa-frsRegistrationRecord](../classes/Fio-epa-frsRegistrationRecord.md)







## LinkML Source

<details>

```yaml
name: fio-epa-frs_hasSupplementalRecord
title: has supplemental record
from_schema: okns:fio-kg
rank: 1000
slot_uri: fio-epa-frs:hasSupplementalRecord
alias: fio_epa_frs_hasSupplementalRecord
domain_of:
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
subproperty_of: fio-epa-frs_hasRecord
union_of:
- owl_Thing
- fio_Facility
- fio-epa-frs_FRS-Facility
range: Any
any_of:
- range: fio-epa-frs_PermitRecord
- range: fio-epa-frs_RiskPlanRecord
- range: fio-epa-frs_FRS-Facility
- range: fio-epa-frs_SupplementalRecord
- range: fio-epa-frs_Record
- range: fio-epa-frs_EnforcementTrackingRecord
- range: fio-epa-frs_SiteRecord
- range: fio-epa-frs_ReportingRecord
- range: owl_Thing
- range: fio-epa-frs_RegistrationRecord

```
</details>