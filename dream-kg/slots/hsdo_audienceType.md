

# Slot: hsdo_audienceType


_The target group associated with a given audience (e.g. veterans, car owners, musicians, etc.)._






This slot occurs 81 times.


URI: [schema:audienceType](http://schema.org/audienceType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoAudience](../classes/HsdoAudience.md) | Intended audience for an item, i |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Audience | string | dreamkg:category/audience/AbuseOrNeglectSurvivors | abuse or neglect survivors | 81 |
| prov_Entity | string | dreamkg:category/audience/AbuseOrNeglectSurvivors | abuse or neglect survivors | 81 |




## LinkML Source

<details>

```yaml
name: hsdo_audienceType
annotations:
  count:
    tag: count
    value: 81
description: The target group associated with a given audience (e.g. veterans, car
  owners, musicians, etc.).
examples:
- object:
    example_object: abuse or neglect survivors
    example_object_type: string
    example_predicate: schema:audienceType
    example_subject: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_subject_type: hsdo_Audience
- object:
    example_object: abuse or neglect survivors
    example_object_type: string
    example_predicate: schema:audienceType
    example_subject: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_subject_type: prov_Entity
from_schema: dream-kg
rank: 1000
slot_uri: schema:audienceType
alias: hsdo_audienceType
domain_of:
- hsdo_Audience
- prov_Entity
range: string

```
</details>