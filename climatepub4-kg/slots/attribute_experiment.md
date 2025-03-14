

# Slot: attribute_experiment


_No slot (predicate) description specified_






This slot occurs 322 times.


URI: [attribute:experiment](http://attribute.org/experiment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoExperiment](../classes/HsdoExperiment.md) | No class (type) description specified |  yes  |
| [HsdoProject](../classes/HsdoProject.md) | An enterprise (potentially individual but typically collaborative), planned t... |  yes  |
| [HsdoProvider](../classes/HsdoProvider.md) | No class (type) description specified |  yes  |
| [HsdoModel](../classes/HsdoModel.md) | No class (type) description specified |  yes  |
| [HsdoVariable](../classes/HsdoVariable.md) | No class (type) description specified |  yes  |
| [HsdoLocation](../classes/HsdoLocation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Experiment | string | https://climateKG.org/entity/033c6854-b6b0-47b7-b41d-6c482932f336 | pre-industrial control (spin-up; CMIP5-era [1850-2005] forcing) | 322 |
| hsdo_Model | string | https://climateKG.org/entity/0f07d4c2-cfee-43ff-86d1-289058fe5050 | update of RCP8.5 based on SSP5 | 4 |
| hsdo_Provider | string | https://climateKG.org/entity/20dea6db-e5d4-42a9-a1d5-0421c65fced8 | all-forcing simulation of the recent past | 2 |
| hsdo_Variable | string | https://climateKG.org/entity/20dea6db-e5d4-42a9-a1d5-0421c65fced8 | all-forcing simulation of the recent past | 5 |
| hsdo_Location | string | https://climateKG.org/entity/20dea6db-e5d4-42a9-a1d5-0421c65fced8 | all-forcing simulation of the recent past | 3 |
| hsdo_Project | string | https://climateKG.org/entity/4c94cb2e-37fb-4a76-a69b-a9d0731dbe3c | last glacial maximum | 4 |




## LinkML Source

<details>

```yaml
name: attribute_experiment
annotations:
  count:
    tag: count
    value: 322
description: No slot (predicate) description specified
examples:
- description: hsdo_Experiment→string
  object:
    example_object: pre-industrial control (spin-up; CMIP5-era [1850-2005] forcing)
    example_object_type: string
    example_predicate: attribute:experiment
    example_subject: https://climateKG.org/entity/033c6854-b6b0-47b7-b41d-6c482932f336
    example_subject_type: hsdo_Experiment
- description: hsdo_Model→string
  object:
    example_object: update of RCP8.5 based on SSP5
    example_object_type: string
    example_predicate: attribute:experiment
    example_subject: https://climateKG.org/entity/0f07d4c2-cfee-43ff-86d1-289058fe5050
    example_subject_type: hsdo_Model
- description: hsdo_Provider→string
  object:
    example_object: all-forcing simulation of the recent past
    example_object_type: string
    example_predicate: attribute:experiment
    example_subject: https://climateKG.org/entity/20dea6db-e5d4-42a9-a1d5-0421c65fced8
    example_subject_type: hsdo_Provider
- description: hsdo_Variable→string
  object:
    example_object: all-forcing simulation of the recent past
    example_object_type: string
    example_predicate: attribute:experiment
    example_subject: https://climateKG.org/entity/20dea6db-e5d4-42a9-a1d5-0421c65fced8
    example_subject_type: hsdo_Variable
- description: hsdo_Location→string
  object:
    example_object: all-forcing simulation of the recent past
    example_object_type: string
    example_predicate: attribute:experiment
    example_subject: https://climateKG.org/entity/20dea6db-e5d4-42a9-a1d5-0421c65fced8
    example_subject_type: hsdo_Location
- description: hsdo_Project→string
  object:
    example_object: last glacial maximum
    example_object_type: string
    example_predicate: attribute:experiment
    example_subject: https://climateKG.org/entity/4c94cb2e-37fb-4a76-a69b-a9d0731dbe3c
    example_subject_type: hsdo_Project
from_schema: climatepub4-kg
rank: 1000
slot_uri: attribute:experiment
alias: attribute_experiment
domain_of:
- hsdo_Experiment
- hsdo_Location
- hsdo_Model
- hsdo_Project
- hsdo_Provider
- hsdo_Variable
range: string

```
</details>