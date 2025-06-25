

# Slot: No slot (predicate) name specified (sockg_harvestedFrac)


_No slot (predicate) description specified_






This slot occurs 18047 times.


URI: [sockg:harvestedFrac](https://idir.uta.edu/sockg-ontology/docs/harvestedFrac)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgHarvest](../classes/SockgHarvest.md) | Harvest represents the process of collecting mature crops from the fields, wi... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Harvest | string | sockg:individuals/172906 | Grain | 18047 |


## See Also

* [https://lod.nal.usda.gov/nalt/30174](https://lod.nal.usda.gov/nalt/30174)



## LinkML Source

<details>

```yaml
name: sockg_harvestedFrac
annotations:
  count:
    tag: count
    value: 18047
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Grain
    example_object_type: string
    example_predicate: sockg:harvestedFrac
    example_subject: sockg:individuals/172906
    example_subject_type: sockg_Harvest
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/30174
rank: 1000
domain: sockg_Harvest
slot_uri: sockg:harvestedFrac
alias: sockg_harvestedFrac
domain_of:
- sockg_Harvest
range: string

```
</details>