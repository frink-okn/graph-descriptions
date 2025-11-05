

# Slot: endedAtTime (prov_endedAtTime)


_The time at which an activity ended. See also prov:startedAtTime._






This slot occurs 137752 times.


URI: [prov:endedAtTime](http://www.w3.org/ns/prov#endedAtTime)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Fio-epa-frsReportingRecord](../classes/Fio-epa-frsReportingRecord.md) |  |  no  |
| [Fio-epa-frsSiteRecord](../classes/Fio-epa-frsSiteRecord.md) | A record that monitors a site, beyond specific ownership of one organization ... |  no  |
| [Fio-epa-frsProjectRecord](../classes/Fio-epa-frsProjectRecord.md) |  |  no  |
| [Fio-epa-frsPermitRecord](../classes/Fio-epa-frsPermitRecord.md) | A record that tracks a permit or license awarded to the facility |  no  |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies somet... |  no  |
| [Fio-epa-frsEnforcementTrackingRecord](../classes/Fio-epa-frsEnforcementTrackingRecord.md) |  |  no  |







## Properties

* Range: [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime)







## LinkML Source

<details>

```yaml
name: prov_endedAtTime
description: The time at which an activity ended. See also prov:startedAtTime.
title: endedAtTime
notes:
- No occurrences of this slot in the graph.
from_schema: okns:prov
source: http://www.w3.org/ns/prov-o#
domain: prov_Activity
slot_uri: prov:endedAtTime
domain_of:
- fio-epa-frs_EnforcementTrackingRecord
- fio-epa-frs_FRS-Facility
- fio-epa-frs_PermitRecord
- fio-epa-frs_ProjectRecord
- fio-epa-frs_ReportingRecord
- fio-epa-frs_SiteRecord
- fio-epa-frs_SupplementalRecord
range: datetime

```
</details>