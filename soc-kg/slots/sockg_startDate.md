

# Slot: No slot (predicate) name specified (sockg_startDate)


_No slot (predicate) description specified_






This slot occurs 93567 times.


URI: [sockg:startDate](https://idir.uta.edu/sockg-ontology/docs/startDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGrazingManagementEvent](../classes/SockgGrazingManagementEvent.md) | A GrazingManagementEvent represents a specific instance of land management pr... |  yes  |
| [SockgPlantingEvent](../classes/SockgPlantingEvent.md) | An event involving the act of planting, which includes considerations for spa... |  yes  |
| [SockgTillage](../classes/SockgTillage.md) | Tillage refers to the agricultural preparation of soil through mechanical agi... |  yes  |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |
| [SockgExperiment](../classes/SockgExperiment.md) | An Experiment is a structured investigation carried out to observe and analyz... |  yes  |
| [SockgAmendment](../classes/SockgAmendment.md) | An Amendment represents a specific alteration or addition made to agricultura... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:date](http://www.w3.org/2001/XMLSchema#date)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Amendment | string | sockg:individuals/0 | 2012-06-05 | 37796 |
| sockg_GrazingManagementEvent | string | sockg:individuals/170955 | 2006-05-08 | 1951 |
| sockg_Tillage | string | sockg:individuals/336419 | 1987-04-30 | 27137 |
| sockg_Experiment | string | sockg:individuals/51906 | 2007-04-01 | 55 |
| sockg_ExperimentalUnit | string | sockg:individuals/51937 | 2009-01-01 | 3178 |
| sockg_PlantingEvent | string | sockg:individuals/203988 | 2004-11-04 | 23450 |


## See Also

* [https://lod.nal.usda.gov/nalt/9183](https://lod.nal.usda.gov/nalt/9183)



## LinkML Source

<details>

```yaml
name: sockg_startDate
annotations:
  count:
    tag: count
    value: 93567
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '2012-06-05'
    example_object_type: string
    example_predicate: sockg:startDate
    example_subject: sockg:individuals/0
    example_subject_type: sockg_Amendment
- object:
    example_object: '2006-05-08'
    example_object_type: string
    example_predicate: sockg:startDate
    example_subject: sockg:individuals/170955
    example_subject_type: sockg_GrazingManagementEvent
- object:
    example_object: '1987-04-30'
    example_object_type: string
    example_predicate: sockg:startDate
    example_subject: sockg:individuals/336419
    example_subject_type: sockg_Tillage
- object:
    example_object: '2007-04-01'
    example_object_type: string
    example_predicate: sockg:startDate
    example_subject: sockg:individuals/51906
    example_subject_type: sockg_Experiment
- object:
    example_object: '2009-01-01'
    example_object_type: string
    example_predicate: sockg:startDate
    example_subject: sockg:individuals/51937
    example_subject_type: sockg_ExperimentalUnit
- object:
    example_object: '2004-11-04'
    example_object_type: string
    example_predicate: sockg:startDate
    example_subject: sockg:individuals/203988
    example_subject_type: sockg_PlantingEvent
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/9183
rank: 1000
slot_uri: sockg:startDate
alias: sockg_startDate
domain_of:
- sockg_Amendment
- sockg_Experiment
- sockg_ExperimentalUnit
- sockg_GrazingManagementEvent
- sockg_PlantingEvent
- sockg_Tillage
union_of:
- '{''domain'': ''sockg_ExperimentalUnit''}'
- '{''domain'': ''sockg_GrazingManagementEvent''}'
- '{''domain'': ''sockg_WeatherStation''}'
- '{''domain'': ''sockg_Experiment''}'
- '{''domain'': ''sockg_Amendment''}'
range: Any
any_of:
- range: date
- range: string

```
</details>