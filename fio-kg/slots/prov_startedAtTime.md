

# Slot: startedAtTime (prov_startedAtTime)


_The time at which an activity started. See also prov:endedAtTime._






This slot occurs 756926 times.


URI: [prov:startedAtTime](http://www.w3.org/ns/prov#startedAtTime)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies somet... |  no  |
| [Fio-epa-frsRegistrationRecord](../classes/Fio-epa-frsRegistrationRecord.md) |  |  no  |
| [Fio-epa-frsProjectRecord](../classes/Fio-epa-frsProjectRecord.md) |  |  no  |
| [Fio-epa-frsSiteRecord](../classes/Fio-epa-frsSiteRecord.md) | A record that monitors a site, beyond specific ownership of one organization ... |  no  |
| [Fio-epa-frsReportingRecord](../classes/Fio-epa-frsReportingRecord.md) |  |  no  |
| [Fio-epa-frsTribalTrackingRecord](../classes/Fio-epa-frsTribalTrackingRecord.md) |  |  no  |
| [Fio-epa-frsEnforcementActivity](../classes/Fio-epa-frsEnforcementActivity.md) | A record that tracks a specific legal, corrective or assistance action taken ... |  no  |
| [Fio-epa-frsEnforcementTrackingRecord](../classes/Fio-epa-frsEnforcementTrackingRecord.md) |  |  no  |
| [Fio-epa-frsRiskPlanRecord](../classes/Fio-epa-frsRiskPlanRecord.md) |  |  no  |
| [Fio-epa-frsStateTrackingRecord](../classes/Fio-epa-frsStateTrackingRecord.md) |  |  no  |
| [Fio-epa-frsPermitRecord](../classes/Fio-epa-frsPermitRecord.md) | A record that tracks a permit or license awarded to the facility |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |







## Properties

* Range: [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime)







## LinkML Source

<details>

```yaml
name: prov_startedAtTime
description: The time at which an activity started. See also prov:endedAtTime.
title: startedAtTime
notes:
- No occurrences of this slot in the graph.
from_schema: okns:prov
source: http://www.w3.org/ns/prov-o#
domain: prov_Activity
slot_uri: prov:startedAtTime
domain_of:
- fio-epa-frs_EnforcementActivity
- fio-epa-frs_EnforcementTrackingRecord
- fio-epa-frs_FRS-Facility
- fio-epa-frs_PermitRecord
- fio-epa-frs_ProjectRecord
- fio-epa-frs_RegistrationRecord
- fio-epa-frs_ReportingRecord
- fio-epa-frs_RiskPlanRecord
- fio-epa-frs_SiteRecord
- fio-epa-frs_StateTrackingRecord
- fio-epa-frs_SupplementalRecord
- fio-epa-frs_TribalTrackingRecord
range: datetime

```
</details>