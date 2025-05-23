

# Slot: No slot (predicate) name specified (sockg_chamberPlacement)


_No slot (predicate) description specified_






This slot occurs 103543 times.


URI: [sockg:chamberPlacement](https://idir.uta.edu/sockg-ontology/docs/chamberPlacement)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGasSample](../classes/SockgGasSample.md) | GasSample represents a collection of measurements related to greenhouse gas e... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_GasSample | string | sockg:individuals/100000 | Rangeland | 103543 |




## LinkML Source

<details>

```yaml
name: sockg_chamberPlacement
annotations:
  count:
    tag: count
    value: 103543
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Rangeland
    example_object_type: string
    example_predicate: sockg:chamberPlacement
    example_subject: sockg:individuals/100000
    example_subject_type: sockg_GasSample
from_schema: soc-kg
rank: 1000
domain: sockg_GasSample
slot_uri: sockg:chamberPlacement
alias: sockg_chamberPlacement
domain_of:
- sockg_GasSample
range: string

```
</details>