

# Slot: No slot (predicate) name specified (sockg_departmentName)


_No slot (predicate) description specified_






This slot occurs 33 times.


URI: [sockg:departmentName](https://idir.uta.edu/sockg-ontology/docs/departmentName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgDepartment](../classes/SockgDepartment.md) | A Department represents a specialized division within an agricultural institu... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Department | string | sockg:individuals/51833 | USDA ARS | 33 |




## LinkML Source

<details>

```yaml
name: sockg_departmentName
annotations:
  count:
    tag: count
    value: 33
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: USDA ARS
    example_object_type: string
    example_predicate: sockg:departmentName
    example_subject: sockg:individuals/51833
    example_subject_type: sockg_Department
from_schema: soc-kg
rank: 1000
domain: sockg_Department
slot_uri: sockg:departmentName
alias: sockg_departmentName
domain_of:
- sockg_Department
range: string

```
</details>