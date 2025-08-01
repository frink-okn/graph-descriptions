

# Slot: Date (dct_date)


_Date may be used to express temporal information at any level of granularity.  Recommended practice is to express the date, date/time, or period of time according to ISO 8601-1 [[ISO 8601-1](https://www.iso.org/iso-8601-date-and-time-format.html)] or a published profile of the ISO standard, such as the W3C Note on Date and Time Formats [[W3CDTF](https://www.w3.org/TR/NOTE-datetime)] or the Extended Date/Time Format Specification [[EDTF](http://www.loc.gov/standards/datetime/)].  If the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used. Date ranges may be specified using ISO 8601 period of time specification in which start and end dates are separated by a '/' (slash) character.  Either the start or end date may be missing._






This slot occurs 913191 times.


URI: [dct:date](http://purl.org/dc/terms/date)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |







## Properties

* Range: [RdfsLiteral](../classes/RdfsLiteral.md)





## Comments

* description: A point or period of time associated with an event in the lifecycle of the resource.
* No occurrences of this slot in the graph.



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
comments:
- 'description: A point or period of time associated with an event in the lifecycle
  of the resource.'
- No occurrences of this slot in the graph.
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:date
domain_of:
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
subproperty_of: dc_date
range: rdfs_Literal

```
</details>