

# Slot: hsdo_longitude


_The longitude of a location. For example ```-122.08585``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System))._






This slot occurs 89 times.


URI: [schema:longitude](http://schema.org/longitude)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  yes  |







## Properties

* Range: [xsd:decimal](http://www.w3.org/2001/XMLSchema#decimal)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Place | decimal | dreamkg:service/location/4542572480692224 | -75.239064 | 89 |
| prov_Entity | decimal | dreamkg:service/location/4542572480692224 | -75.239064 | 89 |




## LinkML Source

<details>

```yaml
name: hsdo_longitude
annotations:
  count:
    tag: count
    value: 89
description: The longitude of a location. For example ```-122.08585``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System)).
examples:
- object:
    example_object: '-75.239064'
    example_object_type: decimal
    example_predicate: schema:longitude
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
- object:
    example_object: '-75.239064'
    example_object_type: decimal
    example_predicate: schema:longitude
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: prov_Entity
from_schema: dream-kg
rank: 1000
slot_uri: schema:longitude
alias: hsdo_longitude
domain_of:
- hsdo_Place
- prov_Entity
range: decimal

```
</details>