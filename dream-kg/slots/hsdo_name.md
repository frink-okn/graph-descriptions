

# Slot: hsdo_name


_The name of the item._






This slot occurs 177 times.


URI: [schema:name](http://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | string | dreamkg:service/4542572480692224 | Drug and Alcohol Services | 177 |
| hsdo_Service | string | dreamkg:service/4542572480692224 | Drug and Alcohol Services | 88 |
| hsdo_Organization | string | dreamkg:service/provider/4542572480692224 | Child Guidance Resource Centers | 89 |




## LinkML Source

<details>

```yaml
name: hsdo_name
annotations:
  count:
    tag: count
    value: 177
description: The name of the item.
examples:
- object:
    example_object: Drug and Alcohol Services
    example_object_type: string
    example_predicate: schema:name
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: Drug and Alcohol Services
    example_object_type: string
    example_predicate: schema:name
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: Child Guidance Resource Centers
    example_object_type: string
    example_predicate: schema:name
    example_subject: dreamkg:service/provider/4542572480692224
    example_subject_type: hsdo_Organization
from_schema: dream-kg
rank: 1000
slot_uri: schema:name
alias: hsdo_name
domain_of:
- hsdo_Organization
- hsdo_Service
- prov_Entity
range: string

```
</details>