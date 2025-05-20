

# Slot: No slot (predicate) name specified (sockg_solarRadiationBareSoil_MJ_per_m_squared_per_d)


_No slot (predicate) description specified_






This slot occurs 38763 times.


URI: [sockg:solarRadiationBareSoil_MJ_per_m_squared_per_d](https://idir.uta.edu/sockg-ontology/docs/solarRadiationBareSoil_MJ_per_m_squared_per_d)



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
| sockg_WeatherObservation | double | sockg:individuals/439235 | 7.35 | 38763 |


## See Also

* [https://lod.nal.usda.gov/nalt/47447](https://lod.nal.usda.gov/nalt/47447)



## LinkML Source

<details>

```yaml
name: sockg_solarRadiationBareSoil_MJ_per_m_squared_per_d
annotations:
  count:
    tag: count
    value: 38763
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '7.35'
    example_object_type: double
    example_predicate: sockg:solarRadiationBareSoil_MJ_per_m_squared_per_d
    example_subject: sockg:individuals/439235
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/47447
rank: 1000
domain: sockg_WeatherObservation
slot_uri: sockg:solarRadiationBareSoil_MJ_per_m_squared_per_d
alias: sockg_solarRadiationBareSoil_MJ_per_m_squared_per_d
domain_of:
- sockg_WeatherObservation
range: Any
any_of:
- range: double
- range: float

```
</details>