

# Slot: No slot (predicate) name specified (sockg_weatherRecordedAt)


_No slot (predicate) description specified_






This slot occurs 149473 times.


URI: [sockg:weatherRecordedAt](https://idir.uta.edu/sockg-ontology/docs/weatherRecordedAt)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherObservation](../classes/SockgWeatherObservation.md) | The WeatherObservation class captures daily meteorological data that are cruc... |  yes  |







## Properties

* Range: [SockgSite](../classes/SockgSite.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WeatherObservation | sockg_Site | sockg:individuals/439235 | sockg:individuals/231084 | 149473 |




## LinkML Source

<details>

```yaml
name: sockg_weatherRecordedAt
annotations:
  count:
    tag: count
    value: 149473
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/231084
    example_object_type: sockg_Site
    example_predicate: sockg:weatherRecordedAt
    example_subject: sockg:individuals/439235
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
rank: 1000
domain: sockg_WeatherObservation
slot_uri: sockg:weatherRecordedAt
alias: sockg_weatherRecordedAt
domain_of:
- sockg_WeatherObservation
range: sockg_Site

```
</details>