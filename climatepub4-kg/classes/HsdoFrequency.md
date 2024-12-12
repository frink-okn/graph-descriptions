

# Class: TODO -- what's a good name for this class (type)? (hsdo_Frequency)


_No type description provided_





URI: [hsdo:Frequency](http://schema.org/Frequency)






```mermaid
 classDiagram
    class HsdoFrequency
    click HsdoFrequency href "../HsdoFrequency"
      HsdoFrequency : relation_MeasuredAt
        
          
    
    
    HsdoFrequency --> "0..1" Any : relation_MeasuredAt
    click Any href "../Any"

        
      HsdoFrequency : skos_broader
        
          
    
    
    HsdoFrequency --> "0..1" Any : skos_broader
    click Any href "../Any"

        
      HsdoFrequency : skos_definition
        
          
    
    
    HsdoFrequency --> "0..1" String : skos_definition
    click String href "../String"

        
      HsdoFrequency : skos_prefLabel
        
          
    
    
    HsdoFrequency --> "0..1" String : skos_prefLabel
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [skos_broader](../slots/skos_broader.md) | 0..1 <br/> [HsdoScienceKeyword](../classes/HsdoScienceKeyword.md)&nbsp;or&nbsp;<br />[HsdoModels](../classes/HsdoModels.md)&nbsp;or&nbsp;<br />[SkosConcept](../classes/SkosConcept.md)&nbsp;or&nbsp;<br />[HsdoDataFormat](../classes/HsdoDataFormat.md)&nbsp;or&nbsp;<br />[HsdoVariable](../classes/HsdoVariable.md)&nbsp;or&nbsp;<br />[HsdoDataset](../classes/HsdoDataset.md)&nbsp;or&nbsp;<br />[HsdoModel](../classes/HsdoModel.md)&nbsp;or&nbsp;<br />[HsdoChronostratigraphicUnit](../classes/HsdoChronostratigraphicUnit.md)&nbsp;or&nbsp;<br />[HsdoLocation](../classes/HsdoLocation.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)&nbsp;or&nbsp;<br />[HsdoTemporalResolutionRange](../classes/HsdoTemporalResolutionRange.md)&nbsp;or&nbsp;<br />[HsdoMeasurementName](../classes/HsdoMeasurementName.md)&nbsp;or&nbsp;<br />[HsdoPlatform](../classes/HsdoPlatform.md)&nbsp;or&nbsp;<br />[HsdoMimeType](../classes/HsdoMimeType.md)&nbsp;or&nbsp;<br />[HsdoRelatedUrlContentType](../classes/HsdoRelatedUrlContentType.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoProject](../classes/HsdoProject.md)&nbsp;or&nbsp;<br />[HsdoNominalResolution](../classes/HsdoNominalResolution.md)&nbsp;or&nbsp;<br />[HsdoSubExperimentId](../classes/HsdoSubExperimentId.md)&nbsp;or&nbsp;<br />[HsdoInstrument](../classes/HsdoInstrument.md)&nbsp;or&nbsp;<br />[HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md)&nbsp;or&nbsp;<br />[HsdoSourceType](../classes/HsdoSourceType.md) | No slot description provided | direct |
| [skos_prefLabel](../slots/skos_prefLabel.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [relation_MeasuredAt](../slots/relation_MeasuredAt.md) | 0..1 <br/> [HsdoScienceKeyword](../classes/HsdoScienceKeyword.md)&nbsp;or&nbsp;<br />[HsdoActivity](../classes/HsdoActivity.md)&nbsp;or&nbsp;<br />[HsdoModels](../classes/HsdoModels.md)&nbsp;or&nbsp;<br />[HsdoDataFormat](../classes/HsdoDataFormat.md)&nbsp;or&nbsp;<br />[HsdoVariable](../classes/HsdoVariable.md)&nbsp;or&nbsp;<br />[HsdoDataset](../classes/HsdoDataset.md)&nbsp;or&nbsp;<br />[HsdoModel](../classes/HsdoModel.md)&nbsp;or&nbsp;<br />[HsdoChronostratigraphicUnit](../classes/HsdoChronostratigraphicUnit.md)&nbsp;or&nbsp;<br />[HsdoLocation](../classes/HsdoLocation.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)&nbsp;or&nbsp;<br />[HsdoTemporalResolutionRange](../classes/HsdoTemporalResolutionRange.md)&nbsp;or&nbsp;<br />[HsdoMeasurementName](../classes/HsdoMeasurementName.md)&nbsp;or&nbsp;<br />[HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md)&nbsp;or&nbsp;<br />[HsdoPlatform](../classes/HsdoPlatform.md)&nbsp;or&nbsp;<br />[HsdoRelatedUrlContentType](../classes/HsdoRelatedUrlContentType.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoProject](../classes/HsdoProject.md)&nbsp;or&nbsp;<br />[HsdoSubExperimentId](../classes/HsdoSubExperimentId.md)&nbsp;or&nbsp;<br />[HsdoInstrument](../classes/HsdoInstrument.md) | No slot description provided | direct |
| [skos_definition](../slots/skos_definition.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HsdoActivity](../classes/HsdoActivity.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoChronostratigraphicUnit](../classes/HsdoChronostratigraphicUnit.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoDataFormat](../classes/HsdoDataFormat.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoDataset](../classes/HsdoDataset.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoExperiment](../classes/HsdoExperiment.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoInstitution](../classes/HsdoInstitution.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoInstrument](../classes/HsdoInstrument.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoLocation](../classes/HsdoLocation.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoMeasurementName](../classes/HsdoMeasurementName.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoModel](../classes/HsdoModel.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoModels](../classes/HsdoModels.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoPlatform](../classes/HsdoPlatform.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoProject](../classes/HsdoProject.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoProvider](../classes/HsdoProvider.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoRelatedUrlContentType](../classes/HsdoRelatedUrlContentType.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoScienceKeyword](../classes/HsdoScienceKeyword.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoSubExperimentId](../classes/HsdoSubExperimentId.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoTemporalResolutionRange](../classes/HsdoTemporalResolutionRange.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoVariable](../classes/HsdoVariable.md) | [relation_TargetsLocation](../slots/relation_TargetsLocation.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |
| [HsdoPaper](../classes/HsdoPaper.md) | [relation_Mention](../slots/relation_Mention.md) | any_of[range] | [HsdoFrequency](../classes/HsdoFrequency.md) |






## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:Frequency |
| native | climatepub4-kg/:HsdoFrequency |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: hsdo_Frequency
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 16 occurences.
from_schema: climatepub4-kg
rank: 1000
slots:
- skos_broader
- skos_prefLabel
- relation_MeasuredAt
- skos_definition
class_uri: hsdo:Frequency

```
</details>

### Induced

<details>
```yaml
name: hsdo_Frequency
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 16 occurences.
from_schema: climatepub4-kg
rank: 1000
attributes:
  skos_broader:
    name: skos_broader
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 2245 occurrences with subject type hsdo_Location and object type hsdo_Location.
    - 261 occurrences with subject type hsdo_Location and object type hsdo_Instrument.
    - 8109 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Science_Keyword.
    - 2953 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Provider.
    - 1937 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Location.
    - 312 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Model.
    - 1761 occurrences with subject type hsdo_Platform and object type hsdo_Instrument.
    - 2153 occurrences with subject type hsdo_Platform and object type hsdo_Platform.
    - 102 occurrences with subject type hsdo_Location and object type hsdo_Project.
    - 48 occurrences with subject type hsdo_Activity and object type hsdo_Project.
    - 40 occurrences with subject type hsdo_Model and object type hsdo_Instrument.
    - 34 occurrences with subject type hsdo_Model and object type hsdo_Platform.
    - 789 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type
      hsdo_Chronostratigraphic_Unit.
    - 47 occurrences with subject type hsdo_Experiment and object type hsdo_Project.
    - 8707 occurrences with subject type hsdo_Provider and object type hsdo_Provider.
    - 86 occurrences with subject type hsdo_Model and object type hsdo_Project.
    - 6114 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.
    - 2038 occurrences with subject type hsdo_Instrument and object type hsdo_Experiment.
    - 57 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.
    - 475 occurrences with subject type hsdo_Location and object type hsdo_Science_Keyword.
    - 311 occurrences with subject type hsdo_Location and object type hsdo_Provider.
    - 26 occurrences with subject type hsdo_Location and object type hsdo_Model.
    - 3416 occurrences with subject type hsdo_Project and object type hsdo_Project.
    - 4 occurrences with subject type hsdo_Realm and object type hsdo_Location.
    - 304 occurrences with subject type hsdo_Provider and object type hsdo_Location.
    - 180 occurrences with subject type hsdo_Instrument and object type hsdo_Project.
    - 891 occurrences with subject type hsdo_Models and object type hsdo_Science_Keyword.
    - 286 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Instrument.
    - 355 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
    - 131 occurrences with subject type hsdo_Model and object type hsdo_Science_Keyword.
    - 32 occurrences with subject type hsdo_Model and object type hsdo_Model.
    - 9 occurrences with subject type hsdo_Model and object type hsdo_Experiment.
    - 80 occurrences with subject type hsdo_Model and object type hsdo_Provider.
    - 317 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Instrument.
    - 20 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Location.
    - 75 occurrences with subject type hsdo_Institution and object type hsdo_Provider.
    - 38 occurrences with subject type hsdo_Model and object type hsdo_Location.
    - 12 occurrences with subject type hsdo_Instrument and object type hsdo_Variable.
    - 352 occurrences with subject type hsdo_Instrument and object type hsdo_Science_Keyword.
    - 160 occurrences with subject type hsdo_Instrument and object type hsdo_Provider.
    - 137 occurrences with subject type hsdo_Experiment and object type hsdo_Science_Keyword.
    - 31 occurrences with subject type hsdo_Experiment and object type hsdo_Location.
    - 54 occurrences with subject type hsdo_Sub_Experiment_Id and object type hsdo_Sub_Experiment_Id.
    - 227 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Measurement_Name.
    - 130 occurrences with subject type hsdo_Instrument and object type hsdo_Location.
    - 154 occurrences with subject type hsdo_Provider and object type hsdo_Science_Keyword.
    - 182 occurrences with subject type hsdo_Provider and object type hsdo_Model.
    - 183 occurrences with subject type hsdo_Provider and object type hsdo_Instrument.
    - 43 occurrences with subject type hsdo_Location and object type hsdo_Platform.
    - 242 occurrences with subject type hsdo_Data_Format and object type hsdo_Data_Format.
    - 63 occurrences with subject type hsdo_Location and object type hsdo_Experiment.
    - 1281 occurrences with subject type hsdo_Variable and object type hsdo_Variable.
    - 55 occurrences with subject type hsdo_Platform and object type hsdo_Science_Keyword.
    - 25 occurrences with subject type hsdo_Platform and object type hsdo_Location.
    - 33 occurrences with subject type hsdo_Platform and object type hsdo_Provider.
    - 84 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.
    - 27 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Project.
    - 22 occurrences with subject type hsdo_Provider and object type hsdo_Related_Url_Content_Type.
    - 402 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Science_Keyword.
    - 15 occurrences with subject type hsdo_Provider and object type hsdo_Sub_Experiment_Id.
    - 3 occurrences with subject type hsdo_Model and object type hsdo_Source_Type.
    - 58 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.
    - 6 occurrences with subject type hsdo_Experiment and object type hsdo_Platform.
    - 34 occurrences with subject type hsdo_Instrument and object type hsdo_Model.
    - 5 occurrences with subject type hsdo_Location and object type hsdo_Sub_Experiment_Id.
    - 220 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Experiment.
    - 42 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Platform.
    - 7 occurrences with subject type hsdo_Model and object type hsdo_Variable.
    - 13 occurrences with subject type hsdo_Provider and object type hsdo_Variable.
    - 4 occurrences with subject type hsdo_Provider and object type hsdo_Experiment.
    - 211 occurrences with subject type hsdo_Related_Url_Content_Type and object type
      hsdo_Related_Url_Content_Type.
    - 106 occurrences with subject type hsdo_Dataset and object type hsdo_Dataset.
    - 26 occurrences with subject type hsdo_Project and object type hsdo_Science_Keyword.
    - 4 occurrences with subject type hsdo_Project and object type hsdo_Location.
    - 15 occurrences with subject type hsdo_Project and object type hsdo_Provider.
    - 4 occurrences with subject type hsdo_Platform and object type hsdo_Experiment.
    - 7 occurrences with subject type hsdo_Location and object type hsdo_Related_Url_Content_Type.
    - 16 occurrences with subject type hsdo_Models and object type hsdo_Instrument.
    - 10 occurrences with subject type hsdo_Location and object type hsdo_Measurement_Name.
    - 1 occurrences with subject type hsdo_Provider and object type hsdo_Source_Type.
    - 14 occurrences with subject type hsdo_Instrument and object type hsdo_Related_Url_Content_Type.
    - 12 occurrences with subject type hsdo_Experiment and object type hsdo_Model.
    - 85 occurrences with subject type hsdo_Platform and object type hsdo_Model.
    - 18 occurrences with subject type hsdo_Temporal_Resolution_Range and object type
      hsdo_Temporal_Resolution_Range.
    - 4 occurrences with subject type hsdo_Project and object type hsdo_Model.
    - 17 occurrences with subject type hsdo_Platform and object type hsdo_Project.
    - 2 occurrences with subject type hsdo_Experiment and object type hsdo_Variable.
    - 3 occurrences with subject type hsdo_Provider and object type hsdo_Platform.
    - 12 occurrences with subject type hsdo_Location and object type hsdo_Variable.
    - 2 occurrences with subject type hsdo_Institution and object type hsdo_Location.
    - 4 occurrences with subject type hsdo_Source_Type and object type hsdo_Source_Type.
    - 15 occurrences with subject type hsdo_Nominal_Resolution and object type hsdo_Nominal_Resolution.
    - 3 occurrences with subject type hsdo_Experiment and object type hsdo_Source_Type.
    - 16 occurrences with subject type hsdo_Frequency and object type hsdo_Temporal_Resolution_Range.
    - 4 occurrences with subject type hsdo_License and object type hsdo_Instrument.
    - 1 occurrences with subject type hsdo_Instrument and object type hsdo_Models.
    - 3 occurrences with subject type hsdo_Location and object type hsdo_Source_Type.
    - 3 occurrences with subject type hsdo_Model and object type hsdo_Related_Url_Content_Type.
    - 24 occurrences with subject type hsdo_Related_Url_Content_Type and object type
      hsdo_Provider.
    - 1 occurrences with subject type hsdo_Project and object type hsdo_Experiment.
    - 1 occurrences with subject type hsdo_Project and object type hsdo_Variable.
    - 1 occurrences with subject type hsdo_Model and object type hsdo_Temporal_Resolution_Range.
    - 3 occurrences with subject type hsdo_Models and object type hsdo_Models.
    - 1 occurrences with subject type hsdo_Provider and object type hsdo_Project.
    - 2 occurrences with subject type hsdo_Experiment and object type hsdo_Measurement_Name.
    - 16338 occurrences with subject type skos_Concept and object type skos_Concept.
    - 37 occurrences with subject type hsdo_Mime_Type and object type hsdo_Mime_Type.
    - 14 occurrences with subject type hsdo_Horizontal_Resolution_Range and object
      type hsdo_Horizontal_Resolution_Range.
    - 6 occurrences with subject type hsdo_Vertical_Resolution_Range and object type
      hsdo_Variable.
    - 2 occurrences with subject type hsdo_Related_Url_Content_Type and object type
      hsdo_Instrument.
    examples:
    - value: https://climateKG.org/entity/ffcee960-5527-43e0-bfd0-ad48b1151cf0 skos:broader
        https://climateKG.org/entity/713eb469-abe4-4b6b-bad6-134187deabd8
    - value: https://climateKG.org/entity/fe4326f9-1089-4ede-ae32-5d7bc7d2349b skos:broader
        https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb
    - value: https://climateKG.org/entity/ffc61516-ea33-48f3-94df-7065fea388ee skos:broader
        https://climateKG.org/entity/d64a9627-3cf8-41d3-aaf7-8c2c46fb4a13
    - value: https://climateKG.org/entity/ffc61516-ea33-48f3-94df-7065fea388ee skos:broader
        https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
    - value: https://climateKG.org/entity/ff9f8056-84d6-4fbc-abe0-9b6e82ed3f5e skos:broader
        https://climateKG.org/entity/c47f6052-634e-40ef-a5ac-13f69f6f4c2a
    - value: https://climateKG.org/entity/fec6c2e4-ca15-426a-b344-36bba69e5c1f skos:broader
        https://climateKG.org/entity/6f6423e8-ab4e-4572-8982-d9c40f64e28b
    - value: https://climateKG.org/entity/ffc0ac45-f742-49b2-a51b-000205e38669 skos:broader
        https://climateKG.org/entity/f3261de5-34c1-4980-af22-f9d7e7206d12
    - value: https://climateKG.org/entity/ffc0ac45-f742-49b2-a51b-000205e38669 skos:broader
        https://climateKG.org/entity/ef71c514-0fec-4354-bb1e-6baa5967634f
    - value: https://climateKG.org/entity/fe439b0d-db2c-4998-9890-c11c5c16641f skos:broader
        https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    - value: https://climateKG.org/entity/d7144e27-6122-46e2-8335-b60c49a83248 skos:broader
        https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    - value: https://climateKG.org/entity/ff1ace7a-7924-4198-8385-f7f7ede361c1 skos:broader
        https://climateKG.org/entity/085edf65-1c8c-414a-b8e4-a1a08ff08f22
    - value: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66 skos:broader
        https://climateKG.org/entity/b39a69b4-c3b9-4a94-b296-bbbbe5e4c847
    - value: https://climateKG.org/entity/ff133a4b-a23a-4710-93d3-2b802b21c8c4 skos:broader
        https://climateKG.org/entity/b44427cd-4b20-42a3-9e14-8d1f6d8399d5
    - value: https://climateKG.org/entity/e25399d8-139f-4641-89ee-24d42e9ed81c skos:broader
        https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    - value: https://climateKG.org/entity/ffaea6a1-8b76-4e2e-a09f-a0280bc0952e skos:broader
        https://climateKG.org/entity/b301e170-c91e-4275-9858-d7720fb93416
    - value: https://climateKG.org/entity/fe761190-36bb-4eb1-8d5d-340c4a7f89ea skos:broader
        https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    - value: https://climateKG.org/entity/fff596a8-f792-4627-8c3a-954012a1969b skos:broader
        https://climateKG.org/entity/6c0e547e-70cc-47db-8c8c-97c5ba73f1da
    - value: https://climateKG.org/entity/fff596a8-f792-4627-8c3a-954012a1969b skos:broader
        https://climateKG.org/entity/b2140059-b3ca-415c-b0a7-3e142783ffe8
    - value: https://climateKG.org/entity/f5df87b6-ed50-4da0-9ba5-7ce4c907bdb3 skos:broader
        https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
    - value: https://climateKG.org/entity/ff5d5c12-74d9-435d-9164-1c9d69f967d7 skos:broader
        https://climateKG.org/entity/35e1f93b-99b3-4430-b477-0ecafa80d67a
    - value: https://climateKG.org/entity/ff5d5c12-74d9-435d-9164-1c9d69f967d7 skos:broader
        https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
    - value: https://climateKG.org/entity/f4c1a555-4758-47ce-baa6-536730333833 skos:broader
        https://climateKG.org/entity/23703b6b-ee15-4512-b5b2-f441547e2edf
    - value: https://climateKG.org/entity/ffcca1c5-fffd-4359-b282-e00fc77c979e skos:broader
        https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    - value: https://climateKG.org/entity/da44d8bd-4896-44c9-ab2b-4ab9ab263c65 skos:broader
        https://climateKG.org/entity/61cd0af2-2f62-4aa4-b6c3-f683e975c820
    - value: https://climateKG.org/entity/fed7e934-6a34-4379-9b57-ad6d49991498 skos:broader
        https://climateKG.org/entity/aef2fc80-def0-46a4-9259-9dc37e80ed08
    - value: https://climateKG.org/entity/ff25845a-5d94-43c1-abc4-419a108b0f1f skos:broader
        https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    - value: https://climateKG.org/entity/ff7d51fb-85cb-4350-8817-b4121cf72357 skos:broader
        https://climateKG.org/entity/e1f20631-b5b9-438c-b5c2-b1fa0fce100a
    - value: https://climateKG.org/entity/ff889b84-e12f-40ab-815b-61d5aecf2b63 skos:broader
        https://climateKG.org/entity/431eca76-9d34-4f86-b1d3-a0b40221e905
    - value: https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 skos:broader
        https://climateKG.org/entity/d69f7457-db31-48ce-b8c2-98058c412bc6
    - value: https://climateKG.org/entity/ff1ace7a-7924-4198-8385-f7f7ede361c1 skos:broader
        https://climateKG.org/entity/fb93d937-c17c-45d0-a9e3-ca5c8a800ca8
    - value: https://climateKG.org/entity/f8845bec-c628-4185-aac1-4af22481c024 skos:broader
        https://climateKG.org/entity/8eb84f36-f355-458b-889f-b37cfa120654
    - value: https://climateKG.org/entity/e5b724af-b661-406a-ae1f-7cd2730c0576 skos:broader
        https://climateKG.org/entity/a956d045-3b12-441c-8a18-fac7d33b2b4e
    - value: https://climateKG.org/entity/ff1ace7a-7924-4198-8385-f7f7ede361c1 skos:broader
        https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
    - value: https://climateKG.org/entity/ffcda4b1-0956-4413-a4c9-8d72b5dffb58 skos:broader
        https://climateKG.org/entity/e384382c-fb2a-43ea-b064-610e6d4807e9
    - value: https://climateKG.org/entity/fcb181b4-4732-4752-b70d-bbcc81fcdc59 skos:broader
        https://climateKG.org/entity/369c608c-787a-4ca6-8811-cc8eca7447d5
    - value: https://climateKG.org/entity/bf904092-467c-468e-99da-8722f9141204 skos:broader
        https://climateKG.org/entity/a158f804-b000-4013-9513-cee7790381c3
    - value: https://climateKG.org/entity/f8845bec-c628-4185-aac1-4af22481c024 skos:broader
        https://climateKG.org/entity/91c64c46-d040-4daa-b26c-61952fdfaf50
    - value: https://climateKG.org/entity/b3416c55-cdff-4e8b-89af-a9b219a9e538 skos:broader
        https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
    - value: https://climateKG.org/entity/fe4392b0-13a9-43ff-bacc-f44a65aed4fa skos:broader
        https://climateKG.org/entity/e1f20631-b5b9-438c-b5c2-b1fa0fce100a
    - value: https://climateKG.org/entity/fe06f678-7155-4f93-9e28-4c083d60cccc skos:broader
        https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
    - value: https://climateKG.org/entity/f5df87b6-ed50-4da0-9ba5-7ce4c907bdb3 skos:broader
        https://climateKG.org/entity/b6fd22ab-dca7-4dfa-8812-913453b5695b
    - value: https://climateKG.org/entity/f5df87b6-ed50-4da0-9ba5-7ce4c907bdb3 skos:broader
        https://climateKG.org/entity/91697b7d-8f2b-4954-850e-61d5f61c867d
    - value: https://climateKG.org/entity/fc01908a-f93e-46e6-9f85-5b428b8d2b8d skos:broader
        https://climateKG.org/entity/2eecd388-25be-4367-90c6-0d683ef476ac
    - value: https://climateKG.org/entity/ffcda4b1-0956-4413-a4c9-8d72b5dffb58 skos:broader
        https://climateKG.org/entity/1f697c83-969d-48ee-87b8-245b11f7e24f
    - value: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb skos:broader
        https://climateKG.org/entity/713eb469-abe4-4b6b-bad6-134187deabd8
    - value: https://climateKG.org/entity/ff850d62-675c-4386-a375-fe4af92ec3ff skos:broader
        https://climateKG.org/entity/d35b9ba5-d018-48a5-8f0d-92b9c55b3279
    - value: https://climateKG.org/entity/ff2f2855-6cdd-4bf0-a4ea-5aa61698d765 skos:broader
        https://climateKG.org/entity/5fea4160-25a7-44b5-bfba-ef140fdffaf4
    - value: https://climateKG.org/entity/feab952c-49ca-41c1-a2a0-b35bf4dd7048 skos:broader
        https://climateKG.org/entity/5527d704-a0fe-45ab-99f9-90fa64f4af7f
    - value: https://climateKG.org/entity/f62c196b-8ec3-40e8-a824-6849e5a496f2 skos:broader
        https://climateKG.org/entity/b39a69b4-c3b9-4a94-b296-bbbbe5e4c847
    - value: https://climateKG.org/entity/fd79ac2d-c42e-4f3d-9aa1-d5ae94d4d2e3 skos:broader
        https://climateKG.org/entity/bb6184eb-1ced-44fb-9668-d57cf1baa2e3
    - value: https://climateKG.org/entity/fbe91a4f-4d27-4cfe-ba1b-69a62e359a3d skos:broader
        https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
    - value: https://climateKG.org/entity/ffb483cf-a660-4ec1-b470-304efce6005d skos:broader
        https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
    - value: https://climateKG.org/entity/fee25cad-7ffe-4ee2-a6f2-8116b8a0a707 skos:broader
        https://climateKG.org/entity/fb93d937-c17c-45d0-a9e3-ca5c8a800ca8
    - value: https://climateKG.org/entity/f9846838-fdbc-4aa0-86e9-b0e70e97d0e2 skos:broader
        https://climateKG.org/entity/d62db12c-fdcf-40ec-a714-4fb7c615aebe
    - value: https://climateKG.org/entity/fee25cad-7ffe-4ee2-a6f2-8116b8a0a707 skos:broader
        https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
    - value: https://climateKG.org/entity/fbcd0c2b-f8ac-4199-9a37-5e7a39150730 skos:broader
        https://climateKG.org/entity/267606d3-4918-4651-b40d-be12b09dd2fe
    - value: https://climateKG.org/entity/fd19a3f1-8eeb-49ab-bcaf-e7b4b267d415 skos:broader
        https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
    - value: https://climateKG.org/entity/d1996d91-e824-4b24-b94e-3aae4543b63b skos:broader
        https://climateKG.org/entity/894edd57-afb3-4bb3-878f-fc245d8b6e82
    - value: https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 skos:broader
        https://climateKG.org/entity/e1f20631-b5b9-438c-b5c2-b1fa0fce100a
    - value: https://climateKG.org/entity/dcbcdf6d-f4d7-4040-b7a5-07c46587b4bc skos:broader
        https://climateKG.org/entity/2eecd388-25be-4367-90c6-0d683ef476ac
    - value: https://climateKG.org/entity/bae77e96-ede8-44ab-8035-31feb2527fad skos:broader
        https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d skos:broader
        https://climateKG.org/entity/2bc6e372-93d8-4672-96b1-ec159aff2e19
    - value: https://climateKG.org/entity/f80b13a8-7692-4d1a-be08-851544cd0cde skos:broader
        https://climateKG.org/entity/e8baa3a4-ef5a-455a-bf25-d61e59fc9bb3
    - value: https://climateKG.org/entity/fe06f678-7155-4f93-9e28-4c083d60cccc skos:broader
        https://climateKG.org/entity/23703b6b-ee15-4512-b5b2-f441547e2edf
    - value: https://climateKG.org/entity/c129a8c2-b9d5-4405-914f-a6949a8e7b5a skos:broader
        https://climateKG.org/entity/2eecd388-25be-4367-90c6-0d683ef476ac
    - value: https://climateKG.org/entity/fed291ec-8f7d-4131-a5cd-dc04706f61b0 skos:broader
        https://climateKG.org/entity/c7245882-84a1-4192-acfa-a758b5b9c151
    - value: https://climateKG.org/entity/f2295f39-e8c5-4032-8a05-618d95410b28 skos:broader
        https://climateKG.org/entity/cc9e67fc-eafa-43cc-879f-0cb56b25bc39
    - value: https://climateKG.org/entity/f860ed88-991f-4b52-90b9-fc8d4046a598 skos:broader
        https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
    - value: https://climateKG.org/entity/fe950f88-6d5e-4741-8076-3fbe16b0b9c4 skos:broader
        https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
    - value: https://climateKG.org/entity/e91ff41a-5cf5-460b-b765-c553ca2a4ae2 skos:broader
        https://climateKG.org/entity/bd1834b0-4f8f-4616-b330-6205bff567c2
    - value: https://climateKG.org/entity/fd01f7ec-fdf6-4440-b974-75f12fb4ec5f skos:broader
        https://climateKG.org/entity/894edd57-afb3-4bb3-878f-fc245d8b6e82
    - value: https://climateKG.org/entity/fe64cea2-19de-470c-a919-b24c744c696b skos:broader
        https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
    - value: https://climateKG.org/entity/f69374fe-eda2-4223-b130-096220251235 skos:broader
        https://climateKG.org/entity/fb93d937-c17c-45d0-a9e3-ca5c8a800ca8
    - value: https://climateKG.org/entity/7cacbfdf-71a3-4fac-b690-9aa54e4060dd skos:broader
        https://climateKG.org/entity/c47f6052-634e-40ef-a5ac-13f69f6f4c2a
    - value: https://climateKG.org/entity/f69374fe-eda2-4223-b130-096220251235 skos:broader
        https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
    - value: https://climateKG.org/entity/d609fc5c-8267-4e79-84ec-93629d52aba8 skos:broader
        https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
    - value: https://climateKG.org/entity/e5803df8-c802-4f3f-96f5-53e534835887 skos:broader
        https://climateKG.org/entity/8759ab63-ac04-4136-bc25-0c00eece1096
    - value: https://climateKG.org/entity/fdd890fa-377a-46ce-8fdc-2d7d16a461b7 skos:broader
        https://climateKG.org/entity/fe4392b0-13a9-43ff-bacc-f44a65aed4fa
    - value: https://climateKG.org/entity/fb3ca6d5-ab16-413b-80f6-c2e2d50ec4c0 skos:broader
        https://climateKG.org/entity/67cc1cc2-04b9-4763-8e73-fb028f45baab
    - value: https://climateKG.org/entity/3b16a2e8-cc4d-40ce-a6c8-336bea211078 skos:broader
        https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b
    - value: https://climateKG.org/entity/fcc9411c-a1c9-415d-a16c-75c42f2cec45 skos:broader
        https://climateKG.org/entity/894edd57-afb3-4bb3-878f-fc245d8b6e82
    - value: https://climateKG.org/entity/eaa0bc43-e283-4bf1-ba20-ca32850a66ef skos:broader
        https://climateKG.org/entity/23703b6b-ee15-4512-b5b2-f441547e2edf
    - value: https://climateKG.org/entity/fe979e09-fcb1-4991-8fab-8ff32a28e84b skos:broader
        https://climateKG.org/entity/0a184cdc-c074-4946-90a6-02f03c686341
    - value: https://climateKG.org/entity/f86e464a-cf9d-4e15-a39b-501855d1dc5a skos:broader
        https://climateKG.org/entity/502ad03c-dba8-4b32-8af5-13fa947c3988
    - value: https://climateKG.org/entity/be7f6de0-f51e-42bc-9a66-fff30d809a67 skos:broader
        https://climateKG.org/entity/22ec2f9b-1f1a-469b-bc09-851d58637ff4
    - value: https://climateKG.org/entity/db7e4e2a-f55a-4515-bdd9-c5bc48e3c6d9 skos:broader
        https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
    - value: https://climateKG.org/entity/d4b91aac-8ca8-44e8-8854-ceae0cf3bc4e skos:broader
        https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
    - value: https://climateKG.org/entity/ab7eb13f-5fcb-4afa-8819-c37d36feeec1 skos:broader
        https://climateKG.org/entity/0a454dc9-de56-4682-8688-36ffd547d42f
    - value: https://climateKG.org/entity/f90ae98a-cdfb-490a-ba47-0186d69b4f8c skos:broader
        https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
    - value: https://climateKG.org/entity/7cf22186-281a-4665-b79b-5a6e5ea5b471 skos:broader
        https://climateKG.org/entity/aef2fc80-def0-46a4-9259-9dc37e80ed08
    - value: https://climateKG.org/entity/ff7b2b19-a8f6-4e84-a2c7-f2256199e13c skos:broader
        https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b
    - value: https://climateKG.org/entity/ef23b094-00f7-4ad3-8a9c-fa4ab8666c12 skos:broader
        https://climateKG.org/entity/c059a189-5d19-42f1-8a3a-1d0154da17dd
    - value: https://climateKG.org/entity/cd77430e-8e10-4581-b36e-e2db1124c34f skos:broader
        https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b
    - value: https://climateKG.org/entity/fb3ad06c-6a16-494b-a539-87da59e25c54 skos:broader
        https://climateKG.org/entity/502ad03c-dba8-4b32-8af5-13fa947c3988
    - value: https://climateKG.org/entity/9e36c429-c63a-48d8-8e94-caab8195f034 skos:broader
        https://climateKG.org/entity/3c937799-5ee5-4ea3-b7d5-418a625a7872
    - value: https://climateKG.org/entity/a68048f4-181c-4c6c-9bfa-9e4171e9f237 skos:broader
        https://climateKG.org/entity/35d2677c-619a-4a47-a5a7-3feb9973c5ab
    - value: https://climateKG.org/entity/e8c6761b-0653-495c-82e9-feb685344542 skos:broader
        https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b
    - value: https://climateKG.org/entity/ab2fce71-e5f9-4ba6-bfb1-bc428a8b7dd8 skos:broader
        https://climateKG.org/entity/894edd57-afb3-4bb3-878f-fc245d8b6e82
    - value: https://climateKG.org/entity/da43d7e4-4cb4-4b65-a9a1-94bf542f96de skos:broader
        https://climateKG.org/entity/750f6c61-0f15-4185-94d8-c029dec04bc5
    - value: https://climateKG.org/entity/be7f6de0-f51e-42bc-9a66-fff30d809a67 skos:broader
        https://climateKG.org/entity/a956d045-3b12-441c-8a18-fac7d33b2b4e
    - value: https://climateKG.org/entity/c819d2c9-fb81-4ce5-9737-ae8ea19690a2 skos:broader
        https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
    - value: https://climateKG.org/entity/e0040d4b-e398-4b65-bd42-d39434b5cc95 skos:broader
        https://climateKG.org/entity/502ad03c-dba8-4b32-8af5-13fa947c3988
    - value: https://climateKG.org/entity/3165b02f-962f-48bf-944b-66dd470f5988 skos:broader
        https://climateKG.org/entity/8cf3a3ce-4dd4-4364-8414-83e3b01354ec
    - value: https://climateKG.org/entity/f634ab55-de40-4d0b-93bc-691bf5408ccb skos:broader
        https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d skos:broader
        https://climateKG.org/entity/5b2a974e-0461-4eb1-86bd-807a29dccfc9
    - value: https://gcmd.earthdata.nasa.gov/kms/concept/ffff565f-15e9-4d15-a840-05c1a44fd2bf
        skos:broader https://gcmd.earthdata.nasa.gov/kms/concept/a31c2828-9b6d-44e9-b6ad-7ae81030f322
    - value: https://climateKG.org/entity/fea4e0a7-d794-481d-9915-52f1be226714 skos:broader
        https://climateKG.org/entity/ec1a1350-be24-42e6-a5cc-ccb806793def
    - value: https://climateKG.org/entity/e5c4876e-47b7-4d53-90a2-081a6b150140 skos:broader
        https://climateKG.org/entity/1499785c-8b74-45f4-bbf7-19d2d4e43b2f
    - value: https://climateKG.org/entity/eccf8700-c503-46a3-b6f7-86cf7e48465a skos:broader
        https://climateKG.org/entity/9728ca44-7bb3-40a4-9dd2-49470ad47fa5
    - value: https://climateKG.org/entity/f02b0c6a-7fd9-473d-a1cb-a6482e8daa61 skos:broader
        https://climateKG.org/entity/3c9d4493-22fd-48a8-9af5-bf0d16b7ede5
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: skos:broader
    alias: skos_broader
    owner: hsdo_Frequency
    domain_of:
    - hsdo_Activity
    - hsdo_Chronostratigraphic_Unit
    - hsdo_Cmip6_Source_Id
    - hsdo_Data_Format
    - hsdo_Dataset
    - hsdo_Experiment
    - hsdo_Frequency
    - hsdo_Horizontal_Resolution_Range
    - hsdo_Institution
    - hsdo_Instrument
    - hsdo_License
    - hsdo_Location
    - hsdo_Measurement_Name
    - hsdo_Mime_Type
    - hsdo_Model
    - hsdo_Models
    - hsdo_Nominal_Resolution
    - hsdo_Platform
    - hsdo_Project
    - hsdo_Provider
    - hsdo_Realm
    - hsdo_Related_Url_Content_Type
    - hsdo_Science_Keyword
    - hsdo_Source_Type
    - hsdo_Sub_Experiment_Id
    - hsdo_Temporal_Resolution_Range
    - hsdo_Variable
    - hsdo_Vertical_Resolution_Range
    - skos_Concept
    range: Any
    any_of:
    - range: hsdo_Science_Keyword
    - range: hsdo_Models
    - range: skos_Concept
    - range: hsdo_Data_Format
    - range: hsdo_Variable
    - range: hsdo_Dataset
    - range: hsdo_Model
    - range: hsdo_Chronostratigraphic_Unit
    - range: hsdo_Location
    - range: hsdo_Experiment
    - range: hsdo_Temporal_Resolution_Range
    - range: hsdo_Measurement_Name
    - range: hsdo_Platform
    - range: hsdo_Mime_Type
    - range: hsdo_Related_Url_Content_Type
    - range: hsdo_Provider
    - range: hsdo_Project
    - range: hsdo_Nominal_Resolution
    - range: hsdo_Sub_Experiment_Id
    - range: hsdo_Instrument
    - range: hsdo_Horizontal_Resolution_Range
    - range: hsdo_Source_Type
  skos_prefLabel:
    name: skos_prefLabel
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 983 occurrences with subject type hsdo_Location and object type string.
    - 2975 occurrences with subject type hsdo_Science_Keyword and object type string.
    - 1171 occurrences with subject type hsdo_Platform and object type string.
    - 24 occurrences with subject type hsdo_Activity and object type string.
    - 150 occurrences with subject type hsdo_Model and object type string.
    - 184 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type
      string.
    - 444 occurrences with subject type hsdo_Experiment and object type string.
    - 3745 occurrences with subject type hsdo_Provider and object type string.
    - 2363 occurrences with subject type hsdo_Instrument and object type string.
    - 1727 occurrences with subject type hsdo_Project and object type string.
    - 4 occurrences with subject type hsdo_Realm and object type string.
    - 297 occurrences with subject type hsdo_Models and object type string.
    - 234 occurrences with subject type hsdo_Measurement_Name and object type string.
    - 75 occurrences with subject type hsdo_Institution and object type string.
    - 55 occurrences with subject type hsdo_Sub_Experiment_Id and object type string.
    - 198 occurrences with subject type hsdo_Data_Format and object type string.
    - 1283 occurrences with subject type hsdo_Variable and object type string.
    - 134 occurrences with subject type hsdo_Cmip6_Source_Id and object type string.
    - 15 occurrences with subject type hsdo_Horizontal_Resolution_Range and object
      type string.
    - 5 occurrences with subject type hsdo_Source_Type and object type string.
    - 88 occurrences with subject type hsdo_Related_Url_Content_Type and object type
      string.
    - 107 occurrences with subject type hsdo_Dataset and object type string.
    - 19 occurrences with subject type hsdo_Temporal_Resolution_Range and object type
      string.
    - 16 occurrences with subject type hsdo_Nominal_Resolution and object type string.
    - 16 occurrences with subject type hsdo_Frequency and object type string.
    - 4 occurrences with subject type hsdo_License and object type string.
    - 38 occurrences with subject type hsdo_Mime_Type and object type string.
    - 16359 occurrences with subject type skos_Concept and object type string.
    - 6 occurrences with subject type hsdo_Vertical_Resolution_Range and object type
      string.
    examples:
    - value: https://climateKG.org/entity/0006e246-4296-448c-9b81-a0831cad7f1c skos:prefLabel
        LABRADOR_SEA
    - value: https://climateKG.org/entity/001f18d3-7e61-430b-9883-1960c6256fe5 skos:prefLabel
        OPTICAL_DEPTH
    - value: https://climateKG.org/entity/007c3084-89db-458e-8387-14e192b6cb8e skos:prefLabel
        Sentinel_1
    - value: https://climateKG.org/entity/00a97d0c-e05e-43c9-93d0-3c7a2527b3c0 skos:prefLabel
        SIMIP
    - value: https://climateKG.org/entity/00bb59aa-755d-4710-a097-f1e2836f4032 skos:prefLabel
        RCM_3
    - value: https://climateKG.org/entity/00c6f0f3-5734-4500-a69e-f6780e365985 skos:prefLabel
        EARLY
    - value: https://climateKG.org/entity/00ce4800-70ef-4346-aa15-0554280d0896 skos:prefLabel
        HAB
    - value: https://climateKG.org/entity/0111fbd3-e6ec-464a-bc65-2323c2328e7c skos:prefLabel
        DOI
    - value: https://climateKG.org/entity/01407ecf-45af-4fcc-8a1b-9b383636e2e4 skos:prefLabel
        HYDRA
    - value: https://climateKG.org/entity/01e75216-1cee-4cc3-b31d-83019730da85 skos:prefLabel
        USNPS_ENVIRONMENTAL_CHANGE_IN_BERINGIAN_ARCTIC
    - value: https://climateKG.org/entity/021d2b85-4728-4434-b429-082874cfab69 skos:prefLabel
        ocnBgchem
    - value: https://climateKG.org/entity/028fe075-8ed0-47f0-b462-71e4adf72a4e skos:prefLabel
        HadGEM2_ES
    - value: https://climateKG.org/entity/038ac74c-470a-43e0-b80d-2b2fb1acfc13 skos:prefLabel
        ambient_aerosol_particles
    - value: https://climateKG.org/entity/03976e48-3ff9-4dc6-a4c4-fd77026380ff skos:prefLabel
        E3SM_Project
    - value: https://climateKG.org/entity/04e00ed0-39b6-4323-a788-2344264695c0 skos:prefLabel
        s2016
    - value: https://climateKG.org/entity/0679d78d-0931-4948-94ec-46ab130785a6 skos:prefLabel
        ICI
    - value: https://climateKG.org/entity/0893353d-4e8c-4b31-bcc5-fce552ccfff3 skos:prefLabel
        Point_Resolution
    - value: https://climateKG.org/entity/0cd4d2c4-ebfa-4759-b7aa-f9982122f581 skos:prefLabel
        IPSL_CM5A2_INCA
    - value: https://climateKG.org/entity/1499785c-8b74-45f4-bbf7-19d2d4e43b2f skos:prefLabel
        Horizontal_Resolution_Ranges
    - value: https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b skos:prefLabel
        Source_Type
    - value: https://climateKG.org/entity/2892b502-2c66-42d5-af3d-bcddb57d9195 skos:prefLabel
        GET_CAPABILITIES
    - value: https://climateKG.org/entity/2892e23f-5249-439d-8c0e-6c1d190b3beb skos:prefLabel
        ERA_5
    - value: https://climateKG.org/entity/3d97e993-dc6a-41ff-8a49-3e837c1fc2b1 skos:prefLabel
        Decadal
    - value: https://climateKG.org/entity/82a2971f-82eb-46aa-8d70-1343570edba8 skos:prefLabel
        10000_km
    - value: https://climateKG.org/entity/8e4900ff-c7bc-47a1-aa55-a8892696d769 skos:prefLabel
        day
    - value: https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428 skos:prefLabel
        CC_BY_4_0
    - value: https://climateKG.org/entity/ec1a1350-be24-42e6-a5cc-ccb806793def skos:prefLabel
        Mime_Type
    - value: https://gcmd.earthdata.nasa.gov/kms/concept/0006e246-4296-448c-9b81-a0831cad7f1c
        skos:prefLabel LABRADOR_SEA
    - value: https://climateKG.org/entity/201337ea-fa14-4e58-a538-e92c5ff734a4 skos:prefLabel
        1_meter_10_meters
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: skos:prefLabel
    alias: skos_prefLabel
    owner: hsdo_Frequency
    domain_of:
    - hsdo_Activity
    - hsdo_Chronostratigraphic_Unit
    - hsdo_Cmip6_Source_Id
    - hsdo_Data_Format
    - hsdo_Dataset
    - hsdo_Experiment
    - hsdo_Frequency
    - hsdo_Horizontal_Resolution_Range
    - hsdo_Institution
    - hsdo_Instrument
    - hsdo_License
    - hsdo_Location
    - hsdo_Measurement_Name
    - hsdo_Mime_Type
    - hsdo_Model
    - hsdo_Models
    - hsdo_Nominal_Resolution
    - hsdo_Platform
    - hsdo_Project
    - hsdo_Provider
    - hsdo_Realm
    - hsdo_Related_Url_Content_Type
    - hsdo_Science_Keyword
    - hsdo_Source_Type
    - hsdo_Sub_Experiment_Id
    - hsdo_Temporal_Resolution_Range
    - hsdo_Variable
    - hsdo_Vertical_Resolution_Range
    - skos_Concept
    range: string
  relation_MeasuredAt:
    name: relation_MeasuredAt
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 542 occurrences with subject type hsdo_Location and object type hsdo_Location.
    - 71 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Science_Keyword.
    - 150 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Instrument.
    - 240 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Location.
    - 76 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Experiment.
    - 10 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Platform.
    - 43 occurrences with subject type hsdo_Experiment and object type hsdo_Science_Keyword.
    - 128 occurrences with subject type hsdo_Experiment and object type hsdo_Location.
    - 73 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.
    - 49 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.
    - 9 occurrences with subject type hsdo_Experiment and object type hsdo_Model.
    - 108 occurrences with subject type hsdo_Location and object type hsdo_Experiment.
    - 44 occurrences with subject type hsdo_Project and object type hsdo_Location.
    - 20 occurrences with subject type hsdo_Project and object type hsdo_Experiment.
    - 349 occurrences with subject type hsdo_Instrument and object type hsdo_Location.
    - 10 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Provider.
    - 4 occurrences with subject type hsdo_Project and object type hsdo_Project.
    - 15 occurrences with subject type hsdo_Model and object type hsdo_Science_Keyword.
    - 41 occurrences with subject type hsdo_Model and object type hsdo_Location.
    - 15 occurrences with subject type hsdo_Model and object type hsdo_Experiment.
    - 27 occurrences with subject type hsdo_Model and object type hsdo_Instrument.
    - 178 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.
    - 14 occurrences with subject type hsdo_Instrument and object type hsdo_Model.
    - 15 occurrences with subject type hsdo_Location and object type hsdo_Measurement_Name.
    - 223 occurrences with subject type hsdo_Location and object type hsdo_Instrument.
    - 64 occurrences with subject type hsdo_Location and object type hsdo_Science_Keyword.
    - 9 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.
    - 17 occurrences with subject type hsdo_Instrument and object type hsdo_Provider.
    - 15 occurrences with subject type hsdo_Instrument and object type hsdo_Measurement_Name.
    - 91 occurrences with subject type hsdo_Instrument and object type hsdo_Experiment.
    - 5 occurrences with subject type hsdo_Project and object type hsdo_Model.
    - 16 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Model.
    - 93 occurrences with subject type hsdo_Instrument and object type hsdo_Science_Keyword.
    - 2 occurrences with subject type hsdo_Models and object type hsdo_Chronostratigraphic_Unit.
    - 8 occurrences with subject type hsdo_Models and object type hsdo_Instrument.
    - 1 occurrences with subject type hsdo_Models and object type hsdo_Project.
    - 13 occurrences with subject type hsdo_Project and object type hsdo_Science_Keyword.
    - 1 occurrences with subject type hsdo_Experiment and object type hsdo_Activity.
    - 10 occurrences with subject type hsdo_Location and object type hsdo_Data_Format.
    - 61 occurrences with subject type hsdo_Provider and object type hsdo_Location.
    - 11 occurrences with subject type hsdo_Instrument and object type hsdo_Project.
    - 2 occurrences with subject type hsdo_Instrument and object type hsdo_Data_Format.
    - 27 occurrences with subject type hsdo_Variable and object type hsdo_Instrument.
    - 7 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Chronostratigraphic_Unit.
    - 11 occurrences with subject type hsdo_Location and object type hsdo_Chronostratigraphic_Unit.
    - 32 occurrences with subject type hsdo_Location and object type hsdo_Provider.
    - 7 occurrences with subject type hsdo_Variable and object type hsdo_Model.
    - 5 occurrences with subject type hsdo_Platform and object type hsdo_Science_Keyword.
    - 30 occurrences with subject type hsdo_Platform and object type hsdo_Location.
    - 21 occurrences with subject type hsdo_Platform and object type hsdo_Instrument.
    - 12 occurrences with subject type hsdo_Platform and object type hsdo_Experiment.
    - 17 occurrences with subject type hsdo_Provider and object type hsdo_Experiment.
    - 29 occurrences with subject type hsdo_Provider and object type hsdo_Instrument.
    - 7 occurrences with subject type hsdo_Location and object type hsdo_Platform.
    - 13 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Project.
    - 17 occurrences with subject type hsdo_Location and object type hsdo_Variable.
    - 3 occurrences with subject type hsdo_Model and object type hsdo_Model.
    - 2 occurrences with subject type hsdo_Data_Format and object type hsdo_Experiment.
    - 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Chronostratigraphic_Unit.
    - 5 occurrences with subject type hsdo_Data_Format and object type hsdo_Instrument.
    - 9 occurrences with subject type hsdo_Experiment and object type hsdo_Variable.
    - 16 occurrences with subject type hsdo_Location and object type hsdo_Project.
    - 20 occurrences with subject type hsdo_Location and object type hsdo_Model.
    - 1 occurrences with subject type hsdo_Horizontal_Resolution_Range and object
      type hsdo_Location.
    - 5 occurrences with subject type hsdo_Variable and object type hsdo_Models.
    - 12 occurrences with subject type hsdo_Variable and object type hsdo_Experiment.
    - 6 occurrences with subject type hsdo_Experiment and object type hsdo_Project.
    - 12 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.
    - 27 occurrences with subject type hsdo_Project and object type hsdo_Instrument.
    - 23 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Location.
    - 4 occurrences with subject type hsdo_Model and object type hsdo_Variable.
    - 1 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Data_Format.
    - 7 occurrences with subject type hsdo_Instrument and object type hsdo_Chronostratigraphic_Unit.
    - 23 occurrences with subject type hsdo_Location and object type hsdo_Models.
    - 6 occurrences with subject type hsdo_Models and object type hsdo_Variable.
    - 36 occurrences with subject type hsdo_Variable and object type hsdo_Location.
    - 5 occurrences with subject type hsdo_Variable and object type hsdo_Science_Keyword.
    - 6 occurrences with subject type hsdo_Variable and object type hsdo_Provider.
    - 10 occurrences with subject type hsdo_Provider and object type hsdo_Science_Keyword.
    - 16 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Instrument.
    - 2 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Platform.
    - 6 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Science_Keyword.
    - 5 occurrences with subject type hsdo_Provider and object type hsdo_Project.
    - 2 occurrences with subject type hsdo_Model and object type hsdo_Project.
    - 6 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Measurement_Name.
    - 5 occurrences with subject type hsdo_Instrument and object type hsdo_Models.
    - 3 occurrences with subject type hsdo_Provider and object type hsdo_Model.
    - 15 occurrences with subject type hsdo_Instrument and object type hsdo_Variable.
    - 2 occurrences with subject type hsdo_Dataset and object type hsdo_Location.
    - 3 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Measurement_Name.
    - 1 occurrences with subject type hsdo_Project and object type hsdo_Platform.
    - 3 occurrences with subject type hsdo_Location and object type hsdo_Related_Url_Content_Type.
    - 7 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Models.
    - 8 occurrences with subject type hsdo_Variable and object type hsdo_Chronostratigraphic_Unit.
    - 2 occurrences with subject type hsdo_Variable and object type hsdo_Platform.
    - 2 occurrences with subject type hsdo_Variable and object type hsdo_Variable.
    - 1 occurrences with subject type hsdo_Variable and object type hsdo_Data_Format.
    - 1 occurrences with subject type hsdo_Project and object type hsdo_Provider.
    - 2 occurrences with subject type hsdo_Project and object type hsdo_Models.
    - 3 occurrences with subject type hsdo_Models and object type hsdo_Experiment.
    - 1 occurrences with subject type hsdo_Model and object type hsdo_Provider.
    - 4 occurrences with subject type hsdo_Provider and object type hsdo_Models.
    - 2 occurrences with subject type hsdo_Models and object type hsdo_Location.
    - 2 occurrences with subject type hsdo_Institution and object type hsdo_Variable.
    - 1 occurrences with subject type hsdo_Project and object type hsdo_Chronostratigraphic_Unit.
    - 3 occurrences with subject type hsdo_Location and object type hsdo_Dataset.
    - 5 occurrences with subject type hsdo_Related_Url_Content_Type and object type
      hsdo_Location.
    - 3 occurrences with subject type hsdo_Related_Url_Content_Type and object type
      hsdo_Instrument.
    - 1 occurrences with subject type hsdo_Related_Url_Content_Type and object type
      hsdo_Experiment.
    - 5 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Variable.
    - 6 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Experiment.
    - 3 occurrences with subject type hsdo_Activity and object type hsdo_Variable.
    - 4 occurrences with subject type hsdo_Experiment and object type hsdo_Data_Format.
    - 2 occurrences with subject type hsdo_Project and object type hsdo_Measurement_Name.
    - 2 occurrences with subject type hsdo_Model and object type hsdo_Measurement_Name.
    - 2 occurrences with subject type hsdo_Platform and object type hsdo_Provider.
    - 1 occurrences with subject type hsdo_Experiment and object type hsdo_Chronostratigraphic_Unit.
    - 2 occurrences with subject type hsdo_Experiment and object type hsdo_Measurement_Name.
    - 2 occurrences with subject type hsdo_Instrument and object type hsdo_Related_Url_Content_Type.
    - 9 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type
      hsdo_Location.
    - 3 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type
      hsdo_Instrument.
    - 1 occurrences with subject type hsdo_Variable and object type hsdo_Measurement_Name.
    - 2 occurrences with subject type hsdo_Temporal_Resolution_Range and object type
      hsdo_Location.
    - 4 occurrences with subject type hsdo_Sub_Experiment_Id and object type hsdo_Location.
    - 2 occurrences with subject type hsdo_Experiment and object type hsdo_Platform.
    - 1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Chronostratigraphic_Unit.
    - 2 occurrences with subject type hsdo_Platform and object type hsdo_Chronostratigraphic_Unit.
    - 1 occurrences with subject type hsdo_Location and object type hsdo_Temporal_Resolution_Range.
    - 1 occurrences with subject type hsdo_Frequency and object type hsdo_Location.
    - 1 occurrences with subject type hsdo_Instrument and object type hsdo_Activity.
    - 1 occurrences with subject type hsdo_Temporal_Resolution_Range and object type
      hsdo_Model.
    - 1 occurrences with subject type hsdo_Temporal_Resolution_Range and object type
      hsdo_Instrument.
    - 1 occurrences with subject type hsdo_Model and object type hsdo_Platform.
    - 2 occurrences with subject type hsdo_Provider and object type hsdo_Measurement_Name.
    - 1 occurrences with subject type hsdo_Institution and object type hsdo_Instrument.
    - 1 occurrences with subject type hsdo_Provider and object type hsdo_Platform.
    - 2 occurrences with subject type hsdo_Platform and object type hsdo_Models.
    - 3 occurrences with subject type hsdo_Provider and object type hsdo_Variable.
    - 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Provider.
    - 2 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type
      hsdo_Variable.
    - 1 occurrences with subject type hsdo_Provider and object type hsdo_Provider.
    - 1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Project.
    - 2 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Model.
    - 1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Data_Format.
    - 1 occurrences with subject type hsdo_Provider and object type hsdo_Chronostratigraphic_Unit.
    - 1 occurrences with subject type hsdo_Provider and object type hsdo_Cmip6_Source_Id.
    - 1 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type
      hsdo_Project.
    - 1 occurrences with subject type hsdo_Dataset and object type hsdo_Provider.
    - 1 occurrences with subject type hsdo_Dataset and object type hsdo_Science_Keyword.
    - 1 occurrences with subject type hsdo_Dataset and object type hsdo_Project.
    - 1 occurrences with subject type hsdo_Platform and object type hsdo_Project.
    - 4 occurrences with subject type hsdo_Experiment and object type hsdo_Models.
    - 3 occurrences with subject type hsdo_Data_Format and object type hsdo_Location.
    - 1 occurrences with subject type hsdo_Data_Format and object type hsdo_Science_Keyword.
    - 1 occurrences with subject type hsdo_Model and object type hsdo_Models.
    - 1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Variable.
    - 1 occurrences with subject type hsdo_Project and object type hsdo_Sub_Experiment_Id.
    examples:
    - value: https://climateKG.org/entity/ff1cfc9c-5e73-4137-b8e1-d6f4e83e61c4 relation:MeasuredAt
        https://climateKG.org/entity/c322d007-8d19-451b-ba46-daa216782248
    - value: https://climateKG.org/entity/fc77777e-614f-41f1-9b97-d5324fa99105 relation:MeasuredAt
        https://climateKG.org/entity/27dd85c2-3403-438d-8b0c-8d424df60468
    - value: https://climateKG.org/entity/d76e6734-956b-419d-9d7a-52b8e645b6ac relation:MeasuredAt
        https://climateKG.org/entity/e384382c-fb2a-43ea-b064-610e6d4807e9
    - value: https://climateKG.org/entity/fc77777e-614f-41f1-9b97-d5324fa99105 relation:MeasuredAt
        https://climateKG.org/entity/d40d9651-aa19-4b2c-9764-7371bb64b9a7
    - value: https://climateKG.org/entity/f829171e-8b22-4f93-8f71-7932dfd7a70b relation:MeasuredAt
        https://climateKG.org/entity/e2e53a45-c6ee-4fac-9c08-7677c1318533
    - value: https://climateKG.org/entity/f9fe1bc0-88c5-4c26-9b4c-a9867d027685 relation:MeasuredAt
        https://climateKG.org/entity/67290503-94b9-4517-b5b6-063bba2bee27
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d relation:MeasuredAt
        https://climateKG.org/entity/fa68e752-f3a7-4361-a000-47c908545e49
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d relation:MeasuredAt
        https://climateKG.org/entity/feff6e5e-27be-4404-af9c-c80b56d48ad4
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d relation:MeasuredAt
        https://climateKG.org/entity/fbb455d3-de90-43dc-b678-48f463461740
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d relation:MeasuredAt
        https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d relation:MeasuredAt
        https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58
    - value: https://climateKG.org/entity/ff5d5c12-74d9-435d-9164-1c9d69f967d7 relation:MeasuredAt
        https://climateKG.org/entity/9d7eed04-9c49-4024-8d0f-06474cc38bbc
    - value: https://climateKG.org/entity/ffdb1819-43ba-4307-80db-dae705f62a8d relation:MeasuredAt
        https://climateKG.org/entity/5c439818-3a80-4c6d-9d2c-74ea1f1a294a
    - value: https://climateKG.org/entity/f39bac00-b827-46c3-aae2-3b98df0be0dc relation:MeasuredAt
        https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
    - value: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb relation:MeasuredAt
        https://climateKG.org/entity/fc95c990-47cb-4087-a08f-235dd1eb1260
    - value: https://climateKG.org/entity/b9107ec3-c777-4e71-9046-55bd7ed57ef0 relation:MeasuredAt
        https://climateKG.org/entity/c297fda0-848a-4a9b-85be-86f29c92f212
    - value: https://climateKG.org/entity/8e6ac9fb-b2a0-4547-915d-15b4e0df7d4a relation:MeasuredAt
        https://climateKG.org/entity/6a04c8fb-53aa-465d-803d-d0aaad32be12
    - value: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66 relation:MeasuredAt
        https://climateKG.org/entity/b9107ec3-c777-4e71-9046-55bd7ed57ef0
    - value: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66 relation:MeasuredAt
        https://climateKG.org/entity/e657b41f-4aa0-4816-b3c8-5b477812a0bc
    - value: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66 relation:MeasuredAt
        https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
    - value: https://climateKG.org/entity/f8845bec-c628-4185-aac1-4af22481c024 relation:MeasuredAt
        https://climateKG.org/entity/91d0d91a-6395-49a0-b498-41f71ae83ecc
    - value: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb relation:MeasuredAt
        https://climateKG.org/entity/f6350232-b1c7-458c-bc43-bda357ebb6db
    - value: https://climateKG.org/entity/ee0fce70-2097-4f5b-853a-c34e6cbff929 relation:MeasuredAt
        https://climateKG.org/entity/0399b52c-e3de-4dcc-9eb6-b1e3acf2cf1b
    - value: https://climateKG.org/entity/f36d71c6-f2ad-49c4-809f-09b4f0688412 relation:MeasuredAt
        https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
    - value: https://climateKG.org/entity/ff5d5c12-74d9-435d-9164-1c9d69f967d7 relation:MeasuredAt
        https://climateKG.org/entity/ea213be5-fe37-4179-9a9b-030c2bf42cf5
    - value: https://climateKG.org/entity/fd03d204-4391-4e98-8142-8b8efa235231 relation:MeasuredAt
        https://climateKG.org/entity/9db10fb2-0ceb-412e-9936-a286c579fa9f
    - value: https://climateKG.org/entity/fe2719de-c5c8-4ce6-8230-1d16c8155991 relation:MeasuredAt
        https://climateKG.org/entity/d8bb1aa0-49d7-4a6a-a96e-66231b3fc7f6
    - value: https://climateKG.org/entity/fe4392b0-13a9-43ff-bacc-f44a65aed4fa relation:MeasuredAt
        https://climateKG.org/entity/26fc4850-7ba9-44d8-a156-5c623e17b72f
    - value: https://climateKG.org/entity/eeba88d2-20bf-43b1-bccf-b125485405f4 relation:MeasuredAt
        https://climateKG.org/entity/511637f3-82aa-43b2-9eee-0c099ecbfcce
    - value: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb relation:MeasuredAt
        https://climateKG.org/entity/b2140059-b3ca-415c-b0a7-3e142783ffe8
    - value: https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92 relation:MeasuredAt
        https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66
    - value: https://climateKG.org/entity/fc5a1b7a-5ee8-4d67-80f5-a57e3f1734ab relation:MeasuredAt
        https://climateKG.org/entity/10a9c153-f37d-48fe-920d-c790d946ab07
    - value: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb relation:MeasuredAt
        https://climateKG.org/entity/482453d7-ffa4-4ae9-8158-9fa73bcf39ef
    - value: https://climateKG.org/entity/063177a9-14cd-4750-9aa4-ad5d266bd7ad relation:MeasuredAt
        https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
    - value: https://climateKG.org/entity/640d703f-9312-4f11-8367-30a8bd8fc508 relation:MeasuredAt
        https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb
    - value: https://climateKG.org/entity/063177a9-14cd-4750-9aa4-ad5d266bd7ad relation:MeasuredAt
        https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
    - value: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3 relation:MeasuredAt
        https://climateKG.org/entity/b9107ec3-c777-4e71-9046-55bd7ed57ef0
    - value: https://climateKG.org/entity/0720043d-4d31-45ae-a37c-9ba5959bf97d relation:MeasuredAt
        https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58
    - value: https://climateKG.org/entity/ecac51c2-4def-4dac-b965-a5103402395b relation:MeasuredAt
        https://climateKG.org/entity/ebe6f3c4-a78f-4152-977c-296d42e4e9e8
    - value: https://climateKG.org/entity/facdb262-04eb-47f9-b46e-ba7a379722ec relation:MeasuredAt
        https://climateKG.org/entity/559411a8-5fe5-4d2c-ad6b-30849e650396
    - value: https://climateKG.org/entity/d7742082-5461-4610-9ced-e0ec3bb64697 relation:MeasuredAt
        https://climateKG.org/entity/75b8d2f7-5c8a-41d3-9660-ebd2f2cb4b4b
    - value: https://climateKG.org/entity/c45c4e30-e253-4329-8838-8991a53f494f relation:MeasuredAt
        https://climateKG.org/entity/ddcd5941-9ba8-4c39-a498-1e214d1bfa6e
    - value: https://climateKG.org/entity/43e825a7-4080-44d5-ac32-f355ed1e35c0 relation:MeasuredAt
        https://climateKG.org/entity/8dc44d7b-e349-42ab-860e-18f5acfc1b28
    - value: https://climateKG.org/entity/d1ef1ce2-7a50-446d-b744-73513700f351 relation:MeasuredAt
        https://climateKG.org/entity/c7e7fb38-44ef-4c5b-aa1d-b3fdcf89d838
    - value: https://climateKG.org/entity/df160e31-ae45-41a4-9093-a80fe5303cea relation:MeasuredAt
        https://climateKG.org/entity/e000088a-8252-4603-ba55-38189c45612c
    - value: https://climateKG.org/entity/ecc4a2bb-f195-4296-b300-c1227221b688 relation:MeasuredAt
        https://climateKG.org/entity/4e366444-01ea-4517-9d93-56f55ddf41b7
    - value: https://climateKG.org/entity/ba70b595-5263-4ffd-97a2-f86ba91681ae relation:MeasuredAt
        https://climateKG.org/entity/3b20a141-8408-44b2-adf1-632ac9222c61
    - value: https://climateKG.org/entity/d8bb1aa0-49d7-4a6a-a96e-66231b3fc7f6 relation:MeasuredAt
        https://climateKG.org/entity/c5563d03-2f68-4dac-a50b-3b8450725356
    - value: https://climateKG.org/entity/fdb04105-e8ba-4a83-9c35-ed3c931ccc9f relation:MeasuredAt
        https://climateKG.org/entity/a4202721-0cba-4fa1-853f-890f146b04f9
    - value: https://climateKG.org/entity/fdb04105-e8ba-4a83-9c35-ed3c931ccc9f relation:MeasuredAt
        https://climateKG.org/entity/f6350232-b1c7-458c-bc43-bda357ebb6db
    - value: https://climateKG.org/entity/fdb04105-e8ba-4a83-9c35-ed3c931ccc9f relation:MeasuredAt
        https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
    - value: https://climateKG.org/entity/f634ab55-de40-4d0b-93bc-691bf5408ccb relation:MeasuredAt
        https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
    - value: https://climateKG.org/entity/fe950f88-6d5e-4741-8076-3fbe16b0b9c4 relation:MeasuredAt
        https://climateKG.org/entity/655fe09d-7335-467f-a286-3d1906d194d6
    - value: https://climateKG.org/entity/a4aea007-d297-4051-8b41-5cdde00b4d1e relation:MeasuredAt
        https://climateKG.org/entity/d8bb1aa0-49d7-4a6a-a96e-66231b3fc7f6
    - value: https://climateKG.org/entity/e5815f58-8232-4c7f-b50d-ea71d73891a9 relation:MeasuredAt
        https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
    - value: https://climateKG.org/entity/ff1cfc9c-5e73-4137-b8e1-d6f4e83e61c4 relation:MeasuredAt
        https://climateKG.org/entity/be15e9d3-5879-4432-96d1-3c16c81a4c8c
    - value: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66 relation:MeasuredAt
        https://climateKG.org/entity/10a9c153-f37d-48fe-920d-c790d946ab07
    - value: https://climateKG.org/entity/10de1987-5896-42d6-be7c-506fd7ba1f21 relation:MeasuredAt
        https://climateKG.org/entity/5ce16b97-c91c-420c-9701-33d19d50b286
    - value: https://climateKG.org/entity/10de1987-5896-42d6-be7c-506fd7ba1f21 relation:MeasuredAt
        https://climateKG.org/entity/a686e751-3639-4cd0-840b-c8ad25c441c1
    - value: https://climateKG.org/entity/ebe6f3c4-a78f-4152-977c-296d42e4e9e8 relation:MeasuredAt
        https://climateKG.org/entity/c88a747b-2302-49c9-b747-f2faa21e2b6b
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d relation:MeasuredAt
        https://climateKG.org/entity/569a2936-7543-434e-92e2-6f75a5be68c0
    - value: https://climateKG.org/entity/a4aea007-d297-4051-8b41-5cdde00b4d1e relation:MeasuredAt
        https://climateKG.org/entity/6831004a-34d7-42f5-a903-6c84a5e7590f
    - value: https://climateKG.org/entity/df160e31-ae45-41a4-9093-a80fe5303cea relation:MeasuredAt
        https://climateKG.org/entity/e6fb1b81-8ffc-486f-b1a1-2f292af8cee6
    - value: https://climateKG.org/entity/1499785c-8b74-45f4-bbf7-19d2d4e43b2f relation:MeasuredAt
        https://climateKG.org/entity/51e3593f-4b42-4141-972e-96666c479f9c
    - value: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e relation:MeasuredAt
        https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
    - value: https://climateKG.org/entity/43e825a7-4080-44d5-ac32-f355ed1e35c0 relation:MeasuredAt
        https://climateKG.org/entity/a6212424-1146-4a79-a14c-8ce88543b08b
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d relation:MeasuredAt
        https://climateKG.org/entity/7e317dda-643f-494d-bdf1-b017c7194add
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d relation:MeasuredAt
        https://climateKG.org/entity/f634ab55-de40-4d0b-93bc-691bf5408ccb
    - value: https://climateKG.org/entity/ffdb1819-43ba-4307-80db-dae705f62a8d relation:MeasuredAt
        https://climateKG.org/entity/4401ec0e-0d64-41d3-b4bd-2ff797865e83
    - value: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9 relation:MeasuredAt
        https://climateKG.org/entity/74d079b5-9b36-45c9-9b09-7e3646b65a85
    - value: https://climateKG.org/entity/8894d92c-be32-465b-ae08-e5de755a92fc relation:MeasuredAt
        https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    - value: https://climateKG.org/entity/1af675ae-9a65-4d91-970e-a8b9fcce0232 relation:MeasuredAt
        https://climateKG.org/entity/d896a8cc-4fce-4a8d-86bc-185b324fab2b
    - value: https://climateKG.org/entity/e6f9524a-e4bc-460a-bdf3-a5e8f0e921a9 relation:MeasuredAt
        https://climateKG.org/entity/a686e751-3639-4cd0-840b-c8ad25c441c1
    - value: https://climateKG.org/entity/f26c754c-1765-4a45-920e-792b43353a39 relation:MeasuredAt
        https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
    - value: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9 relation:MeasuredAt
        https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    - value: https://climateKG.org/entity/80a294bd-b8a1-44f3-ac3d-acb7d409d23f relation:MeasuredAt
        https://climateKG.org/entity/0b3765f7-20f7-4425-bd50-d1bb99d09d86
    - value: https://climateKG.org/entity/1b945d01-2f5c-4008-b1b3-d78b2822b466 relation:MeasuredAt
        https://climateKG.org/entity/d78e5503-d78e-466d-97bb-e68d6e768a9d
    - value: https://climateKG.org/entity/ba70b595-5263-4ffd-97a2-f86ba91681ae relation:MeasuredAt
        https://climateKG.org/entity/c297fda0-848a-4a9b-85be-86f29c92f212
    - value: https://climateKG.org/entity/f634ab55-de40-4d0b-93bc-691bf5408ccb relation:MeasuredAt
        https://climateKG.org/entity/27dd85c2-3403-438d-8b0c-8d424df60468
    - value: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9 relation:MeasuredAt
        https://climateKG.org/entity/c88a747b-2302-49c9-b747-f2faa21e2b6b
    - value: https://climateKG.org/entity/511637f3-82aa-43b2-9eee-0c099ecbfcce relation:MeasuredAt
        https://climateKG.org/entity/a9b21edd-49b7-43be-8e35-8652bbc5559a
    - value: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9 relation:MeasuredAt
        https://climateKG.org/entity/d2e93932-0231-4b23-af2f-217c6315a95e
    - value: https://climateKG.org/entity/f634ab55-de40-4d0b-93bc-691bf5408ccb relation:MeasuredAt
        https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
    - value: https://climateKG.org/entity/5fd5ccc2-5edb-4823-940d-03a290a5c5fc relation:MeasuredAt
        https://climateKG.org/entity/4ea1b3cc-d4d2-4803-a416-753cdd1ec451
    - value: https://climateKG.org/entity/406bfa8b-8522-4776-936a-1fda8b0cfe97 relation:MeasuredAt
        https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
    - value: https://climateKG.org/entity/ea213be5-fe37-4179-9a9b-030c2bf42cf5 relation:MeasuredAt
        https://climateKG.org/entity/bbd90aa4-fe5e-4580-a51d-90d7568a9fee
    - value: https://climateKG.org/entity/bb9c9be6-78c7-4fbd-9a35-a218276393ec relation:MeasuredAt
        https://climateKG.org/entity/3f45aadf-ec7c-43a1-a008-b24ca139837a
    - value: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb relation:MeasuredAt
        https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    - value: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54 relation:MeasuredAt
        https://climateKG.org/entity/734f8f27-6976-4b67-8794-c7fc79d6161e
    - value: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9 relation:MeasuredAt
        https://climateKG.org/entity/e4e4dac0-f0aa-4757-989c-70522eb64e76
    - value: https://climateKG.org/entity/2a60df4a-a0d7-4e4b-b02a-372a083f0170 relation:MeasuredAt
        https://climateKG.org/entity/a9b21edd-49b7-43be-8e35-8652bbc5559a
    - value: https://climateKG.org/entity/8cb47594-3af6-4f4f-8ba1-4299a6d6887e relation:MeasuredAt
        https://climateKG.org/entity/4f3c0b04-1fe6-4e11-994a-9cc4afd09ce0
    - value: https://climateKG.org/entity/b9107ec3-c777-4e71-9046-55bd7ed57ef0 relation:MeasuredAt
        https://climateKG.org/entity/1e11026d-b012-494a-a813-8c69cb41fc0d
    - value: https://climateKG.org/entity/b631f7b6-9a64-4f2b-bd29-7a20a466e44b relation:MeasuredAt
        https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
    - value: https://climateKG.org/entity/b631f7b6-9a64-4f2b-bd29-7a20a466e44b relation:MeasuredAt
        https://climateKG.org/entity/a9b21edd-49b7-43be-8e35-8652bbc5559a
    - value: https://climateKG.org/entity/569a2936-7543-434e-92e2-6f75a5be68c0 relation:MeasuredAt
        https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    - value: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e relation:MeasuredAt
        https://climateKG.org/entity/d896a8cc-4fce-4a8d-86bc-185b324fab2b
    - value: https://climateKG.org/entity/342ee29f-1e63-4bb4-b8d0-8f07472de7a9 relation:MeasuredAt
        https://climateKG.org/entity/4e366444-01ea-4517-9d93-56f55ddf41b7
    - value: https://climateKG.org/entity/4ea1b3cc-d4d2-4803-a416-753cdd1ec451 relation:MeasuredAt
        https://climateKG.org/entity/063177a9-14cd-4750-9aa4-ad5d266bd7ad
    - value: https://climateKG.org/entity/640d703f-9312-4f11-8367-30a8bd8fc508 relation:MeasuredAt
        https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
    - value: https://climateKG.org/entity/3f45aadf-ec7c-43a1-a008-b24ca139837a relation:MeasuredAt
        https://climateKG.org/entity/a9586b25-36da-4e7d-ac2a-b1b24e2f44bd
    - value: https://climateKG.org/entity/f634ab55-de40-4d0b-93bc-691bf5408ccb relation:MeasuredAt
        https://climateKG.org/entity/c266a473-338f-4fe9-965c-f8ae853ff57b
    - value: https://climateKG.org/entity/640d703f-9312-4f11-8367-30a8bd8fc508 relation:MeasuredAt
        https://climateKG.org/entity/885735f3-121e-4ca0-ac8b-f37dbc972f03
    - value: https://climateKG.org/entity/e8df7edd-a176-45c9-8515-3a520948ef63 relation:MeasuredAt
        https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
    - value: https://climateKG.org/entity/453a6807-abfa-481b-95b3-60bacf2cbb73 relation:MeasuredAt
        https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
    - value: https://climateKG.org/entity/ff5d5c12-74d9-435d-9164-1c9d69f967d7 relation:MeasuredAt
        https://climateKG.org/entity/2892e23f-5249-439d-8c0e-6c1d190b3beb
    - value: https://climateKG.org/entity/4f3c0b04-1fe6-4e11-994a-9cc4afd09ce0 relation:MeasuredAt
        https://climateKG.org/entity/f75bc31f-afda-45f4-bc90-226b7b0ee818
    - value: https://climateKG.org/entity/b7ed88ce-3f04-40ea-863e-ac58bd048ff3 relation:MeasuredAt
        https://climateKG.org/entity/0bdca141-ccec-471e-9dd9-f47d3a94abf7
    - value: https://climateKG.org/entity/4f3c0b04-1fe6-4e11-994a-9cc4afd09ce0 relation:MeasuredAt
        https://climateKG.org/entity/e2e53a45-c6ee-4fac-9c08-7677c1318533
    - value: https://climateKG.org/entity/f6a8db71-9686-46ec-a3ac-66ca4a0ec1bd relation:MeasuredAt
        https://climateKG.org/entity/569a2936-7543-434e-92e2-6f75a5be68c0
    - value: https://climateKG.org/entity/e4e4dac0-f0aa-4757-989c-70522eb64e76 relation:MeasuredAt
        https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
    - value: https://climateKG.org/entity/5796ebd9-7dcb-4968-b876-1e678484cc62 relation:MeasuredAt
        https://climateKG.org/entity/b631f7b6-9a64-4f2b-bd29-7a20a466e44b
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d relation:MeasuredAt
        https://climateKG.org/entity/2c37a52f-c159-4d16-a5c1-36ca833863e1
    - value: https://climateKG.org/entity/6831004a-34d7-42f5-a903-6c84a5e7590f relation:MeasuredAt
        https://climateKG.org/entity/7e304e75-b6b9-4e4b-bbaf-64a0a49d157d
    - value: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66 relation:MeasuredAt
        https://climateKG.org/entity/7e304e75-b6b9-4e4b-bbaf-64a0a49d157d
    - value: https://climateKG.org/entity/6fff6994-a0d8-4f19-8d36-c9f354b08b19 relation:MeasuredAt
        https://climateKG.org/entity/4e366444-01ea-4517-9d93-56f55ddf41b7
    - value: https://climateKG.org/entity/67a21bdb-2f92-4692-96e7-6a27e95f8c55 relation:MeasuredAt
        https://climateKG.org/entity/a686e751-3639-4cd0-840b-c8ad25c441c1
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d relation:MeasuredAt
        https://climateKG.org/entity/e4e4dac0-f0aa-4757-989c-70522eb64e76
    - value: https://climateKG.org/entity/e384382c-fb2a-43ea-b064-610e6d4807e9 relation:MeasuredAt
        https://climateKG.org/entity/4f3c0b04-1fe6-4e11-994a-9cc4afd09ce0
    - value: https://climateKG.org/entity/e000088a-8252-4603-ba55-38189c45612c relation:MeasuredAt
        https://climateKG.org/entity/e125e285-b547-47ea-b566-5dffce2bbcbd
    - value: https://climateKG.org/entity/e000088a-8252-4603-ba55-38189c45612c relation:MeasuredAt
        https://climateKG.org/entity/d9750f06-3784-4058-941f-40289c8d9d8b
    - value: https://climateKG.org/entity/77c41d31-ec6f-4d1f-8fc5-acdadebd6a80 relation:MeasuredAt
        https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
    - value: https://climateKG.org/entity/8c8c70b1-f6c5-4f34-89b5-510049b8c8ab relation:MeasuredAt
        https://climateKG.org/entity/6fa811fb-3666-4970-9208-ca8a21d57138
    - value: https://climateKG.org/entity/e95a1ee1-8a3e-47dd-aa5c-c2d66377bfc7 relation:MeasuredAt
        https://climateKG.org/entity/deeef0af-f305-4fd4-9796-e9e1906e5e15
    - value: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049 relation:MeasuredAt
        https://climateKG.org/entity/386eb378-1d17-4fdb-b0de-7aec4db7be59
    - value: https://climateKG.org/entity/7e304e75-b6b9-4e4b-bbaf-64a0a49d157d relation:MeasuredAt
        https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
    - value: https://climateKG.org/entity/82823ffa-e4d5-4877-bf0a-b9eb5b8c1108 relation:MeasuredAt
        https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
    - value: https://climateKG.org/entity/82b62e59-6ea1-48e1-a402-bd386c5046eb relation:MeasuredAt
        https://climateKG.org/entity/99ef187e-6940-4c10-8d65-00d4426d493b
    - value: https://climateKG.org/entity/8e4900ff-c7bc-47a1-aa55-a8892696d769 relation:MeasuredAt
        https://climateKG.org/entity/74d079b5-9b36-45c9-9b09-7e3646b65a85
    - value: https://climateKG.org/entity/9315c474-b65f-400d-beba-611c9a6a62cb relation:MeasuredAt
        https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58
    - value: https://climateKG.org/entity/99ef187e-6940-4c10-8d65-00d4426d493b relation:MeasuredAt
        https://climateKG.org/entity/10a9c153-f37d-48fe-920d-c790d946ab07
    - value: https://climateKG.org/entity/99ef187e-6940-4c10-8d65-00d4426d493b relation:MeasuredAt
        https://climateKG.org/entity/ea213be5-fe37-4179-9a9b-030c2bf42cf5
    - value: https://climateKG.org/entity/9a0c4d32-54c1-450e-aafd-f086678ed176 relation:MeasuredAt
        https://climateKG.org/entity/67290503-94b9-4517-b5b6-063bba2bee27
    - value: https://climateKG.org/entity/b9e718df-0a3a-46b6-a34f-4960e9449660 relation:MeasuredAt
        https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
    - value: https://climateKG.org/entity/a2e701d9-65e4-495c-b478-95b7d6a70ef8 relation:MeasuredAt
        https://climateKG.org/entity/ac87227c-b943-400a-ac61-71e42e8eb5f3
    - value: https://climateKG.org/entity/a463163e-8e86-4086-8b10-8fd6a95fca4a relation:MeasuredAt
        https://climateKG.org/entity/d8bb1aa0-49d7-4a6a-a96e-66231b3fc7f6
    - value: https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e relation:MeasuredAt
        https://climateKG.org/entity/eb539ad7-79ee-4d76-8e38-b298b2385626
    - value: https://climateKG.org/entity/d738d343-0440-4258-850d-107f9cd8072c relation:MeasuredAt
        https://climateKG.org/entity/ba70b595-5263-4ffd-97a2-f86ba91681ae
    - value: https://climateKG.org/entity/ac392872-1571-4bfd-94dd-81f93d9f1fd0 relation:MeasuredAt
        https://climateKG.org/entity/3b16a2e8-cc4d-40ce-a6c8-336bea211078
    - value: https://climateKG.org/entity/c98a4c91-1b1d-464d-8380-497a186db7eb relation:MeasuredAt
        https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
    - value: https://climateKG.org/entity/b45d57f9-5c45-4e46-8dcd-6158fee8151b relation:MeasuredAt
        https://climateKG.org/entity/750f6c61-0f15-4185-94d8-c029dec04bc5
    - value: https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e relation:MeasuredAt
        https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
    - value: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9 relation:MeasuredAt
        https://climateKG.org/entity/db28e274-27f4-4006-a363-32a98eab859d
    - value: https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e relation:MeasuredAt
        https://climateKG.org/entity/ebe6f3c4-a78f-4152-977c-296d42e4e9e8
    - value: https://climateKG.org/entity/be92ce0f-2f1f-4649-a3b2-36360964187a relation:MeasuredAt
        https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
    - value: https://climateKG.org/entity/be92ce0f-2f1f-4649-a3b2-36360964187a relation:MeasuredAt
        https://climateKG.org/entity/bff6b593-1884-4aea-87a1-36f606d3a020
    - value: https://climateKG.org/entity/c98a4c91-1b1d-464d-8380-497a186db7eb relation:MeasuredAt
        https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
    - value: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54 relation:MeasuredAt
        https://climateKG.org/entity/1411273b-4793-485b-91d6-1da4bfdaef22
    - value: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54 relation:MeasuredAt
        https://climateKG.org/entity/4353d710-3d65-44b3-b988-26af1415646a
    - value: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54 relation:MeasuredAt
        https://climateKG.org/entity/89fd4098-0bc4-4d26-a9fa-345390d7c9a9
    - value: https://climateKG.org/entity/d8bb1aa0-49d7-4a6a-a96e-66231b3fc7f6 relation:MeasuredAt
        https://climateKG.org/entity/6ffd7617-25fd-4464-bbd3-fc02e33ffafb
    - value: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d relation:MeasuredAt
        https://climateKG.org/entity/640d703f-9312-4f11-8367-30a8bd8fc508
    - value: https://climateKG.org/entity/ebe6f3c4-a78f-4152-977c-296d42e4e9e8 relation:MeasuredAt
        https://climateKG.org/entity/a4202721-0cba-4fa1-853f-890f146b04f9
    - value: https://climateKG.org/entity/ddcd5941-9ba8-4c39-a498-1e214d1bfa6e relation:MeasuredAt
        https://climateKG.org/entity/75ab3537-34b1-4025-b758-7296626079ba
    - value: https://climateKG.org/entity/de62c07e-96c6-44fb-a3a1-cd2902305691 relation:MeasuredAt
        https://climateKG.org/entity/640d703f-9312-4f11-8367-30a8bd8fc508
    - value: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9 relation:MeasuredAt
        https://climateKG.org/entity/1f1436a3-ac80-48e1-abbe-095fc74c9655
    - value: https://climateKG.org/entity/fcce904f-2989-49bb-801f-8829c5f85644 relation:MeasuredAt
        https://climateKG.org/entity/04e00ed0-39b6-4323-a788-2344264695c0
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: relation:MeasuredAt
    alias: relation_MeasuredAt
    owner: hsdo_Frequency
    domain_of:
    - hsdo_Activity
    - hsdo_Chronostratigraphic_Unit
    - hsdo_Data_Format
    - hsdo_Dataset
    - hsdo_Experiment
    - hsdo_Frequency
    - hsdo_Horizontal_Resolution_Range
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
    - hsdo_Sub_Experiment_Id
    - hsdo_Temporal_Resolution_Range
    - hsdo_Variable
    range: Any
    any_of:
    - range: hsdo_Science_Keyword
    - range: hsdo_Activity
    - range: hsdo_Models
    - range: hsdo_Data_Format
    - range: hsdo_Variable
    - range: hsdo_Dataset
    - range: hsdo_Model
    - range: hsdo_Chronostratigraphic_Unit
    - range: hsdo_Location
    - range: hsdo_Experiment
    - range: hsdo_Temporal_Resolution_Range
    - range: hsdo_Measurement_Name
    - range: hsdo_Cmip6_Source_Id
    - range: hsdo_Platform
    - range: hsdo_Related_Url_Content_Type
    - range: hsdo_Provider
    - range: hsdo_Project
    - range: hsdo_Sub_Experiment_Id
    - range: hsdo_Instrument
  skos_definition:
    name: skos_definition
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 368 occurrences with subject type hsdo_Location and object type string.
    - 2792 occurrences with subject type hsdo_Science_Keyword and object type string.
    - 1114 occurrences with subject type hsdo_Platform and object type string.
    - 24 occurrences with subject type hsdo_Activity and object type string.
    - 141 occurrences with subject type hsdo_Model and object type string.
    - 422 occurrences with subject type hsdo_Experiment and object type string.
    - 3483 occurrences with subject type hsdo_Provider and object type string.
    - 1913 occurrences with subject type hsdo_Instrument and object type string.
    - 1560 occurrences with subject type hsdo_Project and object type string.
    - 168 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type
      string.
    - 93 occurrences with subject type hsdo_Measurement_Name and object type string.
    - 75 occurrences with subject type hsdo_Institution and object type string.
    - 54 occurrences with subject type hsdo_Sub_Experiment_Id and object type string.
    - 37 occurrences with subject type hsdo_Models and object type string.
    - 187 occurrences with subject type hsdo_Data_Format and object type string.
    - 1280 occurrences with subject type hsdo_Variable and object type string.
    - 134 occurrences with subject type hsdo_Cmip6_Source_Id and object type string.
    - 5 occurrences with subject type hsdo_Source_Type and object type string.
    - 106 occurrences with subject type hsdo_Dataset and object type string.
    - 68 occurrences with subject type hsdo_Related_Url_Content_Type and object type
      string.
    - 16 occurrences with subject type hsdo_Frequency and object type string.
    - 4 occurrences with subject type hsdo_License and object type string.
    - 1 occurrences with subject type hsdo_Temporal_Resolution_Range and object type
      string.
    - 16359 occurrences with subject type skos_Concept and object type string.
    - 32 occurrences with subject type hsdo_Mime_Type and object type string.
    examples:
    - value: https://climateKG.org/entity/0006e246-4296-448c-9b81-a0831cad7f1c skos:definition
        An arm of the Atlantic Ocean between Greenland and Labrador Canada
    - value: https://climateKG.org/entity/001f18d3-7e61-430b-9883-1960c6256fe5 skos:definition
        The degree to which the ocean absorbs light assuming verticalseparation between
        light source and light receiver
    - value: https://climateKG.org/entity/007c3084-89db-458e-8387-14e192b6cb8e skos:definition
        PREFERRED TERMS 1A S1B S1C S1D Sentinel1DEFINITIONSentinel1 is the European
        Radar Observatory representing the first new space component of the GMES Global
        Monitoring for Environment and Security satellite family designed and developed
        by ESA and funded by the EC European Commission The Copernicus missions Sentinel1
        2 and 3 represent the EU contribution to GEOSS Global Earth Observation System
        of Systems Sentinel1 is composed of a constellation of two satellites Sentinel1A
        and Sentinel1B sharing the same orbital plane with a 180 orbital phasing difference
        The mission provides an independent operational capability for continuous
        radar mapping of the Earth with enhanced revisit frequency coverage timeliness
        and reliability for operational services and applications requiring long time
        seriesBROADER CONCEPT Earth Observation SatelliteENTRY TERMS SENTINEL1NOTE
        ABCDHOSTS SARURI httpsearthesaintconceptsentinel1
    - value: https://climateKG.org/entity/00a97d0c-e05e-43c9-93d0-3c7a2527b3c0 skos:definition
        Sea Ice Model Intercomparison Project
    - value: https://climateKG.org/entity/00bb59aa-755d-4710-a097-f1e2836f4032 skos:definition
        The evolution of the RADARSAT program the RCM includes a trio of Earth observation
        satellites capable of scanning Earth day or night and in any weather conditions
        The threesatellite configuration allows for daily revisits of Canadas vast
        territory and maritime approaches as well as daily access to 90 of the worlds
        surface and the Arctic up to four times a day
    - value: https://climateKG.org/entity/00ce4800-70ef-4346-aa15-0554280d0896 skos:definition
        Concerns about harmful algal blooms HAB have increased over the lastdecade
        largely because of the perceived increase in the number andduration of events
        The toxins produced by these species cause finfishand shellfish poisoning
        and mortality of marine animals includingmammals and birdsAdvance warning
        of HABs increases the options for managing theseevents The HAB Project develops
        and supports systems that provideinformation on the location and extent of
        red tide blooms in the Gulfof Mexico The Experimental HAB bulletin alerts
        subscribers todeveloping blooms and changes in the location and extent of
        existingblooms The HAB Mapping System HABMapS provides the position of anidentified
        bloom and data from environmental conditions that mayaffect the extent or
        position Both tools rely on remote sensingtechnology to provide the large
        spatial scale and high frequency ofobservations required to assess bloom location
        and movements Thesetools can be used together to provide a regional perspective
        on HABeventsAdditional information on HAB available athttpwwwcscnoaagovcrshabfindexhtmlAdditional
        information on the HAB Mapping System available athttpwwwcscnoaagovcrshabfhabmapshtmlSST      Summary
        provided by NOAA
    - value: https://climateKG.org/entity/0111fbd3-e6ec-464a-bc65-2323c2328e7c skos:definition
        The US Department of the Interior manages one of every five acres of land
        inthe United States providing opportunities for wilderness wildlife protectionrecreation
        and resource development They supply water for much of the west sothat farmers
        can grow food and people can turn on their taps They provideaccess to energy
        and minerals so that people can warm and cool their homes anddrive to their
        jobs They honor American Indians Alaska Natives andaffiliated Island communities
        and protect wildlife and improve theenvironmentWebsite httpwwwdoigovSummary
        provided by the US Department of the Interior
    - value: https://climateKG.org/entity/01407ecf-45af-4fcc-8a1b-9b383636e2e4 skos:definition
        HYDRA is a plasma experimental investigation on the POLAR spacecraft HYDRA
        isa collection of electrostatic analyzers designed for high resolutionobservations
        of electron and ion velocity distributions in the earths polarmagnetosphere
        and was designed and constructed by a consortium of institutionsfor the purpose
        of improving our understanding of the complex interactions ofthe polar magnetosphere
        with the solar wind and the ionosphereHYDRA subsystems are DuoDecaElectronIonSpectrometer
        DDEIS Parallel Plate Analyzer PPA Data Processing Unit DPU and UV Intracalibration
        System For more information see httpwwwstphysicsuiowaeduandhttppwggsfcnasagovpolarpolarinstshtmlGroup
        InstrumentDetails   EntryID HYDRA   Group InstrumentIdentification      InstrumentCategory
        SolarSpace Observing Instruments      InstrumentClass Particle Detectors      ShortName
        HYDRA      LongName Hot Plasma Analyzer   EndGroup   Group AssociatedPlatforms      ShortName
        POLAR   EndGroup   OnlineResource httpwwwstphysicsuiowaedu   SampleImage httpwwwstphysicsuiowaeduwwwimagesddeis2jpg   Group
        InstrumentLogistics      InstrumentStartDate 19960224      InstrumentOwner
        University of Iowa   EndGroupEndGroup
    - value: https://climateKG.org/entity/01e75216-1cee-4cc3-b31d-83019730da85 skos:definition
        The US National Park Service NPS proposes a series of integrated research
        monitoring education and outreach projects designed to better understand and
        communicate change in Arctic environments in Alaska United States and adjacent
        areas of Chukotka Russia and the Yukon Territory Canada Proposed projects
        within this effort include the followingImplement the Vital Sign Monitoring
        Program for Arctic ARCN and Central Alaska CAKN Networks These new programs
        based on conceptual models and long term monitoring objectives now in development
        will implement monitoring of a broad suite of biological chemical and physical
        indicators on 406 million acres of NPS lands and waters in and around eight
        national park units in Alaska Implement baseline archaeological inventories
        and ethnographic research During 20072008 new archaeological inventories will
        be conducted at selected locations in Cape Krusenstern Denali and YukonCharley
        Rivers to locate and systematically document prehistoric human occupation
        sites in arctic and subarctic coastal inland and riverine environments Also
        ethnographic research at YukonCharley will synthesize oral written and archival
        data to produce a comprehensive ethnographic assessmentReport results of the
        Western Airborne Contaminants Assessment Program WACAP During 20072008 this
        ongoing multiregional interagency US program will report on airborne contaminants
        in arctic subarctic highaltitude and high latitude areas A series of journal
        articles and presentations will be submitted for publication during the IPY
        Results will include contaminants assessments spring snow pack data and atmospheric
        back trajectories for multiple airborne contaminants potentially affecting
        polar areas A separate study will report on biological effects of airborne
        heavy metal deposition mineral dust in Cape KrusensternConvene two conferences
        on arctic parks and protected areas Scientific conferences and workshops focused
        on science and conservation of Arctic ecosystems and cultures will be cosponsored
        by NPS during the IPY The 2007 bilingual conference in Chukotka will be organized
        with Russian cooperators through the Beringian International Heritage Program
        Beringia The 2008 symposium in Alaska will be organized with the USGS other
        US cooperating agencies and possibly Beringia program cooperators Both symposia
        will be multidisciplinary biological physical cultural and social sciencesFocused
        journal issue on climate change in Alaskas national parks A focused issue
        of the Alaska Park Science journal will be published during 2007 in both printed
        and webbased formats Internetbased supporting materials targeted to meet the
        curriculum requirements of middle and highschool science teachers and students
        will also be developed Issues in 20082009 will highlight findings from research
        underway during IPYDigitized photo archives of arctic national parks NPS collections
        of Alaska photos will be screened and a representative collection of historic
        photographs documenting natural and cultural resources and human activities
        in Alaskas NPS areas targeting 50100 photographs of each area will be digitally
        reproduced for use in IPY symposia and publications This collection will also
        be augmented by recent photos possibly including repeat visits to photograph
        and document change at the sites of historic photographs Augment photo collection
        by working in cooperation with local Native residents and Native entities
        of the 36 neighboring communities to Arctic parks to acquire copies of historical
        photos documenting historical landform conditions Obtain use permission digitize
        and make available to Arctic researchers for use as dated baseline conditionsFocused
        competitive funding programs Support for a series of new focused projects
        will be provided through identification and consideration of IPYrelated criteria
        in the proposal request and evaluation processes of appropriate National Park
        Service competitive grant programs Eligible activities will include research
        natural and cultural resource inventories and monitoring recording of local
        and traditional knowledge trend analysis education and public outreach in
        Alaska and adjacent areas of Chukotka and the Yukon Territory For IPY 20072008
        we will specifically invite proposals to study and inform the public about
        arcticsubarctic climate change global and local contaminants exotic species
        in the arctic and subarctic increasing human use of parks and protected areas
        and resource development within and surrounding these areasSummary provided
        by httpclassicipyorgdevelopmenteoiproposaldetailsphpid21
    - value: https://climateKG.org/entity/02f8be65-6bdd-4f4d-9e69-adac5aec33f6 skos:definition
        The Ordovician Period lasted almost 45 million years beginning 4883 million
        years ago and ending 4437 million years ago During this period the area north
        of the tropics was almost entirely ocean and most of the worlds land was collected
        into the southern supercontinent Gondwana Throughout the Ordovician Gondwana
        shifted towards the South Pole and much of it was submerged underwater The
        Ordovician is best known for its diverse marine invertebrates including graptolites
        trilobites brachiopods and the conodonts early vertebrates A typical marine
        community consisted of these animals plus red and green algae primitive fish
        cephalopods corals crinoids and gastropods More recently tetrahedral spores
        that are similar to those of primitive land plants have been found suggesting
        that plants invaded the land at this time From the Lower to Middle Ordovician
        the Earth experienced a milder climate  the weather was warm and the atmosphere
        contained a lot of moisture However when Gondwana finally settled on the South
        Pole during the Upper Ordovician massive glaciers formed causing shallow seas
        to drain and sea levels to drop This likely caused the mass extinctions that
        characterize the end of the Ordovician in which 60 of all marine invertebrate
        genera and 25 of all families went extinct
    - value: https://climateKG.org/entity/038ac74c-470a-43e0-b80d-2b2fb1acfc13 skos:definition
        Airborne solid particles also called dust or particulate matter PM or liquid
        droplets
    - value: https://climateKG.org/entity/03976e48-3ff9-4dc6-a4c4-fd77026380ff skos:definition
        LLNL Lawrence Livermore National Laboratory Livermore CA 94550 USA ANL Argonne
        National Laboratory Argonne IL 60439 USA BNL Brookhaven National Laboratory
        Upton NY 11973 USA LANL Los Alamos National Laboratory Los Alamos NM 87545
        USA LBNL Lawrence Berkeley National Laboratory Berkeley CA 94720 USA ORNL
        Oak Ridge National Laboratory Oak Ridge TN 37831 USA PNNL Pacific Northwest
        National Laboratory Richland WA 99352 USA SNL Sandia National Laboratories
        Albuquerque NM 87185 USA Mailing address LLNL Climate Program co David C Bader
        Principal Investigator L103 7000 East Avenue Livermore CA 94550 USA
    - value: https://climateKG.org/entity/04e00ed0-39b6-4323-a788-2344264695c0 skos:definition
        initialized near end of year 2016
    - value: https://climateKG.org/entity/063177a9-14cd-4750-9aa4-ad5d266bd7ad skos:definition
        Numerical representation of the atmosphere and its phenomena over the entireEarth
        using the equations of motion and including radiation photochemistryand the
        transfer of heat water vapor and momentum
    - value: https://climateKG.org/entity/0679d78d-0931-4948-94ec-46ab130785a6 skos:definition
        A generalpurpose programming language that is interpreted and contains several
        features such as dynamic typing along with the flexible data types is known
        as ICI not an acronym programming language It is considered to be similar
        to the Perl language This ICI language comprises flow control constructs and
        also contains some operators of the C language It is not an objectoriented
        language but some of the features of OOP can be attained by a specific inheritance
        method known as superstructures Similar to C this ICI programming language
        has the same system interface and a standard library for builtin functions
    - value: https://climateKG.org/entity/0a23c6c7-d4e5-4ab4-a906-03e9b9bbee64 skos:definition
        Depth to Soil Thaw
    - value: https://climateKG.org/entity/0cd4d2c4-ebfa-4759-b7aa-f9982122f581 skos:definition
        IPSLCM5A2INCA
    - value: https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b skos:definition
        Specific subsystems or modules that together constitute a comprehensive climate
        model
    - value: https://climateKG.org/entity/2892e23f-5249-439d-8c0e-6c1d190b3beb skos:definition
        ECMWF  ERA5 European ReAnalysis
    - value: https://climateKG.org/entity/4f3c0b04-1fe6-4e11-994a-9cc4afd09ce0 skos:definition
        The URL for accessing micro articles Micro articles are concise and focused
        selections of information that allow users to quickly assess topics and locate
        the most useful or relevant associated data information and tools
    - value: https://climateKG.org/entity/8e4900ff-c7bc-47a1-aa55-a8892696d769 skos:definition
        daily mean samples
    - value: https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428 skos:definition
        Creative Commons Attribution 40 International httpscreativecommonsorglicensesby40
    - value: https://climateKG.org/entity/99ef187e-6940-4c10-8d65-00d4426d493b skos:definition
        A diurnal cycle is any pattern that recurs every 24 hours as a result of one
        full rotation of the Earth1 with respect to the Sun
    - value: 'https://gcmd.earthdata.nasa.gov/kms/concept/0006e246-4296-448c-9b81-a0831cad7f1c
        skos:definition Path = [''NORTH ATLANTIC OCEAN'', ''ATLANTIC OCEAN'', ''OCEAN'',
        ''Locations'']

        An arm of the Atlantic Ocean between Greenland and Labrador, Canada.'
    - value: https://climateKG.org/entity/07bcc60e-1551-44d9-b87e-7c260d230ecb skos:definition
        MIME Type for Opensearch Description files applicationopensearchdescriptionxml
        provides a humanreadable text description of the search engineParent OpenSearchDescriptionRestrictions
        The value must contain 1024 or fewer characters of plain text The value must
        not contain HTML or other markupRequirements This element must appear exactly
        once
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: skos:definition
    alias: skos_definition
    owner: hsdo_Frequency
    domain_of:
    - hsdo_Activity
    - hsdo_Chronostratigraphic_Unit
    - hsdo_Cmip6_Source_Id
    - hsdo_Data_Format
    - hsdo_Dataset
    - hsdo_Experiment
    - hsdo_Frequency
    - hsdo_Institution
    - hsdo_Instrument
    - hsdo_License
    - hsdo_Location
    - hsdo_Measurement_Name
    - hsdo_Mime_Type
    - hsdo_Model
    - hsdo_Models
    - hsdo_Platform
    - hsdo_Project
    - hsdo_Provider
    - hsdo_Related_Url_Content_Type
    - hsdo_Science_Keyword
    - hsdo_Source_Type
    - hsdo_Sub_Experiment_Id
    - hsdo_Temporal_Resolution_Range
    - hsdo_Variable
    - skos_Concept
    range: string
class_uri: hsdo:Frequency

```
</details>