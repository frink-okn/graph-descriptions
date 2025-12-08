

# Slot: datePublished (sdos_datePublished)


_Date of first publication or broadcast. For example the date a [[CreativeWork]] was broadcast or a [[Certification]] was issued._






This slot occurs 8490 times.


URI: [sdos:datePublished](https://schema.org/datePublished)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosDateTime](../classes/SdosDateTime.md)&nbsp;or&nbsp;<br />[SdosDate](../classes/SdosDate.md)







## LinkML Source

<details>

```yaml
name: sdos_datePublished
description: Date of first publication or broadcast. For example the date a [[CreativeWork]]
  was broadcast or a [[Certification]] was issued.
title: datePublished
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
slot_uri: sdos:datePublished
union_of:
- sdos_Certification
- sdos_CreativeWork
range: Any
any_of:
- range: sdos_DateTime
- range: sdos_Date

```
</details>