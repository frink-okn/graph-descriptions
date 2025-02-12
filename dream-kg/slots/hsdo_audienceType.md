

# Slot: audienceType (hsdo_audienceType)


_The target group associated with a given audience (e.g. veterans, car owners, musicians, etc.)._






This slot occurs 81 times.


URI: [hsdo:audienceType](http://schema.org/audienceType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoAudience](../classes/HsdoAudience.md) | Intended audience for an item, i |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Audience | string | dreamkg:category/audience/HivAids | hiv/aids | 81 |




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
title: audienceType
examples:
- description: hsdo_Audience→string
  object:
    example_object: hiv/aids
    example_object_type: string
    example_predicate: hsdo:audienceType
    example_subject: dreamkg:category/audience/HivAids
    example_subject_type: hsdo_Audience
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:audienceType
alias: hsdo_audienceType
domain_of:
- hsdo_Audience
range: string

```
</details>