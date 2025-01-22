

# Slot: relation_ValidatedBy


_No slot (predicate) description specified_





URI: [relation:ValidatedBy](http://relation.org/ValidatedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoLocation](../classes/HsdoLocation.md) | No class (type) description specified |  no  |
| [HsdoModel](../classes/HsdoModel.md) | No class (type) description specified |  no  |
| [HsdoVariable](../classes/HsdoVariable.md) | No class (type) description specified |  no  |
| [HsdoExperiment](../classes/HsdoExperiment.md) | No class (type) description specified |  no  |
| [HsdoProject](../classes/HsdoProject.md) | An enterprise (potentially individual but typically collaborative), planned t... |  no  |
| [HsdoModels](../classes/HsdoModels.md) | No class (type) description specified |  no  |
| [HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md) | No class (type) description specified |  no  |
| [HsdoProvider](../classes/HsdoProvider.md) | No class (type) description specified |  no  |
| [HsdoInstrument](../classes/HsdoInstrument.md) | No class (type) description specified |  no  |
| [HsdoInstitution](../classes/HsdoInstitution.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoModels](../classes/HsdoModels.md)&nbsp;or&nbsp;<br />[HsdoVariable](../classes/HsdoVariable.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoProject](../classes/HsdoProject.md)&nbsp;or&nbsp;<br />[HsdoModel](../classes/HsdoModel.md)&nbsp;or&nbsp;<br />[HsdoDataset](../classes/HsdoDataset.md)&nbsp;or&nbsp;<br />[HsdoInstrument](../classes/HsdoInstrument.md)&nbsp;or&nbsp;<br />[HsdoPlatform](../classes/HsdoPlatform.md)&nbsp;or&nbsp;<br />[HsdoScienceKeyword](../classes/HsdoScienceKeyword.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Models → hsdo_Project | https://climateKG.org/entity/063177a9-14cd-4750-9aa4-ad5d266bd7ad | relation:ValidatedBy | https://climateKG.org/entity/3f037b60-c58c-42df-8f19-32910d0055a5 |
| hsdo_Experiment → hsdo_Instrument | https://climateKG.org/entity/17b1489c-fba7-4252-bf23-b981148343f1 | relation:ValidatedBy | https://climateKG.org/entity/451995e8-a883-4468-abfd-a0e211ca9b72 |
| hsdo_Instrument → hsdo_Project | https://climateKG.org/entity/1ce21438-4c23-4bb5-b99a-da98622cdd02 | relation:ValidatedBy | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 |
| hsdo_Models → hsdo_Instrument | https://climateKG.org/entity/bbd90aa4-fe5e-4580-a51d-90d7568a9fee | relation:ValidatedBy | https://climateKG.org/entity/9cd1c7aa-7949-4b44-bedd-381b1ba9394c |
| hsdo_Models → hsdo_Platform | https://climateKG.org/entity/fc94343c-1809-431f-b3da-8ba5b887dda9 | relation:ValidatedBy | https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e |
| hsdo_Instrument → hsdo_Instrument | https://climateKG.org/entity/bb5002a8-6ff2-43dd-b0c9-8f9a76e11cb5 | relation:ValidatedBy | https://climateKG.org/entity/b62575f6-25e9-4a50-b0f6-a45dbf22c8d4 |
| hsdo_Instrument → hsdo_Models | https://climateKG.org/entity/2878f334-35dc-47a7-a3ae-8c5da1adccd3 | relation:ValidatedBy | https://climateKG.org/entity/c5b13fa4-0069-40ce-85cb-bfbab34c2058 |
| hsdo_Experiment → hsdo_Science_Keyword | https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049 | relation:ValidatedBy | https://climateKG.org/entity/29dbe37e-22e6-4d02-844f-60359fbbc130 |
| hsdo_Experiment → hsdo_Experiment | https://climateKG.org/entity/2be0af28-a6b8-4fce-82e4-1ad86788a4d5 | relation:ValidatedBy | https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049 |
| hsdo_Location → hsdo_Model | https://climateKG.org/entity/3898679c-68f8-42af-bbf1-1400955e0076 | relation:ValidatedBy | https://climateKG.org/entity/5fd5ccc2-5edb-4823-940d-03a290a5c5fc |
| hsdo_Instrument → hsdo_Model | https://climateKG.org/entity/db6471b5-3c29-4a85-bded-cf6e0fbf808d | relation:ValidatedBy | https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58 |
| hsdo_Provider → hsdo_Model | https://climateKG.org/entity/40924daf-07bf-4bab-ac78-9b79be30878e | relation:ValidatedBy | https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58 |
| hsdo_Institution → hsdo_Platform | https://climateKG.org/entity/b62469fa-105e-4e2c-b621-5915a86c93e1 | relation:ValidatedBy | https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e |
| hsdo_Model → hsdo_Instrument | https://climateKG.org/entity/8894d92c-be32-465b-ae08-e5de755a92fc | relation:ValidatedBy | https://climateKG.org/entity/bb5002a8-6ff2-43dd-b0c9-8f9a76e11cb5 |
| hsdo_Project → hsdo_Project | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:ValidatedBy | https://climateKG.org/entity/ab08cada-1a8e-4636-b834-18dc35266953 |
| hsdo_Model → hsdo_Science_Keyword | https://climateKG.org/entity/5b775d6e-de6c-4b11-b986-3c3a32cbf66d | relation:ValidatedBy | https://climateKG.org/entity/db9b56da-e05f-4d58-b9d5-34edc83ca650 |
| hsdo_Variable → hsdo_Experiment | https://climateKG.org/entity/5f69ee7f-5bc3-4974-840b-49998de06860 | relation:ValidatedBy | https://climateKG.org/entity/b283a59c-0e9a-469c-baf4-591b64cd4671 |
| hsdo_Instrument → hsdo_Science_Keyword | https://climateKG.org/entity/75662ed3-35c5-41ee-abba-51ce435d1b31 | relation:ValidatedBy | https://climateKG.org/entity/4cc8def9-a825-4ede-9e34-4e11cf89488d |
| hsdo_Instrument → hsdo_Variable | https://climateKG.org/entity/7b36ad79-8cf3-46a9-b26c-52f3a0f1eac9 | relation:ValidatedBy | https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e |
| hsdo_Instrument → hsdo_Platform | https://climateKG.org/entity/7b36ad79-8cf3-46a9-b26c-52f3a0f1eac9 | relation:ValidatedBy | https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e |
| hsdo_Model → hsdo_Experiment | https://climateKG.org/entity/8ad656db-1324-4e92-8273-5a765ca29282 | relation:ValidatedBy | https://climateKG.org/entity/4dbe7764-a2ea-4a19-b754-696c35ac3205 |
| hsdo_Models → hsdo_Model | https://climateKG.org/entity/bbd90aa4-fe5e-4580-a51d-90d7568a9fee | relation:ValidatedBy | https://climateKG.org/entity/3b20a141-8408-44b2-adf1-632ac9222c61 |
| hsdo_Location → hsdo_Experiment | https://climateKG.org/entity/bf0ddf9c-39ba-4b2d-91ac-63021d644276 | relation:ValidatedBy | https://climateKG.org/entity/a219dbe6-c095-4002-9fbe-012b31da839c |
| hsdo_Experiment → hsdo_Provider | https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049 | relation:ValidatedBy | https://climateKG.org/entity/6f346c4c-8c86-4825-a5de-4b3ca8e5de6f |
| hsdo_Project → hsdo_Experiment | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:ValidatedBy | https://climateKG.org/entity/17b1489c-fba7-4252-bf23-b981148343f1 |
| hsdo_Cmip6_Source_Id → hsdo_Platform | https://climateKG.org/entity/df0ba39b-7461-4cee-8660-c80fee72e96b | relation:ValidatedBy | https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e |
| hsdo_Models → hsdo_Dataset | https://climateKG.org/entity/fc94343c-1809-431f-b3da-8ba5b887dda9 | relation:ValidatedBy | https://climateKG.org/entity/a0b26420-3a13-4742-8d6f-391dc5c49d64 |
| hsdo_Project → hsdo_Model | https://climateKG.org/entity/128c5952-616a-4e81-b961-b98c5af0ec29 | relation:ValidatedBy | https://climateKG.org/entity/6fb2817f-c3e3-4332-85ad-79f74227e6bc |


## Comments

* 1 occurrences with subject type hsdo_Models and object type hsdo_Project.
* 2 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.
* 1 occurrences with subject type hsdo_Instrument and object type hsdo_Project.
* 2 occurrences with subject type hsdo_Models and object type hsdo_Instrument.
* 2 occurrences with subject type hsdo_Models and object type hsdo_Platform.
* 3 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.
* 1 occurrences with subject type hsdo_Instrument and object type hsdo_Models.
* 2 occurrences with subject type hsdo_Experiment and object type hsdo_Science_Keyword.
* 1 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Location and object type hsdo_Model.
* 4 occurrences with subject type hsdo_Instrument and object type hsdo_Model.
* 1 occurrences with subject type hsdo_Provider and object type hsdo_Model.
* 2 occurrences with subject type hsdo_Institution and object type hsdo_Platform.
* 2 occurrences with subject type hsdo_Model and object type hsdo_Instrument.
* 2 occurrences with subject type hsdo_Project and object type hsdo_Project.
* 1 occurrences with subject type hsdo_Model and object type hsdo_Science_Keyword.
* 1 occurrences with subject type hsdo_Variable and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Instrument and object type hsdo_Science_Keyword.
* 1 occurrences with subject type hsdo_Instrument and object type hsdo_Variable.
* 1 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.
* 1 occurrences with subject type hsdo_Model and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Models and object type hsdo_Model.
* 1 occurrences with subject type hsdo_Location and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.
* 3 occurrences with subject type hsdo_Project and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Platform.
* 3 occurrences with subject type hsdo_Models and object type hsdo_Dataset.
* 1 occurrences with subject type hsdo_Project and object type hsdo_Model.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:ValidatedBy |
| native | climatepub4-kg/:relation_ValidatedBy |




## LinkML Source

<details>
```yaml
name: relation_ValidatedBy
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type hsdo_Models and object type hsdo_Project.
- 2 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.
- 1 occurrences with subject type hsdo_Instrument and object type hsdo_Project.
- 2 occurrences with subject type hsdo_Models and object type hsdo_Instrument.
- 2 occurrences with subject type hsdo_Models and object type hsdo_Platform.
- 3 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.
- 1 occurrences with subject type hsdo_Instrument and object type hsdo_Models.
- 2 occurrences with subject type hsdo_Experiment and object type hsdo_Science_Keyword.
- 1 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Location and object type hsdo_Model.
- 4 occurrences with subject type hsdo_Instrument and object type hsdo_Model.
- 1 occurrences with subject type hsdo_Provider and object type hsdo_Model.
- 2 occurrences with subject type hsdo_Institution and object type hsdo_Platform.
- 2 occurrences with subject type hsdo_Model and object type hsdo_Instrument.
- 2 occurrences with subject type hsdo_Project and object type hsdo_Project.
- 1 occurrences with subject type hsdo_Model and object type hsdo_Science_Keyword.
- 1 occurrences with subject type hsdo_Variable and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Instrument and object type hsdo_Science_Keyword.
- 1 occurrences with subject type hsdo_Instrument and object type hsdo_Variable.
- 1 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.
- 1 occurrences with subject type hsdo_Model and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Models and object type hsdo_Model.
- 1 occurrences with subject type hsdo_Location and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.
- 3 occurrences with subject type hsdo_Project and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Platform.
- 3 occurrences with subject type hsdo_Models and object type hsdo_Dataset.
- 1 occurrences with subject type hsdo_Project and object type hsdo_Model.
examples:
- description: hsdo_Models → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/3f037b60-c58c-42df-8f19-32910d0055a5
    example_object_type: hsdo_Project
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/063177a9-14cd-4750-9aa4-ad5d266bd7ad
    example_subject_type: hsdo_Models
- description: hsdo_Experiment → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/451995e8-a883-4468-abfd-a0e211ca9b72
    example_object_type: hsdo_Instrument
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/17b1489c-fba7-4252-bf23-b981148343f1
    example_subject_type: hsdo_Experiment
- description: hsdo_Instrument → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_object_type: hsdo_Project
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/1ce21438-4c23-4bb5-b99a-da98622cdd02
    example_subject_type: hsdo_Instrument
- description: hsdo_Models → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/9cd1c7aa-7949-4b44-bedd-381b1ba9394c
    example_object_type: hsdo_Instrument
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/bbd90aa4-fe5e-4580-a51d-90d7568a9fee
    example_subject_type: hsdo_Models
- description: hsdo_Models → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e
    example_object_type: hsdo_Platform
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/fc94343c-1809-431f-b3da-8ba5b887dda9
    example_subject_type: hsdo_Models
- description: hsdo_Instrument → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/b62575f6-25e9-4a50-b0f6-a45dbf22c8d4
    example_object_type: hsdo_Instrument
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/bb5002a8-6ff2-43dd-b0c9-8f9a76e11cb5
    example_subject_type: hsdo_Instrument
- description: hsdo_Instrument → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/c5b13fa4-0069-40ce-85cb-bfbab34c2058
    example_object_type: hsdo_Models
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/2878f334-35dc-47a7-a3ae-8c5da1adccd3
    example_subject_type: hsdo_Instrument
- description: hsdo_Experiment → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/29dbe37e-22e6-4d02-844f-60359fbbc130
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
    example_object_type: hsdo_Experiment
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/2be0af28-a6b8-4fce-82e4-1ad86788a4d5
    example_subject_type: hsdo_Experiment
- description: hsdo_Location → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/5fd5ccc2-5edb-4823-940d-03a290a5c5fc
    example_object_type: hsdo_Model
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/3898679c-68f8-42af-bbf1-1400955e0076
    example_subject_type: hsdo_Location
- description: hsdo_Instrument → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58
    example_object_type: hsdo_Model
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/db6471b5-3c29-4a85-bded-cf6e0fbf808d
    example_subject_type: hsdo_Instrument
- description: hsdo_Provider → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58
    example_object_type: hsdo_Model
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/40924daf-07bf-4bab-ac78-9b79be30878e
    example_subject_type: hsdo_Provider
- description: hsdo_Institution → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e
    example_object_type: hsdo_Platform
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/b62469fa-105e-4e2c-b621-5915a86c93e1
    example_subject_type: hsdo_Institution
- description: hsdo_Model → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/bb5002a8-6ff2-43dd-b0c9-8f9a76e11cb5
    example_object_type: hsdo_Instrument
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/8894d92c-be32-465b-ae08-e5de755a92fc
    example_subject_type: hsdo_Model
- description: hsdo_Project → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/ab08cada-1a8e-4636-b834-18dc35266953
    example_object_type: hsdo_Project
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Model → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/db9b56da-e05f-4d58-b9d5-34edc83ca650
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/5b775d6e-de6c-4b11-b986-3c3a32cbf66d
    example_subject_type: hsdo_Model
- description: hsdo_Variable → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/b283a59c-0e9a-469c-baf4-591b64cd4671
    example_object_type: hsdo_Experiment
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/5f69ee7f-5bc3-4974-840b-49998de06860
    example_subject_type: hsdo_Variable
- description: hsdo_Instrument → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/4cc8def9-a825-4ede-9e34-4e11cf89488d
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/75662ed3-35c5-41ee-abba-51ce435d1b31
    example_subject_type: hsdo_Instrument
- description: hsdo_Instrument → hsdo_Variable
  object:
    example_object: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    example_object_type: hsdo_Variable
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/7b36ad79-8cf3-46a9-b26c-52f3a0f1eac9
    example_subject_type: hsdo_Instrument
- description: hsdo_Instrument → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e
    example_object_type: hsdo_Platform
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/7b36ad79-8cf3-46a9-b26c-52f3a0f1eac9
    example_subject_type: hsdo_Instrument
- description: hsdo_Model → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/4dbe7764-a2ea-4a19-b754-696c35ac3205
    example_object_type: hsdo_Experiment
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/8ad656db-1324-4e92-8273-5a765ca29282
    example_subject_type: hsdo_Model
- description: hsdo_Models → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/3b20a141-8408-44b2-adf1-632ac9222c61
    example_object_type: hsdo_Model
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/bbd90aa4-fe5e-4580-a51d-90d7568a9fee
    example_subject_type: hsdo_Models
- description: hsdo_Location → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/a219dbe6-c095-4002-9fbe-012b31da839c
    example_object_type: hsdo_Experiment
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/bf0ddf9c-39ba-4b2d-91ac-63021d644276
    example_subject_type: hsdo_Location
- description: hsdo_Experiment → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/6f346c4c-8c86-4825-a5de-4b3ca8e5de6f
    example_object_type: hsdo_Provider
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
    example_subject_type: hsdo_Experiment
- description: hsdo_Project → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/17b1489c-fba7-4252-bf23-b981148343f1
    example_object_type: hsdo_Experiment
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Cmip6_Source_Id → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e
    example_object_type: hsdo_Platform
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/df0ba39b-7461-4cee-8660-c80fee72e96b
    example_subject_type: hsdo_Cmip6_Source_Id
- description: hsdo_Models → hsdo_Dataset
  object:
    example_object: https://climateKG.org/entity/a0b26420-3a13-4742-8d6f-391dc5c49d64
    example_object_type: hsdo_Dataset
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/fc94343c-1809-431f-b3da-8ba5b887dda9
    example_subject_type: hsdo_Models
- description: hsdo_Project → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/6fb2817f-c3e3-4332-85ad-79f74227e6bc
    example_object_type: hsdo_Model
    example_predicate: relation:ValidatedBy
    example_subject: https://climateKG.org/entity/128c5952-616a-4e81-b961-b98c5af0ec29
    example_subject_type: hsdo_Project
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:ValidatedBy
alias: relation_ValidatedBy
domain_of:
- hsdo_Cmip6_Source_Id
- hsdo_Experiment
- hsdo_Institution
- hsdo_Instrument
- hsdo_Location
- hsdo_Model
- hsdo_Models
- hsdo_Project
- hsdo_Provider
- hsdo_Variable
range: Any
any_of:
- range: hsdo_Models
- range: hsdo_Variable
- range: hsdo_Provider
- range: hsdo_Project
- range: hsdo_Model
- range: hsdo_Dataset
- range: hsdo_Instrument
- range: hsdo_Platform
- range: hsdo_Science_Keyword
- range: hsdo_Experiment

```
</details>