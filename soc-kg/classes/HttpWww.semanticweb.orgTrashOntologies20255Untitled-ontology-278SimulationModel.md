

# Class: HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel




This class occurs 12 times.


URI: [http://www.semanticweb.org/trash/ontologies/2025/5/untitled-ontology-278/SimulationModel](http://www.semanticweb.org/trash/ontologies/2025/5/untitled-ontology-278/SimulationModel)






```mermaid
 classDiagram
    class HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel
    click HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel href "../HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel"
      HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel : rdfs_label
        
          
    
    
    HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 12 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss.md) | [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesModel](../slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesModel.md) | range | [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel.md) |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilChemicalSample](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilChemicalSample.md) | [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesModel](../slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesModel.md) | range | [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel.md) |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilPhysicalSample](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilPhysicalSample.md) | [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesModel](../slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesModel.md) | range | [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel.md) |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration.md) | [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesModel](../slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesModel.md) | range | [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel.md) |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea.md) | [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesModel](../slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesModel.md) | range | [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_SimulationModel
from_schema: okns:soc-kg
rank: 1000
slots:
- rdfs_label
class_uri: http://www.semanticweb.org/trash/ontologies/2025/5/untitled-ontology-278/SimulationModel

```
</details>

### Induced

<details>

```yaml
name: http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_SimulationModel
from_schema: okns:soc-kg
rank: 1000
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
    owner: http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_SimulationModel
    domain_of:
    - rdf_List
    - rdfs_Datatype
    - dcam_VocabularyEncodingScheme
    - dct_AgentClass
    - time_DayOfWeek
    - time_TemporalUnit
    - bibo_DocumentStatus
    - bibo_ThesisDegree
    - qudt_AspectClass
    - qudt_BinaryPrefix
    - qudt_BitEncodingType
    - qudt_BooleanEncodingType
    - qudt_ByteEncodingType
    - qudt_CardinalityType
    - qudt_CharEncodingType
    - qudt_ContextualUnit
    - qudt_CountingUnit
    - qudt_CurrencyUnit
    - qudt_DateTimeStringEncodingType
    - qudt_DecimalPrefix
    - qudt_DerivedUnit
    - qudt_DimensionlessUnit
    - qudt_EndianType
    - qudt_FloatingPointEncodingType
    - qudt_IntegerEncodingType
    - qudt_LogarithmicUnit
    - qudt_OrderedType
    - qudt_SignednessType
    - qudt_Unit
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
    - vaem_GraphMetaData
    - vaem_GraphRole
    - vaem_Party
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
    - rdf_DatatypeProperty
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
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Abstract
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_ActiveIngredient
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_AmendmentPlacement
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_AmendmentType
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_AnimalClass
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_AnimalSpecies
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_BookChapter
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_BroadleafOrGrass
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Cultivar
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_CuttingHeight
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Equipment
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_FundingSource
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_GrowthStage
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_HarvestedFraction
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Irrigation
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_JournalArticle
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Location
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_LossesOrDeposition
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_OtherEvents
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Parameter
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_PesticidePlacement
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_PesticideTarget
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_PlantFraction
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_PlantingMethod
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_PopularArticle
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Proceedings
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Report
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_SimulationModel
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_SpeciesMix
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_StartStopInterval
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_SurfaceOrLeaching
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Thesis
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_TillageEvent
    - http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_TillageMethod
    - https___lod.nal.usda.gov_nalt_7140
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
class_uri: http://www.semanticweb.org/trash/ontologies/2025/5/untitled-ontology-278/SimulationModel

```
</details>