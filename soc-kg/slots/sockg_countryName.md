

# Slot: No slot (predicate) name specified (sockg_countryName)


_No slot (predicate) description specified_






This slot occurs 3 times.


URI: [sockg:countryName](https://idir.uta.edu/sockg-ontology/docs/countryName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgCountry](../classes/SockgCountry.md) | A Country is a distinct territorial body with its own government and borders,... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Country | string | sockg:individuals/46901 | USA | 3 |




## LinkML Source

<details>

```yaml
name: sockg_countryName
annotations:
  count:
    tag: count
    value: 3
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: USA
    example_object_type: string
    example_predicate: sockg:countryName
    example_subject: sockg:individuals/46901
    example_subject_type: sockg_Country
from_schema: soc-kg
rank: 1000
domain: sockg_Country
slot_uri: sockg:countryName
alias: sockg_countryName
domain_of:
- sockg_Country
range: string

```
</details>