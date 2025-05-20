

# Slot: sockg_airTemperatureSd_degC


_No slot (predicate) description specified_






This slot occurs 6790 times.


URI: [sockg:airTemperatureSd_degC](https://idir.uta.edu/sockg-ontology/docs/airTemperatureSd_degC)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGasSample](../classes/SockgGasSample.md) | GasSample represents a collection of measurements related to greenhouse gas e... |  yes  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_GasSample | double | sockg:individuals/123531 | 0.7778175 | 6790 |




## LinkML Source

<details>

```yaml
name: sockg_airTemperatureSd_degC
annotations:
  count:
    tag: count
    value: 6790
description: No slot (predicate) description specified
examples:
- object:
    example_object: '0.7778175'
    example_object_type: double
    example_predicate: sockg:airTemperatureSd_degC
    example_subject: sockg:individuals/123531
    example_subject_type: sockg_GasSample
from_schema: soc-kg
rank: 1000
slot_uri: sockg:airTemperatureSd_degC
alias: sockg_airTemperatureSd_degC
domain_of:
- sockg_GasSample
range: double

```
</details>