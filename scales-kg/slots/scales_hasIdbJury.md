

# Slot: scales_hasIdbJury


_No slot (predicate) description specified_






This slot occurs 702501 times.


URI: [scales:hasIdbJury](http://schemas.scales-okn.org/rdf/scales#hasIdbJury)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | string | scales:/CivilCase/akd;;1:16-cv-00001 | N | 685586 |
| scales_CivilCase | integer | scales:/CivilCase/ilnd;;1:02-cv-00001 | -8 | 16915 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbJury
annotations:
  count:
    tag: count
    value: 702501
description: No slot (predicate) description specified
examples:
- object:
    example_object: N
    example_object_type: string
    example_predicate: scales:hasIdbJury
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: '-8'
    example_object_type: integer
    example_predicate: scales:hasIdbJury
    example_subject: scales:/CivilCase/ilnd;;1:02-cv-00001
    example_subject_type: scales_CivilCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbJury
alias: scales_hasIdbJury
domain_of:
- scales_CivilCase
range: Any
any_of:
- range: string
- range: integer

```
</details>