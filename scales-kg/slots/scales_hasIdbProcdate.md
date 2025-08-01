

# Slot: scales_hasIdbProcdate


_No slot (predicate) description specified_






This slot occurs 121785 times.


URI: [scales:hasIdbProcdate](http://schemas.scales-okn.org/rdf/scales#hasIdbProcdate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CriminalCase | string | scales:/CriminalCase/akd;;1:16-cr-00001 | 02/03/2016 | 121785 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbProcdate
annotations:
  count:
    tag: count
    value: 121785
description: No slot (predicate) description specified
examples:
- object:
    example_object: 02/03/2016
    example_object_type: string
    example_predicate: scales:hasIdbProcdate
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbProcdate
alias: scales_hasIdbProcdate
domain_of:
- scales_CriminalCase
range: string

```
</details>