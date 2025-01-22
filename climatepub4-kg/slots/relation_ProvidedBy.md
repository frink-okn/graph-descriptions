

# Slot: relation_ProvidedBy


_No slot (predicate) description specified_





URI: [relation:ProvidedBy](http://relation.org/ProvidedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPlatform](../classes/HsdoPlatform.md) | No class (type) description specified |  no  |
| [HsdoLocation](../classes/HsdoLocation.md) | No class (type) description specified |  no  |
| [HsdoModel](../classes/HsdoModel.md) | No class (type) description specified |  no  |
| [HsdoDataset](../classes/HsdoDataset.md) | A body of structured information describing some topic(s) of interest |  no  |
| [HsdoExperiment](../classes/HsdoExperiment.md) | No class (type) description specified |  no  |
| [HsdoProject](../classes/HsdoProject.md) | An enterprise (potentially individual but typically collaborative), planned t... |  no  |
| [HsdoVariable](../classes/HsdoVariable.md) | No class (type) description specified |  no  |
| [HsdoModels](../classes/HsdoModels.md) | No class (type) description specified |  no  |
| [HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md) | No class (type) description specified |  no  |
| [HsdoProvider](../classes/HsdoProvider.md) | No class (type) description specified |  no  |
| [HsdoScienceKeyword](../classes/HsdoScienceKeyword.md) | No class (type) description specified |  no  |
| [HsdoActivity](../classes/HsdoActivity.md) | No class (type) description specified |  no  |
| [HsdoDataFormat](../classes/HsdoDataFormat.md) | No class (type) description specified |  no  |
| [HsdoInstrument](../classes/HsdoInstrument.md) | No class (type) description specified |  no  |
| [HsdoInstitution](../classes/HsdoInstitution.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoScienceKeyword](../classes/HsdoScienceKeyword.md)&nbsp;or&nbsp;<br />[HsdoMeasurementName](../classes/HsdoMeasurementName.md)&nbsp;or&nbsp;<br />[HsdoVariable](../classes/HsdoVariable.md)&nbsp;or&nbsp;<br />[HsdoModels](../classes/HsdoModels.md)&nbsp;or&nbsp;<br />[HsdoSubExperimentId](../classes/HsdoSubExperimentId.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoChronostratigraphicUnit](../classes/HsdoChronostratigraphicUnit.md)&nbsp;or&nbsp;<br />[HsdoProject](../classes/HsdoProject.md)&nbsp;or&nbsp;<br />[HsdoModel](../classes/HsdoModel.md)&nbsp;or&nbsp;<br />[HsdoInstitution](../classes/HsdoInstitution.md)&nbsp;or&nbsp;<br />[HsdoActivity](../classes/HsdoActivity.md)&nbsp;or&nbsp;<br />[HsdoDataset](../classes/HsdoDataset.md)&nbsp;or&nbsp;<br />[HsdoDataFormat](../classes/HsdoDataFormat.md)&nbsp;or&nbsp;<br />[HsdoInstrument](../classes/HsdoInstrument.md)&nbsp;or&nbsp;<br />[HsdoPlatform](../classes/HsdoPlatform.md)&nbsp;or&nbsp;<br />[HsdoLocation](../classes/HsdoLocation.md)&nbsp;or&nbsp;<br />[HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Model → hsdo_Instrument | https://climateKG.org/entity/f860ed88-991f-4b52-90b9-fc8d4046a598 | relation:ProvidedBy | https://climateKG.org/entity/7b36ad79-8cf3-46a9-b26c-52f3a0f1eac9 |
| hsdo_Experiment → hsdo_Location | https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049 | relation:ProvidedBy | https://climateKG.org/entity/28761db9-82fe-4a24-9a89-0fd6047fa1ea |
| hsdo_Experiment → hsdo_Project | https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d | relation:ProvidedBy | https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799 |
| hsdo_Provider → hsdo_Activity | https://climateKG.org/entity/0258d108-269d-409f-b2de-422483fe808e | relation:ProvidedBy | https://climateKG.org/entity/68885007-d975-4f24-bdd5-dd19b246bdf6 |
| hsdo_Models → hsdo_Activity | https://climateKG.org/entity/80122908-8018-4511-810c-dd7aaf639b91 | relation:ProvidedBy | https://climateKG.org/entity/8f528b66-670d-4198-b014-7fdc9e1f6890 |
| hsdo_Models → hsdo_Project | https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9 | relation:ProvidedBy | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 |
| hsdo_Instrument → hsdo_Measurement_Name | https://climateKG.org/entity/0364f832-b1a8-4056-b811-51d3d1fc32ed | relation:ProvidedBy | https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e |
| hsdo_Instrument → hsdo_Location | https://climateKG.org/entity/ee3e296f-fdc0-4695-95af-dbe63f43b679 | relation:ProvidedBy | https://climateKG.org/entity/523afb73-9b4c-4478-97e2-a7d5e228e31c |
| hsdo_Instrument → hsdo_Instrument | https://climateKG.org/entity/ecbe9f17-6012-4e39-a707-713973b7d167 | relation:ProvidedBy | https://climateKG.org/entity/ecbe9f17-6012-4e39-a707-713973b7d167 |
| hsdo_Science_Keyword → hsdo_Model | https://climateKG.org/entity/bc05d7d2-3c96-4bb6-b759-d45e3c673b86 | relation:ProvidedBy | https://climateKG.org/entity/c1564b40-d4ae-4e5b-b925-411b93cb68c5 |
| hsdo_Instrument → hsdo_Experiment | https://climateKG.org/entity/d9750f06-3784-4058-941f-40289c8d9d8b | relation:ProvidedBy | https://climateKG.org/entity/c7245882-84a1-4192-acfa-a758b5b9c151 |
| hsdo_Science_Keyword → hsdo_Project | https://climateKG.org/entity/bd24a9a9-7d52-4c29-b2a0-6cefd216ae78 | relation:ProvidedBy | https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799 |
| hsdo_Model → hsdo_Project | https://climateKG.org/entity/e66edf58-9a3d-4250-b2ba-9120b943403f | relation:ProvidedBy | https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92 |
| hsdo_Model → hsdo_Location | https://climateKG.org/entity/f1e6caa5-2c97-407d-a0db-7bf01794d8e3 | relation:ProvidedBy | https://climateKG.org/entity/ecc4a2bb-f195-4296-b300-c1227221b688 |
| hsdo_Platform → hsdo_Provider | https://climateKG.org/entity/da2c70fd-d92b-45be-b159-b2c10cb387c6 | relation:ProvidedBy | https://climateKG.org/entity/68447296-6019-453b-9684-3cd3ff1530c9 |
| hsdo_Project → hsdo_Instrument | https://climateKG.org/entity/ffcca1c5-fffd-4359-b282-e00fc77c979e | relation:ProvidedBy | https://climateKG.org/entity/1c645150-c046-4652-8f68-11167a19ba91 |
| hsdo_Provider → hsdo_Provider | https://climateKG.org/entity/df0ab7d8-025d-496d-8d5e-991d208c81fa | relation:ProvidedBy | https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23 |
| hsdo_Provider → hsdo_Institution | https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23 | relation:ProvidedBy | https://climateKG.org/entity/d9fbd2ea-803e-48b7-a1f2-774e6845cc1f |
| hsdo_Provider → hsdo_Project | https://climateKG.org/entity/c19dfe38-1e9d-4cdb-a900-07640628425d | relation:ProvidedBy | https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799 |
| hsdo_Project → hsdo_Platform | https://climateKG.org/entity/8289e024-54f7-4c63-a8ca-e7b1aef80be2 | relation:ProvidedBy | https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5 |
| hsdo_Platform → hsdo_Instrument | https://climateKG.org/entity/da2c70fd-d92b-45be-b159-b2c10cb387c6 | relation:ProvidedBy | https://climateKG.org/entity/eeba88d2-20bf-43b1-bccf-b125485405f4 |
| hsdo_Variable → hsdo_Model | https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa | relation:ProvidedBy | https://climateKG.org/entity/8680cb49-1637-4a47-a5fd-f39d4e618e45 |
| hsdo_Instrument → hsdo_Institution | https://climateKG.org/entity/ba2cf9cf-36c9-421b-bd6e-339e7cef1092 | relation:ProvidedBy | https://climateKG.org/entity/3be6270c-8554-467a-b2c7-9c13bc086b10 |
| hsdo_Project → hsdo_Model | https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab | relation:ProvidedBy | https://climateKG.org/entity/04d24dfe-c9f7-43b6-8bd8-8f2613767257 |
| hsdo_Models → hsdo_Institution | https://climateKG.org/entity/c266a473-338f-4fe9-965c-f8ae853ff57b | relation:ProvidedBy | https://climateKG.org/entity/d9fbd2ea-803e-48b7-a1f2-774e6845cc1f |
| hsdo_Experiment → hsdo_Instrument | https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d | relation:ProvidedBy | https://climateKG.org/entity/ae02541a-4968-4573-8569-0f4a02575ab2 |
| hsdo_Experiment → hsdo_Experiment | https://climateKG.org/entity/cbab6fb9-2240-4fb4-97c0-6ec918ddd729 | relation:ProvidedBy | https://climateKG.org/entity/25f8d5c2-1a32-4453-9421-65c5d9d3d114 |
| hsdo_Location → hsdo_Model | https://climateKG.org/entity/df5ff39e-b49f-4517-afc0-1842a1a6fdc7 | relation:ProvidedBy | https://climateKG.org/entity/04d24dfe-c9f7-43b6-8bd8-8f2613767257 |
| hsdo_Instrument → hsdo_Model | https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb | relation:ProvidedBy | https://climateKG.org/entity/d287b7f5-7565-4602-a023-005578328c22 |
| hsdo_Project → hsdo_Location | https://climateKG.org/entity/ffdb1819-43ba-4307-80db-dae705f62a8d | relation:ProvidedBy | https://climateKG.org/entity/9f36c803-a972-4191-a345-faad9f6cf813 |
| hsdo_Provider → hsdo_Location | https://climateKG.org/entity/ff850d62-675c-4386-a375-fe4af92ec3ff | relation:ProvidedBy | https://climateKG.org/entity/9ac7a1c5-4179-47bc-8589-ebaa90d6cbd1 |
| hsdo_Instrument → hsdo_Platform | https://climateKG.org/entity/f9fd6f89-9a67-4ece-9514-3803e7787520 | relation:ProvidedBy | https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5 |
| hsdo_Location → hsdo_Instrument | https://climateKG.org/entity/fa57b0a0-9723-4195-bdd1-4f26aefa0e07 | relation:ProvidedBy | https://climateKG.org/entity/bc320625-d9ba-41f5-9336-57e86fd878f3 |
| hsdo_Model → hsdo_Model | https://climateKG.org/entity/de863e7e-caf7-4beb-ab2e-b9f37d96d534 | relation:ProvidedBy | https://climateKG.org/entity/04d24dfe-c9f7-43b6-8bd8-8f2613767257 |
| hsdo_Data_Format → hsdo_Science_Keyword | https://climateKG.org/entity/d0b3505e-77bb-45a0-83fe-787bc3812b67 | relation:ProvidedBy | https://climateKG.org/entity/3de6fa74-bb80-4bc6-ae60-1e6fe8ae6c67 |
| hsdo_Science_Keyword → hsdo_Experiment | https://climateKG.org/entity/ecd03762-df34-49b7-91f2-d8a51acd270e | relation:ProvidedBy | https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf |
| hsdo_Project → hsdo_Chronostratigraphic_Unit | https://climateKG.org/entity/25193d98-16dc-47df-a2b1-51bbbdcdbc2e | relation:ProvidedBy | https://climateKG.org/entity/5ba80ec4-1060-4228-ab97-d7c24980c97e |
| hsdo_Model → hsdo_Institution | https://climateKG.org/entity/d6141f58-40bf-4a59-9fc2-707528e53486 | relation:ProvidedBy | https://climateKG.org/entity/3be6270c-8554-467a-b2c7-9c13bc086b10 |
| hsdo_Project → hsdo_Project | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:ProvidedBy | https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799 |
| hsdo_Provider → hsdo_Instrument | https://climateKG.org/entity/f0f5d722-bff7-4811-b834-e012afe7341e | relation:ProvidedBy | https://climateKG.org/entity/4a426aab-4a95-4bf4-8449-19a72a251541 |
| hsdo_Science_Keyword → hsdo_Instrument | https://climateKG.org/entity/c77819e9-f62f-48dc-b924-e7a73b4dcda9 | relation:ProvidedBy | https://climateKG.org/entity/f6350232-b1c7-458c-bc43-bda357ebb6db |
| hsdo_Instrument → hsdo_Provider | https://climateKG.org/entity/fc4f2acd-ace7-452b-a540-4162f9e9ddb0 | relation:ProvidedBy | https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23 |
| hsdo_Dataset → hsdo_Institution | https://climateKG.org/entity/aeec8336-4b23-4f14-a985-9ca0150f1afd | relation:ProvidedBy | https://climateKG.org/entity/3be6270c-8554-467a-b2c7-9c13bc086b10 |
| hsdo_Dataset → hsdo_Location | https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54 | relation:ProvidedBy | https://climateKG.org/entity/2a9bce94-c391-4834-96bb-a9685d3590b1 |
| hsdo_Dataset → hsdo_Science_Keyword | https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54 | relation:ProvidedBy | https://climateKG.org/entity/40386eea-beb0-4b83-906b-75c6bfa24b73 |
| hsdo_Dataset → hsdo_Instrument | https://climateKG.org/entity/f9ce1564-0144-43d2-a9dd-bc48edcefb37 | relation:ProvidedBy | https://climateKG.org/entity/da9cf145-0986-42b4-9ae4-c8b65932ee77 |
| hsdo_Dataset → hsdo_Provider | https://climateKG.org/entity/2892e23f-5249-439d-8c0e-6c1d190b3beb | relation:ProvidedBy | https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5 |
| hsdo_Project → hsdo_Dataset | https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab | relation:ProvidedBy | https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54 |
| hsdo_Project → hsdo_Science_Keyword | https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799 | relation:ProvidedBy | https://climateKG.org/entity/b29b46ad-f05f-4144-b965-5f606ce96963 |
| hsdo_Location → hsdo_Provider | https://climateKG.org/entity/e325f579-2d4c-4c72-81f4-30cb8723261a | relation:ProvidedBy | https://climateKG.org/entity/68057636-bb40-472f-86cd-9b5c01f3c3d0 |
| hsdo_Location → hsdo_Activity | https://climateKG.org/entity/2a726c91-2cd0-4b08-a301-30396de71b91 | relation:ProvidedBy | https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7 |
| hsdo_Science_Keyword → hsdo_Location | https://climateKG.org/entity/2ab4134d-1ac7-4421-a7a6-659a542aff4c | relation:ProvidedBy | https://climateKG.org/entity/162e2243-3266-4999-b352-d8a1a9dc82ac |
| hsdo_Science_Keyword → hsdo_Provider | https://climateKG.org/entity/2ab4134d-1ac7-4421-a7a6-659a542aff4c | relation:ProvidedBy | https://climateKG.org/entity/63dffc44-2557-41a5-80c0-9594fcd19dfc |
| hsdo_Variable → hsdo_Experiment | https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e | relation:ProvidedBy | https://climateKG.org/entity/7f60d215-8aea-467c-9c48-8a88d35da522 |
| hsdo_Location → hsdo_Experiment | https://climateKG.org/entity/a19e4450-64c4-4687-9080-cebded8a90eb | relation:ProvidedBy | https://climateKG.org/entity/79841056-b651-439c-b638-439e94731d31 |
| hsdo_Provider → hsdo_Variable | https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23 | relation:ProvidedBy | https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e |
| hsdo_Institution → hsdo_Institution | https://climateKG.org/entity/ae4dd4b3-9603-4dee-9241-ec1ed2b905bf | relation:ProvidedBy | https://climateKG.org/entity/ae4dd4b3-9603-4dee-9241-ec1ed2b905bf |
| hsdo_Models → hsdo_Location | https://climateKG.org/entity/553cf82e-b07f-48c7-b7ae-48809acde89c | relation:ProvidedBy | https://climateKG.org/entity/2a65dfd1-83e7-4886-a732-316b170522a1 |
| hsdo_Models → hsdo_Instrument | https://climateKG.org/entity/35d2677c-619a-4a47-a5a7-3feb9973c5ab | relation:ProvidedBy | https://climateKG.org/entity/3ce7f4f0-d2db-4352-8762-d88296f7aa15 |
| hsdo_Models → hsdo_Model | https://climateKG.org/entity/ea5ccefb-e390-43d5-8202-33e004565beb | relation:ProvidedBy | https://climateKG.org/entity/8680cb49-1637-4a47-a5fd-f39d4e618e45 |
| hsdo_Models → hsdo_Experiment | https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9 | relation:ProvidedBy | https://climateKG.org/entity/666b0926-b509-4680-b551-530d8aaca9ec |
| hsdo_Instrument → hsdo_Science_Keyword | https://climateKG.org/entity/fe2719de-c5c8-4ce6-8230-1d16c8155991 | relation:ProvidedBy | https://climateKG.org/entity/bc90bc40-2a21-4a6f-9fb9-bf3ae5845157 |
| hsdo_Platform → hsdo_Experiment | https://climateKG.org/entity/b1c1ea44-000a-4535-8e90-d8dd447371d4 | relation:ProvidedBy | https://climateKG.org/entity/666b0926-b509-4680-b551-530d8aaca9ec |
| hsdo_Experiment → hsdo_Science_Keyword | https://climateKG.org/entity/38fb609b-2a10-4d4f-b2e8-7e51161ec974 | relation:ProvidedBy | https://climateKG.org/entity/59920ad4-85fb-4cee-ba56-f39bc5857a3d |
| hsdo_Institution → hsdo_Model | https://climateKG.org/entity/d9fbd2ea-803e-48b7-a1f2-774e6845cc1f | relation:ProvidedBy | https://climateKG.org/entity/6fb2817f-c3e3-4332-85ad-79f74227e6bc |
| hsdo_Institution → hsdo_Dataset | https://climateKG.org/entity/3be6270c-8554-467a-b2c7-9c13bc086b10 | relation:ProvidedBy | https://climateKG.org/entity/f9ce1564-0144-43d2-a9dd-bc48edcefb37 |
| hsdo_Institution → hsdo_Location | https://climateKG.org/entity/3be6270c-8554-467a-b2c7-9c13bc086b10 | relation:ProvidedBy | https://climateKG.org/entity/70fb5a3b-35b1-4048-a8be-56a0d865281c |
| hsdo_Institution → hsdo_Models | https://climateKG.org/entity/e8df7edd-a176-45c9-8515-3a520948ef63 | relation:ProvidedBy | https://climateKG.org/entity/f88c4559-fc4b-4b4a-ac57-0f15bb24e8e0 |
| hsdo_Instrument → hsdo_Models | https://climateKG.org/entity/ae02541a-4968-4573-8569-0f4a02575ab2 | relation:ProvidedBy | https://climateKG.org/entity/c5b13fa4-0069-40ce-85cb-bfbab34c2058 |
| hsdo_Instrument → hsdo_Project | https://climateKG.org/entity/fe37b7a7-b6ca-4880-8dcf-16973cd8ecc8 | relation:ProvidedBy | https://climateKG.org/entity/eab3419f-a0c2-4d55-9500-87ee00600291 |
| hsdo_Project → hsdo_Provider | https://climateKG.org/entity/3970129f-8bb5-49bb-8517-1532f0a0f828 | relation:ProvidedBy | https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23 |
| hsdo_Institution → hsdo_Project | https://climateKG.org/entity/fea56568-3eb7-4527-a8bb-112d5d721e11 | relation:ProvidedBy | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 |
| hsdo_Platform → hsdo_Platform | https://climateKG.org/entity/432d2336-1111-4305-a8cb-8d0c8a3af632 | relation:ProvidedBy | https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5 |
| hsdo_Provider → hsdo_Science_Keyword | https://climateKG.org/entity/efcb13d4-ce68-4d42-8cc5-932ac3ef6126 | relation:ProvidedBy | https://climateKG.org/entity/59920ad4-85fb-4cee-ba56-f39bc5857a3d |
| hsdo_Platform → hsdo_Science_Keyword | https://climateKG.org/entity/b1c1ea44-000a-4535-8e90-d8dd447371d4 | relation:ProvidedBy | https://climateKG.org/entity/d6aec072-daf9-4f96-b667-6c7831cf6bdd |
| hsdo_Platform → hsdo_Location | https://climateKG.org/entity/f959e3c5-f014-40b7-a134-4d41b616f79d | relation:ProvidedBy | https://climateKG.org/entity/d4c65f0d-f825-4040-8dd3-69b85979101a |
| hsdo_Platform → hsdo_Institution | https://climateKG.org/entity/b1c1ea44-000a-4535-8e90-d8dd447371d4 | relation:ProvidedBy | https://climateKG.org/entity/d9fbd2ea-803e-48b7-a1f2-774e6845cc1f |
| hsdo_Platform → hsdo_Model | https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5 | relation:ProvidedBy | https://climateKG.org/entity/7583957b-e902-4daf-a2b9-81b65c3f3b8f |
| hsdo_Platform → hsdo_Project | https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5 | relation:ProvidedBy | https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799 |
| hsdo_Project → hsdo_Activity | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:ProvidedBy | https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7 |
| hsdo_Project → hsdo_Experiment | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:ProvidedBy | https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf |
| hsdo_Location → hsdo_Project | https://climateKG.org/entity/f9837873-62cd-402c-af8b-571876942a83 | relation:ProvidedBy | https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799 |
| hsdo_Cmip6_Source_Id → hsdo_Project | https://climateKG.org/entity/f083ae80-224b-4453-8a18-d1b13d9d2f90 | relation:ProvidedBy | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 |
| hsdo_Experiment → hsdo_Platform | https://climateKG.org/entity/a956d045-3b12-441c-8a18-fac7d33b2b4e | relation:ProvidedBy | https://climateKG.org/entity/da2c70fd-d92b-45be-b159-b2c10cb387c6 |
| hsdo_Provider → hsdo_Model | https://climateKG.org/entity/df0ab7d8-025d-496d-8d5e-991d208c81fa | relation:ProvidedBy | https://climateKG.org/entity/13df63e8-85ad-405d-9b43-256371e259c0 |
| hsdo_Location → hsdo_Location | https://climateKG.org/entity/fa57b0a0-9723-4195-bdd1-4f26aefa0e07 | relation:ProvidedBy | https://climateKG.org/entity/3d7ecc4f-e79e-40d1-8796-63059888bf5f |
| hsdo_Models → hsdo_Provider | https://climateKG.org/entity/b30ecade-ec88-4f0e-9482-532a2ceeb0d5 | relation:ProvidedBy | https://climateKG.org/entity/df0ab7d8-025d-496d-8d5e-991d208c81fa |
| hsdo_Model → hsdo_Platform | https://climateKG.org/entity/57441436-5372-484e-983c-f96cbc51ef72 | relation:ProvidedBy | https://climateKG.org/entity/10c24d93-c480-42fc-a438-4600e2d14a77 |
| hsdo_Activity → hsdo_Models | https://climateKG.org/entity/5796ebd9-7dcb-4968-b876-1e678484cc62 | relation:ProvidedBy | https://climateKG.org/entity/378fef81-dd2e-4e80-9922-28cbf45d32dc |
| hsdo_Activity → hsdo_Institution | https://climateKG.org/entity/5796ebd9-7dcb-4968-b876-1e678484cc62 | relation:ProvidedBy | https://climateKG.org/entity/4315c66b-86e9-4127-a456-e549687012cf |
| hsdo_Activity → hsdo_Experiment | https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58 | relation:ProvidedBy | https://climateKG.org/entity/666b0926-b509-4680-b551-530d8aaca9ec |
| hsdo_Activity → hsdo_Instrument | https://climateKG.org/entity/7c5a2cb8-495a-4d32-b9ef-a54f43192712 | relation:ProvidedBy | https://climateKG.org/entity/51233a6a-ba89-4a05-8692-0934edbadcba |
| hsdo_Provider → hsdo_Experiment | https://climateKG.org/entity/e236abe1-c8c5-4bca-ab7d-89b5a0392d6b | relation:ProvidedBy | https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049 |
| hsdo_Models → hsdo_Science_Keyword | https://climateKG.org/entity/fc94343c-1809-431f-b3da-8ba5b887dda9 | relation:ProvidedBy | https://climateKG.org/entity/ef36cb15-ad64-4bdc-9331-42cc5b493671 |
| hsdo_Activity → hsdo_Project | https://climateKG.org/entity/8f528b66-670d-4198-b014-7fdc9e1f6890 | relation:ProvidedBy | https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799 |
| hsdo_Activity → hsdo_Activity | https://climateKG.org/entity/68885007-d975-4f24-bdd5-dd19b246bdf6 | relation:ProvidedBy | https://climateKG.org/entity/68885007-d975-4f24-bdd5-dd19b246bdf6 |
| hsdo_Location → hsdo_Data_Format | https://climateKG.org/entity/74d079b5-9b36-45c9-9b09-7e3646b65a85 | relation:ProvidedBy | https://climateKG.org/entity/d0b3505e-77bb-45a0-83fe-787bc3812b67 |
| hsdo_Experiment → hsdo_Models | https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049 | relation:ProvidedBy | https://climateKG.org/entity/e49f0aae-c2ef-4fd2-aaf4-ddfad074bb75 |
| hsdo_Project → hsdo_Variable | https://climateKG.org/entity/820f2f42-79e8-4ea5-be0b-b828766e11ad | relation:ProvidedBy | https://climateKG.org/entity/b631f7b6-9a64-4f2b-bd29-7a20a466e44b |
| hsdo_Project → hsdo_Data_Format | https://climateKG.org/entity/8289e024-54f7-4c63-a8ca-e7b1aef80be2 | relation:ProvidedBy | https://climateKG.org/entity/ac392872-1571-4bfd-94dd-81f93d9f1fd0 |
| hsdo_Experiment → hsdo_Institution | https://climateKG.org/entity/8a106157-e0a0-4a3e-bed1-4ce3b8e06151 | relation:ProvidedBy | https://climateKG.org/entity/d9fbd2ea-803e-48b7-a1f2-774e6845cc1f |
| hsdo_Model → hsdo_Experiment | https://climateKG.org/entity/d6141f58-40bf-4a59-9fc2-707528e53486 | relation:ProvidedBy | https://climateKG.org/entity/a6212424-1146-4a79-a14c-8ce88543b08b |
| hsdo_Experiment → hsdo_Model | https://climateKG.org/entity/c72fe5bf-6ec6-48bc-9888-257db1daf0af | relation:ProvidedBy | https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58 |
| hsdo_Experiment → hsdo_Dataset | https://climateKG.org/entity/878e70de-f929-4d2f-9325-145ca95787e9 | relation:ProvidedBy | https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54 |
| hsdo_Experiment → hsdo_Cmip6_Source_Id | https://climateKG.org/entity/910d9fdb-84fe-4f62-9172-41888cc181a4 | relation:ProvidedBy | https://climateKG.org/entity/d0c16581-6951-4e8d-a0c1-97e9fcaa031a |
| hsdo_Location → hsdo_Platform | https://climateKG.org/entity/9af548c9-7050-4d59-b66d-adf52f2fb242 | relation:ProvidedBy | https://climateKG.org/entity/da2c70fd-d92b-45be-b159-b2c10cb387c6 |
| hsdo_Cmip6_Source_Id → hsdo_Activity | https://climateKG.org/entity/df0ba39b-7461-4cee-8660-c80fee72e96b | relation:ProvidedBy | https://climateKG.org/entity/8f528b66-670d-4198-b014-7fdc9e1f6890 |
| hsdo_Dataset → hsdo_Experiment | https://climateKG.org/entity/a0b26420-3a13-4742-8d6f-391dc5c49d64 | relation:ProvidedBy | https://climateKG.org/entity/25f8d5c2-1a32-4453-9421-65c5d9d3d114 |
| hsdo_Data_Format → hsdo_Provider | https://climateKG.org/entity/a2904083-1e32-4086-b028-a2afc2ffd443 | relation:ProvidedBy | https://climateKG.org/entity/32f12730-2c26-43e7-a357-dee6ff4b1764 |
| hsdo_Cmip6_Source_Id → hsdo_Instrument | https://climateKG.org/entity/bff6b593-1884-4aea-87a1-36f606d3a020 | relation:ProvidedBy | https://climateKG.org/entity/b62575f6-25e9-4a50-b0f6-a45dbf22c8d4 |
| hsdo_Provider → hsdo_Platform | https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23 | relation:ProvidedBy | https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5 |
| hsdo_Data_Format → hsdo_Platform | https://climateKG.org/entity/ac392872-1571-4bfd-94dd-81f93d9f1fd0 | relation:ProvidedBy | https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5 |
| hsdo_Experiment → hsdo_Provider | https://climateKG.org/entity/b7eb8278-0dc3-4121-87ea-14173279dfb4 | relation:ProvidedBy | https://climateKG.org/entity/68057636-bb40-472f-86cd-9b5c01f3c3d0 |
| hsdo_Platform → hsdo_Models | https://climateKG.org/entity/b1c1ea44-000a-4535-8e90-d8dd447371d4 | relation:ProvidedBy | https://climateKG.org/entity/553cf82e-b07f-48c7-b7ae-48809acde89c |
| hsdo_Model → hsdo_Provider | https://climateKG.org/entity/b8a877b7-d867-4305-9053-3777e5dd330a | relation:ProvidedBy | https://climateKG.org/entity/85510ccc-5dc9-44ff-871e-775e856714f8 |
| hsdo_Models → hsdo_Measurement_Name | https://climateKG.org/entity/c5b13fa4-0069-40ce-85cb-bfbab34c2058 | relation:ProvidedBy | https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e |
| hsdo_Data_Format → hsdo_Instrument | https://climateKG.org/entity/d0b3505e-77bb-45a0-83fe-787bc3812b67 | relation:ProvidedBy | https://climateKG.org/entity/085edf65-1c8c-414a-b8e4-a1a08ff08f22 |
| hsdo_Data_Format → hsdo_Location | https://climateKG.org/entity/d0b3505e-77bb-45a0-83fe-787bc3812b67 | relation:ProvidedBy | https://climateKG.org/entity/74d079b5-9b36-45c9-9b09-7e3646b65a85 |
| hsdo_Model → hsdo_Models | https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58 | relation:ProvidedBy | https://climateKG.org/entity/4270e57b-0ed2-43ab-9a7a-cd09e3983691 |
| hsdo_Dataset → hsdo_Platform | https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54 | relation:ProvidedBy | https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5 |
| hsdo_Dataset → hsdo_Model | https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54 | relation:ProvidedBy | https://climateKG.org/entity/8680cb49-1637-4a47-a5fd-f39d4e618e45 |
| hsdo_Location → hsdo_Science_Keyword | https://climateKG.org/entity/f36d71c6-f2ad-49c4-809f-09b4f0688412 | relation:ProvidedBy | https://climateKG.org/entity/d2a5c7ec-ccf2-4ab7-8863-9063be91c022 |
| hsdo_Institution → hsdo_Instrument | https://climateKG.org/entity/fea56568-3eb7-4527-a8bb-112d5d721e11 | relation:ProvidedBy | https://climateKG.org/entity/ac87227c-b943-400a-ac61-71e42e8eb5f3 |
| hsdo_Institution → hsdo_Platform | https://climateKG.org/entity/dd747113-048d-4ed1-aa70-23a7bf528077 | relation:ProvidedBy | https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5 |
| hsdo_Project → hsdo_Institution | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:ProvidedBy | https://climateKG.org/entity/3306fdd4-c844-4280-ac37-226d2272dcd4 |
| hsdo_Project → hsdo_Models | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:ProvidedBy | https://climateKG.org/entity/f88c4559-fc4b-4b4a-ac57-0f15bb24e8e0 |
| hsdo_Instrument → hsdo_Variable | https://climateKG.org/entity/ecbe9f17-6012-4e39-a707-713973b7d167 | relation:ProvidedBy | https://climateKG.org/entity/d11237c8-639e-4725-bedf-0abbabfdc3ae |
| hsdo_Data_Format → hsdo_Experiment | https://climateKG.org/entity/ee016d07-002a-4c22-b05b-5ead6121ed3f | relation:ProvidedBy | https://climateKG.org/entity/41cd228c-4677-4900-9507-70144d8b50bc |
| hsdo_Instrument → hsdo_Activity | https://climateKG.org/entity/ee3e296f-fdc0-4695-95af-dbe63f43b679 | relation:ProvidedBy | https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58 |
| hsdo_Project → hsdo_Sub_Experiment_Id | https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 | relation:ProvidedBy | https://climateKG.org/entity/81165ebd-6b7a-44df-ac3a-b640e5d69bc4 |


## Comments

* 17 occurrences with subject type hsdo_Model and object type hsdo_Instrument.
* 5 occurrences with subject type hsdo_Experiment and object type hsdo_Location.
* 7 occurrences with subject type hsdo_Experiment and object type hsdo_Project.
* 1 occurrences with subject type hsdo_Provider and object type hsdo_Activity.
* 3 occurrences with subject type hsdo_Models and object type hsdo_Activity.
* 25 occurrences with subject type hsdo_Models and object type hsdo_Project.
* 1 occurrences with subject type hsdo_Instrument and object type hsdo_Measurement_Name.
* 24 occurrences with subject type hsdo_Instrument and object type hsdo_Location.
* 31 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.
* 4 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Model.
* 16 occurrences with subject type hsdo_Instrument and object type hsdo_Experiment.
* 2 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Project.
* 11 occurrences with subject type hsdo_Model and object type hsdo_Project.
* 4 occurrences with subject type hsdo_Model and object type hsdo_Location.
* 3 occurrences with subject type hsdo_Platform and object type hsdo_Provider.
* 15 occurrences with subject type hsdo_Project and object type hsdo_Instrument.
* 5 occurrences with subject type hsdo_Provider and object type hsdo_Provider.
* 3 occurrences with subject type hsdo_Provider and object type hsdo_Institution.
* 5 occurrences with subject type hsdo_Provider and object type hsdo_Project.
* 4 occurrences with subject type hsdo_Project and object type hsdo_Platform.
* 8 occurrences with subject type hsdo_Platform and object type hsdo_Instrument.
* 1 occurrences with subject type hsdo_Variable and object type hsdo_Model.
* 8 occurrences with subject type hsdo_Instrument and object type hsdo_Institution.
* 9 occurrences with subject type hsdo_Project and object type hsdo_Model.
* 5 occurrences with subject type hsdo_Models and object type hsdo_Institution.
* 6 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.
* 9 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
* 4 occurrences with subject type hsdo_Location and object type hsdo_Model.
* 16 occurrences with subject type hsdo_Instrument and object type hsdo_Model.
* 26 occurrences with subject type hsdo_Project and object type hsdo_Location.
* 20 occurrences with subject type hsdo_Provider and object type hsdo_Location.
* 11 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.
* 19 occurrences with subject type hsdo_Location and object type hsdo_Instrument.
* 4 occurrences with subject type hsdo_Model and object type hsdo_Model.
* 2 occurrences with subject type hsdo_Data_Format and object type hsdo_Science_Keyword.
* 4 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Project and object type hsdo_Chronostratigraphic_Unit.
* 5 occurrences with subject type hsdo_Model and object type hsdo_Institution.
* 16 occurrences with subject type hsdo_Project and object type hsdo_Project.
* 16 occurrences with subject type hsdo_Provider and object type hsdo_Instrument.
* 6 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Instrument.
* 12 occurrences with subject type hsdo_Instrument and object type hsdo_Provider.
* 2 occurrences with subject type hsdo_Dataset and object type hsdo_Institution.
* 3 occurrences with subject type hsdo_Dataset and object type hsdo_Location.
* 2 occurrences with subject type hsdo_Dataset and object type hsdo_Science_Keyword.
* 3 occurrences with subject type hsdo_Dataset and object type hsdo_Instrument.
* 1 occurrences with subject type hsdo_Dataset and object type hsdo_Provider.
* 2 occurrences with subject type hsdo_Project and object type hsdo_Dataset.
* 3 occurrences with subject type hsdo_Project and object type hsdo_Science_Keyword.
* 7 occurrences with subject type hsdo_Location and object type hsdo_Provider.
* 1 occurrences with subject type hsdo_Location and object type hsdo_Activity.
* 1 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Location.
* 1 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Provider.
* 1 occurrences with subject type hsdo_Variable and object type hsdo_Experiment.
* 8 occurrences with subject type hsdo_Location and object type hsdo_Experiment.
* 2 occurrences with subject type hsdo_Provider and object type hsdo_Variable.
* 3 occurrences with subject type hsdo_Institution and object type hsdo_Institution.
* 3 occurrences with subject type hsdo_Models and object type hsdo_Location.
* 1 occurrences with subject type hsdo_Models and object type hsdo_Instrument.
* 3 occurrences with subject type hsdo_Models and object type hsdo_Model.
* 2 occurrences with subject type hsdo_Models and object type hsdo_Experiment.
* 3 occurrences with subject type hsdo_Instrument and object type hsdo_Science_Keyword.
* 2 occurrences with subject type hsdo_Platform and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Experiment and object type hsdo_Science_Keyword.
* 5 occurrences with subject type hsdo_Institution and object type hsdo_Model.
* 2 occurrences with subject type hsdo_Institution and object type hsdo_Dataset.
* 1 occurrences with subject type hsdo_Institution and object type hsdo_Location.
* 7 occurrences with subject type hsdo_Institution and object type hsdo_Models.
* 3 occurrences with subject type hsdo_Instrument and object type hsdo_Models.
* 24 occurrences with subject type hsdo_Instrument and object type hsdo_Project.
* 8 occurrences with subject type hsdo_Project and object type hsdo_Provider.
* 4 occurrences with subject type hsdo_Institution and object type hsdo_Project.
* 1 occurrences with subject type hsdo_Platform and object type hsdo_Platform.
* 2 occurrences with subject type hsdo_Provider and object type hsdo_Science_Keyword.
* 4 occurrences with subject type hsdo_Platform and object type hsdo_Science_Keyword.
* 3 occurrences with subject type hsdo_Platform and object type hsdo_Location.
* 2 occurrences with subject type hsdo_Platform and object type hsdo_Institution.
* 1 occurrences with subject type hsdo_Platform and object type hsdo_Model.
* 1 occurrences with subject type hsdo_Platform and object type hsdo_Project.
* 4 occurrences with subject type hsdo_Project and object type hsdo_Activity.
* 12 occurrences with subject type hsdo_Project and object type hsdo_Experiment.
* 10 occurrences with subject type hsdo_Location and object type hsdo_Project.
* 9 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Project.
* 4 occurrences with subject type hsdo_Experiment and object type hsdo_Platform.
* 5 occurrences with subject type hsdo_Provider and object type hsdo_Model.
* 15 occurrences with subject type hsdo_Location and object type hsdo_Location.
* 2 occurrences with subject type hsdo_Models and object type hsdo_Provider.
* 1 occurrences with subject type hsdo_Model and object type hsdo_Platform.
* 2 occurrences with subject type hsdo_Activity and object type hsdo_Models.
* 1 occurrences with subject type hsdo_Activity and object type hsdo_Institution.
* 2 occurrences with subject type hsdo_Activity and object type hsdo_Experiment.
* 2 occurrences with subject type hsdo_Activity and object type hsdo_Instrument.
* 5 occurrences with subject type hsdo_Provider and object type hsdo_Experiment.
* 2 occurrences with subject type hsdo_Models and object type hsdo_Science_Keyword.
* 3 occurrences with subject type hsdo_Activity and object type hsdo_Project.
* 1 occurrences with subject type hsdo_Activity and object type hsdo_Activity.
* 1 occurrences with subject type hsdo_Location and object type hsdo_Data_Format.
* 3 occurrences with subject type hsdo_Experiment and object type hsdo_Models.
* 3 occurrences with subject type hsdo_Project and object type hsdo_Variable.
* 1 occurrences with subject type hsdo_Project and object type hsdo_Data_Format.
* 2 occurrences with subject type hsdo_Experiment and object type hsdo_Institution.
* 4 occurrences with subject type hsdo_Model and object type hsdo_Experiment.
* 2 occurrences with subject type hsdo_Experiment and object type hsdo_Model.
* 1 occurrences with subject type hsdo_Experiment and object type hsdo_Dataset.
* 1 occurrences with subject type hsdo_Experiment and object type hsdo_Cmip6_Source_Id.
* 1 occurrences with subject type hsdo_Location and object type hsdo_Platform.
* 2 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Activity.
* 1 occurrences with subject type hsdo_Dataset and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Provider.
* 2 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Instrument.
* 2 occurrences with subject type hsdo_Provider and object type hsdo_Platform.
* 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Platform.
* 3 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.
* 1 occurrences with subject type hsdo_Platform and object type hsdo_Models.
* 1 occurrences with subject type hsdo_Model and object type hsdo_Provider.
* 1 occurrences with subject type hsdo_Models and object type hsdo_Measurement_Name.
* 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Instrument.
* 2 occurrences with subject type hsdo_Data_Format and object type hsdo_Location.
* 2 occurrences with subject type hsdo_Model and object type hsdo_Models.
* 1 occurrences with subject type hsdo_Dataset and object type hsdo_Platform.
* 1 occurrences with subject type hsdo_Dataset and object type hsdo_Model.
* 2 occurrences with subject type hsdo_Location and object type hsdo_Science_Keyword.
* 4 occurrences with subject type hsdo_Institution and object type hsdo_Instrument.
* 1 occurrences with subject type hsdo_Institution and object type hsdo_Platform.
* 2 occurrences with subject type hsdo_Project and object type hsdo_Institution.
* 5 occurrences with subject type hsdo_Project and object type hsdo_Models.
* 1 occurrences with subject type hsdo_Instrument and object type hsdo_Variable.
* 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Experiment.
* 1 occurrences with subject type hsdo_Instrument and object type hsdo_Activity.
* 1 occurrences with subject type hsdo_Project and object type hsdo_Sub_Experiment_Id.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:ProvidedBy |
| native | climatepub4-kg/:relation_ProvidedBy |




## LinkML Source

<details>
```yaml
name: relation_ProvidedBy
description: No slot (predicate) description specified
comments:
- 17 occurrences with subject type hsdo_Model and object type hsdo_Instrument.
- 5 occurrences with subject type hsdo_Experiment and object type hsdo_Location.
- 7 occurrences with subject type hsdo_Experiment and object type hsdo_Project.
- 1 occurrences with subject type hsdo_Provider and object type hsdo_Activity.
- 3 occurrences with subject type hsdo_Models and object type hsdo_Activity.
- 25 occurrences with subject type hsdo_Models and object type hsdo_Project.
- 1 occurrences with subject type hsdo_Instrument and object type hsdo_Measurement_Name.
- 24 occurrences with subject type hsdo_Instrument and object type hsdo_Location.
- 31 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.
- 4 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Model.
- 16 occurrences with subject type hsdo_Instrument and object type hsdo_Experiment.
- 2 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Project.
- 11 occurrences with subject type hsdo_Model and object type hsdo_Project.
- 4 occurrences with subject type hsdo_Model and object type hsdo_Location.
- 3 occurrences with subject type hsdo_Platform and object type hsdo_Provider.
- 15 occurrences with subject type hsdo_Project and object type hsdo_Instrument.
- 5 occurrences with subject type hsdo_Provider and object type hsdo_Provider.
- 3 occurrences with subject type hsdo_Provider and object type hsdo_Institution.
- 5 occurrences with subject type hsdo_Provider and object type hsdo_Project.
- 4 occurrences with subject type hsdo_Project and object type hsdo_Platform.
- 8 occurrences with subject type hsdo_Platform and object type hsdo_Instrument.
- 1 occurrences with subject type hsdo_Variable and object type hsdo_Model.
- 8 occurrences with subject type hsdo_Instrument and object type hsdo_Institution.
- 9 occurrences with subject type hsdo_Project and object type hsdo_Model.
- 5 occurrences with subject type hsdo_Models and object type hsdo_Institution.
- 6 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.
- 9 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
- 4 occurrences with subject type hsdo_Location and object type hsdo_Model.
- 16 occurrences with subject type hsdo_Instrument and object type hsdo_Model.
- 26 occurrences with subject type hsdo_Project and object type hsdo_Location.
- 20 occurrences with subject type hsdo_Provider and object type hsdo_Location.
- 11 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.
- 19 occurrences with subject type hsdo_Location and object type hsdo_Instrument.
- 4 occurrences with subject type hsdo_Model and object type hsdo_Model.
- 2 occurrences with subject type hsdo_Data_Format and object type hsdo_Science_Keyword.
- 4 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Project and object type hsdo_Chronostratigraphic_Unit.
- 5 occurrences with subject type hsdo_Model and object type hsdo_Institution.
- 16 occurrences with subject type hsdo_Project and object type hsdo_Project.
- 16 occurrences with subject type hsdo_Provider and object type hsdo_Instrument.
- 6 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Instrument.
- 12 occurrences with subject type hsdo_Instrument and object type hsdo_Provider.
- 2 occurrences with subject type hsdo_Dataset and object type hsdo_Institution.
- 3 occurrences with subject type hsdo_Dataset and object type hsdo_Location.
- 2 occurrences with subject type hsdo_Dataset and object type hsdo_Science_Keyword.
- 3 occurrences with subject type hsdo_Dataset and object type hsdo_Instrument.
- 1 occurrences with subject type hsdo_Dataset and object type hsdo_Provider.
- 2 occurrences with subject type hsdo_Project and object type hsdo_Dataset.
- 3 occurrences with subject type hsdo_Project and object type hsdo_Science_Keyword.
- 7 occurrences with subject type hsdo_Location and object type hsdo_Provider.
- 1 occurrences with subject type hsdo_Location and object type hsdo_Activity.
- 1 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Location.
- 1 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Provider.
- 1 occurrences with subject type hsdo_Variable and object type hsdo_Experiment.
- 8 occurrences with subject type hsdo_Location and object type hsdo_Experiment.
- 2 occurrences with subject type hsdo_Provider and object type hsdo_Variable.
- 3 occurrences with subject type hsdo_Institution and object type hsdo_Institution.
- 3 occurrences with subject type hsdo_Models and object type hsdo_Location.
- 1 occurrences with subject type hsdo_Models and object type hsdo_Instrument.
- 3 occurrences with subject type hsdo_Models and object type hsdo_Model.
- 2 occurrences with subject type hsdo_Models and object type hsdo_Experiment.
- 3 occurrences with subject type hsdo_Instrument and object type hsdo_Science_Keyword.
- 2 occurrences with subject type hsdo_Platform and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Experiment and object type hsdo_Science_Keyword.
- 5 occurrences with subject type hsdo_Institution and object type hsdo_Model.
- 2 occurrences with subject type hsdo_Institution and object type hsdo_Dataset.
- 1 occurrences with subject type hsdo_Institution and object type hsdo_Location.
- 7 occurrences with subject type hsdo_Institution and object type hsdo_Models.
- 3 occurrences with subject type hsdo_Instrument and object type hsdo_Models.
- 24 occurrences with subject type hsdo_Instrument and object type hsdo_Project.
- 8 occurrences with subject type hsdo_Project and object type hsdo_Provider.
- 4 occurrences with subject type hsdo_Institution and object type hsdo_Project.
- 1 occurrences with subject type hsdo_Platform and object type hsdo_Platform.
- 2 occurrences with subject type hsdo_Provider and object type hsdo_Science_Keyword.
- 4 occurrences with subject type hsdo_Platform and object type hsdo_Science_Keyword.
- 3 occurrences with subject type hsdo_Platform and object type hsdo_Location.
- 2 occurrences with subject type hsdo_Platform and object type hsdo_Institution.
- 1 occurrences with subject type hsdo_Platform and object type hsdo_Model.
- 1 occurrences with subject type hsdo_Platform and object type hsdo_Project.
- 4 occurrences with subject type hsdo_Project and object type hsdo_Activity.
- 12 occurrences with subject type hsdo_Project and object type hsdo_Experiment.
- 10 occurrences with subject type hsdo_Location and object type hsdo_Project.
- 9 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Project.
- 4 occurrences with subject type hsdo_Experiment and object type hsdo_Platform.
- 5 occurrences with subject type hsdo_Provider and object type hsdo_Model.
- 15 occurrences with subject type hsdo_Location and object type hsdo_Location.
- 2 occurrences with subject type hsdo_Models and object type hsdo_Provider.
- 1 occurrences with subject type hsdo_Model and object type hsdo_Platform.
- 2 occurrences with subject type hsdo_Activity and object type hsdo_Models.
- 1 occurrences with subject type hsdo_Activity and object type hsdo_Institution.
- 2 occurrences with subject type hsdo_Activity and object type hsdo_Experiment.
- 2 occurrences with subject type hsdo_Activity and object type hsdo_Instrument.
- 5 occurrences with subject type hsdo_Provider and object type hsdo_Experiment.
- 2 occurrences with subject type hsdo_Models and object type hsdo_Science_Keyword.
- 3 occurrences with subject type hsdo_Activity and object type hsdo_Project.
- 1 occurrences with subject type hsdo_Activity and object type hsdo_Activity.
- 1 occurrences with subject type hsdo_Location and object type hsdo_Data_Format.
- 3 occurrences with subject type hsdo_Experiment and object type hsdo_Models.
- 3 occurrences with subject type hsdo_Project and object type hsdo_Variable.
- 1 occurrences with subject type hsdo_Project and object type hsdo_Data_Format.
- 2 occurrences with subject type hsdo_Experiment and object type hsdo_Institution.
- 4 occurrences with subject type hsdo_Model and object type hsdo_Experiment.
- 2 occurrences with subject type hsdo_Experiment and object type hsdo_Model.
- 1 occurrences with subject type hsdo_Experiment and object type hsdo_Dataset.
- 1 occurrences with subject type hsdo_Experiment and object type hsdo_Cmip6_Source_Id.
- 1 occurrences with subject type hsdo_Location and object type hsdo_Platform.
- 2 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Activity.
- 1 occurrences with subject type hsdo_Dataset and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Provider.
- 2 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Instrument.
- 2 occurrences with subject type hsdo_Provider and object type hsdo_Platform.
- 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Platform.
- 3 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.
- 1 occurrences with subject type hsdo_Platform and object type hsdo_Models.
- 1 occurrences with subject type hsdo_Model and object type hsdo_Provider.
- 1 occurrences with subject type hsdo_Models and object type hsdo_Measurement_Name.
- 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Instrument.
- 2 occurrences with subject type hsdo_Data_Format and object type hsdo_Location.
- 2 occurrences with subject type hsdo_Model and object type hsdo_Models.
- 1 occurrences with subject type hsdo_Dataset and object type hsdo_Platform.
- 1 occurrences with subject type hsdo_Dataset and object type hsdo_Model.
- 2 occurrences with subject type hsdo_Location and object type hsdo_Science_Keyword.
- 4 occurrences with subject type hsdo_Institution and object type hsdo_Instrument.
- 1 occurrences with subject type hsdo_Institution and object type hsdo_Platform.
- 2 occurrences with subject type hsdo_Project and object type hsdo_Institution.
- 5 occurrences with subject type hsdo_Project and object type hsdo_Models.
- 1 occurrences with subject type hsdo_Instrument and object type hsdo_Variable.
- 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Experiment.
- 1 occurrences with subject type hsdo_Instrument and object type hsdo_Activity.
- 1 occurrences with subject type hsdo_Project and object type hsdo_Sub_Experiment_Id.
examples:
- description: hsdo_Model → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/7b36ad79-8cf3-46a9-b26c-52f3a0f1eac9
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f860ed88-991f-4b52-90b9-fc8d4046a598
    example_subject_type: hsdo_Model
- description: hsdo_Experiment → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/28761db9-82fe-4a24-9a89-0fd6047fa1ea
    example_object_type: hsdo_Location
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799
    example_object_type: hsdo_Project
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
    example_subject_type: hsdo_Experiment
- description: hsdo_Provider → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/68885007-d975-4f24-bdd5-dd19b246bdf6
    example_object_type: hsdo_Activity
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/0258d108-269d-409f-b2de-422483fe808e
    example_subject_type: hsdo_Provider
- description: hsdo_Models → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/8f528b66-670d-4198-b014-7fdc9e1f6890
    example_object_type: hsdo_Activity
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/80122908-8018-4511-810c-dd7aaf639b91
    example_subject_type: hsdo_Models
- description: hsdo_Models → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_object_type: hsdo_Project
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
    example_subject_type: hsdo_Models
- description: hsdo_Instrument → hsdo_Measurement_Name
  object:
    example_object: https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
    example_object_type: hsdo_Measurement_Name
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/0364f832-b1a8-4056-b811-51d3d1fc32ed
    example_subject_type: hsdo_Instrument
- description: hsdo_Instrument → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/523afb73-9b4c-4478-97e2-a7d5e228e31c
    example_object_type: hsdo_Location
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ee3e296f-fdc0-4695-95af-dbe63f43b679
    example_subject_type: hsdo_Instrument
- description: hsdo_Instrument → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/ecbe9f17-6012-4e39-a707-713973b7d167
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ecbe9f17-6012-4e39-a707-713973b7d167
    example_subject_type: hsdo_Instrument
- description: hsdo_Science_Keyword → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/c1564b40-d4ae-4e5b-b925-411b93cb68c5
    example_object_type: hsdo_Model
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/bc05d7d2-3c96-4bb6-b759-d45e3c673b86
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Instrument → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/c7245882-84a1-4192-acfa-a758b5b9c151
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d9750f06-3784-4058-941f-40289c8d9d8b
    example_subject_type: hsdo_Instrument
- description: hsdo_Science_Keyword → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799
    example_object_type: hsdo_Project
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/bd24a9a9-7d52-4c29-b2a0-6cefd216ae78
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Model → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
    example_object_type: hsdo_Project
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/e66edf58-9a3d-4250-b2ba-9120b943403f
    example_subject_type: hsdo_Model
- description: hsdo_Model → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/ecc4a2bb-f195-4296-b300-c1227221b688
    example_object_type: hsdo_Location
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f1e6caa5-2c97-407d-a0db-7bf01794d8e3
    example_subject_type: hsdo_Model
- description: hsdo_Platform → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/68447296-6019-453b-9684-3cd3ff1530c9
    example_object_type: hsdo_Provider
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/da2c70fd-d92b-45be-b159-b2c10cb387c6
    example_subject_type: hsdo_Platform
- description: hsdo_Project → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/1c645150-c046-4652-8f68-11167a19ba91
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ffcca1c5-fffd-4359-b282-e00fc77c979e
    example_subject_type: hsdo_Project
- description: hsdo_Provider → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23
    example_object_type: hsdo_Provider
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/df0ab7d8-025d-496d-8d5e-991d208c81fa
    example_subject_type: hsdo_Provider
- description: hsdo_Provider → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/d9fbd2ea-803e-48b7-a1f2-774e6845cc1f
    example_object_type: hsdo_Institution
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23
    example_subject_type: hsdo_Provider
- description: hsdo_Provider → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799
    example_object_type: hsdo_Project
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/c19dfe38-1e9d-4cdb-a900-07640628425d
    example_subject_type: hsdo_Provider
- description: hsdo_Project → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5
    example_object_type: hsdo_Platform
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/8289e024-54f7-4c63-a8ca-e7b1aef80be2
    example_subject_type: hsdo_Project
- description: hsdo_Platform → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/eeba88d2-20bf-43b1-bccf-b125485405f4
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/da2c70fd-d92b-45be-b159-b2c10cb387c6
    example_subject_type: hsdo_Platform
- description: hsdo_Variable → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/8680cb49-1637-4a47-a5fd-f39d4e618e45
    example_object_type: hsdo_Model
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
    example_subject_type: hsdo_Variable
- description: hsdo_Instrument → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/3be6270c-8554-467a-b2c7-9c13bc086b10
    example_object_type: hsdo_Institution
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ba2cf9cf-36c9-421b-bd6e-339e7cef1092
    example_subject_type: hsdo_Instrument
- description: hsdo_Project → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/04d24dfe-c9f7-43b6-8bd8-8f2613767257
    example_object_type: hsdo_Model
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    example_subject_type: hsdo_Project
- description: hsdo_Models → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/d9fbd2ea-803e-48b7-a1f2-774e6845cc1f
    example_object_type: hsdo_Institution
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/c266a473-338f-4fe9-965c-f8ae853ff57b
    example_subject_type: hsdo_Models
- description: hsdo_Experiment → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/ae02541a-4968-4573-8569-0f4a02575ab2
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/25f8d5c2-1a32-4453-9421-65c5d9d3d114
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/cbab6fb9-2240-4fb4-97c0-6ec918ddd729
    example_subject_type: hsdo_Experiment
- description: hsdo_Location → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/04d24dfe-c9f7-43b6-8bd8-8f2613767257
    example_object_type: hsdo_Model
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/df5ff39e-b49f-4517-afc0-1842a1a6fdc7
    example_subject_type: hsdo_Location
- description: hsdo_Instrument → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/d287b7f5-7565-4602-a023-005578328c22
    example_object_type: hsdo_Model
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb
    example_subject_type: hsdo_Instrument
- description: hsdo_Project → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/9f36c803-a972-4191-a345-faad9f6cf813
    example_object_type: hsdo_Location
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ffdb1819-43ba-4307-80db-dae705f62a8d
    example_subject_type: hsdo_Project
- description: hsdo_Provider → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/9ac7a1c5-4179-47bc-8589-ebaa90d6cbd1
    example_object_type: hsdo_Location
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ff850d62-675c-4386-a375-fe4af92ec3ff
    example_subject_type: hsdo_Provider
- description: hsdo_Instrument → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5
    example_object_type: hsdo_Platform
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f9fd6f89-9a67-4ece-9514-3803e7787520
    example_subject_type: hsdo_Instrument
- description: hsdo_Location → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/bc320625-d9ba-41f5-9336-57e86fd878f3
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/fa57b0a0-9723-4195-bdd1-4f26aefa0e07
    example_subject_type: hsdo_Location
- description: hsdo_Model → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/04d24dfe-c9f7-43b6-8bd8-8f2613767257
    example_object_type: hsdo_Model
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/de863e7e-caf7-4beb-ab2e-b9f37d96d534
    example_subject_type: hsdo_Model
- description: hsdo_Data_Format → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/3de6fa74-bb80-4bc6-ae60-1e6fe8ae6c67
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d0b3505e-77bb-45a0-83fe-787bc3812b67
    example_subject_type: hsdo_Data_Format
- description: hsdo_Science_Keyword → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ecd03762-df34-49b7-91f2-d8a51acd270e
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Project → hsdo_Chronostratigraphic_Unit
  object:
    example_object: https://climateKG.org/entity/5ba80ec4-1060-4228-ab97-d7c24980c97e
    example_object_type: hsdo_Chronostratigraphic_Unit
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/25193d98-16dc-47df-a2b1-51bbbdcdbc2e
    example_subject_type: hsdo_Project
- description: hsdo_Model → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/3be6270c-8554-467a-b2c7-9c13bc086b10
    example_object_type: hsdo_Institution
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d6141f58-40bf-4a59-9fc2-707528e53486
    example_subject_type: hsdo_Model
- description: hsdo_Project → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799
    example_object_type: hsdo_Project
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Provider → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/4a426aab-4a95-4bf4-8449-19a72a251541
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f0f5d722-bff7-4811-b834-e012afe7341e
    example_subject_type: hsdo_Provider
- description: hsdo_Science_Keyword → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/f6350232-b1c7-458c-bc43-bda357ebb6db
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/c77819e9-f62f-48dc-b924-e7a73b4dcda9
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Instrument → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23
    example_object_type: hsdo_Provider
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/fc4f2acd-ace7-452b-a540-4162f9e9ddb0
    example_subject_type: hsdo_Instrument
- description: hsdo_Dataset → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/3be6270c-8554-467a-b2c7-9c13bc086b10
    example_object_type: hsdo_Institution
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/aeec8336-4b23-4f14-a985-9ca0150f1afd
    example_subject_type: hsdo_Dataset
- description: hsdo_Dataset → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/2a9bce94-c391-4834-96bb-a9685d3590b1
    example_object_type: hsdo_Location
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
    example_subject_type: hsdo_Dataset
- description: hsdo_Dataset → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/40386eea-beb0-4b83-906b-75c6bfa24b73
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
    example_subject_type: hsdo_Dataset
- description: hsdo_Dataset → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/da9cf145-0986-42b4-9ae4-c8b65932ee77
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f9ce1564-0144-43d2-a9dd-bc48edcefb37
    example_subject_type: hsdo_Dataset
- description: hsdo_Dataset → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
    example_object_type: hsdo_Provider
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/2892e23f-5249-439d-8c0e-6c1d190b3beb
    example_subject_type: hsdo_Dataset
- description: hsdo_Project → hsdo_Dataset
  object:
    example_object: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
    example_object_type: hsdo_Dataset
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    example_subject_type: hsdo_Project
- description: hsdo_Project → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/b29b46ad-f05f-4144-b965-5f606ce96963
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799
    example_subject_type: hsdo_Project
- description: hsdo_Location → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/68057636-bb40-472f-86cd-9b5c01f3c3d0
    example_object_type: hsdo_Provider
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/e325f579-2d4c-4c72-81f4-30cb8723261a
    example_subject_type: hsdo_Location
- description: hsdo_Location → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7
    example_object_type: hsdo_Activity
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/2a726c91-2cd0-4b08-a301-30396de71b91
    example_subject_type: hsdo_Location
- description: hsdo_Science_Keyword → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/162e2243-3266-4999-b352-d8a1a9dc82ac
    example_object_type: hsdo_Location
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/2ab4134d-1ac7-4421-a7a6-659a542aff4c
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Science_Keyword → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/63dffc44-2557-41a5-80c0-9594fcd19dfc
    example_object_type: hsdo_Provider
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/2ab4134d-1ac7-4421-a7a6-659a542aff4c
    example_subject_type: hsdo_Science_Keyword
- description: hsdo_Variable → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/7f60d215-8aea-467c-9c48-8a88d35da522
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    example_subject_type: hsdo_Variable
- description: hsdo_Location → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/79841056-b651-439c-b638-439e94731d31
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/a19e4450-64c4-4687-9080-cebded8a90eb
    example_subject_type: hsdo_Location
- description: hsdo_Provider → hsdo_Variable
  object:
    example_object: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    example_object_type: hsdo_Variable
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23
    example_subject_type: hsdo_Provider
- description: hsdo_Institution → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/ae4dd4b3-9603-4dee-9241-ec1ed2b905bf
    example_object_type: hsdo_Institution
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ae4dd4b3-9603-4dee-9241-ec1ed2b905bf
    example_subject_type: hsdo_Institution
- description: hsdo_Models → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/2a65dfd1-83e7-4886-a732-316b170522a1
    example_object_type: hsdo_Location
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/553cf82e-b07f-48c7-b7ae-48809acde89c
    example_subject_type: hsdo_Models
- description: hsdo_Models → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/3ce7f4f0-d2db-4352-8762-d88296f7aa15
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/35d2677c-619a-4a47-a5a7-3feb9973c5ab
    example_subject_type: hsdo_Models
- description: hsdo_Models → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/8680cb49-1637-4a47-a5fd-f39d4e618e45
    example_object_type: hsdo_Model
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ea5ccefb-e390-43d5-8202-33e004565beb
    example_subject_type: hsdo_Models
- description: hsdo_Models → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/666b0926-b509-4680-b551-530d8aaca9ec
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
    example_subject_type: hsdo_Models
- description: hsdo_Instrument → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/bc90bc40-2a21-4a6f-9fb9-bf3ae5845157
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/fe2719de-c5c8-4ce6-8230-1d16c8155991
    example_subject_type: hsdo_Instrument
- description: hsdo_Platform → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/666b0926-b509-4680-b551-530d8aaca9ec
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/b1c1ea44-000a-4535-8e90-d8dd447371d4
    example_subject_type: hsdo_Platform
- description: hsdo_Experiment → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/59920ad4-85fb-4cee-ba56-f39bc5857a3d
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/38fb609b-2a10-4d4f-b2e8-7e51161ec974
    example_subject_type: hsdo_Experiment
- description: hsdo_Institution → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/6fb2817f-c3e3-4332-85ad-79f74227e6bc
    example_object_type: hsdo_Model
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d9fbd2ea-803e-48b7-a1f2-774e6845cc1f
    example_subject_type: hsdo_Institution
- description: hsdo_Institution → hsdo_Dataset
  object:
    example_object: https://climateKG.org/entity/f9ce1564-0144-43d2-a9dd-bc48edcefb37
    example_object_type: hsdo_Dataset
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/3be6270c-8554-467a-b2c7-9c13bc086b10
    example_subject_type: hsdo_Institution
- description: hsdo_Institution → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/70fb5a3b-35b1-4048-a8be-56a0d865281c
    example_object_type: hsdo_Location
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/3be6270c-8554-467a-b2c7-9c13bc086b10
    example_subject_type: hsdo_Institution
- description: hsdo_Institution → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/f88c4559-fc4b-4b4a-ac57-0f15bb24e8e0
    example_object_type: hsdo_Models
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/e8df7edd-a176-45c9-8515-3a520948ef63
    example_subject_type: hsdo_Institution
- description: hsdo_Instrument → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/c5b13fa4-0069-40ce-85cb-bfbab34c2058
    example_object_type: hsdo_Models
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ae02541a-4968-4573-8569-0f4a02575ab2
    example_subject_type: hsdo_Instrument
- description: hsdo_Instrument → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/eab3419f-a0c2-4d55-9500-87ee00600291
    example_object_type: hsdo_Project
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/fe37b7a7-b6ca-4880-8dcf-16973cd8ecc8
    example_subject_type: hsdo_Instrument
- description: hsdo_Project → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23
    example_object_type: hsdo_Provider
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/3970129f-8bb5-49bb-8517-1532f0a0f828
    example_subject_type: hsdo_Project
- description: hsdo_Institution → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_object_type: hsdo_Project
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/fea56568-3eb7-4527-a8bb-112d5d721e11
    example_subject_type: hsdo_Institution
- description: hsdo_Platform → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5
    example_object_type: hsdo_Platform
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/432d2336-1111-4305-a8cb-8d0c8a3af632
    example_subject_type: hsdo_Platform
- description: hsdo_Provider → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/59920ad4-85fb-4cee-ba56-f39bc5857a3d
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/efcb13d4-ce68-4d42-8cc5-932ac3ef6126
    example_subject_type: hsdo_Provider
- description: hsdo_Platform → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/d6aec072-daf9-4f96-b667-6c7831cf6bdd
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/b1c1ea44-000a-4535-8e90-d8dd447371d4
    example_subject_type: hsdo_Platform
- description: hsdo_Platform → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/d4c65f0d-f825-4040-8dd3-69b85979101a
    example_object_type: hsdo_Location
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f959e3c5-f014-40b7-a134-4d41b616f79d
    example_subject_type: hsdo_Platform
- description: hsdo_Platform → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/d9fbd2ea-803e-48b7-a1f2-774e6845cc1f
    example_object_type: hsdo_Institution
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/b1c1ea44-000a-4535-8e90-d8dd447371d4
    example_subject_type: hsdo_Platform
- description: hsdo_Platform → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/7583957b-e902-4daf-a2b9-81b65c3f3b8f
    example_object_type: hsdo_Model
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5
    example_subject_type: hsdo_Platform
- description: hsdo_Platform → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799
    example_object_type: hsdo_Project
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5
    example_subject_type: hsdo_Platform
- description: hsdo_Project → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/9221496b-49fb-4998-a932-a51e11bf6cd7
    example_object_type: hsdo_Activity
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Project → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Location → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799
    example_object_type: hsdo_Project
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f9837873-62cd-402c-af8b-571876942a83
    example_subject_type: hsdo_Location
- description: hsdo_Cmip6_Source_Id → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_object_type: hsdo_Project
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f083ae80-224b-4453-8a18-d1b13d9d2f90
    example_subject_type: hsdo_Cmip6_Source_Id
- description: hsdo_Experiment → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/da2c70fd-d92b-45be-b159-b2c10cb387c6
    example_object_type: hsdo_Platform
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/a956d045-3b12-441c-8a18-fac7d33b2b4e
    example_subject_type: hsdo_Experiment
- description: hsdo_Provider → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/13df63e8-85ad-405d-9b43-256371e259c0
    example_object_type: hsdo_Model
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/df0ab7d8-025d-496d-8d5e-991d208c81fa
    example_subject_type: hsdo_Provider
- description: hsdo_Location → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/3d7ecc4f-e79e-40d1-8796-63059888bf5f
    example_object_type: hsdo_Location
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/fa57b0a0-9723-4195-bdd1-4f26aefa0e07
    example_subject_type: hsdo_Location
- description: hsdo_Models → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/df0ab7d8-025d-496d-8d5e-991d208c81fa
    example_object_type: hsdo_Provider
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/b30ecade-ec88-4f0e-9482-532a2ceeb0d5
    example_subject_type: hsdo_Models
- description: hsdo_Model → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/10c24d93-c480-42fc-a438-4600e2d14a77
    example_object_type: hsdo_Platform
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/57441436-5372-484e-983c-f96cbc51ef72
    example_subject_type: hsdo_Model
- description: hsdo_Activity → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/378fef81-dd2e-4e80-9922-28cbf45d32dc
    example_object_type: hsdo_Models
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/5796ebd9-7dcb-4968-b876-1e678484cc62
    example_subject_type: hsdo_Activity
- description: hsdo_Activity → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/4315c66b-86e9-4127-a456-e549687012cf
    example_object_type: hsdo_Institution
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/5796ebd9-7dcb-4968-b876-1e678484cc62
    example_subject_type: hsdo_Activity
- description: hsdo_Activity → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/666b0926-b509-4680-b551-530d8aaca9ec
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58
    example_subject_type: hsdo_Activity
- description: hsdo_Activity → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/51233a6a-ba89-4a05-8692-0934edbadcba
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/7c5a2cb8-495a-4d32-b9ef-a54f43192712
    example_subject_type: hsdo_Activity
- description: hsdo_Provider → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/e236abe1-c8c5-4bca-ab7d-89b5a0392d6b
    example_subject_type: hsdo_Provider
- description: hsdo_Models → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/ef36cb15-ad64-4bdc-9331-42cc5b493671
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/fc94343c-1809-431f-b3da-8ba5b887dda9
    example_subject_type: hsdo_Models
- description: hsdo_Activity → hsdo_Project
  object:
    example_object: https://climateKG.org/entity/de76fdb4-9055-4cad-8422-3bae8870e799
    example_object_type: hsdo_Project
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/8f528b66-670d-4198-b014-7fdc9e1f6890
    example_subject_type: hsdo_Activity
- description: hsdo_Activity → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/68885007-d975-4f24-bdd5-dd19b246bdf6
    example_object_type: hsdo_Activity
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/68885007-d975-4f24-bdd5-dd19b246bdf6
    example_subject_type: hsdo_Activity
- description: hsdo_Location → hsdo_Data_Format
  object:
    example_object: https://climateKG.org/entity/d0b3505e-77bb-45a0-83fe-787bc3812b67
    example_object_type: hsdo_Data_Format
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/74d079b5-9b36-45c9-9b09-7e3646b65a85
    example_subject_type: hsdo_Location
- description: hsdo_Experiment → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/e49f0aae-c2ef-4fd2-aaf4-ddfad074bb75
    example_object_type: hsdo_Models
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
    example_subject_type: hsdo_Experiment
- description: hsdo_Project → hsdo_Variable
  object:
    example_object: https://climateKG.org/entity/b631f7b6-9a64-4f2b-bd29-7a20a466e44b
    example_object_type: hsdo_Variable
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/820f2f42-79e8-4ea5-be0b-b828766e11ad
    example_subject_type: hsdo_Project
- description: hsdo_Project → hsdo_Data_Format
  object:
    example_object: https://climateKG.org/entity/ac392872-1571-4bfd-94dd-81f93d9f1fd0
    example_object_type: hsdo_Data_Format
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/8289e024-54f7-4c63-a8ca-e7b1aef80be2
    example_subject_type: hsdo_Project
- description: hsdo_Experiment → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/d9fbd2ea-803e-48b7-a1f2-774e6845cc1f
    example_object_type: hsdo_Institution
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/8a106157-e0a0-4a3e-bed1-4ce3b8e06151
    example_subject_type: hsdo_Experiment
- description: hsdo_Model → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/a6212424-1146-4a79-a14c-8ce88543b08b
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d6141f58-40bf-4a59-9fc2-707528e53486
    example_subject_type: hsdo_Model
- description: hsdo_Experiment → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58
    example_object_type: hsdo_Model
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/c72fe5bf-6ec6-48bc-9888-257db1daf0af
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Dataset
  object:
    example_object: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
    example_object_type: hsdo_Dataset
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/878e70de-f929-4d2f-9325-145ca95787e9
    example_subject_type: hsdo_Experiment
- description: hsdo_Experiment → hsdo_Cmip6_Source_Id
  object:
    example_object: https://climateKG.org/entity/d0c16581-6951-4e8d-a0c1-97e9fcaa031a
    example_object_type: hsdo_Cmip6_Source_Id
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/910d9fdb-84fe-4f62-9172-41888cc181a4
    example_subject_type: hsdo_Experiment
- description: hsdo_Location → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/da2c70fd-d92b-45be-b159-b2c10cb387c6
    example_object_type: hsdo_Platform
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/9af548c9-7050-4d59-b66d-adf52f2fb242
    example_subject_type: hsdo_Location
- description: hsdo_Cmip6_Source_Id → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/8f528b66-670d-4198-b014-7fdc9e1f6890
    example_object_type: hsdo_Activity
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/df0ba39b-7461-4cee-8660-c80fee72e96b
    example_subject_type: hsdo_Cmip6_Source_Id
- description: hsdo_Dataset → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/25f8d5c2-1a32-4453-9421-65c5d9d3d114
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/a0b26420-3a13-4742-8d6f-391dc5c49d64
    example_subject_type: hsdo_Dataset
- description: hsdo_Data_Format → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/32f12730-2c26-43e7-a357-dee6ff4b1764
    example_object_type: hsdo_Provider
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/a2904083-1e32-4086-b028-a2afc2ffd443
    example_subject_type: hsdo_Data_Format
- description: hsdo_Cmip6_Source_Id → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/b62575f6-25e9-4a50-b0f6-a45dbf22c8d4
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/bff6b593-1884-4aea-87a1-36f606d3a020
    example_subject_type: hsdo_Cmip6_Source_Id
- description: hsdo_Provider → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5
    example_object_type: hsdo_Platform
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/c9003d36-020d-4e86-995a-498945576c23
    example_subject_type: hsdo_Provider
- description: hsdo_Data_Format → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5
    example_object_type: hsdo_Platform
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ac392872-1571-4bfd-94dd-81f93d9f1fd0
    example_subject_type: hsdo_Data_Format
- description: hsdo_Experiment → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/68057636-bb40-472f-86cd-9b5c01f3c3d0
    example_object_type: hsdo_Provider
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/b7eb8278-0dc3-4121-87ea-14173279dfb4
    example_subject_type: hsdo_Experiment
- description: hsdo_Platform → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/553cf82e-b07f-48c7-b7ae-48809acde89c
    example_object_type: hsdo_Models
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/b1c1ea44-000a-4535-8e90-d8dd447371d4
    example_subject_type: hsdo_Platform
- description: hsdo_Model → hsdo_Provider
  object:
    example_object: https://climateKG.org/entity/85510ccc-5dc9-44ff-871e-775e856714f8
    example_object_type: hsdo_Provider
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/b8a877b7-d867-4305-9053-3777e5dd330a
    example_subject_type: hsdo_Model
- description: hsdo_Models → hsdo_Measurement_Name
  object:
    example_object: https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
    example_object_type: hsdo_Measurement_Name
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/c5b13fa4-0069-40ce-85cb-bfbab34c2058
    example_subject_type: hsdo_Models
- description: hsdo_Data_Format → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/085edf65-1c8c-414a-b8e4-a1a08ff08f22
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d0b3505e-77bb-45a0-83fe-787bc3812b67
    example_subject_type: hsdo_Data_Format
- description: hsdo_Data_Format → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/74d079b5-9b36-45c9-9b09-7e3646b65a85
    example_object_type: hsdo_Location
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d0b3505e-77bb-45a0-83fe-787bc3812b67
    example_subject_type: hsdo_Data_Format
- description: hsdo_Model → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/4270e57b-0ed2-43ab-9a7a-cd09e3983691
    example_object_type: hsdo_Models
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58
    example_subject_type: hsdo_Model
- description: hsdo_Dataset → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5
    example_object_type: hsdo_Platform
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
    example_subject_type: hsdo_Dataset
- description: hsdo_Dataset → hsdo_Model
  object:
    example_object: https://climateKG.org/entity/8680cb49-1637-4a47-a5fd-f39d4e618e45
    example_object_type: hsdo_Model
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
    example_subject_type: hsdo_Dataset
- description: hsdo_Location → hsdo_Science_Keyword
  object:
    example_object: https://climateKG.org/entity/d2a5c7ec-ccf2-4ab7-8863-9063be91c022
    example_object_type: hsdo_Science_Keyword
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f36d71c6-f2ad-49c4-809f-09b4f0688412
    example_subject_type: hsdo_Location
- description: hsdo_Institution → hsdo_Instrument
  object:
    example_object: https://climateKG.org/entity/ac87227c-b943-400a-ac61-71e42e8eb5f3
    example_object_type: hsdo_Instrument
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/fea56568-3eb7-4527-a8bb-112d5d721e11
    example_subject_type: hsdo_Institution
- description: hsdo_Institution → hsdo_Platform
  object:
    example_object: https://climateKG.org/entity/45abac35-586f-4fed-ac38-5dcd59af2cc5
    example_object_type: hsdo_Platform
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/dd747113-048d-4ed1-aa70-23a7bf528077
    example_subject_type: hsdo_Institution
- description: hsdo_Project → hsdo_Institution
  object:
    example_object: https://climateKG.org/entity/3306fdd4-c844-4280-ac37-226d2272dcd4
    example_object_type: hsdo_Institution
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Project → hsdo_Models
  object:
    example_object: https://climateKG.org/entity/f88c4559-fc4b-4b4a-ac57-0f15bb24e8e0
    example_object_type: hsdo_Models
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
- description: hsdo_Instrument → hsdo_Variable
  object:
    example_object: https://climateKG.org/entity/d11237c8-639e-4725-bedf-0abbabfdc3ae
    example_object_type: hsdo_Variable
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ecbe9f17-6012-4e39-a707-713973b7d167
    example_subject_type: hsdo_Instrument
- description: hsdo_Data_Format → hsdo_Experiment
  object:
    example_object: https://climateKG.org/entity/41cd228c-4677-4900-9507-70144d8b50bc
    example_object_type: hsdo_Experiment
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ee016d07-002a-4c22-b05b-5ead6121ed3f
    example_subject_type: hsdo_Data_Format
- description: hsdo_Instrument → hsdo_Activity
  object:
    example_object: https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58
    example_object_type: hsdo_Activity
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/ee3e296f-fdc0-4695-95af-dbe63f43b679
    example_subject_type: hsdo_Instrument
- description: hsdo_Project → hsdo_Sub_Experiment_Id
  object:
    example_object: https://climateKG.org/entity/81165ebd-6b7a-44df-ac3a-b640e5d69bc4
    example_object_type: hsdo_Sub_Experiment_Id
    example_predicate: relation:ProvidedBy
    example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
    example_subject_type: hsdo_Project
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:ProvidedBy
alias: relation_ProvidedBy
domain_of:
- hsdo_Activity
- hsdo_Cmip6_Source_Id
- hsdo_Data_Format
- hsdo_Dataset
- hsdo_Experiment
- hsdo_Institution
- hsdo_Instrument
- hsdo_Location
- hsdo_Model
- hsdo_Models
- hsdo_Platform
- hsdo_Project
- hsdo_Provider
- hsdo_Science_Keyword
- hsdo_Variable
range: Any
any_of:
- range: hsdo_Science_Keyword
- range: hsdo_Measurement_Name
- range: hsdo_Variable
- range: hsdo_Models
- range: hsdo_Sub_Experiment_Id
- range: hsdo_Provider
- range: hsdo_Chronostratigraphic_Unit
- range: hsdo_Project
- range: hsdo_Model
- range: hsdo_Institution
- range: hsdo_Activity
- range: hsdo_Dataset
- range: hsdo_Data_Format
- range: hsdo_Instrument
- range: hsdo_Platform
- range: hsdo_Location
- range: hsdo_Cmip6_Source_Id
- range: hsdo_Experiment

```
</details>