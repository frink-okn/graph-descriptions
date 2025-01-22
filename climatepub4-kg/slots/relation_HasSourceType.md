

# Slot: relation_HasSourceType


_No slot (predicate) description specified_





URI: [relation:HasSourceType](http://relation.org/HasSourceType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoDataset](../classes/HsdoDataset.md) | A body of structured information describing some topic(s) of interest |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoSourceType](../classes/HsdoSourceType.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Dataset → hsdo_Experiment | https://climateKG.org/entity/81fcbd3b-e74e-4285-bc87-928d5852d1cf | relation:HasSourceType | https://climateKG.org/entity/878e70de-f929-4d2f-9325-145ca95787e9 |
| hsdo_Dataset → hsdo_Source_Type | https://climateKG.org/entity/fe64cea2-19de-470c-a919-b24c744c696b | relation:HasSourceType | https://climateKG.org/entity/7568d0fd-d892-4aa6-b724-594920455398 |


## Comments

* 6 occurrences with subject type hsdo_Dataset and object type hsdo_Experiment.
* 100 occurrences with subject type hsdo_Dataset and object type hsdo_Source_Type.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:HasSourceType |
| native | climatepub4-kg/:relation_HasSourceType |




## LinkML Source

<details>
```yaml
name: relation_HasSourceType
description: No slot (predicate) description specified
comments:
- 6 occurrences with subject type hsdo_Dataset and object type hsdo_Experiment.
- 100 occurrences with subject type hsdo_Dataset and object type hsdo_Source_Type.
examples:
- description: hsdo_Dataset → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/878e70de-f929-4d2f-9325-145ca95787e9
    example_object_type: hsdo_Experiment
    example_predicate: relation:HasSourceType
    example_subject: https://climateKG.org/entity/81fcbd3b-e74e-4285-bc87-928d5852d1cf
    example_subject_type: hsdo_Dataset
- description: hsdo_Dataset → hsdo_Source_Type
  object:
    example_object: https://climateKG.org/entity/7568d0fd-d892-4aa6-b724-594920455398
    example_object_type: hsdo_Source_Type
    example_predicate: relation:HasSourceType
    example_subject: https://climateKG.org/entity/fe64cea2-19de-470c-a919-b24c744c696b
    example_subject_type: hsdo_Dataset
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:HasSourceType
alias: relation_HasSourceType
domain_of:
- hsdo_Dataset
range: Any
any_of:
- range: hsdo_Source_Type
- range: hsdo_Experiment

```
</details>