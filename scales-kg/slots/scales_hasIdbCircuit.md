

# Slot: scales_hasIdbCircuit


_No slot (predicate) description specified_






This slot occurs 824286 times.


URI: [scales:hasIdbCircuit](http://schemas.scales-okn.org/rdf/scales#hasIdbCircuit)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | double | scales:/CivilCase/akd;;1:16-cv-00001 | 9.0 | 702501 |
| scales_CriminalCase | double | scales:/CriminalCase/akd;;1:16-cr-00001 | 9.0 | 121785 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbCircuit
annotations:
  count:
    tag: count
    value: 824286
description: No slot (predicate) description specified
examples:
- object:
    example_object: '9.0'
    example_object_type: double
    example_predicate: scales:hasIdbCircuit
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: '9.0'
    example_object_type: double
    example_predicate: scales:hasIdbCircuit
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbCircuit
alias: scales_hasIdbCircuit
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: double

```
</details>