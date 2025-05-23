

# Slot: sockg_totalSolarRadiationBareSoil_MJ_per_m_squared_per_d


_No slot (predicate) description specified_






This slot occurs 8195 times.


URI: [sockg:totalSolarRadiationBareSoil_MJ_per_m_squared_per_d](https://idir.uta.edu/sockg-ontology/docs/totalSolarRadiationBareSoil_MJ_per_m_squared_per_d)



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
| sockg_WeatherObservation | double | sockg:individuals/366472 | 3.964 | 8195 |




## LinkML Source

<details>

```yaml
name: sockg_totalSolarRadiationBareSoil_MJ_per_m_squared_per_d
annotations:
  count:
    tag: count
    value: 8195
description: No slot (predicate) description specified
examples:
- object:
    example_object: '3.964'
    example_object_type: double
    example_predicate: sockg:totalSolarRadiationBareSoil_MJ_per_m_squared_per_d
    example_subject: sockg:individuals/366472
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
rank: 1000
slot_uri: sockg:totalSolarRadiationBareSoil_MJ_per_m_squared_per_d
alias: sockg_totalSolarRadiationBareSoil_MJ_per_m_squared_per_d
domain_of:
- sockg_WeatherObservation
range: double

```
</details>