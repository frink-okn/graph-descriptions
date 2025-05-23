

# Slot: sockg_soilCoverTimingDescriptor


_No slot (predicate) description specified_






This slot occurs 1034 times.


URI: [sockg:soilCoverTimingDescriptor](https://idir.uta.edu/sockg-ontology/docs/soilCoverTimingDescriptor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilCover](../classes/SockgSoilCover.md) | SoilCover refers to the layer of organic and inorganic materials that covers ... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilCover | string | sockg:individuals/307284 | Post harvest (2-4 weeks after harvest) | 1034 |




## LinkML Source

<details>

```yaml
name: sockg_soilCoverTimingDescriptor
annotations:
  count:
    tag: count
    value: 1034
description: No slot (predicate) description specified
examples:
- object:
    example_object: Post harvest (2-4 weeks after harvest)
    example_object_type: string
    example_predicate: sockg:soilCoverTimingDescriptor
    example_subject: sockg:individuals/307284
    example_subject_type: sockg_SoilCover
from_schema: soc-kg
rank: 1000
slot_uri: sockg:soilCoverTimingDescriptor
alias: sockg_soilCoverTimingDescriptor
domain_of:
- sockg_SoilCover
range: string

```
</details>