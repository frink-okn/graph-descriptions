

# Slot: sockg_soilMoisture_percent_volume


_No slot (predicate) description specified_






This slot occurs 107000 times.


URI: [sockg:soilMoisture_percent_volume](https://idir.uta.edu/sockg-ontology/docs/soilMoisture_percent_volume)



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
| sockg_GasSample | double | sockg:individuals/100000 | 22.5 | 107000 |




## LinkML Source

<details>

```yaml
name: sockg_soilMoisture_percent_volume
annotations:
  count:
    tag: count
    value: 107000
description: No slot (predicate) description specified
examples:
- object:
    example_object: '22.5'
    example_object_type: double
    example_predicate: sockg:soilMoisture_percent_volume
    example_subject: sockg:individuals/100000
    example_subject_type: sockg_GasSample
from_schema: soc-kg
rank: 1000
slot_uri: sockg:soilMoisture_percent_volume
alias: sockg_soilMoisture_percent_volume
domain_of:
- sockg_GasSample
range: double

```
</details>