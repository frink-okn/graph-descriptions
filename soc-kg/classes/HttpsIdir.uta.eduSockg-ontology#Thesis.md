

# Class: HttpsIdir.uta.eduSockg-ontology#Thesis




This class occurs 4 times.


URI: [https://idir.uta.edu/sockg-ontology#Thesis](https://idir.uta.edu/sockg-ontology#Thesis)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#Thesis
    click HttpsIdir.uta.eduSockg-ontology#Thesis href "../HttpsIdir.uta.eduSockg-ontology#Thesis"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontology#Thesis
        click DctBibliographicResource href "../DctBibliographicResource"
      
      HttpsIdir.uta.eduSockg-ontology#Thesis : dct_bibliographicCitation
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Thesis --> "0..1" RdfsLiteral : dct_bibliographicCitation
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpsIdir.uta.eduSockg-ontology#Thesis : dct_creator
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Thesis --> "0..1" Any : dct_creator
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#Thesis : dct_description
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Thesis --> "0..1" String : dct_description
    click String href "../String"

        
      HttpsIdir.uta.eduSockg-ontology#Thesis : dct_issued
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Thesis --> "0..1" Any : dct_issued
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#Thesis : dct_title
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Thesis --> "0..1" Any : dct_title
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#Thesis : https___idir.uta.edu_sockg_ontology#correspondingAuthor
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Thesis --> "0..1" String : https___idir.uta.edu_sockg_ontology#correspondingAuthor
    click String href "../String"

        
      HttpsIdir.uta.eduSockg-ontology#Thesis : rdfs_label
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Thesis --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```





## Inheritance
* [DctBibliographicResource](../classes/DctBibliographicResource.md)
    * **HttpsIdir.uta.eduSockg-ontology#Thesis**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [dct_issued](../slots/dct_issued.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md) | Recommended practice is to describe the date, date/time, or period of time as... <br/> description: Date of formal issuance of the resource. | direct | 4 |
| [https___idir.uta.edu_sockg_ontology#correspondingAuthor](../slots/https___idir.uta.edu_sockg_ontology#correspondingAuthor.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 1 |
| [dct_bibliographicCitation](../slots/dct_bibliographicCitation.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | Recommended practice is to include sufficient bibliographic detail to identif... <br/> description: A bibliographic reference for the resource. | direct | 4 |
| [dct_title](../slots/dct_title.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md) | A name given to the resource <br/>  | direct | 4 |
| [dct_description](../slots/dct_description.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | Description may include but is not limited to: an abstract, a table of conten... <br/> description: An account of the resource. | direct | 4 |
| [dct_creator](../slots/dct_creator.md) | 0..1 <br/> [Any](../classes/Any.md) | Recommended practice is to identify the creator with a URI <br/> description: An entity responsible for making the resource. | direct | 4 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 4 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) | [https___idir.uta.edu_sockg_ontology#cites](../slots/https___idir.uta.edu_sockg_ontology#cites.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Thesis](../classes/HttpsIdir.uta.eduSockg-ontology#Thesis.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Thesis
from_schema: okns:soc-kg
rank: 1000
is_a: dct_BibliographicResource
slots:
- dct_issued
- https___idir.uta.edu_sockg-ontology#correspondingAuthor
- dct_bibliographicCitation
- dct_title
- dct_description
- dct_creator
- rdfs_label
class_uri: https://idir.uta.edu/sockg-ontology#Thesis

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Thesis
from_schema: okns:soc-kg
rank: 1000
is_a: dct_BibliographicResource
attributes:
  dct_issued:
    name: dct_issued
    description: Recommended practice is to describe the date, date/time, or period
      of time as recommended for the property Date, of which this is a subproperty.
    title: Date Issued
    comments:
    - 'description: Date of formal issuance of the resource.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:issued
    alias: dct_issued
    owner: https___idir.uta.edu_sockg-ontology#Thesis
    domain_of:
    - dcam_VocabularyEncodingScheme
    - dct_AgentClass
    - https___idir.uta.edu_sockg-ontology#Abstract
    - https___idir.uta.edu_sockg-ontology#BookChapter
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#PopularArticle
    - https___idir.uta.edu_sockg-ontology#Proceedings
    - https___idir.uta.edu_sockg-ontology#Report
    - https___idir.uta.edu_sockg-ontology#Thesis
    subproperty_of: dct_date
    range: Any
    any_of:
    - range: date
    - range: rdfs_Literal
  https___idir.uta.edu_sockg-ontology#correspondingAuthor:
    name: https___idir.uta.edu_sockg-ontology#correspondingAuthor
    from_schema: okns:soc-kg
    rank: 1000
    domain: dct_BibliographicResource
    slot_uri: https://idir.uta.edu/sockg-ontology#correspondingAuthor
    alias: https___idir.uta.edu_sockg_ontology#correspondingAuthor
    owner: https___idir.uta.edu_sockg-ontology#Thesis
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Abstract
    - https___idir.uta.edu_sockg-ontology#BookChapter
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#PopularArticle
    - https___idir.uta.edu_sockg-ontology#Proceedings
    - https___idir.uta.edu_sockg-ontology#Report
    - https___idir.uta.edu_sockg-ontology#Thesis
    range: string
  dct_bibliographicCitation:
    name: dct_bibliographicCitation
    description: Recommended practice is to include sufficient bibliographic detail
      to identify the resource as unambiguously as possible.
    title: Bibliographic Citation
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: A bibliographic reference for the resource.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:bibliographicCitation
    alias: dct_bibliographicCitation
    owner: https___idir.uta.edu_sockg-ontology#Thesis
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Abstract
    - https___idir.uta.edu_sockg-ontology#BookChapter
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#PopularArticle
    - https___idir.uta.edu_sockg-ontology#Proceedings
    - https___idir.uta.edu_sockg-ontology#Report
    - https___idir.uta.edu_sockg-ontology#Thesis
    subproperty_of: dct_identifier
    range: rdfs_Literal
  dct_title:
    name: dct_title
    description: A name given to the resource.
    title: Title
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:title
    alias: dct_title
    owner: https___idir.uta.edu_sockg-ontology#Thesis
    domain_of:
    - vaem_GraphMetaData
    - https___idir.uta.edu_sockg-ontology#Abstract
    - https___idir.uta.edu_sockg-ontology#BookChapter
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#PopularArticle
    - https___idir.uta.edu_sockg-ontology#Proceedings
    - https___idir.uta.edu_sockg-ontology#Report
    - https___idir.uta.edu_sockg-ontology#Thesis
    subproperty_of: dc_title
    range: Any
    any_of:
    - range: string
    - range: rdfs_Literal
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
    owner: https___idir.uta.edu_sockg-ontology#Thesis
    domain_of:
    - qudt_BinaryPrefix
    - qudt_CardinalityType
    - qudt_ContextualUnit
    - qudt_CountingUnit
    - qudt_DecimalPrefix
    - qudt_DerivedUnit
    - qudt_DimensionlessUnit
    - qudt_LogarithmicUnit
    - qudt_Unit
    - vaem_GraphRole
    - https___idir.uta.edu_sockg-ontology#AnimalSpecies
    - https___idir.uta.edu_sockg-ontology#CoverCrop
    - https___idir.uta.edu_sockg-ontology#FertilizerAmendment
    - https___idir.uta.edu_sockg-ontology#GrazingRate
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Proceedings
    - https___idir.uta.edu_sockg-ontology#Project
    - https___idir.uta.edu_sockg-ontology#ProjectScenario
    - https___idir.uta.edu_sockg-ontology#ResidueRemoval
    - https___idir.uta.edu_sockg-ontology#Rotation
    - https___idir.uta.edu_sockg-ontology#Thesis
    - https___idir.uta.edu_sockg-ontology#Tillage
    - https___idir.uta.edu_sockg-ontology#Timing
    - https___idir.uta.edu_sockg-ontology#Treatment
    subproperty_of: dc_description
    range: string
  dct_creator:
    name: dct_creator
    description: Recommended practice is to identify the creator with a URI.  If this
      is not possible or feasible, a literal value that identifies the creator may
      be provided.
    title: Creator
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: An entity responsible for making the resource.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    exact_mappings:
    - http://xmlns.com/foaf/0.1/maker
    slot_uri: dct:creator
    alias: dct_creator
    owner: https___idir.uta.edu_sockg-ontology#Thesis
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Abstract
    - https___idir.uta.edu_sockg-ontology#BookChapter
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#PopularArticle
    - https___idir.uta.edu_sockg-ontology#Proceedings
    - https___idir.uta.edu_sockg-ontology#Report
    - https___idir.uta.edu_sockg-ontology#Thesis
    subproperty_of: dct_contributor
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
    owner: https___idir.uta.edu_sockg-ontology#Thesis
    domain_of:
    - dcam_VocabularyEncodingScheme
    - dct_AgentClass
    - rdf_List
    - rdfs_Datatype
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
    - time_DayOfWeek
    - time_TemporalUnit
    - bibo_DocumentStatus
    - bibo_ThesisDegree
    - vaem_GraphMetaData
    - vaem_GraphRole
    - vaem_Party
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
    - https___idir.uta.edu_sockg-ontology#Abstract
    - https___idir.uta.edu_sockg-ontology#ActiveIngredient
    - https___idir.uta.edu_sockg-ontology#AmendmentPlacement
    - https___idir.uta.edu_sockg-ontology#AmendmentType
    - https___idir.uta.edu_sockg-ontology#AnimalClass
    - https___idir.uta.edu_sockg-ontology#AnimalSpecies
    - https___idir.uta.edu_sockg-ontology#BookChapter
    - https___idir.uta.edu_sockg-ontology#BroadleafOrGrass
    - https___idir.uta.edu_sockg-ontology#ChamberPlacement
    - https___idir.uta.edu_sockg-ontology#Cultivar
    - https___idir.uta.edu_sockg-ontology#CuttingHeight
    - https___idir.uta.edu_sockg-ontology#Equipment
    - https___idir.uta.edu_sockg-ontology#FundingSource
    - https___idir.uta.edu_sockg-ontology#GrowthStage
    - https___idir.uta.edu_sockg-ontology#HarvestedFraction
    - https___idir.uta.edu_sockg-ontology#Irrigation
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#LossesOrDeposition
    - https___idir.uta.edu_sockg-ontology#OtherEvents
    - https___idir.uta.edu_sockg-ontology#Parameter
    - https___idir.uta.edu_sockg-ontology#PesticidePlacement
    - https___idir.uta.edu_sockg-ontology#PesticideTarget
    - https___idir.uta.edu_sockg-ontology#PlantFraction
    - https___idir.uta.edu_sockg-ontology#PlantingMethod
    - https___idir.uta.edu_sockg-ontology#PopularArticle
    - https___idir.uta.edu_sockg-ontology#Proceedings
    - https___idir.uta.edu_sockg-ontology#Report
    - https___idir.uta.edu_sockg-ontology#SimulationModel
    - https___idir.uta.edu_sockg-ontology#SpeciesMix
    - https___idir.uta.edu_sockg-ontology#StartStopInterval
    - https___idir.uta.edu_sockg-ontology#SurfaceOrLeaching
    - https___idir.uta.edu_sockg-ontology#Thesis
    - https___idir.uta.edu_sockg-ontology#TillageEvent
    - https___idir.uta.edu_sockg-ontology#TillageMethod
    - https___lod.nal.usda.gov_nalt_7140
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
class_uri: https://idir.uta.edu/sockg-ontology#Thesis

```
</details>