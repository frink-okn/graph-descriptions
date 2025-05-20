

# Slot: No slot (predicate) name specified (sockg_postalCodeNumber)


_No slot (predicate) description specified_






This slot occurs 60 times.


URI: [sockg:postalCodeNumber](https://idir.uta.edu/sockg-ontology/docs/postalCodeNumber)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSite](../classes/SockgSite.md) | A Site represents a specific geographical location related to agricultural ac... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Site | double | sockg:individuals/231056 | 36075.0 | 60 |


## See Also

* [https://lod.nal.usda.gov/nalt/9775998](https://lod.nal.usda.gov/nalt/9775998)



## LinkML Source

<details>

```yaml
name: sockg_postalCodeNumber
annotations:
  count:
    tag: count
    value: 60
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '36075.0'
    example_object_type: double
    example_predicate: sockg:postalCodeNumber
    example_subject: sockg:individuals/231056
    example_subject_type: sockg_Site
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/9775998
rank: 1000
domain: sockg_Site
slot_uri: sockg:postalCodeNumber
alias: sockg_postalCodeNumber
domain_of:
- sockg_Site
range: Any
any_of:
- range: integer
- range: double

```
</details>