

# Class: HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH




This class occurs 1426 times.


URI: [https://purl.org/okn/frink/kg/spoke/schema/SDoH](https://purl.org/okn/frink/kg/spoke/schema/SDoH)






```mermaid
 classDiagram
    class HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH
    click HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH href "../HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH"
      HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH : dct_source
        
          
    
    
    HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH --> "0..1" Any : dct_source
    click Any href "../Any"

        
      HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH : https___purl.org_okn_frink_kg_spoke_schema_ASSOCIATES_SaD
        
          
    
    
    HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH --> "0..1" HttpsW3id.orgBiolinkVocabDisease : https___purl.org_okn_frink_kg_spoke_schema_ASSOCIATES_SaD
    click HttpsW3id.orgBiolinkVocabDisease href "../HttpsW3id.orgBiolinkVocabDisease"

        
      HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH : https___purl.org_okn_frink_kg_spoke_schema_data_source
        
          
    
    
    HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH --> "0..1" String : https___purl.org_okn_frink_kg_spoke_schema_data_source
    click String href "../String"

        
      HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH : https___purl.org_okn_frink_kg_spoke_schema_domain
        
          
    
    
    HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH --> "0..1" String : https___purl.org_okn_frink_kg_spoke_schema_domain
    click String href "../String"

        
      HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH : https___purl.org_okn_frink_kg_spoke_schema_ISA_SiS
        
          
    
    
    HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH --> "0..1" HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH : https___purl.org_okn_frink_kg_spoke_schema_ISA_SiS
    click HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH href "../HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH"

        
      HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH : https___purl.org_okn_frink_kg_spoke_schema_mesh_ids
        
          
    
    
    HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH --> "0..1" Uri : https___purl.org_okn_frink_kg_spoke_schema_mesh_ids
    click Uri href "../Uri"

        
      HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH : https___purl.org_okn_frink_kg_spoke_schema_PREVALENCEIN_SpL
        
          
    
    
    HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH --> "0..1" SdosAdministrativeArea : https___purl.org_okn_frink_kg_spoke_schema_PREVALENCEIN_SpL
    click SdosAdministrativeArea href "../SdosAdministrativeArea"

        
      HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH : https___purl.org_okn_frink_kg_spoke_schema_topic
        
          
    
    
    HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH --> "0..1" String : https___purl.org_okn_frink_kg_spoke_schema_topic
    click String href "../String"

        
      HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH : rdfs_comment
        
          
    
    
    HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH --> "0..1" Any : rdfs_comment
    click Any href "../Any"

        
      HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH : rdfs_label
        
          
    
    
    HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [dct_source](../slots/dct_source.md) | 0..1 <br/> [Any](../classes/Any.md) | This property is intended to be used with non-literal values <br/> description: A related resource from which the described resource is derived. | direct | 1426 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 1426 |
| [https___purl.org_okn_frink_kg_spoke_schema_data_source](../slots/https___purl.org_okn_frink_kg_spoke_schema_data_source.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 1061 |
| [https___purl.org_okn_frink_kg_spoke_schema_mesh_ids](../slots/https___purl.org_okn_frink_kg_spoke_schema_mesh_ids.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) |  <br/>  | direct | 10 |
| [https___purl.org_okn_frink_kg_spoke_schema_PREVALENCEIN_SpL](../slots/https___purl.org_okn_frink_kg_spoke_schema_PREVALENCEIN_SpL.md) | 0..1 <br/> [SdosAdministrativeArea](../classes/SdosAdministrativeArea.md) |  <br/>  | direct | 2999117 |
| [https___purl.org_okn_frink_kg_spoke_schema_ISA_SiS](../slots/https___purl.org_okn_frink_kg_spoke_schema_ISA_SiS.md) | 0..1 <br/> [HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH](../classes/HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH.md) |  <br/>  | direct | 999 |
| [https___purl.org_okn_frink_kg_spoke_schema_ASSOCIATES_SaD](../slots/https___purl.org_okn_frink_kg_spoke_schema_ASSOCIATES_SaD.md) | 0..1 <br/> [HttpsW3id.orgBiolinkVocabDisease](../classes/HttpsW3id.orgBiolinkVocabDisease.md) |  <br/>  | direct | 39 |
| [https___purl.org_okn_frink_kg_spoke_schema_domain](../slots/https___purl.org_okn_frink_kg_spoke_schema_domain.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 1061 |
| [rdfs_comment](../slots/rdfs_comment.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A description of the subject resource <br/>  | direct | 1368 |
| [https___purl.org_okn_frink_kg_spoke_schema_topic](../slots/https___purl.org_okn_frink_kg_spoke_schema_topic.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 1061 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH](../classes/HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH.md) | [https___purl.org_okn_frink_kg_spoke_schema_ISA_SiS](../slots/https___purl.org_okn_frink_kg_spoke_schema_ISA_SiS.md) | range | [HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH](../classes/HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___purl.org_okn_frink_kg_spoke_schema_SDoH
from_schema: okns:spoke-kg
rank: 1000
slots:
- dct_source
- rdfs_label
- https___purl.org_okn_frink_kg_spoke_schema_data_source
- https___purl.org_okn_frink_kg_spoke_schema_mesh_ids
- https___purl.org_okn_frink_kg_spoke_schema_PREVALENCEIN_SpL
- https___purl.org_okn_frink_kg_spoke_schema_ISA_SiS
- https___purl.org_okn_frink_kg_spoke_schema_ASSOCIATES_SaD
- https___purl.org_okn_frink_kg_spoke_schema_domain
- rdfs_comment
- https___purl.org_okn_frink_kg_spoke_schema_topic
class_uri: https://purl.org/okn/frink/kg/spoke/schema/SDoH

```
</details>

### Induced

<details>

```yaml
name: https___purl.org_okn_frink_kg_spoke_schema_SDoH
from_schema: okns:spoke-kg
rank: 1000
attributes:
  dct_source:
    name: dct_source
    description: This property is intended to be used with non-literal values. The
      described resource may be derived from the related resource in whole or in part.
      Best practice is to identify the related resource by means of a URI or a string
      conforming to a formal identification system.
    title: Source
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: A related resource from which the described resource is derived.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:source
    alias: dct_source
    owner: https___purl.org_okn_frink_kg_spoke_schema_SDoH
    domain_of:
    - https___purl.org_okn_frink_kg_spoke_schema_SDoH
    - https___w3id.org_biolink_vocab_ChemicalEntity
    - https___w3id.org_biolink_vocab_Disease
    - https___w3id.org_biolink_vocab_EnvironmentalFeature
    - https___w3id.org_biolink_vocab_OrganismTaxon
    subproperty_of: dct_relation
    range: Any
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: https___purl.org_okn_frink_kg_spoke_schema_SDoH
    domain_of:
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
    - rdf_List
    - rdfs_Datatype
    - dcam_VocabularyEncodingScheme
    - dct_AgentClass
    - time_DayOfWeek
    - time_TemporalUnit
    - https___purl.org_okn_frink_kg_spoke_schema_SDoH
    - https___w3id.org_biolink_vocab_ChemicalEntity
    - https___w3id.org_biolink_vocab_Disease
    - https___w3id.org_biolink_vocab_EnvironmentalFeature
    - https___w3id.org_biolink_vocab_Gene
    - https___w3id.org_biolink_vocab_OrganismTaxon
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
  https___purl.org_okn_frink_kg_spoke_schema_data_source:
    name: https___purl.org_okn_frink_kg_spoke_schema_data_source
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke/schema/data_source
    alias: https___purl.org_okn_frink_kg_spoke_schema_data_source
    owner: https___purl.org_okn_frink_kg_spoke_schema_SDoH
    domain_of:
    - https___purl.org_okn_frink_kg_spoke_schema_SDoH
    range: string
  https___purl.org_okn_frink_kg_spoke_schema_mesh_ids:
    name: https___purl.org_okn_frink_kg_spoke_schema_mesh_ids
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke/schema/mesh_ids
    alias: https___purl.org_okn_frink_kg_spoke_schema_mesh_ids
    owner: https___purl.org_okn_frink_kg_spoke_schema_SDoH
    domain_of:
    - https___purl.org_okn_frink_kg_spoke_schema_SDoH
    range: uri
  https___purl.org_okn_frink_kg_spoke_schema_PREVALENCEIN_SpL:
    name: https___purl.org_okn_frink_kg_spoke_schema_PREVALENCEIN_SpL
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke/schema/PREVALENCEIN_SpL
    alias: https___purl.org_okn_frink_kg_spoke_schema_PREVALENCEIN_SpL
    owner: https___purl.org_okn_frink_kg_spoke_schema_SDoH
    domain_of:
    - https___purl.org_okn_frink_kg_spoke_schema_SDoH
    range: sdos_AdministrativeArea
  https___purl.org_okn_frink_kg_spoke_schema_ISA_SiS:
    name: https___purl.org_okn_frink_kg_spoke_schema_ISA_SiS
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke/schema/ISA_SiS
    alias: https___purl.org_okn_frink_kg_spoke_schema_ISA_SiS
    owner: https___purl.org_okn_frink_kg_spoke_schema_SDoH
    domain_of:
    - https___purl.org_okn_frink_kg_spoke_schema_SDoH
    range: https___purl.org_okn_frink_kg_spoke_schema_SDoH
  https___purl.org_okn_frink_kg_spoke_schema_ASSOCIATES_SaD:
    name: https___purl.org_okn_frink_kg_spoke_schema_ASSOCIATES_SaD
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke/schema/ASSOCIATES_SaD
    alias: https___purl.org_okn_frink_kg_spoke_schema_ASSOCIATES_SaD
    owner: https___purl.org_okn_frink_kg_spoke_schema_SDoH
    domain_of:
    - https___purl.org_okn_frink_kg_spoke_schema_SDoH
    range: https___w3id.org_biolink_vocab_Disease
  https___purl.org_okn_frink_kg_spoke_schema_domain:
    name: https___purl.org_okn_frink_kg_spoke_schema_domain
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke/schema/domain
    alias: https___purl.org_okn_frink_kg_spoke_schema_domain
    owner: https___purl.org_okn_frink_kg_spoke_schema_SDoH
    domain_of:
    - https___purl.org_okn_frink_kg_spoke_schema_SDoH
    range: string
  rdfs_comment:
    name: rdfs_comment
    description: A description of the subject resource.
    title: comment
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:comment
    alias: rdfs_comment
    owner: https___purl.org_okn_frink_kg_spoke_schema_SDoH
    domain_of:
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
    - rdf_List
    - rdfs_Datatype
    - dcam_VocabularyEncodingScheme
    - dct_AgentClass
    - https___purl.org_okn_frink_kg_spoke_schema_SDoH
    - https___w3id.org_biolink_vocab_Gene
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
  https___purl.org_okn_frink_kg_spoke_schema_topic:
    name: https___purl.org_okn_frink_kg_spoke_schema_topic
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke/schema/topic
    alias: https___purl.org_okn_frink_kg_spoke_schema_topic
    owner: https___purl.org_okn_frink_kg_spoke_schema_SDoH
    domain_of:
    - https___purl.org_okn_frink_kg_spoke_schema_SDoH
    range: string
class_uri: https://purl.org/okn/frink/kg/spoke/schema/SDoH

```
</details>