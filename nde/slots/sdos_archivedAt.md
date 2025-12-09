

# Slot: archivedAt (sdos_archivedAt)


_Indicates a page or other link involved in archival of a [[CreativeWork]]. In the case of [[MediaReview]], the items in a [[MediaReviewItem]] may often become inaccessible, but be archived by archival, journalistic, activist, or law enforcement organizations. In such cases, the referenced page may not directly publish the content._






This slot occurs 10641 times.


URI: [sdos:archivedAt](https://schema.org/archivedAt)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosURL](../classes/SdosURL.md)&nbsp;or&nbsp;<br />[SdosWebPage](../classes/SdosWebPage.md)







## LinkML Source

<details>

```yaml
name: sdos_archivedAt
description: Indicates a page or other link involved in archival of a [[CreativeWork]].
  In the case of [[MediaReview]], the items in a [[MediaReviewItem]] may often become
  inaccessible, but be archived by archival, journalistic, activist, or law enforcement
  organizations. In such cases, the referenced page may not directly publish the content.
title: archivedAt
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
source: https://github.com/schemaorg/schemaorg/issues/2450
domain: sdos_CreativeWork
slot_uri: sdos:archivedAt
range: Any
any_of:
- range: sdos_URL
- range: sdos_WebPage

```
</details>