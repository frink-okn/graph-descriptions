

# Slot: longitude (hsdo_longitude)


_The longitude of a location. For example ```-122.08585``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System))._






This slot occurs 89 times.


URI: [hsdo:longitude](http://schema.org/longitude)



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
| hsdo_Place | decimal | dreamkg:service/location/5552002522939392 | -75.1637779 | 89 |




## LinkML Source

<details>

```yaml
name: hsdo_longitude
annotations:
  count:
    tag: count
    value: 89
description: The longitude of a location. For example ```-122.08585``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System)).
title: longitude
examples:
- description: hsdo_Place→decimal
  object:
    example_object: '-75.1637779'
    example_object_type: decimal
    example_predicate: hsdo:longitude
    example_subject: dreamkg:service/location/5552002522939392
    example_subject_type: hsdo_Place
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:longitude
alias: hsdo_longitude
domain_of:
- hsdo_Place
range: decimal

```
</details>