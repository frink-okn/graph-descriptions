

# Slot: relation_MountedOn


_No slot (predicate) description specified_





URI: [relation:MountedOn](http://relation.org/MountedOn)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPlatform](../classes/HsdoPlatform.md) | No class (type) description specified |  no  |
| [HsdoLocation](../classes/HsdoLocation.md) | No class (type) description specified |  no  |
| [HsdoProject](../classes/HsdoProject.md) | An enterprise (potentially individual but typically collaborative), planned t... |  no  |
| [HsdoExperiment](../classes/HsdoExperiment.md) | No class (type) description specified |  no  |
| [HsdoProvider](../classes/HsdoProvider.md) | No class (type) description specified |  no  |
| [HsdoInstrument](../classes/HsdoInstrument.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoModels](../classes/HsdoModels.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoInstitution](../classes/HsdoInstitution.md)&nbsp;or&nbsp;<br />[HsdoInstrument](../classes/HsdoInstrument.md)&nbsp;or&nbsp;<br />[HsdoPlatform](../classes/HsdoPlatform.md)&nbsp;or&nbsp;<br />[HsdoLocation](../classes/HsdoLocation.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Instrument → hsdo_Location | https://climateKG.org/entity/f9fd6f89-9a67-4ece-9514-3803e7787520 | relation:MountedOn | https://climateKG.org/entity/b791f381-1c1c-4958-bc7d-b72a15da1174 |
| hsdo_Location → hsdo_Instrument | https://climateKG.org/entity/9645d2d7-fcb7-4e34-9433-1328b847048e | relation:MountedOn | https://climateKG.org/entity/8dc44d7b-e349-42ab-860e-18f5acfc1b28 |
| hsdo_Experiment → hsdo_Instrument | https://climateKG.org/entity/8916dafb-5ad5-45c6-ab64-3500ea1e9577 | relation:MountedOn | https://climateKG.org/entity/f6350232-b1c7-458c-bc43-bda357ebb6db |
| hsdo_Instrument → hsdo_Platform | https://climateKG.org/entity/8783344a-b6cb-4905-adab-1ae6281fc83d | relation:MountedOn | https://climateKG.org/entity/5d7f7568-bfc3-4c11-b446-c4f6488c8ae9 |
| hsdo_Platform → hsdo_Instrument | https://climateKG.org/entity/2405ed08-fc64-4251-a242-c879181ebafd | relation:MountedOn | https://climateKG.org/entity/b79c7e06-cd07-442f-bf12-2019cd71c201 |
| hsdo_Platform → hsdo_Provider | https://climateKG.org/entity/2405ed08-fc64-4251-a242-c879181ebafd | relation:MountedOn | https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23 |
| hsdo_Instrument → hsdo_Instrument | https://climateKG.org/entity/ee79f1d4-3a73-408f-beea-945b869b3abf | relation:MountedOn | https://climateKG.org/entity/e5fde4c4-15cd-4278-b922-005488df096f |
| hsdo_Location → hsdo_Location | https://climateKG.org/entity/41191de9-be66-45e2-b4de-95d5090df8d8 | relation:MountedOn | https://climateKG.org/entity/0d209f3c-73b1-412d-828b-22b25da8fc3a |
| hsdo_Instrument → hsdo_Experiment | https://climateKG.org/entity/efbd1edc-388f-4985-8033-6782ee87d463 | relation:MountedOn | https://climateKG.org/entity/205df2ad-cbc2-46a7-941b-d1b49a1c85fe |
| hsdo_Location → hsdo_Institution | https://climateKG.org/entity/4c09d43f-68d5-469d-aaed-f9ef8968ef2e | relation:MountedOn | https://climateKG.org/entity/3be6270c-8554-467a-b2c7-9c13bc086b10 |
| hsdo_Experiment → hsdo_Platform | https://climateKG.org/entity/4f9e19dc-adc1-4c7e-91ab-5947064737e3 | relation:MountedOn | https://climateKG.org/entity/432d2336-1111-4305-a8cb-8d0c8a3af632 |
| hsdo_Project → hsdo_Location | https://climateKG.org/entity/6831004a-34d7-42f5-a903-6c84a5e7590f | relation:MountedOn | https://climateKG.org/entity/a4aea007-d297-4051-8b41-5cdde00b4d1e |
| hsdo_Location → hsdo_Experiment | https://climateKG.org/entity/8b7f66ea-d481-4641-9dbf-da90ca3ad9c9 | relation:MountedOn | https://climateKG.org/entity/a6212424-1146-4a79-a14c-8ce88543b08b |
| hsdo_Provider → hsdo_Models | https://climateKG.org/entity/9c0288cc-864d-40f7-93af-6df413b404f5 | relation:MountedOn | https://climateKG.org/entity/3668de06-8a7d-4667-beb8-d04dcac619b0 |
| hsdo_Experiment → hsdo_Experiment | https://climateKG.org/entity/d69f7457-db31-48ce-b8c2-98058c412bc6 | relation:MountedOn | https://climateKG.org/entity/3cbb9f17-ddb1-48d3-a507-786887e485af |


## Comments

* 22 occurrences with subject type hsdo_Instrument and object type hsdo_Location.
* 4 occurrences with subject type hsdo_Location and object type hsdo_Instrument.
* 7 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.
* 6 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.
* 1 occurrences with subject type hsdo_Platform and object type hsdo_Instrument.
* 1 occurrences with subject type hsdo_Platform and object type hsdo_Provider.
* 21 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.
* 1 occurrences with subject type hsdo_Location and object type hsdo_Location.
* 5 occurrences with subject type hsdo_Instrument and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Location and object type hsdo_Institution.
* 1 occurrences with subject type hsdo_Experiment and object type hsdo_Platform.
* 1 occurrences with subject type hsdo_Project and object type hsdo_Location.
* 1 occurrences with subject type hsdo_Location and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Provider and object type hsdo_Models.
* 1 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:MountedOn |
| native | climatepub4-kg/:relation_MountedOn |




## LinkML Source

<details>
```yaml
name: relation_MountedOn
description: No slot (predicate) description specified
comments:
- 22 occurrences with subject type hsdo_Instrument and object type hsdo_Location.
- 4 occurrences with subject type hsdo_Location and object type hsdo_Instrument.
- 7 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.
- 6 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.
- 1 occurrences with subject type hsdo_Platform and object type hsdo_Instrument.
- 1 occurrences with subject type hsdo_Platform and object type hsdo_Provider.
- 21 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.
- 1 occurrences with subject type hsdo_Location and object type hsdo_Location.
- 5 occurrences with subject type hsdo_Instrument and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Location and object type hsdo_Institution.
- 1 occurrences with subject type hsdo_Experiment and object type hsdo_Platform.
- 1 occurrences with subject type hsdo_Project and object type hsdo_Location.
- 1 occurrences with subject type hsdo_Location and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Provider and object type hsdo_Models.
- 1 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
examples:
- description: hsdo_Instrument → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/b791f381-1c1c-4958-bc7d-b72a15da1174
    example_object_type: hsdo_Location
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/f9fd6f89-9a67-4ece-9514-3803e7787520
    example_subject_type: hsdo_Instrument
- description: hsdo_Location → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/8dc44d7b-e349-42ab-860e-18f5acfc1b28
    example_object_type: hsdo_Instrument
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/9645d2d7-fcb7-4e34-9433-1328b847048e
    example_subject_type: hsdo_Location
- description: hsdo_Experiment → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/f6350232-b1c7-458c-bc43-bda357ebb6db
    example_object_type: hsdo_Instrument
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/8916dafb-5ad5-45c6-ab64-3500ea1e9577
    example_subject_type: hsdo_Experiment
- description: hsdo_Instrument → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/5d7f7568-bfc3-4c11-b446-c4f6488c8ae9
    example_object_type: hsdo_Platform
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/8783344a-b6cb-4905-adab-1ae6281fc83d
    example_subject_type: hsdo_Instrument
- description: hsdo_Platform → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/b79c7e06-cd07-442f-bf12-2019cd71c201
    example_object_type: hsdo_Instrument
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/2405ed08-fc64-4251-a242-c879181ebafd
    example_subject_type: hsdo_Platform
- description: hsdo_Platform → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23
    example_object_type: hsdo_Provider
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/2405ed08-fc64-4251-a242-c879181ebafd
    example_subject_type: hsdo_Platform
- description: hsdo_Instrument → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/e5fde4c4-15cd-4278-b922-005488df096f
    example_object_type: hsdo_Instrument
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/ee79f1d4-3a73-408f-beea-945b869b3abf
    example_subject_type: hsdo_Instrument
- description: hsdo_Location → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/0d209f3c-73b1-412d-828b-22b25da8fc3a
    example_object_type: hsdo_Location
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/41191de9-be66-45e2-b4de-95d5090df8d8
    example_subject_type: hsdo_Location
- description: hsdo_Instrument → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/205df2ad-cbc2-46a7-941b-d1b49a1c85fe
    example_object_type: hsdo_Experiment
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/efbd1edc-388f-4985-8033-6782ee87d463
    example_subject_type: hsdo_Instrument
- description: hsdo_Location → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/3be6270c-8554-467a-b2c7-9c13bc086b10
    example_object_type: hsdo_Institution
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/4c09d43f-68d5-469d-aaed-f9ef8968ef2e
    example_subject_type: hsdo_Location
- description: hsdo_Experiment → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/432d2336-1111-4305-a8cb-8d0c8a3af632
    example_object_type: hsdo_Platform
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/4f9e19dc-adc1-4c7e-91ab-5947064737e3
    example_subject_type: hsdo_Experiment
- description: hsdo_Project → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/a4aea007-d297-4051-8b41-5cdde00b4d1e
    example_object_type: hsdo_Location
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/6831004a-34d7-42f5-a903-6c84a5e7590f
    example_subject_type: hsdo_Project
- description: hsdo_Location → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/a6212424-1146-4a79-a14c-8ce88543b08b
    example_object_type: hsdo_Experiment
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/8b7f66ea-d481-4641-9dbf-da90ca3ad9c9
    example_subject_type: hsdo_Location
- description: hsdo_Provider → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/3668de06-8a7d-4667-beb8-d04dcac619b0
    example_object_type: hsdo_Models
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/9c0288cc-864d-40f7-93af-6df413b404f5
    example_subject_type: hsdo_Provider
- description: hsdo_Experiment → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/3cbb9f17-ddb1-48d3-a507-786887e485af
    example_object_type: hsdo_Experiment
    example_predicate: relation:MountedOn
    example_subject: https://climateKG.org/entity/d69f7457-db31-48ce-b8c2-98058c412bc6
    example_subject_type: hsdo_Experiment
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:MountedOn
alias: relation_MountedOn
domain_of:
- hsdo_Experiment
- hsdo_Instrument
- hsdo_Location
- hsdo_Platform
- hsdo_Project
- hsdo_Provider
range: Any
any_of:
- range: hsdo_Models
- range: hsdo_Provider
- range: hsdo_Institution
- range: hsdo_Instrument
- range: hsdo_Platform
- range: hsdo_Location
- range: hsdo_Experiment

```
</details>