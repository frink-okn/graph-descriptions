

# Slot: No slot (predicate) name specified (sockg_measSoilBiol_UID)


_No slot (predicate) description specified_






This slot occurs 18222 times.


URI: [sockg:measSoilBiol_UID](https://idir.uta.edu/sockg-ontology/docs/measSoilBiol_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilBiologicalSample](../classes/SockgSoilBiologicalSample.md) | SoilBiologicalSample represents a collection of measurements related to micro... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilBiologicalSample | string | sockg:individuals/235229 | AgCros_GAJPCSR1_B2P105F3H1X600Y390_1994-04-11_0_2 | 18222 |




## LinkML Source

<details>

```yaml
name: sockg_measSoilBiol_UID
annotations:
  count:
    tag: count
    value: 18222
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_GAJPCSR1_B2P105F3H1X600Y390_1994-04-11_0_2
    example_object_type: string
    example_predicate: sockg:measSoilBiol_UID
    example_subject: sockg:individuals/235229
    example_subject_type: sockg_SoilBiologicalSample
from_schema: soc-kg
rank: 1000
domain: sockg_SoilBiologicalSample
slot_uri: sockg:measSoilBiol_UID
alias: sockg_measSoilBiol_UID
domain_of:
- sockg_SoilBiologicalSample
range: string

```
</details>