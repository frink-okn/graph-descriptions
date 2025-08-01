

# Slot: scales_hasMemberCase


_No slot (predicate) description specified_






This slot occurs 83603 times.


URI: [scales:hasMemberCase](http://schemas.scales-okn.org/rdf/scales#hasMemberCase)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [ScalesCivilCase](../classes/ScalesCivilCase.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | scales_CivilCase | scales:/CivilCase/akd;;3:16-cv-00172 | scales:/CivilCase/akd;;3:16-cv-00183 | 15136 |
| None | scales_CivilCase | scales:/CivilCase/almd;;2:15-cv-00852 | scales:/CivilCase/almd;;2:16-cv-00342 | 68466 |
| scales_CriminalCase | scales_CivilCase | scales:/CriminalCase/ohsd;;1:16-cr-00004 | scales:/CivilCase/ohsd;;1:16-cv-00014 | 1 |




## LinkML Source

<details>

```yaml
name: scales_hasMemberCase
annotations:
  count:
    tag: count
    value: 83603
  scales_CivilCase:
    tag: scales_CivilCase
    value: 68466
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/CivilCase/akd;;3:16-cv-00183
    example_object_type: scales_CivilCase
    example_predicate: scales:hasMemberCase
    example_subject: scales:/CivilCase/akd;;3:16-cv-00172
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:/CivilCase/almd;;2:16-cv-00342
    example_object_type: scales_CivilCase
    example_predicate: scales:hasMemberCase
    example_subject: scales:/CivilCase/almd;;2:15-cv-00852
    example_subject_type: None
- object:
    example_object: scales:/CivilCase/ohsd;;1:16-cv-00014
    example_object_type: scales_CivilCase
    example_predicate: scales:hasMemberCase
    example_subject: scales:/CriminalCase/ohsd;;1:16-cr-00004
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasMemberCase
alias: scales_hasMemberCase
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: scales_CivilCase

```
</details>