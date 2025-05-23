

# Slot: No slot (predicate) name specified (sockg_relativeHumidityPercent)


_No slot (predicate) description specified_






This slot occurs 138705 times.


URI: [sockg:relativeHumidityPercent](https://idir.uta.edu/sockg-ontology/docs/relativeHumidityPercent)



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
| sockg_WeatherObservation | double | sockg:individuals/439235 | 60.27 | 138705 |


## See Also

* [https://lod.nal.usda.gov/nalt/46149](https://lod.nal.usda.gov/nalt/46149)



## LinkML Source

<details>

```yaml
name: sockg_relativeHumidityPercent
annotations:
  count:
    tag: count
    value: 138705
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '60.27'
    example_object_type: double
    example_predicate: sockg:relativeHumidityPercent
    example_subject: sockg:individuals/439235
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/46149
rank: 1000
domain: sockg_WeatherObservation
slot_uri: sockg:relativeHumidityPercent
alias: sockg_relativeHumidityPercent
domain_of:
- sockg_WeatherObservation
range: Any
any_of:
- range: float
- range: double

```
</details>