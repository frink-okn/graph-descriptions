

# Slot: No slot (predicate) name specified (sockg_tempMax_degC)


_No slot (predicate) description specified_






This slot occurs 144885 times.


URI: [sockg:tempMax_degC](https://idir.uta.edu/sockg-ontology/docs/tempMax_degC)



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
| sockg_WeatherObservation | double | sockg:individuals/439235 | 18.7 | 144885 |


## See Also

* [https://lod.nal.usda.gov/nalt/5859](https://lod.nal.usda.gov/nalt/5859)



## LinkML Source

<details>

```yaml
name: sockg_tempMax_degC
annotations:
  count:
    tag: count
    value: 144885
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '18.7'
    example_object_type: double
    example_predicate: sockg:tempMax_degC
    example_subject: sockg:individuals/439235
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/5859
rank: 1000
domain: sockg_WeatherObservation
slot_uri: sockg:tempMax_degC
alias: sockg_tempMax_degC
domain_of:
- sockg_WeatherObservation
range: Any
any_of:
- range: double
- range: float

```
</details>