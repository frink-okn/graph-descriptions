

# Slot: name (hsdo_name)


_The name of the item._






This slot occurs 177 times.


URI: [hsdo:name](http://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  yes  |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Service | string | dreamkg:service/6379467169595392 | New Pathways for Women Project | 88 |
| hsdo_Organization | string | dreamkg:service/provider/4780892498952192 | Circle Counseling | 89 |




## LinkML Source

<details>

```yaml
name: hsdo_name
annotations:
  count:
    tag: count
    value: 177
description: The name of the item.
title: name
examples:
- description: hsdo_Service→string
  object:
    example_object: New Pathways for Women Project
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: dreamkg:service/6379467169595392
    example_subject_type: hsdo_Service
- description: hsdo_Organization→string
  object:
    example_object: Circle Counseling
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: dreamkg:service/provider/4780892498952192
    example_subject_type: hsdo_Organization
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:name
alias: hsdo_name
domain_of:
- hsdo_Organization
- hsdo_Service
range: string

```
</details>