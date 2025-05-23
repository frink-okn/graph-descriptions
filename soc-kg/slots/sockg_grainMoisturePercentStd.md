

# Slot: sockg_grainMoisturePercentStd


_No slot (predicate) description specified_






This slot occurs 30 times.


URI: [sockg:grainMoisturePercentStd](https://idir.uta.edu/sockg-ontology/docs/grainMoisturePercentStd)



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
| sockg_Harvest | double | sockg:individuals/182268 | 0.1 | 30 |




## LinkML Source

<details>

```yaml
name: sockg_grainMoisturePercentStd
annotations:
  count:
    tag: count
    value: 30
description: No slot (predicate) description specified
examples:
- object:
    example_object: '0.1'
    example_object_type: double
    example_predicate: sockg:grainMoisturePercentStd
    example_subject: sockg:individuals/182268
    example_subject_type: sockg_Harvest
from_schema: soc-kg
rank: 1000
slot_uri: sockg:grainMoisturePercentStd
alias: sockg_grainMoisturePercentStd
domain_of:
- sockg_Harvest
range: double

```
</details>