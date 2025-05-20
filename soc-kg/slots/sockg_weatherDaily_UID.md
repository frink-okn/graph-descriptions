

# Slot: No slot (predicate) name specified (sockg_weatherDaily_UID)


_No slot (predicate) description specified_






This slot occurs 147305 times.


URI: [sockg:weatherDaily_UID](https://idir.uta.edu/sockg-ontology/docs/weatherDaily_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherObservation](../classes/SockgWeatherObservation.md) | The WeatherObservation class captures daily meteorological data that are cruc... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WeatherObservation | string | sockg:individuals/439235 | AgCros_NEMEIRR_2015-10-25 | 147305 |




## LinkML Source

<details>

```yaml
name: sockg_weatherDaily_UID
annotations:
  count:
    tag: count
    value: 147305
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_NEMEIRR_2015-10-25
    example_object_type: string
    example_predicate: sockg:weatherDaily_UID
    example_subject: sockg:individuals/439235
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
rank: 1000
domain: sockg_WeatherObservation
slot_uri: sockg:weatherDaily_UID
alias: sockg_weatherDaily_UID
domain_of:
- sockg_WeatherObservation
range: string

```
</details>