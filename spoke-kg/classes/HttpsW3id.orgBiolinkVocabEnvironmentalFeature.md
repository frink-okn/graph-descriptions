

# Class: HttpsW3id.orgBiolinkVocabEnvironmentalFeature




This class occurs 2 times.


URI: [https://w3id.org/biolink/vocab/EnvironmentalFeature](https://w3id.org/biolink/vocab/EnvironmentalFeature)






```mermaid
 classDiagram
    class HttpsW3id.orgBiolinkVocabEnvironmentalFeature
    click HttpsW3id.orgBiolinkVocabEnvironmentalFeature href "../HttpsW3id.orgBiolinkVocabEnvironmentalFeature"
      HttpsW3id.orgBiolinkVocabEnvironmentalFeature : dct_source
        
          
    
    
    HttpsW3id.orgBiolinkVocabEnvironmentalFeature --> "0..1" Any : dct_source
    click Any href "../Any"

        
      HttpsW3id.orgBiolinkVocabEnvironmentalFeature : https___purl.org_okn_frink_kg_spoke_schema_FOUNDIN_EfL
        
          
    
    
    HttpsW3id.orgBiolinkVocabEnvironmentalFeature --> "0..1" SdosAdministrativeArea : https___purl.org_okn_frink_kg_spoke_schema_FOUNDIN_EfL
    click SdosAdministrativeArea href "../SdosAdministrativeArea"

        
      HttpsW3id.orgBiolinkVocabEnvironmentalFeature : https___purl.org_okn_frink_kg_spoke_schema_ISA_EiE
        
          
    
    
    HttpsW3id.orgBiolinkVocabEnvironmentalFeature --> "0..1" HttpsW3id.orgBiolinkVocabEnvironmentalFeature : https___purl.org_okn_frink_kg_spoke_schema_ISA_EiE
    click HttpsW3id.orgBiolinkVocabEnvironmentalFeature href "../HttpsW3id.orgBiolinkVocabEnvironmentalFeature"

        
      HttpsW3id.orgBiolinkVocabEnvironmentalFeature : https___purl.org_okn_frink_kg_spoke_schema_synonyms
        
          
    
    
    HttpsW3id.orgBiolinkVocabEnvironmentalFeature --> "0..1" String : https___purl.org_okn_frink_kg_spoke_schema_synonyms
    click String href "../String"

        
      HttpsW3id.orgBiolinkVocabEnvironmentalFeature : rdfs_label
        
          
    
    
    HttpsW3id.orgBiolinkVocabEnvironmentalFeature --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [dct_source](../slots/dct_source.md) | 0..1 <br/> [Any](../classes/Any.md) | This property is intended to be used with non-literal values <br/> description: A related resource from which the described resource is derived. | direct | 2 |
| [https___purl.org_okn_frink_kg_spoke_schema_synonyms](../slots/https___purl.org_okn_frink_kg_spoke_schema_synonyms.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 2 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 2 |
| [https___purl.org_okn_frink_kg_spoke_schema_ISA_EiE](../slots/https___purl.org_okn_frink_kg_spoke_schema_ISA_EiE.md) | 0..1 <br/> [HttpsW3id.orgBiolinkVocabEnvironmentalFeature](../classes/HttpsW3id.orgBiolinkVocabEnvironmentalFeature.md) |  <br/>  | direct | 1 |
| [https___purl.org_okn_frink_kg_spoke_schema_FOUNDIN_EfL](../slots/https___purl.org_okn_frink_kg_spoke_schema_FOUNDIN_EfL.md) | 0..1 <br/> [SdosAdministrativeArea](../classes/SdosAdministrativeArea.md) |  <br/>  | direct | 11367 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsW3id.orgBiolinkVocabEnvironmentalFeature](../classes/HttpsW3id.orgBiolinkVocabEnvironmentalFeature.md) | [https___purl.org_okn_frink_kg_spoke_schema_ISA_EiE](../slots/https___purl.org_okn_frink_kg_spoke_schema_ISA_EiE.md) | range | [HttpsW3id.orgBiolinkVocabEnvironmentalFeature](../classes/HttpsW3id.orgBiolinkVocabEnvironmentalFeature.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___w3id.org_biolink_vocab_EnvironmentalFeature
from_schema: okns:spoke-kg
rank: 1000
slots:
- dct_source
- https___purl.org_okn_frink_kg_spoke_schema_synonyms
- rdfs_label
- https___purl.org_okn_frink_kg_spoke_schema_ISA_EiE
- https___purl.org_okn_frink_kg_spoke_schema_FOUNDIN_EfL
class_uri: https://w3id.org/biolink/vocab/EnvironmentalFeature

```
</details>

### Induced

<details>

```yaml
name: https___w3id.org_biolink_vocab_EnvironmentalFeature
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
    owner: https___w3id.org_biolink_vocab_EnvironmentalFeature
    domain_of:
    - https___purl.org_okn_frink_kg_spoke_schema_SDoH
    - https___w3id.org_biolink_vocab_ChemicalEntity
    - https___w3id.org_biolink_vocab_Disease
    - https___w3id.org_biolink_vocab_EnvironmentalFeature
    - https___w3id.org_biolink_vocab_OrganismTaxon
    subproperty_of: dct_relation
    range: Any
  https___purl.org_okn_frink_kg_spoke_schema_synonyms:
    name: https___purl.org_okn_frink_kg_spoke_schema_synonyms
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke/schema/synonyms
    alias: https___purl.org_okn_frink_kg_spoke_schema_synonyms
    owner: https___w3id.org_biolink_vocab_EnvironmentalFeature
    domain_of:
    - https___w3id.org_biolink_vocab_ChemicalEntity
    - https___w3id.org_biolink_vocab_EnvironmentalFeature
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
    owner: https___w3id.org_biolink_vocab_EnvironmentalFeature
    domain_of:
    - rdf_List
    - rdfs_Datatype
    - dcam_VocabularyEncodingScheme
    - dct_AgentClass
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
  https___purl.org_okn_frink_kg_spoke_schema_ISA_EiE:
    name: https___purl.org_okn_frink_kg_spoke_schema_ISA_EiE
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke/schema/ISA_EiE
    alias: https___purl.org_okn_frink_kg_spoke_schema_ISA_EiE
    owner: https___w3id.org_biolink_vocab_EnvironmentalFeature
    domain_of:
    - https___w3id.org_biolink_vocab_EnvironmentalFeature
    range: https___w3id.org_biolink_vocab_EnvironmentalFeature
  https___purl.org_okn_frink_kg_spoke_schema_FOUNDIN_EfL:
    name: https___purl.org_okn_frink_kg_spoke_schema_FOUNDIN_EfL
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke/schema/FOUNDIN_EfL
    alias: https___purl.org_okn_frink_kg_spoke_schema_FOUNDIN_EfL
    owner: https___w3id.org_biolink_vocab_EnvironmentalFeature
    domain_of:
    - https___w3id.org_biolink_vocab_EnvironmentalFeature
    range: sdos_AdministrativeArea
class_uri: https://w3id.org/biolink/vocab/EnvironmentalFeature

```
</details>