

# Slot: latitude (hsdo_latitude)


_The latitude of a location. For example ```37.42242``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System))._






This slot occurs 89 times.


URI: [hsdo:latitude](http://schema.org/latitude)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  yes  |







## Properties

* Range: [xsd:decimal](http://www.w3.org/2001/XMLSchema#decimal)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Place | decimal | dreamkg:service/location/5552002522939392 | 40.0079322 | 89 |




## LinkML Source

<details>

```yaml
name: hsdo_latitude
annotations:
  count:
    tag: count
    value: 89
description: The latitude of a location. For example ```37.42242``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System)).
title: latitude
examples:
- description: hsdo_Place→decimal
  object:
    example_object: '40.0079322'
    example_object_type: decimal
    example_predicate: hsdo:latitude
    example_subject: dreamkg:service/location/5552002522939392
    example_subject_type: hsdo_Place
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:latitude
alias: hsdo_latitude
domain_of:
- hsdo_Place
range: decimal

```
</details>