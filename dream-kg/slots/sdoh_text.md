

# Slot: text (sdoh_text)


_The textual content of this CreativeWork._





URI: [sdoh:text](http://schema.org/text)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohTextObject](../classes/SdohTextObject.md) | A text file |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:service/desc/6272068172382208 sdoh:text Wedge Recovery Center offers the Early Intervention Program for Philadelphia residents between the ages 12-21 who are currently using substances or who are otherwise at risk for substance abuse because of factors in the environmental, school, legal, family, mental health, peer & social, and dependency system domains.We offer:- Substance Use Screening and Assessment- Evidenced-based Substance Abuse Education- Intervention Counseling- Family Counseling- Community/School/Child service outreach- Individualized Service Planning- Group Psychoeducational Sessions- Parental Education/Consultation- Service Linkage |

## Comments

* 90 occurrences with subject type sdoh_TextObject and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:text |
| native | dream-kg/:sdoh_text |




## LinkML Source

<details>
```yaml
name: sdoh_text
description: The textual content of this CreativeWork.
title: text
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 90 occurrences with subject type sdoh_TextObject and object type string.
examples:
- value: dreamkg:service/desc/6272068172382208 sdoh:text Wedge Recovery Center offers
    the Early Intervention Program for Philadelphia residents between the ages 12-21
    who are currently using substances or who are otherwise at risk for substance
    abuse because of factors in the environmental, school, legal, family, mental health,
    peer & social, and dependency system domains.We offer:- Substance Use Screening
    and Assessment- Evidenced-based Substance Abuse Education- Intervention Counseling-
    Family Counseling- Community/School/Child service outreach- Individualized Service
    Planning- Group Psychoeducational Sessions- Parental Education/Consultation- Service
    Linkage
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:text
alias: sdoh_text
domain_of:
- sdoh_TextObject
range: string

```
</details>