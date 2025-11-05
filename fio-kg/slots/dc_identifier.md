

# Slot: Identifier (dc_identifier)


_Recommended practice is to identify the resource by means of a string conforming to an identification system._






This slot occurs 1755984 times.


URI: [dc:identifier](http://purl.org/dc/elements/1.1/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsReportingRecord](../classes/Fio-epa-frsReportingRecord.md) |  |  no  |
| [NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md) |  |  no  |
| [Fio-epa-frsSiteRecord](../classes/Fio-epa-frsSiteRecord.md) | A record that monitors a site, beyond specific ownership of one organization ... |  no  |
| [NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md) |  |  no  |
| [Fio-epa-frsTribalTrackingRecord](../classes/Fio-epa-frsTribalTrackingRecord.md) |  |  no  |
| [Fio-epa-frsComplianceRecord](../classes/Fio-epa-frsComplianceRecord.md) |  |  no  |
| [Fio-epa-frsProjectRecord](../classes/Fio-epa-frsProjectRecord.md) |  |  no  |
| [Fio-epa-frsStateTrackingRecord](../classes/Fio-epa-frsStateTrackingRecord.md) |  |  no  |
| [Fio-epa-frsEnforcementActivity](../classes/Fio-epa-frsEnforcementActivity.md) | A record that tracks a specific legal, corrective or assistance action taken ... |  no  |
| [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |  |  no  |
| [Fio-epa-frsRecord](../classes/Fio-epa-frsRecord.md) |  |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |
| [NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md) |  |  no  |
| [Fio-epa-frsRiskPlanRecord](../classes/Fio-epa-frsRiskPlanRecord.md) |  |  no  |
| [Fio-epa-frsRegistrationRecord](../classes/Fio-epa-frsRegistrationRecord.md) |  |  no  |
| [Fio-epa-frsPermitRecord](../classes/Fio-epa-frsPermitRecord.md) | A record that tracks a permit or license awarded to the facility |  no  |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies somet... |  no  |
| [Fio-epa-frsEnforcementTrackingRecord](../classes/Fio-epa-frsEnforcementTrackingRecord.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)





## Comments

* description: An unambiguous reference to the resource within a given context.



## LinkML Source

<details>

```yaml
name: dc_identifier
description: Recommended practice is to identify the resource by means of a string
  conforming to an identification system.
title: Identifier
notes:
- 'A [second property](/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/identifier)
  with the same name as this property has been declared in the [dcterms: namespace](http://purl.org/dc/terms/).  See
  the Introduction to the document [DCMI Metadata Terms](/specifications/dublin-core/dcmi-terms/)
  for an explanation.'
- No occurrences of this slot in the graph.
comments:
- 'description: An unambiguous reference to the resource within a given context.'
from_schema: okns:dc
source: http://purl.org/dc/elements/1.1/
slot_uri: dc:identifier
domain_of:
- fio-epa-frs_ComplianceRecord
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_EnforcementActivity
- fio-epa-frs_EnforcementTrackingRecord
- fio-epa-frs_FRS-Facility
- fio-epa-frs_PermitRecord
- fio-epa-frs_ProjectRecord
- fio-epa-frs_Record
- fio-epa-frs_RegistrationRecord
- fio-epa-frs_ReportingRecord
- fio-epa-frs_RiskPlanRecord
- fio-epa-frs_SiteRecord
- fio-epa-frs_StateTrackingRecord
- fio-epa-frs_SupplementalRecord
- fio-epa-frs_TribalTrackingRecord
- naics_NAICS-IndustryCode
- naics_NAICS-IndustryGroup
- naics_NAICS-IndustrySector
- naics_NAICS-IndustrySubsector
range: Any

```
</details>