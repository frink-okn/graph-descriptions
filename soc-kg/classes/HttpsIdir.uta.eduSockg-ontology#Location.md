

# Class: HttpsIdir.uta.eduSockg-ontology#Location




This class occurs 58 times.


URI: [https://idir.uta.edu/sockg-ontology#Location](https://idir.uta.edu/sockg-ontology#Location)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#Location
    click HttpsIdir.uta.eduSockg-ontology#Location href "../HttpsIdir.uta.eduSockg-ontology#Location"
      GeoFeature <|-- HttpsIdir.uta.eduSockg-ontology#Location
        click GeoFeature href "../GeoFeature"
      
      HttpsIdir.uta.eduSockg-ontology#Location : dct_description
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Location --> "0..1" String : dct_description
    click String href "../String"

        
      HttpsIdir.uta.eduSockg-ontology#Location : dct_identifier
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Location --> "0..1" RdfsLiteral : dct_identifier
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpsIdir.uta.eduSockg-ontology#Location : geo_hasGeometry
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Location --> "0..1" GeoGeometry : geo_hasGeometry
    click GeoGeometry href "../GeoGeometry"

        
      HttpsIdir.uta.eduSockg-ontology#Location : https___idir.uta.edu_sockg_ontology#cites
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Location --> "0..1" Any : https___idir.uta.edu_sockg_ontology#cites
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#Location : https___idir.uta.edu_sockg_ontology#endDate
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Location --> "0..1" Date : https___idir.uta.edu_sockg_ontology#endDate
    click Date href "../Date"

        
      HttpsIdir.uta.eduSockg-ontology#Location : https___idir.uta.edu_sockg_ontology#fundedBy
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Location --> "0..1" HttpsIdir.uta.eduSockg-ontology#FundingSource : https___idir.uta.edu_sockg_ontology#fundedBy
    click HttpsIdir.uta.eduSockg-ontology#FundingSource href "../HttpsIdir.uta.eduSockg-ontology#FundingSource"

        
      HttpsIdir.uta.eduSockg-ontology#Location : https___idir.uta.edu_sockg_ontology#hasTreatment
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Location --> "0..1" HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#hasTreatment
    click HttpsIdir.uta.eduSockg-ontology#Treatment href "../HttpsIdir.uta.eduSockg-ontology#Treatment"

        
      HttpsIdir.uta.eduSockg-ontology#Location : https___idir.uta.edu_sockg_ontology#startDate
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Location --> "0..1" Date : https___idir.uta.edu_sockg_ontology#startDate
    click Date href "../Date"

        
      HttpsIdir.uta.eduSockg-ontology#Location : kwgo_sfContains
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Location --> "0..1" Any : kwgo_sfContains
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#Location : kwgo_sfWithin
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Location --> "0..1" Any : kwgo_sfWithin
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#Location : rdfs_label
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Location --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#Location : spatial_connectedTo
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Location --> "0..1" Any : spatial_connectedTo
    click Any href "../Any"

        
      
```





## Inheritance
* [GeoSpatialObject](../classes/GeoSpatialObject.md)
    * [GeoFeature](../classes/GeoFeature.md)
        * **HttpsIdir.uta.eduSockg-ontology#Location**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [geo_hasGeometry](../slots/geo_hasGeometry.md) | 0..1 <br/> [GeoGeometry](../classes/GeoGeometry.md) | A spatial representation for a given Feature <br/> source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties<br/>source: http://www.opengis.net/ont/geosparql#<br/>source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties<br/>description: A spatial representation for a given Feature. | direct | 41 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 58 |
| [kwgo_sfContains](../slots/kwgo_sfContains.md) | 0..1 <br/> [Any](../classes/Any.md) | KWG's spatial contains relation <br/>  | direct | 3912 |
| [https___idir.uta.edu_sockg_ontology#hasTreatment](../slots/https___idir.uta.edu_sockg_ontology#hasTreatment.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |  <br/>  | direct | 769 |
| [dct_identifier](../slots/dct_identifier.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | Recommended practice is to identify the resource by means of a string conform... <br/> description: An unambiguous reference to the resource within a given context. | direct | 58 |
| [spatial_connectedTo](../slots/spatial_connectedTo.md) | 0..1 <br/> [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#Site](../classes/HttpsIdir.uta.eduSockg-ontology#Site.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |  <br/>  | direct | 1102 |
| [https___idir.uta.edu_sockg_ontology#endDate](../slots/https___idir.uta.edu_sockg_ontology#endDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 58 |
| [dct_description](../slots/dct_description.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | Description may include but is not limited to: an abstract, a table of conten... <br/> description: An account of the resource. | direct | 116 |
| [kwgo_sfWithin](../slots/kwgo_sfWithin.md) | 0..1 <br/> [Any](../classes/Any.md) | KWG's spatial within relation <br/>  | direct | 166 |
| [https___idir.uta.edu_sockg_ontology#fundedBy](../slots/https___idir.uta.edu_sockg_ontology#fundedBy.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#FundingSource](../classes/HttpsIdir.uta.eduSockg-ontology#FundingSource.md) |  <br/>  | direct | 54 |
| [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 58 |
| [https___idir.uta.edu_sockg_ontology#cites](../slots/https___idir.uta.edu_sockg_ontology#cites.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Thesis](../classes/HttpsIdir.uta.eduSockg-ontology#Thesis.md)&nbsp;or&nbsp;<br />[DctBibliographicResource](../classes/DctBibliographicResource.md)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#Report](../classes/HttpsIdir.uta.eduSockg-ontology#Report.md)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#PopularArticle](../classes/HttpsIdir.uta.eduSockg-ontology#PopularArticle.md)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#BookChapter](../classes/HttpsIdir.uta.eduSockg-ontology#BookChapter.md)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#Abstract](../classes/HttpsIdir.uta.eduSockg-ontology#Abstract.md)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#Proceedings](../classes/HttpsIdir.uta.eduSockg-ontology#Proceedings.md)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#JournalArticle](../classes/HttpsIdir.uta.eduSockg-ontology#JournalArticle.md) |  <br/>  | direct | 177 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) | [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#endDate](../slots/https___idir.uta.edu_sockg_ontology#endDate.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) | [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#GrazingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingManagement.md) | [https___idir.uta.edu_sockg_ontology#endDate](../slots/https___idir.uta.edu_sockg_ontology#endDate.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#GrazingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingManagement.md) | [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) | [https___idir.uta.edu_sockg_ontology#hasTreatment](../slots/https___idir.uta.edu_sockg_ontology#hasTreatment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) | [https___idir.uta.edu_sockg_ontology#endDate](../slots/https___idir.uta.edu_sockg_ontology#endDate.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) | [https___idir.uta.edu_sockg_ontology#fundedBy](../slots/https___idir.uta.edu_sockg_ontology#fundedBy.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) | [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) | [https___idir.uta.edu_sockg_ontology#cites](../slots/https___idir.uta.edu_sockg_ontology#cites.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#PlantingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantingManagement.md) | [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#ResidueManagement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueManagement.md) | [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#Site](../classes/HttpsIdir.uta.eduSockg-ontology#Site.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#TillageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#TillageManagement.md) | [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [HttpsIdir.uta.eduSockg-ontology#WeatherObservation](../classes/HttpsIdir.uta.eduSockg-ontology#WeatherObservation.md) | [https___idir.uta.edu_sockg_ontology#weatherAt](../slots/https___idir.uta.edu_sockg_ontology#weatherAt.md) | range | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Location
from_schema: okns:soc-kg
rank: 1000
is_a: geo_Feature
slots:
- geo_hasGeometry
- rdfs_label
- kwgo_sfContains
- https___idir.uta.edu_sockg-ontology#hasTreatment
- dct_identifier
- spatial_connectedTo
- https___idir.uta.edu_sockg-ontology#endDate
- dct_description
- kwgo_sfWithin
- https___idir.uta.edu_sockg-ontology#fundedBy
- https___idir.uta.edu_sockg-ontology#startDate
- https___idir.uta.edu_sockg-ontology#cites
class_uri: https://idir.uta.edu/sockg-ontology#Location

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Location
from_schema: okns:soc-kg
rank: 1000
is_a: geo_Feature
attributes:
  geo_hasGeometry:
    name: geo_hasGeometry
    description: A spatial representation for a given Feature.
    title: No slot (predicate) name specified -- this slot is noted as a subproperty
      of another slot in this graph but has not itself been defined.
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties'
    - 'source: http://www.opengis.net/ont/geosparql#'
    - 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties'
    - 'description: A spatial representation for a given Feature.'
    from_schema: okns:geo
    source: http://www.opengis.net/ont/geosparql#
    domain: geo_Feature
    slot_uri: geo:hasGeometry
    alias: geo_hasGeometry
    owner: https___idir.uta.edu_sockg-ontology#Location
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Location
    range: geo_Geometry
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: https___idir.uta.edu_sockg-ontology#Location
    domain_of:
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
    - dcam_VocabularyEncodingScheme
    - dct_AgentClass
    - rdf_List
    - rdfs_Datatype
    - vaem_GraphMetaData
    - vaem_GraphRole
    - vaem_Party
    - time_DayOfWeek
    - time_TemporalUnit
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
    - bibo_DocumentStatus
    - bibo_ThesisDegree
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
  kwgo_sfContains:
    name: kwgo_sfContains
    description: KWG's spatial contains relation
    title: contains (simple feature)
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:kwg
    slot_uri: kwgo:sfContains
    alias: kwgo_sfContains
    owner: https___idir.uta.edu_sockg-ontology#Location
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Site
    subproperty_of: kwgo_spatialRelation
    range: Any
  https___idir.uta.edu_sockg-ontology#hasTreatment:
    name: https___idir.uta.edu_sockg-ontology#hasTreatment
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#hasTreatment
    alias: https___idir.uta.edu_sockg_ontology#hasTreatment
    owner: https___idir.uta.edu_sockg-ontology#Location
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Location
    range: https___idir.uta.edu_sockg-ontology#Treatment
  dct_identifier:
    name: dct_identifier
    description: Recommended practice is to identify the resource by means of a string
      conforming to an identification system. Examples include International Standard
      Book Number (ISBN), Digital Object Identifier (DOI), and Uniform Resource Name
      (URN).  Persistent identifiers should be provided as HTTP URIs.
    title: Identifier
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: An unambiguous reference to the resource within a given context.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:identifier
    alias: dct_identifier
    owner: https___idir.uta.edu_sockg-ontology#Location
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Site
    - https___idir.uta.edu_sockg-ontology#Treatment
    subproperty_of: dc_identifier
    range: rdfs_Literal
  spatial_connectedTo:
    name: spatial_connectedTo
    title: topological connection (spatial contact) (sawgraph)
    from_schema: okns:soc-kg
    rank: 1000
    slot_uri: spatial:connectedTo
    alias: spatial_connectedTo
    owner: https___idir.uta.edu_sockg-ontology#Location
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Site
    - kwgo_S2Cell_Level13
    subproperty_of: spatial_spatiallyRelatedTo
    range: Any
    any_of:
    - range: kwgo_AdministrativeRegion_2
    - range: https___idir.uta.edu_sockg-ontology#Site
    - range: kwgo_S2Cell_Level13
    - range: https___idir.uta.edu_sockg-ontology#Location
  https___idir.uta.edu_sockg-ontology#endDate:
    name: https___idir.uta.edu_sockg-ontology#endDate
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#endDate
    alias: https___idir.uta.edu_sockg_ontology#endDate
    owner: https___idir.uta.edu_sockg-ontology#Location
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#GrazingManagement
    - https___idir.uta.edu_sockg-ontology#Location
    range: date
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
    owner: https___idir.uta.edu_sockg-ontology#Location
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
  kwgo_sfWithin:
    name: kwgo_sfWithin
    description: KWG's spatial within relation
    title: within (simple feature)
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:kwg
    slot_uri: kwgo:sfWithin
    alias: kwgo_sfWithin
    owner: https___idir.uta.edu_sockg-ontology#Location
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Site
    - kwgo_S2Cell_Level13
    subproperty_of: kwgo_spatialRelation
    range: Any
  https___idir.uta.edu_sockg-ontology#fundedBy:
    name: https___idir.uta.edu_sockg-ontology#fundedBy
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#fundedBy
    alias: https___idir.uta.edu_sockg_ontology#fundedBy
    owner: https___idir.uta.edu_sockg-ontology#Location
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Location
    range: https___idir.uta.edu_sockg-ontology#FundingSource
  https___idir.uta.edu_sockg-ontology#startDate:
    name: https___idir.uta.edu_sockg-ontology#startDate
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#startDate
    alias: https___idir.uta.edu_sockg_ontology#startDate
    owner: https___idir.uta.edu_sockg-ontology#Location
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Amendment
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#GrazingManagement
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#PlantingManagement
    - https___idir.uta.edu_sockg-ontology#ResidueManagement
    - https___idir.uta.edu_sockg-ontology#TillageManagement
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: date
  https___idir.uta.edu_sockg-ontology#cites:
    name: https___idir.uta.edu_sockg-ontology#cites
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#cites
    alias: https___idir.uta.edu_sockg_ontology#cites
    owner: https___idir.uta.edu_sockg-ontology#Location
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Location
    range: Any
    any_of:
    - range: https___idir.uta.edu_sockg-ontology#Thesis
    - range: dct_BibliographicResource
    - range: https___idir.uta.edu_sockg-ontology#Report
    - range: https___idir.uta.edu_sockg-ontology#PopularArticle
    - range: https___idir.uta.edu_sockg-ontology#BookChapter
    - range: https___idir.uta.edu_sockg-ontology#Abstract
    - range: https___idir.uta.edu_sockg-ontology#Proceedings
    - range: https___idir.uta.edu_sockg-ontology#JournalArticle
class_uri: https://idir.uta.edu/sockg-ontology#Location

```
</details>