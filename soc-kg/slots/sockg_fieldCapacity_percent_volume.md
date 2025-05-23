

# Slot: sockg_fieldCapacity_percent_volume


_No slot (predicate) description specified_






This slot occurs 24 times.


URI: [sockg:fieldCapacity_percent_volume](https://idir.uta.edu/sockg-ontology/docs/fieldCapacity_percent_volume)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilPhysicalSample](../classes/SockgSoilPhysicalSample.md) | SoilPhysicalSample represents a comprehensive analysis of soil characteristic... |  yes  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilPhysicalSample | double | sockg:individuals/334651 | 29.2 | 24 |




## LinkML Source

<details>

```yaml
name: sockg_fieldCapacity_percent_volume
annotations:
  count:
    tag: count
    value: 24
description: No slot (predicate) description specified
examples:
- object:
    example_object: '29.2'
    example_object_type: double
    example_predicate: sockg:fieldCapacity_percent_volume
    example_subject: sockg:individuals/334651
    example_subject_type: sockg_SoilPhysicalSample
from_schema: soc-kg
rank: 1000
slot_uri: sockg:fieldCapacity_percent_volume
alias: sockg_fieldCapacity_percent_volume
domain_of:
- sockg_SoilPhysicalSample
range: double

```
</details>