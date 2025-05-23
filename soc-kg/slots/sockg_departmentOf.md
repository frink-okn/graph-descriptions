

# Slot: No slot (predicate) name specified (sockg_departmentOf)


_No slot (predicate) description specified_






This slot occurs 11 times.


URI: [sockg:departmentOf](https://idir.uta.edu/sockg-ontology/docs/departmentOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgDepartment](../classes/SockgDepartment.md) | A Department represents a specialized division within an agricultural institu... |  yes  |







## Properties

* Range: [SockgOrganization](../classes/SockgOrganization.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Department | sockg_Organization | sockg:individuals/51836 | sockg:individuals/203523 | 11 |




## LinkML Source

<details>

```yaml
name: sockg_departmentOf
annotations:
  count:
    tag: count
    value: 11
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/203523
    example_object_type: sockg_Organization
    example_predicate: sockg:departmentOf
    example_subject: sockg:individuals/51836
    example_subject_type: sockg_Department
from_schema: soc-kg
rank: 1000
domain: sockg_Department
slot_uri: sockg:departmentOf
alias: sockg_departmentOf
domain_of:
- sockg_Department
range: sockg_Organization

```
</details>