

# Slot: relation_UsedIn


_No slot (predicate) description specified_





URI: [relation:UsedIn](http://relation.org/UsedIn)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPlatform](../classes/HsdoPlatform.md) | No class (type) description specified |  no  |
| [HsdoDataFormat](../classes/HsdoDataFormat.md) | No class (type) description specified |  no  |
| [HsdoInstrument](../classes/HsdoInstrument.md) | No class (type) description specified |  no  |
| [HsdoChronostratigraphicUnit](../classes/HsdoChronostratigraphicUnit.md) | No class (type) description specified |  no  |
| [HsdoDataset](../classes/HsdoDataset.md) | A body of structured information describing some topic(s) of interest |  no  |
| [HsdoExperiment](../classes/HsdoExperiment.md) | No class (type) description specified |  no  |
| [HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md) | No class (type) description specified |  no  |
| [HsdoProvider](../classes/HsdoProvider.md) | No class (type) description specified |  no  |
| [HsdoInstitution](../classes/HsdoInstitution.md) | No class (type) description specified |  no  |
| [HsdoVariable](../classes/HsdoVariable.md) | No class (type) description specified |  no  |
| [HsdoModel](../classes/HsdoModel.md) | No class (type) description specified |  no  |
| [HsdoProject](../classes/HsdoProject.md) | An enterprise (potentially individual but typically collaborative), planned t... |  no  |
| [HsdoModels](../classes/HsdoModels.md) | No class (type) description specified |  no  |
| [HsdoScienceKeyword](../classes/HsdoScienceKeyword.md) | No class (type) description specified |  no  |
| [HsdoMeasurementName](../classes/HsdoMeasurementName.md) | No class (type) description specified |  no  |
| [HsdoLocation](../classes/HsdoLocation.md) | No class (type) description specified |  no  |
| [HsdoRelatedUrlContentType](../classes/HsdoRelatedUrlContentType.md) | No class (type) description specified |  no  |
| [HsdoTemporalResolutionRange](../classes/HsdoTemporalResolutionRange.md) | No class (type) description specified |  no  |
| [HsdoActivity](../classes/HsdoActivity.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoPlatform](../classes/HsdoPlatform.md)&nbsp;or&nbsp;<br />[HsdoMeasurementName](../classes/HsdoMeasurementName.md)&nbsp;or&nbsp;<br />[HsdoVariable](../classes/HsdoVariable.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoChronostratigraphicUnit](../classes/HsdoChronostratigraphicUnit.md)&nbsp;or&nbsp;<br />[HsdoLocation](../classes/HsdoLocation.md)&nbsp;or&nbsp;<br />[HsdoProject](../classes/HsdoProject.md)&nbsp;or&nbsp;<br />[HsdoModel](../classes/HsdoModel.md)&nbsp;or&nbsp;<br />[HsdoInstitution](../classes/HsdoInstitution.md)&nbsp;or&nbsp;<br />[HsdoActivity](../classes/HsdoActivity.md)&nbsp;or&nbsp;<br />[HsdoDataset](../classes/HsdoDataset.md)&nbsp;or&nbsp;<br />[HsdoDataFormat](../classes/HsdoDataFormat.md)&nbsp;or&nbsp;<br />[HsdoInstrument](../classes/HsdoInstrument.md)&nbsp;or&nbsp;<br />[HsdoModels](../classes/HsdoModels.md)&nbsp;or&nbsp;<br />[HsdoScienceKeyword](../classes/HsdoScienceKeyword.md)&nbsp;or&nbsp;<br />[HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Model → hsdo_Location | https://climateKG.org/entity/f8845bec-c628-4185-aac1-4af22481c024 | relation:UsedIn | https://climateKG.org/entity/bfbfd84c-6bf0-412f-9e75-1bad5241c339 |
| hsdo_Model → hsdo_Model | https://climateKG.org/entity/f1e6caa5-2c97-407d-a0db-7bf01794d8e3 | relation:UsedIn | https://climateKG.org/entity/8894d92c-be32-465b-ae08-e5de755a92fc |
| hsdo_Experiment → hsdo_Instrument | https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf | relation:UsedIn | https://climateKG.org/entity/ae02541a-4968-4573-8569-0f4a02575ab2 |
| hsdo_Experiment → hsdo_Science_Keyword | https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d | relation:UsedIn | https://climateKG.org/entity/2e69c08b-ee0f-426c-a8d2-dc50876f76c2 |
| hsdo_Experiment → hsdo_Experiment | https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d | relation:UsedIn | https://climateKG.org/entity/79841056-b651-439c-b638-439e94731d31 |
| hsdo_Experiment → hsdo_Project | https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf | relation:UsedIn | https://climateKG.org/entity/6ffd7617-25fd-4464-bbd3-fc02e33ffafb |
| hsdo_Models → hsdo_Experiment | https://climateKG.org/entity/f88c4559-fc4b-4b4a-ac57-0f15bb24e8e0 | relation:UsedIn | https://climateKG.org/entity/cbab6fb9-2240-4fb4-97c0-6ec918ddd729 |
| hsdo_Models → hsdo_Activity | https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9 | relation:UsedIn | https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58 |
| hsdo_Models → hsdo_Project | https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9 | relation:UsedIn | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 |
| hsdo_Instrument → hsdo_Experiment | https://climateKG.org/entity/fe4392b0-13a9-43ff-bacc-f44a65aed4fa | relation:UsedIn | https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049 |
| hsdo_Instrument → hsdo_Model | https://climateKG.org/entity/fe4392b0-13a9-43ff-bacc-f44a65aed4fa | relation:UsedIn | https://climateKG.org/entity/31ca2413-f257-4ceb-849a-68538efecfee |
| hsdo_Model → hsdo_Instrument | https://climateKG.org/entity/f1e6caa5-2c97-407d-a0db-7bf01794d8e3 | relation:UsedIn | https://climateKG.org/entity/b62575f6-25e9-4a50-b0f6-a45dbf22c8d4 |
| hsdo_Model → hsdo_Experiment | https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58 | relation:UsedIn | https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049 |
| hsdo_Model → hsdo_Activity | https://climateKG.org/entity/f860ed88-991f-4b52-90b9-fc8d4046a598 | relation:UsedIn | https://climateKG.org/entity/68885007-d975-4f24-bdd5-dd19b246bdf6 |
| hsdo_Instrument → hsdo_Instrument | https://climateKG.org/entity/fe37b7a7-b6ca-4880-8dcf-16973cd8ecc8 | relation:UsedIn | https://climateKG.org/entity/fcc9411c-a1c9-415d-a16c-75c42f2cec45 |
| hsdo_Instrument → hsdo_Location | https://climateKG.org/entity/fb23c170-9164-40cf-aed0-5a3fbd531fad | relation:UsedIn | https://climateKG.org/entity/8b7f66ea-d481-4641-9dbf-da90ca3ad9c9 |
| hsdo_Project → hsdo_Instrument | https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab | relation:UsedIn | https://climateKG.org/entity/c811bdaf-649f-4e23-b495-940d64e675f4 |
| hsdo_Models → hsdo_Model | https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9 | relation:UsedIn | https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58 |
| hsdo_Models → hsdo_Location | https://climateKG.org/entity/f88c4559-fc4b-4b4a-ac57-0f15bb24e8e0 | relation:UsedIn | https://climateKG.org/entity/0f50133b-1ef8-4c67-97a3-ac0604a41fc8 |
| hsdo_Models → hsdo_Instrument | https://climateKG.org/entity/c266a473-338f-4fe9-965c-f8ae853ff57b | relation:UsedIn | https://climateKG.org/entity/2d580f50-3951-4601-9b08-7fbea94eebef |
| hsdo_Models → hsdo_Models | https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9 | relation:UsedIn | https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9 |
| hsdo_Instrument → hsdo_Science_Keyword | https://climateKG.org/entity/78fb5691-136d-40f8-a834-6e6f4cd768ff | relation:UsedIn | https://climateKG.org/entity/ea936862-2c98-41e5-8514-6b7288a5f941 |
| hsdo_Instrument → hsdo_Platform | https://climateKG.org/entity/085edf65-1c8c-414a-b8e4-a1a08ff08f22 | relation:UsedIn | https://climateKG.org/entity/a96e6cd6-0f35-491d-8198-7551d03e1cbc |
| hsdo_Science_Keyword → hsdo_Experiment | https://climateKG.org/entity/ed925b43-db83-4cbb-8347-3dc0081bb8f4 | relation:UsedIn | https://climateKG.org/entity/00ce4800-70ef-4346-aa15-0554280d0896 |
| hsdo_Model → hsdo_Project | https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58 | relation:UsedIn | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 |
| hsdo_Instrument → hsdo_Models | https://climateKG.org/entity/ae02541a-4968-4573-8569-0f4a02575ab2 | relation:UsedIn | https://climateKG.org/entity/063177a9-14cd-4750-9aa4-ad5d266bd7ad |
| hsdo_Provider → hsdo_Models | https://climateKG.org/entity/c297fda0-848a-4a9b-85be-86f29c92f212 | relation:UsedIn | https://climateKG.org/entity/24b382cb-5ed5-46f5-9134-1e34462f9f20 |
| hsdo_Cmip6_Source_Id → hsdo_Location | https://climateKG.org/entity/f083ae80-224b-4453-8a18-d1b13d9d2f90 | relation:UsedIn | https://climateKG.org/entity/89bb4e2b-dd39-44ed-a4d3-2b205e9fa68a |
| hsdo_Cmip6_Source_Id → hsdo_Chronostratigraphic_Unit | https://climateKG.org/entity/0cd4d2c4-ebfa-4759-b7aa-f9982122f581 | relation:UsedIn | https://climateKG.org/entity/db06b2a9-4ed5-4222-8533-fbf3ed3bdc23 |
| hsdo_Science_Keyword → hsdo_Provider | https://climateKG.org/entity/0de668aa-cc97-482d-a0eb-cddcb1a705b6 | relation:UsedIn | https://climateKG.org/entity/4e366444-01ea-4517-9d93-56f55ddf41b7 |
| hsdo_Location → hsdo_Instrument | https://climateKG.org/entity/fd03d204-4391-4e98-8142-8b8efa235231 | relation:UsedIn | https://climateKG.org/entity/33f20afe-5ce2-43e9-9676-c5f664fbc324 |
| hsdo_Experiment → hsdo_Model | https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d | relation:UsedIn | https://climateKG.org/entity/8e484ec4-50fd-4c08-9c96-6ad483e170ad |
| hsdo_Science_Keyword → hsdo_Location | https://climateKG.org/entity/cf3d1728-7606-4561-a0dd-116b4dbec21f | relation:UsedIn | https://climateKG.org/entity/78369c58-beaa-46f2-b286-dd2540634556 |
| hsdo_Science_Keyword → hsdo_Model | https://climateKG.org/entity/bd24a9a9-7d52-4c29-b2a0-6cefd216ae78 | relation:UsedIn | https://climateKG.org/entity/8680cb49-1637-4a47-a5fd-f39d4e618e45 |
| hsdo_Science_Keyword → hsdo_Measurement_Name | https://climateKG.org/entity/d2e93932-0231-4b23-af2f-217c6315a95e | relation:UsedIn | https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9 |
| hsdo_Variable → hsdo_Models | https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e | relation:UsedIn | https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9 |
| hsdo_Variable → hsdo_Experiment | https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa | relation:UsedIn | https://climateKG.org/entity/79841056-b651-439c-b638-439e94731d31 |
| hsdo_Variable → hsdo_Model | https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e | relation:UsedIn | https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58 |
| hsdo_Variable → hsdo_Instrument | https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e | relation:UsedIn | https://climateKG.org/entity/ae02541a-4968-4573-8569-0f4a02575ab2 |
| hsdo_Location → hsdo_Model | https://climateKG.org/entity/fa57b0a0-9723-4195-bdd1-4f26aefa0e07 | relation:UsedIn | https://climateKG.org/entity/0399b52c-e3de-4dcc-9eb6-b1e3acf2cf1b |
| hsdo_Location → hsdo_Measurement_Name | https://climateKG.org/entity/162e2243-3266-4999-b352-d8a1a9dc82ac | relation:UsedIn | https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e |
| hsdo_Model → hsdo_Models | https://climateKG.org/entity/defd2c00-64e3-4986-9061-feade19f972f | relation:UsedIn | https://climateKG.org/entity/c5b13fa4-0069-40ce-85cb-bfbab34c2058 |
| hsdo_Provider → hsdo_Location | https://climateKG.org/entity/f6e72cf4-b814-4c7d-a013-9e499bcdc773 | relation:UsedIn | https://climateKG.org/entity/c46d59a8-d874-4db8-87f5-d59ecbb79a29 |
| hsdo_Science_Keyword → hsdo_Instrument | https://climateKG.org/entity/ef36cb15-ad64-4bdc-9331-42cc5b493671 | relation:UsedIn | https://climateKG.org/entity/0b4081fa-5233-4484-bc82-706976defa0e |
| hsdo_Measurement_Name → hsdo_Location | https://climateKG.org/entity/1f697c83-969d-48ee-87b8-245b11f7e24f | relation:UsedIn | https://climateKG.org/entity/dcef091b-18b5-48bf-b191-69ab7a3511f1 |
| hsdo_Location → hsdo_Location | https://climateKG.org/entity/eb784368-9b92-49b0-afc5-ea820e996f33 | relation:UsedIn | https://climateKG.org/entity/fa57b0a0-9723-4195-bdd1-4f26aefa0e07 |
| hsdo_Experiment → hsdo_Location | https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf | relation:UsedIn | https://climateKG.org/entity/fa57b0a0-9723-4195-bdd1-4f26aefa0e07 |
| hsdo_Experiment → hsdo_Models | https://climateKG.org/entity/7f1f0059-de73-4a9e-9200-1bbcd2d6e789 | relation:UsedIn | https://climateKG.org/entity/c8a4a768-cdad-42ab-b2b5-3100440ffd8f |
| hsdo_Experiment → hsdo_Activity | https://climateKG.org/entity/cbab6fb9-2240-4fb4-97c0-6ec918ddd729 | relation:UsedIn | https://climateKG.org/entity/8f528b66-670d-4198-b014-7fdc9e1f6890 |
| hsdo_Instrument → hsdo_Provider | https://climateKG.org/entity/543135bc-7749-49ca-89af-b108cac1afaa | relation:UsedIn | https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5 |
| hsdo_Instrument → hsdo_Project | https://climateKG.org/entity/cb8f849f-bbe5-4c62-9a50-d729718ad980 | relation:UsedIn | https://climateKG.org/entity/08684c69-224d-4c4a-a1a7-ea3933ac9081 |
| hsdo_Project → hsdo_Institution | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:UsedIn | https://climateKG.org/entity/e8df7edd-a176-45c9-8515-3a520948ef63 |
| hsdo_Location → hsdo_Variable | https://climateKG.org/entity/3d4e44c4-5d99-4a9b-8388-43c63533ee97 | relation:UsedIn | https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e |
| hsdo_Location → hsdo_Experiment | https://climateKG.org/entity/ecc4a2bb-f195-4296-b300-c1227221b688 | relation:UsedIn | https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf |
| hsdo_Provider → hsdo_Experiment | https://climateKG.org/entity/2b890e5b-1b50-4454-90a9-538dd891da9a | relation:UsedIn | https://climateKG.org/entity/aef9855c-70e1-4e22-aa25-8ccd23176d3b |
| hsdo_Location → hsdo_Models | https://climateKG.org/entity/df160e31-ae45-41a4-9093-a80fe5303cea | relation:UsedIn | https://climateKG.org/entity/3668de06-8a7d-4667-beb8-d04dcac619b0 |
| hsdo_Platform → hsdo_Experiment | https://climateKG.org/entity/fdb04105-e8ba-4a83-9c35-ed3c931ccc9f | relation:UsedIn | https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf |
| hsdo_Variable → hsdo_Location | https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e | relation:UsedIn | https://climateKG.org/entity/2b424588-9bb6-418a-b1c7-06b93be4ba28 |
| hsdo_Variable → hsdo_Institution | https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e | relation:UsedIn | https://climateKG.org/entity/e2f64d50-da88-4d6a-abfa-4b0b7e99312e |
| hsdo_Variable → hsdo_Project | https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e | relation:UsedIn | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 |
| hsdo_Instrument → hsdo_Data_Format | https://climateKG.org/entity/fb23c170-9164-40cf-aed0-5a3fbd531fad | relation:UsedIn | https://climateKG.org/entity/191a9f1d-cfd3-469d-86b8-ce2d2355034a |
| hsdo_Models → hsdo_Science_Keyword | https://climateKG.org/entity/fc94343c-1809-431f-b3da-8ba5b887dda9 | relation:UsedIn | https://climateKG.org/entity/ef36cb15-ad64-4bdc-9331-42cc5b493671 |
| hsdo_Platform → hsdo_Model | https://climateKG.org/entity/f24c4f33-5b89-4e8d-8de7-296078a7f18a | relation:UsedIn | https://climateKG.org/entity/2bfd42f1-0453-4c33-a21e-74df3ad64813 |
| hsdo_Platform → hsdo_Instrument | https://climateKG.org/entity/f959e3c5-f014-40b7-a134-4d41b616f79d | relation:UsedIn | https://climateKG.org/entity/267b7dc6-ffae-4d76-a145-bca4e80313b3 |
| hsdo_Platform → hsdo_Project | https://climateKG.org/entity/9830be3b-80ea-4e8c-af46-526882b7f26d | relation:UsedIn | https://climateKG.org/entity/4d569982-00c1-4e7f-b357-0bf0b624998d |
| hsdo_Project → hsdo_Location | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:UsedIn | https://climateKG.org/entity/a4202721-0cba-4fa1-853f-890f146b04f9 |
| hsdo_Data_Format → hsdo_Instrument | https://climateKG.org/entity/d0b3505e-77bb-45a0-83fe-787bc3812b67 | relation:UsedIn | https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb |
| hsdo_Instrument → hsdo_Measurement_Name | https://climateKG.org/entity/3ce7f4f0-d2db-4352-8762-d88296f7aa15 | relation:UsedIn | https://climateKG.org/entity/1f697c83-969d-48ee-87b8-245b11f7e24f |
| hsdo_Instrument → hsdo_Activity | https://climateKG.org/entity/ba008542-5c6f-462a-8ddf-21e54cbf3034 | relation:UsedIn | https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58 |
| hsdo_Science_Keyword → hsdo_Variable | https://climateKG.org/entity/3de6fa74-bb80-4bc6-ae60-1e6fe8ae6c67 | relation:UsedIn | https://climateKG.org/entity/7471c00f-60c7-4ac3-a6db-d49020f22014 |
| hsdo_Experiment → hsdo_Provider | https://climateKG.org/entity/aef9855c-70e1-4e22-aa25-8ccd23176d3b | relation:UsedIn | https://climateKG.org/entity/4e366444-01ea-4517-9d93-56f55ddf41b7 |
| hsdo_Project → hsdo_Experiment | https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab | relation:UsedIn | https://climateKG.org/entity/b7eb8278-0dc3-4121-87ea-14173279dfb4 |
| hsdo_Location → hsdo_Platform | https://climateKG.org/entity/46e4aaa4-349c-4049-a910-035391360010 | relation:UsedIn | https://climateKG.org/entity/82fdb39c-4fe8-4e2b-9dcf-67ceb4c6d8b9 |
| hsdo_Provider → hsdo_Instrument | https://climateKG.org/entity/a463163e-8e86-4086-8b10-8fd6a95fca4a | relation:UsedIn | https://climateKG.org/entity/418a8c09-a533-4f9a-ac4b-7078107980bf |
| hsdo_Provider → hsdo_Science_Keyword | https://climateKG.org/entity/5a5c7e50-e5a0-45f2-be81-0cb96b32cb1e | relation:UsedIn | https://climateKG.org/entity/dfc20833-d79a-4976-91fd-db9f3efc7822 |
| hsdo_Location → hsdo_Data_Format | https://climateKG.org/entity/f3b5489d-6723-40bf-bd55-68a0f2fc1874 | relation:UsedIn | https://climateKG.org/entity/d896a8cc-4fce-4a8d-86bc-185b324fab2b |
| hsdo_Project → hsdo_Project | https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab | relation:UsedIn | https://climateKG.org/entity/01e75216-1cee-4cc3-b31d-83019730da85 |
| hsdo_Project → hsdo_Model | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:UsedIn | https://climateKG.org/entity/c85170ef-cf60-470e-b9d0-f22c138911fd |
| hsdo_Activity → hsdo_Model | https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7 | relation:UsedIn | https://climateKG.org/entity/13df63e8-85ad-405d-9b43-256371e259c0 |
| hsdo_Activity → hsdo_Activity | https://climateKG.org/entity/8f528b66-670d-4198-b014-7fdc9e1f6890 | relation:UsedIn | https://climateKG.org/entity/5796ebd9-7dcb-4968-b876-1e678484cc62 |
| hsdo_Activity → hsdo_Experiment | https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58 | relation:UsedIn | https://climateKG.org/entity/99ea6719-b751-4a4f-95d4-aaa02e961bc1 |
| hsdo_Activity → hsdo_Instrument | https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7 | relation:UsedIn | https://climateKG.org/entity/fe2719de-c5c8-4ce6-8230-1d16c8155991 |
| hsdo_Activity → hsdo_Project | https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7 | relation:UsedIn | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 |
| hsdo_Model → hsdo_Science_Keyword | https://climateKG.org/entity/652349bd-f6f9-4c8d-8573-d71e05ad1208 | relation:UsedIn | https://climateKG.org/entity/e660d917-0c77-463c-a15b-e8061ed296f8 |
| hsdo_Science_Keyword → hsdo_Science_Keyword | https://climateKG.org/entity/d3055f47-258e-4556-a885-54cd1fff4680 | relation:UsedIn | https://climateKG.org/entity/a90306f0-353c-4083-941a-0973a6fd6584 |
| hsdo_Data_Format → hsdo_Location | https://climateKG.org/entity/6231402a-7e4c-42d9-802d-7184eb812f46 | relation:UsedIn | https://climateKG.org/entity/1ac29014-a695-49a1-93d8-bf32d2684e44 |
| hsdo_Activity → hsdo_Location | https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7 | relation:UsedIn | https://climateKG.org/entity/d34c3aa5-81b8-4b56-b298-5f33307815b0 |
| hsdo_Activity → hsdo_Models | https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7 | relation:UsedIn | https://climateKG.org/entity/5467feeb-5956-46b5-8d45-fc695339ff48 |
| hsdo_Chronostratigraphic_Unit → hsdo_Experiment | https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0 | relation:UsedIn | https://climateKG.org/entity/c7245882-84a1-4192-acfa-a758b5b9c151 |
| hsdo_Chronostratigraphic_Unit → hsdo_Chronostratigraphic_Unit | https://climateKG.org/entity/6cb96c3b-1a1c-4d26-a894-2638d5cd05d1 | relation:UsedIn | https://climateKG.org/entity/c7e7fb38-44ef-4c5b-aa1d-b3fdcf89d838 |
| hsdo_Cmip6_Source_Id → hsdo_Project | https://climateKG.org/entity/6f7a0a68-6387-4f49-84ea-9652139018f5 | relation:UsedIn | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 |
| hsdo_Cmip6_Source_Id → hsdo_Model | https://climateKG.org/entity/df0ba39b-7461-4cee-8660-c80fee72e96b | relation:UsedIn | https://climateKG.org/entity/ba7cc1c1-c5ef-43ff-9a2e-84629f0a94fa |
| hsdo_Model → hsdo_Platform | https://climateKG.org/entity/785f7c57-93c9-4fe0-8309-ff32aa59a637 | relation:UsedIn | https://climateKG.org/entity/67290503-94b9-4517-b5b6-063bba2bee27 |
| hsdo_Instrument → hsdo_Variable | https://climateKG.org/entity/a68048f4-181c-4c6c-9bfa-9e4171e9f237 | relation:UsedIn | https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa |
| hsdo_Temporal_Resolution_Range → hsdo_Experiment | https://climateKG.org/entity/7c5420a6-94e2-40ca-9dff-20309090d327 | relation:UsedIn | https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049 |
| hsdo_Instrument → hsdo_Dataset | https://climateKG.org/entity/804d4f03-ee93-4fc9-ada0-f3dc9a7a6706 | relation:UsedIn | https://climateKG.org/entity/2892e23f-5249-439d-8c0e-6c1d190b3beb |
| hsdo_Model → hsdo_Chronostratigraphic_Unit | https://climateKG.org/entity/8491e067-951e-4cba-9619-d376b5c628a0 | relation:UsedIn | https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0 |
| hsdo_Model → hsdo_Variable | https://climateKG.org/entity/8680cb49-1637-4a47-a5fd-f39d4e618e45 | relation:UsedIn | https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa |
| hsdo_Model → hsdo_Provider | https://climateKG.org/entity/8680cb49-1637-4a47-a5fd-f39d4e618e45 | relation:UsedIn | https://climateKG.org/entity/e85b6d64-a230-4c1d-99a5-c62be8af18c7 |
| hsdo_Project → hsdo_Models | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:UsedIn | https://climateKG.org/entity/fc94343c-1809-431f-b3da-8ba5b887dda9 |
| hsdo_Science_Keyword → hsdo_Models | https://climateKG.org/entity/90c21a67-6703-4b59-96ee-c2c602652c80 | relation:UsedIn | https://climateKG.org/entity/ca240508-9cd7-400e-9420-ad96f72195bd |
| hsdo_Related_Url_Content_Type → hsdo_Model | https://climateKG.org/entity/914cbb7e-5b20-4bcd-86e3-ffcfa26f0a73 | relation:UsedIn | https://climateKG.org/entity/5612b95e-cc41-4286-9946-e78506f70f59 |
| hsdo_Temporal_Resolution_Range → hsdo_Science_Keyword | https://climateKG.org/entity/99ef187e-6940-4c10-8d65-00d4426d493b | relation:UsedIn | https://climateKG.org/entity/fbc53539-ce4e-4e3e-bbd2-8270386616b4 |
| hsdo_Location → hsdo_Project | https://climateKG.org/entity/e1078fd4-fa6b-4c35-81ee-648bc086e9c5 | relation:UsedIn | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 |
| hsdo_Platform → hsdo_Science_Keyword | https://climateKG.org/entity/a96e6cd6-0f35-491d-8198-7551d03e1cbc | relation:UsedIn | https://climateKG.org/entity/d6464d91-2373-456f-85a7-a5019bdb1076 |
| hsdo_Platform → hsdo_Models | https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e | relation:UsedIn | https://climateKG.org/entity/eb539ad7-79ee-4d76-8e38-b298b2385626 |
| hsdo_Instrument → hsdo_Institution | https://climateKG.org/entity/cb8f849f-bbe5-4c62-9a50-d729718ad980 | relation:UsedIn | https://climateKG.org/entity/4315c66b-86e9-4127-a456-e549687012cf |
| hsdo_Institution → hsdo_Model | https://climateKG.org/entity/b62469fa-105e-4e2c-b621-5915a86c93e1 | relation:UsedIn | https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58 |
| hsdo_Location → hsdo_Science_Keyword | https://climateKG.org/entity/b6782a30-639e-4d70-8290-81683d248b1f | relation:UsedIn | https://climateKG.org/entity/e5a658d5-74db-4022-894f-edc8d297767a |
| hsdo_Variable → hsdo_Platform | https://climateKG.org/entity/ba70b595-5263-4ffd-97a2-f86ba91681ae | relation:UsedIn | https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e |
| hsdo_Platform → hsdo_Location | https://climateKG.org/entity/bac2e743-1d02-4868-8bd6-b8b8741e3794 | relation:UsedIn | https://climateKG.org/entity/5668f6df-ab5a-4991-9720-dda2faae7f3e |
| hsdo_Measurement_Name → hsdo_Model | https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e | relation:UsedIn | https://climateKG.org/entity/8ad656db-1324-4e92-8273-5a765ca29282 |
| hsdo_Provider → hsdo_Project | https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23 | relation:UsedIn | https://climateKG.org/entity/e23b4757-38f3-4be1-8d70-035dacb782f6 |
| hsdo_Cmip6_Source_Id → hsdo_Instrument | https://climateKG.org/entity/d0c16581-6951-4e8d-a0c1-97e9fcaa031a | relation:UsedIn | https://climateKG.org/entity/b62575f6-25e9-4a50-b0f6-a45dbf22c8d4 |
| hsdo_Project → hsdo_Science_Keyword | https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab | relation:UsedIn | https://climateKG.org/entity/0de668aa-cc97-482d-a0eb-cddcb1a705b6 |
| hsdo_Dataset → hsdo_Location | https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54 | relation:UsedIn | https://climateKG.org/entity/2ca1b865-5555-4375-aa81-72811335b695 |
| hsdo_Cmip6_Source_Id → hsdo_Experiment | https://climateKG.org/entity/d4548c1b-c0b1-47a9-a2ea-6000baa98647 | relation:UsedIn | https://climateKG.org/entity/e3f2ed37-dfb2-4d74-9aa7-efe0d67fdd54 |
| hsdo_Experiment → hsdo_Variable | https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049 | relation:UsedIn | https://climateKG.org/entity/1f1436a3-ac80-48e1-abbe-095fc74c9655 |
| hsdo_Institution → hsdo_Project | https://climateKG.org/entity/d9fbd2ea-803e-48b7-a1f2-774e6845cc1f | relation:UsedIn | https://climateKG.org/entity/b971f45d-3a45-4ef2-99df-d6b88bbc7cc3 |
| hsdo_Project → hsdo_Activity | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:UsedIn | https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7 |
| hsdo_Location → hsdo_Provider | https://climateKG.org/entity/ecc4a2bb-f195-4296-b300-c1227221b688 | relation:UsedIn | https://climateKG.org/entity/4e366444-01ea-4517-9d93-56f55ddf41b7 |
| hsdo_Provider → hsdo_Activity | https://climateKG.org/entity/e236abe1-c8c5-4bca-ab7d-89b5a0392d6b | relation:UsedIn | https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58 |
| hsdo_Project → hsdo_Provider | https://climateKG.org/entity/e23b4757-38f3-4be1-8d70-035dacb782f6 | relation:UsedIn | https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23 |
| hsdo_Provider → hsdo_Model | https://climateKG.org/entity/e8df433e-f868-4ad1-97e7-8610d60a86e3 | relation:UsedIn | https://climateKG.org/entity/b8a877b7-d867-4305-9053-3777e5dd330a |
| hsdo_Experiment → hsdo_Data_Format | https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf | relation:UsedIn | https://climateKG.org/entity/d0b3505e-77bb-45a0-83fe-787bc3812b67 |
| hsdo_Project → hsdo_Cmip6_Source_Id | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:UsedIn | https://climateKG.org/entity/f083ae80-224b-4453-8a18-d1b13d9d2f90 |
| hsdo_Measurement_Name → hsdo_Instrument | https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9 | relation:UsedIn | https://climateKG.org/entity/33f20afe-5ce2-43e9-9676-c5f664fbc324 |
| hsdo_Models → hsdo_Chronostratigraphic_Unit | https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9 | relation:UsedIn | https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0 |


## Comments

* 14 occurrences with subject type hsdo_Model and object type hsdo_Location.
* 17 occurrences with subject type hsdo_Model and object type hsdo_Model.
* 29 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.
* 2 occurrences with subject type hsdo_Experiment and object type hsdo_Science_Keyword.
* 46 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
* 20 occurrences with subject type hsdo_Experiment and object type hsdo_Project.
* 16 occurrences with subject type hsdo_Models and object type hsdo_Experiment.
* 11 occurrences with subject type hsdo_Models and object type hsdo_Activity.
* 27 occurrences with subject type hsdo_Models and object type hsdo_Project.
* 46 occurrences with subject type hsdo_Instrument and object type hsdo_Experiment.
* 37 occurrences with subject type hsdo_Instrument and object type hsdo_Model.
* 28 occurrences with subject type hsdo_Model and object type hsdo_Instrument.
* 16 occurrences with subject type hsdo_Model and object type hsdo_Experiment.
* 8 occurrences with subject type hsdo_Model and object type hsdo_Activity.
* 114 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.
* 44 occurrences with subject type hsdo_Instrument and object type hsdo_Location.
* 18 occurrences with subject type hsdo_Project and object type hsdo_Instrument.
* 16 occurrences with subject type hsdo_Models and object type hsdo_Model.
* 7 occurrences with subject type hsdo_Models and object type hsdo_Location.
* 7 occurrences with subject type hsdo_Models and object type hsdo_Instrument.
* 11 occurrences with subject type hsdo_Models and object type hsdo_Models.
* 5 occurrences with subject type hsdo_Instrument and object type hsdo_Science_Keyword.
* 1 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.
* 5 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Experiment.
* 10 occurrences with subject type hsdo_Model and object type hsdo_Project.
* 6 occurrences with subject type hsdo_Instrument and object type hsdo_Models.
* 2 occurrences with subject type hsdo_Provider and object type hsdo_Models.
* 8 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Location.
* 1 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Chronostratigraphic_Unit.
* 1 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Provider.
* 29 occurrences with subject type hsdo_Location and object type hsdo_Instrument.
* 15 occurrences with subject type hsdo_Experiment and object type hsdo_Model.
* 5 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Location.
* 7 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Model.
* 2 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Measurement_Name.
* 4 occurrences with subject type hsdo_Variable and object type hsdo_Models.
* 1 occurrences with subject type hsdo_Variable and object type hsdo_Experiment.
* 5 occurrences with subject type hsdo_Variable and object type hsdo_Model.
* 2 occurrences with subject type hsdo_Variable and object type hsdo_Instrument.
* 15 occurrences with subject type hsdo_Location and object type hsdo_Model.
* 1 occurrences with subject type hsdo_Location and object type hsdo_Measurement_Name.
* 4 occurrences with subject type hsdo_Model and object type hsdo_Models.
* 6 occurrences with subject type hsdo_Provider and object type hsdo_Location.
* 9 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Instrument.
* 1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Location.
* 17 occurrences with subject type hsdo_Location and object type hsdo_Location.
* 17 occurrences with subject type hsdo_Experiment and object type hsdo_Location.
* 7 occurrences with subject type hsdo_Experiment and object type hsdo_Models.
* 9 occurrences with subject type hsdo_Experiment and object type hsdo_Activity.
* 3 occurrences with subject type hsdo_Instrument and object type hsdo_Provider.
* 13 occurrences with subject type hsdo_Instrument and object type hsdo_Project.
* 3 occurrences with subject type hsdo_Project and object type hsdo_Institution.
* 2 occurrences with subject type hsdo_Location and object type hsdo_Variable.
* 25 occurrences with subject type hsdo_Location and object type hsdo_Experiment.
* 2 occurrences with subject type hsdo_Provider and object type hsdo_Experiment.
* 4 occurrences with subject type hsdo_Location and object type hsdo_Models.
* 4 occurrences with subject type hsdo_Platform and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Variable and object type hsdo_Location.
* 1 occurrences with subject type hsdo_Variable and object type hsdo_Institution.
* 1 occurrences with subject type hsdo_Variable and object type hsdo_Project.
* 4 occurrences with subject type hsdo_Instrument and object type hsdo_Data_Format.
* 3 occurrences with subject type hsdo_Models and object type hsdo_Science_Keyword.
* 4 occurrences with subject type hsdo_Platform and object type hsdo_Model.
* 6 occurrences with subject type hsdo_Platform and object type hsdo_Instrument.
* 4 occurrences with subject type hsdo_Platform and object type hsdo_Project.
* 8 occurrences with subject type hsdo_Project and object type hsdo_Location.
* 5 occurrences with subject type hsdo_Data_Format and object type hsdo_Instrument.
* 1 occurrences with subject type hsdo_Instrument and object type hsdo_Measurement_Name.
* 3 occurrences with subject type hsdo_Instrument and object type hsdo_Activity.
* 1 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Variable.
* 3 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.
* 14 occurrences with subject type hsdo_Project and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Location and object type hsdo_Platform.
* 3 occurrences with subject type hsdo_Provider and object type hsdo_Instrument.
* 2 occurrences with subject type hsdo_Provider and object type hsdo_Science_Keyword.
* 6 occurrences with subject type hsdo_Location and object type hsdo_Data_Format.
* 6 occurrences with subject type hsdo_Project and object type hsdo_Project.
* 8 occurrences with subject type hsdo_Project and object type hsdo_Model.
* 8 occurrences with subject type hsdo_Activity and object type hsdo_Model.
* 3 occurrences with subject type hsdo_Activity and object type hsdo_Activity.
* 4 occurrences with subject type hsdo_Activity and object type hsdo_Experiment.
* 3 occurrences with subject type hsdo_Activity and object type hsdo_Instrument.
* 6 occurrences with subject type hsdo_Activity and object type hsdo_Project.
* 3 occurrences with subject type hsdo_Model and object type hsdo_Science_Keyword.
* 5 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Science_Keyword.
* 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Location.
* 2 occurrences with subject type hsdo_Activity and object type hsdo_Location.
* 3 occurrences with subject type hsdo_Activity and object type hsdo_Models.
* 2 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type hsdo_Chronostratigraphic_Unit.
* 1 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Project.
* 2 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Model.
* 1 occurrences with subject type hsdo_Model and object type hsdo_Platform.
* 2 occurrences with subject type hsdo_Instrument and object type hsdo_Variable.
* 1 occurrences with subject type hsdo_Temporal_Resolution_Range and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Instrument and object type hsdo_Dataset.
* 1 occurrences with subject type hsdo_Model and object type hsdo_Chronostratigraphic_Unit.
* 1 occurrences with subject type hsdo_Model and object type hsdo_Variable.
* 1 occurrences with subject type hsdo_Model and object type hsdo_Provider.
* 10 occurrences with subject type hsdo_Project and object type hsdo_Models.
* 1 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Models.
* 1 occurrences with subject type hsdo_Related_Url_Content_Type and object type hsdo_Model.
* 1 occurrences with subject type hsdo_Temporal_Resolution_Range and object type hsdo_Science_Keyword.
* 3 occurrences with subject type hsdo_Location and object type hsdo_Project.
* 3 occurrences with subject type hsdo_Platform and object type hsdo_Science_Keyword.
* 2 occurrences with subject type hsdo_Platform and object type hsdo_Models.
* 2 occurrences with subject type hsdo_Instrument and object type hsdo_Institution.
* 1 occurrences with subject type hsdo_Institution and object type hsdo_Model.
* 1 occurrences with subject type hsdo_Location and object type hsdo_Science_Keyword.
* 1 occurrences with subject type hsdo_Variable and object type hsdo_Platform.
* 1 occurrences with subject type hsdo_Platform and object type hsdo_Location.
* 1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Model.
* 1 occurrences with subject type hsdo_Provider and object type hsdo_Project.
* 1 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Instrument.
* 2 occurrences with subject type hsdo_Project and object type hsdo_Science_Keyword.
* 1 occurrences with subject type hsdo_Dataset and object type hsdo_Location.
* 1 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Experiment and object type hsdo_Variable.
* 1 occurrences with subject type hsdo_Institution and object type hsdo_Project.
* 4 occurrences with subject type hsdo_Project and object type hsdo_Activity.
* 2 occurrences with subject type hsdo_Location and object type hsdo_Provider.
* 1 occurrences with subject type hsdo_Provider and object type hsdo_Activity.
* 1 occurrences with subject type hsdo_Project and object type hsdo_Provider.
* 1 occurrences with subject type hsdo_Provider and object type hsdo_Model.
* 1 occurrences with subject type hsdo_Experiment and object type hsdo_Data_Format.
* 6 occurrences with subject type hsdo_Project and object type hsdo_Cmip6_Source_Id.
* 1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Instrument.
* 2 occurrences with subject type hsdo_Models and object type hsdo_Chronostratigraphic_Unit.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:UsedIn |
| native | climatepub4-kg/:relation_UsedIn |




## LinkML Source

<details>
```yaml
name: relation_UsedIn
description: No slot (predicate) description specified
comments:
- 14 occurrences with subject type hsdo_Model and object type hsdo_Location.
- 17 occurrences with subject type hsdo_Model and object type hsdo_Model.
- 29 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.
- 2 occurrences with subject type hsdo_Experiment and object type hsdo_Science_Keyword.
- 46 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
- 20 occurrences with subject type hsdo_Experiment and object type hsdo_Project.
- 16 occurrences with subject type hsdo_Models and object type hsdo_Experiment.
- 11 occurrences with subject type hsdo_Models and object type hsdo_Activity.
- 27 occurrences with subject type hsdo_Models and object type hsdo_Project.
- 46 occurrences with subject type hsdo_Instrument and object type hsdo_Experiment.
- 37 occurrences with subject type hsdo_Instrument and object type hsdo_Model.
- 28 occurrences with subject type hsdo_Model and object type hsdo_Instrument.
- 16 occurrences with subject type hsdo_Model and object type hsdo_Experiment.
- 8 occurrences with subject type hsdo_Model and object type hsdo_Activity.
- 114 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.
- 44 occurrences with subject type hsdo_Instrument and object type hsdo_Location.
- 18 occurrences with subject type hsdo_Project and object type hsdo_Instrument.
- 16 occurrences with subject type hsdo_Models and object type hsdo_Model.
- 7 occurrences with subject type hsdo_Models and object type hsdo_Location.
- 7 occurrences with subject type hsdo_Models and object type hsdo_Instrument.
- 11 occurrences with subject type hsdo_Models and object type hsdo_Models.
- 5 occurrences with subject type hsdo_Instrument and object type hsdo_Science_Keyword.
- 1 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.
- 5 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Experiment.
- 10 occurrences with subject type hsdo_Model and object type hsdo_Project.
- 6 occurrences with subject type hsdo_Instrument and object type hsdo_Models.
- 2 occurrences with subject type hsdo_Provider and object type hsdo_Models.
- 8 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Location.
- 1 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Chronostratigraphic_Unit.
- 1 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Provider.
- 29 occurrences with subject type hsdo_Location and object type hsdo_Instrument.
- 15 occurrences with subject type hsdo_Experiment and object type hsdo_Model.
- 5 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Location.
- 7 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Model.
- 2 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Measurement_Name.
- 4 occurrences with subject type hsdo_Variable and object type hsdo_Models.
- 1 occurrences with subject type hsdo_Variable and object type hsdo_Experiment.
- 5 occurrences with subject type hsdo_Variable and object type hsdo_Model.
- 2 occurrences with subject type hsdo_Variable and object type hsdo_Instrument.
- 15 occurrences with subject type hsdo_Location and object type hsdo_Model.
- 1 occurrences with subject type hsdo_Location and object type hsdo_Measurement_Name.
- 4 occurrences with subject type hsdo_Model and object type hsdo_Models.
- 6 occurrences with subject type hsdo_Provider and object type hsdo_Location.
- 9 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Instrument.
- 1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Location.
- 17 occurrences with subject type hsdo_Location and object type hsdo_Location.
- 17 occurrences with subject type hsdo_Experiment and object type hsdo_Location.
- 7 occurrences with subject type hsdo_Experiment and object type hsdo_Models.
- 9 occurrences with subject type hsdo_Experiment and object type hsdo_Activity.
- 3 occurrences with subject type hsdo_Instrument and object type hsdo_Provider.
- 13 occurrences with subject type hsdo_Instrument and object type hsdo_Project.
- 3 occurrences with subject type hsdo_Project and object type hsdo_Institution.
- 2 occurrences with subject type hsdo_Location and object type hsdo_Variable.
- 25 occurrences with subject type hsdo_Location and object type hsdo_Experiment.
- 2 occurrences with subject type hsdo_Provider and object type hsdo_Experiment.
- 4 occurrences with subject type hsdo_Location and object type hsdo_Models.
- 4 occurrences with subject type hsdo_Platform and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Variable and object type hsdo_Location.
- 1 occurrences with subject type hsdo_Variable and object type hsdo_Institution.
- 1 occurrences with subject type hsdo_Variable and object type hsdo_Project.
- 4 occurrences with subject type hsdo_Instrument and object type hsdo_Data_Format.
- 3 occurrences with subject type hsdo_Models and object type hsdo_Science_Keyword.
- 4 occurrences with subject type hsdo_Platform and object type hsdo_Model.
- 6 occurrences with subject type hsdo_Platform and object type hsdo_Instrument.
- 4 occurrences with subject type hsdo_Platform and object type hsdo_Project.
- 8 occurrences with subject type hsdo_Project and object type hsdo_Location.
- 5 occurrences with subject type hsdo_Data_Format and object type hsdo_Instrument.
- 1 occurrences with subject type hsdo_Instrument and object type hsdo_Measurement_Name.
- 3 occurrences with subject type hsdo_Instrument and object type hsdo_Activity.
- 1 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Variable.
- 3 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.
- 14 occurrences with subject type hsdo_Project and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Location and object type hsdo_Platform.
- 3 occurrences with subject type hsdo_Provider and object type hsdo_Instrument.
- 2 occurrences with subject type hsdo_Provider and object type hsdo_Science_Keyword.
- 6 occurrences with subject type hsdo_Location and object type hsdo_Data_Format.
- 6 occurrences with subject type hsdo_Project and object type hsdo_Project.
- 8 occurrences with subject type hsdo_Project and object type hsdo_Model.
- 8 occurrences with subject type hsdo_Activity and object type hsdo_Model.
- 3 occurrences with subject type hsdo_Activity and object type hsdo_Activity.
- 4 occurrences with subject type hsdo_Activity and object type hsdo_Experiment.
- 3 occurrences with subject type hsdo_Activity and object type hsdo_Instrument.
- 6 occurrences with subject type hsdo_Activity and object type hsdo_Project.
- 3 occurrences with subject type hsdo_Model and object type hsdo_Science_Keyword.
- 5 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Science_Keyword.
- 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Location.
- 2 occurrences with subject type hsdo_Activity and object type hsdo_Location.
- 3 occurrences with subject type hsdo_Activity and object type hsdo_Models.
- 2 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type hsdo_Chronostratigraphic_Unit.
- 1 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Project.
- 2 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Model.
- 1 occurrences with subject type hsdo_Model and object type hsdo_Platform.
- 2 occurrences with subject type hsdo_Instrument and object type hsdo_Variable.
- 1 occurrences with subject type hsdo_Temporal_Resolution_Range and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Instrument and object type hsdo_Dataset.
- 1 occurrences with subject type hsdo_Model and object type hsdo_Chronostratigraphic_Unit.
- 1 occurrences with subject type hsdo_Model and object type hsdo_Variable.
- 1 occurrences with subject type hsdo_Model and object type hsdo_Provider.
- 10 occurrences with subject type hsdo_Project and object type hsdo_Models.
- 1 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Models.
- 1 occurrences with subject type hsdo_Related_Url_Content_Type and object type hsdo_Model.
- 1 occurrences with subject type hsdo_Temporal_Resolution_Range and object type hsdo_Science_Keyword.
- 3 occurrences with subject type hsdo_Location and object type hsdo_Project.
- 3 occurrences with subject type hsdo_Platform and object type hsdo_Science_Keyword.
- 2 occurrences with subject type hsdo_Platform and object type hsdo_Models.
- 2 occurrences with subject type hsdo_Instrument and object type hsdo_Institution.
- 1 occurrences with subject type hsdo_Institution and object type hsdo_Model.
- 1 occurrences with subject type hsdo_Location and object type hsdo_Science_Keyword.
- 1 occurrences with subject type hsdo_Variable and object type hsdo_Platform.
- 1 occurrences with subject type hsdo_Platform and object type hsdo_Location.
- 1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Model.
- 1 occurrences with subject type hsdo_Provider and object type hsdo_Project.
- 1 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Instrument.
- 2 occurrences with subject type hsdo_Project and object type hsdo_Science_Keyword.
- 1 occurrences with subject type hsdo_Dataset and object type hsdo_Location.
- 1 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Experiment and object type hsdo_Variable.
- 1 occurrences with subject type hsdo_Institution and object type hsdo_Project.
- 4 occurrences with subject type hsdo_Project and object type hsdo_Activity.
- 2 occurrences with subject type hsdo_Location and object type hsdo_Provider.
- 1 occurrences with subject type hsdo_Provider and object type hsdo_Activity.
- 1 occurrences with subject type hsdo_Project and object type hsdo_Provider.
- 1 occurrences with subject type hsdo_Provider and object type hsdo_Model.
- 1 occurrences with subject type hsdo_Experiment and object type hsdo_Data_Format.
- 6 occurrences with subject type hsdo_Project and object type hsdo_Cmip6_Source_Id.
- 1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Instrument.
- 2 occurrences with subject type hsdo_Models and object type hsdo_Chronostratigraphic_Unit.
examples:
- description: hsdo_Model → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/bfbfd84c-6bf0-412f-9e75-1bad5241c339
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f8845bec-c628-4185-aac1-4af22481c024
    example_subject_type: hsdo_Model
- description: hsdo_Model → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/8894d92c-be32-465b-ae08-e5de755a92fc
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f1e6caa5-2c97-407d-a0db-7bf01794d8e3
    example_subject_type: hsdo_Model
- description: hsdo_Experiment → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/ae02541a-4968-4573-8569-0f4a02575ab2
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/2e69c08b-ee0f-426c-a8d2-dc50876f76c2
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/79841056-b651-439c-b638-439e94731d31
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/6ffd7617-25fd-4464-bbd3-fc02e33ffafb
    example_object_type: hsdo_Project
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
    example_subject_type: hsdo_Experiment
- description: hsdo_Models → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/cbab6fb9-2240-4fb4-97c0-6ec918ddd729
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f88c4559-fc4b-4b4a-ac57-0f15bb24e8e0
    example_subject_type: hsdo_Models
- description: hsdo_Models → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58
    example_object_type: hsdo_Activity
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
    example_subject_type: hsdo_Models
- description: hsdo_Models → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_object_type: hsdo_Project
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
    example_subject_type: hsdo_Models
- description: hsdo_Instrument → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fe4392b0-13a9-43ff-bacc-f44a65aed4fa
    example_subject_type: hsdo_Instrument
- description: hsdo_Instrument → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/31ca2413-f257-4ceb-849a-68538efecfee
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fe4392b0-13a9-43ff-bacc-f44a65aed4fa
    example_subject_type: hsdo_Instrument
- description: hsdo_Model → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/b62575f6-25e9-4a50-b0f6-a45dbf22c8d4
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f1e6caa5-2c97-407d-a0db-7bf01794d8e3
    example_subject_type: hsdo_Model
- description: hsdo_Model → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58
    example_subject_type: hsdo_Model
- description: hsdo_Model → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/68885007-d975-4f24-bdd5-dd19b246bdf6
    example_object_type: hsdo_Activity
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f860ed88-991f-4b52-90b9-fc8d4046a598
    example_subject_type: hsdo_Model
- description: hsdo_Instrument → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/fcc9411c-a1c9-415d-a16c-75c42f2cec45
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fe37b7a7-b6ca-4880-8dcf-16973cd8ecc8
    example_subject_type: hsdo_Instrument
- description: hsdo_Instrument → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/8b7f66ea-d481-4641-9dbf-da90ca3ad9c9
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fb23c170-9164-40cf-aed0-5a3fbd531fad
    example_subject_type: hsdo_Instrument
- description: hsdo_Project → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/c811bdaf-649f-4e23-b495-940d64e675f4
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    example_subject_type: hsdo_Project
- description: hsdo_Models → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
    example_subject_type: hsdo_Models
- description: hsdo_Models → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/0f50133b-1ef8-4c67-97a3-ac0604a41fc8
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f88c4559-fc4b-4b4a-ac57-0f15bb24e8e0
    example_subject_type: hsdo_Models
- description: hsdo_Models → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/2d580f50-3951-4601-9b08-7fbea94eebef
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/c266a473-338f-4fe9-965c-f8ae853ff57b
    example_subject_type: hsdo_Models
- description: hsdo_Models → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
    example_object_type: hsdo_Models
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
    example_subject_type: hsdo_Models
- description: hsdo_Instrument → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/ea936862-2c98-41e5-8514-6b7288a5f941
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/78fb5691-136d-40f8-a834-6e6f4cd768ff
    example_subject_type: hsdo_Instrument
- description: hsdo_Instrument → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/a96e6cd6-0f35-491d-8198-7551d03e1cbc
    example_object_type: hsdo_Platform
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/085edf65-1c8c-414a-b8e4-a1a08ff08f22
    example_subject_type: hsdo_Instrument
- description: hsdo_Science_Keyword → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/00ce4800-70ef-4346-aa15-0554280d0896
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/ed925b43-db83-4cbb-8347-3dc0081bb8f4
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Model → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_object_type: hsdo_Project
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58
    example_subject_type: hsdo_Model
- description: hsdo_Instrument → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/063177a9-14cd-4750-9aa4-ad5d266bd7ad
    example_object_type: hsdo_Models
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/ae02541a-4968-4573-8569-0f4a02575ab2
    example_subject_type: hsdo_Instrument
- description: hsdo_Provider → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/24b382cb-5ed5-46f5-9134-1e34462f9f20
    example_object_type: hsdo_Models
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/c297fda0-848a-4a9b-85be-86f29c92f212
    example_subject_type: hsdo_Provider
- description: hsdo_Cmip6_Source_Id → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/89bb4e2b-dd39-44ed-a4d3-2b205e9fa68a
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f083ae80-224b-4453-8a18-d1b13d9d2f90
    example_subject_type: hsdo_Cmip6_Source_Id
- description: hsdo_Cmip6_Source_Id → hsdo_Chronostratigraphic_Unit
  object:
    example_object: https://climateKG.org/entity/db06b2a9-4ed5-4222-8533-fbf3ed3bdc23
    example_object_type: hsdo_Chronostratigraphic_Unit
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/0cd4d2c4-ebfa-4759-b7aa-f9982122f581
    example_subject_type: hsdo_Cmip6_Source_Id
- description: hsdo_Science_Keyword → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/4e366444-01ea-4517-9d93-56f55ddf41b7
    example_object_type: hsdo_Provider
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/0de668aa-cc97-482d-a0eb-cddcb1a705b6
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Location → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/33f20afe-5ce2-43e9-9676-c5f664fbc324
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fd03d204-4391-4e98-8142-8b8efa235231
    example_subject_type: hsdo_Location
- description: hsdo_Experiment → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/8e484ec4-50fd-4c08-9c96-6ad483e170ad
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
    example_subject_type: hsdo_Experiment
- description: hsdo_Science_Keyword → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/78369c58-beaa-46f2-b286-dd2540634556
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/cf3d1728-7606-4561-a0dd-116b4dbec21f
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Science_Keyword → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/8680cb49-1637-4a47-a5fd-f39d4e618e45
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/bd24a9a9-7d52-4c29-b2a0-6cefd216ae78
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Science_Keyword → hsdo_Measurement_Name
  object:
    example_object: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9
    example_object_type: hsdo_Measurement_Name
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/d2e93932-0231-4b23-af2f-217c6315a95e
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Variable → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
    example_object_type: hsdo_Models
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    example_subject_type: hsdo_Variable
- description: hsdo_Variable → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/79841056-b651-439c-b638-439e94731d31
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
    example_subject_type: hsdo_Variable
- description: hsdo_Variable → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    example_subject_type: hsdo_Variable
- description: hsdo_Variable → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/ae02541a-4968-4573-8569-0f4a02575ab2
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    example_subject_type: hsdo_Variable
- description: hsdo_Location → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/0399b52c-e3de-4dcc-9eb6-b1e3acf2cf1b
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fa57b0a0-9723-4195-bdd1-4f26aefa0e07
    example_subject_type: hsdo_Location
- description: hsdo_Location → hsdo_Measurement_Name
  object:
    example_object: https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
    example_object_type: hsdo_Measurement_Name
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/162e2243-3266-4999-b352-d8a1a9dc82ac
    example_subject_type: hsdo_Location
- description: hsdo_Model → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/c5b13fa4-0069-40ce-85cb-bfbab34c2058
    example_object_type: hsdo_Models
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/defd2c00-64e3-4986-9061-feade19f972f
    example_subject_type: hsdo_Model
- description: hsdo_Provider → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/c46d59a8-d874-4db8-87f5-d59ecbb79a29
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f6e72cf4-b814-4c7d-a013-9e499bcdc773
    example_subject_type: hsdo_Provider
- description: hsdo_Science_Keyword → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/0b4081fa-5233-4484-bc82-706976defa0e
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/ef36cb15-ad64-4bdc-9331-42cc5b493671
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Measurement_Name → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/dcef091b-18b5-48bf-b191-69ab7a3511f1
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/1f697c83-969d-48ee-87b8-245b11f7e24f
    example_subject_type: hsdo_Measurement_Name
- description: hsdo_Location → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/fa57b0a0-9723-4195-bdd1-4f26aefa0e07
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/eb784368-9b92-49b0-afc5-ea820e996f33
    example_subject_type: hsdo_Location
- description: hsdo_Experiment → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/fa57b0a0-9723-4195-bdd1-4f26aefa0e07
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/c8a4a768-cdad-42ab-b2b5-3100440ffd8f
    example_object_type: hsdo_Models
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/7f1f0059-de73-4a9e-9200-1bbcd2d6e789
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/8f528b66-670d-4198-b014-7fdc9e1f6890
    example_object_type: hsdo_Activity
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/cbab6fb9-2240-4fb4-97c0-6ec918ddd729
    example_subject_type: hsdo_Experiment
- description: hsdo_Instrument → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
    example_object_type: hsdo_Provider
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/543135bc-7749-49ca-89af-b108cac1afaa
    example_subject_type: hsdo_Instrument
- description: hsdo_Instrument → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/08684c69-224d-4c4a-a1a7-ea3933ac9081
    example_object_type: hsdo_Project
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/cb8f849f-bbe5-4c62-9a50-d729718ad980
    example_subject_type: hsdo_Instrument
- description: hsdo_Project → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/e8df7edd-a176-45c9-8515-3a520948ef63
    example_object_type: hsdo_Institution
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Location → hsdo_Variable
  object:
    example_object: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    example_object_type: hsdo_Variable
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/3d4e44c4-5d99-4a9b-8388-43c63533ee97
    example_subject_type: hsdo_Location
- description: hsdo_Location → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/ecc4a2bb-f195-4296-b300-c1227221b688
    example_subject_type: hsdo_Location
- description: hsdo_Provider → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/aef9855c-70e1-4e22-aa25-8ccd23176d3b
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/2b890e5b-1b50-4454-90a9-538dd891da9a
    example_subject_type: hsdo_Provider
- description: hsdo_Location → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/3668de06-8a7d-4667-beb8-d04dcac619b0
    example_object_type: hsdo_Models
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/df160e31-ae45-41a4-9093-a80fe5303cea
    example_subject_type: hsdo_Location
- description: hsdo_Platform → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fdb04105-e8ba-4a83-9c35-ed3c931ccc9f
    example_subject_type: hsdo_Platform
- description: hsdo_Variable → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/2b424588-9bb6-418a-b1c7-06b93be4ba28
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    example_subject_type: hsdo_Variable
- description: hsdo_Variable → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/e2f64d50-da88-4d6a-abfa-4b0b7e99312e
    example_object_type: hsdo_Institution
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    example_subject_type: hsdo_Variable
- description: hsdo_Variable → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_object_type: hsdo_Project
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    example_subject_type: hsdo_Variable
- description: hsdo_Instrument → hsdo_Data_Format
  object:
    example_object: https://climateKG.org/entity/191a9f1d-cfd3-469d-86b8-ce2d2355034a
    example_object_type: hsdo_Data_Format
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fb23c170-9164-40cf-aed0-5a3fbd531fad
    example_subject_type: hsdo_Instrument
- description: hsdo_Models → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/ef36cb15-ad64-4bdc-9331-42cc5b493671
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fc94343c-1809-431f-b3da-8ba5b887dda9
    example_subject_type: hsdo_Models
- description: hsdo_Platform → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/2bfd42f1-0453-4c33-a21e-74df3ad64813
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f24c4f33-5b89-4e8d-8de7-296078a7f18a
    example_subject_type: hsdo_Platform
- description: hsdo_Platform → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/267b7dc6-ffae-4d76-a145-bca4e80313b3
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f959e3c5-f014-40b7-a134-4d41b616f79d
    example_subject_type: hsdo_Platform
- description: hsdo_Platform → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/4d569982-00c1-4e7f-b357-0bf0b624998d
    example_object_type: hsdo_Project
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/9830be3b-80ea-4e8c-af46-526882b7f26d
    example_subject_type: hsdo_Platform
- description: hsdo_Project → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/a4202721-0cba-4fa1-853f-890f146b04f9
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Data_Format → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/d0b3505e-77bb-45a0-83fe-787bc3812b67
    example_subject_type: hsdo_Data_Format
- description: hsdo_Instrument → hsdo_Measurement_Name
  object:
    example_object: https://climateKG.org/entity/1f697c83-969d-48ee-87b8-245b11f7e24f
    example_object_type: hsdo_Measurement_Name
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/3ce7f4f0-d2db-4352-8762-d88296f7aa15
    example_subject_type: hsdo_Instrument
- description: hsdo_Instrument → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58
    example_object_type: hsdo_Activity
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/ba008542-5c6f-462a-8ddf-21e54cbf3034
    example_subject_type: hsdo_Instrument
- description: hsdo_Science_Keyword → hsdo_Variable
  object:
    example_object: https://climateKG.org/entity/7471c00f-60c7-4ac3-a6db-d49020f22014
    example_object_type: hsdo_Variable
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/3de6fa74-bb80-4bc6-ae60-1e6fe8ae6c67
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Experiment → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/4e366444-01ea-4517-9d93-56f55ddf41b7
    example_object_type: hsdo_Provider
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/aef9855c-70e1-4e22-aa25-8ccd23176d3b
    example_subject_type: hsdo_Experiment
- description: hsdo_Project → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/b7eb8278-0dc3-4121-87ea-14173279dfb4
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    example_subject_type: hsdo_Project
- description: hsdo_Location → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/82fdb39c-4fe8-4e2b-9dcf-67ceb4c6d8b9
    example_object_type: hsdo_Platform
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/46e4aaa4-349c-4049-a910-035391360010
    example_subject_type: hsdo_Location
- description: hsdo_Provider → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/418a8c09-a533-4f9a-ac4b-7078107980bf
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/a463163e-8e86-4086-8b10-8fd6a95fca4a
    example_subject_type: hsdo_Provider
- description: hsdo_Provider → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/dfc20833-d79a-4976-91fd-db9f3efc7822
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/5a5c7e50-e5a0-45f2-be81-0cb96b32cb1e
    example_subject_type: hsdo_Provider
- description: hsdo_Location → hsdo_Data_Format
  object:
    example_object: https://climateKG.org/entity/d896a8cc-4fce-4a8d-86bc-185b324fab2b
    example_object_type: hsdo_Data_Format
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f3b5489d-6723-40bf-bd55-68a0f2fc1874
    example_subject_type: hsdo_Location
- description: hsdo_Project → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/01e75216-1cee-4cc3-b31d-83019730da85
    example_object_type: hsdo_Project
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    example_subject_type: hsdo_Project
- description: hsdo_Project → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/c85170ef-cf60-470e-b9d0-f22c138911fd
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Activity → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/13df63e8-85ad-405d-9b43-256371e259c0
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7
    example_subject_type: hsdo_Activity
- description: hsdo_Activity → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/5796ebd9-7dcb-4968-b876-1e678484cc62
    example_object_type: hsdo_Activity
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/8f528b66-670d-4198-b014-7fdc9e1f6890
    example_subject_type: hsdo_Activity
- description: hsdo_Activity → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/99ea6719-b751-4a4f-95d4-aaa02e961bc1
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58
    example_subject_type: hsdo_Activity
- description: hsdo_Activity → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/fe2719de-c5c8-4ce6-8230-1d16c8155991
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7
    example_subject_type: hsdo_Activity
- description: hsdo_Activity → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_object_type: hsdo_Project
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7
    example_subject_type: hsdo_Activity
- description: hsdo_Model → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/e660d917-0c77-463c-a15b-e8061ed296f8
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/652349bd-f6f9-4c8d-8573-d71e05ad1208
    example_subject_type: hsdo_Model
- description: hsdo_Science_Keyword → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/a90306f0-353c-4083-941a-0973a6fd6584
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/d3055f47-258e-4556-a885-54cd1fff4680
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Data_Format → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/1ac29014-a695-49a1-93d8-bf32d2684e44
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/6231402a-7e4c-42d9-802d-7184eb812f46
    example_subject_type: hsdo_Data_Format
- description: hsdo_Activity → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/d34c3aa5-81b8-4b56-b298-5f33307815b0
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7
    example_subject_type: hsdo_Activity
- description: hsdo_Activity → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/5467feeb-5956-46b5-8d45-fc695339ff48
    example_object_type: hsdo_Models
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7
    example_subject_type: hsdo_Activity
- description: hsdo_Chronostratigraphic_Unit → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/c7245882-84a1-4192-acfa-a758b5b9c151
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
    example_subject_type: hsdo_Chronostratigraphic_Unit
- description: hsdo_Chronostratigraphic_Unit → hsdo_Chronostratigraphic_Unit
  object:
    example_object: https://climateKG.org/entity/c7e7fb38-44ef-4c5b-aa1d-b3fdcf89d838
    example_object_type: hsdo_Chronostratigraphic_Unit
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/6cb96c3b-1a1c-4d26-a894-2638d5cd05d1
    example_subject_type: hsdo_Chronostratigraphic_Unit
- description: hsdo_Cmip6_Source_Id → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_object_type: hsdo_Project
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/6f7a0a68-6387-4f49-84ea-9652139018f5
    example_subject_type: hsdo_Cmip6_Source_Id
- description: hsdo_Cmip6_Source_Id → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/ba7cc1c1-c5ef-43ff-9a2e-84629f0a94fa
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/df0ba39b-7461-4cee-8660-c80fee72e96b
    example_subject_type: hsdo_Cmip6_Source_Id
- description: hsdo_Model → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/67290503-94b9-4517-b5b6-063bba2bee27
    example_object_type: hsdo_Platform
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/785f7c57-93c9-4fe0-8309-ff32aa59a637
    example_subject_type: hsdo_Model
- description: hsdo_Instrument → hsdo_Variable
  object:
    example_object: https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
    example_object_type: hsdo_Variable
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/a68048f4-181c-4c6c-9bfa-9e4171e9f237
    example_subject_type: hsdo_Instrument
- description: hsdo_Temporal_Resolution_Range → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/7c5420a6-94e2-40ca-9dff-20309090d327
    example_subject_type: hsdo_Temporal_Resolution_Range
- description: hsdo_Instrument → hsdo_Dataset
  object:
    example_object: https://climateKG.org/entity/2892e23f-5249-439d-8c0e-6c1d190b3beb
    example_object_type: hsdo_Dataset
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/804d4f03-ee93-4fc9-ada0-f3dc9a7a6706
    example_subject_type: hsdo_Instrument
- description: hsdo_Model → hsdo_Chronostratigraphic_Unit
  object:
    example_object: https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
    example_object_type: hsdo_Chronostratigraphic_Unit
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/8491e067-951e-4cba-9619-d376b5c628a0
    example_subject_type: hsdo_Model
- description: hsdo_Model → hsdo_Variable
  object:
    example_object: https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
    example_object_type: hsdo_Variable
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/8680cb49-1637-4a47-a5fd-f39d4e618e45
    example_subject_type: hsdo_Model
- description: hsdo_Model → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/e85b6d64-a230-4c1d-99a5-c62be8af18c7
    example_object_type: hsdo_Provider
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/8680cb49-1637-4a47-a5fd-f39d4e618e45
    example_subject_type: hsdo_Model
- description: hsdo_Project → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/fc94343c-1809-431f-b3da-8ba5b887dda9
    example_object_type: hsdo_Models
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Science_Keyword → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/ca240508-9cd7-400e-9420-ad96f72195bd
    example_object_type: hsdo_Models
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/90c21a67-6703-4b59-96ee-c2c602652c80
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Related_Url_Content_Type → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/5612b95e-cc41-4286-9946-e78506f70f59
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/914cbb7e-5b20-4bcd-86e3-ffcfa26f0a73
    example_subject_type: hsdo_Related_Url_Content_Type
- description: hsdo_Temporal_Resolution_Range → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/fbc53539-ce4e-4e3e-bbd2-8270386616b4
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/99ef187e-6940-4c10-8d65-00d4426d493b
    example_subject_type: hsdo_Temporal_Resolution_Range
- description: hsdo_Location → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_object_type: hsdo_Project
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/e1078fd4-fa6b-4c35-81ee-648bc086e9c5
    example_subject_type: hsdo_Location
- description: hsdo_Platform → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/d6464d91-2373-456f-85a7-a5019bdb1076
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/a96e6cd6-0f35-491d-8198-7551d03e1cbc
    example_subject_type: hsdo_Platform
- description: hsdo_Platform → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/eb539ad7-79ee-4d76-8e38-b298b2385626
    example_object_type: hsdo_Models
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e
    example_subject_type: hsdo_Platform
- description: hsdo_Instrument → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/4315c66b-86e9-4127-a456-e549687012cf
    example_object_type: hsdo_Institution
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/cb8f849f-bbe5-4c62-9a50-d729718ad980
    example_subject_type: hsdo_Instrument
- description: hsdo_Institution → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/b62469fa-105e-4e2c-b621-5915a86c93e1
    example_subject_type: hsdo_Institution
- description: hsdo_Location → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/e5a658d5-74db-4022-894f-edc8d297767a
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/b6782a30-639e-4d70-8290-81683d248b1f
    example_subject_type: hsdo_Location
- description: hsdo_Variable → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e
    example_object_type: hsdo_Platform
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/ba70b595-5263-4ffd-97a2-f86ba91681ae
    example_subject_type: hsdo_Variable
- description: hsdo_Platform → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/5668f6df-ab5a-4991-9720-dda2faae7f3e
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/bac2e743-1d02-4868-8bd6-b8b8741e3794
    example_subject_type: hsdo_Platform
- description: hsdo_Measurement_Name → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/8ad656db-1324-4e92-8273-5a765ca29282
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
    example_subject_type: hsdo_Measurement_Name
- description: hsdo_Provider → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/e23b4757-38f3-4be1-8d70-035dacb782f6
    example_object_type: hsdo_Project
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23
    example_subject_type: hsdo_Provider
- description: hsdo_Cmip6_Source_Id → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/b62575f6-25e9-4a50-b0f6-a45dbf22c8d4
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/d0c16581-6951-4e8d-a0c1-97e9fcaa031a
    example_subject_type: hsdo_Cmip6_Source_Id
- description: hsdo_Project → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/0de668aa-cc97-482d-a0eb-cddcb1a705b6
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    example_subject_type: hsdo_Project
- description: hsdo_Dataset → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/2ca1b865-5555-4375-aa81-72811335b695
    example_object_type: hsdo_Location
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
    example_subject_type: hsdo_Dataset
- description: hsdo_Cmip6_Source_Id → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/e3f2ed37-dfb2-4d74-9aa7-efe0d67fdd54
    example_object_type: hsdo_Experiment
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/d4548c1b-c0b1-47a9-a2ea-6000baa98647
    example_subject_type: hsdo_Cmip6_Source_Id
- description: hsdo_Experiment → hsdo_Variable
  object:
    example_object: https://climateKG.org/entity/1f1436a3-ac80-48e1-abbe-095fc74c9655
    example_object_type: hsdo_Variable
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
    example_subject_type: hsdo_Experiment
- description: hsdo_Institution → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/b971f45d-3a45-4ef2-99df-d6b88bbc7cc3
    example_object_type: hsdo_Project
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/d9fbd2ea-803e-48b7-a1f2-774e6845cc1f
    example_subject_type: hsdo_Institution
- description: hsdo_Project → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7
    example_object_type: hsdo_Activity
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Location → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/4e366444-01ea-4517-9d93-56f55ddf41b7
    example_object_type: hsdo_Provider
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/ecc4a2bb-f195-4296-b300-c1227221b688
    example_subject_type: hsdo_Location
- description: hsdo_Provider → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58
    example_object_type: hsdo_Activity
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/e236abe1-c8c5-4bca-ab7d-89b5a0392d6b
    example_subject_type: hsdo_Provider
- description: hsdo_Project → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23
    example_object_type: hsdo_Provider
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/e23b4757-38f3-4be1-8d70-035dacb782f6
    example_subject_type: hsdo_Project
- description: hsdo_Provider → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/b8a877b7-d867-4305-9053-3777e5dd330a
    example_object_type: hsdo_Model
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/e8df433e-f868-4ad1-97e7-8610d60a86e3
    example_subject_type: hsdo_Provider
- description: hsdo_Experiment → hsdo_Data_Format
  object:
    example_object: https://climateKG.org/entity/d0b3505e-77bb-45a0-83fe-787bc3812b67
    example_object_type: hsdo_Data_Format
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
    example_subject_type: hsdo_Experiment
- description: hsdo_Project → hsdo_Cmip6_Source_Id
  object:
    example_object: https://climateKG.org/entity/f083ae80-224b-4453-8a18-d1b13d9d2f90
    example_object_type: hsdo_Cmip6_Source_Id
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Measurement_Name → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/33f20afe-5ce2-43e9-9676-c5f664fbc324
    example_object_type: hsdo_Instrument
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9
    example_subject_type: hsdo_Measurement_Name
- description: hsdo_Models → hsdo_Chronostratigraphic_Unit
  object:
    example_object: https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
    example_object_type: hsdo_Chronostratigraphic_Unit
    example_predicate: relation:UsedIn
    example_subject: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
    example_subject_type: hsdo_Models
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:UsedIn
alias: relation_UsedIn
domain_of:
- hsdo_Activity
- hsdo_Chronostratigraphic_Unit
- hsdo_Cmip6_Source_Id
- hsdo_Data_Format
- hsdo_Dataset
- hsdo_Experiment
- hsdo_Institution
- hsdo_Instrument
- hsdo_Location
- hsdo_Measurement_Name
- hsdo_Model
- hsdo_Models
- hsdo_Platform
- hsdo_Project
- hsdo_Provider
- hsdo_Related_Url_Content_Type
- hsdo_Science_Keyword
- hsdo_Temporal_Resolution_Range
- hsdo_Variable
range: Any
any_of:
- range: hsdo_Platform
- range: hsdo_Measurement_Name
- range: hsdo_Variable
- range: hsdo_Provider
- range: hsdo_Chronostratigraphic_Unit
- range: hsdo_Location
- range: hsdo_Project
- range: hsdo_Model
- range: hsdo_Institution
- range: hsdo_Activity
- range: hsdo_Dataset
- range: hsdo_Data_Format
- range: hsdo_Instrument
- range: hsdo_Models
- range: hsdo_Science_Keyword
- range: hsdo_Cmip6_Source_Id
- range: hsdo_Experiment

```
</details>