

# Slot: No slot (predicate) name specified (sockg_windSpeed_m_per_s)


_No slot (predicate) description specified_






This slot occurs 92684 times.


URI: [sockg:windSpeed_m_per_s](https://idir.uta.edu/sockg-ontology/docs/windSpeed_m_per_s)



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
| sockg_WeatherObservation | double | sockg:individuals/439235 | 2.4 | 92684 |


## See Also

* [https://lod.nal.usda.gov/nalt/4651](https://lod.nal.usda.gov/nalt/4651)



## LinkML Source

<details>

```yaml
name: sockg_windSpeed_m_per_s
annotations:
  count:
    tag: count
    value: 92684
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '2.4'
    example_object_type: double
    example_predicate: sockg:windSpeed_m_per_s
    example_subject: sockg:individuals/439235
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/4651
rank: 1000
domain: sockg_WeatherObservation
slot_uri: sockg:windSpeed_m_per_s
alias: sockg_windSpeed_m_per_s
domain_of:
- sockg_WeatherObservation
range: Any
any_of:
- range: float
- range: double

```
</details>