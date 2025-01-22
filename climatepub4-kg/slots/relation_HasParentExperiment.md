

# Slot: relation_HasParentExperiment


_No slot (predicate) description specified_





URI: [relation:HasParentExperiment](http://relation.org/HasParentExperiment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoExperiment](../classes/HsdoExperiment.md) | No class (type) description specified |  no  |







## Properties

* Range: [HsdoExperiment](../classes/HsdoExperiment.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Experiment → hsdo_Experiment | https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 | relation:HasParentExperiment | https://climateKG.org/entity/9cb8f903-708a-4b88-be4a-ee05926e86c4 |


## Comments

* 251 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:HasParentExperiment |
| native | climatepub4-kg/:relation_HasParentExperiment |




## LinkML Source

<details>
```yaml
name: relation_HasParentExperiment
description: No slot (predicate) description specified
comments:
- 251 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
examples:
- description: hsdo_Experiment → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/9cb8f903-708a-4b88-be4a-ee05926e86c4
    example_object_type: hsdo_Experiment
    example_predicate: relation:HasParentExperiment
    example_subject: https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9
    example_subject_type: hsdo_Experiment
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:HasParentExperiment
alias: relation_HasParentExperiment
domain_of:
- hsdo_Experiment
range: hsdo_Experiment

```
</details>