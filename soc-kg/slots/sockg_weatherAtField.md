

# Slot: No slot (predicate) name specified (sockg_weatherAtField)


_No slot (predicate) description specified_






This slot occurs 147305 times.


URI: [sockg:weatherAtField](https://idir.uta.edu/sockg-ontology/docs/weatherAtField)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherObservation](../classes/SockgWeatherObservation.md) | The WeatherObservation class captures daily meteorological data that are cruc... |  yes  |







## Properties

* Range: [SockgField](../classes/SockgField.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WeatherObservation | sockg_Field | sockg:individuals/439235 | sockg:individuals/55827 | 147305 |




## LinkML Source

<details>

```yaml
name: sockg_weatherAtField
annotations:
  count:
    tag: count
    value: 147305
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/55827
    example_object_type: sockg_Field
    example_predicate: sockg:weatherAtField
    example_subject: sockg:individuals/439235
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
rank: 1000
domain: sockg_WeatherObservation
slot_uri: sockg:weatherAtField
alias: sockg_weatherAtField
domain_of:
- sockg_WeatherObservation
range: sockg_Field

```
</details>