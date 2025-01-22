

# Slot: relation_HasParentActivity


_No slot (predicate) description specified_





URI: [relation:HasParentActivity](http://relation.org/HasParentActivity)



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
| hsdo_Experiment → hsdo_Activity | https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 | relation:HasParentActivity | https://climateKG.org/entity/8f528b66-670d-4198-b014-7fdc9e1f6890 |


## Comments

* 251 occurrences with subject type hsdo_Experiment and object type hsdo_Activity.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:HasParentActivity |
| native | climatepub4-kg/:relation_HasParentActivity |




## LinkML Source

<details>
```yaml
name: relation_HasParentActivity
description: No slot (predicate) description specified
comments:
- 251 occurrences with subject type hsdo_Experiment and object type hsdo_Activity.
examples:
- description: hsdo_Experiment → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/8f528b66-670d-4198-b014-7fdc9e1f6890
    example_object_type: hsdo_Activity
    example_predicate: relation:HasParentActivity
    example_subject: https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9
    example_subject_type: hsdo_Experiment
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:HasParentActivity
alias: relation_HasParentActivity
domain_of:
- hsdo_Experiment
range: hsdo_Activity

```
</details>