

# Slot: workLocation (sdos_workLocation)


_A contact location for a person's place of work._






This slot occurs 158 times.


URI: [sdos:workLocation](https://schema.org/workLocation)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosPlace](../classes/SdosPlace.md)&nbsp;or&nbsp;<br />[SdosContactPoint](../classes/SdosContactPoint.md)







## LinkML Source

<details>

```yaml
name: sdos_workLocation
description: A contact location for a person's place of work.
title: workLocation
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
domain: sdos_Person
slot_uri: sdos:workLocation
subproperty_of: sdos_location
range: Any
any_of:
- range: sdos_Place
- range: sdos_ContactPoint

```
</details>