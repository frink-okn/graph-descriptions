

# Slot: No slot (predicate) name specified (sockg_recordsWeatherForSite)


_No slot (predicate) description specified_






This slot occurs 14 times.


URI: [sockg:recordsWeatherForSite](https://idir.uta.edu/sockg-ontology/docs/recordsWeatherForSite)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherStation](../classes/SockgWeatherStation.md) | A WeatherStation is a facility that collects and records meteorological data,... |  yes  |







## Properties

* Range: [SockgSite](../classes/SockgSite.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WeatherStation | sockg_Site | sockg:individuals/588342 | sockg:individuals/231084 | 14 |




## LinkML Source

<details>

```yaml
name: sockg_recordsWeatherForSite
annotations:
  count:
    tag: count
    value: 14
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/231084
    example_object_type: sockg_Site
    example_predicate: sockg:recordsWeatherForSite
    example_subject: sockg:individuals/588342
    example_subject_type: sockg_WeatherStation
from_schema: soc-kg
rank: 1000
domain: sockg_WeatherStation
slot_uri: sockg:recordsWeatherForSite
alias: sockg_recordsWeatherForSite
domain_of:
- sockg_WeatherStation
range: sockg_Site

```
</details>