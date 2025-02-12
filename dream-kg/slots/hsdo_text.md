

# Slot: text (hsdo_text)


_The textual content of this CreativeWork._






This slot occurs 90 times.


URI: [hsdo:text](http://schema.org/text)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoTextObject](../classes/HsdoTextObject.md) | A text file |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_TextObject | string | dreamkg:service/desc/6354456388829184 | Centralized Homeless Intake Services includes an assessment of eligibility and service needs of persons and families presenting for placement into emergency housing. If eligible, persons and families are placed in appropriate emergency housing, boarding homes, or other alternative housing. Services include:- Temporary shelter- Ongoing case management services- Assistance with obtaining transitional and/or permanent housing- Supportive housing for special populations- An optional savings program which allows households to save a part of their income for future housing expensesMental health assessments and referrals to drug/alcohol treatment, health services, children and youth services, legal services and veteran's services, etc., are provided as needed to clients of the program.- Connecting Services to other community resources- ScreeningIf you are currently experiencing homelessness, please call us during business hours. You must go through central intake for an initial assessment of your housing needs before placement into the homeless housing system. | 90 |




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
- description: hsdo_TextObject→string
  object:
    example_object: Centralized Homeless Intake Services includes an assessment of
      eligibility and service needs of persons and families presenting for placement
      into emergency housing. If eligible, persons and families are placed in appropriate
      emergency housing, boarding homes, or other alternative housing. Services include:-
      Temporary shelter- Ongoing case management services- Assistance with obtaining
      transitional and/or permanent housing- Supportive housing for special populations-
      An optional savings program which allows households to save a part of their
      income for future housing expensesMental health assessments and referrals to
      drug/alcohol treatment, health services, children and youth services, legal
      services and veteran's services, etc., are provided as needed to clients of
      the program.- Connecting Services to other community resources- ScreeningIf
      you are currently experiencing homelessness, please call us during business
      hours. You must go through central intake for an initial assessment of your
      housing needs before placement into the homeless housing system.
    example_object_type: string
    example_predicate: hsdo:text
    example_subject: dreamkg:service/desc/6354456388829184
    example_subject_type: hsdo_TextObject
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:text
alias: hsdo_text
domain_of:
- hsdo_TextObject
range: string

```
</details>