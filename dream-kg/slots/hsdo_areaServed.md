

# Slot: hsdo_areaServed


_The geographic area where a service or offered item is provided._






This slot occurs 87 times.


URI: [schema:areaServed](http://schema.org/areaServed)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | string | dreamkg:service/4542572480692224 | This program covers residents of the following counties: Chester County, PA, Delaware County, PA, Montgomery County, PA and Philadelphia County, PA. | 87 |
| hsdo_Service | string | dreamkg:service/4542572480692224 | This program covers residents of the following counties: Chester County, PA, Delaware County, PA, Montgomery County, PA and Philadelphia County, PA. | 87 |




## LinkML Source

<details>

```yaml
name: hsdo_areaServed
annotations:
  count:
    tag: count
    value: 87
description: The geographic area where a service or offered item is provided.
examples:
- object:
    example_object: 'This program covers residents of the following counties: Chester
      County, PA, Delaware County, PA, Montgomery County, PA and Philadelphia County,
      PA.'
    example_object_type: string
    example_predicate: schema:areaServed
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: 'This program covers residents of the following counties: Chester
      County, PA, Delaware County, PA, Montgomery County, PA and Philadelphia County,
      PA.'
    example_object_type: string
    example_predicate: schema:areaServed
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: schema:areaServed
alias: hsdo_areaServed
domain_of:
- hsdo_Service
- prov_Entity
range: string

```
</details>