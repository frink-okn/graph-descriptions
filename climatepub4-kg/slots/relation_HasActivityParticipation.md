

# Slot: relation_HasActivityParticipation


_No slot (predicate) description specified_





URI: [relation:HasActivityParticipation](http://relation.org/HasActivityParticipation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md) | No class (type) description specified |  no  |







## Properties

* Range: [HsdoActivity](../classes/HsdoActivity.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Cmip6_Source_Id → hsdo_Activity | https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 | relation:HasActivityParticipation | https://climateKG.org/entity/09347fb2-7842-4939-836e-6b8b2c35f5b1 |


## Comments

* 685 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Activity.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:HasActivityParticipation |
| native | climatepub4-kg/:relation_HasActivityParticipation |




## LinkML Source

<details>
```yaml
name: relation_HasActivityParticipation
description: No slot (predicate) description specified
comments:
- 685 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Activity.
examples:
- description: hsdo_Cmip6_Source_Id → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/09347fb2-7842-4939-836e-6b8b2c35f5b1
    example_object_type: hsdo_Activity
    example_predicate: relation:HasActivityParticipation
    example_subject: https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7
    example_subject_type: hsdo_Cmip6_Source_Id
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:HasActivityParticipation
alias: relation_HasActivityParticipation
domain_of:
- hsdo_Cmip6_Source_Id
range: hsdo_Activity

```
</details>