

# Slot: areaServed (hsdo_areaServed)


_The geographic area where a service or offered item is provided._






This slot occurs 87 times.


URI: [hsdo:areaServed](http://schema.org/areaServed)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Service | string | dreamkg:service/6379467169595392 | This program covers residents of the following counties: Philadelphia County, PA. | 87 |




## LinkML Source

<details>

```yaml
name: hsdo_areaServed
annotations:
  count:
    tag: count
    value: 87
description: The geographic area where a service or offered item is provided.
title: areaServed
examples:
- description: hsdo_Service→string
  object:
    example_object: 'This program covers residents of the following counties: Philadelphia
      County, PA.'
    example_object_type: string
    example_predicate: hsdo:areaServed
    example_subject: dreamkg:service/6379467169595392
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:areaServed
alias: hsdo_areaServed
domain_of:
- hsdo_Service
range: string

```
</details>