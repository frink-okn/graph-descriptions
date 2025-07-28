

# Slot: No slot (predicate) name specified (owl_hasValue)


_No slot (predicate) description specified_






This slot occurs 2 times.


URI: [owl:hasValue](http://www.w3.org/2002/07/owl#hasValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpW3id.orgFioV1Epa-frs#FacilitySiteIdentification](../classes/HttpW3id.orgFioV1Epa-frs#FacilitySiteIdentification.md)&nbsp;or&nbsp;<br />[HttpW3id.orgFioV1Epa-frs#EnvironmentalInterestByProgram](../classes/HttpW3id.orgFioV1Epa-frs#EnvironmentalInterestByProgram.md)&nbsp;or&nbsp;<br />[HttpW3id.orgFioV1Epa-frs#EnvironmentalInterestType](../classes/HttpW3id.orgFioV1Epa-frs#EnvironmentalInterestType.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | http___w3id.org_fio_v1_epa-frs#FacilitySiteIdentification | _:B2eae44cdbebb2dc00571e0a34d8dba01 | http://w3id.org/fio/v1/epa-frs-data#d.EnvironmentalInterestType.Tribalmaster | 2 |
| owl_Restriction | http___w3id.org_fio_v1_epa-frs#EnvironmentalInterestByProgram | _:B2eae44cdbebb2dc00571e0a34d8dba01 | http://w3id.org/fio/v1/epa-frs-data#d.EnvironmentalInterestType.Tribalmaster | 2 |
| owl_Restriction | http___w3id.org_fio_v1_epa-frs#EnvironmentalInterestType | _:B2eae44cdbebb2dc00571e0a34d8dba01 | http://w3id.org/fio/v1/epa-frs-data#d.EnvironmentalInterestType.Tribalmaster | 2 |
| owl_Restriction | owl_Thing | _:B2eae44cdbebb2dc00571e0a34d8dba01 | http://w3id.org/fio/v1/epa-frs-data#d.EnvironmentalInterestType.Tribalmaster | 2 |




## LinkML Source

<details>

```yaml
name: owl_hasValue
annotations:
  count:
    tag: count
    value: 2
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: http://w3id.org/fio/v1/epa-frs-data#d.EnvironmentalInterestType.Tribalmaster
    example_object_type: http___w3id.org_fio_v1_epa-frs#FacilitySiteIdentification
    example_predicate: owl:hasValue
    example_subject: _:B2eae44cdbebb2dc00571e0a34d8dba01
    example_subject_type: owl_Restriction
- object:
    example_object: http://w3id.org/fio/v1/epa-frs-data#d.EnvironmentalInterestType.Tribalmaster
    example_object_type: http___w3id.org_fio_v1_epa-frs#EnvironmentalInterestByProgram
    example_predicate: owl:hasValue
    example_subject: _:B2eae44cdbebb2dc00571e0a34d8dba01
    example_subject_type: owl_Restriction
- object:
    example_object: http://w3id.org/fio/v1/epa-frs-data#d.EnvironmentalInterestType.Tribalmaster
    example_object_type: http___w3id.org_fio_v1_epa-frs#EnvironmentalInterestType
    example_predicate: owl:hasValue
    example_subject: _:B2eae44cdbebb2dc00571e0a34d8dba01
    example_subject_type: owl_Restriction
- object:
    example_object: http://w3id.org/fio/v1/epa-frs-data#d.EnvironmentalInterestType.Tribalmaster
    example_object_type: owl_Thing
    example_predicate: owl:hasValue
    example_subject: _:B2eae44cdbebb2dc00571e0a34d8dba01
    example_subject_type: owl_Restriction
from_schema: fio-kg
rank: 1000
slot_uri: owl:hasValue
alias: owl_hasValue
domain_of:
- owl_Restriction
union_of:
- '{''domain'': ''owl_Restriction''}'
- '{''domain'': ''owl_Class''}'
- '{''domain'': ''rdfs_Class''}'
range: Any
any_of:
- range: http___w3id.org_fio_v1_epa-frs#FacilitySiteIdentification
- range: http___w3id.org_fio_v1_epa-frs#EnvironmentalInterestByProgram
- range: http___w3id.org_fio_v1_epa-frs#EnvironmentalInterestType
- range: owl_Thing

```
</details>