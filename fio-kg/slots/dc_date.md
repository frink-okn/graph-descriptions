

# Slot: Date (dc_date)


_Date may be used to express temporal information at any level of granularity.  Recommended practice is to express the date, date/time, or period of time according to ISO 8601-1 [[ISO 8601-1](https://www.iso.org/iso-8601-date-and-time-format.html)] or a published profile of the ISO standard, such as the W3C Note on Date and Time Formats [[W3CDTF](https://www.w3.org/TR/NOTE-datetime)] or the Extended Date/Time Format Specification [[EDTF](http://www.loc.gov/standards/datetime/)].  If the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used. Date ranges may be specified using ISO 8601 period of time specification in which start and end dates are separated by a '/' (slash) character.  Either the start or end date may be missing._






This slot occurs 913191 times.


URI: [dc:date](http://purl.org/dc/elements/1.1/date)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |







## Properties

* Range: [Any](../classes/Any.md)





## Comments

* description: A point or period of time associated with an event in the lifecycle of the resource.



## LinkML Source

<details>

```yaml
name: dc_date
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
- 'A [second property](/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/date)
  with the same name as this property has been declared in the [dcterms: namespace](http://purl.org/dc/terms/).  See
  the Introduction to the document [DCMI Metadata Terms](/specifications/dublin-core/dcmi-terms/)
  for an explanation.'
- No occurrences of this slot in the graph.
comments:
- 'description: A point or period of time associated with an event in the lifecycle
  of the resource.'
from_schema: okns:dc
source: http://purl.org/dc/elements/1.1/
slot_uri: dc:date
domain_of:
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
range: Any

```
</details>