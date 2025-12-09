

# Slot: dateCreated (sdos_dateCreated)


_The date on which the CreativeWork was created or the item was added to a DataFeed._






This slot occurs 8451 times.


URI: [sdos:dateCreated](https://schema.org/dateCreated)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosDateTime](../classes/SdosDateTime.md)&nbsp;or&nbsp;<br />[SdosDate](../classes/SdosDate.md)







## LinkML Source

<details>

```yaml
name: sdos_dateCreated
description: The date on which the CreativeWork was created or the item was added
  to a DataFeed.
title: dateCreated
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
slot_uri: sdos:dateCreated
union_of:
- sdos_CreativeWork
- sdos_DataFeedItem
range: Any
any_of:
- range: sdos_DateTime
- range: sdos_Date

```
</details>