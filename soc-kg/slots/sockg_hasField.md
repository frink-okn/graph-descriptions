

# Slot: No slot (predicate) name specified (sockg_hasField)


_No slot (predicate) description specified_






This slot occurs 65 times.


URI: [sockg:hasField](https://idir.uta.edu/sockg-ontology/docs/hasField)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSite](../classes/SockgSite.md) | A Site represents a specific geographical location related to agricultural ac... |  yes  |







## Properties

* Range: [SockgField](../classes/SockgField.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Site | sockg_Field | sockg:individuals/231056 | sockg:individuals/55800 | 65 |




## LinkML Source

<details>

```yaml
name: sockg_hasField
annotations:
  count:
    tag: count
    value: 65
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/55800
    example_object_type: sockg_Field
    example_predicate: sockg:hasField
    example_subject: sockg:individuals/231056
    example_subject_type: sockg_Site
from_schema: soc-kg
rank: 1000
domain: sockg_Site
slot_uri: sockg:hasField
alias: sockg_hasField
domain_of:
- sockg_Site
range: sockg_Field

```
</details>