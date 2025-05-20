

# Slot: No slot (predicate) name specified (sockg_totalPesticideAmount_kg_per_ha)


_No slot (predicate) description specified_






This slot occurs 353 times.


URI: [sockg:totalPesticideAmount_kg_per_ha](https://idir.uta.edu/sockg-ontology/docs/totalPesticideAmount_kg_per_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPesticide](../classes/SockgPesticide.md) | Pesticides are substances used in agriculture to manage pests and diseases th... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Pesticide | double | sockg:individuals/203632 | 0.0 | 353 |




## LinkML Source

<details>

```yaml
name: sockg_totalPesticideAmount_kg_per_ha
annotations:
  count:
    tag: count
    value: 353
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.0'
    example_object_type: double
    example_predicate: sockg:totalPesticideAmount_kg_per_ha
    example_subject: sockg:individuals/203632
    example_subject_type: sockg_Pesticide
from_schema: soc-kg
rank: 1000
domain: sockg_Pesticide
slot_uri: sockg:totalPesticideAmount_kg_per_ha
alias: sockg_totalPesticideAmount_kg_per_ha
domain_of:
- sockg_Pesticide
range: Any
any_of:
- range: double
- range: float

```
</details>