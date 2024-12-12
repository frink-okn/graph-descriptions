

# Slot: hsdo_text


_No slot (predicate) description specified_





URI: [hsdo:text](hsdo:text)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoTextObject](../classes/HsdoTextObject.md) | A text file |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_TextObject → string | dreamkg:service/desc/4542572480692224 | hsdo:text | Child Guidance Resource Centers offers a supportive and effective program specifically for teenagers struggling with addiction. The Drug and Alcohol Service (D and A) is an extensive, family-based program that focuses on education, treatment and recovery from substance abuse. We supportively confront and coach our clients through the personal, academic, social and family problems created by and participating in the use of drugs and alcohol.Our treatment includes- Individual therapy- Family therapy- Group therapy- Relapse prevention techniques - After-care planningChild Guidance Resource Centers accepts Medicaid for their services. |


## Comments

* 90 occurrences with subject type hsdo_TextObject and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:text |
| native | dream-kg/:hsdo_text |




## LinkML Source

<details>
```yaml
name: hsdo_text
description: No slot (predicate) description specified
comments:
- 90 occurrences with subject type hsdo_TextObject and object type string.
examples:
- description: hsdo_TextObject → string
  object:
    example_object: Child Guidance Resource Centers offers a supportive and effective
      program specifically for teenagers struggling with addiction. The Drug and Alcohol
      Service (D and A) is an extensive, family-based program that focuses on education,
      treatment and recovery from substance abuse. We supportively confront and coach
      our clients through the personal, academic, social and family problems created
      by and participating in the use of drugs and alcohol.Our treatment includes-
      Individual therapy- Family therapy- Group therapy- Relapse prevention techniques
      - After-care planningChild Guidance Resource Centers accepts Medicaid for their
      services.
    example_predicate: hsdo:text
    example_subject: dreamkg:service/desc/4542572480692224
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:text
alias: hsdo_text
domain_of:
- hsdo_TextObject
range: string

```
</details>