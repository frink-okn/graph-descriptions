

# Slot: address (hsdo_address)


_Physical address of the item._






This slot occurs 93 times.


URI: [hsdo:address](http://schema.org/address)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Place | string | dreamkg:service/location/5552002522939392 | 2107 West Tioga Street, Philadelphia, PA 19140 | 93 |




## LinkML Source

<details>

```yaml
name: hsdo_address
annotations:
  count:
    tag: count
    value: 93
description: Physical address of the item.
title: address
examples:
- description: hsdo_Place→string
  object:
    example_object: 2107 West Tioga Street, Philadelphia, PA 19140
    example_object_type: string
    example_predicate: hsdo:address
    example_subject: dreamkg:service/location/5552002522939392
    example_subject_type: hsdo_Place
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:address
alias: hsdo_address
domain_of:
- hsdo_Place
range: string

```
</details>