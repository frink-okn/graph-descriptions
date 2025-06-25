

# Slot: sockg_soilMoistureSd_percent_volume


_No slot (predicate) description specified_






This slot occurs 5038 times.


URI: [sockg:soilMoistureSd_percent_volume](https://idir.uta.edu/sockg-ontology/docs/soilMoistureSd_percent_volume)



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
| sockg_GasSample | double | sockg:individuals/114567 | 4.24 | 5038 |




## LinkML Source

<details>

```yaml
name: sockg_soilMoistureSd_percent_volume
annotations:
  count:
    tag: count
    value: 5038
description: No slot (predicate) description specified
examples:
- object:
    example_object: '4.24'
    example_object_type: double
    example_predicate: sockg:soilMoistureSd_percent_volume
    example_subject: sockg:individuals/114567
    example_subject_type: sockg_GasSample
from_schema: soc-kg
rank: 1000
slot_uri: sockg:soilMoistureSd_percent_volume
alias: sockg_soilMoistureSd_percent_volume
domain_of:
- sockg_GasSample
range: double

```
</details>