

# Slot: No slot (predicate) name specified (sockg_versionDate)


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [sockg:versionDate](https://idir.uta.edu/sockg-ontology/docs/versionDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgVersion](../classes/SockgVersion.md) | A Version represents a specific iteration or update of agricultural practices... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Version | string | sockg:individuals/364325 | 04/17/2025 | 1 |




## LinkML Source

<details>

```yaml
name: sockg_versionDate
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: 04/17/2025
    example_object_type: string
    example_predicate: sockg:versionDate
    example_subject: sockg:individuals/364325
    example_subject_type: sockg_Version
from_schema: soc-kg
rank: 1000
domain: sockg_Version
slot_uri: sockg:versionDate
alias: sockg_versionDate
domain_of:
- sockg_Version
range: string

```
</details>