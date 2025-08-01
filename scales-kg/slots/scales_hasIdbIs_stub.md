

# Slot: scales_hasIdbIs_stub


_No slot (predicate) description specified_






This slot occurs 824286 times.


URI: [scales:hasIdbIs_stub](http://schemas.scales-okn.org/rdf/scales#hasIdbIs_stub)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | boolean | scales:/CivilCase/akd;;1:16-cv-00001 | false | 702501 |
| scales_CriminalCase | boolean | scales:/CriminalCase/akd;;1:16-cr-00001 | false | 121785 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbIs_stub
annotations:
  count:
    tag: count
    value: 824286
description: No slot (predicate) description specified
examples:
- object:
    example_object: 'false'
    example_object_type: boolean
    example_predicate: scales:hasIdbIs_stub
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: 'false'
    example_object_type: boolean
    example_predicate: scales:hasIdbIs_stub
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbIs_stub
alias: scales_hasIdbIs_stub
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: boolean

```
</details>