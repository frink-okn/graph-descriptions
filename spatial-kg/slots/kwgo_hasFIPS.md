

# Slot: No slot (predicate) name specified (kwgo_hasFIPS)


_No slot (predicate) description specified_






This slot occurs 2345 times.


URI: [kwgo:hasFIPS](http://stko-kwg.geog.ucsb.edu/lod/ontology/hasFIPS)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [KwgoAdministrativeRegion1](../classes/KwgoAdministrativeRegion1.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [KwgoAdministrativeRegion3](../classes/KwgoAdministrativeRegion3.md) | No class (type) description specified |  yes  |
| [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| kwgo_AdministrativeRegion_1 | string | kwgr:administrativeRegion.USA.17 | 17 | 2 |
| owl_Thing | string | kwgr:administrativeRegion.USA.17 | 17 | 2345 |
| kwgo_AdministrativeRegion_2 | string | kwgr:administrativeRegion.USA.17001 | 17001 | 118 |
| kwgo_AdministrativeRegion_3 | string | https://datacommons.org/browser/geoId/1700105742 | 1700105742 | 2225 |




## LinkML Source

<details>

```yaml
name: kwgo_hasFIPS
annotations:
  count:
    tag: count
    value: 2345
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '17'
    example_object_type: string
    example_predicate: kwgo:hasFIPS
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: kwgo_AdministrativeRegion_1
- object:
    example_object: '17'
    example_object_type: string
    example_predicate: kwgo:hasFIPS
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: owl_Thing
- object:
    example_object: '17001'
    example_object_type: string
    example_predicate: kwgo:hasFIPS
    example_subject: kwgr:administrativeRegion.USA.17001
    example_subject_type: kwgo_AdministrativeRegion_2
- object:
    example_object: '1700105742'
    example_object_type: string
    example_predicate: kwgo:hasFIPS
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: kwgo_AdministrativeRegion_3
from_schema: spatial-kg
rank: 1000
slot_uri: kwgo:hasFIPS
alias: kwgo_hasFIPS
domain_of:
- kwgo_AdministrativeRegion_1
- kwgo_AdministrativeRegion_2
- kwgo_AdministrativeRegion_3
- owl_Thing
range: string

```
</details>