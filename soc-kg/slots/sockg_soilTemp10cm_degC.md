

# Slot: No slot (predicate) name specified (sockg_soilTemp10cm_degC)


_No slot (predicate) description specified_






This slot occurs 138926 times.


URI: [sockg:soilTemp10cm_degC](https://idir.uta.edu/sockg-ontology/docs/soilTemp10cm_degC)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherObservation](../classes/SockgWeatherObservation.md) | The WeatherObservation class captures daily meteorological data that are cruc... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WeatherObservation | double | sockg:individuals/439235 | 12.3 | 138926 |


## See Also

* [https://lod.nal.usda.gov/nalt/61641](https://lod.nal.usda.gov/nalt/61641)



## LinkML Source

<details>

```yaml
name: sockg_soilTemp10cm_degC
annotations:
  count:
    tag: count
    value: 138926
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '12.3'
    example_object_type: double
    example_predicate: sockg:soilTemp10cm_degC
    example_subject: sockg:individuals/439235
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/61641
rank: 1000
domain: sockg_WeatherObservation
slot_uri: sockg:soilTemp10cm_degC
alias: sockg_soilTemp10cm_degC
domain_of:
- sockg_WeatherObservation
range: Any
any_of:
- range: double
- range: float

```
</details>