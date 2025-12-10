

# Class: HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform




This class occurs 451 times.


URI: [https://nasa-gesdisc.proto-okn.net/kg/schema/Platform](https://nasa-gesdisc.proto-okn.net/kg/schema/Platform)






```mermaid
 classDiagram
    class HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform
    click HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform href "../HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform"
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : dct_subject
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform --> "0..1" Any : dct_subject
    click Any href "../Any"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : https___nasa_gesdisc.proto_okn.net_kg_schema_globalId
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform --> "0..1" String : https___nasa_gesdisc.proto_okn.net_kg_schema_globalId
    click String href "../String"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_INSTRUMENT
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform --> "0..1" HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument : https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_INSTRUMENT
    click HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument href "../HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : https___nasa_gesdisc.proto_okn.net_kg_schema_Type
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform --> "0..1" String : https___nasa_gesdisc.proto_okn.net_kg_schema_Type
    click String href "../String"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : rdfs_label
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_globalId](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_globalId.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 451 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](xsd:string) | A human-readable name for the subject <br/>  | direct | 451 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_Type](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_Type.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 444 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_INSTRUMENT](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_INSTRUMENT.md) | 0..1 <br/> [HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument.md) |  <br/>  | direct | 2526 |
| [dct_subject](../slots/dct_subject.md) | 0..1 <br/> [Any](../classes/Any.md) | Recommended practice is to refer to the subject with a URI <br/> description: A topic of the resource. | direct | 378 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset.md) | [https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_PLATFORM](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_PLATFORM.md) | range | [HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
from_schema: okns:nasa-gesdisc
rank: 1000
slots:
- https___nasa-gesdisc.proto-okn.net_kg_schema_globalId
- rdfs_label
- https___nasa-gesdisc.proto-okn.net_kg_schema_Type
- https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_INSTRUMENT
- dct_subject
class_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/Platform

```
</details>

### Induced

<details>

```yaml
name: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
from_schema: okns:nasa-gesdisc
rank: 1000
attributes:
  https___nasa-gesdisc.proto-okn.net_kg_schema_globalId:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_globalId
    from_schema: okns:nasa-gesdisc
    rank: 1000
    slot_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
    alias: https___nasa_gesdisc.proto_okn.net_kg_schema_globalId
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Project
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    - https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
    range: string
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    domain_of:
    - rdf_List
    - rdfs_Datatype
    - sdos_ActionStatusType
    - sdos_AdultOrientedEnumeration
    - sdos_BoardingPolicyType
    - sdos_BodyMeasurementTypeEnumeration
    - sdos_BookFormatType
    - sdos_Boolean
    - sdos_CarUsageType
    - sdos_CertificationStatusEnumeration
    - sdos_ContactPointOption
    - sdos_DataType
    - sdos_DayOfWeek
    - sdos_DeliveryMethod
    - sdos_DigitalDocumentPermissionType
    - sdos_DigitalPlatformEnumeration
    - sdos_DriveWheelConfigurationValue
    - sdos_DrugCostCategory
    - sdos_DrugPregnancyCategory
    - sdos_DrugPrescriptionStatus
    - sdos_EUEnergyEfficiencyEnumeration
    - sdos_EnergyStarEnergyEfficiencyEnumeration
    - sdos_EventAttendanceModeEnumeration
    - sdos_EventStatusType
    - sdos_FulfillmentTypeEnumeration
    - sdos_GameAvailabilityEnumeration
    - sdos_GamePlayMode
    - sdos_GameServerStatus
    - sdos_GenderType
    - sdos_GovernmentBenefitsType
    - sdos_HealthAspectEnumeration
    - sdos_IPTCDigitalSourceEnumeration
    - sdos_IncentiveQualifiedExpenseType
    - sdos_IncentiveStatus
    - sdos_IncentiveType
    - sdos_InfectiousAgentClass
    - sdos_ItemAvailability
    - sdos_ItemListOrderType
    - sdos_LegalForceStatus
    - sdos_LegalValueLevel
    - sdos_MapCategoryType
    - sdos_MeasurementMethodEnum
    - sdos_MediaManipulationRatingEnumeration
    - sdos_MedicalAudienceType
    - sdos_MedicalDevicePurpose
    - sdos_MedicalEvidenceLevel
    - sdos_MedicalImagingTechnique
    - sdos_MedicalObservationalStudyDesign
    - sdos_MedicalProcedureType
    - sdos_MedicalSpecialty
    - sdos_MedicalStudyStatus
    - sdos_MedicalTrialDesign
    - sdos_MedicineSystem
    - sdos_MerchantReturnEnumeration
    - sdos_MusicAlbumProductionType
    - sdos_MusicAlbumReleaseType
    - sdos_MusicReleaseFormatType
    - sdos_NLNonprofitType
    - sdos_OfferItemCondition
    - sdos_OrderStatus
    - sdos_PaymentMethodType
    - sdos_PaymentStatusType
    - sdos_PhysicalActivityCategory
    - sdos_PhysicalExam
    - sdos_PriceComponentTypeEnumeration
    - sdos_PriceTypeEnumeration
    - sdos_ProductReturnEnumeration
    - sdos_PurchaseType
    - sdos_RefundTypeEnumeration
    - sdos_ReservationStatusType
    - sdos_RestrictedDiet
    - sdos_ReturnFeesEnumeration
    - sdos_ReturnLabelSourceEnumeration
    - sdos_ReturnMethodEnumeration
    - sdos_RsvpResponseType
    - sdos_SizeSystemEnumeration
    - sdos_SteeringPositionValue
    - sdos_TierBenefitEnumeration
    - sdos_UKNonprofitType
    - sdos_USNonprofitType
    - sdos_WearableMeasurementTypeEnumeration
    - sdos_WearableSizeGroupEnumeration
    - sdos_WearableSizeSystemEnumeration
    - dcam_VocabularyEncodingScheme
    - dct_AgentClass
    - time_DayOfWeek
    - time_TemporalUnit
    - https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Project
    - https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
  https___nasa-gesdisc.proto-okn.net_kg_schema_Type:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_Type
    from_schema: okns:nasa-gesdisc
    rank: 1000
    slot_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/Type
    alias: https___nasa_gesdisc.proto_okn.net_kg_schema_Type
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    range: string
  https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_INSTRUMENT:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_INSTRUMENT
    from_schema: okns:nasa-gesdisc
    rank: 1000
    slot_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/HAS_INSTRUMENT
    alias: https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_INSTRUMENT
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    range: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
  dct_subject:
    name: dct_subject
    description: Recommended practice is to refer to the subject with a URI. If this
      is not possible or feasible, a literal value that identifies the subject may
      be provided. Both should preferably refer to a subject in a controlled vocabulary.
    title: Subject
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: A topic of the resource.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:subject
    alias: dct_subject
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Project
    subproperty_of: dc_subject
    range: Any
class_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/Platform

```
</details>