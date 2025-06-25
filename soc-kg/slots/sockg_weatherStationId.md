

# Slot: No slot (predicate) name specified (sockg_weatherStationId)


_No slot (predicate) description specified_






This slot occurs 38375 times.


URI: [sockg:weatherStationId](https://idir.uta.edu/sockg-ontology/docs/weatherStationId)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherObservation](../classes/SockgWeatherObservation.md) | The WeatherObservation class captures daily meteorological data that are cruc... |  yes  |
| [SockgWeatherStation](../classes/SockgWeatherStation.md) | A WeatherStation is a facility that collects and records meteorological data,... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WeatherObservation | string | sockg:individuals/439235 | MEADAGROFARM | 38363 |
| sockg_WeatherStation | string | sockg:individuals/588342 | MEADAGROFARM | 12 |




## LinkML Source

<details>

```yaml
name: sockg_weatherStationId
annotations:
  count:
    tag: count
    value: 38375
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: MEADAGROFARM
    example_object_type: string
    example_predicate: sockg:weatherStationId
    example_subject: sockg:individuals/439235
    example_subject_type: sockg_WeatherObservation
- object:
    example_object: MEADAGROFARM
    example_object_type: string
    example_predicate: sockg:weatherStationId
    example_subject: sockg:individuals/588342
    example_subject_type: sockg_WeatherStation
from_schema: soc-kg
rank: 1000
domain: sockg_WeatherStation
slot_uri: sockg:weatherStationId
alias: sockg_weatherStationId
domain_of:
- sockg_WeatherObservation
- sockg_WeatherStation
range: string

```
</details>