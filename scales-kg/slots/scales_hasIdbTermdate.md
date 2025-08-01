

# Slot: scales_hasIdbTermdate


_No slot (predicate) description specified_






This slot occurs 712609 times.


URI: [scales:hasIdbTermdate](http://schemas.scales-okn.org/rdf/scales#hasIdbTermdate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | datetime | scales:/CivilCase/akd;;1:16-cv-00001 | 2018-05-21T00:00:00 | 662201 |
| scales_CriminalCase | datetime | scales:/CriminalCase/akd;;1:16-cr-00001 | 2016-08-01T00:00:00 | 50408 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbTermdate
annotations:
  count:
    tag: count
    value: 712609
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2018-05-21T00:00:00'
    example_object_type: datetime
    example_predicate: scales:hasIdbTermdate
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: '2016-08-01T00:00:00'
    example_object_type: datetime
    example_predicate: scales:hasIdbTermdate
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTermdate
alias: scales_hasIdbTermdate
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: datetime

```
</details>