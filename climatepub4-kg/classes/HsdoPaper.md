

# Class: TODO -- what's a good name for this class (type)? (hsdo_paper)


_No type description provided_





URI: [hsdo:paper](http://schema.org/paper)






```mermaid
 classDiagram
    class HsdoPaper
    click HsdoPaper href "../HsdoPaper"
      HsdoPaper : attribute_authors
        
          
    
    
    HsdoPaper --> "0..1" String : attribute_authors
    click String href "../String"

        
      HsdoPaper : attribute_doi
        
          
    
    
    HsdoPaper --> "0..1" String : attribute_doi
    click String href "../String"

        
      HsdoPaper : attribute_pub_date
        
          
    
    
    HsdoPaper --> "0..1" String : attribute_pub_date
    click String href "../String"

        
      HsdoPaper : attribute_title
        
          
    
    
    HsdoPaper --> "0..1" String : attribute_title
    click String href "../String"

        
      HsdoPaper : relation_Mention
        
          
    
    
    HsdoPaper --> "0..1" Any : relation_Mention
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [attribute_title](../slots/attribute_title.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [attribute_authors](../slots/attribute_authors.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [relation_Mention](../slots/relation_Mention.md) | 0..1 <br/> [HsdoScienceKeyword](../classes/HsdoScienceKeyword.md)&nbsp;or&nbsp;<br />[HsdoActivity](../classes/HsdoActivity.md)&nbsp;or&nbsp;<br />[HsdoModels](../classes/HsdoModels.md)&nbsp;or&nbsp;<br />[HsdoDataFormat](../classes/HsdoDataFormat.md)&nbsp;or&nbsp;<br />[HsdoInstitution](../classes/HsdoInstitution.md)&nbsp;or&nbsp;<br />[HsdoVariable](../classes/HsdoVariable.md)&nbsp;or&nbsp;<br />[HsdoDataset](../classes/HsdoDataset.md)&nbsp;or&nbsp;<br />[HsdoModel](../classes/HsdoModel.md)&nbsp;or&nbsp;<br />[HsdoChronostratigraphicUnit](../classes/HsdoChronostratigraphicUnit.md)&nbsp;or&nbsp;<br />[HsdoLocation](../classes/HsdoLocation.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)&nbsp;or&nbsp;<br />[HsdoTemporalResolutionRange](../classes/HsdoTemporalResolutionRange.md)&nbsp;or&nbsp;<br />[HsdoMeasurementName](../classes/HsdoMeasurementName.md)&nbsp;or&nbsp;<br />[HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md)&nbsp;or&nbsp;<br />[HsdoPlatform](../classes/HsdoPlatform.md)&nbsp;or&nbsp;<br />[HsdoRelatedUrlContentType](../classes/HsdoRelatedUrlContentType.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoProject](../classes/HsdoProject.md)&nbsp;or&nbsp;<br />[HsdoNominalResolution](../classes/HsdoNominalResolution.md)&nbsp;or&nbsp;<br />[HsdoSubExperimentId](../classes/HsdoSubExperimentId.md)&nbsp;or&nbsp;<br />[HsdoFrequency](../classes/HsdoFrequency.md)&nbsp;or&nbsp;<br />[HsdoInstrument](../classes/HsdoInstrument.md)&nbsp;or&nbsp;<br />[HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) | No slot description provided | direct |
| [attribute_pub_date](../slots/attribute_pub_date.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [attribute_doi](../slots/attribute_doi.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |









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
| self | hsdo:paper |
| native | climatepub4-kg/:HsdoPaper |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: hsdo_paper
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 300 occurences.
from_schema: climatepub4-kg
rank: 1000
slots:
- attribute_title
- attribute_authors
- relation_Mention
- attribute_pub_date
- attribute_doi
class_uri: hsdo:paper

```
</details>

### Induced

<details>
```yaml
name: hsdo_paper
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 300 occurences.
from_schema: climatepub4-kg
rank: 1000
attributes:
  attribute_title:
    name: attribute_title
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 286 occurrences with subject type hsdo_paper and object type string.
    examples:
    - value: https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb
        attribute:title Evaluating management strategies for eastern Bering Sea walleye
        pollock (Theragra chalcogramma) in a changing environment
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: attribute:title
    alias: attribute_title
    owner: hsdo_paper
    domain_of:
    - hsdo_paper
    range: string
  attribute_authors:
    name: attribute_authors
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 287 occurrences with subject type hsdo_paper and object type string.
    examples:
    - value: https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb
        attribute:authors James N Ianelli; Anne B Hollowed; Alan C Haynie; Franz J
        Mueter; Nicholas A Bond
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: attribute:authors
    alias: attribute_authors
    owner: hsdo_paper
    domain_of:
    - hsdo_paper
    range: string
  relation_Mention:
    name: relation_Mention
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1416 occurrences with subject type hsdo_paper and object type hsdo_Experiment.
    - 1646 occurrences with subject type hsdo_paper and object type hsdo_Science_Keyword.
    - 784 occurrences with subject type hsdo_paper and object type hsdo_Model.
    - 3054 occurrences with subject type hsdo_paper and object type hsdo_Instrument.
    - 5961 occurrences with subject type hsdo_paper and object type hsdo_Location.
    - 582 occurrences with subject type hsdo_paper and object type hsdo_Provider.
    - 627 occurrences with subject type hsdo_paper and object type hsdo_Project.
    - 434 occurrences with subject type hsdo_paper and object type hsdo_Models.
    - 125 occurrences with subject type hsdo_paper and object type hsdo_Variable.
    - 318 occurrences with subject type hsdo_paper and object type hsdo_Platform.
    - 107 occurrences with subject type hsdo_paper and object type hsdo_Measurement_Name.
    - 119 occurrences with subject type hsdo_paper and object type hsdo_Chronostratigraphic_Unit.
    - 85 occurrences with subject type hsdo_paper and object type hsdo_Data_Format.
    - 33 occurrences with subject type hsdo_paper and object type hsdo_Dataset.
    - 104 occurrences with subject type hsdo_paper and object type hsdo_Institution.
    - 21 occurrences with subject type hsdo_paper and object type hsdo_Sub_Experiment_Id.
    - 65 occurrences with subject type hsdo_paper and object type hsdo_Activity.
    - 14 occurrences with subject type hsdo_paper and object type hsdo_Related_Url_Content_Type.
    - 3 occurrences with subject type hsdo_paper and object type hsdo_Horizontal_Resolution_Range.
    - 24 occurrences with subject type hsdo_paper and object type hsdo_Temporal_Resolution_Range.
    - 30 occurrences with subject type hsdo_paper and object type hsdo_Cmip6_Source_Id.
    - 5 occurrences with subject type hsdo_paper and object type hsdo_Frequency.
    - 2 occurrences with subject type hsdo_paper and object type hsdo_Nominal_Resolution.
    examples:
    - value: https://climateKG.org/entity/initial_3 relation:Mention https://climateKG.org/entity/878e70de-f929-4d2f-9325-145ca95787e9
    - value: https://climateKG.org/entity/initial_3 relation:Mention https://climateKG.org/entity/d6aec072-daf9-4f96-b667-6c7831cf6bdd
    - value: https://climateKG.org/entity/initial_3 relation:Mention https://climateKG.org/entity/3fe9c479-3cb5-45bf-8f4d-637282dccfa3
    - value: https://climateKG.org/entity/initial_3 relation:Mention https://climateKG.org/entity/ba008542-5c6f-462a-8ddf-21e54cbf3034
    - value: https://climateKG.org/entity/initial_3 relation:Mention https://climateKG.org/entity/fa0ec8a7-ebed-4f2d-834b-1fa6a1c2e0ed
    - value: https://climateKG.org/entity/initial_2 relation:Mention https://climateKG.org/entity/d738d343-0440-4258-850d-107f9cd8072c
    - value: https://climateKG.org/entity/initial_3 relation:Mention https://climateKG.org/entity/4ea1b3cc-d4d2-4803-a416-753cdd1ec451
    - value: https://climateKG.org/entity/initial_3 relation:Mention https://climateKG.org/entity/b0346391-1b8a-41b8-9427-ff6e314fa06d
    - value: https://climateKG.org/entity/initial_2 relation:Mention https://climateKG.org/entity/ba70b595-5263-4ffd-97a2-f86ba91681ae
    - value: https://climateKG.org/entity/initial_2 relation:Mention https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e
    - value: https://climateKG.org/entity/f5e16581be56679d091bec59956504b6c3e30239
        relation:Mention https://climateKG.org/entity/fabeb7da-9d33-450e-83b0-5c3651d1e4a1
    - value: https://climateKG.org/entity/fb813628076a23fecc28f478f08a09ebdee33b0f
        relation:Mention https://climateKG.org/entity/c7e7fb38-44ef-4c5b-aa1d-b3fdcf89d838
    - value: https://climateKG.org/entity/initial_2 relation:Mention https://climateKG.org/entity/ac392872-1571-4bfd-94dd-81f93d9f1fd0
    - value: https://climateKG.org/entity/initial_3 relation:Mention https://climateKG.org/entity/a0b26420-3a13-4742-8d6f-391dc5c49d64
    - value: https://climateKG.org/entity/initial_3 relation:Mention https://climateKG.org/entity/e8df7edd-a176-45c9-8515-3a520948ef63
    - value: https://climateKG.org/entity/e6047f024856646877a812ee5a3f3848a9830b49
        relation:Mention https://climateKG.org/entity/3bc6fedc-c5a4-4986-bec2-eacc7b75a5dd
    - value: https://climateKG.org/entity/initial_2 relation:Mention https://climateKG.org/entity/68885007-d975-4f24-bdd5-dd19b246bdf6
    - value: https://climateKG.org/entity/f71f5612d64efcb9af7ebc9cd2e550d6d053e5a7
        relation:Mention https://climateKG.org/entity/86b8b121-d710-4c5b-84b0-7b40717f6c76
    - value: https://climateKG.org/entity/c3ff320aa72c7e29d067731f19e847505567c120
        relation:Mention https://climateKG.org/entity/1499785c-8b74-45f4-bbf7-19d2d4e43b2f
    - value: https://climateKG.org/entity/f1c594d8410ba7bf74732bfa710f08a935511a7d
        relation:Mention https://climateKG.org/entity/7c5420a6-94e2-40ca-9dff-20309090d327
    - value: https://climateKG.org/entity/initial_2 relation:Mention https://climateKG.org/entity/df0ba39b-7461-4cee-8660-c80fee72e96b
    - value: https://climateKG.org/entity/c3ff320aa72c7e29d067731f19e847505567c120
        relation:Mention https://climateKG.org/entity/8e4900ff-c7bc-47a1-aa55-a8892696d769
    - value: https://climateKG.org/entity/cd3e2817ca55a23192a862920ac38ad5c06e2adf
        relation:Mention https://climateKG.org/entity/82a2971f-82eb-46aa-8d70-1343570edba8
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: relation:Mention
    alias: relation_Mention
    owner: hsdo_paper
    domain_of:
    - hsdo_paper
    range: Any
    any_of:
    - range: hsdo_Science_Keyword
    - range: hsdo_Activity
    - range: hsdo_Models
    - range: hsdo_Data_Format
    - range: hsdo_Institution
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
    - range: hsdo_Nominal_Resolution
    - range: hsdo_Sub_Experiment_Id
    - range: hsdo_Frequency
    - range: hsdo_Instrument
    - range: hsdo_Horizontal_Resolution_Range
  attribute_pub_date:
    name: attribute_pub_date
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 181 occurrences with subject type hsdo_paper and object type string.
    examples:
    - value: https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb
        attribute:pub_date 2024-07-17
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: attribute:pub_date
    alias: attribute_pub_date
    owner: hsdo_paper
    domain_of:
    - hsdo_paper
    range: string
  attribute_doi:
    name: attribute_doi
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 284 occurrences with subject type hsdo_paper and object type string.
    examples:
    - value: https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb
        attribute:doi 10.1093/icesjms/fsr010
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: attribute:doi
    alias: attribute_doi
    owner: hsdo_paper
    domain_of:
    - hsdo_paper
    range: string
class_uri: hsdo:paper

```
</details>