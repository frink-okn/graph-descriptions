

# Slot: subjectOf (sdos_subjectOf)


_A CreativeWork or Event about this Thing._






This slot occurs 10410 times.


URI: [sdos:subjectOf](https://schema.org/subjectOf)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosCreativeWork](../classes/SdosCreativeWork.md)&nbsp;or&nbsp;<br />[SdosEvent](../classes/SdosEvent.md)







## LinkML Source

<details>

```yaml
name: sdos_subjectOf
description: A CreativeWork or Event about this Thing.
title: subjectOf
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
source: https://github.com/schemaorg/schemaorg/issues/1670
domain: sdos_Thing
slot_uri: sdos:subjectOf
inverse: sdos_about
range: Any
any_of:
- range: sdos_CreativeWork
- range: sdos_Event

```
</details>