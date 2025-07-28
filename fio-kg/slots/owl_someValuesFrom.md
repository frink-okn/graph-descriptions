

# Slot: No slot (predicate) name specified (owl_someValuesFrom)


_No slot (predicate) description specified_






This slot occurs 14 times.


URI: [owl:someValuesFrom](http://www.w3.org/2002/07/owl#someValuesFrom)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[OwlClass](../classes/OwlClass.md)&nbsp;or&nbsp;<br />[RdfsClass](../classes/RdfsClass.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | owl_Thing | _:B010019df0d645bc4b640e83c5a648a6d | http://w3id.org/fio/v1/epa-frs#ReportingSystem | 13 |
| owl_Restriction | owl_Class | _:B010019df0d645bc4b640e83c5a648a6d | http://w3id.org/fio/v1/epa-frs#ReportingSystem | 13 |
| owl_Restriction | rdfs_Class | _:B010019df0d645bc4b640e83c5a648a6d | http://w3id.org/fio/v1/epa-frs#ReportingSystem | 13 |
| owl_Restriction | uri | _:Bcea60150512b327394ca7037688906b9 | _:B1b00703a3b4a6351310cd78550f4f30c | 1 |




## LinkML Source

<details>

```yaml
name: owl_someValuesFrom
annotations:
  count:
    tag: count
    value: 14
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: http://w3id.org/fio/v1/epa-frs#ReportingSystem
    example_object_type: owl_Thing
    example_predicate: owl:someValuesFrom
    example_subject: _:B010019df0d645bc4b640e83c5a648a6d
    example_subject_type: owl_Restriction
- object:
    example_object: http://w3id.org/fio/v1/epa-frs#ReportingSystem
    example_object_type: owl_Class
    example_predicate: owl:someValuesFrom
    example_subject: _:B010019df0d645bc4b640e83c5a648a6d
    example_subject_type: owl_Restriction
- object:
    example_object: http://w3id.org/fio/v1/epa-frs#ReportingSystem
    example_object_type: rdfs_Class
    example_predicate: owl:someValuesFrom
    example_subject: _:B010019df0d645bc4b640e83c5a648a6d
    example_subject_type: owl_Restriction
- object:
    example_object: _:B1b00703a3b4a6351310cd78550f4f30c
    example_object_type: uri
    example_predicate: owl:someValuesFrom
    example_subject: _:Bcea60150512b327394ca7037688906b9
    example_subject_type: owl_Restriction
from_schema: fio-kg
rank: 1000
slot_uri: owl:someValuesFrom
alias: owl_someValuesFrom
domain_of:
- owl_Restriction
union_of:
- '{''domain'': ''owl_Restriction''}'
- '{''domain'': ''owl_Class''}'
- '{''domain'': ''rdfs_Class''}'
range: Any
any_of:
- range: owl_Thing
- range: uri
- range: owl_Class
- range: rdfs_Class

```
</details>