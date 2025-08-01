

# Class: Program Information System (fio-epa-frs_ProgramInformationSystem)


_An Information System maintained for an environmental program_






This class occurs 10 times.


URI: [fio-epa-frs:ProgramInformationSystem](http://w3id.org/fio/v1/epa-frs#ProgramInformationSystem)






```mermaid
 classDiagram
    class Fio-epa-frsProgramInformationSystem
    click Fio-epa-frsProgramInformationSystem href "../Fio-epa-frsProgramInformationSystem"
      OwlThing <|-- Fio-epa-frsProgramInformationSystem
        click OwlThing href "../OwlThing"
      
      Fio-epa-frsProgramInformationSystem : dct_description
        
          
    
    
    Fio-epa-frsProgramInformationSystem --> "0..1" String : dct_description
    click String href "../String"

        
      Fio-epa-frsProgramInformationSystem : owl_sameAs
        
          
    
    
    Fio-epa-frsProgramInformationSystem --> "0..1" OwlThing : owl_sameAs
    click OwlThing href "../OwlThing"

        
      Fio-epa-frsProgramInformationSystem : rdfs_label
        
          
    
    
    Fio-epa-frsProgramInformationSystem --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * **Fio-epa-frsProgramInformationSystem**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 10 |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md) | The property that determines that two given individuals are equal <br/> No occurrences of this slot in the graph. | direct | 10 |
| [dct_description](../slots/dct_description.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | Description may include but is not limited to: an abstract, a table of conten... <br/> description: An account of the resource. | direct | 10 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Node359](../classes/Node359.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node499](../classes/Node499.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node501](../classes/Node501.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node502](../classes/Node502.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node506](../classes/Node506.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node507](../classes/Node507.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node508](../classes/Node508.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node510](../classes/Node510.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node512](../classes/Node512.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node513](../classes/Node513.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node515](../classes/Node515.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node517](../classes/Node517.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node518](../classes/Node518.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node519](../classes/Node519.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node521](../classes/Node521.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Node523](../classes/Node523.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Fio-epa-frsLegacySystem](../classes/Fio-epa-frsLegacySystem.md) | [fio_epa_frs_replacedBy](../slots/fio_epa_frs_replacedBy.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Fio-epa-frsPermitSystem](../classes/Fio-epa-frsPermitSystem.md) | [fio_epa_frs_partOf](../slots/fio_epa_frs_partOf.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Fio-epa-frsRecord](../classes/Fio-epa-frsRecord.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Fio-epa-frsReportingSystem](../classes/Fio-epa-frsReportingSystem.md) | [fio_epa_frs_replacedBy](../slots/fio_epa_frs_replacedBy.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Fio-epa-frsReportingSystem](../classes/Fio-epa-frsReportingSystem.md) | [fio_epa_frs_partOf](../slots/fio_epa_frs_partOf.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Fio-epa-frsSiteSystem](../classes/Fio-epa-frsSiteSystem.md) | [fio_epa_frs_replacedBy](../slots/fio_epa_frs_replacedBy.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | [fio_epa_frs_fromSystem](../slots/fio_epa_frs_fromSystem.md) | any_of[range] | [Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: fio-epa-frs_ProgramInformationSystem
description: An Information System maintained for an environmental program
title: Program Information System
from_schema: okns:fiokg
exact_mappings:
- http://w3id.org/fio/v1/epa-frs#ProgramInformationSystem
rank: 1000
is_a: owl_Thing
slots:
- rdfs_label
- owl_sameAs
- dct_description
class_uri: fio-epa-frs:ProgramInformationSystem

```
</details>

### Induced

<details>

```yaml
name: fio-epa-frs_ProgramInformationSystem
description: An Information System maintained for an environmental program
title: Program Information System
from_schema: okns:fiokg
exact_mappings:
- http://w3id.org/fio/v1/epa-frs#ProgramInformationSystem
rank: 1000
is_a: owl_Thing
attributes:
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: fio-epa-frs_ProgramInformationSystem
    domain_of:
    - dcam_VocabularyEncodingScheme
    - owl_OntologyProperty
    - rdf_List
    - rdfs_Datatype
    - time_DayOfWeek
    - time_TemporalUnit
    - sdos_ActionStatusType
    - sdos_AdultOrientedEnumeration
    - sdos_BoardingPolicyType
    - sdos_BodyMeasurementTypeEnumeration
    - sdos_BookFormatType
    - sdos_Boolean
    - sdos_CarUsageType
    - sdos_CertificationStatusEnumeration
    - sdos_ContactPointOption
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
    - rdf_DatatypeProperty
    - vaem_GraphMetaData
    - vaem_GraphRole
    - vaem_Party
    - vaem_CatalogEntry
    - voag_Attribution
    - voag_AttributionLogo
    - voag_ChangeFrequency
    - voag_ChangeType
    - voag_ConfidentialityLevel
    - voag_CreativeCommonsPermission
    - voag_CreativeCommonsProhibition
    - voag_CreativeCommonsRequirement
    - voag_Governance
    - voag_GovernanceRole
    - voag_Icon
    - voag_IssueStatus
    - voag_LicenseModel
    - voag_Logo
    - voag_Maturity
    - voag_OrganizationLogo
    - voag_Pedigree
    - voag_PriorityValue
    - voag_ProductLogo
    - voag_Provenance
    - voag_PublicationStatus
    - voag_SchemaGraph
    - qudt_AspectClass
    - qudt_BitEncodingType
    - qudt_BooleanEncodingType
    - qudt_ByteEncodingType
    - qudt_CardinalityType
    - qudt_CharEncodingType
    - qudt_DateTimeStringEncodingType
    - qudt_EndianType
    - qudt_FloatingPointEncodingType
    - qudt_IntegerEncodingType
    - qudt_OrderedType
    - qudt_SignednessType
    - kwgo_AirPollutant
    - kwgo_BlueskyWildfireObservableProperty
    - kwgo_CensusObservableProperty
    - kwgo_ClimateObservableProperty
    - kwgo_CroplandObservableProperty
    - kwgo_DroughtIntensity
    - kwgo_FireCause
    - kwgo_HelipadAvailability
    - kwgo_HospitalStatus
    - kwgo_HospitalType
    - kwgo_ImpactObservableProperty
    - kwgo_LSADArea
    - kwgo_MTBSFireObservableProperty
    - kwgo_MagnitudeObservableProperty
    - kwgo_NIFCFireObservableProperty
    - kwgo_PublicHealthObservableProperty
    - kwgo_RoadType
    - kwgo_SmokePlumeObservableProperty
    - kwgo_SoilMapUnitObservableProperty
    - kwgo_StormTrackObservableProperty
    - kwgo_StormTrackletObservableProperty
    - kwgo_VulnerabilityObservableProperty
    - __node359
    - __node499
    - __node501
    - __node502
    - __node506
    - __node507
    - __node508
    - __node510
    - __node512
    - __node513
    - __node515
    - __node517
    - __node518
    - __node519
    - __node521
    - __node523
    - fio-epa-frs_Agency
    - fio-epa-frs_Agency.Agriculture
    - fio-epa-frs_Agency.Commerce
    - fio-epa-frs_Agency.Congress
    - fio-epa-frs_Agency.Defense
    - fio-epa-frs_Agency.Energy
    - fio-epa-frs_Agency.HealthandHumanServices
    - fio-epa-frs_Agency.HomelandSecurity
    - fio-epa-frs_Agency.HousingandUrbanDevelopment
    - fio-epa-frs_Agency.Interior
    - fio-epa-frs_Agency.Judicial
    - fio-epa-frs_Agency.Justice
    - fio-epa-frs_Agency.Labor
    - fio-epa-frs_Agency.State
    - fio-epa-frs_Agency.Transportation
    - fio-epa-frs_Agency.Treasury
    - fio-epa-frs_Agency.VeteransAffairs
    - fio-epa-frs_AirProgram
    - fio-epa-frs_AnimalOperation
    - fio-epa-frs_AssistanceSupportProgram
    - fio-epa-frs_ChemicalReleaseProgram
    - fio-epa-frs_ChemicalStorageProgram
    - fio-epa-frs_CoastalOceanProgram
    - fio-epa-frs_ComplianceInterest
    - fio-epa-frs_ComplianceSystem
    - fio-epa-frs_DrinkingWaterProgram
    - fio-epa-frs_EPA-PFAS-Facility
    - fio-epa-frs_EcologyOperation
    - fio-epa-frs_ElectronicPermitSystem
    - fio-epa-frs_EnforcementInterest
    - fio-epa-frs_EnforcementSystem
    - fio-epa-frs_EnvironmentalInterestByProgram
    - fio-epa-frs_EnvironmentalInterestType
    - fio-epa-frs_FRS-Facility
    - fio-epa-frs_FacilitySiteIdentification
    - fio-epa-frs_FacilityType
    - fio-epa-frs_GrantSystem
    - fio-epa-frs_GroundWaterProgram
    - fio-epa-frs_HazardousWasteProgram
    - fio-epa-frs_HealthSafetyProgram
    - fio-epa-frs_LegacySystem
    - fio-epa-frs_LegalEnforcementActivities
    - fio-epa-frs_PermitInterest
    - fio-epa-frs_PermitSystem
    - fio-epa-frs_PesticidesProgram
    - fio-epa-frs_ProgramInformationSystem
    - fio-epa-frs_ProjectSystem
    - fio-epa-frs_RadiationProtectionProgram
    - fio-epa-frs_RegistryInterest
    - fio-epa-frs_RegistrySystem
    - fio-epa-frs_RemediationRedevelopmentProgram
    - fio-epa-frs_ReportingInterest
    - fio-epa-frs_ReportingSystem
    - fio-epa-frs_RiskInterest
    - fio-epa-frs_SiteInterest
    - fio-epa-frs_SiteSystem
    - fio-epa-frs_SolidWasteProgram
    - fio-epa-frs_StateSystem
    - fio-epa-frs_SupplementalRecord
    - fio-epa-frs_TribalSystem
    - fio-epa-frs_UndergroundStorageTankProgram
    - fio-epa-frs_WasteWaterProgram
    - fio-epa-frs_WaterResourcesProgram
    - naics_NAICS-IndustryCode
    - naics_NAICS-IndustryGroup
    - naics_NAICS-IndustrySector
    - naics_NAICS-IndustrySubsector
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
  owl_sameAs:
    name: owl_sameAs
    description: The property that determines that two given individuals are equal.
    title: sameAs
    comments:
    - No occurrences of this slot in the graph.
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2002/07/owl#
    domain: owl_Thing
    slot_uri: owl:sameAs
    alias: owl_sameAs
    owner: fio-epa-frs_ProgramInformationSystem
    domain_of:
    - __node359
    - __node499
    - __node501
    - __node502
    - __node506
    - __node507
    - __node508
    - __node510
    - __node512
    - __node513
    - __node515
    - __node517
    - __node518
    - __node519
    - __node521
    - __node523
    - fio-epa-frs_Agency
    - fio-epa-frs_Agency.Agriculture
    - fio-epa-frs_Agency.Commerce
    - fio-epa-frs_Agency.Congress
    - fio-epa-frs_Agency.Defense
    - fio-epa-frs_Agency.Energy
    - fio-epa-frs_Agency.HealthandHumanServices
    - fio-epa-frs_Agency.HomelandSecurity
    - fio-epa-frs_Agency.HousingandUrbanDevelopment
    - fio-epa-frs_Agency.Interior
    - fio-epa-frs_Agency.Judicial
    - fio-epa-frs_Agency.Justice
    - fio-epa-frs_Agency.Labor
    - fio-epa-frs_Agency.State
    - fio-epa-frs_Agency.Transportation
    - fio-epa-frs_Agency.Treasury
    - fio-epa-frs_Agency.VeteransAffairs
    - fio-epa-frs_AirProgram
    - fio-epa-frs_AnimalOperation
    - fio-epa-frs_AssistanceSupportProgram
    - fio-epa-frs_ChemicalReleaseProgram
    - fio-epa-frs_ChemicalStorageProgram
    - fio-epa-frs_CoastalOceanProgram
    - fio-epa-frs_ComplianceInterest
    - fio-epa-frs_ComplianceSystem
    - fio-epa-frs_DrinkingWaterProgram
    - fio-epa-frs_EPA-PFAS-Facility
    - fio-epa-frs_EcologyOperation
    - fio-epa-frs_ElectronicPermitSystem
    - fio-epa-frs_EnforcementInterest
    - fio-epa-frs_EnforcementSystem
    - fio-epa-frs_EnvironmentalInterestByProgram
    - fio-epa-frs_EnvironmentalInterestType
    - fio-epa-frs_FRS-Facility
    - fio-epa-frs_FacilitySiteIdentification
    - fio-epa-frs_FacilityType
    - fio-epa-frs_GrantSystem
    - fio-epa-frs_GroundWaterProgram
    - fio-epa-frs_HazardousWasteProgram
    - fio-epa-frs_HealthSafetyProgram
    - fio-epa-frs_LegacySystem
    - fio-epa-frs_LegalEnforcementActivities
    - fio-epa-frs_PermitInterest
    - fio-epa-frs_PermitSystem
    - fio-epa-frs_PesticidesProgram
    - fio-epa-frs_ProgramInformationSystem
    - fio-epa-frs_ProjectSystem
    - fio-epa-frs_RadiationProtectionProgram
    - fio-epa-frs_Record
    - fio-epa-frs_RegistryInterest
    - fio-epa-frs_RegistrySystem
    - fio-epa-frs_RemediationRedevelopmentProgram
    - fio-epa-frs_ReportingInterest
    - fio-epa-frs_ReportingSystem
    - fio-epa-frs_RiskInterest
    - fio-epa-frs_SiteInterest
    - fio-epa-frs_SiteSystem
    - fio-epa-frs_SolidWasteProgram
    - fio-epa-frs_StateSystem
    - fio-epa-frs_SupplementalRecord
    - fio-epa-frs_TribalSystem
    - fio-epa-frs_UndergroundStorageTankProgram
    - fio-epa-frs_WasteWaterProgram
    - fio-epa-frs_WaterResourcesProgram
    - fio_Industry
    - kwgo_S2Cell_Level13
    - naics_NAICS-IndustryCode
    - naics_NAICS-IndustryGroup
    - naics_NAICS-IndustrySector
    - naics_NAICS-IndustrySubsector
    range: owl_Thing
  dct_description:
    name: dct_description
    description: 'Description may include but is not limited to: an abstract, a table
      of contents, a graphical representation, or a free-text account of the resource.'
    title: Description
    comments:
    - 'description: An account of the resource.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:description
    alias: dct_description
    owner: fio-epa-frs_ProgramInformationSystem
    domain_of:
    - vaem_GraphRole
    - qudt_CardinalityType
    - __node359
    - __node499
    - __node501
    - __node502
    - __node507
    - __node508
    - __node510
    - __node512
    - __node513
    - __node517
    - __node519
    - __node521
    - __node523
    - fio-epa-frs_AirProgram
    - fio-epa-frs_AnimalOperation
    - fio-epa-frs_AssistanceSupportProgram
    - fio-epa-frs_ChemicalReleaseProgram
    - fio-epa-frs_ChemicalStorageProgram
    - fio-epa-frs_CoastalOceanProgram
    - fio-epa-frs_ComplianceInterest
    - fio-epa-frs_ComplianceSystem
    - fio-epa-frs_DrinkingWaterProgram
    - fio-epa-frs_EcologyOperation
    - fio-epa-frs_ElectronicPermitSystem
    - fio-epa-frs_EnforcementInterest
    - fio-epa-frs_EnforcementSystem
    - fio-epa-frs_EnvironmentalInterestByProgram
    - fio-epa-frs_FRS-Facility
    - fio-epa-frs_FacilitySiteIdentification
    - fio-epa-frs_GrantSystem
    - fio-epa-frs_GroundWaterProgram
    - fio-epa-frs_HazardousWasteProgram
    - fio-epa-frs_HealthSafetyProgram
    - fio-epa-frs_LegacySystem
    - fio-epa-frs_LegalEnforcementActivities
    - fio-epa-frs_PermitInterest
    - fio-epa-frs_PermitSystem
    - fio-epa-frs_PesticidesProgram
    - fio-epa-frs_ProgramInformationSystem
    - fio-epa-frs_ProjectSystem
    - fio-epa-frs_RadiationProtectionProgram
    - fio-epa-frs_RegistryInterest
    - fio-epa-frs_RegistrySystem
    - fio-epa-frs_RemediationRedevelopmentProgram
    - fio-epa-frs_ReportingInterest
    - fio-epa-frs_ReportingSystem
    - fio-epa-frs_RiskInterest
    - fio-epa-frs_SiteInterest
    - fio-epa-frs_SiteSystem
    - fio-epa-frs_SolidWasteProgram
    - fio-epa-frs_StateSystem
    - fio-epa-frs_SupplementalRecord
    - fio-epa-frs_TribalSystem
    - fio-epa-frs_UndergroundStorageTankProgram
    - fio-epa-frs_WasteWaterProgram
    - fio-epa-frs_WaterResourcesProgram
    subproperty_of: dc_description
    range: string
class_uri: fio-epa-frs:ProgramInformationSystem

```
</details>