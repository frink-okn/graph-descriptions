

# Slot: No slot (predicate) name specified (sockg_unitGrainWeight_mg)


_No slot (predicate) description specified_






This slot occurs 120 times.


URI: [sockg:unitGrainWeight_mg](https://idir.uta.edu/sockg-ontology/docs/unitGrainWeight_mg)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgHarvest](../classes/SockgHarvest.md) | Harvest represents the process of collecting mature crops from the fields, wi... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Harvest | double | sockg:individuals/173872 | 894.7 | 120 |




## LinkML Source

<details>

```yaml
name: sockg_unitGrainWeight_mg
annotations:
  count:
    tag: count
    value: 120
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '894.7'
    example_object_type: double
    example_predicate: sockg:unitGrainWeight_mg
    example_subject: sockg:individuals/173872
    example_subject_type: sockg_Harvest
from_schema: soc-kg
rank: 1000
domain: sockg_Harvest
slot_uri: sockg:unitGrainWeight_mg
alias: sockg_unitGrainWeight_mg
domain_of:
- sockg_Harvest
range: Any
any_of:
- range: float
- range: double

```
</details>