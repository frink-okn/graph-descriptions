

# Slot: No slot (predicate) name specified (kwgo_administrativePartOf)


_No slot (predicate) description specified_






This slot occurs 2345 times.


URI: [kwgo:administrativePartOf](http://stko-kwg.geog.ucsb.edu/lod/ontology/administrativePartOf)



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

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion1](../classes/KwgoAdministrativeRegion1.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| kwgo_AdministrativeRegion_1 | owl_Thing | kwgr:administrativeRegion.USA.17 | kwgr:administrativeRegion.USA | 2 |
| owl_Thing | owl_Thing | kwgr:administrativeRegion.USA.17 | kwgr:administrativeRegion.USA | 2345 |
| kwgo_AdministrativeRegion_2 | kwgo_AdministrativeRegion_1 | kwgr:administrativeRegion.USA.17001 | kwgr:administrativeRegion.USA.17 | 118 |
| kwgo_AdministrativeRegion_2 | owl_Thing | kwgr:administrativeRegion.USA.17001 | kwgr:administrativeRegion.USA.17 | 118 |
| owl_Thing | kwgo_AdministrativeRegion_1 | kwgr:administrativeRegion.USA.17001 | kwgr:administrativeRegion.USA.17 | 118 |
| owl_Thing | kwgo_AdministrativeRegion_2 | https://datacommons.org/browser/geoId/1700105742 | kwgr:administrativeRegion.USA.17001 | 2225 |
| kwgo_AdministrativeRegion_3 | kwgo_AdministrativeRegion_2 | https://datacommons.org/browser/geoId/1700105742 | kwgr:administrativeRegion.USA.17001 | 2225 |
| kwgo_AdministrativeRegion_3 | owl_Thing | https://datacommons.org/browser/geoId/1700105742 | kwgr:administrativeRegion.USA.17001 | 2225 |




## LinkML Source

<details>

```yaml
name: kwgo_administrativePartOf
annotations:
  count:
    tag: count
    value: 2345
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: kwgr:administrativeRegion.USA
    example_object_type: owl_Thing
    example_predicate: kwgo:administrativePartOf
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: kwgo_AdministrativeRegion_1
- object:
    example_object: kwgr:administrativeRegion.USA
    example_object_type: owl_Thing
    example_predicate: kwgo:administrativePartOf
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:administrativeRegion.USA.17
    example_object_type: kwgo_AdministrativeRegion_1
    example_predicate: kwgo:administrativePartOf
    example_subject: kwgr:administrativeRegion.USA.17001
    example_subject_type: kwgo_AdministrativeRegion_2
- object:
    example_object: kwgr:administrativeRegion.USA.17
    example_object_type: owl_Thing
    example_predicate: kwgo:administrativePartOf
    example_subject: kwgr:administrativeRegion.USA.17001
    example_subject_type: kwgo_AdministrativeRegion_2
- object:
    example_object: kwgr:administrativeRegion.USA.17
    example_object_type: kwgo_AdministrativeRegion_1
    example_predicate: kwgo:administrativePartOf
    example_subject: kwgr:administrativeRegion.USA.17001
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:administrativeRegion.USA.17001
    example_object_type: kwgo_AdministrativeRegion_2
    example_predicate: kwgo:administrativePartOf
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:administrativeRegion.USA.17001
    example_object_type: kwgo_AdministrativeRegion_2
    example_predicate: kwgo:administrativePartOf
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: kwgo_AdministrativeRegion_3
- object:
    example_object: kwgr:administrativeRegion.USA.17001
    example_object_type: owl_Thing
    example_predicate: kwgo:administrativePartOf
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: kwgo_AdministrativeRegion_3
from_schema: spatial-kg
rank: 1000
slot_uri: kwgo:administrativePartOf
alias: kwgo_administrativePartOf
domain_of:
- kwgo_AdministrativeRegion_1
- kwgo_AdministrativeRegion_2
- kwgo_AdministrativeRegion_3
- owl_Thing
range: Any
any_of:
- range: owl_Thing
- range: kwgo_AdministrativeRegion_2
- range: kwgo_AdministrativeRegion_1

```
</details>