

# Slot: author (sdos_author)


_The author of this content or rating. Please note that author is special in that HTML 5 provides a special mechanism for indicating authorship via the rel tag. That is equivalent to this and may be used interchangeably._






This slot occurs 23043 times.


URI: [sdos:author](https://schema.org/author)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosOrganization](../classes/SdosOrganization.md)&nbsp;or&nbsp;<br />[SdosPerson](../classes/SdosPerson.md)







## LinkML Source

<details>

```yaml
name: sdos_author
description: The author of this content or rating. Please note that author is special
  in that HTML 5 provides a special mechanism for indicating authorship via the rel
  tag. That is equivalent to this and may be used interchangeably.
title: author
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
slot_uri: sdos:author
union_of:
- sdos_CreativeWork
- sdos_Rating
range: Any
any_of:
- range: sdos_Organization
- range: sdos_Person

```
</details>