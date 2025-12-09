

# Slot: endDate (sdos_endDate)


_The end date and time of the item (in [ISO 8601 date format](http://en.wikipedia.org/wiki/ISO_8601))._






This slot occurs 555 times.


URI: [sdos:endDate](https://schema.org/endDate)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosDateTime](../classes/SdosDateTime.md)&nbsp;or&nbsp;<br />[SdosDate](../classes/SdosDate.md)







## LinkML Source

<details>

```yaml
name: sdos_endDate
description: The end date and time of the item (in [ISO 8601 date format](http://en.wikipedia.org/wiki/ISO_8601)).
title: endDate
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
source: https://github.com/schemaorg/schemaorg/issues/2486
slot_uri: sdos:endDate
union_of:
- sdos_MerchantReturnPolicySeasonalOverride
- sdos_Role
- sdos_CreativeWorkSeason
- sdos_CreativeWorkSeries
- sdos_EducationalOccupationalProgram
- sdos_Schedule
- sdos_Event
- sdos_DatedMoneySpecification
range: Any
any_of:
- range: sdos_DateTime
- range: sdos_Date

```
</details>