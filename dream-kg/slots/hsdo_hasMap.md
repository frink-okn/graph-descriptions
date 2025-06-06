

# Slot: hsdo_hasMap


_A URL to a map of the place._






This slot occurs 88 times.


URI: [schema:hasMap](http://schema.org/hasMap)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Place | uri | dreamkg:service/location/4542572480692224 | https://www.google.com/maps/?q=2901+Island+Avenue,+Philadelphia,+PA+19153/ | 88 |
| prov_Entity | uri | dreamkg:service/location/4542572480692224 | https://www.google.com/maps/?q=2901+Island+Avenue,+Philadelphia,+PA+19153/ | 88 |




## LinkML Source

<details>

```yaml
name: hsdo_hasMap
annotations:
  count:
    tag: count
    value: 88
description: A URL to a map of the place.
examples:
- object:
    example_object: https://www.google.com/maps/?q=2901+Island+Avenue,+Philadelphia,+PA+19153/
    example_object_type: uri
    example_predicate: schema:hasMap
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
- object:
    example_object: https://www.google.com/maps/?q=2901+Island+Avenue,+Philadelphia,+PA+19153/
    example_object_type: uri
    example_predicate: schema:hasMap
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: prov_Entity
from_schema: dream-kg
rank: 1000
slot_uri: schema:hasMap
alias: hsdo_hasMap
domain_of:
- hsdo_Place
- prov_Entity
range: uri

```
</details>