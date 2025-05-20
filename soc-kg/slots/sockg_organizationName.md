

# Slot: No slot (predicate) name specified (sockg_organizationName)


_No slot (predicate) description specified_






This slot occurs 95 times.


URI: [sockg:organizationName](https://idir.uta.edu/sockg-ontology/docs/organizationName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgOrganization](../classes/SockgOrganization.md) | An Organization is a structured group of individuals working together to achi... |  yes  |
| [SockgPerson](../classes/SockgPerson.md) | A Person represents an individual involved in agricultural activities, servin... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Organization | string | sockg:individuals/203523 | USDA-ARS | 7 |
| sockg_Person | string | sockg:individuals/203534 | Soil Plant Nutrient Research Unit | 88 |


## See Also

* [https://lod.nal.usda.gov/nalt/13189](https://lod.nal.usda.gov/nalt/13189)



## LinkML Source

<details>

```yaml
name: sockg_organizationName
annotations:
  count:
    tag: count
    value: 95
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: USDA-ARS
    example_object_type: string
    example_predicate: sockg:organizationName
    example_subject: sockg:individuals/203523
    example_subject_type: sockg_Organization
- object:
    example_object: Soil Plant Nutrient Research Unit
    example_object_type: string
    example_predicate: sockg:organizationName
    example_subject: sockg:individuals/203534
    example_subject_type: sockg_Person
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/13189
rank: 1000
domain: sockg_Organization
slot_uri: sockg:organizationName
alias: sockg_organizationName
domain_of:
- sockg_Organization
- sockg_Person
range: string

```
</details>