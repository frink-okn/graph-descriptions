

# Class: No class (type) name specified (hsdo_Horizontal_Resolution_Range)


_No class (type) description specified_





URI: [hsdo:Horizontal_Resolution_Range](http://schema.org/Horizontal_Resolution_Range)






```mermaid
 classDiagram
    class HsdoHorizontalResolutionRange
    click HsdoHorizontalResolutionRange href "../HsdoHorizontalResolutionRange"
      HsdoHorizontalResolutionRange : relation_MeasuredAt
        
          
    
    
    HsdoHorizontalResolutionRange --> "0..1" Any : relation_MeasuredAt
    click Any href "../Any"

        
      HsdoHorizontalResolutionRange : skos_broader
        
          
    
    
    HsdoHorizontalResolutionRange --> "0..1" Any : skos_broader
    click Any href "../Any"

        
      HsdoHorizontalResolutionRange : skos_prefLabel
        
          
    
    
    HsdoHorizontalResolutionRange --> "0..1" String : skos_prefLabel
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [relation_MeasuredAt](../slots/relation_MeasuredAt.md) | 0..1 <br/> [HsdoMeasurementName](../classes/HsdoMeasurementName.md)&nbsp;or&nbsp;<br />[HsdoProject](../classes/HsdoProject.md)&nbsp;or&nbsp;<br />[HsdoSubExperimentId](../classes/HsdoSubExperimentId.md)&nbsp;or&nbsp;<br />[HsdoActivity](../classes/HsdoActivity.md)&nbsp;or&nbsp;<br />[HsdoRelatedUrlContentType](../classes/HsdoRelatedUrlContentType.md)&nbsp;or&nbsp;<br />[HsdoModels](../classes/HsdoModels.md)&nbsp;or&nbsp;<br />[HsdoPlatform](../classes/HsdoPlatform.md)&nbsp;or&nbsp;<br />[HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)&nbsp;or&nbsp;<br />[HsdoVariable](../classes/HsdoVariable.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoModel](../classes/HsdoModel.md)&nbsp;or&nbsp;<br />[HsdoInstrument](../classes/HsdoInstrument.md)&nbsp;or&nbsp;<br />[HsdoLocation](../classes/HsdoLocation.md)&nbsp;or&nbsp;<br />[HsdoChronostratigraphicUnit](../classes/HsdoChronostratigraphicUnit.md)&nbsp;or&nbsp;<br />[HsdoTemporalResolutionRange](../classes/HsdoTemporalResolutionRange.md)&nbsp;or&nbsp;<br />[HsdoDataFormat](../classes/HsdoDataFormat.md)&nbsp;or&nbsp;<br />[HsdoScienceKeyword](../classes/HsdoScienceKeyword.md)&nbsp;or&nbsp;<br />[HsdoDataset](../classes/HsdoDataset.md) | No slot (predicate) description specified <br/> 542 occurrences with subject type hsdo_Location and object type hsdo_Location.<br/>71 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Science_Keyword.<br/>150 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Instrument.<br/>240 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Location.<br/>76 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Experiment.<br/>10 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Platform.<br/>43 occurrences with subject type hsdo_Experiment and object type hsdo_Science_Keyword.<br/>128 occurrences with subject type hsdo_Experiment and object type hsdo_Location.<br/>73 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.<br/>49 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.<br/>9 occurrences with subject type hsdo_Experiment and object type hsdo_Model.<br/>108 occurrences with subject type hsdo_Location and object type hsdo_Experiment.<br/>44 occurrences with subject type hsdo_Project and object type hsdo_Location.<br/>20 occurrences with subject type hsdo_Project and object type hsdo_Experiment.<br/>349 occurrences with subject type hsdo_Instrument and object type hsdo_Location.<br/>10 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Provider.<br/>4 occurrences with subject type hsdo_Project and object type hsdo_Project.<br/>15 occurrences with subject type hsdo_Model and object type hsdo_Science_Keyword.<br/>41 occurrences with subject type hsdo_Model and object type hsdo_Location.<br/>15 occurrences with subject type hsdo_Model and object type hsdo_Experiment.<br/>27 occurrences with subject type hsdo_Model and object type hsdo_Instrument.<br/>178 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.<br/>14 occurrences with subject type hsdo_Instrument and object type hsdo_Model.<br/>15 occurrences with subject type hsdo_Location and object type hsdo_Measurement_Name.<br/>223 occurrences with subject type hsdo_Location and object type hsdo_Instrument.<br/>64 occurrences with subject type hsdo_Location and object type hsdo_Science_Keyword.<br/>9 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.<br/>17 occurrences with subject type hsdo_Instrument and object type hsdo_Provider.<br/>15 occurrences with subject type hsdo_Instrument and object type hsdo_Measurement_Name.<br/>91 occurrences with subject type hsdo_Instrument and object type hsdo_Experiment.<br/>5 occurrences with subject type hsdo_Project and object type hsdo_Model.<br/>16 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Model.<br/>93 occurrences with subject type hsdo_Instrument and object type hsdo_Science_Keyword.<br/>2 occurrences with subject type hsdo_Models and object type hsdo_Chronostratigraphic_Unit.<br/>8 occurrences with subject type hsdo_Models and object type hsdo_Instrument.<br/>1 occurrences with subject type hsdo_Models and object type hsdo_Project.<br/>13 occurrences with subject type hsdo_Project and object type hsdo_Science_Keyword.<br/>1 occurrences with subject type hsdo_Experiment and object type hsdo_Activity.<br/>10 occurrences with subject type hsdo_Location and object type hsdo_Data_Format.<br/>61 occurrences with subject type hsdo_Provider and object type hsdo_Location.<br/>11 occurrences with subject type hsdo_Instrument and object type hsdo_Project.<br/>2 occurrences with subject type hsdo_Instrument and object type hsdo_Data_Format.<br/>27 occurrences with subject type hsdo_Variable and object type hsdo_Instrument.<br/>7 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Chronostratigraphic_Unit.<br/>11 occurrences with subject type hsdo_Location and object type hsdo_Chronostratigraphic_Unit.<br/>32 occurrences with subject type hsdo_Location and object type hsdo_Provider.<br/>7 occurrences with subject type hsdo_Variable and object type hsdo_Model.<br/>5 occurrences with subject type hsdo_Platform and object type hsdo_Science_Keyword.<br/>30 occurrences with subject type hsdo_Platform and object type hsdo_Location.<br/>21 occurrences with subject type hsdo_Platform and object type hsdo_Instrument.<br/>12 occurrences with subject type hsdo_Platform and object type hsdo_Experiment.<br/>17 occurrences with subject type hsdo_Provider and object type hsdo_Experiment.<br/>29 occurrences with subject type hsdo_Provider and object type hsdo_Instrument.<br/>7 occurrences with subject type hsdo_Location and object type hsdo_Platform.<br/>13 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Project.<br/>17 occurrences with subject type hsdo_Location and object type hsdo_Variable.<br/>3 occurrences with subject type hsdo_Model and object type hsdo_Model.<br/>2 occurrences with subject type hsdo_Data_Format and object type hsdo_Experiment.<br/>1 occurrences with subject type hsdo_Data_Format and object type hsdo_Chronostratigraphic_Unit.<br/>5 occurrences with subject type hsdo_Data_Format and object type hsdo_Instrument.<br/>9 occurrences with subject type hsdo_Experiment and object type hsdo_Variable.<br/>16 occurrences with subject type hsdo_Location and object type hsdo_Project.<br/>20 occurrences with subject type hsdo_Location and object type hsdo_Model.<br/>1 occurrences with subject type hsdo_Horizontal_Resolution_Range and object type hsdo_Location.<br/>5 occurrences with subject type hsdo_Variable and object type hsdo_Models.<br/>12 occurrences with subject type hsdo_Variable and object type hsdo_Experiment.<br/>6 occurrences with subject type hsdo_Experiment and object type hsdo_Project.<br/>12 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.<br/>27 occurrences with subject type hsdo_Project and object type hsdo_Instrument.<br/>23 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Location.<br/>4 occurrences with subject type hsdo_Model and object type hsdo_Variable.<br/>1 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Data_Format.<br/>7 occurrences with subject type hsdo_Instrument and object type hsdo_Chronostratigraphic_Unit.<br/>23 occurrences with subject type hsdo_Location and object type hsdo_Models.<br/>6 occurrences with subject type hsdo_Models and object type hsdo_Variable.<br/>36 occurrences with subject type hsdo_Variable and object type hsdo_Location.<br/>5 occurrences with subject type hsdo_Variable and object type hsdo_Science_Keyword.<br/>6 occurrences with subject type hsdo_Variable and object type hsdo_Provider.<br/>10 occurrences with subject type hsdo_Provider and object type hsdo_Science_Keyword.<br/>16 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Instrument.<br/>2 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Platform.<br/>6 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Science_Keyword.<br/>5 occurrences with subject type hsdo_Provider and object type hsdo_Project.<br/>2 occurrences with subject type hsdo_Model and object type hsdo_Project.<br/>6 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Measurement_Name.<br/>5 occurrences with subject type hsdo_Instrument and object type hsdo_Models.<br/>3 occurrences with subject type hsdo_Provider and object type hsdo_Model.<br/>15 occurrences with subject type hsdo_Instrument and object type hsdo_Variable.<br/>2 occurrences with subject type hsdo_Dataset and object type hsdo_Location.<br/>3 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Measurement_Name.<br/>1 occurrences with subject type hsdo_Project and object type hsdo_Platform.<br/>3 occurrences with subject type hsdo_Location and object type hsdo_Related_Url_Content_Type.<br/>7 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Models.<br/>8 occurrences with subject type hsdo_Variable and object type hsdo_Chronostratigraphic_Unit.<br/>2 occurrences with subject type hsdo_Variable and object type hsdo_Platform.<br/>2 occurrences with subject type hsdo_Variable and object type hsdo_Variable.<br/>1 occurrences with subject type hsdo_Variable and object type hsdo_Data_Format.<br/>1 occurrences with subject type hsdo_Project and object type hsdo_Provider.<br/>2 occurrences with subject type hsdo_Project and object type hsdo_Models.<br/>3 occurrences with subject type hsdo_Models and object type hsdo_Experiment.<br/>1 occurrences with subject type hsdo_Model and object type hsdo_Provider.<br/>4 occurrences with subject type hsdo_Provider and object type hsdo_Models.<br/>2 occurrences with subject type hsdo_Models and object type hsdo_Location.<br/>2 occurrences with subject type hsdo_Institution and object type hsdo_Variable.<br/>1 occurrences with subject type hsdo_Project and object type hsdo_Chronostratigraphic_Unit.<br/>3 occurrences with subject type hsdo_Location and object type hsdo_Dataset.<br/>5 occurrences with subject type hsdo_Related_Url_Content_Type and object type hsdo_Location.<br/>3 occurrences with subject type hsdo_Related_Url_Content_Type and object type hsdo_Instrument.<br/>1 occurrences with subject type hsdo_Related_Url_Content_Type and object type hsdo_Experiment.<br/>5 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Variable.<br/>6 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Experiment.<br/>3 occurrences with subject type hsdo_Activity and object type hsdo_Variable.<br/>4 occurrences with subject type hsdo_Experiment and object type hsdo_Data_Format.<br/>2 occurrences with subject type hsdo_Project and object type hsdo_Measurement_Name.<br/>2 occurrences with subject type hsdo_Model and object type hsdo_Measurement_Name.<br/>2 occurrences with subject type hsdo_Platform and object type hsdo_Provider.<br/>1 occurrences with subject type hsdo_Experiment and object type hsdo_Chronostratigraphic_Unit.<br/>2 occurrences with subject type hsdo_Experiment and object type hsdo_Measurement_Name.<br/>2 occurrences with subject type hsdo_Instrument and object type hsdo_Related_Url_Content_Type.<br/>9 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type hsdo_Location.<br/>3 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type hsdo_Instrument.<br/>1 occurrences with subject type hsdo_Variable and object type hsdo_Measurement_Name.<br/>2 occurrences with subject type hsdo_Temporal_Resolution_Range and object type hsdo_Location.<br/>4 occurrences with subject type hsdo_Sub_Experiment_Id and object type hsdo_Location.<br/>2 occurrences with subject type hsdo_Experiment and object type hsdo_Platform.<br/>1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Chronostratigraphic_Unit.<br/>2 occurrences with subject type hsdo_Platform and object type hsdo_Chronostratigraphic_Unit.<br/>1 occurrences with subject type hsdo_Location and object type hsdo_Temporal_Resolution_Range.<br/>1 occurrences with subject type hsdo_Frequency and object type hsdo_Location.<br/>1 occurrences with subject type hsdo_Instrument and object type hsdo_Activity.<br/>1 occurrences with subject type hsdo_Temporal_Resolution_Range and object type hsdo_Model.<br/>1 occurrences with subject type hsdo_Temporal_Resolution_Range and object type hsdo_Instrument.<br/>1 occurrences with subject type hsdo_Model and object type hsdo_Platform.<br/>2 occurrences with subject type hsdo_Provider and object type hsdo_Measurement_Name.<br/>1 occurrences with subject type hsdo_Institution and object type hsdo_Instrument.<br/>1 occurrences with subject type hsdo_Provider and object type hsdo_Platform.<br/>2 occurrences with subject type hsdo_Platform and object type hsdo_Models.<br/>3 occurrences with subject type hsdo_Provider and object type hsdo_Variable.<br/>1 occurrences with subject type hsdo_Data_Format and object type hsdo_Provider.<br/>2 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type hsdo_Variable.<br/>1 occurrences with subject type hsdo_Provider and object type hsdo_Provider.<br/>1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Project.<br/>2 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Model.<br/>1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Data_Format.<br/>1 occurrences with subject type hsdo_Provider and object type hsdo_Chronostratigraphic_Unit.<br/>1 occurrences with subject type hsdo_Provider and object type hsdo_Cmip6_Source_Id.<br/>1 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type hsdo_Project.<br/>1 occurrences with subject type hsdo_Dataset and object type hsdo_Provider.<br/>1 occurrences with subject type hsdo_Dataset and object type hsdo_Science_Keyword.<br/>1 occurrences with subject type hsdo_Dataset and object type hsdo_Project.<br/>1 occurrences with subject type hsdo_Platform and object type hsdo_Project.<br/>4 occurrences with subject type hsdo_Experiment and object type hsdo_Models.<br/>3 occurrences with subject type hsdo_Data_Format and object type hsdo_Location.<br/>1 occurrences with subject type hsdo_Data_Format and object type hsdo_Science_Keyword.<br/>1 occurrences with subject type hsdo_Model and object type hsdo_Models.<br/>1 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Variable.<br/>1 occurrences with subject type hsdo_Project and object type hsdo_Sub_Experiment_Id. | direct |
| [skos_prefLabel](../slots/skos_prefLabel.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 983 occurrences with subject type hsdo_Location and object type string.<br/>2975 occurrences with subject type hsdo_Science_Keyword and object type string.<br/>1171 occurrences with subject type hsdo_Platform and object type string.<br/>24 occurrences with subject type hsdo_Activity and object type string.<br/>150 occurrences with subject type hsdo_Model and object type string.<br/>184 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type string.<br/>444 occurrences with subject type hsdo_Experiment and object type string.<br/>3745 occurrences with subject type hsdo_Provider and object type string.<br/>2363 occurrences with subject type hsdo_Instrument and object type string.<br/>1727 occurrences with subject type hsdo_Project and object type string.<br/>4 occurrences with subject type hsdo_Realm and object type string.<br/>297 occurrences with subject type hsdo_Models and object type string.<br/>234 occurrences with subject type hsdo_Measurement_Name and object type string.<br/>75 occurrences with subject type hsdo_Institution and object type string.<br/>55 occurrences with subject type hsdo_Sub_Experiment_Id and object type string.<br/>198 occurrences with subject type hsdo_Data_Format and object type string.<br/>1283 occurrences with subject type hsdo_Variable and object type string.<br/>134 occurrences with subject type hsdo_Cmip6_Source_Id and object type string.<br/>15 occurrences with subject type hsdo_Horizontal_Resolution_Range and object type string.<br/>5 occurrences with subject type hsdo_Source_Type and object type string.<br/>88 occurrences with subject type hsdo_Related_Url_Content_Type and object type string.<br/>107 occurrences with subject type hsdo_Dataset and object type string.<br/>19 occurrences with subject type hsdo_Temporal_Resolution_Range and object type string.<br/>16 occurrences with subject type hsdo_Nominal_Resolution and object type string.<br/>16 occurrences with subject type hsdo_Frequency and object type string.<br/>4 occurrences with subject type hsdo_License and object type string.<br/>38 occurrences with subject type hsdo_Mime_Type and object type string.<br/>16359 occurrences with subject type skos_Concept and object type string.<br/>6 occurrences with subject type hsdo_Vertical_Resolution_Range and object type string. | direct |
| [skos_broader](../slots/skos_broader.md) | 0..1 <br/> [HsdoMeasurementName](../classes/HsdoMeasurementName.md)&nbsp;or&nbsp;<br />[SkosConcept](../classes/SkosConcept.md)&nbsp;or&nbsp;<br />[HsdoProject](../classes/HsdoProject.md)&nbsp;or&nbsp;<br />[HsdoSubExperimentId](../classes/HsdoSubExperimentId.md)&nbsp;or&nbsp;<br />[HsdoMimeType](../classes/HsdoMimeType.md)&nbsp;or&nbsp;<br />[HsdoRelatedUrlContentType](../classes/HsdoRelatedUrlContentType.md)&nbsp;or&nbsp;<br />[HsdoModels](../classes/HsdoModels.md)&nbsp;or&nbsp;<br />[HsdoPlatform](../classes/HsdoPlatform.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)&nbsp;or&nbsp;<br />[HsdoVariable](../classes/HsdoVariable.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoModel](../classes/HsdoModel.md)&nbsp;or&nbsp;<br />[HsdoInstrument](../classes/HsdoInstrument.md)&nbsp;or&nbsp;<br />[HsdoNominalResolution](../classes/HsdoNominalResolution.md)&nbsp;or&nbsp;<br />[HsdoLocation](../classes/HsdoLocation.md)&nbsp;or&nbsp;<br />[HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md)&nbsp;or&nbsp;<br />[HsdoChronostratigraphicUnit](../classes/HsdoChronostratigraphicUnit.md)&nbsp;or&nbsp;<br />[HsdoTemporalResolutionRange](../classes/HsdoTemporalResolutionRange.md)&nbsp;or&nbsp;<br />[HsdoSourceType](../classes/HsdoSourceType.md)&nbsp;or&nbsp;<br />[HsdoDataFormat](../classes/HsdoDataFormat.md)&nbsp;or&nbsp;<br />[HsdoScienceKeyword](../classes/HsdoScienceKeyword.md)&nbsp;or&nbsp;<br />[HsdoDataset](../classes/HsdoDataset.md) | No slot (predicate) description specified <br/> 2245 occurrences with subject type hsdo_Location and object type hsdo_Location.<br/>261 occurrences with subject type hsdo_Location and object type hsdo_Instrument.<br/>8109 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Science_Keyword.<br/>2953 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Provider.<br/>1937 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Location.<br/>312 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Model.<br/>1761 occurrences with subject type hsdo_Platform and object type hsdo_Instrument.<br/>2153 occurrences with subject type hsdo_Platform and object type hsdo_Platform.<br/>102 occurrences with subject type hsdo_Location and object type hsdo_Project.<br/>48 occurrences with subject type hsdo_Activity and object type hsdo_Project.<br/>40 occurrences with subject type hsdo_Model and object type hsdo_Instrument.<br/>34 occurrences with subject type hsdo_Model and object type hsdo_Platform.<br/>789 occurrences with subject type hsdo_Chronostratigraphic_Unit and object type hsdo_Chronostratigraphic_Unit.<br/>47 occurrences with subject type hsdo_Experiment and object type hsdo_Project.<br/>8707 occurrences with subject type hsdo_Provider and object type hsdo_Provider.<br/>86 occurrences with subject type hsdo_Model and object type hsdo_Project.<br/>6114 occurrences with subject type hsdo_Instrument and object type hsdo_Instrument.<br/>2038 occurrences with subject type hsdo_Instrument and object type hsdo_Experiment.<br/>57 occurrences with subject type hsdo_Experiment and object type hsdo_Provider.<br/>475 occurrences with subject type hsdo_Location and object type hsdo_Science_Keyword.<br/>311 occurrences with subject type hsdo_Location and object type hsdo_Provider.<br/>26 occurrences with subject type hsdo_Location and object type hsdo_Model.<br/>3416 occurrences with subject type hsdo_Project and object type hsdo_Project.<br/>4 occurrences with subject type hsdo_Realm and object type hsdo_Location.<br/>304 occurrences with subject type hsdo_Provider and object type hsdo_Location.<br/>180 occurrences with subject type hsdo_Instrument and object type hsdo_Project.<br/>891 occurrences with subject type hsdo_Models and object type hsdo_Science_Keyword.<br/>286 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Instrument.<br/>355 occurrences with subject type hsdo_Experiment and object type hsdo_Experiment.<br/>131 occurrences with subject type hsdo_Model and object type hsdo_Science_Keyword.<br/>32 occurrences with subject type hsdo_Model and object type hsdo_Model.<br/>9 occurrences with subject type hsdo_Model and object type hsdo_Experiment.<br/>80 occurrences with subject type hsdo_Model and object type hsdo_Provider.<br/>317 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Instrument.<br/>20 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Location.<br/>75 occurrences with subject type hsdo_Institution and object type hsdo_Provider.<br/>38 occurrences with subject type hsdo_Model and object type hsdo_Location.<br/>12 occurrences with subject type hsdo_Instrument and object type hsdo_Variable.<br/>352 occurrences with subject type hsdo_Instrument and object type hsdo_Science_Keyword.<br/>160 occurrences with subject type hsdo_Instrument and object type hsdo_Provider.<br/>137 occurrences with subject type hsdo_Experiment and object type hsdo_Science_Keyword.<br/>31 occurrences with subject type hsdo_Experiment and object type hsdo_Location.<br/>54 occurrences with subject type hsdo_Sub_Experiment_Id and object type hsdo_Sub_Experiment_Id.<br/>227 occurrences with subject type hsdo_Measurement_Name and object type hsdo_Measurement_Name.<br/>130 occurrences with subject type hsdo_Instrument and object type hsdo_Location.<br/>154 occurrences with subject type hsdo_Provider and object type hsdo_Science_Keyword.<br/>182 occurrences with subject type hsdo_Provider and object type hsdo_Model.<br/>183 occurrences with subject type hsdo_Provider and object type hsdo_Instrument.<br/>43 occurrences with subject type hsdo_Location and object type hsdo_Platform.<br/>242 occurrences with subject type hsdo_Data_Format and object type hsdo_Data_Format.<br/>63 occurrences with subject type hsdo_Location and object type hsdo_Experiment.<br/>1281 occurrences with subject type hsdo_Variable and object type hsdo_Variable.<br/>55 occurrences with subject type hsdo_Platform and object type hsdo_Science_Keyword.<br/>25 occurrences with subject type hsdo_Platform and object type hsdo_Location.<br/>33 occurrences with subject type hsdo_Platform and object type hsdo_Provider.<br/>84 occurrences with subject type hsdo_Instrument and object type hsdo_Platform.<br/>27 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Project.<br/>22 occurrences with subject type hsdo_Provider and object type hsdo_Related_Url_Content_Type.<br/>402 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Science_Keyword.<br/>15 occurrences with subject type hsdo_Provider and object type hsdo_Sub_Experiment_Id.<br/>3 occurrences with subject type hsdo_Model and object type hsdo_Source_Type.<br/>58 occurrences with subject type hsdo_Experiment and object type hsdo_Instrument.<br/>6 occurrences with subject type hsdo_Experiment and object type hsdo_Platform.<br/>34 occurrences with subject type hsdo_Instrument and object type hsdo_Model.<br/>5 occurrences with subject type hsdo_Location and object type hsdo_Sub_Experiment_Id.<br/>220 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Experiment.<br/>42 occurrences with subject type hsdo_Science_Keyword and object type hsdo_Platform.<br/>7 occurrences with subject type hsdo_Model and object type hsdo_Variable.<br/>13 occurrences with subject type hsdo_Provider and object type hsdo_Variable.<br/>4 occurrences with subject type hsdo_Provider and object type hsdo_Experiment.<br/>211 occurrences with subject type hsdo_Related_Url_Content_Type and object type hsdo_Related_Url_Content_Type.<br/>106 occurrences with subject type hsdo_Dataset and object type hsdo_Dataset.<br/>26 occurrences with subject type hsdo_Project and object type hsdo_Science_Keyword.<br/>4 occurrences with subject type hsdo_Project and object type hsdo_Location.<br/>15 occurrences with subject type hsdo_Project and object type hsdo_Provider.<br/>4 occurrences with subject type hsdo_Platform and object type hsdo_Experiment.<br/>7 occurrences with subject type hsdo_Location and object type hsdo_Related_Url_Content_Type.<br/>16 occurrences with subject type hsdo_Models and object type hsdo_Instrument.<br/>10 occurrences with subject type hsdo_Location and object type hsdo_Measurement_Name.<br/>1 occurrences with subject type hsdo_Provider and object type hsdo_Source_Type.<br/>14 occurrences with subject type hsdo_Instrument and object type hsdo_Related_Url_Content_Type.<br/>12 occurrences with subject type hsdo_Experiment and object type hsdo_Model.<br/>85 occurrences with subject type hsdo_Platform and object type hsdo_Model.<br/>18 occurrences with subject type hsdo_Temporal_Resolution_Range and object type hsdo_Temporal_Resolution_Range.<br/>4 occurrences with subject type hsdo_Project and object type hsdo_Model.<br/>17 occurrences with subject type hsdo_Platform and object type hsdo_Project.<br/>2 occurrences with subject type hsdo_Experiment and object type hsdo_Variable.<br/>3 occurrences with subject type hsdo_Provider and object type hsdo_Platform.<br/>12 occurrences with subject type hsdo_Location and object type hsdo_Variable.<br/>2 occurrences with subject type hsdo_Institution and object type hsdo_Location.<br/>4 occurrences with subject type hsdo_Source_Type and object type hsdo_Source_Type.<br/>15 occurrences with subject type hsdo_Nominal_Resolution and object type hsdo_Nominal_Resolution.<br/>3 occurrences with subject type hsdo_Experiment and object type hsdo_Source_Type.<br/>16 occurrences with subject type hsdo_Frequency and object type hsdo_Temporal_Resolution_Range.<br/>4 occurrences with subject type hsdo_License and object type hsdo_Instrument.<br/>1 occurrences with subject type hsdo_Instrument and object type hsdo_Models.<br/>3 occurrences with subject type hsdo_Location and object type hsdo_Source_Type.<br/>3 occurrences with subject type hsdo_Model and object type hsdo_Related_Url_Content_Type.<br/>24 occurrences with subject type hsdo_Related_Url_Content_Type and object type hsdo_Provider.<br/>1 occurrences with subject type hsdo_Project and object type hsdo_Experiment.<br/>1 occurrences with subject type hsdo_Project and object type hsdo_Variable.<br/>1 occurrences with subject type hsdo_Model and object type hsdo_Temporal_Resolution_Range.<br/>3 occurrences with subject type hsdo_Models and object type hsdo_Models.<br/>1 occurrences with subject type hsdo_Provider and object type hsdo_Project.<br/>2 occurrences with subject type hsdo_Experiment and object type hsdo_Measurement_Name.<br/>16338 occurrences with subject type skos_Concept and object type skos_Concept.<br/>37 occurrences with subject type hsdo_Mime_Type and object type hsdo_Mime_Type.<br/>14 occurrences with subject type hsdo_Horizontal_Resolution_Range and object type hsdo_Horizontal_Resolution_Range.<br/>6 occurrences with subject type hsdo_Vertical_Resolution_Range and object type hsdo_Variable.<br/>2 occurrences with subject type hsdo_Related_Url_Content_Type and object type hsdo_Instrument. | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HsdoActivity](../classes/HsdoActivity.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoChronostratigraphicUnit](../classes/HsdoChronostratigraphicUnit.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoDataFormat](../classes/HsdoDataFormat.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoDataset](../classes/HsdoDataset.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoExperiment](../classes/HsdoExperiment.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoFrequency](../classes/HsdoFrequency.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoInstitution](../classes/HsdoInstitution.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoInstrument](../classes/HsdoInstrument.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoLicense](../classes/HsdoLicense.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoLocation](../classes/HsdoLocation.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoMeasurementName](../classes/HsdoMeasurementName.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoMimeType](../classes/HsdoMimeType.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoModel](../classes/HsdoModel.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoModels](../classes/HsdoModels.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoNominalResolution](../classes/HsdoNominalResolution.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoPlatform](../classes/HsdoPlatform.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoProject](../classes/HsdoProject.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoProvider](../classes/HsdoProvider.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoRealm](../classes/HsdoRealm.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoRelatedUrlContentType](../classes/HsdoRelatedUrlContentType.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoScienceKeyword](../classes/HsdoScienceKeyword.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoSourceType](../classes/HsdoSourceType.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoSubExperimentId](../classes/HsdoSubExperimentId.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoTemporalResolutionRange](../classes/HsdoTemporalResolutionRange.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoVariable](../classes/HsdoVariable.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoVerticalResolutionRange](../classes/HsdoVerticalResolutionRange.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [HsdoPaper](../classes/HsdoPaper.md) | [relation_Mention](../slots/relation_Mention.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |
| [SkosConcept](../classes/SkosConcept.md) | [skos_broader](../slots/skos_broader.md) | any_of[range] | [HsdoHorizontalResolutionRange](../classes/HsdoHorizontalResolutionRange.md) |






## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:Horizontal_Resolution_Range |
| native | climatepub4-kg/:HsdoHorizontalResolutionRange |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: hsdo_Horizontal_Resolution_Range
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 15 occurrences.
from_schema: climatepub4-kg
rank: 1000
slots:
- relation_MeasuredAt
- skos_prefLabel
- skos_broader
class_uri: hsdo:Horizontal_Resolution_Range

```
</details>

### Induced

<details>
```yaml
name: hsdo_Horizontal_Resolution_Range
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 15 occurrences.
from_schema: climatepub4-kg
rank: 1000
attributes:
  relation_MeasuredAt:
    name: relation_MeasuredAt
    description: No slot (predicate) description specified
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
    - description: hsdo_Location → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/c322d007-8d19-451b-ba46-daa216782248
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ff1cfc9c-5e73-4137-b8e1-d6f4e83e61c4
        example_subject_type: hsdo_Location
    - description: hsdo_Science_Keyword → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/27dd85c2-3403-438d-8b0c-8d424df60468
        example_object_type: hsdo_Science_Keyword
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fc77777e-614f-41f1-9b97-d5324fa99105
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Science_Keyword → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/e384382c-fb2a-43ea-b064-610e6d4807e9
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/d76e6734-956b-419d-9d7a-52b8e645b6ac
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Science_Keyword → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/d40d9651-aa19-4b2c-9764-7371bb64b9a7
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fc77777e-614f-41f1-9b97-d5324fa99105
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Science_Keyword → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/e2e53a45-c6ee-4fac-9c08-7677c1318533
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f829171e-8b22-4f93-8f71-7932dfd7a70b
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Science_Keyword → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/67290503-94b9-4517-b5b6-063bba2bee27
        example_object_type: hsdo_Platform
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f9fe1bc0-88c5-4c26-9b4c-a9867d027685
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Experiment → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/fa68e752-f3a7-4361-a000-47c908545e49
        example_object_type: hsdo_Science_Keyword
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Experiment → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/feff6e5e-27be-4404-af9c-c80b56d48ad4
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Experiment → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/fbb455d3-de90-43dc-b678-48f463461740
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Experiment → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Experiment → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/d1e2c5e2-076b-4949-8125-384712a33b58
        example_object_type: hsdo_Model
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Location → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/9d7eed04-9c49-4024-8d0f-06474cc38bbc
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ff5d5c12-74d9-435d-9164-1c9d69f967d7
        example_subject_type: hsdo_Location
    - description: hsdo_Project → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/5c439818-3a80-4c6d-9d2c-74ea1f1a294a
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ffdb1819-43ba-4307-80db-dae705f62a8d
        example_subject_type: hsdo_Project
    - description: hsdo_Project → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f39bac00-b827-46c3-aae2-3b98df0be0dc
        example_subject_type: hsdo_Project
    - description: hsdo_Instrument → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/fc95c990-47cb-4087-a08f-235dd1eb1260
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb
        example_subject_type: hsdo_Instrument
    - description: hsdo_Science_Keyword → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/c297fda0-848a-4a9b-85be-86f29c92f212
        example_object_type: hsdo_Provider
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/b9107ec3-c777-4e71-9046-55bd7ed57ef0
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Project → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/6a04c8fb-53aa-465d-803d-d0aaad32be12
        example_object_type: hsdo_Project
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/8e6ac9fb-b2a0-4547-915d-15b4e0df7d4a
        example_subject_type: hsdo_Project
    - description: hsdo_Model → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/b9107ec3-c777-4e71-9046-55bd7ed57ef0
        example_object_type: hsdo_Science_Keyword
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66
        example_subject_type: hsdo_Model
    - description: hsdo_Model → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/e657b41f-4aa0-4816-b3c8-5b477812a0bc
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66
        example_subject_type: hsdo_Model
    - description: hsdo_Model → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66
        example_subject_type: hsdo_Model
    - description: hsdo_Model → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/91d0d91a-6395-49a0-b498-41f71ae83ecc
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f8845bec-c628-4185-aac1-4af22481c024
        example_subject_type: hsdo_Model
    - description: hsdo_Instrument → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/f6350232-b1c7-458c-bc43-bda357ebb6db
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb
        example_subject_type: hsdo_Instrument
    - description: hsdo_Instrument → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/0399b52c-e3de-4dcc-9eb6-b1e3acf2cf1b
        example_object_type: hsdo_Model
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ee0fce70-2097-4f5b-853a-c34e6cbff929
        example_subject_type: hsdo_Instrument
    - description: hsdo_Location → hsdo_Measurement_Name
      object:
        example_object: https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
        example_object_type: hsdo_Measurement_Name
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f36d71c6-f2ad-49c4-809f-09b4f0688412
        example_subject_type: hsdo_Location
    - description: hsdo_Location → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/ea213be5-fe37-4179-9a9b-030c2bf42cf5
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ff5d5c12-74d9-435d-9164-1c9d69f967d7
        example_subject_type: hsdo_Location
    - description: hsdo_Location → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/9db10fb2-0ceb-412e-9936-a286c579fa9f
        example_object_type: hsdo_Science_Keyword
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fd03d204-4391-4e98-8142-8b8efa235231
        example_subject_type: hsdo_Location
    - description: hsdo_Instrument → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/d8bb1aa0-49d7-4a6a-a96e-66231b3fc7f6
        example_object_type: hsdo_Platform
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fe2719de-c5c8-4ce6-8230-1d16c8155991
        example_subject_type: hsdo_Instrument
    - description: hsdo_Instrument → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/26fc4850-7ba9-44d8-a156-5c623e17b72f
        example_object_type: hsdo_Provider
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fe4392b0-13a9-43ff-bacc-f44a65aed4fa
        example_subject_type: hsdo_Instrument
    - description: hsdo_Instrument → hsdo_Measurement_Name
      object:
        example_object: https://climateKG.org/entity/511637f3-82aa-43b2-9eee-0c099ecbfcce
        example_object_type: hsdo_Measurement_Name
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/eeba88d2-20bf-43b1-bccf-b125485405f4
        example_subject_type: hsdo_Instrument
    - description: hsdo_Instrument → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/b2140059-b3ca-415c-b0a7-3e142783ffe8
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb
        example_subject_type: hsdo_Instrument
    - description: hsdo_Project → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66
        example_object_type: hsdo_Model
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
        example_subject_type: hsdo_Project
    - description: hsdo_Science_Keyword → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/10a9c153-f37d-48fe-920d-c790d946ab07
        example_object_type: hsdo_Model
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fc5a1b7a-5ee8-4d67-80f5-a57e3f1734ab
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Instrument → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/482453d7-ffa4-4ae9-8158-9fa73bcf39ef
        example_object_type: hsdo_Science_Keyword
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb
        example_subject_type: hsdo_Instrument
    - description: hsdo_Models → hsdo_Chronostratigraphic_Unit
      object:
        example_object: https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
        example_object_type: hsdo_Chronostratigraphic_Unit
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/063177a9-14cd-4750-9aa4-ad5d266bd7ad
        example_subject_type: hsdo_Models
    - description: hsdo_Models → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/640d703f-9312-4f11-8367-30a8bd8fc508
        example_subject_type: hsdo_Models
    - description: hsdo_Models → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
        example_object_type: hsdo_Project
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/063177a9-14cd-4750-9aa4-ad5d266bd7ad
        example_subject_type: hsdo_Models
    - description: hsdo_Project → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/b9107ec3-c777-4e71-9046-55bd7ed57ef0
        example_object_type: hsdo_Science_Keyword
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f4bc60f4-5505-4eb4-83e6-585e0683eac3
        example_subject_type: hsdo_Project
    - description: hsdo_Experiment → hsdo_Activity
      object:
        example_object: https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58
        example_object_type: hsdo_Activity
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/0720043d-4d31-45ae-a37c-9ba5959bf97d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Location → hsdo_Data_Format
      object:
        example_object: https://climateKG.org/entity/ebe6f3c4-a78f-4152-977c-296d42e4e9e8
        example_object_type: hsdo_Data_Format
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ecac51c2-4def-4dac-b965-a5103402395b
        example_subject_type: hsdo_Location
    - description: hsdo_Provider → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/559411a8-5fe5-4d2c-ad6b-30849e650396
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/facdb262-04eb-47f9-b46e-ba7a379722ec
        example_subject_type: hsdo_Provider
    - description: hsdo_Instrument → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/75b8d2f7-5c8a-41d3-9660-ebd2f2cb4b4b
        example_object_type: hsdo_Project
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/d7742082-5461-4610-9ced-e0ec3bb64697
        example_subject_type: hsdo_Instrument
    - description: hsdo_Instrument → hsdo_Data_Format
      object:
        example_object: https://climateKG.org/entity/ddcd5941-9ba8-4c39-a498-1e214d1bfa6e
        example_object_type: hsdo_Data_Format
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/c45c4e30-e253-4329-8838-8991a53f494f
        example_subject_type: hsdo_Instrument
    - description: hsdo_Variable → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/8dc44d7b-e349-42ab-860e-18f5acfc1b28
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/43e825a7-4080-44d5-ac32-f355ed1e35c0
        example_subject_type: hsdo_Variable
    - description: hsdo_Science_Keyword → hsdo_Chronostratigraphic_Unit
      object:
        example_object: https://climateKG.org/entity/c7e7fb38-44ef-4c5b-aa1d-b3fdcf89d838
        example_object_type: hsdo_Chronostratigraphic_Unit
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/d1ef1ce2-7a50-446d-b744-73513700f351
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Location → hsdo_Chronostratigraphic_Unit
      object:
        example_object: https://climateKG.org/entity/e000088a-8252-4603-ba55-38189c45612c
        example_object_type: hsdo_Chronostratigraphic_Unit
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/df160e31-ae45-41a4-9093-a80fe5303cea
        example_subject_type: hsdo_Location
    - description: hsdo_Location → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/4e366444-01ea-4517-9d93-56f55ddf41b7
        example_object_type: hsdo_Provider
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ecc4a2bb-f195-4296-b300-c1227221b688
        example_subject_type: hsdo_Location
    - description: hsdo_Variable → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/3b20a141-8408-44b2-adf1-632ac9222c61
        example_object_type: hsdo_Model
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ba70b595-5263-4ffd-97a2-f86ba91681ae
        example_subject_type: hsdo_Variable
    - description: hsdo_Platform → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/c5563d03-2f68-4dac-a50b-3b8450725356
        example_object_type: hsdo_Science_Keyword
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/d8bb1aa0-49d7-4a6a-a96e-66231b3fc7f6
        example_subject_type: hsdo_Platform
    - description: hsdo_Platform → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/a4202721-0cba-4fa1-853f-890f146b04f9
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fdb04105-e8ba-4a83-9c35-ed3c931ccc9f
        example_subject_type: hsdo_Platform
    - description: hsdo_Platform → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/f6350232-b1c7-458c-bc43-bda357ebb6db
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fdb04105-e8ba-4a83-9c35-ed3c931ccc9f
        example_subject_type: hsdo_Platform
    - description: hsdo_Platform → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fdb04105-e8ba-4a83-9c35-ed3c931ccc9f
        example_subject_type: hsdo_Platform
    - description: hsdo_Provider → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/f1a25060-330c-4f84-9633-ed59ae8c64bf
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f634ab55-de40-4d0b-93bc-691bf5408ccb
        example_subject_type: hsdo_Provider
    - description: hsdo_Provider → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/655fe09d-7335-467f-a286-3d1906d194d6
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fe950f88-6d5e-4741-8076-3fbe16b0b9c4
        example_subject_type: hsdo_Provider
    - description: hsdo_Location → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/d8bb1aa0-49d7-4a6a-a96e-66231b3fc7f6
        example_object_type: hsdo_Platform
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/a4aea007-d297-4051-8b41-5cdde00b4d1e
        example_subject_type: hsdo_Location
    - description: hsdo_Science_Keyword → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
        example_object_type: hsdo_Project
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/e5815f58-8232-4c7f-b50d-ea71d73891a9
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Location → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/be15e9d3-5879-4432-96d1-3c16c81a4c8c
        example_object_type: hsdo_Variable
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ff1cfc9c-5e73-4137-b8e1-d6f4e83e61c4
        example_subject_type: hsdo_Location
    - description: hsdo_Model → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/10a9c153-f37d-48fe-920d-c790d946ab07
        example_object_type: hsdo_Model
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66
        example_subject_type: hsdo_Model
    - description: hsdo_Data_Format → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/5ce16b97-c91c-420c-9701-33d19d50b286
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/10de1987-5896-42d6-be7c-506fd7ba1f21
        example_subject_type: hsdo_Data_Format
    - description: hsdo_Data_Format → hsdo_Chronostratigraphic_Unit
      object:
        example_object: https://climateKG.org/entity/a686e751-3639-4cd0-840b-c8ad25c441c1
        example_object_type: hsdo_Chronostratigraphic_Unit
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/10de1987-5896-42d6-be7c-506fd7ba1f21
        example_subject_type: hsdo_Data_Format
    - description: hsdo_Data_Format → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/c88a747b-2302-49c9-b747-f2faa21e2b6b
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ebe6f3c4-a78f-4152-977c-296d42e4e9e8
        example_subject_type: hsdo_Data_Format
    - description: hsdo_Experiment → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/569a2936-7543-434e-92e2-6f75a5be68c0
        example_object_type: hsdo_Variable
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Location → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/6831004a-34d7-42f5-a903-6c84a5e7590f
        example_object_type: hsdo_Project
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/a4aea007-d297-4051-8b41-5cdde00b4d1e
        example_subject_type: hsdo_Location
    - description: hsdo_Location → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/e6fb1b81-8ffc-486f-b1a1-2f292af8cee6
        example_object_type: hsdo_Model
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/df160e31-ae45-41a4-9093-a80fe5303cea
        example_subject_type: hsdo_Location
    - description: hsdo_Horizontal_Resolution_Range → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/51e3593f-4b42-4141-972e-96666c479f9c
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/1499785c-8b74-45f4-bbf7-19d2d4e43b2f
        example_subject_type: hsdo_Horizontal_Resolution_Range
    - description: hsdo_Variable → hsdo_Models
      object:
        example_object: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
        example_object_type: hsdo_Models
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
        example_subject_type: hsdo_Variable
    - description: hsdo_Variable → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/a6212424-1146-4a79-a14c-8ce88543b08b
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/43e825a7-4080-44d5-ac32-f355ed1e35c0
        example_subject_type: hsdo_Variable
    - description: hsdo_Experiment → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/7e317dda-643f-494d-bdf1-b017c7194add
        example_object_type: hsdo_Project
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Experiment → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/f634ab55-de40-4d0b-93bc-691bf5408ccb
        example_object_type: hsdo_Provider
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Project → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/4401ec0e-0d64-41d3-b4bd-2ff797865e83
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ffdb1819-43ba-4307-80db-dae705f62a8d
        example_subject_type: hsdo_Project
    - description: hsdo_Measurement_Name → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/74d079b5-9b36-45c9-9b09-7e3646b65a85
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Model → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
        example_object_type: hsdo_Variable
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/8894d92c-be32-465b-ae08-e5de755a92fc
        example_subject_type: hsdo_Model
    - description: hsdo_Science_Keyword → hsdo_Data_Format
      object:
        example_object: https://climateKG.org/entity/d896a8cc-4fce-4a8d-86bc-185b324fab2b
        example_object_type: hsdo_Data_Format
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/1af675ae-9a65-4d91-970e-a8b9fcce0232
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Instrument → hsdo_Chronostratigraphic_Unit
      object:
        example_object: https://climateKG.org/entity/a686e751-3639-4cd0-840b-c8ad25c441c1
        example_object_type: hsdo_Chronostratigraphic_Unit
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/e6f9524a-e4bc-460a-bdf3-a5e8f0e921a9
        example_subject_type: hsdo_Instrument
    - description: hsdo_Location → hsdo_Models
      object:
        example_object: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
        example_object_type: hsdo_Models
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f26c754c-1765-4a45-920e-792b43353a39
        example_subject_type: hsdo_Location
    - description: hsdo_Models → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
        example_object_type: hsdo_Variable
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ff0316d3-bbdd-463d-9a23-9f1eb69ca2a9
        example_subject_type: hsdo_Models
    - description: hsdo_Variable → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/0b3765f7-20f7-4425-bd50-d1bb99d09d86
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/80a294bd-b8a1-44f3-ac3d-acb7d409d23f
        example_subject_type: hsdo_Variable
    - description: hsdo_Variable → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/d78e5503-d78e-466d-97bb-e68d6e768a9d
        example_object_type: hsdo_Science_Keyword
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/1b945d01-2f5c-4008-b1b3-d78b2822b466
        example_subject_type: hsdo_Variable
    - description: hsdo_Variable → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/c297fda0-848a-4a9b-85be-86f29c92f212
        example_object_type: hsdo_Provider
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ba70b595-5263-4ffd-97a2-f86ba91681ae
        example_subject_type: hsdo_Variable
    - description: hsdo_Provider → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/27dd85c2-3403-438d-8b0c-8d424df60468
        example_object_type: hsdo_Science_Keyword
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f634ab55-de40-4d0b-93bc-691bf5408ccb
        example_subject_type: hsdo_Provider
    - description: hsdo_Measurement_Name → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/c88a747b-2302-49c9-b747-f2faa21e2b6b
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Measurement_Name → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/a9b21edd-49b7-43be-8e35-8652bbc5559a
        example_object_type: hsdo_Platform
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/511637f3-82aa-43b2-9eee-0c099ecbfcce
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Measurement_Name → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/d2e93932-0231-4b23-af2f-217c6315a95e
        example_object_type: hsdo_Science_Keyword
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Provider → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
        example_object_type: hsdo_Project
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f634ab55-de40-4d0b-93bc-691bf5408ccb
        example_subject_type: hsdo_Provider
    - description: hsdo_Model → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/4ea1b3cc-d4d2-4803-a416-753cdd1ec451
        example_object_type: hsdo_Project
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/5fd5ccc2-5edb-4823-940d-03a290a5c5fc
        example_subject_type: hsdo_Model
    - description: hsdo_Science_Keyword → hsdo_Measurement_Name
      object:
        example_object: https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
        example_object_type: hsdo_Measurement_Name
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/406bfa8b-8522-4776-936a-1fda8b0cfe97
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Instrument → hsdo_Models
      object:
        example_object: https://climateKG.org/entity/bbd90aa4-fe5e-4580-a51d-90d7568a9fee
        example_object_type: hsdo_Models
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ea213be5-fe37-4179-9a9b-030c2bf42cf5
        example_subject_type: hsdo_Instrument
    - description: hsdo_Provider → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/3f45aadf-ec7c-43a1-a008-b24ca139837a
        example_object_type: hsdo_Model
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/bb9c9be6-78c7-4fbd-9a35-a218276393ec
        example_subject_type: hsdo_Provider
    - description: hsdo_Instrument → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
        example_object_type: hsdo_Variable
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ff03e9fc-9882-4a5e-ad0b-830d8f1186cb
        example_subject_type: hsdo_Instrument
    - description: hsdo_Dataset → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/734f8f27-6976-4b67-8794-c7fc79d6161e
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
        example_subject_type: hsdo_Dataset
    - description: hsdo_Measurement_Name → hsdo_Measurement_Name
      object:
        example_object: https://climateKG.org/entity/e4e4dac0-f0aa-4757-989c-70522eb64e76
        example_object_type: hsdo_Measurement_Name
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Project → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/a9b21edd-49b7-43be-8e35-8652bbc5559a
        example_object_type: hsdo_Platform
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/2a60df4a-a0d7-4e4b-b02a-372a083f0170
        example_subject_type: hsdo_Project
    - description: hsdo_Location → hsdo_Related_Url_Content_Type
      object:
        example_object: https://climateKG.org/entity/4f3c0b04-1fe6-4e11-994a-9cc4afd09ce0
        example_object_type: hsdo_Related_Url_Content_Type
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/8cb47594-3af6-4f4f-8ba1-4299a6d6887e
        example_subject_type: hsdo_Location
    - description: hsdo_Science_Keyword → hsdo_Models
      object:
        example_object: https://climateKG.org/entity/1e11026d-b012-494a-a813-8c69cb41fc0d
        example_object_type: hsdo_Models
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/b9107ec3-c777-4e71-9046-55bd7ed57ef0
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Variable → hsdo_Chronostratigraphic_Unit
      object:
        example_object: https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
        example_object_type: hsdo_Chronostratigraphic_Unit
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/b631f7b6-9a64-4f2b-bd29-7a20a466e44b
        example_subject_type: hsdo_Variable
    - description: hsdo_Variable → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/a9b21edd-49b7-43be-8e35-8652bbc5559a
        example_object_type: hsdo_Platform
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/b631f7b6-9a64-4f2b-bd29-7a20a466e44b
        example_subject_type: hsdo_Variable
    - description: hsdo_Variable → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
        example_object_type: hsdo_Variable
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/569a2936-7543-434e-92e2-6f75a5be68c0
        example_subject_type: hsdo_Variable
    - description: hsdo_Variable → hsdo_Data_Format
      object:
        example_object: https://climateKG.org/entity/d896a8cc-4fce-4a8d-86bc-185b324fab2b
        example_object_type: hsdo_Data_Format
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
        example_subject_type: hsdo_Variable
    - description: hsdo_Project → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/4e366444-01ea-4517-9d93-56f55ddf41b7
        example_object_type: hsdo_Provider
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/342ee29f-1e63-4bb4-b8d0-8f07472de7a9
        example_subject_type: hsdo_Project
    - description: hsdo_Project → hsdo_Models
      object:
        example_object: https://climateKG.org/entity/063177a9-14cd-4750-9aa4-ad5d266bd7ad
        example_object_type: hsdo_Models
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/4ea1b3cc-d4d2-4803-a416-753cdd1ec451
        example_subject_type: hsdo_Project
    - description: hsdo_Models → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/640d703f-9312-4f11-8367-30a8bd8fc508
        example_subject_type: hsdo_Models
    - description: hsdo_Model → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/a9586b25-36da-4e7d-ac2a-b1b24e2f44bd
        example_object_type: hsdo_Provider
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/3f45aadf-ec7c-43a1-a008-b24ca139837a
        example_subject_type: hsdo_Model
    - description: hsdo_Provider → hsdo_Models
      object:
        example_object: https://climateKG.org/entity/c266a473-338f-4fe9-965c-f8ae853ff57b
        example_object_type: hsdo_Models
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f634ab55-de40-4d0b-93bc-691bf5408ccb
        example_subject_type: hsdo_Provider
    - description: hsdo_Models → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/885735f3-121e-4ca0-ac8b-f37dbc972f03
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/640d703f-9312-4f11-8367-30a8bd8fc508
        example_subject_type: hsdo_Models
    - description: hsdo_Institution → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/2e0784f1-4c74-4e59-adc9-1245ae47db1e
        example_object_type: hsdo_Variable
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/e8df7edd-a176-45c9-8515-3a520948ef63
        example_subject_type: hsdo_Institution
    - description: hsdo_Project → hsdo_Chronostratigraphic_Unit
      object:
        example_object: https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
        example_object_type: hsdo_Chronostratigraphic_Unit
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/453a6807-abfa-481b-95b3-60bacf2cbb73
        example_subject_type: hsdo_Project
    - description: hsdo_Location → hsdo_Dataset
      object:
        example_object: https://climateKG.org/entity/2892e23f-5249-439d-8c0e-6c1d190b3beb
        example_object_type: hsdo_Dataset
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ff5d5c12-74d9-435d-9164-1c9d69f967d7
        example_subject_type: hsdo_Location
    - description: hsdo_Related_Url_Content_Type → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/f75bc31f-afda-45f4-bc90-226b7b0ee818
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/4f3c0b04-1fe6-4e11-994a-9cc4afd09ce0
        example_subject_type: hsdo_Related_Url_Content_Type
    - description: hsdo_Related_Url_Content_Type → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/0bdca141-ccec-471e-9dd9-f47d3a94abf7
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/b7ed88ce-3f04-40ea-863e-ac58bd048ff3
        example_subject_type: hsdo_Related_Url_Content_Type
    - description: hsdo_Related_Url_Content_Type → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/e2e53a45-c6ee-4fac-9c08-7677c1318533
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/4f3c0b04-1fe6-4e11-994a-9cc4afd09ce0
        example_subject_type: hsdo_Related_Url_Content_Type
    - description: hsdo_Science_Keyword → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/569a2936-7543-434e-92e2-6f75a5be68c0
        example_object_type: hsdo_Variable
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f6a8db71-9686-46ec-a3ac-66ca4a0ec1bd
        example_subject_type: hsdo_Science_Keyword
    - description: hsdo_Measurement_Name → hsdo_Experiment
      object:
        example_object: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_object_type: hsdo_Experiment
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/e4e4dac0-f0aa-4757-989c-70522eb64e76
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Activity → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/b631f7b6-9a64-4f2b-bd29-7a20a466e44b
        example_object_type: hsdo_Variable
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/5796ebd9-7dcb-4968-b876-1e678484cc62
        example_subject_type: hsdo_Activity
    - description: hsdo_Experiment → hsdo_Data_Format
      object:
        example_object: https://climateKG.org/entity/2c37a52f-c159-4d16-a5c1-36ca833863e1
        example_object_type: hsdo_Data_Format
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Project → hsdo_Measurement_Name
      object:
        example_object: https://climateKG.org/entity/7e304e75-b6b9-4e4b-bbaf-64a0a49d157d
        example_object_type: hsdo_Measurement_Name
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/6831004a-34d7-42f5-a903-6c84a5e7590f
        example_subject_type: hsdo_Project
    - description: hsdo_Model → hsdo_Measurement_Name
      object:
        example_object: https://climateKG.org/entity/7e304e75-b6b9-4e4b-bbaf-64a0a49d157d
        example_object_type: hsdo_Measurement_Name
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f2b0301b-2f33-4048-9381-25a92226ed66
        example_subject_type: hsdo_Model
    - description: hsdo_Platform → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/4e366444-01ea-4517-9d93-56f55ddf41b7
        example_object_type: hsdo_Provider
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/6fff6994-a0d8-4f19-8d36-c9f354b08b19
        example_subject_type: hsdo_Platform
    - description: hsdo_Experiment → hsdo_Chronostratigraphic_Unit
      object:
        example_object: https://climateKG.org/entity/a686e751-3639-4cd0-840b-c8ad25c441c1
        example_object_type: hsdo_Chronostratigraphic_Unit
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/67a21bdb-2f92-4692-96e7-6a27e95f8c55
        example_subject_type: hsdo_Experiment
    - description: hsdo_Experiment → hsdo_Measurement_Name
      object:
        example_object: https://climateKG.org/entity/e4e4dac0-f0aa-4757-989c-70522eb64e76
        example_object_type: hsdo_Measurement_Name
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Instrument → hsdo_Related_Url_Content_Type
      object:
        example_object: https://climateKG.org/entity/4f3c0b04-1fe6-4e11-994a-9cc4afd09ce0
        example_object_type: hsdo_Related_Url_Content_Type
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/e384382c-fb2a-43ea-b064-610e6d4807e9
        example_subject_type: hsdo_Instrument
    - description: hsdo_Chronostratigraphic_Unit → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/e125e285-b547-47ea-b566-5dffce2bbcbd
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/e000088a-8252-4603-ba55-38189c45612c
        example_subject_type: hsdo_Chronostratigraphic_Unit
    - description: hsdo_Chronostratigraphic_Unit → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/d9750f06-3784-4058-941f-40289c8d9d8b
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/e000088a-8252-4603-ba55-38189c45612c
        example_subject_type: hsdo_Chronostratigraphic_Unit
    - description: hsdo_Variable → hsdo_Measurement_Name
      object:
        example_object: https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
        example_object_type: hsdo_Measurement_Name
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/77c41d31-ec6f-4d1f-8fc5-acdadebd6a80
        example_subject_type: hsdo_Variable
    - description: hsdo_Temporal_Resolution_Range → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/6fa811fb-3666-4970-9208-ca8a21d57138
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/8c8c70b1-f6c5-4f34-89b5-510049b8c8ab
        example_subject_type: hsdo_Temporal_Resolution_Range
    - description: hsdo_Sub_Experiment_Id → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/deeef0af-f305-4fd4-9796-e9e1906e5e15
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/e95a1ee1-8a3e-47dd-aa5c-c2d66377bfc7
        example_subject_type: hsdo_Sub_Experiment_Id
    - description: hsdo_Experiment → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/386eb378-1d17-4fdb-b0de-7aec4db7be59
        example_object_type: hsdo_Platform
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/d91ab3c6-89b0-4748-b824-1e3d45e49049
        example_subject_type: hsdo_Experiment
    - description: hsdo_Measurement_Name → hsdo_Chronostratigraphic_Unit
      object:
        example_object: https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
        example_object_type: hsdo_Chronostratigraphic_Unit
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/7e304e75-b6b9-4e4b-bbaf-64a0a49d157d
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Platform → hsdo_Chronostratigraphic_Unit
      object:
        example_object: https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
        example_object_type: hsdo_Chronostratigraphic_Unit
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/82823ffa-e4d5-4877-bf0a-b9eb5b8c1108
        example_subject_type: hsdo_Platform
    - description: hsdo_Location → hsdo_Temporal_Resolution_Range
      object:
        example_object: https://climateKG.org/entity/99ef187e-6940-4c10-8d65-00d4426d493b
        example_object_type: hsdo_Temporal_Resolution_Range
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/82b62e59-6ea1-48e1-a402-bd386c5046eb
        example_subject_type: hsdo_Location
    - description: hsdo_Frequency → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/74d079b5-9b36-45c9-9b09-7e3646b65a85
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/8e4900ff-c7bc-47a1-aa55-a8892696d769
        example_subject_type: hsdo_Frequency
    - description: hsdo_Instrument → hsdo_Activity
      object:
        example_object: https://climateKG.org/entity/88dc22d3-1fb6-471a-94de-56acb94f0f58
        example_object_type: hsdo_Activity
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/9315c474-b65f-400d-beba-611c9a6a62cb
        example_subject_type: hsdo_Instrument
    - description: hsdo_Temporal_Resolution_Range → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/10a9c153-f37d-48fe-920d-c790d946ab07
        example_object_type: hsdo_Model
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/99ef187e-6940-4c10-8d65-00d4426d493b
        example_subject_type: hsdo_Temporal_Resolution_Range
    - description: hsdo_Temporal_Resolution_Range → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/ea213be5-fe37-4179-9a9b-030c2bf42cf5
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/99ef187e-6940-4c10-8d65-00d4426d493b
        example_subject_type: hsdo_Temporal_Resolution_Range
    - description: hsdo_Model → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/67290503-94b9-4517-b5b6-063bba2bee27
        example_object_type: hsdo_Platform
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/9a0c4d32-54c1-450e-aafd-f086678ed176
        example_subject_type: hsdo_Model
    - description: hsdo_Provider → hsdo_Measurement_Name
      object:
        example_object: https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
        example_object_type: hsdo_Measurement_Name
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/b9e718df-0a3a-46b6-a34f-4960e9449660
        example_subject_type: hsdo_Provider
    - description: hsdo_Institution → hsdo_Instrument
      object:
        example_object: https://climateKG.org/entity/ac87227c-b943-400a-ac61-71e42e8eb5f3
        example_object_type: hsdo_Instrument
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/a2e701d9-65e4-495c-b478-95b7d6a70ef8
        example_subject_type: hsdo_Institution
    - description: hsdo_Provider → hsdo_Platform
      object:
        example_object: https://climateKG.org/entity/d8bb1aa0-49d7-4a6a-a96e-66231b3fc7f6
        example_object_type: hsdo_Platform
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/a463163e-8e86-4086-8b10-8fd6a95fca4a
        example_subject_type: hsdo_Provider
    - description: hsdo_Platform → hsdo_Models
      object:
        example_object: https://climateKG.org/entity/eb539ad7-79ee-4d76-8e38-b298b2385626
        example_object_type: hsdo_Models
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/a9c4dcab-bbd0-4f67-b2c0-bbbe71b8245e
        example_subject_type: hsdo_Platform
    - description: hsdo_Provider → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/ba70b595-5263-4ffd-97a2-f86ba91681ae
        example_object_type: hsdo_Variable
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/d738d343-0440-4258-850d-107f9cd8072c
        example_subject_type: hsdo_Provider
    - description: hsdo_Data_Format → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/3b16a2e8-cc4d-40ce-a6c8-336bea211078
        example_object_type: hsdo_Provider
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ac392872-1571-4bfd-94dd-81f93d9f1fd0
        example_subject_type: hsdo_Data_Format
    - description: hsdo_Chronostratigraphic_Unit → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/160af7da-6036-4af5-ba04-d666df8a0daa
        example_object_type: hsdo_Variable
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/c98a4c91-1b1d-464d-8380-497a186db7eb
        example_subject_type: hsdo_Chronostratigraphic_Unit
    - description: hsdo_Provider → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/750f6c61-0f15-4185-94d8-c029dec04bc5
        example_object_type: hsdo_Provider
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/b45d57f9-5c45-4e46-8dcd-6158fee8151b
        example_subject_type: hsdo_Provider
    - description: hsdo_Measurement_Name → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
        example_object_type: hsdo_Project
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Measurement_Name → hsdo_Model
      object:
        example_object: https://climateKG.org/entity/db28e274-27f4-4006-a363-32a98eab859d
        example_object_type: hsdo_Model
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Measurement_Name → hsdo_Data_Format
      object:
        example_object: https://climateKG.org/entity/ebe6f3c4-a78f-4152-977c-296d42e4e9e8
        example_object_type: hsdo_Data_Format
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/bbafe0e9-38c1-4124-9bbd-ce0a83e4ca6e
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Provider → hsdo_Chronostratigraphic_Unit
      object:
        example_object: https://climateKG.org/entity/afd62c36-fd25-4673-a56d-85be8d47f3d0
        example_object_type: hsdo_Chronostratigraphic_Unit
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/be92ce0f-2f1f-4649-a3b2-36360964187a
        example_subject_type: hsdo_Provider
    - description: hsdo_Provider → hsdo_Cmip6_Source_Id
      object:
        example_object: https://climateKG.org/entity/bff6b593-1884-4aea-87a1-36f606d3a020
        example_object_type: hsdo_Cmip6_Source_Id
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/be92ce0f-2f1f-4649-a3b2-36360964187a
        example_subject_type: hsdo_Provider
    - description: hsdo_Chronostratigraphic_Unit → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/5a7bb095-4d12-4232-bc75-b8e82197cb92
        example_object_type: hsdo_Project
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/c98a4c91-1b1d-464d-8380-497a186db7eb
        example_subject_type: hsdo_Chronostratigraphic_Unit
    - description: hsdo_Dataset → hsdo_Provider
      object:
        example_object: https://climateKG.org/entity/1411273b-4793-485b-91d6-1da4bfdaef22
        example_object_type: hsdo_Provider
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
        example_subject_type: hsdo_Dataset
    - description: hsdo_Dataset → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/4353d710-3d65-44b3-b988-26af1415646a
        example_object_type: hsdo_Science_Keyword
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
        example_subject_type: hsdo_Dataset
    - description: hsdo_Dataset → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/89fd4098-0bc4-4d26-a9fa-345390d7c9a9
        example_object_type: hsdo_Project
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/d3df0ea0-8954-4bea-aa01-c84c5d32eb54
        example_subject_type: hsdo_Dataset
    - description: hsdo_Platform → hsdo_Project
      object:
        example_object: https://climateKG.org/entity/6ffd7617-25fd-4464-bbd3-fc02e33ffafb
        example_object_type: hsdo_Project
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/d8bb1aa0-49d7-4a6a-a96e-66231b3fc7f6
        example_subject_type: hsdo_Platform
    - description: hsdo_Experiment → hsdo_Models
      object:
        example_object: https://climateKG.org/entity/640d703f-9312-4f11-8367-30a8bd8fc508
        example_object_type: hsdo_Models
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fa13c1b2-6be4-45c3-aefa-7918575a583d
        example_subject_type: hsdo_Experiment
    - description: hsdo_Data_Format → hsdo_Location
      object:
        example_object: https://climateKG.org/entity/a4202721-0cba-4fa1-853f-890f146b04f9
        example_object_type: hsdo_Location
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ebe6f3c4-a78f-4152-977c-296d42e4e9e8
        example_subject_type: hsdo_Data_Format
    - description: hsdo_Data_Format → hsdo_Science_Keyword
      object:
        example_object: https://climateKG.org/entity/75ab3537-34b1-4025-b758-7296626079ba
        example_object_type: hsdo_Science_Keyword
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/ddcd5941-9ba8-4c39-a498-1e214d1bfa6e
        example_subject_type: hsdo_Data_Format
    - description: hsdo_Model → hsdo_Models
      object:
        example_object: https://climateKG.org/entity/640d703f-9312-4f11-8367-30a8bd8fc508
        example_object_type: hsdo_Models
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/de62c07e-96c6-44fb-a3a1-cd2902305691
        example_subject_type: hsdo_Model
    - description: hsdo_Measurement_Name → hsdo_Variable
      object:
        example_object: https://climateKG.org/entity/1f1436a3-ac80-48e1-abbe-095fc74c9655
        example_object_type: hsdo_Variable
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/f4f7a865-befc-439b-8b6d-bb43ba772ba9
        example_subject_type: hsdo_Measurement_Name
    - description: hsdo_Project → hsdo_Sub_Experiment_Id
      object:
        example_object: https://climateKG.org/entity/04e00ed0-39b6-4323-a788-2344264695c0
        example_object_type: hsdo_Sub_Experiment_Id
        example_predicate: relation:MeasuredAt
        example_subject: https://climateKG.org/entity/fcce904f-2989-49bb-801f-8829c5f85644
        example_subject_type: hsdo_Project
    from_schema: climatepub4-kg
    rank: 1000
    slot_uri: relation:MeasuredAt
    alias: relation_MeasuredAt
    owner: hsdo_Horizontal_Resolution_Range
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
    - range: hsdo_Measurement_Name
    - range: hsdo_Project
    - range: hsdo_Sub_Experiment_Id
    - range: hsdo_Activity
    - range: hsdo_Related_Url_Content_Type
    - range: hsdo_Models
    - range: hsdo_Platform
    - range: hsdo_Cmip6_Source_Id
    - range: hsdo_Experiment
    - range: hsdo_Variable
    - range: hsdo_Provider
    - range: hsdo_Model
    - range: hsdo_Instrument
    - range: hsdo_Location
    - range: hsdo_Chronostratigraphic_Unit
    - range: hsdo_Temporal_Resolution_Range
    - range: hsdo_Data_Format
    - range: hsdo_Science_Keyword
    - range: hsdo_Dataset
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
    owner: hsdo_Horizontal_Resolution_Range
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
    owner: hsdo_Horizontal_Resolution_Range
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
class_uri: hsdo:Horizontal_Resolution_Range

```
</details>