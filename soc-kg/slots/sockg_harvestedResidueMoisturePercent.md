

# Slot: sockg_harvestedResidueMoisturePercent


_No slot (predicate) description specified_






This slot occurs 1086 times.


URI: [sockg:harvestedResidueMoisturePercent](https://idir.uta.edu/sockg-ontology/docs/harvestedResidueMoisturePercent)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgHarvest](../classes/SockgHarvest.md) | Harvest represents the process of collecting mature crops from the fields, wi... |  yes  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Harvest | double | sockg:individuals/173007 | 67.86667 | 1086 |




## LinkML Source

<details>

```yaml
name: sockg_harvestedResidueMoisturePercent
annotations:
  count:
    tag: count
    value: 1086
description: No slot (predicate) description specified
examples:
- object:
    example_object: '67.86667'
    example_object_type: double
    example_predicate: sockg:harvestedResidueMoisturePercent
    example_subject: sockg:individuals/173007
    example_subject_type: sockg_Harvest
from_schema: soc-kg
rank: 1000
slot_uri: sockg:harvestedResidueMoisturePercent
alias: sockg_harvestedResidueMoisturePercent
domain_of:
- sockg_Harvest
range: double

```
</details>