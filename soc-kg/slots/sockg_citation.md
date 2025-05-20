

# Slot: No slot (predicate) name specified (sockg_citation)


_No slot (predicate) description specified_






This slot occurs 162 times.


URI: [sockg:citation](https://idir.uta.edu/sockg-ontology/docs/citation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPublication](../classes/SockgPublication.md) | A Publication is a documented work that disseminates findings, research, or i... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Publication | string | sockg:individuals/227447 | Franzluebbers AJ, Stuedemann JA. 2005. Bermudagrass management in the Southern Piedmont USA. VII. Soil-profile organic carbon and total nitrogen. Soil Science Society of America Journal 69, 1455-1462. | 162 |


## See Also

* [https://lod.nal.usda.gov/nalt/305490](https://lod.nal.usda.gov/nalt/305490)



## LinkML Source

<details>

```yaml
name: sockg_citation
annotations:
  count:
    tag: count
    value: 162
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Franzluebbers AJ, Stuedemann JA. 2005. Bermudagrass management
      in the Southern Piedmont USA. VII. Soil-profile organic carbon and total nitrogen.
      Soil Science Society of America Journal 69, 1455-1462.
    example_object_type: string
    example_predicate: sockg:citation
    example_subject: sockg:individuals/227447
    example_subject_type: sockg_Publication
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/305490
rank: 1000
domain: sockg_Publication
slot_uri: sockg:citation
alias: sockg_citation
domain_of:
- sockg_Publication
range: string

```
</details>