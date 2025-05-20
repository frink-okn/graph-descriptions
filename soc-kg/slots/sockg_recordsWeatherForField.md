

# Slot: No slot (predicate) name specified (sockg_recordsWeatherForField)


_No slot (predicate) description specified_






This slot occurs 14 times.


URI: [sockg:recordsWeatherForField](https://idir.uta.edu/sockg-ontology/docs/recordsWeatherForField)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherStation](../classes/SockgWeatherStation.md) | A WeatherStation is a facility that collects and records meteorological data,... |  yes  |







## Properties

* Range: [SockgField](../classes/SockgField.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WeatherStation | sockg_Field | sockg:individuals/588342 | sockg:individuals/55827 | 14 |




## LinkML Source

<details>

```yaml
name: sockg_recordsWeatherForField
annotations:
  count:
    tag: count
    value: 14
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/55827
    example_object_type: sockg_Field
    example_predicate: sockg:recordsWeatherForField
    example_subject: sockg:individuals/588342
    example_subject_type: sockg_WeatherStation
from_schema: soc-kg
rank: 1000
domain: sockg_WeatherStation
slot_uri: sockg:recordsWeatherForField
alias: sockg_recordsWeatherForField
domain_of:
- sockg_WeatherStation
range: sockg_Field

```
</details>