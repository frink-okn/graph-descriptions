

# Slot: endedAtTime (prov_endedAtTime)


_The time at which an activity ended. See also prov:startedAtTime._






This slot occurs 137752 times.


URI: [prov:endedAtTime](http://www.w3.org/ns/prov#endedAtTime)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Node510](../classes/Node510.md) |  |  no  |
| [Node523](../classes/Node523.md) |  |  no  |
| [Node521](../classes/Node521.md) |  |  no  |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies somet... |  no  |
| [Node512](../classes/Node512.md) |  |  no  |
| [Node513](../classes/Node513.md) |  |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Node501](../classes/Node501.md) |  |  no  |
| [Node359](../classes/Node359.md) |  |  no  |
| [Node508](../classes/Node508.md) |  |  no  |
| [Node499](../classes/Node499.md) |  |  no  |







## Properties

* Range: [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime)





## Comments

* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: prov_endedAtTime
description: The time at which an activity ended. See also prov:startedAtTime.
title: endedAtTime
comments:
- No occurrences of this slot in the graph.
from_schema: okns:prov
source: http://www.w3.org/ns/prov-o#
domain: prov_Activity
slot_uri: prov:endedAtTime
domain_of:
- __node359
- __node499
- __node501
- __node508
- __node510
- __node512
- __node513
- __node521
- __node523
- fio-epa-frs_FRS-Facility
- fio-epa-frs_SupplementalRecord
range: datetime

```
</details>