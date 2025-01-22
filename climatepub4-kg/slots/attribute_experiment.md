

# Slot: attribute_experiment


_No slot (predicate) description specified_





URI: [attribute:experiment](http://attribute.org/experiment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoExperiment](../classes/HsdoExperiment.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Experiment → string | https://climateKG.org/entity/033c6854-b6b0-47b7-b41d-6c482932f336 | attribute:experiment | pre-industrial control (spin-up; CMIP5-era [1850-2005] forcing) |


## Comments

* 322 occurrences with subject type hsdo_Experiment and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | attribute:experiment |
| native | climatepub4-kg/:attribute_experiment |




## LinkML Source

<details>
```yaml
name: attribute_experiment
description: No slot (predicate) description specified
comments:
- 322 occurrences with subject type hsdo_Experiment and object type string.
examples:
- description: hsdo_Experiment → string
  object:
    example_object: pre-industrial control (spin-up; CMIP5-era [1850-2005] forcing)
    example_object_type: string
    example_predicate: attribute:experiment
    example_subject: https://climateKG.org/entity/033c6854-b6b0-47b7-b41d-6c482932f336
    example_subject_type: hsdo_Experiment
from_schema: climatepub4-kg
rank: 1000
slot_uri: attribute:experiment
alias: attribute_experiment
domain_of:
- hsdo_Experiment
range: string

```
</details>