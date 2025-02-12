

# Slot: containedInPlace (hsdo_containedInPlace)


_The basic containment relation between a place and one that contains it._






This slot occurs 88 times.


URI: [hsdo:containedInPlace](http://schema.org/containedInPlace)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  yes  |







## Properties

* Range: [HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Place | hsdo_AdministrativeArea | dreamkg:service/location/5552002522939392 | dreamkg:zip/19140 | 88 |




## LinkML Source

<details>

```yaml
name: hsdo_containedInPlace
annotations:
  count:
    tag: count
    value: 88
description: The basic containment relation between a place and one that contains
  it.
title: containedInPlace
examples:
- description: hsdo_Place→hsdo_AdministrativeArea
  object:
    example_object: dreamkg:zip/19140
    example_object_type: hsdo_AdministrativeArea
    example_predicate: hsdo:containedInPlace
    example_subject: dreamkg:service/location/5552002522939392
    example_subject_type: hsdo_Place
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:containedInPlace
alias: hsdo_containedInPlace
domain_of:
- hsdo_Place
range: hsdo_AdministrativeArea

```
</details>