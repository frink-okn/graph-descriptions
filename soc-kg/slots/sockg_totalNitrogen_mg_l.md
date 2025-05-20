

# Slot: sockg_totalNitrogen_mg_l


_No slot (predicate) description specified_






This slot occurs 667 times.


URI: [sockg:totalNitrogen_mg_l](https://idir.uta.edu/sockg-ontology/docs/totalNitrogen_mg_l)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | WaterQualityConc represents the concentration of various water quality parame... |  yes  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WaterQualityConc | double | sockg:individuals/365805 | 11.6 | 667 |




## LinkML Source

<details>

```yaml
name: sockg_totalNitrogen_mg_l
annotations:
  count:
    tag: count
    value: 667
description: No slot (predicate) description specified
examples:
- object:
    example_object: '11.6'
    example_object_type: double
    example_predicate: sockg:totalNitrogen_mg_l
    example_subject: sockg:individuals/365805
    example_subject_type: sockg_WaterQualityConc
from_schema: soc-kg
rank: 1000
slot_uri: sockg:totalNitrogen_mg_l
alias: sockg_totalNitrogen_mg_l
domain_of:
- sockg_WaterQualityConc
range: double

```
</details>