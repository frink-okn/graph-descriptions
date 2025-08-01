

# Slot: scales_hasIdbTermoff


_No slot (predicate) description specified_






This slot occurs 121785 times.


URI: [scales:hasIdbTermoff](http://schemas.scales-okn.org/rdf/scales#hasIdbTermoff)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CriminalCase | integer | scales:/CriminalCase/akd;;1:16-cr-00001 | 1 | 113263 |
| scales_CriminalCase | string | scales:/CriminalCase/cand;;1:16-cr-00325 | 1 | 8522 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbTermoff
annotations:
  count:
    tag: count
    value: 121785
description: No slot (predicate) description specified
examples:
- object:
    example_object: '1'
    example_object_type: integer
    example_predicate: scales:hasIdbTermoff
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
- object:
    example_object: '1'
    example_object_type: string
    example_predicate: scales:hasIdbTermoff
    example_subject: scales:/CriminalCase/cand;;1:16-cr-00325
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTermoff
alias: scales_hasIdbTermoff
domain_of:
- scales_CriminalCase
range: Any
any_of:
- range: string
- range: integer

```
</details>