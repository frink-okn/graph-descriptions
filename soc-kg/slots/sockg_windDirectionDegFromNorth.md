

# Slot: No slot (predicate) name specified (sockg_windDirectionDegFromNorth)


_No slot (predicate) description specified_






This slot occurs 51210 times.


URI: [sockg:windDirectionDegFromNorth](https://idir.uta.edu/sockg-ontology/docs/windDirectionDegFromNorth)



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
| sockg_WeatherObservation | double | sockg:individuals/468806 | 52.84 | 51210 |


## See Also

* [https://lod.nal.usda.gov/nalt/67367](https://lod.nal.usda.gov/nalt/67367)



## LinkML Source

<details>

```yaml
name: sockg_windDirectionDegFromNorth
annotations:
  count:
    tag: count
    value: 51210
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '52.84'
    example_object_type: double
    example_predicate: sockg:windDirectionDegFromNorth
    example_subject: sockg:individuals/468806
    example_subject_type: sockg_WeatherObservation
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/67367
rank: 1000
domain: sockg_WeatherObservation
slot_uri: sockg:windDirectionDegFromNorth
alias: sockg_windDirectionDegFromNorth
domain_of:
- sockg_WeatherObservation
range: Any
any_of:
- range: double
- range: float

```
</details>