

# Slot: No slot (predicate) name specified (sockg_weatherBadValueFlag)


_No slot (predicate) description specified_






This slot occurs 1824 times.


URI: [sockg:weatherBadValueFlag](https://idir.uta.edu/sockg-ontology/docs/weatherBadValueFlag)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherObservation](../classes/SockgWeatherObservation.md) | The WeatherObservation class captures daily meteorological data that are cruc... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WeatherObservation | double | sockg:individuals/501979 | -999.0 | 1824 |




## LinkML Source

<details>

```yaml
name: sockg_weatherBadValueFlag
annotations:
  count:
    tag: count
    value: 1824
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '-999.0'
    example_object_type: double
    example_predicate: sockg:weatherBadValueFlag
    example_subject: sockg:individuals/501979
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
rank: 1000
domain: sockg_WeatherObservation
slot_uri: sockg:weatherBadValueFlag
alias: sockg_weatherBadValueFlag
domain_of:
- sockg_WeatherObservation
range: Any
any_of:
- range: integer
- range: double

```
</details>