

# Slot: No slot (predicate) name specified (sockg_weatherRecordedBy)


_No slot (predicate) description specified_






This slot occurs 39489 times.


URI: [sockg:weatherRecordedBy](https://idir.uta.edu/sockg-ontology/docs/weatherRecordedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherStation](../classes/SockgWeatherStation.md) | A WeatherStation is a facility that collects and records meteorological data,... |  yes  |







## Properties

* Range: [SockgWeatherObservation](../classes/SockgWeatherObservation.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WeatherStation | sockg_WeatherObservation | sockg:individuals/588342 | sockg:individuals/439235 | 39489 |




## LinkML Source

<details>

```yaml
name: sockg_weatherRecordedBy
annotations:
  count:
    tag: count
    value: 39489
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/439235
    example_object_type: sockg_WeatherObservation
    example_predicate: sockg:weatherRecordedBy
    example_subject: sockg:individuals/588342
    example_subject_type: sockg_WeatherStation
from_schema: soc-kg
rank: 1000
domain: sockg_WeatherStation
slot_uri: sockg:weatherRecordedBy
alias: sockg_weatherRecordedBy
domain_of:
- sockg_WeatherStation
range: sockg_WeatherObservation

```
</details>