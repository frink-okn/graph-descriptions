

# Slot: relation_HasRequiredModelComponents


_No slot (predicate) description specified_





URI: [relation:HasRequiredModelComponents](http://relation.org/HasRequiredModelComponents)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoExperiment](../classes/HsdoExperiment.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoModel](../classes/HsdoModel.md)&nbsp;or&nbsp;<br />[HsdoSourceType](../classes/HsdoSourceType.md)&nbsp;or&nbsp;<br />[HsdoLocation](../classes/HsdoLocation.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Experiment → hsdo_Model | https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 | relation:HasRequiredModelComponents | https://climateKG.org/entity/13df63e8-85ad-405d-9b43-256371e259c0 |
| hsdo_Experiment → hsdo_Location | https://climateKG.org/entity/f0e8aae3-6f13-476f-a3cf-7ef5fcd70c12 | relation:HasRequiredModelComponents | https://climateKG.org/entity/e8c6761b-0653-495c-82e9-feb685344542 |
| hsdo_Experiment → hsdo_Experiment | https://climateKG.org/entity/f085b587-57ca-421c-a2d1-717f77e17822 | relation:HasRequiredModelComponents | https://climateKG.org/entity/910d9fdb-84fe-4f62-9172-41888cc181a4 |
| hsdo_Experiment → hsdo_Provider | https://climateKG.org/entity/f1a939e7-6c56-4a7d-97c8-645783b546c0 | relation:HasRequiredModelComponents | https://climateKG.org/entity/3b16a2e8-cc4d-40ce-a6c8-336bea211078 |
| hsdo_Experiment → hsdo_Source_Type | https://climateKG.org/entity/ea07120e-7d96-48ed-a75f-22018b93738a | relation:HasRequiredModelComponents | https://climateKG.org/entity/eb6ac594-7a26-4220-a587-4f2200e5dca6 |


## Comments

* 287 occurrences with subject type hsdo_Experiment and object type hsdo_Model.
* 40 occurrences with subject type hsdo_Experiment and object type hsdo_Location.
* 50 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
* 38 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.
* 15 occurrences with subject type hsdo_Experiment and object type hsdo_Source_Type.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:HasRequiredModelComponents |
| native | climatepub4-kg/:relation_HasRequiredModelComponents |




## LinkML Source

<details>
```yaml
name: relation_HasRequiredModelComponents
description: No slot (predicate) description specified
comments:
- 287 occurrences with subject type hsdo_Experiment and object type hsdo_Model.
- 40 occurrences with subject type hsdo_Experiment and object type hsdo_Location.
- 50 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
- 38 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.
- 15 occurrences with subject type hsdo_Experiment and object type hsdo_Source_Type.
examples:
- description: hsdo_Experiment → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/13df63e8-85ad-405d-9b43-256371e259c0
    example_object_type: hsdo_Model
    example_predicate: relation:HasRequiredModelComponents
    example_subject: https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/e8c6761b-0653-495c-82e9-feb685344542
    example_object_type: hsdo_Location
    example_predicate: relation:HasRequiredModelComponents
    example_subject: https://climateKG.org/entity/f0e8aae3-6f13-476f-a3cf-7ef5fcd70c12
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/910d9fdb-84fe-4f62-9172-41888cc181a4
    example_object_type: hsdo_Experiment
    example_predicate: relation:HasRequiredModelComponents
    example_subject: https://climateKG.org/entity/f085b587-57ca-421c-a2d1-717f77e17822
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/3b16a2e8-cc4d-40ce-a6c8-336bea211078
    example_object_type: hsdo_Provider
    example_predicate: relation:HasRequiredModelComponents
    example_subject: https://climateKG.org/entity/f1a939e7-6c56-4a7d-97c8-645783b546c0
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Source_Type
  object:
    example_object: https://climateKG.org/entity/eb6ac594-7a26-4220-a587-4f2200e5dca6
    example_object_type: hsdo_Source_Type
    example_predicate: relation:HasRequiredModelComponents
    example_subject: https://climateKG.org/entity/ea07120e-7d96-48ed-a75f-22018b93738a
    example_subject_type: hsdo_Experiment
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:HasRequiredModelComponents
alias: relation_HasRequiredModelComponents
domain_of:
- hsdo_Experiment
range: Any
any_of:
- range: hsdo_Provider
- range: hsdo_Model
- range: hsdo_Source_Type
- range: hsdo_Location
- range: hsdo_Experiment

```
</details>