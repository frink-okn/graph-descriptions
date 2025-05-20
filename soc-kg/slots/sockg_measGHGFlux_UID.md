

# Slot: No slot (predicate) name specified (sockg_measGHGFlux_UID)


_No slot (predicate) description specified_






This slot occurs 107354 times.


URI: [sockg:measGHGFlux_UID](https://idir.uta.edu/sockg-ontology/docs/measGHGFlux_UID)



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
| sockg_GasSample | string | sockg:individuals/100000 | AgCros_NDMAHGPE_TANURExclosure1_2005-06-28_nan_Rangeland | 107354 |




## LinkML Source

<details>

```yaml
name: sockg_measGHGFlux_UID
annotations:
  count:
    tag: count
    value: 107354
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_NDMAHGPE_TANURExclosure1_2005-06-28_nan_Rangeland
    example_object_type: string
    example_predicate: sockg:measGHGFlux_UID
    example_subject: sockg:individuals/100000
    example_subject_type: sockg_GasSample
from_schema: soc-kg
rank: 1000
domain: sockg_GasSample
slot_uri: sockg:measGHGFlux_UID
alias: sockg_measGHGFlux_UID
domain_of:
- sockg_GasSample
range: string

```
</details>