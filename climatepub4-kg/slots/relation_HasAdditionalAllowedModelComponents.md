

# Slot: relation_HasAdditionalAllowedModelComponents


_No slot (predicate) description specified_





URI: [relation:HasAdditionalAllowedModelComponents](http://relation.org/HasAdditionalAllowedModelComponents)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoExperiment](../classes/HsdoExperiment.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoSourceType](../classes/HsdoSourceType.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Experiment → hsdo_Provider | https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 | relation:HasAdditionalAllowedModelComponents | https://climateKG.org/entity/3b16a2e8-cc4d-40ce-a6c8-336bea211078 |
| hsdo_Experiment → hsdo_Experiment | https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 | relation:HasAdditionalAllowedModelComponents | https://climateKG.org/entity/910d9fdb-84fe-4f62-9172-41888cc181a4 |
| hsdo_Experiment → hsdo_Source_Type | https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 | relation:HasAdditionalAllowedModelComponents | https://climateKG.org/entity/eb6ac594-7a26-4220-a587-4f2200e5dca6 |


## Comments

* 239 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.
* 216 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
* 251 occurrences with subject type hsdo_Experiment and object type hsdo_Source_Type.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:HasAdditionalAllowedModelComponents |
| native | climatepub4-kg/:relation_HasAdditionalAllowedModelComponents |




## LinkML Source

<details>
```yaml
name: relation_HasAdditionalAllowedModelComponents
description: No slot (predicate) description specified
comments:
- 239 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.
- 216 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
- 251 occurrences with subject type hsdo_Experiment and object type hsdo_Source_Type.
examples:
- description: hsdo_Experiment → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/3b16a2e8-cc4d-40ce-a6c8-336bea211078
    example_object_type: hsdo_Provider
    example_predicate: relation:HasAdditionalAllowedModelComponents
    example_subject: https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/910d9fdb-84fe-4f62-9172-41888cc181a4
    example_object_type: hsdo_Experiment
    example_predicate: relation:HasAdditionalAllowedModelComponents
    example_subject: https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Source_Type
  object:
    example_object: https://climateKG.org/entity/eb6ac594-7a26-4220-a587-4f2200e5dca6
    example_object_type: hsdo_Source_Type
    example_predicate: relation:HasAdditionalAllowedModelComponents
    example_subject: https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9
    example_subject_type: hsdo_Experiment
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:HasAdditionalAllowedModelComponents
alias: relation_HasAdditionalAllowedModelComponents
domain_of:
- hsdo_Experiment
range: Any
any_of:
- range: hsdo_Provider
- range: hsdo_Source_Type
- range: hsdo_Experiment

```
</details>