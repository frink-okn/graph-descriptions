

# Slot: startDate (sdos_startDate)


_The start date and time of the item (in [ISO 8601 date format](http://en.wikipedia.org/wiki/ISO_8601))._






This slot occurs 556 times.


URI: [sdos:startDate](https://schema.org/startDate)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosDateTime](../classes/SdosDateTime.md)&nbsp;or&nbsp;<br />[SdosDate](../classes/SdosDate.md)







## LinkML Source

<details>

```yaml
name: sdos_startDate
description: The start date and time of the item (in [ISO 8601 date format](http://en.wikipedia.org/wiki/ISO_8601)).
title: startDate
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
source: https://github.com/schemaorg/schemaorg/issues/2486
slot_uri: sdos:startDate
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