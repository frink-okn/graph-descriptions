

# Class: No class name specified (hsdo_Nominal_Resolution)


_No class (type) description specified_





URI: [hsdo:Nominal_Resolution](http://schema.org/Nominal_Resolution)






```mermaid
 classDiagram
    class HsdoNominalResolution
    click HsdoNominalResolution href "../HsdoNominalResolution"
      HsdoNominalResolution : skos_broader
        
          
    
    
    HsdoNominalResolution --> "0..1" Any : skos_broader
    click Any href "../Any"

        
      HsdoNominalResolution : skos_prefLabel
        
          
    
    
    HsdoNominalResolution --> "0..1" String : skos_prefLabel
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [skos_prefLabel](../slots/skos_prefLabel.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 983 occurrences with subject type hsdo_Location and object type string.<br/>2975 occurrences with subject type hsdo_Science_Keyword and object type string.<br/>1171 occurrences with subject type hsdo_Platform and object type string.<br/>24 occurrences with subject type hsdo_Activity and object type string.<br/>150 occurrences with subject type hsdo_Model and object type string.<br/>184 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type string.<br/>444 occurrences with subject type hsdo_Experiment and object type string.<br/>3745 occurrences with subject type hsdo_Provider and object type string.<br/>2363 occurrences with subject type hsdo_Instrument and object type string.<br/>1727 occurrences with subject type hsdo_Project and object type string.<br/>4 occurrences with subject type hsdo_Realm and object type string.<br/>297 occurrences with subject type hsdo_Models and object type string.<br/>234 occurrences with subject type hsdo_Measurement_Name and object type string.<br/>75 occurrences with subject type hsdo_Institution and object type string.<br/>55 occurrences with subject type hsdo_Sub_Experiment_Id and object type string.<br/>198 occurrences with subject type hsdo_Data_Format and object type string.<br/>1283 occurrences with subject type hsdo_Variable and object type string.<br/>134 occurrences with subject type hsdo_Cmip6_Source_Id and object type string.<br/>15 occurrences with subject type hsdo_Horizontal_Resolution_Range and object type string.<br/>5 occurrences with subject type hsdo_Source_Type and object type string.<br/>88 occurrences with subject type hsdo_Related_Url_Content_Type and object type string.<br/>107 occurrences with subject type hsdo_Dataset and object type string.<br/>19 occurrences with subject type hsdo_Temporal_Resolution_Range and object type string.<br/>16 occurrences with subject type hsdo_Nominal_Resolution and object type string.<br/>16 occurrences with subject type hsdo_Frequency and object type string.<br/>4 occurrences with subject type hsdo_License and object type string.<br/>38 occurrences with subject type hsdo_Mime_Type and object type string.<br/>16359 occurrences with subject type skos_Concept and object type string.<br/>6 occurrences with subject type hsdo_Vertical_Resolution_Range and object type string. | direct |
| [skos_broader](../slots/skos_broader.md) | 0..1 <br/> [HsdoMeasurementName](../classes/HsdoMeasurementName.md)&nbsp;or&nbsp;<br />[SkosConcept](../classes/SkosConcept.md)&nbsp;or&nbsp;<br />[HsdoProject](../classes/HsdoProject.md)&nbsp;or&nbsp;<br />[HsdoSubExperimentId](../classes/HsdoSubExperimentId.md)&nbsp;or&nbsp;<br />[HsdoMimeType](../classes/HsdoMimeType.md)&nbsp;or&nbsp;<br />[HsdoRelatedUrlContentType](../classes/HsdoRelatedUrlContentType.md)&nbsp;or&nbsp;<br />[HsdoModels](../classes/HsdoModels.md)&nbsp;or&nbsp;<br />[HsdoPlatform](../classes/HsdoPlatform.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)&nbsp;or&nbsp;<br />[HsdoVariable](../classes/HsdoVariable.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoModel](../classes/HsdoModel.md)&nbsp;or&nbsp;<br />[HsdoInstrument](../classes/HsdoInstrument.md)&nbsp;or&nbsp;<br />[HsdoNominalResolution](../classes/HsdoNominalResolution.md)&nbsp;or&nbsp;<br />[HsdoLocation](../classes/HsdoLocation.md)&nbsp;or&nbsp;<br />[HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md)&nbsp;or&nbsp;<br />[HsdoChronostratigraphicUnit](../classes/HsdoChronostratigraphicUnit.md)&nbsp;or&nbsp;<br />[HsdoTemporalResolutionRange](../classes/HsdoTemporalResolutionRange.md)&nbsp;or&nbsp;<br />[HsdoSourceType](../classes/HsdoSourceType.md)&nbsp;or&nbsp;<br />[HsdoDataFormat](../classes/HsdoDataFormat.md)&nbsp;or&nbsp;<br />[HsdoScienceKeyword](../classes/HsdoScienceKeyword.md)&nbsp;or&nbsp;<br />[HsdoDataset](../classes/HsdoDataset.md) | No slot (predicate) description specified <br/> 2245 occurrences with subject type hsdo_Location and object type hsdo_Location.<br/>261 occurrences with subject type hsdo_Location and object type hsdo_Instrument.<br/>8109 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Science_Keyword.<br/>2953 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Provider.<br/>1937 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Location.<br/>312 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Model.<br/>1761 occurrences with subject type hsdo_Platform and object type hsdo_Instrument.<br/>2153 occurrences with subject type hsdo_Platform and object type hsdo_Platform.<br/>102 occurrences with subject type hsdo_Location and object type hsdo_Project.<br/>48 occurrences with subject type hsdo_Activity and object type hsdo_Project.<br/>40 occurrences with subject type hsdo_Model and object type hsdo_Instrument.<br/>34 occurrences with subject type hsdo_Model and object type hsdo_Platform.<br/>789 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type hsdo_Chronostratigraphic_Unit.<br/>47 occurrences with subject type hsdo_Experiment and object type hsdo_Project.<br/>8707 occurrences with subject type hsdo_Provider and object type hsdo_Provider.<br/>86 occurrences with subject type hsdo_Model and object type hsdo_Project.<br/>6114 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.<br/>2038 occurrences with subject type hsdo_Instrument and object type hsdo_Experiment.<br/>57 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.<br/>475 occurrences with subject type hsdo_Location and object type hsdo_Science_Keyword.<br/>311 occurrences with subject type hsdo_Location and object type hsdo_Provider.<br/>26 occurrences with subject type hsdo_Location and object type hsdo_Model.<br/>3416 occurrences with subject type hsdo_Project and object type hsdo_Project.<br/>4 occurrences with subject type hsdo_Realm and object type hsdo_Location.<br/>304 occurrences with subject type hsdo_Provider and object type hsdo_Location.<br/>180 occurrences with subject type hsdo_Instrument and object type hsdo_Project.<br/>891 occurrences with subject type hsdo_Models and object type hsdo_Science_Keyword.<br/>286 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Instrument.<br/>355 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.<br/>131 occurrences with subject type hsdo_Model and object type hsdo_Science_Keyword.<br/>32 occurrences with subject type hsdo_Model and object type hsdo_Model.<br/>9 occurrences with subject type hsdo_Model and object type hsdo_Experiment.<br/>80 occurrences with subject type hsdo_Model and object type hsdo_Provider.<br/>317 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Instrument.<br/>20 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Location.<br/>75 occurrences with subject type hsdo_Institution and object type hsdo_Provider.<br/>38 occurrences with subject type hsdo_Model and object type hsdo_Location.<br/>12 occurrences with subject type hsdo_Instrument and object type hsdo_Variable.<br/>352 occurrences with subject type hsdo_Instrument and object type hsdo_Science_Keyword.<br/>160 occurrences with subject type hsdo_Instrument and object type hsdo_Provider.<br/>137 occurrences with subject type hsdo_Experiment and object type hsdo_Science_Keyword.<br/>31 occurrences with subject type hsdo_Experiment and object type hsdo_Location.<br/>54 occurrences with subject type hsdo_Sub_Experiment_Id and object type hsdo_Sub_Experiment_Id.<br/>227 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Measurement_Name.<br/>130 occurrences with subject type hsdo_Instrument and object type hsdo_Location.<br/>154 occurrences with subject type hsdo_Provider and object type hsdo_Science_Keyword.<br/>182 occurrences with subject type hsdo_Provider and object type hsdo_Model.<br/>183 occurrences with subject type hsdo_Provider and object type hsdo_Instrument.<br/>43 occurrences with subject type hsdo_Location and object type hsdo_Platform.<br/>242 occurrences with subject type hsdo_Data_Format and object type hsdo_Data_Format.<br/>63 occurrences with subject type hsdo_Location and object type hsdo_Experiment.<br/>1281 occurrences with subject type hsdo_Variable and object type hsdo_Variable.<br/>55 occurrences with subject type hsdo_Platform and object type hsdo_Science_Keyword.<br/>25 occurrences with subject type hsdo_Platform and object type hsdo_Location.<br/>33 occurrences with subject type hsdo_Platform and object type hsdo_Provider.<br/>84 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.<br/>27 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Project.<br/>22 occurrences with subject type hsdo_Provider and object type hsdo_Related_Url_Content_Type.<br/>402 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Science_Keyword.<br/>15 occurrences with subject type hsdo_Provider and object type hsdo_Sub_Experiment_Id.<br/>3 occurrences with subject type hsdo_Model and object type hsdo_Source_Type.<br/>58 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.<br/>6 occurrences with subject type hsdo_Experiment and object type hsdo_Platform.<br/>34 occurrences with subject type hsdo_Instrument and object type hsdo_Model.<br/>5 occurrences with subject type hsdo_Location and object type hsdo_Sub_Experiment_Id.<br/>220 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Experiment.<br/>42 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Platform.<br/>7 occurrences with subject type hsdo_Model and object type hsdo_Variable.<br/>13 occurrences with subject type hsdo_Provider and object type hsdo_Variable.<br/>4 occurrences with subject type hsdo_Provider and object type hsdo_Experiment.<br/>211 occurrences with subject type hsdo_Related_Url_Content_Type and object type hsdo_Related_Url_Content_Type.<br/>106 occurrences with subject type hsdo_Dataset and object type hsdo_Dataset.<br/>26 occurrences with subject type hsdo_Project and object type hsdo_Science_Keyword.<br/>4 occurrences with subject type hsdo_Project and object type hsdo_Location.<br/>15 occurrences with subject type hsdo_Project and object type hsdo_Provider.<br/>4 occurrences with subject type hsdo_Platform and object type hsdo_Experiment.<br/>7 occurrences with subject type hsdo_Location and object type hsdo_Related_Url_Content_Type.<br/>16 occurrences with subject type hsdo_Models and object type hsdo_Instrument.<br/>10 occurrences with subject type hsdo_Location and object type hsdo_Measurement_Name.<br/>1 occurrences with subject type hsdo_Provider and object type hsdo_Source_Type.<br/>14 occurrences with subject type hsdo_Instrument and object type hsdo_Related_Url_Content_Type.<br/>12 occurrences with subject type hsdo_Experiment and object type hsdo_Model.<br/>85 occurrences with subject type hsdo_Platform and object type hsdo_Model.<br/>18 occurrences with subject type hsdo_Temporal_Resolution_Range and object type hsdo_Temporal_Resolution_Range.<br/>4 occurrences with subject type hsdo_Project and object type hsdo_Model.<br/>17 occurrences with subject type hsdo_Platform and object type hsdo_Project.<br/>2 occurrences with subject type hsdo_Experiment and object type hsdo_Variable.<br/>3 occurrences with subject type hsdo_Provider and object type hsdo_Platform.<br/>12 occurrences with subject type hsdo_Location and object type hsdo_Variable.<br/>2 occurrences with subject type hsdo_Institution and object type hsdo_Location.<br/>4 occurrences with subject type hsdo_Source_Type and object type hsdo_Source_Type.<br/>15 occurrences with subject type hsdo_Nominal_Resolution and object type hsdo_Nominal_Resolution.<br/>3 occurrences with subject type hsdo_Experiment and object type hsdo_Source_Type.<br/>16 occurrences with subject type hsdo_Frequency and object type hsdo_Temporal_Resolution_Range.<br/>4 occurrences with subject type hsdo_License and object type hsdo_Instrument.<br/>1 occurrences with subject type hsdo_Instrument and object type hsdo_Models.<br/>3 occurrences with subject type hsdo_Location and object type hsdo_Source_Type.<br/>3 occurrences with subject type hsdo_Model and object type hsdo_Related_Url_Content_Type.<br/>24 occurrences with subject type hsdo_Related_Url_Content_Type and object type hsdo_Provider.<br/>1 occurrences with subject type hsdo_Project and object type hsdo_Experiment.<br/>1 occurrences with subject type hsdo_Project and object type hsdo_Variable.<br/>1 occurrences with subject type hsdo_Model and object type hsdo_Temporal_Resolution_Range.<br/>3 occurrences with subject type hsdo_Models and object type hsdo_Models.<br/>1 occurrences with subject type hsdo_Provider and object type hsdo_Project.<br/>2 occurrences with subject type hsdo_Experiment and object type hsdo_Measurement_Name.<br/>16338 occurrences with subject type skos_Concept and object type skos_Concept.<br/>37 occurrences with subject type hsdo_Mime_Type and object type hsdo_Mime_Type.<br/>14 occurrences with subject type hsdo_Horizontal_Resolution_Range and object type hsdo_Horizontal_Resolution_Range.<br/>6 occurrences with subject type hsdo_Vertical_Resolution_Range and object type hsdo_Variable.<br/>2 occurrences with subject type hsdo_Related_Url_Content_Type and object type hsdo_Instrument. | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HsdoActivity](../classes/HsdoActivity.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoChronostratigraphicUnit](../classes/HsdoChronostratigraphicUnit.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoDataFormat](../classes/HsdoDataFormat.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoDataset](../classes/HsdoDataset.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoExperiment](../classes/HsdoExperiment.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoFrequency](../classes/HsdoFrequency.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoInstitution](../classes/HsdoInstitution.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoInstrument](../classes/HsdoInstrument.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoLicense](../classes/HsdoLicense.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoLocation](../classes/HsdoLocation.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoMeasurementName](../classes/HsdoMeasurementName.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoMimeType](../classes/HsdoMimeType.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoModel](../classes/HsdoModel.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoModels](../classes/HsdoModels.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoNominalResolution](../classes/HsdoNominalResolution.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoPlatform](../classes/HsdoPlatform.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoProject](../classes/HsdoProject.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoProvider](../classes/HsdoProvider.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoRealm](../classes/HsdoRealm.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoRelatedUrlContentType](../classes/HsdoRelatedUrlContentType.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoScienceKeyword](../classes/HsdoScienceKeyword.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoSourceType](../classes/HsdoSourceType.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoSubExperimentId](../classes/HsdoSubExperimentId.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoTemporalResolutionRange](../classes/HsdoTemporalResolutionRange.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoVariable](../classes/HsdoVariable.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoVerticalResolutionRange](../classes/HsdoVerticalResolutionRange.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [HsdoPaper](../classes/HsdoPaper.md) | [relation_Mention](../slots/relation_Mention.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |
| [SkosConcept](../classes/SkosConcept.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoNominalResolution](../classes/HsdoNominalResolution.md) |







## Examples

| Value |
| --- |
| https://climateKG.org/entity/82a2971f-82eb-46aa-8d70-1343570edba8 |


## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:Nominal_Resolution |
| native | climatepub4-kg/:HsdoNominalResolution |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: hsdo_Nominal_Resolution
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class name specified
notes:
- Class with 16 occurrences.
examples:
- value: https://climateKG.org/entity/82a2971f-82eb-46aa-8d70-1343570edba8
from_schema: climatepub4-kg
rank: 1000
slots:
- skos_prefLabel
- skos_broader
class_uri: hsdo:Nominal_Resolution

```
</details>

### Induced

<details>
```yaml
name: hsdo_Nominal_Resolution
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class name specified
notes:
- Class with 16 occurrences.
examples:
- value: https://climateKG.org/entity/82a2971f-82eb-46aa-8d70-1343570edba8
from_schema: climatepub4-kg
rank: 1000
attributes:
  skos_prefLabel:
    name: skos_prefLabel
    description: No slot (predicate) description specified
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
    - description: hsdo_Location → string
      object:
        example_object: LABRADOR_SEA
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/0006e246-4296-448c-9b81-a0831cad7f1c
        example_subject_type: hsdo_Location
    - description: hsdo_Science_Keyword → string
      object:
        example_object: OPTICAL_DEPTH
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/001f18d3-7e61-430b-9883-1960c6256fe5
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Platform → string
      object:
        example_object: Sentinel_1
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/007c3084-89db-458e-8387-14e192b6cb8e
        example_subject_type: hsdo_Platform
    - description: hsdo_Activity → string
      object:
        example_object: SIMIP
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/00a97d0c-e05e-43c9-93d0-3c7a2527b3c0
        example_subject_type: hsdo_Activity
    - description: hsdo_Model → string
      object:
        example_object: RCM_3
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/00bb59aa-755d-4710-a097-f1e2836f4032
        example_subject_type: hsdo_Model
    - description: hsdo_Chronostratigraphic_Unit → string
      object:
        example_object: EARLY
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/00c6f0f3-5734-4500-a69e-f6780e365985
        example_subject_type: hsdo_Chronostratigraphic_Unit
    - description: hsdo_Experiment → string
      object:
        example_object: HAB
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/00ce4800-70ef-4346-aa15-0554280d0896
        example_subject_type: hsdo_Experiment
    - description: hsdo_Provider → string
      object:
        example_object: DOI
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/0111fbd3-e6ec-464a-bc65-2323c2328e7c
        example_subject_type: hsdo_Provider
    - description: hsdo_Instrument → string
      object:
        example_object: HYDRA
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/01407ecf-45af-4fcc-8a1b-9b383636e2e4
        example_subject_type: hsdo_Instrument
    - description: hsdo_Project → string
      object:
        example_object: USNPS_ENVIRONMENTAL_CHANGE_IN_BERINGIAN_ARCTIC
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/01e75216-1cee-4cc3-b31d-83019730da85
        example_subject_type: hsdo_Project
    - description: hsdo_Realm → string
      object:
        example_object: ocnBgchem
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/021d2b85-4728-4434-b429-082874cfab69
        example_subject_type: hsdo_Realm
    - description: hsdo_Models → string
      object:
        example_object: HadGEM2_ES
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/028fe075-8ed0-47f0-b462-71e4adf72a4e
        example_subject_type: hsdo_Models
    - description: hsdo_Measurement_Name → string
      object:
        example_object: ambient_aerosol_particles
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/038ac74c-470a-43e0-b80d-2b2fb1acfc13
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Institution → string
      object:
        example_object: E3SM_Project
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/03976e48-3ff9-4dc6-a4c4-fd77026380ff
        example_subject_type: hsdo_Institution
    - description: hsdo_Sub_Experiment_Id → string
      object:
        example_object: s2016
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/04e00ed0-39b6-4323-a788-2344264695c0
        example_subject_type: hsdo_Sub_Experiment_Id
    - description: hsdo_Data_Format → string
      object:
        example_object: ICI
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/0679d78d-0931-4948-94ec-46ab130785a6
        example_subject_type: hsdo_Data_Format
    - description: hsdo_Variable → string
      object:
        example_object: Point_Resolution
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/0893353d-4e8c-4b31-bcc5-fce552ccfff3
        example_subject_type: hsdo_Variable
    - description: hsdo_Cmip6_Source_Id → string
      object:
        example_object: IPSL_CM5A2_INCA
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/0cd4d2c4-ebfa-4759-b7aa-f9982122f581
        example_subject_type: hsdo_Cmip6_Source_Id
    - description: hsdo_Horizontal_Resolution_Range → string
      object:
        example_object: Horizontal_Resolution_Ranges
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/1499785c-8b74-45f4-bbf7-19d2d4e43b2f
        example_subject_type: hsdo_Horizontal_Resolution_Range
    - description: hsdo_Source_Type → string
      object:
        example_object: Source_Type
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b
        example_subject_type: hsdo_Source_Type
    - description: hsdo_Related_Url_Content_Type → string
      object:
        example_object: GET_CAPABILITIES
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/2892b502-2c66-42d5-af3d-bcddb57d9195
        example_subject_type: hsdo_Related_Url_Content_Type
    - description: hsdo_Dataset → string
      object:
        example_object: ERA_5
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/2892e23f-5249-439d-8c0e-6c1d190b3beb
        example_subject_type: hsdo_Dataset
    - description: hsdo_Temporal_Resolution_Range → string
      object:
        example_object: Decadal
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/3d97e993-dc6a-41ff-8a49-3e837c1fc2b1
        example_subject_type: hsdo_Temporal_Resolution_Range
    - description: hsdo_Nominal_Resolution → string
      object:
        example_object: 10000_km
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/82a2971f-82eb-46aa-8d70-1343570edba8
        example_subject_type: hsdo_Nominal_Resolution
    - description: hsdo_Frequency → string
      object:
        example_object: day
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/8e4900ff-c7bc-47a1-aa55-a8892696d769
        example_subject_type: hsdo_Frequency
    - description: hsdo_License → string
      object:
        example_object: CC_BY_4_0
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428
        example_subject_type: hsdo_License
    - description: hsdo_Mime_Type → string
      object:
        example_object: Mime_Type
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/ec1a1350-be24-42e6-a5cc-ccb806793def
        example_subject_type: hsdo_Mime_Type
    - description: skos_Concept → string
      object:
        example_object: LABRADOR_SEA
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://gcmd.earthdata.nasa.gov/kms/concept/0006e246-4296-448c-9b81-a0831cad7f1c
        example_subject_type: skos_Concept
    - description: hsdo_Vertical_Resolution_Range → string
      object:
        example_object: 1_meter_10_meters
        example_object_type: string
        example_predicate: skos:prefLabel
        example_subject: https://climateKG.org/entity/201337ea-fa14-4e58-a538-e92c5ff734a4
        example_subject_type: hsdo_Vertical_Resolution_Range
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: skos:prefLabel
    alias: skos_prefLabel
    owner: hsdo_Nominal_Resolution
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
  skos_broader:
    name: skos_broader
    description: No slot (predicate) description specified
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
    - description: hsdo_Location → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/713eb469-abe4-4b6b-bad6-134187deabd8
        example_object_type: hsdo_Location
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ffcee960-5527-43e0-bfd0-ad48b1151cf0
        example_subject_type: hsdo_Location
    - description: hsdo_Location → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb
        example_object_type: hsdo_Instrument
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fe4326f9-1089-4ede-ae32-5d7bc7d2349b
        example_subject_type: hsdo_Location
    - description: hsdo_Science_Keyword → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/d64a9627-3cf8-41d3-aaf7-8c2c46fb4a13
        example_object_type: hsdo_Science_Keyword
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ffc61516-ea33-48f3-94df-7065fea388ee
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Science_Keyword → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
        example_object_type: hsdo_Provider
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ffc61516-ea33-48f3-94df-7065fea388ee
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Science_Keyword → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/c47f6052-634e-40ef-a5ac-13f69f6f4c2a
        example_object_type: hsdo_Location
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff9f8056-84d6-4fbc-abe0-9b6e82ed3f5e
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Science_Keyword → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/6f6423e8-ab4e-4572-8982-d9c40f64e28b
        example_object_type: hsdo_Model
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fec6c2e4-ca15-426a-b344-36bba69e5c1f
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Platform → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/f3261de5-34c1-4980-af22-f9d7e7206d12
        example_object_type: hsdo_Instrument
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ffc0ac45-f742-49b2-a51b-000205e38669
        example_subject_type: hsdo_Platform
    - description: hsdo_Platform → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/ef71c514-0fec-4354-bb1e-6baa5967634f
        example_object_type: hsdo_Platform
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ffc0ac45-f742-49b2-a51b-000205e38669
        example_subject_type: hsdo_Platform
    - description: hsdo_Location → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
        example_object_type: hsdo_Project
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fe439b0d-db2c-4998-9890-c11c5c16641f
        example_subject_type: hsdo_Location
    - description: hsdo_Activity → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
        example_object_type: hsdo_Project
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/d7144e27-6122-46e2-8335-b60c49a83248
        example_subject_type: hsdo_Activity
    - description: hsdo_Model → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/085edf65-1c8c-414a-b8e4-a1a08ff08f22
        example_object_type: hsdo_Instrument
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff1ace7a-7924-4198-8385-f7f7ede361c1
        example_subject_type: hsdo_Model
    - description: hsdo_Model → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/b39a69b4-c3b9-4a94-b296-bbbbe5e4c847
        example_object_type: hsdo_Platform
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66
        example_subject_type: hsdo_Model
    - description: hsdo_Chronostratigraphic_Unit → hsdo_Chronostratigraphic_Unit
      object:
        example_object: https://climateKG.org/entity/b44427cd-4b20-42a3-9e14-8d1f6d8399d5
        example_object_type: hsdo_Chronostratigraphic_Unit
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff133a4b-a23a-4710-93d3-2b802b21c8c4
        example_subject_type: hsdo_Chronostratigraphic_Unit
    - description: hsdo_Experiment → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
        example_object_type: hsdo_Project
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/e25399d8-139f-4641-89ee-24d42e9ed81c
        example_subject_type: hsdo_Experiment
    - description: hsdo_Provider → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/b301e170-c91e-4275-9858-d7720fb93416
        example_object_type: hsdo_Provider
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ffaea6a1-8b76-4e2e-a09f-a0280bc0952e
        example_subject_type: hsdo_Provider
    - description: hsdo_Model → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
        example_object_type: hsdo_Project
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fe761190-36bb-4eb1-8d5d-340c4a7f89ea
        example_subject_type: hsdo_Model
    - description: hsdo_Instrument → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/6c0e547e-70cc-47db-8c8c-97c5ba73f1da
        example_object_type: hsdo_Instrument
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fff596a8-f792-4627-8c3a-954012a1969b
        example_subject_type: hsdo_Instrument
    - description: hsdo_Instrument → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/b2140059-b3ca-415c-b0a7-3e142783ffe8
        example_object_type: hsdo_Experiment
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fff596a8-f792-4627-8c3a-954012a1969b
        example_subject_type: hsdo_Instrument
    - description: hsdo_Experiment → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
        example_object_type: hsdo_Provider
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f5df87b6-ed50-4da0-9ba5-7ce4c907bdb3
        example_subject_type: hsdo_Experiment
    - description: hsdo_Location → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/35e1f93b-99b3-4430-b477-0ecafa80d67a
        example_object_type: hsdo_Science_Keyword
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff5d5c12-74d9-435d-9164-1c9d69f967d7
        example_subject_type: hsdo_Location
    - description: hsdo_Location → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
        example_object_type: hsdo_Provider
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff5d5c12-74d9-435d-9164-1c9d69f967d7
        example_subject_type: hsdo_Location
    - description: hsdo_Location → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/23703b6b-ee15-4512-b5b2-f441547e2edf
        example_object_type: hsdo_Model
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f4c1a555-4758-47ce-baa6-536730333833
        example_subject_type: hsdo_Location
    - description: hsdo_Project → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
        example_object_type: hsdo_Project
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ffcca1c5-fffd-4359-b282-e00fc77c979e
        example_subject_type: hsdo_Project
    - description: hsdo_Realm → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/61cd0af2-2f62-4aa4-b6c3-f683e975c820
        example_object_type: hsdo_Location
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/da44d8bd-4896-44c9-ab2b-4ab9ab263c65
        example_subject_type: hsdo_Realm
    - description: hsdo_Provider → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/aef2fc80-def0-46a4-9259-9dc37e80ed08
        example_object_type: hsdo_Location
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fed7e934-6a34-4379-9b57-ad6d49991498
        example_subject_type: hsdo_Provider
    - description: hsdo_Instrument → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
        example_object_type: hsdo_Project
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff25845a-5d94-43c1-abc4-419a108b0f1f
        example_subject_type: hsdo_Instrument
    - description: hsdo_Models → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/e1f20631-b5b9-438c-b5c2-b1fa0fce100a
        example_object_type: hsdo_Science_Keyword
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff7d51fb-85cb-4350-8817-b4121cf72357
        example_subject_type: hsdo_Models
    - description: hsdo_Science_Keyword → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/431eca76-9d34-4f86-b1d3-a0b40221e905
        example_object_type: hsdo_Instrument
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff889b84-e12f-40ab-815b-61d5aecf2b63
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Experiment → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/d69f7457-db31-48ce-b8c2-98058c412bc6
        example_object_type: hsdo_Experiment
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9
        example_subject_type: hsdo_Experiment
    - description: hsdo_Model → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/fb93d937-c17c-45d0-a9e3-ca5c8a800ca8
        example_object_type: hsdo_Science_Keyword
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff1ace7a-7924-4198-8385-f7f7ede361c1
        example_subject_type: hsdo_Model
    - description: hsdo_Model → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/8eb84f36-f355-458b-889f-b37cfa120654
        example_object_type: hsdo_Model
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f8845bec-c628-4185-aac1-4af22481c024
        example_subject_type: hsdo_Model
    - description: hsdo_Model → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/a956d045-3b12-441c-8a18-fac7d33b2b4e
        example_object_type: hsdo_Experiment
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/e5b724af-b661-406a-ae1f-7cd2730c0576
        example_subject_type: hsdo_Model
    - description: hsdo_Model → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
        example_object_type: hsdo_Provider
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff1ace7a-7924-4198-8385-f7f7ede361c1
        example_subject_type: hsdo_Model
    - description: hsdo_Measurement_Name → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/e384382c-fb2a-43ea-b064-610e6d4807e9
        example_object_type: hsdo_Instrument
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ffcda4b1-0956-4413-a4c9-8d72b5dffb58
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Measurement_Name → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/369c608c-787a-4ca6-8811-cc8eca7447d5
        example_object_type: hsdo_Location
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fcb181b4-4732-4752-b70d-bbcc81fcdc59
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Institution → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/a158f804-b000-4013-9513-cee7790381c3
        example_object_type: hsdo_Provider
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/bf904092-467c-468e-99da-8722f9141204
        example_subject_type: hsdo_Institution
    - description: hsdo_Model → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/91c64c46-d040-4daa-b26c-61952fdfaf50
        example_object_type: hsdo_Location
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f8845bec-c628-4185-aac1-4af22481c024
        example_subject_type: hsdo_Model
    - description: hsdo_Instrument → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
        example_object_type: hsdo_Variable
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/b3416c55-cdff-4e8b-89af-a9b219a9e538
        example_subject_type: hsdo_Instrument
    - description: hsdo_Instrument → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/e1f20631-b5b9-438c-b5c2-b1fa0fce100a
        example_object_type: hsdo_Science_Keyword
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fe4392b0-13a9-43ff-bacc-f44a65aed4fa
        example_subject_type: hsdo_Instrument
    - description: hsdo_Instrument → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
        example_object_type: hsdo_Provider
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fe06f678-7155-4f93-9e28-4c083d60cccc
        example_subject_type: hsdo_Instrument
    - description: hsdo_Experiment → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/b6fd22ab-dca7-4dfa-8812-913453b5695b
        example_object_type: hsdo_Science_Keyword
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f5df87b6-ed50-4da0-9ba5-7ce4c907bdb3
        example_subject_type: hsdo_Experiment
    - description: hsdo_Experiment → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/91697b7d-8f2b-4954-850e-61d5f61c867d
        example_object_type: hsdo_Location
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f5df87b6-ed50-4da0-9ba5-7ce4c907bdb3
        example_subject_type: hsdo_Experiment
    - description: hsdo_Sub_Experiment_Id → hsdo_Sub_Experiment_Id
      object:
        example_object: https://climateKG.org/entity/2eecd388-25be-4367-90c6-0d683ef476ac
        example_object_type: hsdo_Sub_Experiment_Id
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fc01908a-f93e-46e6-9f85-5b428b8d2b8d
        example_subject_type: hsdo_Sub_Experiment_Id
    - description: hsdo_Measurement_Name → hsdo_Measurement_Name
      object:
        example_object: https://climateKG.org/entity/1f697c83-969d-48ee-87b8-245b11f7e24f
        example_object_type: hsdo_Measurement_Name
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ffcda4b1-0956-4413-a4c9-8d72b5dffb58
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Instrument → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/713eb469-abe4-4b6b-bad6-134187deabd8
        example_object_type: hsdo_Location
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb
        example_subject_type: hsdo_Instrument
    - description: hsdo_Provider → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/d35b9ba5-d018-48a5-8f0d-92b9c55b3279
        example_object_type: hsdo_Science_Keyword
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff850d62-675c-4386-a375-fe4af92ec3ff
        example_subject_type: hsdo_Provider
    - description: hsdo_Provider → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/5fea4160-25a7-44b5-bfba-ef140fdffaf4
        example_object_type: hsdo_Model
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff2f2855-6cdd-4bf0-a4ea-5aa61698d765
        example_subject_type: hsdo_Provider
    - description: hsdo_Provider → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/5527d704-a0fe-45ab-99f9-90fa64f4af7f
        example_object_type: hsdo_Instrument
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/feab952c-49ca-41c1-a2a0-b35bf4dd7048
        example_subject_type: hsdo_Provider
    - description: hsdo_Location → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/b39a69b4-c3b9-4a94-b296-bbbbe5e4c847
        example_object_type: hsdo_Platform
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f62c196b-8ec3-40e8-a824-6849e5a496f2
        example_subject_type: hsdo_Location
    - description: hsdo_Data_Format → hsdo_Data_Format
      object:
        example_object: https://climateKG.org/entity/bb6184eb-1ced-44fb-9668-d57cf1baa2e3
        example_object_type: hsdo_Data_Format
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fd79ac2d-c42e-4f3d-9aa1-d5ae94d4d2e3
        example_subject_type: hsdo_Data_Format
    - description: hsdo_Location → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
        example_object_type: hsdo_Experiment
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fbe91a4f-4d27-4cfe-ba1b-69a62e359a3d
        example_subject_type: hsdo_Location
    - description: hsdo_Variable → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
        example_object_type: hsdo_Variable
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ffb483cf-a660-4ec1-b470-304efce6005d
        example_subject_type: hsdo_Variable
    - description: hsdo_Platform → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/fb93d937-c17c-45d0-a9e3-ca5c8a800ca8
        example_object_type: hsdo_Science_Keyword
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fee25cad-7ffe-4ee2-a6f2-8116b8a0a707
        example_subject_type: hsdo_Platform
    - description: hsdo_Platform → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/d62db12c-fdcf-40ec-a714-4fb7c615aebe
        example_object_type: hsdo_Location
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f9846838-fdbc-4aa0-86e9-b0e70e97d0e2
        example_subject_type: hsdo_Platform
    - description: hsdo_Platform → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
        example_object_type: hsdo_Provider
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fee25cad-7ffe-4ee2-a6f2-8116b8a0a707
        example_subject_type: hsdo_Platform
    - description: hsdo_Instrument → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/267606d3-4918-4651-b40d-be12b09dd2fe
        example_object_type: hsdo_Platform
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fbcd0c2b-f8ac-4199-9a37-5e7a39150730
        example_subject_type: hsdo_Instrument
    - description: hsdo_Science_Keyword → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
        example_object_type: hsdo_Project
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fd19a3f1-8eeb-49ab-bcaf-e7b4b267d415
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Provider → hsdo_Related_Url_Content_Type
      object:
        example_object: https://climateKG.org/entity/894edd57-afb3-4bb3-878f-fc245d8b6e82
        example_object_type: hsdo_Related_Url_Content_Type
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/d1996d91-e824-4b24-b94e-3aae4543b63b
        example_subject_type: hsdo_Provider
    - description: hsdo_Cmip6_Source_Id → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/e1f20631-b5b9-438c-b5c2-b1fa0fce100a
        example_object_type: hsdo_Science_Keyword
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7
        example_subject_type: hsdo_Cmip6_Source_Id
    - description: hsdo_Provider → hsdo_Sub_Experiment_Id
      object:
        example_object: https://climateKG.org/entity/2eecd388-25be-4367-90c6-0d683ef476ac
        example_object_type: hsdo_Sub_Experiment_Id
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/dcbcdf6d-f4d7-4040-b7a5-07c46587b4bc
        example_subject_type: hsdo_Provider
    - description: hsdo_Model → hsdo_Source_Type
      object:
        example_object: https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b
        example_object_type: hsdo_Source_Type
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/bae77e96-ede8-44ab-8035-31feb2527fad
        example_subject_type: hsdo_Model
    - description: hsdo_Experiment → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/2bc6e372-93d8-4672-96b1-ec159aff2e19
        example_object_type: hsdo_Instrument
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Experiment → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/e8baa3a4-ef5a-455a-bf25-d61e59fc9bb3
        example_object_type: hsdo_Platform
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f80b13a8-7692-4d1a-be08-851544cd0cde
        example_subject_type: hsdo_Experiment
    - description: hsdo_Instrument → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/23703b6b-ee15-4512-b5b2-f441547e2edf
        example_object_type: hsdo_Model
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fe06f678-7155-4f93-9e28-4c083d60cccc
        example_subject_type: hsdo_Instrument
    - description: hsdo_Location → hsdo_Sub_Experiment_Id
      object:
        example_object: https://climateKG.org/entity/2eecd388-25be-4367-90c6-0d683ef476ac
        example_object_type: hsdo_Sub_Experiment_Id
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/c129a8c2-b9d5-4405-914f-a6949a8e7b5a
        example_subject_type: hsdo_Location
    - description: hsdo_Science_Keyword → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/c7245882-84a1-4192-acfa-a758b5b9c151
        example_object_type: hsdo_Experiment
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fed291ec-8f7d-4131-a5cd-dc04706f61b0
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Science_Keyword → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/cc9e67fc-eafa-43cc-879f-0cb56b25bc39
        example_object_type: hsdo_Platform
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f2295f39-e8c5-4032-8a05-618d95410b28
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Model → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
        example_object_type: hsdo_Variable
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f860ed88-991f-4b52-90b9-fc8d4046a598
        example_subject_type: hsdo_Model
    - description: hsdo_Provider → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
        example_object_type: hsdo_Variable
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fe950f88-6d5e-4741-8076-3fbe16b0b9c4
        example_subject_type: hsdo_Provider
    - description: hsdo_Provider → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/bd1834b0-4f8f-4616-b330-6205bff567c2
        example_object_type: hsdo_Experiment
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/e91ff41a-5cf5-460b-b765-c553ca2a4ae2
        example_subject_type: hsdo_Provider
    - description: hsdo_Related_Url_Content_Type → hsdo_Related_Url_Content_Type
      object:
        example_object: https://climateKG.org/entity/894edd57-afb3-4bb3-878f-fc245d8b6e82
        example_object_type: hsdo_Related_Url_Content_Type
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fd01f7ec-fdf6-4440-b974-75f12fb4ec5f
        example_subject_type: hsdo_Related_Url_Content_Type
    - description: hsdo_Dataset → hsdo_Dataset
      object:
        example_object: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
        example_object_type: hsdo_Dataset
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fe64cea2-19de-470c-a919-b24c744c696b
        example_subject_type: hsdo_Dataset
    - description: hsdo_Project → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/fb93d937-c17c-45d0-a9e3-ca5c8a800ca8
        example_object_type: hsdo_Science_Keyword
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f69374fe-eda2-4223-b130-096220251235
        example_subject_type: hsdo_Project
    - description: hsdo_Project → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/c47f6052-634e-40ef-a5ac-13f69f6f4c2a
        example_object_type: hsdo_Location
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/7cacbfdf-71a3-4fac-b690-9aa54e4060dd
        example_subject_type: hsdo_Project
    - description: hsdo_Project → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/e9f67a66-e9fc-435c-b720-ae32a2c3d8f5
        example_object_type: hsdo_Provider
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f69374fe-eda2-4223-b130-096220251235
        example_subject_type: hsdo_Project
    - description: hsdo_Platform → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
        example_object_type: hsdo_Experiment
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/d609fc5c-8267-4e79-84ec-93629d52aba8
        example_subject_type: hsdo_Platform
    - description: hsdo_Location → hsdo_Related_Url_Content_Type
      object:
        example_object: https://climateKG.org/entity/8759ab63-ac04-4136-bc25-0c00eece1096
        example_object_type: hsdo_Related_Url_Content_Type
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/e5803df8-c802-4f3f-96f5-53e534835887
        example_subject_type: hsdo_Location
    - description: hsdo_Models → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/fe4392b0-13a9-43ff-bacc-f44a65aed4fa
        example_object_type: hsdo_Instrument
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fdd890fa-377a-46ce-8fdc-2d7d16a461b7
        example_subject_type: hsdo_Models
    - description: hsdo_Location → hsdo_Measurement_Name
      object:
        example_object: https://climateKG.org/entity/67cc1cc2-04b9-4763-8e73-fb028f45baab
        example_object_type: hsdo_Measurement_Name
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fb3ca6d5-ab16-413b-80f6-c2e2d50ec4c0
        example_subject_type: hsdo_Location
    - description: hsdo_Provider → hsdo_Source_Type
      object:
        example_object: https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b
        example_object_type: hsdo_Source_Type
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/3b16a2e8-cc4d-40ce-a6c8-336bea211078
        example_subject_type: hsdo_Provider
    - description: hsdo_Instrument → hsdo_Related_Url_Content_Type
      object:
        example_object: https://climateKG.org/entity/894edd57-afb3-4bb3-878f-fc245d8b6e82
        example_object_type: hsdo_Related_Url_Content_Type
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fcc9411c-a1c9-415d-a16c-75c42f2cec45
        example_subject_type: hsdo_Instrument
    - description: hsdo_Experiment → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/23703b6b-ee15-4512-b5b2-f441547e2edf
        example_object_type: hsdo_Model
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/eaa0bc43-e283-4bf1-ba20-ca32850a66ef
        example_subject_type: hsdo_Experiment
    - description: hsdo_Platform → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/0a184cdc-c074-4946-90a6-02f03c686341
        example_object_type: hsdo_Model
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fe979e09-fcb1-4991-8fab-8ff32a28e84b
        example_subject_type: hsdo_Platform
    - description: hsdo_Temporal_Resolution_Range → hsdo_Temporal_Resolution_Range
      object:
        example_object: https://climateKG.org/entity/502ad03c-dba8-4b32-8af5-13fa947c3988
        example_object_type: hsdo_Temporal_Resolution_Range
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f86e464a-cf9d-4e15-a39b-501855d1dc5a
        example_subject_type: hsdo_Temporal_Resolution_Range
    - description: hsdo_Project → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/22ec2f9b-1f1a-469b-bc09-851d58637ff4
        example_object_type: hsdo_Model
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/be7f6de0-f51e-42bc-9a66-fff30d809a67
        example_subject_type: hsdo_Project
    - description: hsdo_Platform → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/fb0b9fcd-5c96-4989-8c64-a479bbed83ab
        example_object_type: hsdo_Project
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/db7e4e2a-f55a-4515-bdd9-c5bc48e3c6d9
        example_subject_type: hsdo_Platform
    - description: hsdo_Experiment → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
        example_object_type: hsdo_Variable
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/d4b91aac-8ca8-44e8-8854-ceae0cf3bc4e
        example_subject_type: hsdo_Experiment
    - description: hsdo_Provider → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/0a454dc9-de56-4682-8688-36ffd547d42f
        example_object_type: hsdo_Platform
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ab7eb13f-5fcb-4afa-8819-c37d36feeec1
        example_subject_type: hsdo_Provider
    - description: hsdo_Location → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
        example_object_type: hsdo_Variable
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f90ae98a-cdfb-490a-ba47-0186d69b4f8c
        example_subject_type: hsdo_Location
    - description: hsdo_Institution → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/aef2fc80-def0-46a4-9259-9dc37e80ed08
        example_object_type: hsdo_Location
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/7cf22186-281a-4665-b79b-5a6e5ea5b471
        example_subject_type: hsdo_Institution
    - description: hsdo_Source_Type → hsdo_Source_Type
      object:
        example_object: https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b
        example_object_type: hsdo_Source_Type
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ff7b2b19-a8f6-4e84-a2c7-f2256199e13c
        example_subject_type: hsdo_Source_Type
    - description: hsdo_Nominal_Resolution → hsdo_Nominal_Resolution
      object:
        example_object: https://climateKG.org/entity/c059a189-5d19-42f1-8a3a-1d0154da17dd
        example_object_type: hsdo_Nominal_Resolution
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ef23b094-00f7-4ad3-8a9c-fa4ab8666c12
        example_subject_type: hsdo_Nominal_Resolution
    - description: hsdo_Experiment → hsdo_Source_Type
      object:
        example_object: https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b
        example_object_type: hsdo_Source_Type
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/cd77430e-8e10-4581-b36e-e2db1124c34f
        example_subject_type: hsdo_Experiment
    - description: hsdo_Frequency → hsdo_Temporal_Resolution_Range
      object:
        example_object: https://climateKG.org/entity/502ad03c-dba8-4b32-8af5-13fa947c3988
        example_object_type: hsdo_Temporal_Resolution_Range
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fb3ad06c-6a16-494b-a539-87da59e25c54
        example_subject_type: hsdo_Frequency
    - description: hsdo_License → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/3c937799-5ee5-4ea3-b7d5-418a625a7872
        example_object_type: hsdo_Instrument
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/9e36c429-c63a-48d8-8e94-caab8195f034
        example_subject_type: hsdo_License
    - description: hsdo_Instrument → hsdo_Models
      object:
        example_object: https://climateKG.org/entity/35d2677c-619a-4a47-a5a7-3feb9973c5ab
        example_object_type: hsdo_Models
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/a68048f4-181c-4c6c-9bfa-9e4171e9f237
        example_subject_type: hsdo_Instrument
    - description: hsdo_Location → hsdo_Source_Type
      object:
        example_object: https://climateKG.org/entity/27a62e86-0b64-4e21-9766-cfdcd95ff87b
        example_object_type: hsdo_Source_Type
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/e8c6761b-0653-495c-82e9-feb685344542
        example_subject_type: hsdo_Location
    - description: hsdo_Model → hsdo_Related_Url_Content_Type
      object:
        example_object: https://climateKG.org/entity/894edd57-afb3-4bb3-878f-fc245d8b6e82
        example_object_type: hsdo_Related_Url_Content_Type
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/ab2fce71-e5f9-4ba6-bfb1-bc428a8b7dd8
        example_subject_type: hsdo_Model
    - description: hsdo_Related_Url_Content_Type → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/750f6c61-0f15-4185-94d8-c029dec04bc5
        example_object_type: hsdo_Provider
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/da43d7e4-4cb4-4b65-a9a1-94bf542f96de
        example_subject_type: hsdo_Related_Url_Content_Type
    - description: hsdo_Project → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/a956d045-3b12-441c-8a18-fac7d33b2b4e
        example_object_type: hsdo_Experiment
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/be7f6de0-f51e-42bc-9a66-fff30d809a67
        example_subject_type: hsdo_Project
    - description: hsdo_Project → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
        example_object_type: hsdo_Variable
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/c819d2c9-fb81-4ce5-9737-ae8ea19690a2
        example_subject_type: hsdo_Project
    - description: hsdo_Model → hsdo_Temporal_Resolution_Range
      object:
        example_object: https://climateKG.org/entity/502ad03c-dba8-4b32-8af5-13fa947c3988
        example_object_type: hsdo_Temporal_Resolution_Range
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/e0040d4b-e398-4b65-bd42-d39434b5cc95
        example_subject_type: hsdo_Model
    - description: hsdo_Models → hsdo_Models
      object:
        example_object: https://climateKG.org/entity/8cf3a3ce-4dd4-4364-8414-83e3b01354ec
        example_object_type: hsdo_Models
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/3165b02f-962f-48bf-944b-66dd470f5988
        example_subject_type: hsdo_Models
    - description: hsdo_Provider → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
        example_object_type: hsdo_Project
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f634ab55-de40-4d0b-93bc-691bf5408ccb
        example_subject_type: hsdo_Provider
    - description: hsdo_Experiment → hsdo_Measurement_Name
      object:
        example_object: https://climateKG.org/entity/5b2a974e-0461-4eb1-86bd-807a29dccfc9
        example_object_type: hsdo_Measurement_Name
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: skos_Concept → skos_Concept
      object:
        example_object: https://gcmd.earthdata.nasa.gov/kms/concept/a31c2828-9b6d-44e9-b6ad-7ae81030f322
        example_object_type: skos_Concept
        example_predicate: skos:broader
        example_subject: https://gcmd.earthdata.nasa.gov/kms/concept/ffff565f-15e9-4d15-a840-05c1a44fd2bf
        example_subject_type: skos_Concept
    - description: hsdo_Mime_Type → hsdo_Mime_Type
      object:
        example_object: https://climateKG.org/entity/ec1a1350-be24-42e6-a5cc-ccb806793def
        example_object_type: hsdo_Mime_Type
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/fea4e0a7-d794-481d-9915-52f1be226714
        example_subject_type: hsdo_Mime_Type
    - description: hsdo_Horizontal_Resolution_Range → hsdo_Horizontal_Resolution_Range
      object:
        example_object: https://climateKG.org/entity/1499785c-8b74-45f4-bbf7-19d2d4e43b2f
        example_object_type: hsdo_Horizontal_Resolution_Range
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/e5c4876e-47b7-4d53-90a2-081a6b150140
        example_subject_type: hsdo_Horizontal_Resolution_Range
    - description: hsdo_Vertical_Resolution_Range → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/9728ca44-7bb3-40a4-9dd2-49470ad47fa5
        example_object_type: hsdo_Variable
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/eccf8700-c503-46a3-b6f7-86cf7e48465a
        example_subject_type: hsdo_Vertical_Resolution_Range
    - description: hsdo_Related_Url_Content_Type → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/3c9d4493-22fd-48a8-9af5-bf0d16b7ede5
        example_object_type: hsdo_Instrument
        example_predicate: skos:broader
        example_subject: https://climateKG.org/entity/f02b0c6a-7fd9-473d-a1cb-a6482e8daa61
        example_subject_type: hsdo_Related_Url_Content_Type
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: skos:broader
    alias: skos_broader
    owner: hsdo_Nominal_Resolution
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
    - range: hsdo_Measurement_Name
    - range: skos_Concept
    - range: hsdo_Project
    - range: hsdo_Sub_Experiment_Id
    - range: hsdo_Mime_Type
    - range: hsdo_Related_Url_Content_Type
    - range: hsdo_Models
    - range: hsdo_Platform
    - range: hsdo_Experiment
    - range: hsdo_Variable
    - range: hsdo_Provider
    - range: hsdo_Model
    - range: hsdo_Instrument
    - range: hsdo_Nominal_Resolution
    - range: hsdo_Location
    - range: hsdo_Horizontal_Resolution_Range
    - range: hsdo_Chronostratigraphic_Unit
    - range: hsdo_Temporal_Resolution_Range
    - range: hsdo_Source_Type
    - range: hsdo_Data_Format
    - range: hsdo_Science_Keyword
    - range: hsdo_Dataset
class_uri: hsdo:Nominal_Resolution

```
</details>