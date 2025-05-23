

# Slot: No slot (predicate) name specified (sockg_precipitation_mm_per_d)


_No slot (predicate) description specified_






This slot occurs 147232 times.


URI: [sockg:precipitation_mm_per_d](https://idir.uta.edu/sockg-ontology/docs/precipitation_mm_per_d)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherObservation](../classes/SockgWeatherObservation.md) | The WeatherObservation class captures daily meteorological data that are cruc... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WeatherObservation | double | sockg:individuals/439235 | 0.0 | 147232 |


## See Also

* [https://lod.nal.usda.gov/nalt/44298](https://lod.nal.usda.gov/nalt/44298)



## LinkML Source

<details>

```yaml
name: sockg_precipitation_mm_per_d
annotations:
  count:
    tag: count
    value: 147232
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.0'
    example_object_type: double
    example_predicate: sockg:precipitation_mm_per_d
    example_subject: sockg:individuals/439235
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/44298
rank: 1000
domain: sockg_WeatherObservation
slot_uri: sockg:precipitation_mm_per_d
alias: sockg_precipitation_mm_per_d
domain_of:
- sockg_WeatherObservation
range: Any
any_of:
- range: float
- range: double

```
</details>