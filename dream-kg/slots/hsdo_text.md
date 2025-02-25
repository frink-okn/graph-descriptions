

# Slot: text (hsdo_text)


_The textual content of this CreativeWork._






This slot occurs 90 times.


URI: [hsdo:text](http://schema.org/text)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoTextObject](../classes/HsdoTextObject.md) | A text file |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | string | dreamkg:service/desc/4542572480692224 | Child Guidance Resource Centers offers a supportive and effective program specifically for teenagers struggling with addiction. The Drug and Alcohol Service (D and A) is an extensive, family-based program that focuses on education, treatment and recovery from substance abuse. We supportively confront and coach our clients through the personal, academic, social and family problems created by and participating in the use of drugs and alcohol.Our treatment includes- Individual therapy- Family therapy- Group therapy- Relapse prevention techniques - After-care planningChild Guidance Resource Centers accepts Medicaid for their services. | 90 |
| hsdo_TextObject | string | dreamkg:service/desc/4542572480692224 | Child Guidance Resource Centers offers a supportive and effective program specifically for teenagers struggling with addiction. The Drug and Alcohol Service (D and A) is an extensive, family-based program that focuses on education, treatment and recovery from substance abuse. We supportively confront and coach our clients through the personal, academic, social and family problems created by and participating in the use of drugs and alcohol.Our treatment includes- Individual therapy- Family therapy- Group therapy- Relapse prevention techniques - After-care planningChild Guidance Resource Centers accepts Medicaid for their services. | 90 |




## LinkML Source

<details>

```yaml
name: hsdo_text
annotations:
  count:
    tag: count
    value: 90
description: The textual content of this CreativeWork.
title: text
examples:
- object:
    example_object: Child Guidance Resource Centers offers a supportive and effective
      program specifically for teenagers struggling with addiction. The Drug and Alcohol
      Service (D and A) is an extensive, family-based program that focuses on education,
      treatment and recovery from substance abuse. We supportively confront and coach
      our clients through the personal, academic, social and family problems created
      by and participating in the use of drugs and alcohol.Our treatment includes-
      Individual therapy- Family therapy- Group therapy- Relapse prevention techniques
      - After-care planningChild Guidance Resource Centers accepts Medicaid for their
      services.
    example_object_type: string
    example_predicate: hsdo:text
    example_subject: dreamkg:service/desc/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: Child Guidance Resource Centers offers a supportive and effective
      program specifically for teenagers struggling with addiction. The Drug and Alcohol
      Service (D and A) is an extensive, family-based program that focuses on education,
      treatment and recovery from substance abuse. We supportively confront and coach
      our clients through the personal, academic, social and family problems created
      by and participating in the use of drugs and alcohol.Our treatment includes-
      Individual therapy- Family therapy- Group therapy- Relapse prevention techniques
      - After-care planningChild Guidance Resource Centers accepts Medicaid for their
      services.
    example_object_type: string
    example_predicate: hsdo:text
    example_subject: dreamkg:service/desc/4542572480692224
    example_subject_type: hsdo_TextObject
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:text
alias: hsdo_text
domain_of:
- hsdo_TextObject
- prov_Entity
range: string

```
</details>