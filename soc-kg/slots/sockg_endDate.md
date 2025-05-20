

# Slot: No slot (predicate) name specified (sockg_endDate)


_No slot (predicate) description specified_






This slot occurs 3951 times.


URI: [sockg:endDate](https://idir.uta.edu/sockg-ontology/docs/endDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGrazingManagementEvent](../classes/SockgGrazingManagementEvent.md) | A GrazingManagementEvent represents a specific instance of land management pr... |  yes  |
| [SockgExperiment](../classes/SockgExperiment.md) | An Experiment is a structured investigation carried out to observe and analyz... |  yes  |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:date](http://www.w3.org/2001/XMLSchema#date)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_GrazingManagementEvent | string | sockg:individuals/170955 | 2006-05-12 | 1951 |
| sockg_Experiment | string | sockg:individuals/51906 | 2016-11-01 | 55 |
| sockg_ExperimentalUnit | string | sockg:individuals/51937 | 2011-12-31 | 1945 |


## See Also

* [https://lod.nal.usda.gov/nalt/9183](https://lod.nal.usda.gov/nalt/9183)



## LinkML Source

<details>

```yaml
name: sockg_endDate
annotations:
  count:
    tag: count
    value: 3951
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '2006-05-12'
    example_object_type: string
    example_predicate: sockg:endDate
    example_subject: sockg:individuals/170955
    example_subject_type: sockg_GrazingManagementEvent
- object:
    example_object: '2016-11-01'
    example_object_type: string
    example_predicate: sockg:endDate
    example_subject: sockg:individuals/51906
    example_subject_type: sockg_Experiment
- object:
    example_object: '2011-12-31'
    example_object_type: string
    example_predicate: sockg:endDate
    example_subject: sockg:individuals/51937
    example_subject_type: sockg_ExperimentalUnit
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/9183
rank: 1000
slot_uri: sockg:endDate
alias: sockg_endDate
domain_of:
- sockg_Experiment
- sockg_ExperimentalUnit
- sockg_GrazingManagementEvent
union_of:
- '{''domain'': ''sockg_Amendment''}'
- '{''domain'': ''sockg_ExperimentalUnit''}'
- '{''domain'': ''sockg_GrazingManagementEvent''}'
- '{''domain'': ''sockg_Experiment''}'
range: Any
any_of:
- range: date
- range: string

```
</details>