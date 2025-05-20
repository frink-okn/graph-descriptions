

# Slot: No slot (predicate) name specified (sockg_cityName)


_No slot (predicate) description specified_






This slot occurs 33 times.


URI: [sockg:cityName](https://idir.uta.edu/sockg-ontology/docs/cityName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgCity](../classes/SockgCity.md) | A City is a large human settlement that serves as a hub for economic, social,... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_City | string | sockg:individuals/46864 | Shorter | 33 |


## See Also

* [https://lod.nal.usda.gov/nalt/7485997](https://lod.nal.usda.gov/nalt/7485997)



## LinkML Source

<details>

```yaml
name: sockg_cityName
annotations:
  count:
    tag: count
    value: 33
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Shorter
    example_object_type: string
    example_predicate: sockg:cityName
    example_subject: sockg:individuals/46864
    example_subject_type: sockg_City
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/7485997
rank: 1000
domain: sockg_City
slot_uri: sockg:cityName
alias: sockg_cityName
domain_of:
- sockg_City
range: string

```
</details>