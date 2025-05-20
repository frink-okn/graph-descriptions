

# Slot: No slot (predicate) name specified (sockg_siteSpatialDescription)


_No slot (predicate) description specified_






This slot occurs 60 times.


URI: [sockg:siteSpatialDescription](https://idir.uta.edu/sockg-ontology/docs/siteSpatialDescription)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSite](../classes/SockgSite.md) | A Site represents a specific geographical location related to agricultural ac... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Site | string | sockg:individuals/231056 | Bounding Box:,-85.897912,32.423849,-85.895231,32.421965 | 60 |




## LinkML Source

<details>

```yaml
name: sockg_siteSpatialDescription
annotations:
  count:
    tag: count
    value: 60
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Bounding Box:,-85.897912,32.423849,-85.895231,32.421965
    example_object_type: string
    example_predicate: sockg:siteSpatialDescription
    example_subject: sockg:individuals/231056
    example_subject_type: sockg_Site
from_schema: soc-kg
rank: 1000
domain: sockg_Site
slot_uri: sockg:siteSpatialDescription
alias: sockg_siteSpatialDescription
domain_of:
- sockg_Site
range: string

```
</details>