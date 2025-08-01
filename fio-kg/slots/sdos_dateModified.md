

# Slot: dateModified (sdos_dateModified)


_The date on which the CreativeWork was most recently modified or when the item's entry was modified within a DataFeed._






This slot occurs 458427 times.


URI: [sdos:dateModified](https://schema.org/dateModified)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosDate](../classes/SdosDate.md)&nbsp;or&nbsp;<br />[SdosDateTime](../classes/SdosDateTime.md)





## Comments

* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: sdos_dateModified
description: The date on which the CreativeWork was most recently modified or when
  the item's entry was modified within a DataFeed.
title: dateModified
comments:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
slot_uri: sdos:dateModified
union_of:
- sdos_DataFeedItem
- sdos_CreativeWork
range: Any
any_of:
- range: sdos_Date
- range: sdos_DateTime

```
</details>