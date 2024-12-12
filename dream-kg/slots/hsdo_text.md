

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
| hsdo_TextObject → string | dreamkg:service/desc/6032260047568896 | hsdo:text | Merakey offers comprehensive clinical, evidence-based practice, and therapeutic programs in both community based and clinic based settings to address the impact of addiction on the community, family, and individual.Services Include:- Group, Family, and Individual Counseling- Outpatient and Intensive Outpatient Programs- Drug Free and Medication Assisted Modalities- Co-Occurring Disorders Treatment- Pharmacotherapy Programs- Drug and Alcohol Education- Life Skills Management- Relapse Prevention Planning- Drug ScreeningMerakey accepts Medicaid. |


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
    example_object: Merakey offers comprehensive clinical, evidence-based practice,
      and therapeutic programs in both community based and clinic based settings to
      address the impact of addiction on the community, family, and individual.Services
      Include:- Group, Family, and Individual Counseling- Outpatient and Intensive
      Outpatient Programs- Drug Free and Medication Assisted Modalities- Co-Occurring
      Disorders Treatment- Pharmacotherapy Programs- Drug and Alcohol Education- Life
      Skills Management- Relapse Prevention Planning- Drug ScreeningMerakey accepts
      Medicaid.
    example_predicate: hsdo:text
    example_subject: dreamkg:service/desc/6032260047568896
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:text
alias: hsdo_text
domain_of:
- hsdo_TextObject
range: string

```
</details>