

# Slot: sockg_soilMoistureDepth_cm


_No slot (predicate) description specified_






This slot occurs 107354 times.


URI: [sockg:soilMoistureDepth_cm](https://idir.uta.edu/sockg-ontology/docs/soilMoistureDepth_cm)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGasSample](../classes/SockgGasSample.md) | GasSample represents a collection of measurements related to greenhouse gas e... |  yes  |







## Properties

* Range: [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_GasSample | integer | sockg:individuals/100000 | 6 | 107354 |




## LinkML Source

<details>

```yaml
name: sockg_soilMoistureDepth_cm
annotations:
  count:
    tag: count
    value: 107354
description: No slot (predicate) description specified
examples:
- object:
    example_object: '6'
    example_object_type: integer
    example_predicate: sockg:soilMoistureDepth_cm
    example_subject: sockg:individuals/100000
    example_subject_type: sockg_GasSample
from_schema: soc-kg
rank: 1000
slot_uri: sockg:soilMoistureDepth_cm
alias: sockg_soilMoistureDepth_cm
domain_of:
- sockg_GasSample
range: integer

```
</details>