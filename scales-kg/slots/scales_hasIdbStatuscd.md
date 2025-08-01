

# Slot: scales_hasIdbStatuscd


_No slot (predicate) description specified_






This slot occurs 824285 times.


URI: [scales:hasIdbStatuscd](http://schemas.scales-okn.org/rdf/scales#hasIdbStatuscd)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | string | scales:/CivilCase/akd;;1:16-cv-00001 | L | 702500 |
| scales_CriminalCase | string | scales:/CriminalCase/akd;;1:16-cr-00001 | J | 121785 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbStatuscd
annotations:
  count:
    tag: count
    value: 824285
description: No slot (predicate) description specified
examples:
- object:
    example_object: L
    example_object_type: string
    example_predicate: scales:hasIdbStatuscd
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: J
    example_object_type: string
    example_predicate: scales:hasIdbStatuscd
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbStatuscd
alias: scales_hasIdbStatuscd
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: string

```
</details>