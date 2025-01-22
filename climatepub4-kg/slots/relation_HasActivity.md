

# Slot: relation_HasActivity


_No slot (predicate) description specified_





URI: [relation:HasActivity](http://relation.org/HasActivity)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoExperiment](../classes/HsdoExperiment.md) | No class (type) description specified |  no  |







## Properties

* Range: [HsdoActivity](../classes/HsdoActivity.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Experiment → hsdo_Activity | https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 | relation:HasActivity | https://climateKG.org/entity/a219681a-8eb1-4d8d-8b63-1103afa1127c |


## Comments

* 334 occurrences with subject type hsdo_Experiment and object type hsdo_Activity.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:HasActivity |
| native | climatepub4-kg/:relation_HasActivity |




## LinkML Source

<details>
```yaml
name: relation_HasActivity
description: No slot (predicate) description specified
comments:
- 334 occurrences with subject type hsdo_Experiment and object type hsdo_Activity.
examples:
- description: hsdo_Experiment → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/a219681a-8eb1-4d8d-8b63-1103afa1127c
    example_object_type: hsdo_Activity
    example_predicate: relation:HasActivity
    example_subject: https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9
    example_subject_type: hsdo_Experiment
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:HasActivity
alias: relation_HasActivity
domain_of:
- hsdo_Experiment
range: hsdo_Activity

```
</details>