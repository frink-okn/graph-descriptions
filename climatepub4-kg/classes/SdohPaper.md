

# Class: TODO -- what's a good name for this class (type)? (sdoh_paper)


_TODO -- tell the world what this class (type) describes._





URI: [sdoh:paper](http://schema.org/paper)






```mermaid
 classDiagram
    class SdohPaper
    click SdohPaper href "../SdohPaper"
      SdohPaper : http___attribute.org_authors
        
          
    
    
    SdohPaper --> "0..1" String : http___attribute.org_authors
    click String href "../String"

        
      SdohPaper : http___attribute.org_doi
        
          
    
    
    SdohPaper --> "0..1" String : http___attribute.org_doi
    click String href "../String"

        
      SdohPaper : http___attribute.org_pub_date
        
          
    
    
    SdohPaper --> "0..1" String : http___attribute.org_pub_date
    click String href "../String"

        
      SdohPaper : http___attribute.org_title
        
          
    
    
    SdohPaper --> "0..1" String : http___attribute.org_title
    click String href "../String"

        
      SdohPaper : http___relation.org_Mention
        
          
    
    
    SdohPaper --> "0..1" Any : http___relation.org_Mention
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [http___attribute.org_title](../slots/http___attribute.org_title.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [http___attribute.org_authors](../slots/http___attribute.org_authors.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [http___attribute.org_doi](../slots/http___attribute.org_doi.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [http___attribute.org_pub_date](../slots/http___attribute.org_pub_date.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [http___relation.org_Mention](../slots/http___relation.org_Mention.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdohInstrument](../classes/SdohInstrument.md)&nbsp;or&nbsp;<br />[SdohMeasurementName](../classes/SdohMeasurementName.md)&nbsp;or&nbsp;<br />[SdohInstitution](../classes/SdohInstitution.md)&nbsp;or&nbsp;<br />[SdohDataFormat](../classes/SdohDataFormat.md)&nbsp;or&nbsp;<br />[SdohFrequency](../classes/SdohFrequency.md)&nbsp;or&nbsp;<br />[SdohChronostratigraphicUnit](../classes/SdohChronostratigraphicUnit.md)&nbsp;or&nbsp;<br />[SdohModel](../classes/SdohModel.md)&nbsp;or&nbsp;<br />[SdohNominalResolution](../classes/SdohNominalResolution.md)&nbsp;or&nbsp;<br />[SdohExperiment](../classes/SdohExperiment.md)&nbsp;or&nbsp;<br />[SdohTemporalResolutionRange](../classes/SdohTemporalResolutionRange.md)&nbsp;or&nbsp;<br />[SdohActivity](../classes/SdohActivity.md)&nbsp;or&nbsp;<br />[SdohVariable](../classes/SdohVariable.md)&nbsp;or&nbsp;<br />[SdohDataset](../classes/SdohDataset.md)&nbsp;or&nbsp;<br />[SdohCmip6SourceId](../classes/SdohCmip6SourceId.md)&nbsp;or&nbsp;<br />[SdohHorizontalResolutionRange](../classes/SdohHorizontalResolutionRange.md)&nbsp;or&nbsp;<br />[SdohProject](../classes/SdohProject.md)&nbsp;or&nbsp;<br />[SdohModels](../classes/SdohModels.md)&nbsp;or&nbsp;<br />[SdohSubExperimentId](../classes/SdohSubExperimentId.md)&nbsp;or&nbsp;<br />[SdohPlatform](../classes/SdohPlatform.md)&nbsp;or&nbsp;<br />[SdohRelatedUrlContentType](../classes/SdohRelatedUrlContentType.md)&nbsp;or&nbsp;<br />[SdohProvider](../classes/SdohProvider.md)&nbsp;or&nbsp;<br />[SdohLocation](../classes/SdohLocation.md)&nbsp;or&nbsp;<br />[SdohScienceKeyword](../classes/SdohScienceKeyword.md) | TODO -- tell the world what this slot (predicate) describes | direct |









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
| self | sdoh:paper |
| native | climatepub4-kg/:SdohPaper |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_paper
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 300 occurences.
from_schema: climatepub4-kg
slots:
- http___attribute.org_title
- http___attribute.org_authors
- http___attribute.org_doi
- http___attribute.org_pub_date
- http___relation.org_Mention
class_uri: sdoh:paper

```
</details>

### Induced

<details>
```yaml
name: sdoh_paper
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 300 occurences.
from_schema: climatepub4-kg
attributes:
  http___attribute.org_title:
    name: http___attribute.org_title
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 286 occurrences with subject type sdoh_paper and object type string.
    examples:
    - value: https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb
        http://attribute.org/title Evaluating management strategies for eastern Bering
        Sea walleye pollock (Theragra chalcogramma) in a changing environment
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: http://attribute.org/title
    alias: http___attribute.org_title
    owner: sdoh_paper
    domain_of:
    - sdoh_paper
    range: string
  http___attribute.org_authors:
    name: http___attribute.org_authors
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 287 occurrences with subject type sdoh_paper and object type string.
    examples:
    - value: https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb
        http://attribute.org/authors James N Ianelli; Anne B Hollowed; Alan C Haynie;
        Franz J Mueter; Nicholas A Bond
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: http://attribute.org/authors
    alias: http___attribute.org_authors
    owner: sdoh_paper
    domain_of:
    - sdoh_paper
    range: string
  http___attribute.org_doi:
    name: http___attribute.org_doi
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 284 occurrences with subject type sdoh_paper and object type string.
    examples:
    - value: https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb
        http://attribute.org/doi 10.1093/icesjms/fsr010
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: http://attribute.org/doi
    alias: http___attribute.org_doi
    owner: sdoh_paper
    domain_of:
    - sdoh_paper
    range: string
  http___attribute.org_pub_date:
    name: http___attribute.org_pub_date
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 181 occurrences with subject type sdoh_paper and object type string.
    examples:
    - value: https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb
        http://attribute.org/pub_date 2024-07-17
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: http://attribute.org/pub_date
    alias: http___attribute.org_pub_date
    owner: sdoh_paper
    domain_of:
    - sdoh_paper
    range: string
  http___relation.org_Mention:
    name: http___relation.org_Mention
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 1416 occurrences with subject type sdoh_paper and object type sdoh_Experiment.
    - 1646 occurrences with subject type sdoh_paper and object type sdoh_Science_Keyword.
    - 784 occurrences with subject type sdoh_paper and object type sdoh_Model.
    - 3054 occurrences with subject type sdoh_paper and object type sdoh_Instrument.
    - 5961 occurrences with subject type sdoh_paper and object type sdoh_Location.
    - 582 occurrences with subject type sdoh_paper and object type sdoh_Provider.
    - 627 occurrences with subject type sdoh_paper and object type sdoh_Project.
    - 434 occurrences with subject type sdoh_paper and object type sdoh_Models.
    - 125 occurrences with subject type sdoh_paper and object type sdoh_Variable.
    - 318 occurrences with subject type sdoh_paper and object type sdoh_Platform.
    - 107 occurrences with subject type sdoh_paper and object type sdoh_Measurement_Name.
    - 119 occurrences with subject type sdoh_paper and object type sdoh_Chronostratigraphic_Unit.
    - 85 occurrences with subject type sdoh_paper and object type sdoh_Data_Format.
    - 33 occurrences with subject type sdoh_paper and object type sdoh_Dataset.
    - 104 occurrences with subject type sdoh_paper and object type sdoh_Institution.
    - 21 occurrences with subject type sdoh_paper and object type sdoh_Sub_Experiment_Id.
    - 65 occurrences with subject type sdoh_paper and object type sdoh_Activity.
    - 14 occurrences with subject type sdoh_paper and object type sdoh_Related_Url_Content_Type.
    - 3 occurrences with subject type sdoh_paper and object type sdoh_Horizontal_Resolution_Range.
    - 24 occurrences with subject type sdoh_paper and object type sdoh_Temporal_Resolution_Range.
    - 30 occurrences with subject type sdoh_paper and object type sdoh_Cmip6_Source_Id.
    - 5 occurrences with subject type sdoh_paper and object type sdoh_Frequency.
    - 2 occurrences with subject type sdoh_paper and object type sdoh_Nominal_Resolution.
    examples:
    - value: https://climateKG.org/entity/initial_3 http://relation.org/Mention https://climateKG.org/entity/878e70de-f929-4d2f-9325-145ca95787e9
    - value: https://climateKG.org/entity/initial_3 http://relation.org/Mention https://climateKG.org/entity/d6aec072-daf9-4f96-b667-6c7831cf6bdd
    - value: https://climateKG.org/entity/initial_3 http://relation.org/Mention https://climateKG.org/entity/3fe9c479-3cb5-45bf-8f4d-637282dccfa3
    - value: https://climateKG.org/entity/initial_3 http://relation.org/Mention https://climateKG.org/entity/ba008542-5c6f-462a-8ddf-21e54cbf3034
    - value: https://climateKG.org/entity/initial_3 http://relation.org/Mention https://climateKG.org/entity/fa0ec8a7-ebed-4f2d-834b-1fa6a1c2e0ed
    - value: https://climateKG.org/entity/initial_2 http://relation.org/Mention https://climateKG.org/entity/d738d343-0440-4258-850d-107f9cd8072c
    - value: https://climateKG.org/entity/initial_3 http://relation.org/Mention https://climateKG.org/entity/4ea1b3cc-d4d2-4803-a416-753cdd1ec451
    - value: https://climateKG.org/entity/initial_3 http://relation.org/Mention https://climateKG.org/entity/b0346391-1b8a-41b8-9427-ff6e314fa06d
    - value: https://climateKG.org/entity/initial_2 http://relation.org/Mention https://climateKG.org/entity/ba70b595-5263-4ffd-97a2-f86ba91681ae
    - value: https://climateKG.org/entity/initial_2 http://relation.org/Mention https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e
    - value: https://climateKG.org/entity/f5e16581be56679d091bec59956504b6c3e30239
        http://relation.org/Mention https://climateKG.org/entity/fabeb7da-9d33-450e-83b0-5c3651d1e4a1
    - value: https://climateKG.org/entity/fb813628076a23fecc28f478f08a09ebdee33b0f
        http://relation.org/Mention https://climateKG.org/entity/c7e7fb38-44ef-4c5b-aa1d-b3fdcf89d838
    - value: https://climateKG.org/entity/initial_2 http://relation.org/Mention https://climateKG.org/entity/ac392872-1571-4bfd-94dd-81f93d9f1fd0
    - value: https://climateKG.org/entity/initial_3 http://relation.org/Mention https://climateKG.org/entity/a0b26420-3a13-4742-8d6f-391dc5c49d64
    - value: https://climateKG.org/entity/initial_3 http://relation.org/Mention https://climateKG.org/entity/e8df7edd-a176-45c9-8515-3a520948ef63
    - value: https://climateKG.org/entity/e6047f024856646877a812ee5a3f3848a9830b49
        http://relation.org/Mention https://climateKG.org/entity/3bc6fedc-c5a4-4986-bec2-eacc7b75a5dd
    - value: https://climateKG.org/entity/initial_2 http://relation.org/Mention https://climateKG.org/entity/68885007-d975-4f24-bdd5-dd19b246bdf6
    - value: https://climateKG.org/entity/f71f5612d64efcb9af7ebc9cd2e550d6d053e5a7
        http://relation.org/Mention https://climateKG.org/entity/86b8b121-d710-4c5b-84b0-7b40717f6c76
    - value: https://climateKG.org/entity/c3ff320aa72c7e29d067731f19e847505567c120
        http://relation.org/Mention https://climateKG.org/entity/1499785c-8b74-45f4-bbf7-19d2d4e43b2f
    - value: https://climateKG.org/entity/f1c594d8410ba7bf74732bfa710f08a935511a7d
        http://relation.org/Mention https://climateKG.org/entity/7c5420a6-94e2-40ca-9dff-20309090d327
    - value: https://climateKG.org/entity/initial_2 http://relation.org/Mention https://climateKG.org/entity/df0ba39b-7461-4cee-8660-c80fee72e96b
    - value: https://climateKG.org/entity/c3ff320aa72c7e29d067731f19e847505567c120
        http://relation.org/Mention https://climateKG.org/entity/8e4900ff-c7bc-47a1-aa55-a8892696d769
    - value: https://climateKG.org/entity/cd3e2817ca55a23192a862920ac38ad5c06e2adf
        http://relation.org/Mention https://climateKG.org/entity/82a2971f-82eb-46aa-8d70-1343570edba8
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: http://relation.org/Mention
    alias: http___relation.org_Mention
    owner: sdoh_paper
    domain_of:
    - sdoh_paper
    range: Any
    any_of:
    - range: sdoh_Instrument
    - range: sdoh_Measurement_Name
    - range: sdoh_Institution
    - range: sdoh_Data_Format
    - range: sdoh_Frequency
    - range: sdoh_Chronostratigraphic_Unit
    - range: sdoh_Model
    - range: sdoh_Nominal_Resolution
    - range: sdoh_Experiment
    - range: sdoh_Temporal_Resolution_Range
    - range: sdoh_Activity
    - range: sdoh_Variable
    - range: sdoh_Dataset
    - range: sdoh_Cmip6_Source_Id
    - range: sdoh_Horizontal_Resolution_Range
    - range: sdoh_Project
    - range: sdoh_Models
    - range: sdoh_Sub_Experiment_Id
    - range: sdoh_Platform
    - range: sdoh_Related_Url_Content_Type
    - range: sdoh_Provider
    - range: sdoh_Location
    - range: sdoh_Science_Keyword
class_uri: sdoh:paper

```
</details>