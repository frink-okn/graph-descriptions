

# Slot: sosa_resultTime


_No slot (predicate) description specified_






This slot occurs 578715 times.


URI: [sosa:resultTime](http://www.w3.org/ns/sosa/resultTime)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-PFAS-Observation | date | me_egad_data:observation.AAL210144001R.20210112.1763231 | 2021-01-18 | 578715 |




## LinkML Source

<details>

```yaml
name: sosa_resultTime
annotations:
  count:
    tag: count
    value: 578715
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2021-01-18'
    example_object_type: date
    example_predicate: sosa:resultTime
    example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
from_schema: sawgraph-kg
rank: 1000
slot_uri: sosa:resultTime
alias: sosa_resultTime
domain_of:
- me_egad_EGAD-PFAS-Observation
range: date

```
</details>