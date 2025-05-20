

# Slot: sockg_dewPointDegc


_No slot (predicate) description specified_






This slot occurs 121030 times.


URI: [sockg:dewPointDegc](https://idir.uta.edu/sockg-ontology/docs/dewPointDegc)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherObservation](../classes/SockgWeatherObservation.md) | The WeatherObservation class captures daily meteorological data that are cruc... |  yes  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WeatherObservation | double | sockg:individuals/439235 | 0.0 | 121030 |




## LinkML Source

<details>

```yaml
name: sockg_dewPointDegc
annotations:
  count:
    tag: count
    value: 121030
description: No slot (predicate) description specified
examples:
- object:
    example_object: '0.0'
    example_object_type: double
    example_predicate: sockg:dewPointDegc
    example_subject: sockg:individuals/439235
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
rank: 1000
slot_uri: sockg:dewPointDegc
alias: sockg_dewPointDegc
domain_of:
- sockg_WeatherObservation
range: double

```
</details>