

# Slot: hsdo_address


_Physical address of the item._






This slot occurs 93 times.


URI: [schema:address](http://schema.org/address)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Place | string | dreamkg:service/location/4542572480692224 | 2901 Island Avenue, Philadelphia, PA 19153 | 93 |
| prov_Entity | string | dreamkg:service/location/4542572480692224 | 2901 Island Avenue, Philadelphia, PA 19153 | 93 |




## LinkML Source

<details>

```yaml
name: hsdo_address
annotations:
  count:
    tag: count
    value: 93
description: Physical address of the item.
examples:
- object:
    example_object: 2901 Island Avenue, Philadelphia, PA 19153
    example_object_type: string
    example_predicate: schema:address
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
- object:
    example_object: 2901 Island Avenue, Philadelphia, PA 19153
    example_object_type: string
    example_predicate: schema:address
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: prov_Entity
from_schema: dream-kg
rank: 1000
slot_uri: schema:address
alias: hsdo_address
domain_of:
- hsdo_Place
- prov_Entity
range: string

```
</details>