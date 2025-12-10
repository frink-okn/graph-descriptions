

# Slot: Date (dct_date)


_Date may be used to express temporal information at any level of granularity.  Recommended practice is to express the date, date/time, or period of time according to ISO 8601-1 [[ISO 8601-1](https://www.iso.org/iso-8601-date-and-time-format.html)] or a published profile of the ISO standard, such as the W3C Note on Date and Time Formats [[W3CDTF](https://www.w3.org/TR/NOTE-datetime)] or the Extended Date/Time Format Specification [[EDTF](http://www.loc.gov/standards/datetime/)].  If the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used. Date ranges may be specified using ISO 8601 period of time specification in which start and end dates are separated by a '/' (slash) character.  Either the start or end date may be missing._






This slot occurs 10817 times.


URI: [dct:date](http://purl.org/dc/terms/date)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset.md) |  |  no  |







## Properties

* Range: [RdfsLiteral](../classes/RdfsLiteral.md)





## Comments

* description: A point or period of time associated with an event in the lifecycle of the resource.



## LinkML Source

<details>

```yaml
name: dct_date
description: Date may be used to express temporal information at any level of granularity.  Recommended
  practice is to express the date, date/time, or period of time according to ISO 8601-1
  [[ISO 8601-1](https://www.iso.org/iso-8601-date-and-time-format.html)] or a published
  profile of the ISO standard, such as the W3C Note on Date and Time Formats [[W3CDTF](https://www.w3.org/TR/NOTE-datetime)]
  or the Extended Date/Time Format Specification [[EDTF](http://www.loc.gov/standards/datetime/)].  If
  the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used.
  Date ranges may be specified using ISO 8601 period of time specification in which
  start and end dates are separated by a '/' (slash) character.  Either the start
  or end date may be missing.
title: Date
notes:
- No occurrences of this slot in the graph.
comments:
- 'description: A point or period of time associated with an event in the lifecycle
  of the resource.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:date
domain_of:
- https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
subproperty_of: dc_date
range: rdfs_Literal

```
</details>