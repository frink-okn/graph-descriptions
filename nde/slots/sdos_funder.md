

# Slot: funder (sdos_funder)


_A person or organization that supports (sponsors) something through some kind of financial contribution._






This slot occurs 588 times.


URI: [sdos:funder](https://schema.org/funder)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosOrganization](../classes/SdosOrganization.md)&nbsp;or&nbsp;<br />[SdosPerson](../classes/SdosPerson.md)







## LinkML Source

<details>

```yaml
name: sdos_funder
description: A person or organization that supports (sponsors) something through some
  kind of financial contribution.
title: funder
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
slot_uri: sdos:funder
subproperty_of: sdos_sponsor
union_of:
- sdos_MonetaryGrant
- sdos_Grant
- sdos_CreativeWork
- sdos_Person
- sdos_Organization
- sdos_Event
range: Any
any_of:
- range: sdos_Organization
- range: sdos_Person

```
</details>