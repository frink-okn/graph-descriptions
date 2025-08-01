# SAWGraph FIO KG

The FIO KG is part of the SAWGraph project.



## Schema Diagram

```mermaid
erDiagram
DcamVocabularyEncodingScheme {
    uri rdfs_seeAlso  
    string rdfs_label  
    string rdfs_comment  
    date dct_issued  
    uri rdfs_isDefinedBy  
}
DcmitypeCollection {

}
DcmitypeDataset {

}
DcmitypeEvent {

}
DcmitypeImage {

}
DcmitypeInteractiveResource {

}
DcmitypeMovingImage {

}
DcmitypePhysicalObject {

}
DcmitypeService {

}
DcmitypeSoftware {

}
DcmitypeSound {

}
DcmitypeStillImage {

}
DcmitypeText {

}
DctAgent {

}
DctAgentClass {

}
DctBibliographicResource {

}
DctFileFormat {

}
DctFrequency {

}
DctJurisdiction {

}
DctLicenseDocument {

}
DctLinguisticSystem {

}
DctLocation {

}
DctLocationPeriodOrJurisdiction {

}
DctMediaType {

}
DctMediaTypeOrExtent {

}
DctMethodOfAccrual {

}
DctMethodOfInstruction {

}
DctPeriodOfTime {

}
DctPhysicalMedium {

}
DctPhysicalResource {

}
DctPolicy {

}
DctProvenanceStatement {

}
DctRightsStatement {

}
DctSizeOrDuration {

}
DctStandard {

}
ProvAccept {

}
ProvActivity {

}
ProvActivityInfluence {

}
ProvAgent {

}
ProvAgentInfluence {

}
ProvAssociation {

}
ProvAttribution {

}
ProvBundle {

}
ProvCollection {

}
ProvCommunication {

}
ProvContribute {

}
ProvContributor {

}
ProvCopyright {

}
ProvCreate {

}
ProvCreator {

}
ProvDelegation {

}
ProvDerivation {

}
ProvDictionary {

}
ProvDirectQueryService {

}
ProvEmptyCollection {

}
ProvEmptyDictionary {

}
ProvEnd {

}
ProvEntity {

}
ProvEntityInfluence {

}
ProvGeneration {

}
ProvInfluence {

}
ProvInsertion {

}
ProvInstantaneousEvent {

}
ProvInvalidation {

}
ProvKeyEntityPair {

}
ProvLocation {

}
ProvModify {

}
ProvOrganization {

}
ProvPerson {

}
ProvPlan {

}
ProvPrimarySource {

}
ProvPublish {

}
ProvPublisher {

}
ProvQuotation {

}
ProvRemoval {

}
ProvReplace {

}
ProvRevision {

}
ProvRightsAssignment {

}
ProvRightsHolder {

}
ProvRole {

}
ProvServiceDescription {

}
ProvSoftwareAgent {

}
ProvStart {

}
ProvSubmit {

}
ProvUsage {

}
GeoFeature {

}
GeoFeatureCollection {

}
GeoGeometry {

}
GeoGeometryCollection {

}
GeoSpatialObject {

}
GeoSpatialObjectCollection {

}
OwlAllDifferent {

}
OwlAllDisjointClasses {

}
OwlAllDisjointProperties {

}
OwlAnnotation {

}
OwlAnnotationProperty {

}
OwlAsymmetricProperty {

}
OwlAxiom {

}
OwlClass {

}
OwlDataRange {
    uri rdfs_isDefinedBy  
    uri rdfs_seeAlso  
    string rdfs_comment  
    string rdfs_label  
}
OwlDatatypeProperty {

}
OwlDeprecatedClass {

}
OwlDeprecatedProperty {

}
OwlFunctionalProperty {

}
OwlInverseFunctionalProperty {

}
OwlIrreflexiveProperty {

}
OwlNamedIndividual {

}
OwlNegativePropertyAssertion {

}
OwlNothing {

}
OwlObjectProperty {

}
OwlOntology {

}
OwlOntologyProperty {
    uri rdfs_isDefinedBy  
    string rdfs_comment  
    string rdfs_label  
}
OwlReflexiveProperty {

}
OwlRestriction {

}
OwlSymmetricProperty {

}
OwlThing {

}
OwlTransitiveProperty {

}
RdfAlt {

}
RdfBag {

}
RdfCompoundLiteral {

}
RdfList {
    uri rdfs_isDefinedBy  
    string rdfs_comment  
    string rdfs_label  
}
RdfProperty {

}
RdfSeq {

}
RdfStatement {

}
RdfsClass {

}
RdfsContainer {

}
RdfsContainerMembershipProperty {

}
RdfsDatatype {
    uri rdfs_isDefinedBy  
    uri rdfs_seeAlso  
    string rdfs_comment  
    string rdfs_label  
}
RdfsLiteral {

}
RdfsResource {

}
TimeDateTimeDescription {

}
TimeDateTimeInterval {

}
TimeDayOfWeek {
    string rdfs_label  
}
TimeDuration {

}
TimeDurationDescription {

}
TimeGeneralDateTimeDescription {

}
TimeGeneralDurationDescription {

}
TimeInstant {

}
TimeInterval {

}
TimeJanuary {

}
TimeMonthOfYear {

}
TimeProperInterval {

}
TimeTRS {

}
TimeTemporalDuration {

}
TimeTemporalEntity {

}
TimeTemporalPosition {

}
TimeTemporalUnit {
    decimal time_months  
    decimal time_seconds  
    decimal time_hours  
    decimal time_weeks  
    decimal time_minutes  
    decimal time_days  
    decimal time_years  
    string rdfs_label  
}
TimeTimePosition {

}
TimeTimeZone {

}
TimeYear {

}
XsdDateTimeStamp {

}
XsdDuration {

}
XsdGYear {

}
XsdGYearMonth {

}
SkosCollection {

}
SkosConcept {

}
SkosConceptScheme {

}
SkosOrderedCollection {

}
DtypeCodeList {

}
DtypeCompositeCodeList {

}
DtypeDerivedCodeList {

}
DtypeEnumeratedValue {

}
DtypeEnumeration {

}
DtypeSimpleCodeList {

}
DtypeValueReference {

}
XsdAnySimpleType {

}
Sdos3DModel {

}
SdosAMRadioChannel {

}
SdosAPIReference {

}
SdosAboutPage {

}
SdosAcceptAction {

}
SdosAccommodation {

}
SdosAccountingService {

}
SdosAchieveAction {

}
SdosAction {

}
SdosActionAccessSpecification {

}
SdosActionStatusType {
    string rdfs_label  
    string rdfs_comment  
}
SdosActivateAction {

}
SdosAddAction {

}
SdosAdministrativeArea {

}
SdosAdultEntertainment {

}
SdosAdultOrientedEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosAdvertiserContentArticle {

}
SdosAggregateOffer {

}
SdosAggregateRating {

}
SdosAgreeAction {

}
SdosAirline {

}
SdosAirport {

}
SdosAlignmentObject {

}
SdosAllocateAction {

}
SdosAmpStory {

}
SdosAmusementPark {

}
SdosAnalysisNewsArticle {

}
SdosAnatomicalStructure {

}
SdosAnatomicalSystem {

}
SdosAnimalShelter {

}
SdosAnswer {

}
SdosApartment {

}
SdosApartmentComplex {

}
SdosAppendAction {

}
SdosApplyAction {

}
SdosApprovedIndication {

}
SdosAquarium {

}
SdosArchiveComponent {

}
SdosArchiveOrganization {

}
SdosArriveAction {

}
SdosArtGallery {

}
SdosArtery {

}
SdosArticle {

}
SdosAskAction {

}
SdosAskPublicNewsArticle {

}
SdosAssessAction {

}
SdosAssignAction {

}
SdosAtlas {

}
SdosAttorney {

}
SdosAudience {

}
SdosAudioObject {

}
SdosAudioObjectSnapshot {

}
SdosAudiobook {

}
SdosAuthorizeAction {

}
SdosAutoBodyShop {

}
SdosAutoDealer {

}
SdosAutoPartsStore {

}
SdosAutoRental {

}
SdosAutoRepair {

}
SdosAutoWash {

}
SdosAutomatedTeller {

}
SdosAutomotiveBusiness {

}
SdosBackgroundNewsArticle {

}
SdosBakery {

}
SdosBankAccount {

}
SdosBankOrCreditUnion {

}
SdosBarOrPub {

}
SdosBarcode {

}
SdosBeach {

}
SdosBeautySalon {

}
SdosBedAndBreakfast {

}
SdosBedDetails {

}
SdosBedType {

}
SdosBefriendAction {

}
SdosBikeStore {

}
SdosBioChemEntity {

}
SdosBlog {

}
SdosBlogPosting {

}
SdosBloodTest {

}
SdosBoardingPolicyType {
    string rdfs_label  
    string rdfs_comment  
}
SdosBoatReservation {

}
SdosBoatTerminal {

}
SdosBoatTrip {

}
SdosBodyMeasurementTypeEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosBodyOfWater {

}
SdosBone {

}
SdosBook {

}
SdosBookFormatType {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosBookSeries {

}
SdosBookStore {

}
SdosBookmarkAction {

}
SdosBoolean {
    string rdfs_label  
    string rdfs_comment  
}
SdosBorrowAction {

}
SdosBowlingAlley {

}
SdosBrainStructure {

}
SdosBrand {

}
SdosBreadcrumbList {

}
SdosBrewery {

}
SdosBridge {

}
SdosBroadcastChannel {

}
SdosBroadcastEvent {

}
SdosBroadcastFrequencySpecification {

}
SdosBroadcastService {

}
SdosBrokerageAccount {

}
SdosBuddhistTemple {

}
SdosBusOrCoach {

}
SdosBusReservation {

}
SdosBusStation {

}
SdosBusStop {

}
SdosBusTrip {

}
SdosBusinessAudience {

}
SdosBusinessEntityType {

}
SdosBusinessEvent {

}
SdosBusinessFunction {

}
SdosBuyAction {

}
SdosCDCPMDRecord {

}
SdosCableOrSatelliteService {

}
SdosCafeOrCoffeeShop {

}
SdosCampground {

}
SdosCampingPitch {

}
SdosCanal {

}
SdosCancelAction {

}
SdosCar {

}
SdosCarUsageType {
    string rdfs_label  
    uri sdos_contributor  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosCasino {

}
SdosCategoryCode {

}
SdosCategoryCodeSet {

}
SdosCatholicChurch {

}
SdosCemetery {

}
SdosCertification {

}
SdosCertificationStatusEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosChapter {

}
SdosCheckAction {

}
SdosCheckInAction {

}
SdosCheckOutAction {

}
SdosCheckoutPage {

}
SdosChemicalSubstance {

}
SdosChildCare {

}
SdosChildrensEvent {

}
SdosChooseAction {

}
SdosChurch {

}
SdosCity {

}
SdosCityHall {

}
SdosCivicStructure {

}
SdosClaim {

}
SdosClaimReview {

}
SdosClass {

}
SdosClip {

}
SdosClothingStore {

}
SdosCode {

}
SdosCollection {

}
SdosCollectionPage {

}
SdosCollegeOrUniversity {

}
SdosComedyClub {

}
SdosComedyEvent {

}
SdosComicCoverArt {

}
SdosComicIssue {

}
SdosComicSeries {

}
SdosComicStory {

}
SdosComment {

}
SdosCommentAction {

}
SdosCommunicateAction {

}
SdosCompleteDataFeed {

}
SdosCompoundPriceSpecification {

}
SdosComputerLanguage {

}
SdosComputerStore {

}
SdosConfirmAction {

}
SdosConsortium {

}
SdosConstraintNode {

}
SdosConsumeAction {

}
SdosContactPage {

}
SdosContactPoint {

}
SdosContactPointOption {
    string rdfs_label  
    string rdfs_comment  
}
SdosContinent {

}
SdosControlAction {

}
SdosConvenienceStore {

}
SdosConversation {

}
SdosCookAction {

}
SdosCooperative {

}
SdosCorporation {

}
SdosCorrectionComment {

}
SdosCountry {

}
SdosCourse {

}
SdosCourseInstance {

}
SdosCourthouse {

}
SdosCoverArt {

}
SdosCovidTestingFacility {

}
SdosCreateAction {

}
SdosCreativeWork {

}
SdosCreativeWorkSeason {

}
SdosCreativeWorkSeries {

}
SdosCreditCard {

}
SdosCrematorium {

}
SdosCriticReview {

}
SdosCssSelectorType {

}
SdosCurrencyConversionService {

}
SdosDDxElement {

}
SdosDanceEvent {

}
SdosDanceGroup {

}
SdosDataCatalog {

}
SdosDataDownload {

}
SdosDataFeed {

}
SdosDataFeedItem {

}
SdosDataType {

}
SdosDataset {

}
SdosDate {

}
SdosDateTime {

}
SdosDatedMoneySpecification {

}
SdosDayOfWeek {
    string rdfs_label  
    uri sdos_sameAs  
    uri sdos_contributor  
    string rdfs_comment  
}
SdosDaySpa {

}
SdosDeactivateAction {

}
SdosDefenceEstablishment {

}
SdosDefinedRegion {

}
SdosDefinedTerm {

}
SdosDefinedTermSet {

}
SdosDeleteAction {

}
SdosDeliveryChargeSpecification {

}
SdosDeliveryEvent {

}
SdosDeliveryMethod {
    string rdfs_label  
    uri sdos_contributor  
    string rdfs_comment  
}
SdosDeliveryTimeSettings {

}
SdosDemand {

}
SdosDentist {

}
SdosDepartAction {

}
SdosDepartmentStore {

}
SdosDepositAccount {

}
SdosDiagnosticLab {

}
SdosDiagnosticProcedure {

}
SdosDiet {

}
SdosDietarySupplement {

}
SdosDigitalDocument {

}
SdosDigitalDocumentPermission {

}
SdosDigitalDocumentPermissionType {
    string rdfs_label  
    string rdfs_comment  
}
SdosDigitalPlatformEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosDisagreeAction {

}
SdosDiscoverAction {

}
SdosDiscussionForumPosting {

}
SdosDislikeAction {

}
SdosDistance {

}
SdosDistillery {

}
SdosDonateAction {

}
SdosDoseSchedule {

}
SdosDownloadAction {

}
SdosDrawAction {

}
SdosDrawing {

}
SdosDrinkAction {

}
SdosDriveWheelConfigurationValue {
    string rdfs_label  
    uri sdos_contributor  
    string rdfs_comment  
}
SdosDrug {

}
SdosDrugClass {

}
SdosDrugCost {

}
SdosDrugCostCategory {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosDrugLegalStatus {

}
SdosDrugPregnancyCategory {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosDrugPrescriptionStatus {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosDrugStrength {

}
SdosDryCleaningOrLaundry {

}
SdosDuration {

}
SdosEUEnergyEfficiencyEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosEatAction {

}
SdosEducationEvent {

}
SdosEducationalAudience {

}
SdosEducationalOccupationalCredential {

}
SdosEducationalOccupationalProgram {

}
SdosEducationalOrganization {

}
SdosElectrician {

}
SdosElectronicsStore {

}
SdosElementarySchool {

}
SdosEmailMessage {

}
SdosEmbassy {

}
SdosEmergencyService {

}
SdosEmployeeRole {

}
SdosEmployerAggregateRating {

}
SdosEmployerReview {

}
SdosEmploymentAgency {

}
SdosEndorseAction {

}
SdosEndorsementRating {

}
SdosEnergy {

}
SdosEnergyConsumptionDetails {

}
SdosEnergyEfficiencyEnumeration {

}
SdosEnergyStarEnergyEfficiencyEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosEngineSpecification {

}
SdosEntertainmentBusiness {

}
SdosEntryPoint {

}
SdosEnumeration {

}
SdosEpisode {

}
SdosEvent {

}
SdosEventAttendanceModeEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosEventReservation {

}
SdosEventSeries {

}
SdosEventStatusType {
    string rdfs_label  
    string rdfs_comment  
}
SdosEventVenue {

}
SdosExchangeRateSpecification {

}
SdosExerciseAction {

}
SdosExerciseGym {

}
SdosExercisePlan {

}
SdosExhibitionEvent {

}
SdosFAQPage {

}
SdosFMRadioChannel {

}
SdosFastFoodRestaurant {

}
SdosFestival {

}
SdosFilmAction {

}
SdosFinancialIncentive {

}
SdosFinancialProduct {

}
SdosFinancialService {

}
SdosFindAction {

}
SdosFireStation {

}
SdosFlight {

}
SdosFlightReservation {

}
SdosFloat {

}
SdosFloorPlan {

}
SdosFlorist {

}
SdosFollowAction {

}
SdosFoodEstablishment {

}
SdosFoodEstablishmentReservation {

}
SdosFoodEvent {

}
SdosFoodService {

}
SdosFulfillmentTypeEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosFundingAgency {

}
SdosFundingScheme {

}
SdosFurnitureStore {

}
SdosGame {

}
SdosGameAvailabilityEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosGamePlayMode {
    string rdfs_label  
    string rdfs_comment  
}
SdosGameServer {

}
SdosGameServerStatus {
    string rdfs_label  
    string rdfs_comment  
}
SdosGardenStore {

}
SdosGasStation {

}
SdosGatedResidenceCommunity {

}
SdosGenderType {
    string rdfs_label  
    string rdfs_comment  
}
SdosGene {

}
SdosGeneralContractor {

}
SdosGeoCircle {

}
SdosGeoCoordinates {

}
SdosGeoShape {

}
SdosGeospatialGeometry {

}
SdosGiveAction {

}
SdosGolfCourse {

}
SdosGovernmentBenefitsType {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosGovernmentBuilding {

}
SdosGovernmentOffice {

}
SdosGovernmentOrganization {

}
SdosGovernmentPermit {

}
SdosGovernmentService {

}
SdosGrant {

}
SdosGroceryStore {

}
SdosGuide {

}
SdosHVACBusiness {

}
SdosHackathon {

}
SdosHairSalon {

}
SdosHardwareStore {

}
SdosHealthAndBeautyBusiness {

}
SdosHealthAspectEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosHealthClub {

}
SdosHealthInsurancePlan {

}
SdosHealthPlanCostSharingSpecification {

}
SdosHealthPlanFormulary {

}
SdosHealthPlanNetwork {

}
SdosHealthTopicContent {

}
SdosHighSchool {

}
SdosHinduTemple {

}
SdosHobbyShop {

}
SdosHomeAndConstructionBusiness {

}
SdosHomeGoodsStore {

}
SdosHospital {

}
SdosHostel {

}
SdosHotel {

}
SdosHotelRoom {

}
SdosHouse {

}
SdosHousePainter {

}
SdosHowTo {

}
SdosHowToDirection {

}
SdosHowToItem {

}
SdosHowToSection {

}
SdosHowToStep {

}
SdosHowToSupply {

}
SdosHowToTip {

}
SdosHowToTool {

}
SdosHyperToc {

}
SdosHyperTocEntry {

}
SdosIPTCDigitalSourceEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
    uri sdos_source  
}
SdosIceCreamShop {

}
SdosIgnoreAction {

}
SdosImageGallery {

}
SdosImageObject {

}
SdosImageObjectSnapshot {

}
SdosImagingTest {

}
SdosIncentiveQualifiedExpenseType {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosIncentiveStatus {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosIncentiveType {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosIndividualPhysician {

}
SdosIndividualProduct {

}
SdosInfectiousAgentClass {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosInfectiousDisease {

}
SdosInformAction {

}
SdosInsertAction {

}
SdosInstallAction {

}
SdosInsuranceAgency {

}
SdosIntangible {

}
SdosInteger {

}
SdosInteractAction {

}
SdosInteractionCounter {

}
SdosInternetCafe {

}
SdosInvestmentFund {

}
SdosInvestmentOrDeposit {

}
SdosInviteAction {

}
SdosInvoice {

}
SdosItemAvailability {
    string rdfs_label  
    string rdfs_comment  
}
SdosItemList {

}
SdosItemListOrderType {
    string rdfs_label  
    string rdfs_comment  
}
SdosItemPage {

}
SdosJewelryStore {

}
SdosJobPosting {

}
SdosJoinAction {

}
SdosJoint {

}
SdosLakeBodyOfWater {

}
SdosLandform {

}
SdosLandmarksOrHistoricalBuildings {

}
SdosLanguage {

}
SdosLearningResource {

}
SdosLeaveAction {

}
SdosLegalForceStatus {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
    uri sdos_contributor  
    uri sdos_source  
}
SdosLegalService {

}
SdosLegalValueLevel {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
    uri sdos_contributor  
    uri sdos_source  
}
SdosLegislation {

}
SdosLegislationObject {

}
SdosLegislativeBuilding {

}
SdosLendAction {

}
SdosLibrary {

}
SdosLibrarySystem {

}
SdosLifestyleModification {

}
SdosLigament {

}
SdosLikeAction {

}
SdosLinkRole {

}
SdosLiquorStore {

}
SdosListItem {

}
SdosListenAction {

}
SdosLiteraryEvent {

}
SdosLiveBlogPosting {

}
SdosLoanOrCredit {

}
SdosLocalBusiness {

}
SdosLocationFeatureSpecification {

}
SdosLocksmith {

}
SdosLodgingBusiness {

}
SdosLodgingReservation {

}
SdosLoseAction {

}
SdosLymphaticVessel {

}
SdosManuscript {

}
SdosMap {

}
SdosMapCategoryType {
    string rdfs_label  
    string rdfs_comment  
}
SdosMarryAction {

}
SdosMass {

}
SdosMathSolver {

}
SdosMaximumDoseSchedule {

}
SdosMeasurementMethodEnum {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosMeasurementTypeEnumeration {

}
SdosMediaEnumeration {

}
SdosMediaGallery {

}
SdosMediaManipulationRatingEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosMediaObject {

}
SdosMediaReview {

}
SdosMediaReviewItem {

}
SdosMediaSubscription {

}
SdosMedicalAudience {

}
SdosMedicalAudienceType {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosMedicalBusiness {

}
SdosMedicalCause {

}
SdosMedicalClinic {

}
SdosMedicalCode {

}
SdosMedicalCondition {

}
SdosMedicalConditionStage {

}
SdosMedicalContraindication {

}
SdosMedicalDevice {

}
SdosMedicalDevicePurpose {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosMedicalEntity {

}
SdosMedicalEnumeration {

}
SdosMedicalEvidenceLevel {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosMedicalGuideline {

}
SdosMedicalGuidelineContraindication {

}
SdosMedicalGuidelineRecommendation {

}
SdosMedicalImagingTechnique {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosMedicalIndication {

}
SdosMedicalIntangible {

}
SdosMedicalObservationalStudy {

}
SdosMedicalObservationalStudyDesign {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosMedicalOrganization {

}
SdosMedicalProcedure {

}
SdosMedicalProcedureType {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosMedicalRiskCalculator {

}
SdosMedicalRiskEstimator {

}
SdosMedicalRiskFactor {

}
SdosMedicalRiskScore {

}
SdosMedicalScholarlyArticle {

}
SdosMedicalSign {

}
SdosMedicalSignOrSymptom {

}
SdosMedicalSpecialty {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosMedicalStudy {

}
SdosMedicalStudyStatus {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosMedicalSymptom {

}
SdosMedicalTest {

}
SdosMedicalTestPanel {

}
SdosMedicalTherapy {

}
SdosMedicalTrial {

}
SdosMedicalTrialDesign {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosMedicalWebPage {

}
SdosMedicineSystem {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosMeetingRoom {

}
SdosMemberProgram {

}
SdosMemberProgramTier {

}
SdosMensClothingStore {

}
SdosMenu {

}
SdosMenuItem {

}
SdosMenuSection {

}
SdosMerchantReturnEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosMerchantReturnPolicy {

}
SdosMerchantReturnPolicySeasonalOverride {

}
SdosMessage {

}
SdosMiddleSchool {

}
SdosMobileApplication {

}
SdosMobilePhoneStore {

}
SdosMolecularEntity {

}
SdosMonetaryAmount {

}
SdosMonetaryAmountDistribution {

}
SdosMonetaryGrant {

}
SdosMoneyTransfer {

}
SdosMortgageLoan {

}
SdosMosque {

}
SdosMotel {

}
SdosMotorcycle {

}
SdosMotorcycleDealer {

}
SdosMotorcycleRepair {

}
SdosMotorizedBicycle {

}
SdosMountain {

}
SdosMoveAction {

}
SdosMovie {

}
SdosMovieClip {

}
SdosMovieRentalStore {

}
SdosMovieSeries {

}
SdosMovieTheater {

}
SdosMovingCompany {

}
SdosMuscle {

}
SdosMuseum {

}
SdosMusicAlbum {

}
SdosMusicAlbumProductionType {
    string rdfs_label  
    uri sdos_contributor  
    string rdfs_comment  
}
SdosMusicAlbumReleaseType {
    string rdfs_label  
    uri sdos_contributor  
    string rdfs_comment  
}
SdosMusicComposition {

}
SdosMusicEvent {

}
SdosMusicGroup {

}
SdosMusicPlaylist {

}
SdosMusicRecording {

}
SdosMusicRelease {

}
SdosMusicReleaseFormatType {
    string rdfs_label  
    uri sdos_contributor  
    string rdfs_comment  
}
SdosMusicStore {

}
SdosMusicVenue {

}
SdosMusicVideoObject {

}
SdosNGO {

}
SdosNLNonprofitType {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosNailSalon {

}
SdosNerve {

}
SdosNewsArticle {

}
SdosNewsMediaOrganization {

}
SdosNewspaper {

}
SdosNightClub {

}
SdosNonprofitType {

}
SdosNotary {

}
SdosNoteDigitalDocument {

}
SdosNumber {

}
SdosNutritionInformation {

}
SdosObservation {

}
SdosOccupation {

}
SdosOccupationalExperienceRequirements {

}
SdosOccupationalTherapy {

}
SdosOceanBodyOfWater {

}
SdosOffer {

}
SdosOfferCatalog {

}
SdosOfferForLease {

}
SdosOfferForPurchase {

}
SdosOfferItemCondition {
    string rdfs_label  
    string rdfs_comment  
}
SdosOfferShippingDetails {

}
SdosOfficeEquipmentStore {

}
SdosOnDemandEvent {

}
SdosOnlineBusiness {

}
SdosOnlineStore {

}
SdosOpeningHoursSpecification {

}
SdosOpinionNewsArticle {

}
SdosOptician {

}
SdosOrder {

}
SdosOrderAction {

}
SdosOrderItem {

}
SdosOrderStatus {
    string rdfs_label  
    string rdfs_comment  
}
SdosOrganization {

}
SdosOrganizationRole {

}
SdosOrganizeAction {

}
SdosOutletStore {

}
SdosOwnershipInfo {

}
SdosPaintAction {

}
SdosPainting {

}
SdosPalliativeProcedure {

}
SdosParcelDelivery {

}
SdosParentAudience {

}
SdosPark {

}
SdosParkingFacility {

}
SdosPathologyTest {

}
SdosPatient {

}
SdosPawnShop {

}
SdosPayAction {

}
SdosPaymentCard {

}
SdosPaymentChargeSpecification {

}
SdosPaymentMethod {

}
SdosPaymentMethodType {
    string rdfs_label  
    string rdfs_comment  
}
SdosPaymentService {

}
SdosPaymentStatusType {
    string rdfs_label  
    string rdfs_comment  
}
SdosPeopleAudience {

}
SdosPerformAction {

}
SdosPerformanceRole {

}
SdosPerformingArtsTheater {

}
SdosPerformingGroup {

}
SdosPeriodical {

}
SdosPermit {

}
SdosPerson {

}
SdosPetStore {

}
SdosPharmacy {

}
SdosPhotograph {

}
SdosPhotographAction {

}
SdosPhysicalActivity {

}
SdosPhysicalActivityCategory {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosPhysicalExam {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
}
SdosPhysicalTherapy {

}
SdosPhysician {

}
SdosPhysiciansOffice {

}
SdosPlace {

}
SdosPlaceOfWorship {

}
SdosPlanAction {

}
SdosPlay {

}
SdosPlayAction {

}
SdosPlayGameAction {

}
SdosPlayground {

}
SdosPlumber {

}
SdosPodcastEpisode {

}
SdosPodcastSeason {

}
SdosPodcastSeries {

}
SdosPoliceStation {

}
SdosPoliticalParty {

}
SdosPond {

}
SdosPostOffice {

}
SdosPostalAddress {

}
SdosPostalCodeRangeSpecification {

}
SdosPoster {

}
SdosPreOrderAction {

}
SdosPrependAction {

}
SdosPreschool {

}
SdosPresentationDigitalDocument {

}
SdosPreventionIndication {

}
SdosPriceComponentTypeEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosPriceSpecification {

}
SdosPriceTypeEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosProduct {

}
SdosProductCollection {

}
SdosProductGroup {

}
SdosProductModel {

}
SdosProductReturnEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    string rdfs_comment  
    uri sdos_source  
}
SdosProductReturnPolicy {

}
SdosProfessionalService {

}
SdosProfilePage {

}
SdosProgramMembership {

}
SdosProject {

}
SdosPronounceableText {

}
SdosProperty {

}
SdosPropertyValue {

}
SdosPropertyValueSpecification {

}
SdosProtein {

}
SdosPsychologicalTreatment {

}
SdosPublicSwimmingPool {

}
SdosPublicToilet {

}
SdosPublicationEvent {

}
SdosPublicationIssue {

}
SdosPublicationVolume {

}
SdosPurchaseType {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosQAPage {

}
SdosQualitativeValue {

}
SdosQuantitativeValue {

}
SdosQuantitativeValueDistribution {

}
SdosQuantity {

}
SdosQuestion {

}
SdosQuiz {

}
SdosQuotation {

}
SdosQuoteAction {

}
SdosRVPark {

}
SdosRadiationTherapy {

}
SdosRadioBroadcastService {

}
SdosRadioChannel {

}
SdosRadioClip {

}
SdosRadioEpisode {

}
SdosRadioSeason {

}
SdosRadioSeries {

}
SdosRadioStation {

}
SdosRating {

}
SdosReactAction {

}
SdosReadAction {

}
SdosRealEstateAgent {

}
SdosRealEstateListing {

}
SdosReceiveAction {

}
SdosRecipe {

}
SdosRecommendation {

}
SdosRecommendedDoseSchedule {

}
SdosRecyclingCenter {

}
SdosRefundTypeEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosRegisterAction {

}
SdosRejectAction {

}
SdosRentAction {

}
SdosRentalCarReservation {

}
SdosRepaymentSpecification {

}
SdosReplaceAction {

}
SdosReplyAction {

}
SdosReport {

}
SdosReportageNewsArticle {

}
SdosReportedDoseSchedule {

}
SdosResearchOrganization {

}
SdosResearchProject {

}
SdosResearcher {

}
SdosReservation {

}
SdosReservationPackage {

}
SdosReservationStatusType {
    string rdfs_label  
    string rdfs_comment  
}
SdosReserveAction {

}
SdosReservoir {

}
SdosResidence {

}
SdosResort {

}
SdosRestaurant {

}
SdosRestrictedDiet {
    string rdfs_label  
    string rdfs_comment  
}
SdosResumeAction {

}
SdosReturnAction {

}
SdosReturnFeesEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosReturnLabelSourceEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosReturnMethodEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosReview {

}
SdosReviewAction {

}
SdosReviewNewsArticle {

}
SdosRiverBodyOfWater {

}
SdosRole {

}
SdosRoofingContractor {

}
SdosRoom {

}
SdosRsvpAction {

}
SdosRsvpResponseType {
    string rdfs_label  
    string rdfs_comment  
}
SdosSaleEvent {

}
SdosSatiricalArticle {

}
SdosSchedule {

}
SdosScheduleAction {

}
SdosScholarlyArticle {

}
SdosSchool {

}
SdosSchoolDistrict {

}
SdosScreeningEvent {

}
SdosSculpture {

}
SdosSeaBodyOfWater {

}
SdosSearchAction {

}
SdosSearchRescueOrganization {

}
SdosSearchResultsPage {

}
SdosSeason {

}
SdosSeat {

}
SdosSeekToAction {

}
SdosSelfStorage {

}
SdosSellAction {

}
SdosSendAction {

}
SdosSeries {

}
SdosService {

}
SdosServiceChannel {

}
SdosServicePeriod {

}
SdosShareAction {

}
SdosSheetMusic {

}
SdosShippingConditions {

}
SdosShippingDeliveryTime {

}
SdosShippingRateSettings {

}
SdosShippingService {

}
SdosShoeStore {

}
SdosShoppingCenter {

}
SdosShortStory {

}
SdosSingleFamilyResidence {

}
SdosSiteNavigationElement {

}
SdosSizeGroupEnumeration {

}
SdosSizeSpecification {

}
SdosSizeSystemEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosSkiResort {

}
SdosSocialEvent {

}
SdosSocialMediaPosting {

}
SdosSoftwareApplication {

}
SdosSoftwareSourceCode {

}
SdosSolveMathAction {

}
SdosSomeProducts {

}
SdosSpeakableSpecification {

}
SdosSpecialAnnouncement {

}
SdosSpecialty {

}
SdosSportingGoodsStore {

}
SdosSportsActivityLocation {

}
SdosSportsClub {

}
SdosSportsEvent {

}
SdosSportsOrganization {

}
SdosSportsTeam {

}
SdosSpreadsheetDigitalDocument {

}
SdosStadiumOrArena {

}
SdosState {

}
SdosStatement {

}
SdosStatisticalPopulation {

}
SdosStatisticalVariable {

}
SdosStatusEnumeration {

}
SdosSteeringPositionValue {
    string rdfs_label  
    uri sdos_contributor  
    string rdfs_comment  
}
SdosStore {

}
SdosStructuredValue {

}
SdosStupidType {

}
SdosSubscribeAction {

}
SdosSubstance {

}
SdosSubwayStation {

}
SdosSuite {

}
SdosSuperficialAnatomy {

}
SdosSurgicalProcedure {

}
SdosSuspendAction {

}
SdosSyllabus {

}
SdosSynagogue {

}
SdosTVClip {

}
SdosTVEpisode {

}
SdosTVSeason {

}
SdosTVSeries {

}
SdosTable {

}
SdosTakeAction {

}
SdosTattooParlor {

}
SdosTaxi {

}
SdosTaxiReservation {

}
SdosTaxiService {

}
SdosTaxiStand {

}
SdosTaxon {

}
SdosTechArticle {

}
SdosTelevisionChannel {

}
SdosTelevisionStation {

}
SdosTennisComplex {

}
SdosText {

}
SdosTextDigitalDocument {

}
SdosTextObject {

}
SdosTheaterEvent {

}
SdosTheaterGroup {

}
SdosTherapeuticProcedure {

}
SdosThesis {

}
SdosThing {

}
SdosTicket {

}
SdosTieAction {

}
SdosTierBenefitEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosTime {

}
SdosTipAction {

}
SdosTireShop {

}
SdosTouristAttraction {

}
SdosTouristDestination {

}
SdosTouristInformationCenter {

}
SdosTouristTrip {

}
SdosToyStore {

}
SdosTrackAction {

}
SdosTradeAction {

}
SdosTrainReservation {

}
SdosTrainStation {

}
SdosTrainTrip {

}
SdosTransferAction {

}
SdosTravelAction {

}
SdosTravelAgency {

}
SdosTreatmentIndication {

}
SdosTrip {

}
SdosTypeAndQuantityNode {

}
SdosUKNonprofitType {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosURL {

}
SdosUSNonprofitType {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosUnRegisterAction {

}
SdosUnitPriceSpecification {

}
SdosUpdateAction {

}
SdosUseAction {

}
SdosUserBlocks {

}
SdosUserCheckins {

}
SdosUserComments {

}
SdosUserDownloads {

}
SdosUserInteraction {

}
SdosUserLikes {

}
SdosUserPageVisits {

}
SdosUserPlays {

}
SdosUserPlusOnes {

}
SdosUserReview {

}
SdosUserTweets {

}
SdosVacationRental {

}
SdosVehicle {

}
SdosVein {

}
SdosVessel {

}
SdosVeterinaryCare {

}
SdosVideoGallery {

}
SdosVideoGame {

}
SdosVideoGameClip {

}
SdosVideoGameSeries {

}
SdosVideoObject {

}
SdosVideoObjectSnapshot {

}
SdosViewAction {

}
SdosVirtualLocation {

}
SdosVisualArtsEvent {

}
SdosVisualArtwork {

}
SdosVitalSign {

}
SdosVolcano {

}
SdosVoteAction {

}
SdosWPAdBlock {

}
SdosWPFooter {

}
SdosWPHeader {

}
SdosWPSideBar {

}
SdosWantAction {

}
SdosWarrantyPromise {

}
SdosWarrantyScope {

}
SdosWatchAction {

}
SdosWaterfall {

}
SdosWearAction {

}
SdosWearableMeasurementTypeEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosWearableSizeGroupEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosWearableSizeSystemEnumeration {
    string rdfs_label  
    uri sdos_isPartOf  
    uri sdos_source  
    string rdfs_comment  
}
SdosWebAPI {

}
SdosWebApplication {

}
SdosWebContent {

}
SdosWebPage {

}
SdosWebPageElement {

}
SdosWebSite {

}
SdosWholesaleStore {

}
SdosWinAction {

}
SdosWinery {

}
SdosWorkBasedProgram {

}
SdosWorkersUnion {

}
SdosWriteAction {

}
SdosXPathType {

}
SdosZoo {

}
FoafAgent {

}
FoafDocument {

}
Wn16Credential {

}
Wn16Endorsement-4 {

}
Wn16Event {

}
WotEncryptedDocument {

}
WotEndorsement {

}
WotPubKey {

}
WotSigEvent {

}
WotUser {

}
FoafGroup {

}
FoafImage {

}
FoafLabelProperty {

}
FoafOnlineAccount {

}
FoafOnlineChatAccount {

}
FoafOnlineEcommerceAccount {

}
FoafOnlineGamingAccount {

}
FoafOrganization {

}
FoafPerson {

}
FoafPersonalProfileDocument {

}
FoafProject {

}
AdmsAsset {

}
AdmsAssetDistribution {

}
AdmsAssetRepository {

}
AdmsIdentifier {

}
DcatCatalog {

}
DcatDataset {

}
DcatDistribution {

}
WgsPoint {

}
WgsSpatialThing {

}
IcalDomainOfRrule {

}
IcalListOfFloat {

}
IcalValarm {

}
IcalValueCAL-ADDRESS {

}
IcalValueDATE {

}
IcalValueDATE-TIME {

}
IcalValueDURATION {

}
IcalValuePERIOD {

}
IcalValueRECUR {

}
IcalVevent {

}
IcalVfreebusy {

}
IcalVjournal {

}
IcalVtimezone {

}
IcalVtodo {

}
AdmsSemanticAssetDistribution {
    string adms_accessURL  
}
RdfDatatypeProperty {
    string rdfs_comment  
    string rdfs_label  
}
VoidDataset {

}
VoidDatasetDescription {

}
VoidLinkset {

}
VoidTechnicalFeature {

}
VaemAspect {

}
VaemDimension {

}
VaemDiscipline {

}
VaemDomain {

}
VaemGraphMetaData {
    uri vaem_namespace  
    date dct_modified  
    string vaem_withAttributionTo  
    uri vaem_turtleFileURL  
    string vaem_name  
    string vaem_intent  
    string dct_title  
    string vaem_description  
    string rdfs_label  
    uri vaem_previousPublishedVersion  
    uri vaem_rdfxmlFileURL  
    string vaem_revision  
    uri vaem_latestPublishedVersion  
    uri vaem_usesNonImportedResource  
    uri vaem_logo  
    uri rdfs_isDefinedBy  
    string vaem_title  
    string vaem_namespacePrefix  
    string vaem_owner  
}
VaemGraphRole {
    string vaem_filePrefix  
    string dct_description  
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VaemParty {
    string vaem_name  
    string rdfs_label  
    uri vaem_url  
    uri rdfs_isDefinedBy  
}
VaemViewpoint {

}
VaemCatalogEntry {
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VaemDateUnion {

}
VoagAccredidation {

}
VoagAdministrativeEvent {

}
VoagApprovalEvent {

}
VoagApprovalProcess {

}
VoagAssignedRole {

}
VoagAttribution {
    string rdfs_label  
    uri voag_url  
    string voag_pointOfContact  
    uri rdfs_isDefinedBy  
    string vaem_name  
}
VoagAttributionLogo {
    string rdfs_label  
    string voag_height  
    string voag_width  
    uri rdfs_isDefinedBy  
    string vaem_description  
    uri voag_image  
    string voag_caption  
}
VoagCatalog {

}
VoagChangeFrequency {
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VoagChangeManagementProcess {

}
VoagChangeType {
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VoagConcurrenceEvent {

}
VoagConfidentialityLevel {
    string rdfs_label  
    integer dtype_order  
    uri rdfs_isDefinedBy  
    string vaem_description  
}
VoagCreativeCommonsJurisdiction {

}
VoagCreativeCommonsPermission {
    string rdfs_label  
    uri rdfs_isDefinedBy  
    string vaem_description  
}
VoagCreativeCommonsProhibition {
    string rdfs_label  
    uri rdfs_isDefinedBy  
    string vaem_description  
}
VoagCreativeCommonsRequirement {
    string rdfs_label  
    uri rdfs_isDefinedBy  
    string vaem_description  
    uri vaem_url  
}
VoagCreativeCommonsWork {

}
VoagDeletionEvent {

}
VoagDesignatedGovernanceRole {

}
VoagDocument {

}
VoagEnumeratedValue {

}
VoagEvent {

}
VoagFigure {

}
VoagGovernance {
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VoagGovernanceEvent {

}
VoagGovernanceProcess {

}
VoagGovernanceProtocol {

}
VoagGovernanceRole {
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VoagGovernedObject {

}
VoagGovernedService {

}
VoagGraph {

}
VoagIcon {
    string rdfs_label  
    string voag_height  
    string voag_width  
    uri rdfs_isDefinedBy  
    string vaem_description  
    uri voag_image  
    string voag_caption  
}
VoagImage {

}
VoagIssue {

}
VoagIssueResolutionProcess {

}
VoagIssueStatus {
    string rdfs_label  
    uri rdfs_isDefinedBy  
    string vaem_description  
}
VoagLicenseModel {
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VoagLogo {
    string rdfs_label  
    string voag_height  
    string voag_width  
    uri rdfs_isDefinedBy  
    string vaem_description  
    uri voag_image  
    string voag_caption  
}
VoagMaturity {
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VoagNonConcurrenceEvent {

}
VoagOrganization {

}
VoagOrganizationLogo {
    string rdfs_label  
    string voag_height  
    string voag_width  
    uri rdfs_isDefinedBy  
    string vaem_description  
    uri voag_image  
    string voag_caption  
}
VoagParty {

}
VoagPedigree {
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VoagPerson {

}
VoagPriorityValue {
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VoagProcess {

}
VoagProductLogo {
    string rdfs_label  
    string voag_height  
    string voag_width  
    uri rdfs_isDefinedBy  
    uri voag_image  
    string voag_caption  
    string vaem_description  
}
VoagProvenance {
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VoagPublicationStatus {
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VoagQualifier {

}
VoagRejectionEvent {

}
VoagRetreivalEvent {

}
VoagReviewEvent {

}
VoagSchemaGraph {
    string rdfs_label  
    uri rdfs_isDefinedBy  
}
VoagService {

}
VoagStakeholderGroup {

}
VoagStandard {

}
VoagVocabGraph {

}
QudtAbstractQuantityKind {

}
QudtAngleUnit {

}
QudtAspect {

}
QudtAspectClass {
    string rdfs_label  
    uri rdfs_isDefinedBy  
    string rdfs_comment  
}
QudtBaseDimensionMagnitude {

}
QudtBinaryPrefix {

}
QudtBitEncodingType {
    integer qudt_bits  
    uri rdfs_isDefinedBy  
    string rdfs_label  
}
QudtBooleanEncodingType {
    integer qudt_bits  
    uri rdfs_isDefinedBy  
    string rdfs_label  
    integer qudt_bytes  
}
QudtByteEncodingType {
    integer qudt_bytes  
    uri rdfs_isDefinedBy  
    string rdfs_label  
}
QudtCardinalityType {
    string dct_description  
    uri rdfs_isDefinedBy  
    string rdfs_label  
    string dtype_literal  
    uri qudt_informativeReference  
}
QudtCharEncodingType {
    string rdfs_label  
    integer qudt_bytes  
    uri rdfs_isDefinedBy  
}
QudtCitation {

}
QudtComment {

}
QudtConcept {

}
QudtConstantValue {

}
QudtContextualUnit {

}
QudtCountingUnit {

}
QudtCurrencyUnit {

}
QudtDataEncoding {

}
QudtDataItem {

}
QudtDatatype {

}
QudtDateTimeStringEncodingType {
    string rdfs_label  
    string qudt_allowedPattern  
    uri rdfs_isDefinedBy  
}
QudtDecimalPrefix {

}
QudtDerivedUnit {

}
QudtDimensionlessUnit {

}
QudtDiscipline {

}
QudtEncoding {

}
QudtEndianType {
    string rdfs_label  
    string dtype_literal  
    uri rdfs_isDefinedBy  
}
QudtEnumeratedValue {

}
QudtEnumeration {

}
QudtEnumerationScale {

}
QudtFigure {

}
QudtFloatingPointEncodingType {
    integer qudt_bytes  
    uri rdfs_isDefinedBy  
    string rdfs_label  
}
QudtIntegerEncodingType {
    integer qudt_bytes  
    uri rdfs_isDefinedBy  
    string rdfs_label  
}
QudtIntervalScale {

}
QudtLogarithmicUnit {

}
QudtMathsFunctionType {

}
QudtNISTSP811Comment {

}
QudtNominalScale {

}
QudtOrderedType {
    string rdfs_label  
    string dtype_literal  
    string qudt_plainTextDescription  
    uri rdfs_isDefinedBy  
}
QudtOrdinalScale {

}
QudtOrganization {

}
QudtPhysicalConstant {

}
QudtPlaneAngleUnit {

}
QudtPrefix {

}
QudtQuantifiable {

}
QudtQuantity {

}
QudtQuantityKind {

}
QudtQuantityKindDimensionVector {

}
QudtQuantityKindDimensionVectorCGS {

}
QudtQuantityKindDimensionVectorCGS-EMU {

}
QudtQuantityKindDimensionVectorCGS-ESU {

}
QudtQuantityKindDimensionVectorCGS-GAUSS {

}
QudtQuantityKindDimensionVectorCGS-LH {

}
QudtQuantityKindDimensionVectorISO {

}
QudtQuantityKindDimensionVectorImperial {

}
QudtQuantityKindDimensionVectorSI {

}
QudtQuantityType {

}
QudtQuantityValue {

}
QudtRatioScale {

}
QudtRule {

}
QudtRuleType {

}
QudtScalarDatatype {

}
QudtScale {

}
QudtScaleType {

}
QudtSignednessType {
    string rdfs_label  
    string dtype_literal  
    uri rdfs_isDefinedBy  
}
QudtSolidAngleUnit {

}
QudtStatement {

}
QudtStringEncodingType {

}
QudtSymbol {

}
QudtSystemOfQuantityKinds {

}
QudtSystemOfUnits {

}
QudtTransformType {

}
QudtUnit {

}
QudtUserQuantityKind {

}
QudtVerifiable {

}
XsdString {

}
Gnis-ld-usgsAirport {

}
Gnis-ld-usgsArch {

}
Gnis-ld-usgsArea {

}
Gnis-ld-usgsArroyo {

}
Gnis-ld-usgsBar {

}
Gnis-ld-usgsBasin {

}
Gnis-ld-usgsBay {

}
Gnis-ld-usgsBeach {

}
Gnis-ld-usgsBench {

}
Gnis-ld-usgsBend {

}
Gnis-ld-usgsBridge {

}
Gnis-ld-usgsBuilding {

}
Gnis-ld-usgsBuiltUpArea {

}
Gnis-ld-usgsCanal {

}
Gnis-ld-usgsCape {

}
Gnis-ld-usgsCemetery {

}
Gnis-ld-usgsCensus {

}
Gnis-ld-usgsChannel {

}
Gnis-ld-usgsChurch {

}
Gnis-ld-usgsCivilGovernment {

}
Gnis-ld-usgsCliff {

}
Gnis-ld-usgsCrater {

}
Gnis-ld-usgsCrossing {

}
Gnis-ld-usgsDam {

}
Gnis-ld-usgsDivision {

}
Gnis-ld-usgsEcologicalRegime {

}
Gnis-ld-usgsEmbankment {

}
Gnis-ld-usgsFlat {

}
Gnis-ld-usgsForest {

}
Gnis-ld-usgsGap {

}
Gnis-ld-usgsGlacier {

}
Gnis-ld-usgsGut {

}
Gnis-ld-usgsHarbor {

}
Gnis-ld-usgsHospital {

}
Gnis-ld-usgsIsland {

}
Gnis-ld-usgsIsthmus {

}
Gnis-ld-usgsLake {

}
Gnis-ld-usgsLava {

}
Gnis-ld-usgsLevee {

}
Gnis-ld-usgsLocale {

}
Gnis-ld-usgsMilitary {

}
Gnis-ld-usgsMine {

}
Gnis-ld-usgsMountainRange {

}
Gnis-ld-usgsOcean {

}
Gnis-ld-usgsOilField {

}
Gnis-ld-usgsPark {

}
Gnis-ld-usgsPlain {

}
Gnis-ld-usgsPopulatedPlace {

}
Gnis-ld-usgsPostOffice {

}
Gnis-ld-usgsRapids {

}
Gnis-ld-usgsReserve {

}
Gnis-ld-usgsReservoir {

}
Gnis-ld-usgsRidge {

}
Gnis-ld-usgsRock {

}
Gnis-ld-usgsSchool {

}
Gnis-ld-usgsSea {

}
Gnis-ld-usgsSlope {

}
Gnis-ld-usgsSpring {

}
Gnis-ld-usgsStream {

}
Gnis-ld-usgsSummit {

}
Gnis-ld-usgsSurfaceWater {

}
Gnis-ld-usgsSwamp {

}
Gnis-ld-usgsTerrain {

}
Gnis-ld-usgsTower {

}
Gnis-ld-usgsTrail {

}
Gnis-ld-usgsTunnel {

}
Gnis-ld-usgsUnknown {

}
Gnis-ld-usgsValley {

}
Gnis-ld-usgsWaterfall {

}
Gnis-ld-usgsWell {

}
Gnis-ld-usgsWoodland {

}
Gnis-ld-gnisCounty {

}
Gnis-ld-gnisState {

}
Gnis-ld-usgsFeature {

}
HttpPurl.orgVocabFrbrCoreEndeavour {

}
IospressGeoCodedLocation {

}
IrdrAnimalIncident {

}
IrdrBiological {

}
IrdrClimatological {

}
IrdrConvectiveStorm {

}
IrdrDisease {

}
IrdrDrought {

}
IrdrEarthquake {

}
IrdrExtraterrestrial {

}
IrdrExtratropicalStorm {

}
IrdrExtremeTemperature {

}
IrdrFlood {

}
IrdrFog {

}
IrdrGeophysical {

}
IrdrGlacialLakeOutburst {

}
IrdrHydrological {

}
IrdrImpact {

}
IrdrInsectInfestation {

}
IrdrLandslide {

}
IrdrMassMovement {

}
IrdrMetereological {

}
IrdrSpaceWeather {

}
IrdrTropicalCyclone {

}
IrdrVolcanicActivity {

}
IrdrWaveAction {

}
IrdrWildfire {

}
KwgoATH {

}
KwgoAdministrativeRegion {

}
KwgoAdministrativeRegion0 {

}
KwgoAdministrativeRegion1 {

}
KwgoAdministrativeRegion2 {

}
KwgoAdministrativeRegion3 {

}
KwgoAdministrativeRegion4 {

}
KwgoAdministrativeRegion5 {

}
KwgoAdministrativeRegion6 {

}
KwgoAirPollutant {
    string rdfs_label  
}
KwgoAirQualityInstrument {

}
KwgoAirQualityObservation {

}
KwgoAirQualityObservationCollection {

}
KwgoAirQualitySite {

}
KwgoBlueskyModel {

}
KwgoBlueskyModeledWildfire {

}
KwgoBlueskyWildfireObservableProperty {
    string rdfs_label  
}
KwgoBlueskyWildfireObservation {

}
KwgoBlueskyWildfireObservationCollection {

}
KwgoCTH {

}
KwgoCell {

}
KwgoCensusACS5YearEstimatesObservation {

}
KwgoCensusACS5YearEstimatesObservationCollection {

}
KwgoCensusObservableProperty {
    uri rdfs_isDefinedBy  
    string rdfs_comment  
    string rdfs_label  
}
KwgoChiefJudge {

}
KwgoClimateDivisionObservationCollection {

}
KwgoClimateDivisionObservationResult {

}
KwgoClimateDivisionPropertyObservationCollection {

}
KwgoClimateObservableProperty {
    string rdfs_label  
}
KwgoClimateObservation {

}
KwgoComplexFire {

}
KwgoCrisisCounselling {

}
KwgoCroplandObservableProperty {
    string rdfs_label  
}
KwgoCroplandObservation {

}
KwgoCroplandObservationCollection {

}
KwgoCroplandResult {

}
KwgoDebrisRemoval-PA-A {

}
KwgoDeclaration {

}
KwgoDirectFederalAssistance {

}
KwgoDisaster {

}
KwgoDisasterHousing {

}
KwgoDisasterUnemploymentAssistance {

}
KwgoDoD {

}
KwgoDroughtIntensity {
    string rdfs_label  
}
KwgoDroughtZone {

}
KwgoDroughtZoneOverlapObservation {

}
KwgoDroughtZoneOverlapObservationCollection {

}
KwgoEarthquake {

}
KwgoEarthquakeObservableProperty {

}
KwgoEarthquakeObservationCollection {

}
KwgoEmergencyDeclaration {

}
KwgoEventSegment {

}
KwgoExpertiseTopic {

}
KwgoFederalJudicalDistrict {

}
KwgoFieldsOfStudy {

}
KwgoFire {

}
KwgoFireCause {
    string rdfs_label  
}
KwgoFireManagementAssistance-PA-I {

}
KwgoFireManagementDeclaration {

}
KwgoFireMappingAssessmentLabel {

}
KwgoFix {

}
KwgoGeometry {

}
KwgoGeometryCollection {

}
KwgoHazard {

}
KwgoHazardEpisode {

}
KwgoHazardMitigation {

}
KwgoHelipadAvailability {
    string rdfs_label  
}
KwgoHospital {

}
KwgoHospitalStatus {
    string rdfs_label  
}
KwgoHospitalType {
    string rdfs_label  
}
KwgoHousingAssistance {

}
KwgoImpactObservableProperty {
    string rdfs_label  
}
KwgoImpactObservation {

}
KwgoImpactObservationCollection {

}
KwgoIndividualAndFamilyGrant {

}
KwgoIndividualAssistance {

}
KwgoIndividualAssistance-PA-C {

}
KwgoIndividualsAndHouseholds {

}
KwgoJudegeInfo {

}
KwgoLSADArea {
    string rdfs_label  
    string rdfs_comment  
}
KwgoLevelI {

}
KwgoLevelII {

}
KwgoLevelIII {

}
KwgoLevelIIIPediatric {

}
KwgoLevelIIPediatric {

}
KwgoLevelIIRehab {

}
KwgoLevelIV {

}
KwgoLevelIPediatric {

}
KwgoLevelIPediatricRehab {

}
KwgoLevelIRehab {

}
KwgoLevelPediatric {

}
KwgoLevelV {

}
KwgoMTBSComplexFire {

}
KwgoMTBSFire {

}
KwgoMTBSFireObservableProperty {
    string rdfs_label  
    string rdfs_comment  
}
KwgoMTBSFireObservation {

}
KwgoMTBSFireObservationCollection {

}
KwgoMTBSOutOfAreaResponseFire {

}
KwgoMTBSPrescribedFire {

}
KwgoMTBSUnknownFire {

}
KwgoMTBSWildfire {

}
KwgoMTBSWildlandFireUse {

}
KwgoMagnitudeObservableProperty {
    string rdfs_label  
}
KwgoMagnitudeObservation {

}
KwgoMagnitudeObservationCollection {

}
KwgoMajorDisasterDeclaration {

}
KwgoMappingProgram {

}
KwgoNIFCFire {

}
KwgoNIFCFireObservableProperty {
    string rdfs_label  
}
KwgoNIFCFireObservation {

}
KwgoNIFCIncidentComplexFire {

}
KwgoNIFCPrescribedFire {

}
KwgoNIFCWildfire {

}
KwgoNOAAAstronomicalLowTide {

}
KwgoNOAAAvalanche {

}
KwgoNOAABlizzard {

}
KwgoNOAACoastalFlood {

}
KwgoNOAAColdWindChill {

}
KwgoNOAADebrisFlow {

}
KwgoNOAADenseFog {

}
KwgoNOAADenseSmoke {

}
KwgoNOAADrought {

}
KwgoNOAADustDevil {

}
KwgoNOAADustStorm {

}
KwgoNOAAExcessiveHeat {

}
KwgoNOAAExtremeColdWindChill {

}
KwgoNOAAFlashFlood {

}
KwgoNOAAFlood {

}
KwgoNOAAFreezingFog {

}
KwgoNOAAFrostFreeze {

}
KwgoNOAAFunnelCloud {

}
KwgoNOAAHail {

}
KwgoNOAAHazard {

}
KwgoNOAAHeat {

}
KwgoNOAAHeavyRain {

}
KwgoNOAAHeavySnow {

}
KwgoNOAAHighSurf {

}
KwgoNOAAHighWind {

}
KwgoNOAAHurricane {

}
KwgoNOAAIceStorm {

}
KwgoNOAALake-EffectSnow {

}
KwgoNOAALakeshoreFlood {

}
KwgoNOAALightning {

}
KwgoNOAAMarineHail {

}
KwgoNOAAMarineHighWind {

}
KwgoNOAAMarineHurricaneTyphoon {

}
KwgoNOAAMarineStrongWind {

}
KwgoNOAAMarineThunderstormWind {

}
KwgoNOAAMarineTropicalDepression {

}
KwgoNOAAMarineTropicalStorm {

}
KwgoNOAARipCurrent {

}
KwgoNOAASleet {

}
KwgoNOAASneakerwave {

}
KwgoNOAAStormSurgeTide {

}
KwgoNOAAStrongWind {

}
KwgoNOAAThunderstormWind {

}
KwgoNOAATornado {

}
KwgoNOAATropicalDepression {

}
KwgoNOAATropicalStorm {

}
KwgoNOAAWaterspout {

}
KwgoNOAAWildfire {

}
KwgoNOAAWinterStorm {

}
KwgoNOAAWinterWeather {

}
KwgoNWZone {

}
KwgoNielsenMarketZone {

}
KwgoOther {

}
KwgoOutOfAreaResponseFire {

}
KwgoPARC {

}
KwgoPrescribedFire {

}
KwgoProgram {

}
KwgoProtectiveMeasures-PA-B {

}
KwgoPublicAssistance {

}
KwgoPublicBuildings-PA-F {

}
KwgoPublicHealthObservableProperty {
    string rdfs_label  
}
KwgoPublicHealthObservation {

}
KwgoPublicHealthObservationCollection {

}
KwgoPublicUtilitiesPA-G {

}
KwgoQuantity {

}
KwgoRPTC {

}
KwgoRTC {

}
KwgoRTH {

}
KwgoRecreationalOrOther-PA-H {

}
KwgoRegion {

}
KwgoRegionalCircuit {

}
KwgoRoadSegment {

}
KwgoRoadSegmentNode {

}
KwgoRoadType {
    string rdfs_label  
}
KwgoRoadsAndBridges-PA-D {

}
KwgoS2Cell {

}
KwgoSmallBusinessAdministration {

}
KwgoSmokePlumeObservableProperty {
    string rdfs_label  
}
KwgoSmokePlumeObservation {

}
KwgoSmokePlumeSnapshot {

}
KwgoSoilMapUnit {

}
KwgoSoilMapUnitObservableProperty {
    string rdfs_label  
    string rdfs_comment  
}
KwgoSoilMapUnitObservation {

}
KwgoSoilMapUnitObservationCollection {

}
KwgoSoilMapUnitOverlapObservation {

}
KwgoStormTrack {

}
KwgoStormTrackObservableProperty {
    string rdfs_label  
}
KwgoStormTrackObservation {

}
KwgoStormTrackObservationCollection {

}
KwgoStormTracklet {

}
KwgoStormTrackletObservableProperty {
    string rdfs_label  
}
KwgoStormTrackletObservation {

}
KwgoStormTrackletObservationCollection {

}
KwgoTRF {

}
KwgoTRH {

}
KwgoTornadoMagnitudeObservationCollection {

}
KwgoTraumaDescription {

}
KwgoTraumaLevelCare {

}
KwgoUSCensusMSA {

}
KwgoUSClimateDivision {

}
KwgoUSPresident {

}
KwgoVenue {

}
KwgoVulnerabilityIndexObservation {

}
KwgoVulnerabilityObservableProperty {
    string rdfs_label  
}
KwgoWaterControlFacilities-PA-E {

}
KwgoWildfire {

}
KwgoWildlandFireUse {

}
KwgoWindMagnitudeObservationCollection {

}
KwgoZipCodeArea {

}
Sf#LineString {

}
Sf#Point {

}
SosaEarthquakeObservation {

}
SosaFeatureOfInterest {

}
SosaObservableProperty {

}
SosaObservation {

}
SosaObservationCollection {

}
SosaPlatform {

}
SosaResult {

}
SosaSensor {

}
Node359 {
    datetime prov_endedAtTime  
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Node499 {
    datetime prov_endedAtTime  
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Node501 {
    datetime prov_endedAtTime  
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Node502 {
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Node503 {

}
Node506 {
    string rdfs_label  
}
Node507 {
    string rdfs_label  
    string dct_description  
}
Node508 {
    datetime prov_endedAtTime  
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Node510 {
    datetime prov_endedAtTime  
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Node512 {
    datetime prov_endedAtTime  
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Node513 {
    datetime prov_endedAtTime  
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Node515 {
    string rdfs_label  
}
Node517 {
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Node518 {
    string rdfs_label  
}
Node519 {
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Node521 {
    datetime prov_endedAtTime  
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Node523 {
    datetime prov_endedAtTime  
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Fio-epa-frsAgency {
    string rdfs_label  
}
Fio-epa-frsAgency.Agriculture {
    string rdfs_label  
}
Fio-epa-frsAgency.Commerce {
    string rdfs_label  
}
Fio-epa-frsAgency.Congress {
    string rdfs_label  
}
Fio-epa-frsAgency.Defense {
    string rdfs_label  
}
Fio-epa-frsAgency.Energy {
    string rdfs_label  
}
Fio-epa-frsAgency.HealthandHumanServices {
    string rdfs_label  
}
Fio-epa-frsAgency.HomelandSecurity {
    string rdfs_label  
}
Fio-epa-frsAgency.HousingandUrbanDevelopment {
    string rdfs_label  
}
Fio-epa-frsAgency.Interior {
    string rdfs_label  
}
Fio-epa-frsAgency.Judicial {
    string rdfs_label  
}
Fio-epa-frsAgency.Justice {
    string rdfs_label  
}
Fio-epa-frsAgency.Labor {
    string rdfs_label  
}
Fio-epa-frsAgency.State {
    string rdfs_label  
}
Fio-epa-frsAgency.Transportation {
    string rdfs_label  
}
Fio-epa-frsAgency.Treasury {
    string rdfs_label  
}
Fio-epa-frsAgency.VeteransAffairs {
    string rdfs_label  
}
Fio-epa-frsAirProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsAnimalOperation {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsAssistanceSupportProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsChemicalReleaseProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsChemicalStorageProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsChemicalstorageprograms {

}
Fio-epa-frsCoastalOceanProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsComplianceInterest {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsComplianceRecord {

}
Fio-epa-frsComplianceSystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsDrinkingWaterProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsEPA-PFAS-Facility {
    string dct_title  
    string fio_epa_frs_hasFRSId  
    date dct_modified  
    string rdfs_label  
}
Fio-epa-frsEcologyOperation {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsElectronicPermitSystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsEnforcementActivity {

}
Fio-epa-frsEnforcementInterest {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsEnforcementSystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsEnforcementTrackingRecord {

}
Fio-epa-frsEnvironmentalInterestByProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsEnvironmentalInterestByRecordType {

}
Fio-epa-frsEnvironmentalInterestType {
    string rdfs_label  
}
Fio-epa-frsFRS-Facility {
    string dct_title  
    datetime prov_startedAtTime  
    string dct_description  
    string fio_epa_frs_hasFRSId  
    datetime prov_endedAtTime  
    date dct_modified  
    string rdfs_label  
}
Fio-epa-frsFacilitySiteIdentification {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsFacilityType {
    string rdfs_label  
}
Fio-epa-frsGrantSystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsGroundWaterProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsHazardousWasteProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsHealthSafetyProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsLegacySystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsLegalEnforcementActivities {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsMonitoringRecord {

}
Fio-epa-frsPermitInterest {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsPermitRecord {

}
Fio-epa-frsPermitSystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsPesticidesProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsProgramInformationSystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsProjectRecord {

}
Fio-epa-frsProjectSystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsRadiationProtectionProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsRecord {

}
Fio-epa-frsRegistrationRecord {

}
Fio-epa-frsRegistryInterest {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsRegistrySystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsRemediationRedevelopmentProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsReportingInterest {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsReportingRecord {

}
Fio-epa-frsReportingSystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsRiskInterest {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsRiskPlanRecord {

}
Fio-epa-frsSiteInterest {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsSiteRecord {

}
Fio-epa-frsSiteSystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsSolidWasteProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsStateSystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsStateTrackingRecord {

}
Fio-epa-frsStationSystem {

}
Fio-epa-frsSupplementalRecord {
    datetime prov_endedAtTime  
    string rdfs_label  
    datetime prov_startedAtTime  
    string dct_description  
}
Fio-epa-frsTribalSystem {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsTribalTrackingRecord {

}
Fio-epa-frsUndergroundStorageTankProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsWasteWaterProgram {
    string rdfs_label  
    string dct_description  
}
Fio-epa-frsWaterResourcesProgram {
    string rdfs_label  
    string dct_description  
}
FioFacility {

}
FioIndustry {

}
FioOrganization {

}
KwgoS2CellLevel13 {

}
NaicsNAICS-Industry {

}
NaicsNAICS-IndustryCode {
    string rdfs_label  
    date fio_ofYear  
}
NaicsNAICS-IndustryGroup {
    string rdfs_label  
    date fio_ofYear  
}
NaicsNAICS-IndustrySector {
    string rdfs_label  
    date fio_ofYear  
}
NaicsNAICS-IndustrySubsector {
    string rdfs_label  
    date fio_ofYear  
}
OwlRational {

}
OwlReal {

}
XsdNCName {

}
XsdNMTOKEN {

}
XsdName {

}
XsdAnyURI {

}
XsdBase64Binary {

}
XsdBoolean {

}
XsdByte {

}
XsdDate {

}
XsdDateTime {

}
XsdDecimal {

}
XsdDouble {

}
XsdFloat {

}
XsdHexBinary {

}
XsdInt {

}
XsdInteger {

}
XsdLanguage {

}
XsdLong {

}
XsdNegativeInteger {

}
XsdNonNegativeInteger {

}
XsdNonPositiveInteger {

}
XsdNormalizedString {

}
XsdPositiveInteger {

}
XsdShort {

}
XsdToken {

}
XsdUnsignedByte {

}
XsdUnsignedInt {

}
XsdUnsignedLong {

}
XsdUnsignedShort {

}

DcamVocabularyEncodingScheme ||--|o RdfsResource : "rdfs_seeAlso"
DcamVocabularyEncodingScheme ||--|o RdfsLiteral : "rdfs_label"
DcamVocabularyEncodingScheme ||--|o RdfsLiteral : "rdfs_comment"
DcamVocabularyEncodingScheme ||--|o RdfsLiteral : "dct_issued"
DcamVocabularyEncodingScheme ||--|o OwlOntology : "rdfs_isDefinedBy"
DcamVocabularyEncodingScheme ||--|o RdfsResource : "rdfs_isDefinedBy"
OwlDataRange ||--|o OwlOntology : "rdfs_isDefinedBy"
OwlDataRange ||--|o RdfsResource : "rdfs_isDefinedBy"
OwlDataRange ||--|o RdfsResource : "rdfs_seeAlso"
OwlDataRange ||--|o RdfsLiteral : "rdfs_comment"
OwlDataRange ||--|o RdfsLiteral : "rdfs_label"
OwlDataRange ||--|o RdfsClass : "rdfs_subClassOf"
OwlOntologyProperty ||--|o RdfsClass : "rdfs_range"
OwlOntologyProperty ||--|o OwlOntology : "rdfs_isDefinedBy"
OwlOntologyProperty ||--|o RdfsResource : "rdfs_isDefinedBy"
OwlOntologyProperty ||--|o RdfsLiteral : "rdfs_comment"
OwlOntologyProperty ||--|o RdfsLiteral : "rdfs_label"
OwlOntologyProperty ||--|o RdfsClass : "rdfs_domain"
RdfList ||--|o OwlOntology : "rdfs_isDefinedBy"
RdfList ||--|o RdfsResource : "rdfs_isDefinedBy"
RdfList ||--|o RdfsLiteral : "rdfs_comment"
RdfList ||--|o RdfsLiteral : "rdfs_label"
RdfsDatatype ||--|o OwlOntology : "rdfs_isDefinedBy"
RdfsDatatype ||--|o RdfsResource : "rdfs_isDefinedBy"
RdfsDatatype ||--|o RdfsResource : "rdfs_seeAlso"
RdfsDatatype ||--|o RdfsLiteral : "rdfs_comment"
RdfsDatatype ||--|o RdfsLiteral : "rdfs_label"
RdfsDatatype ||--|o RdfsClass : "rdfs_subClassOf"
TimeDayOfWeek ||--|o RdfsLiteral : "rdfs_label"
TimeTemporalUnit ||--|o RdfsLiteral : "rdfs_label"
SdosActionStatusType ||--|o RdfsLiteral : "rdfs_label"
SdosActionStatusType ||--|o RdfsLiteral : "rdfs_comment"
SdosAdultOrientedEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosAdultOrientedEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosAdultOrientedEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosAdultOrientedEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosBoardingPolicyType ||--|o RdfsLiteral : "rdfs_label"
SdosBoardingPolicyType ||--|o RdfsLiteral : "rdfs_comment"
SdosBodyMeasurementTypeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosBodyMeasurementTypeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosBodyMeasurementTypeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosBodyMeasurementTypeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosBookFormatType ||--|o RdfsLiteral : "rdfs_label"
SdosBookFormatType ||--|o SdosURL : "sdos_isPartOf"
SdosBookFormatType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosBookFormatType ||--|o RdfsLiteral : "rdfs_comment"
SdosBoolean ||--|o RdfsLiteral : "rdfs_label"
SdosBoolean ||--|o RdfsLiteral : "rdfs_comment"
SdosCarUsageType ||--|o RdfsLiteral : "rdfs_label"
SdosCarUsageType ||--|o SdosOrganization : "sdos_contributor"
SdosCarUsageType ||--|o SdosPerson : "sdos_contributor"
SdosCarUsageType ||--|o SdosURL : "sdos_isPartOf"
SdosCarUsageType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosCarUsageType ||--|o RdfsLiteral : "rdfs_comment"
SdosCertificationStatusEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosCertificationStatusEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosCertificationStatusEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosCertificationStatusEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosContactPointOption ||--|o RdfsLiteral : "rdfs_label"
SdosContactPointOption ||--|o RdfsLiteral : "rdfs_comment"
SdosDayOfWeek ||--|o RdfsLiteral : "rdfs_label"
SdosDayOfWeek ||--|o SdosURL : "sdos_sameAs"
SdosDayOfWeek ||--|o SdosOrganization : "sdos_contributor"
SdosDayOfWeek ||--|o SdosPerson : "sdos_contributor"
SdosDayOfWeek ||--|o RdfsLiteral : "rdfs_comment"
SdosDeliveryMethod ||--|o RdfsLiteral : "rdfs_label"
SdosDeliveryMethod ||--|o SdosOrganization : "sdos_contributor"
SdosDeliveryMethod ||--|o SdosPerson : "sdos_contributor"
SdosDeliveryMethod ||--|o RdfsLiteral : "rdfs_comment"
SdosDigitalDocumentPermissionType ||--|o RdfsLiteral : "rdfs_label"
SdosDigitalDocumentPermissionType ||--|o RdfsLiteral : "rdfs_comment"
SdosDigitalPlatformEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosDigitalPlatformEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosDigitalPlatformEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosDigitalPlatformEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosDriveWheelConfigurationValue ||--|o RdfsLiteral : "rdfs_label"
SdosDriveWheelConfigurationValue ||--|o SdosOrganization : "sdos_contributor"
SdosDriveWheelConfigurationValue ||--|o SdosPerson : "sdos_contributor"
SdosDriveWheelConfigurationValue ||--|o RdfsLiteral : "rdfs_comment"
SdosDrugCostCategory ||--|o RdfsLiteral : "rdfs_label"
SdosDrugCostCategory ||--|o SdosURL : "sdos_isPartOf"
SdosDrugCostCategory ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosDrugCostCategory ||--|o RdfsLiteral : "rdfs_comment"
SdosDrugPregnancyCategory ||--|o RdfsLiteral : "rdfs_label"
SdosDrugPregnancyCategory ||--|o SdosURL : "sdos_isPartOf"
SdosDrugPregnancyCategory ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosDrugPregnancyCategory ||--|o RdfsLiteral : "rdfs_comment"
SdosDrugPrescriptionStatus ||--|o RdfsLiteral : "rdfs_label"
SdosDrugPrescriptionStatus ||--|o SdosURL : "sdos_isPartOf"
SdosDrugPrescriptionStatus ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosDrugPrescriptionStatus ||--|o RdfsLiteral : "rdfs_comment"
SdosEUEnergyEfficiencyEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosEUEnergyEfficiencyEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosEUEnergyEfficiencyEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosEUEnergyEfficiencyEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosEnergyStarEnergyEfficiencyEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosEnergyStarEnergyEfficiencyEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosEnergyStarEnergyEfficiencyEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosEnergyStarEnergyEfficiencyEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosEventAttendanceModeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosEventAttendanceModeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosEventAttendanceModeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosEventAttendanceModeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosEventStatusType ||--|o RdfsLiteral : "rdfs_label"
SdosEventStatusType ||--|o RdfsLiteral : "rdfs_comment"
SdosFulfillmentTypeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosFulfillmentTypeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosFulfillmentTypeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosFulfillmentTypeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosGameAvailabilityEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosGameAvailabilityEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosGameAvailabilityEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosGameAvailabilityEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosGamePlayMode ||--|o RdfsLiteral : "rdfs_label"
SdosGamePlayMode ||--|o RdfsLiteral : "rdfs_comment"
SdosGameServerStatus ||--|o RdfsLiteral : "rdfs_label"
SdosGameServerStatus ||--|o RdfsLiteral : "rdfs_comment"
SdosGenderType ||--|o RdfsLiteral : "rdfs_label"
SdosGenderType ||--|o RdfsLiteral : "rdfs_comment"
SdosGovernmentBenefitsType ||--|o RdfsLiteral : "rdfs_label"
SdosGovernmentBenefitsType ||--|o SdosURL : "sdos_isPartOf"
SdosGovernmentBenefitsType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosGovernmentBenefitsType ||--|o RdfsLiteral : "rdfs_comment"
SdosHealthAspectEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosHealthAspectEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosHealthAspectEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosHealthAspectEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosIPTCDigitalSourceEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosIPTCDigitalSourceEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosIPTCDigitalSourceEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosIPTCDigitalSourceEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosIncentiveQualifiedExpenseType ||--|o RdfsLiteral : "rdfs_label"
SdosIncentiveQualifiedExpenseType ||--|o SdosURL : "sdos_isPartOf"
SdosIncentiveQualifiedExpenseType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosIncentiveQualifiedExpenseType ||--|o RdfsLiteral : "rdfs_comment"
SdosIncentiveStatus ||--|o RdfsLiteral : "rdfs_label"
SdosIncentiveStatus ||--|o SdosURL : "sdos_isPartOf"
SdosIncentiveStatus ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosIncentiveStatus ||--|o RdfsLiteral : "rdfs_comment"
SdosIncentiveType ||--|o RdfsLiteral : "rdfs_label"
SdosIncentiveType ||--|o SdosURL : "sdos_isPartOf"
SdosIncentiveType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosIncentiveType ||--|o RdfsLiteral : "rdfs_comment"
SdosInfectiousAgentClass ||--|o RdfsLiteral : "rdfs_label"
SdosInfectiousAgentClass ||--|o SdosURL : "sdos_isPartOf"
SdosInfectiousAgentClass ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosInfectiousAgentClass ||--|o RdfsLiteral : "rdfs_comment"
SdosItemAvailability ||--|o RdfsLiteral : "rdfs_label"
SdosItemAvailability ||--|o RdfsLiteral : "rdfs_comment"
SdosItemListOrderType ||--|o RdfsLiteral : "rdfs_label"
SdosItemListOrderType ||--|o RdfsLiteral : "rdfs_comment"
SdosLegalForceStatus ||--|o RdfsLiteral : "rdfs_label"
SdosLegalForceStatus ||--|o SdosURL : "sdos_isPartOf"
SdosLegalForceStatus ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosLegalForceStatus ||--|o RdfsLiteral : "rdfs_comment"
SdosLegalForceStatus ||--|o SdosOrganization : "sdos_contributor"
SdosLegalForceStatus ||--|o SdosPerson : "sdos_contributor"
SdosLegalValueLevel ||--|o RdfsLiteral : "rdfs_label"
SdosLegalValueLevel ||--|o SdosURL : "sdos_isPartOf"
SdosLegalValueLevel ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosLegalValueLevel ||--|o RdfsLiteral : "rdfs_comment"
SdosLegalValueLevel ||--|o SdosOrganization : "sdos_contributor"
SdosLegalValueLevel ||--|o SdosPerson : "sdos_contributor"
SdosMapCategoryType ||--|o RdfsLiteral : "rdfs_label"
SdosMapCategoryType ||--|o RdfsLiteral : "rdfs_comment"
SdosMeasurementMethodEnum ||--|o RdfsLiteral : "rdfs_label"
SdosMeasurementMethodEnum ||--|o SdosURL : "sdos_isPartOf"
SdosMeasurementMethodEnum ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMeasurementMethodEnum ||--|o RdfsLiteral : "rdfs_comment"
SdosMediaManipulationRatingEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosMediaManipulationRatingEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosMediaManipulationRatingEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMediaManipulationRatingEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalAudienceType ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalAudienceType ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalAudienceType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalAudienceType ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalDevicePurpose ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalDevicePurpose ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalDevicePurpose ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalDevicePurpose ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalEvidenceLevel ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalEvidenceLevel ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalEvidenceLevel ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalEvidenceLevel ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalImagingTechnique ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalImagingTechnique ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalImagingTechnique ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalImagingTechnique ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalObservationalStudyDesign ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalObservationalStudyDesign ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalObservationalStudyDesign ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalObservationalStudyDesign ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalProcedureType ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalProcedureType ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalProcedureType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalProcedureType ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalSpecialty ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalSpecialty ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalSpecialty ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalSpecialty ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalSpecialty ||--|o SdosMedicalSpecialty : "sdos_supersededBy"
SdosMedicalSpecialty ||--|o SdosProperty : "sdos_supersededBy"
SdosMedicalSpecialty ||--|o SdosMerchantReturnEnumeration : "sdos_supersededBy"
SdosMedicalSpecialty ||--|o SdosClass : "sdos_supersededBy"
SdosMedicalSpecialty ||--|o SdosEnumeration : "sdos_supersededBy"
SdosMedicalSpecialty ||--|o RdfsClass : "rdfs_subClassOf"
SdosMedicalStudyStatus ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalStudyStatus ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalStudyStatus ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalStudyStatus ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalTrialDesign ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalTrialDesign ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalTrialDesign ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalTrialDesign ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicineSystem ||--|o RdfsLiteral : "rdfs_label"
SdosMedicineSystem ||--|o SdosURL : "sdos_isPartOf"
SdosMedicineSystem ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicineSystem ||--|o RdfsLiteral : "rdfs_comment"
SdosMerchantReturnEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosMerchantReturnEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosMerchantReturnEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMerchantReturnEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosMusicAlbumProductionType ||--|o RdfsLiteral : "rdfs_label"
SdosMusicAlbumProductionType ||--|o SdosOrganization : "sdos_contributor"
SdosMusicAlbumProductionType ||--|o SdosPerson : "sdos_contributor"
SdosMusicAlbumProductionType ||--|o RdfsLiteral : "rdfs_comment"
SdosMusicAlbumReleaseType ||--|o RdfsLiteral : "rdfs_label"
SdosMusicAlbumReleaseType ||--|o SdosOrganization : "sdos_contributor"
SdosMusicAlbumReleaseType ||--|o SdosPerson : "sdos_contributor"
SdosMusicAlbumReleaseType ||--|o RdfsLiteral : "rdfs_comment"
SdosMusicReleaseFormatType ||--|o RdfsLiteral : "rdfs_label"
SdosMusicReleaseFormatType ||--|o SdosOrganization : "sdos_contributor"
SdosMusicReleaseFormatType ||--|o SdosPerson : "sdos_contributor"
SdosMusicReleaseFormatType ||--|o RdfsLiteral : "rdfs_comment"
SdosNLNonprofitType ||--|o RdfsLiteral : "rdfs_label"
SdosNLNonprofitType ||--|o SdosURL : "sdos_isPartOf"
SdosNLNonprofitType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosNLNonprofitType ||--|o RdfsLiteral : "rdfs_comment"
SdosOfferItemCondition ||--|o RdfsLiteral : "rdfs_label"
SdosOfferItemCondition ||--|o RdfsLiteral : "rdfs_comment"
SdosOrderStatus ||--|o RdfsLiteral : "rdfs_label"
SdosOrderStatus ||--|o RdfsLiteral : "rdfs_comment"
SdosPaymentMethodType ||--|o RdfsLiteral : "rdfs_label"
SdosPaymentMethodType ||--|o RdfsLiteral : "rdfs_comment"
SdosPaymentStatusType ||--|o RdfsLiteral : "rdfs_label"
SdosPaymentStatusType ||--|o RdfsLiteral : "rdfs_comment"
SdosPhysicalActivityCategory ||--|o RdfsLiteral : "rdfs_label"
SdosPhysicalActivityCategory ||--|o SdosURL : "sdos_isPartOf"
SdosPhysicalActivityCategory ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosPhysicalActivityCategory ||--|o RdfsLiteral : "rdfs_comment"
SdosPhysicalExam ||--|o RdfsLiteral : "rdfs_label"
SdosPhysicalExam ||--|o SdosURL : "sdos_isPartOf"
SdosPhysicalExam ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosPhysicalExam ||--|o RdfsLiteral : "rdfs_comment"
SdosPriceComponentTypeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosPriceComponentTypeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosPriceComponentTypeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosPriceComponentTypeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosPriceTypeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosPriceTypeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosPriceTypeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosPriceTypeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosProductReturnEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosProductReturnEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosProductReturnEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosProductReturnEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosProductReturnEnumeration ||--|o SdosMedicalSpecialty : "sdos_supersededBy"
SdosProductReturnEnumeration ||--|o SdosProperty : "sdos_supersededBy"
SdosProductReturnEnumeration ||--|o SdosMerchantReturnEnumeration : "sdos_supersededBy"
SdosProductReturnEnumeration ||--|o SdosClass : "sdos_supersededBy"
SdosProductReturnEnumeration ||--|o SdosEnumeration : "sdos_supersededBy"
SdosPurchaseType ||--|o RdfsLiteral : "rdfs_label"
SdosPurchaseType ||--|o SdosURL : "sdos_isPartOf"
SdosPurchaseType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosPurchaseType ||--|o RdfsLiteral : "rdfs_comment"
SdosRefundTypeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosRefundTypeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosRefundTypeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosRefundTypeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosReservationStatusType ||--|o RdfsLiteral : "rdfs_label"
SdosReservationStatusType ||--|o RdfsLiteral : "rdfs_comment"
SdosRestrictedDiet ||--|o RdfsLiteral : "rdfs_label"
SdosRestrictedDiet ||--|o RdfsLiteral : "rdfs_comment"
SdosReturnFeesEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosReturnFeesEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosReturnFeesEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosReturnFeesEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosReturnLabelSourceEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosReturnLabelSourceEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosReturnLabelSourceEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosReturnLabelSourceEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosReturnMethodEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosReturnMethodEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosReturnMethodEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosReturnMethodEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosRsvpResponseType ||--|o RdfsLiteral : "rdfs_label"
SdosRsvpResponseType ||--|o RdfsLiteral : "rdfs_comment"
SdosSizeSystemEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosSizeSystemEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosSizeSystemEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosSizeSystemEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosSteeringPositionValue ||--|o RdfsLiteral : "rdfs_label"
SdosSteeringPositionValue ||--|o SdosOrganization : "sdos_contributor"
SdosSteeringPositionValue ||--|o SdosPerson : "sdos_contributor"
SdosSteeringPositionValue ||--|o RdfsLiteral : "rdfs_comment"
SdosTierBenefitEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosTierBenefitEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosTierBenefitEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosTierBenefitEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosUKNonprofitType ||--|o RdfsLiteral : "rdfs_label"
SdosUKNonprofitType ||--|o SdosURL : "sdos_isPartOf"
SdosUKNonprofitType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosUKNonprofitType ||--|o RdfsLiteral : "rdfs_comment"
SdosUSNonprofitType ||--|o RdfsLiteral : "rdfs_label"
SdosUSNonprofitType ||--|o SdosURL : "sdos_isPartOf"
SdosUSNonprofitType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosUSNonprofitType ||--|o RdfsLiteral : "rdfs_comment"
SdosWearableMeasurementTypeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosWearableMeasurementTypeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosWearableMeasurementTypeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosWearableMeasurementTypeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosWearableSizeGroupEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosWearableSizeGroupEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosWearableSizeGroupEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosWearableSizeGroupEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosWearableSizeSystemEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosWearableSizeSystemEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosWearableSizeSystemEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosWearableSizeSystemEnumeration ||--|o RdfsLiteral : "rdfs_comment"
AdmsSemanticAssetDistribution ||--|o SkosConcept : "adms_status"
RdfDatatypeProperty ||--|o RdfsLiteral : "rdfs_comment"
RdfDatatypeProperty ||--|o RdfsClass : "rdfs_domain"
RdfDatatypeProperty ||--|o RdfsLiteral : "rdfs_label"
VaemGraphMetaData ||--|o RdfsLiteral : "dct_created"
VaemGraphMetaData ||--|o RdfsLiteral : "dct_modified"
VaemGraphMetaData ||--|o RdfsLiteral : "dct_title"
VaemGraphMetaData ||--|o RdfsLiteral : "rdfs_label"
VaemGraphMetaData ||--|o VaemParty : "vaem_hasOwner"
VaemGraphMetaData ||--|o OwlAnnotationProperty : "vaem_usesNonImportedResource"
VaemGraphMetaData ||--|o RdfsResource : "vaem_usesNonImportedResource"
VaemGraphMetaData ||--|o VaemGraphRole : "vaem_hasGraphRole"
VaemGraphMetaData ||--|o OwlOntology : "rdfs_isDefinedBy"
VaemGraphMetaData ||--|o RdfsResource : "rdfs_isDefinedBy"
VaemGraphMetaData ||--|o VaemParty : "vaem_hasSteward"
VaemGraphRole ||--|o RdfsLiteral : "rdfs_label"
VaemGraphRole ||--|o OwlOntology : "rdfs_isDefinedBy"
VaemGraphRole ||--|o RdfsResource : "rdfs_isDefinedBy"
VaemParty ||--|o RdfsLiteral : "rdfs_label"
VaemParty ||--|o OwlOntology : "rdfs_isDefinedBy"
VaemParty ||--|o RdfsResource : "rdfs_isDefinedBy"
VaemCatalogEntry ||--|o RdfsLiteral : "rdfs_label"
VaemCatalogEntry ||--|o OwlOntology : "rdfs_isDefinedBy"
VaemCatalogEntry ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagAttribution ||--|o RdfsLiteral : "rdfs_label"
VoagAttribution ||--|o VoagAttributionLogo : "voag_hasLogo"
VoagAttribution ||--|o VoagLogo : "voag_hasLogo"
VoagAttribution ||--|o VoagOrganizationLogo : "voag_hasLogo"
VoagAttribution ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagAttribution ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagAttributionLogo ||--|o RdfsLiteral : "rdfs_label"
VoagAttributionLogo ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagAttributionLogo ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagChangeFrequency ||--|o RdfsLiteral : "rdfs_label"
VoagChangeFrequency ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagChangeFrequency ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagChangeFrequency ||--|o XsdAnySimpleType : "dtype_value"
VoagChangeType ||--|o RdfsLiteral : "rdfs_label"
VoagChangeType ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagChangeType ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagConfidentialityLevel ||--|o RdfsLiteral : "rdfs_label"
VoagConfidentialityLevel ||--|o XsdAnySimpleType : "dtype_code"
VoagConfidentialityLevel ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagConfidentialityLevel ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagConfidentialityLevel ||--|o XsdAnySimpleType : "dtype_value"
VoagCreativeCommonsPermission ||--|o RdfsLiteral : "rdfs_label"
VoagCreativeCommonsPermission ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagCreativeCommonsPermission ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagCreativeCommonsProhibition ||--|o RdfsLiteral : "rdfs_label"
VoagCreativeCommonsProhibition ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagCreativeCommonsProhibition ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagCreativeCommonsRequirement ||--|o RdfsLiteral : "rdfs_label"
VoagCreativeCommonsRequirement ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagCreativeCommonsRequirement ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagGovernance ||--|o RdfsLiteral : "rdfs_label"
VoagGovernance ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagGovernance ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagGovernanceRole ||--|o RdfsLiteral : "rdfs_label"
VoagGovernanceRole ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagGovernanceRole ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagGovernanceRole ||--|o XsdAnySimpleType : "dtype_value"
VoagIcon ||--|o RdfsLiteral : "rdfs_label"
VoagIcon ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagIcon ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagIssueStatus ||--|o RdfsLiteral : "rdfs_label"
VoagIssueStatus ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagIssueStatus ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagIssueStatus ||--|o XsdAnySimpleType : "dtype_value"
VoagLicenseModel ||--|o RdfsLiteral : "rdfs_label"
VoagLicenseModel ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagLicenseModel ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagLogo ||--|o RdfsLiteral : "rdfs_label"
VoagLogo ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagLogo ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagMaturity ||--|o RdfsLiteral : "rdfs_label"
VoagMaturity ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagMaturity ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagOrganizationLogo ||--|o RdfsLiteral : "rdfs_label"
VoagOrganizationLogo ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagOrganizationLogo ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagPedigree ||--|o RdfsLiteral : "rdfs_label"
VoagPedigree ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagPedigree ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagPriorityValue ||--|o RdfsLiteral : "rdfs_label"
VoagPriorityValue ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagPriorityValue ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagPriorityValue ||--|o XsdAnySimpleType : "dtype_value"
VoagProductLogo ||--|o RdfsLiteral : "rdfs_label"
VoagProductLogo ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagProductLogo ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagProvenance ||--|o RdfsLiteral : "rdfs_label"
VoagProvenance ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagProvenance ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagPublicationStatus ||--|o RdfsLiteral : "rdfs_label"
VoagPublicationStatus ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagPublicationStatus ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagPublicationStatus ||--|o XsdAnySimpleType : "dtype_value"
VoagSchemaGraph ||--|o RdfsLiteral : "rdfs_label"
VoagSchemaGraph ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagSchemaGraph ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtAspectClass ||--|o RdfsLiteral : "rdfs_label"
QudtAspectClass ||--|o RdfsClass : "rdfs_subClassOf"
QudtAspectClass ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtAspectClass ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtAspectClass ||--|o RdfsLiteral : "rdfs_comment"
QudtBitEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtBitEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtBitEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtBooleanEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtBooleanEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtBooleanEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtByteEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtByteEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtByteEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtCardinalityType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtCardinalityType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtCardinalityType ||--|o RdfsLiteral : "rdfs_label"
QudtCharEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtCharEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtCharEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtDateTimeStringEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtDateTimeStringEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtDateTimeStringEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtEndianType ||--|o RdfsLiteral : "rdfs_label"
QudtEndianType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtEndianType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtFloatingPointEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtFloatingPointEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtFloatingPointEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtIntegerEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtIntegerEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtIntegerEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtOrderedType ||--|o RdfsLiteral : "rdfs_label"
QudtOrderedType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtOrderedType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtSignednessType ||--|o RdfsLiteral : "rdfs_label"
QudtSignednessType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtSignednessType ||--|o RdfsResource : "rdfs_isDefinedBy"
KwgoAirPollutant ||--|o RdfsLiteral : "rdfs_label"
KwgoBlueskyWildfireObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoCensusObservableProperty ||--|o OwlOntology : "rdfs_isDefinedBy"
KwgoCensusObservableProperty ||--|o RdfsResource : "rdfs_isDefinedBy"
KwgoCensusObservableProperty ||--|o RdfsLiteral : "rdfs_comment"
KwgoCensusObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoClimateObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoCroplandObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoDroughtIntensity ||--|o RdfsLiteral : "rdfs_label"
KwgoFireCause ||--|o RdfsLiteral : "rdfs_label"
KwgoHelipadAvailability ||--|o RdfsLiteral : "rdfs_label"
KwgoHospitalStatus ||--|o RdfsLiteral : "rdfs_label"
KwgoHospitalType ||--|o RdfsLiteral : "rdfs_label"
KwgoImpactObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoLSADArea ||--|o RdfsLiteral : "rdfs_label"
KwgoLSADArea ||--|o RdfsLiteral : "rdfs_comment"
KwgoMTBSFireObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoMTBSFireObservableProperty ||--|o RdfsLiteral : "rdfs_comment"
KwgoMagnitudeObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoNIFCFireObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoPublicHealthObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoRoadType ||--|o RdfsLiteral : "rdfs_label"
KwgoSmokePlumeObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoSoilMapUnitObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoSoilMapUnitObservableProperty ||--|o RdfsLiteral : "rdfs_comment"
KwgoStormTrackObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoStormTrackletObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoVulnerabilityObservableProperty ||--|o RdfsLiteral : "rdfs_label"
Node359 ||--|o RdfsLiteral : "rdfs_label"
Node359 ||--|o RdfsLiteral : "dct_identifier"
Node359 ||--|o OwlNamedIndividual : "fio_ofIndustry"
Node359 ||--|o OwlThing : "fio_ofIndustry"
Node359 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Node359 ||--|o FioIndustry : "fio_ofIndustry"
Node359 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Node359 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Node359 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Node359 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node359 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node359 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node359 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Node359 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Node359 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Node359 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Node359 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Node359 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Node359 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Node359 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Node359 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Node359 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Node359 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Node359 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Node359 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Node359 ||--|o OwlThing : "owl_sameAs"
Node359 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node359 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node359 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node359 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node359 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node359 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node359 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node359 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node359 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node359 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node359 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node359 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node359 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node499 ||--|o RdfsLiteral : "rdfs_label"
Node499 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node499 ||--|o OwlNamedIndividual : "fio_ofIndustry"
Node499 ||--|o OwlThing : "fio_ofIndustry"
Node499 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Node499 ||--|o FioIndustry : "fio_ofIndustry"
Node499 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Node499 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Node499 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Node499 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Node499 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Node499 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Node499 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Node499 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Node499 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Node499 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Node499 ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Node499 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node499 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node499 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node499 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node499 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node499 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node499 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node499 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node499 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node499 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node499 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node499 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node499 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node499 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node499 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node499 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node499 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Node499 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Node499 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Node499 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Node499 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Node499 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Node499 ||--|o Node502 : "fio-epa-frs_hasRecord"
Node499 ||--|o Node519 : "fio-epa-frs_hasRecord"
Node499 ||--|o Node515 : "fio-epa-frs_hasRecord"
Node499 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Node499 ||--|o Node517 : "fio-epa-frs_hasRecord"
Node499 ||--|o Node501 : "fio-epa-frs_hasRecord"
Node499 ||--|o Node523 : "fio-epa-frs_hasRecord"
Node499 ||--|o Node521 : "fio-epa-frs_hasRecord"
Node499 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Node499 ||--|o Node518 : "fio-epa-frs_hasRecord"
Node499 ||--|o Node510 : "fio-epa-frs_hasRecord"
Node499 ||--|o OwlThing : "fio-epa-frs_hasRecord"
Node499 ||--|o Node512 : "fio-epa-frs_hasRecord"
Node499 ||--|o Node513 : "fio-epa-frs_hasRecord"
Node499 ||--|o Node359 : "fio-epa-frs_hasRecord"
Node499 ||--|o Node507 : "fio-epa-frs_hasRecord"
Node499 ||--|o Node506 : "fio-epa-frs_hasRecord"
Node499 ||--|o Node508 : "fio-epa-frs_hasRecord"
Node499 ||--|o Node499 : "fio-epa-frs_hasRecord"
Node499 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Node499 ||--|o OwlThing : "owl_sameAs"
Node499 ||--|o RdfsLiteral : "dct_identifier"
Node501 ||--|o RdfsLiteral : "rdfs_label"
Node501 ||--|o Node502 : "fio-epa-frs_hasRecord"
Node501 ||--|o Node519 : "fio-epa-frs_hasRecord"
Node501 ||--|o Node515 : "fio-epa-frs_hasRecord"
Node501 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Node501 ||--|o Node517 : "fio-epa-frs_hasRecord"
Node501 ||--|o Node501 : "fio-epa-frs_hasRecord"
Node501 ||--|o Node523 : "fio-epa-frs_hasRecord"
Node501 ||--|o Node521 : "fio-epa-frs_hasRecord"
Node501 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Node501 ||--|o Node518 : "fio-epa-frs_hasRecord"
Node501 ||--|o Node510 : "fio-epa-frs_hasRecord"
Node501 ||--|o OwlThing : "fio-epa-frs_hasRecord"
Node501 ||--|o Node512 : "fio-epa-frs_hasRecord"
Node501 ||--|o Node513 : "fio-epa-frs_hasRecord"
Node501 ||--|o Node359 : "fio-epa-frs_hasRecord"
Node501 ||--|o Node507 : "fio-epa-frs_hasRecord"
Node501 ||--|o Node506 : "fio-epa-frs_hasRecord"
Node501 ||--|o Node508 : "fio-epa-frs_hasRecord"
Node501 ||--|o Node499 : "fio-epa-frs_hasRecord"
Node501 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Node501 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node501 ||--|o OwlNamedIndividual : "fio_ofIndustry"
Node501 ||--|o OwlThing : "fio_ofIndustry"
Node501 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Node501 ||--|o FioIndustry : "fio_ofIndustry"
Node501 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Node501 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Node501 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Node501 ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Node501 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node501 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node501 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node501 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node501 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node501 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node501 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node501 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node501 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node501 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node501 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node501 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node501 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node501 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node501 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node501 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node501 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Node501 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Node501 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Node501 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Node501 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Node501 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Node501 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Node501 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Node501 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Node501 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Node501 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Node501 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Node501 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Node501 ||--|o OwlThing : "owl_sameAs"
Node501 ||--|o RdfsLiteral : "dct_identifier"
Node502 ||--|o RdfsLiteral : "rdfs_label"
Node502 ||--|o RdfsLiteral : "dct_identifier"
Node502 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node502 ||--|o OwlNamedIndividual : "fio_ofIndustry"
Node502 ||--|o OwlThing : "fio_ofIndustry"
Node502 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Node502 ||--|o FioIndustry : "fio_ofIndustry"
Node502 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Node502 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Node502 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Node502 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Node502 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Node502 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Node502 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Node502 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Node502 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Node502 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Node502 ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Node502 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node502 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node502 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node502 ||--|o Node502 : "fio-epa-frs_hasRecord"
Node502 ||--|o Node519 : "fio-epa-frs_hasRecord"
Node502 ||--|o Node515 : "fio-epa-frs_hasRecord"
Node502 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Node502 ||--|o Node517 : "fio-epa-frs_hasRecord"
Node502 ||--|o Node501 : "fio-epa-frs_hasRecord"
Node502 ||--|o Node523 : "fio-epa-frs_hasRecord"
Node502 ||--|o Node521 : "fio-epa-frs_hasRecord"
Node502 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Node502 ||--|o Node518 : "fio-epa-frs_hasRecord"
Node502 ||--|o Node510 : "fio-epa-frs_hasRecord"
Node502 ||--|o OwlThing : "fio-epa-frs_hasRecord"
Node502 ||--|o Node512 : "fio-epa-frs_hasRecord"
Node502 ||--|o Node513 : "fio-epa-frs_hasRecord"
Node502 ||--|o Node359 : "fio-epa-frs_hasRecord"
Node502 ||--|o Node507 : "fio-epa-frs_hasRecord"
Node502 ||--|o Node506 : "fio-epa-frs_hasRecord"
Node502 ||--|o Node508 : "fio-epa-frs_hasRecord"
Node502 ||--|o Node499 : "fio-epa-frs_hasRecord"
Node502 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Node502 ||--|o OwlThing : "owl_sameAs"
Node502 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node502 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node502 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node502 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node502 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node502 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node502 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node502 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node502 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node502 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node502 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node502 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node502 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node506 ||--|o RdfsLiteral : "rdfs_label"
Node506 ||--|o RdfsLiteral : "dct_identifier"
Node506 ||--|o OwlNamedIndividual : "fio_ofIndustry"
Node506 ||--|o OwlThing : "fio_ofIndustry"
Node506 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Node506 ||--|o FioIndustry : "fio_ofIndustry"
Node506 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Node506 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Node506 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Node506 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node506 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node506 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node506 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Node506 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Node506 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Node506 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Node506 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Node506 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Node506 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Node506 ||--|o OwlThing : "owl_sameAs"
Node506 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node506 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node506 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node506 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node506 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node506 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node506 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node506 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node506 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node506 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node506 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node506 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node506 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node507 ||--|o RdfsLiteral : "rdfs_label"
Node507 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node507 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node507 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node507 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node507 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node507 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node507 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node507 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node507 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node507 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node507 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node507 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node507 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node507 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node507 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node507 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node507 ||--|o OwlThing : "owl_sameAs"
Node507 ||--|o RdfsLiteral : "dct_identifier"
Node508 ||--|o RdfsLiteral : "rdfs_label"
Node508 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node508 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node508 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node508 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node508 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node508 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node508 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node508 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node508 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node508 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node508 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node508 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node508 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node508 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node508 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node508 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node508 ||--|o OwlThing : "owl_sameAs"
Node508 ||--|o RdfsLiteral : "dct_identifier"
Node510 ||--|o RdfsLiteral : "rdfs_label"
Node510 ||--|o RdfsLiteral : "dct_identifier"
Node510 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node510 ||--|o Node502 : "fio-epa-frs_hasRecord"
Node510 ||--|o Node519 : "fio-epa-frs_hasRecord"
Node510 ||--|o Node515 : "fio-epa-frs_hasRecord"
Node510 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Node510 ||--|o Node517 : "fio-epa-frs_hasRecord"
Node510 ||--|o Node501 : "fio-epa-frs_hasRecord"
Node510 ||--|o Node523 : "fio-epa-frs_hasRecord"
Node510 ||--|o Node521 : "fio-epa-frs_hasRecord"
Node510 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Node510 ||--|o Node518 : "fio-epa-frs_hasRecord"
Node510 ||--|o Node510 : "fio-epa-frs_hasRecord"
Node510 ||--|o OwlThing : "fio-epa-frs_hasRecord"
Node510 ||--|o Node512 : "fio-epa-frs_hasRecord"
Node510 ||--|o Node513 : "fio-epa-frs_hasRecord"
Node510 ||--|o Node359 : "fio-epa-frs_hasRecord"
Node510 ||--|o Node507 : "fio-epa-frs_hasRecord"
Node510 ||--|o Node506 : "fio-epa-frs_hasRecord"
Node510 ||--|o Node508 : "fio-epa-frs_hasRecord"
Node510 ||--|o Node499 : "fio-epa-frs_hasRecord"
Node510 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Node510 ||--|o OwlNamedIndividual : "fio_ofIndustry"
Node510 ||--|o OwlThing : "fio_ofIndustry"
Node510 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Node510 ||--|o FioIndustry : "fio_ofIndustry"
Node510 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Node510 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Node510 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Node510 ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Node510 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node510 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node510 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node510 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Node510 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Node510 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Node510 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Node510 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Node510 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Node510 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Node510 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Node510 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Node510 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Node510 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Node510 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Node510 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Node510 ||--|o OwlThing : "owl_sameAs"
Node510 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node510 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node510 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node510 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node510 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node510 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node510 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node510 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node510 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node510 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node510 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node510 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node510 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node512 ||--|o RdfsLiteral : "rdfs_label"
Node512 ||--|o OwlNamedIndividual : "fio_ofIndustry"
Node512 ||--|o OwlThing : "fio_ofIndustry"
Node512 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Node512 ||--|o FioIndustry : "fio_ofIndustry"
Node512 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Node512 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Node512 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Node512 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node512 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node512 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node512 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node512 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node512 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node512 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node512 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node512 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node512 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node512 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node512 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node512 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node512 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node512 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node512 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node512 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Node512 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Node512 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Node512 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Node512 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Node512 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Node512 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Node512 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Node512 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Node512 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Node512 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Node512 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Node512 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Node512 ||--|o OwlThing : "owl_sameAs"
Node512 ||--|o RdfsLiteral : "dct_identifier"
Node513 ||--|o RdfsLiteral : "rdfs_label"
Node513 ||--|o RdfsLiteral : "dct_identifier"
Node513 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node513 ||--|o Node502 : "fio-epa-frs_hasRecord"
Node513 ||--|o Node519 : "fio-epa-frs_hasRecord"
Node513 ||--|o Node515 : "fio-epa-frs_hasRecord"
Node513 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Node513 ||--|o Node517 : "fio-epa-frs_hasRecord"
Node513 ||--|o Node501 : "fio-epa-frs_hasRecord"
Node513 ||--|o Node523 : "fio-epa-frs_hasRecord"
Node513 ||--|o Node521 : "fio-epa-frs_hasRecord"
Node513 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Node513 ||--|o Node518 : "fio-epa-frs_hasRecord"
Node513 ||--|o Node510 : "fio-epa-frs_hasRecord"
Node513 ||--|o OwlThing : "fio-epa-frs_hasRecord"
Node513 ||--|o Node512 : "fio-epa-frs_hasRecord"
Node513 ||--|o Node513 : "fio-epa-frs_hasRecord"
Node513 ||--|o Node359 : "fio-epa-frs_hasRecord"
Node513 ||--|o Node507 : "fio-epa-frs_hasRecord"
Node513 ||--|o Node506 : "fio-epa-frs_hasRecord"
Node513 ||--|o Node508 : "fio-epa-frs_hasRecord"
Node513 ||--|o Node499 : "fio-epa-frs_hasRecord"
Node513 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Node513 ||--|o OwlNamedIndividual : "fio_ofIndustry"
Node513 ||--|o OwlThing : "fio_ofIndustry"
Node513 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Node513 ||--|o FioIndustry : "fio_ofIndustry"
Node513 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Node513 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Node513 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Node513 ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Node513 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node513 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node513 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node513 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Node513 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Node513 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Node513 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Node513 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Node513 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Node513 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Node513 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Node513 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Node513 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Node513 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Node513 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Node513 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Node513 ||--|o OwlThing : "owl_sameAs"
Node513 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node513 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node513 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node513 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node513 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node513 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node513 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node513 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node513 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node513 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node513 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node513 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node513 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node515 ||--|o RdfsLiteral : "rdfs_label"
Node515 ||--|o RdfsLiteral : "dct_identifier"
Node515 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node515 ||--|o Node502 : "fio-epa-frs_hasRecord"
Node515 ||--|o Node519 : "fio-epa-frs_hasRecord"
Node515 ||--|o Node515 : "fio-epa-frs_hasRecord"
Node515 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Node515 ||--|o Node517 : "fio-epa-frs_hasRecord"
Node515 ||--|o Node501 : "fio-epa-frs_hasRecord"
Node515 ||--|o Node523 : "fio-epa-frs_hasRecord"
Node515 ||--|o Node521 : "fio-epa-frs_hasRecord"
Node515 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Node515 ||--|o Node518 : "fio-epa-frs_hasRecord"
Node515 ||--|o Node510 : "fio-epa-frs_hasRecord"
Node515 ||--|o OwlThing : "fio-epa-frs_hasRecord"
Node515 ||--|o Node512 : "fio-epa-frs_hasRecord"
Node515 ||--|o Node513 : "fio-epa-frs_hasRecord"
Node515 ||--|o Node359 : "fio-epa-frs_hasRecord"
Node515 ||--|o Node507 : "fio-epa-frs_hasRecord"
Node515 ||--|o Node506 : "fio-epa-frs_hasRecord"
Node515 ||--|o Node508 : "fio-epa-frs_hasRecord"
Node515 ||--|o Node499 : "fio-epa-frs_hasRecord"
Node515 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Node515 ||--|o OwlNamedIndividual : "fio_ofIndustry"
Node515 ||--|o OwlThing : "fio_ofIndustry"
Node515 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Node515 ||--|o FioIndustry : "fio_ofIndustry"
Node515 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Node515 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Node515 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Node515 ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Node515 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node515 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node515 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node515 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Node515 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Node515 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Node515 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Node515 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Node515 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Node515 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Node515 ||--|o OwlThing : "owl_sameAs"
Node515 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node515 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node515 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node515 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node515 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node515 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node515 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node515 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node515 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node515 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node515 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node515 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node515 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node517 ||--|o RdfsLiteral : "rdfs_label"
Node517 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node517 ||--|o OwlNamedIndividual : "fio_ofIndustry"
Node517 ||--|o OwlThing : "fio_ofIndustry"
Node517 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Node517 ||--|o FioIndustry : "fio_ofIndustry"
Node517 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Node517 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Node517 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Node517 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Node517 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Node517 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Node517 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Node517 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Node517 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Node517 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Node517 ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Node517 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node517 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node517 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node517 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node517 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node517 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node517 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node517 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node517 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node517 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node517 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node517 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node517 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node517 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node517 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node517 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node517 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Node517 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Node517 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Node517 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Node517 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Node517 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Node517 ||--|o Node502 : "fio-epa-frs_hasRecord"
Node517 ||--|o Node519 : "fio-epa-frs_hasRecord"
Node517 ||--|o Node515 : "fio-epa-frs_hasRecord"
Node517 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Node517 ||--|o Node517 : "fio-epa-frs_hasRecord"
Node517 ||--|o Node501 : "fio-epa-frs_hasRecord"
Node517 ||--|o Node523 : "fio-epa-frs_hasRecord"
Node517 ||--|o Node521 : "fio-epa-frs_hasRecord"
Node517 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Node517 ||--|o Node518 : "fio-epa-frs_hasRecord"
Node517 ||--|o Node510 : "fio-epa-frs_hasRecord"
Node517 ||--|o OwlThing : "fio-epa-frs_hasRecord"
Node517 ||--|o Node512 : "fio-epa-frs_hasRecord"
Node517 ||--|o Node513 : "fio-epa-frs_hasRecord"
Node517 ||--|o Node359 : "fio-epa-frs_hasRecord"
Node517 ||--|o Node507 : "fio-epa-frs_hasRecord"
Node517 ||--|o Node506 : "fio-epa-frs_hasRecord"
Node517 ||--|o Node508 : "fio-epa-frs_hasRecord"
Node517 ||--|o Node499 : "fio-epa-frs_hasRecord"
Node517 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Node517 ||--|o OwlThing : "owl_sameAs"
Node517 ||--|o RdfsLiteral : "dct_identifier"
Node518 ||--|o RdfsLiteral : "rdfs_label"
Node518 ||--|o RdfsLiteral : "dct_identifier"
Node518 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node518 ||--|o OwlNamedIndividual : "fio_ofIndustry"
Node518 ||--|o OwlThing : "fio_ofIndustry"
Node518 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Node518 ||--|o FioIndustry : "fio_ofIndustry"
Node518 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Node518 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Node518 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Node518 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Node518 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Node518 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Node518 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Node518 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Node518 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Node518 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Node518 ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Node518 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node518 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node518 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node518 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Node518 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Node518 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Node518 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Node518 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Node518 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Node518 ||--|o Node502 : "fio-epa-frs_hasRecord"
Node518 ||--|o Node519 : "fio-epa-frs_hasRecord"
Node518 ||--|o Node515 : "fio-epa-frs_hasRecord"
Node518 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Node518 ||--|o Node517 : "fio-epa-frs_hasRecord"
Node518 ||--|o Node501 : "fio-epa-frs_hasRecord"
Node518 ||--|o Node523 : "fio-epa-frs_hasRecord"
Node518 ||--|o Node521 : "fio-epa-frs_hasRecord"
Node518 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Node518 ||--|o Node518 : "fio-epa-frs_hasRecord"
Node518 ||--|o Node510 : "fio-epa-frs_hasRecord"
Node518 ||--|o OwlThing : "fio-epa-frs_hasRecord"
Node518 ||--|o Node512 : "fio-epa-frs_hasRecord"
Node518 ||--|o Node513 : "fio-epa-frs_hasRecord"
Node518 ||--|o Node359 : "fio-epa-frs_hasRecord"
Node518 ||--|o Node507 : "fio-epa-frs_hasRecord"
Node518 ||--|o Node506 : "fio-epa-frs_hasRecord"
Node518 ||--|o Node508 : "fio-epa-frs_hasRecord"
Node518 ||--|o Node499 : "fio-epa-frs_hasRecord"
Node518 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Node518 ||--|o OwlThing : "owl_sameAs"
Node518 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node518 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node518 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node518 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node518 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node518 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node518 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node518 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node518 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node518 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node518 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node518 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node518 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node519 ||--|o RdfsLiteral : "rdfs_label"
Node519 ||--|o RdfsLiteral : "dct_identifier"
Node519 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node519 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node519 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node519 ||--|o OwlThing : "owl_sameAs"
Node519 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node519 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node519 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node519 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node519 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node519 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node519 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node519 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node519 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node519 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node519 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node519 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node519 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node521 ||--|o RdfsLiteral : "rdfs_label"
Node521 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node521 ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Node521 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node521 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node521 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node521 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node521 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node521 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node521 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node521 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node521 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node521 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node521 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node521 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node521 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Node521 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node521 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node521 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node521 ||--|o Node502 : "fio-epa-frs_hasRecord"
Node521 ||--|o Node519 : "fio-epa-frs_hasRecord"
Node521 ||--|o Node515 : "fio-epa-frs_hasRecord"
Node521 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Node521 ||--|o Node517 : "fio-epa-frs_hasRecord"
Node521 ||--|o Node501 : "fio-epa-frs_hasRecord"
Node521 ||--|o Node523 : "fio-epa-frs_hasRecord"
Node521 ||--|o Node521 : "fio-epa-frs_hasRecord"
Node521 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Node521 ||--|o Node518 : "fio-epa-frs_hasRecord"
Node521 ||--|o Node510 : "fio-epa-frs_hasRecord"
Node521 ||--|o OwlThing : "fio-epa-frs_hasRecord"
Node521 ||--|o Node512 : "fio-epa-frs_hasRecord"
Node521 ||--|o Node513 : "fio-epa-frs_hasRecord"
Node521 ||--|o Node359 : "fio-epa-frs_hasRecord"
Node521 ||--|o Node507 : "fio-epa-frs_hasRecord"
Node521 ||--|o Node506 : "fio-epa-frs_hasRecord"
Node521 ||--|o Node508 : "fio-epa-frs_hasRecord"
Node521 ||--|o Node499 : "fio-epa-frs_hasRecord"
Node521 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Node521 ||--|o OwlThing : "owl_sameAs"
Node521 ||--|o RdfsLiteral : "dct_identifier"
Node523 ||--|o RdfsLiteral : "rdfs_label"
Node523 ||--|o RdfsLiteral : "dct_identifier"
Node523 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Node523 ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Node523 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Node523 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Node523 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Node523 ||--|o Node502 : "fio-epa-frs_hasRecord"
Node523 ||--|o Node519 : "fio-epa-frs_hasRecord"
Node523 ||--|o Node515 : "fio-epa-frs_hasRecord"
Node523 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Node523 ||--|o Node517 : "fio-epa-frs_hasRecord"
Node523 ||--|o Node501 : "fio-epa-frs_hasRecord"
Node523 ||--|o Node523 : "fio-epa-frs_hasRecord"
Node523 ||--|o Node521 : "fio-epa-frs_hasRecord"
Node523 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Node523 ||--|o Node518 : "fio-epa-frs_hasRecord"
Node523 ||--|o Node510 : "fio-epa-frs_hasRecord"
Node523 ||--|o OwlThing : "fio-epa-frs_hasRecord"
Node523 ||--|o Node512 : "fio-epa-frs_hasRecord"
Node523 ||--|o Node513 : "fio-epa-frs_hasRecord"
Node523 ||--|o Node359 : "fio-epa-frs_hasRecord"
Node523 ||--|o Node507 : "fio-epa-frs_hasRecord"
Node523 ||--|o Node506 : "fio-epa-frs_hasRecord"
Node523 ||--|o Node508 : "fio-epa-frs_hasRecord"
Node523 ||--|o Node499 : "fio-epa-frs_hasRecord"
Node523 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Node523 ||--|o OwlThing : "owl_sameAs"
Node523 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Node523 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Node523 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Node523 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Node523 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Node523 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Node523 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Node523 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Node523 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Node523 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Node523 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Node523 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Node523 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsAgency ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.Agriculture ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.Agriculture ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.Commerce ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.Commerce ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.Congress ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.Congress ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.Defense ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.Defense ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.Energy ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.Energy ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.HealthandHumanServices ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.HealthandHumanServices ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.HomelandSecurity ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.HomelandSecurity ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.HousingandUrbanDevelopment ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.HousingandUrbanDevelopment ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.Interior ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.Interior ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.Judicial ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.Judicial ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.Justice ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.Justice ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.Labor ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.Labor ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.State ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.State ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.Transportation ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.Transportation ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.Treasury ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.Treasury ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAgency.VeteransAffairs ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAgency.VeteransAffairs ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAirProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAirProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAnimalOperation ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAnimalOperation ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAssistanceSupportProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAssistanceSupportProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsChemicalReleaseProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsChemicalReleaseProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsChemicalStorageProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsChemicalStorageProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsCoastalOceanProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsCoastalOceanProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsComplianceInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsComplianceInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsComplianceSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsComplianceSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsDrinkingWaterProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsDrinkingWaterProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "dct_date"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "dct_title"
Fio-epa-frsEPA-PFAS-Facility ||--|o SdosText : "sdos_address"
Fio-epa-frsEPA-PFAS-Facility ||--|o SdosPostalAddress : "sdos_address"
Fio-epa-frsEPA-PFAS-Facility ||--|o GeoGeometry : "geo_hasGeometry"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "dct_identifier"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "fio-epa-frs_hasFRSId"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "dct_created"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node502 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node519 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node515 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node517 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node501 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node523 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node521 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node518 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node510 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlThing : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node512 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node513 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node359 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node507 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node506 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node508 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Node499 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "dct_modified"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlThing : "fio-epa-frs_ofFacilityType"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsFacilityType : "fio-epa-frs_ofFacilityType"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "dct_alternative"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlThing : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o FioIndustry : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.VeteransAffairs : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Interior : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Justice : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Defense : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Energy : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Agriculture : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Commerce : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.HealthandHumanServices : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.HomelandSecurity : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Transportation : "fio_ownedBy"
Fio-epa-frsEcologyOperation ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEcologyOperation ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsElectronicPermitSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsElectronicPermitSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsEnforcementInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEnforcementInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsEnforcementSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEnforcementSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsEnvironmentalInterestByProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEnvironmentalInterestByProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsEnvironmentalInterestType ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEnvironmentalInterestType ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "dct_date"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "dct_title"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o SdosText : "sdos_address"
Fio-epa-frsFRS-Facility ||--|o SdosPostalAddress : "sdos_address"
Fio-epa-frsFRS-Facility ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o GeoGeometry : "geo_hasGeometry"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "dct_identifier"
Fio-epa-frsFRS-Facility ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsFRS-Facility ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "fio-epa-frs_hasFRSId"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "dct_created"
Fio-epa-frsFRS-Facility ||--|o Node502 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node519 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node515 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node517 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node501 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node523 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node521 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node518 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node510 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node512 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node513 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node359 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node507 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node506 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node508 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Node499 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "dct_modified"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_ofFacilityType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsFacilityType : "fio-epa-frs_ofFacilityType"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "dct_alternative"
Fio-epa-frsFRS-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o FioIndustry : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o OwlNamedIndividual : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.VeteransAffairs : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Interior : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Justice : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Defense : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Energy : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Agriculture : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Commerce : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.HealthandHumanServices : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.HomelandSecurity : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Transportation : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFacilitySiteIdentification ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsFacilitySiteIdentification ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsFacilityType ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsFacilityType ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsGrantSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsGrantSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsGroundWaterProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsGroundWaterProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsHazardousWasteProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsHazardousWasteProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsHealthSafetyProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsHealthSafetyProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsLegacySystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsLegacySystem ||--|o OwlThing : "fio-epa-frs_replacedBy"
Fio-epa-frsLegacySystem ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsLegacySystem ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsLegacySystem ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsLegacySystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsLegalEnforcementActivities ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsLegalEnforcementActivities ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsPermitInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsPermitInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsPermitSystem ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_partOf"
Fio-epa-frsPermitSystem ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_partOf"
Fio-epa-frsPermitSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsPermitSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsPesticidesProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsPesticidesProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsProgramInformationSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsProgramInformationSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsProjectSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsProjectSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsRadiationProtectionProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsRadiationProtectionProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsRecord ||--|o Node502 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node519 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node515 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node517 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node501 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node523 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node521 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node518 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node510 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o OwlThing : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node512 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node513 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node359 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node507 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node506 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node508 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Node499 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o RdfsLiteral : "dct_identifier"
Fio-epa-frsRecord ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o OwlNamedIndividual : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o OwlThing : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o FioIndustry : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsRecord ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o OwlThing : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRegistryInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsRegistryInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsRegistrySystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsRegistrySystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsRemediationRedevelopmentProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsRemediationRedevelopmentProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsReportingInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsReportingInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsReportingSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsReportingSystem ||--|o OwlThing : "fio-epa-frs_replacedBy"
Fio-epa-frsReportingSystem ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsReportingSystem ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsReportingSystem ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsReportingSystem ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_partOf"
Fio-epa-frsReportingSystem ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_partOf"
Fio-epa-frsReportingSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsRiskInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsRiskInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsSiteInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsSiteInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsSiteSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsSiteSystem ||--|o OwlThing : "fio-epa-frs_replacedBy"
Fio-epa-frsSiteSystem ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsSiteSystem ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsSiteSystem ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsSiteSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsSolidWasteProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsSolidWasteProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsStateSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsStateSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsSupplementalRecord ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsSupplementalRecord ||--|o Node502 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node519 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node515 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node517 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node501 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node523 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node521 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node518 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node510 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node512 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node513 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node359 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node507 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node506 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node508 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Node499 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o OwlNamedIndividual : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o FioIndustry : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o Node359 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Node510 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Node501 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Node507 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Node521 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Node512 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Node499 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Node513 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Node517 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsSupplementalRecord ||--|o RdfsLiteral : "dct_identifier"
Fio-epa-frsTribalSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsTribalSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsUndergroundStorageTankProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsUndergroundStorageTankProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsWasteWaterProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsWasteWaterProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsWaterResourcesProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsWaterResourcesProgram ||--|o OwlThing : "owl_sameAs"
FioIndustry ||--|o OwlThing : "owl_sameAs"
KwgoS2CellLevel13 ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustryCode ||--|o RdfsLiteral : "rdfs_label"
NaicsNAICS-IndustryCode ||--|o OwlNamedIndividual : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o OwlThing : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o FioIndustry : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustryCode : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-IndustryCode ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustryCode ||--|o RdfsLiteral : "dct_identifier"
NaicsNAICS-IndustryGroup ||--|o RdfsLiteral : "rdfs_label"
NaicsNAICS-IndustryGroup ||--|o OwlNamedIndividual : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o OwlThing : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o FioIndustry : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustryCode : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-IndustryGroup ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustryGroup ||--|o RdfsLiteral : "dct_identifier"
NaicsNAICS-IndustrySector ||--|o RdfsLiteral : "rdfs_label"
NaicsNAICS-IndustrySector ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-IndustrySector ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustrySector ||--|o RdfsLiteral : "dct_identifier"
NaicsNAICS-IndustrySubsector ||--|o RdfsLiteral : "rdfs_label"
NaicsNAICS-IndustrySubsector ||--|o OwlNamedIndividual : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o OwlThing : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o FioIndustry : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustryCode : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-IndustrySubsector ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustrySubsector ||--|o RdfsLiteral : "dct_identifier"

```



## Imports


* okns:dc
* okns:prov
* okns:kwg
* okns:extended_types
* linkml:types
* okns:geo
* okns:time
* okns:sdo
* okns:owl-rdf-rdfs



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [Node503](classes/Node503.md) | None<br/>|  | 
| [KwgoS2CellLevel13](classes/KwgoS2CellLevel13.md) | None<br/>| 249509 | 
| [OwlThing](classes/OwlThing.md) | The class of OWL individuals.<br/>| 731253 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node359](classes/Node359.md) | None<br/>| 165107 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node499](classes/Node499.md) | None<br/>| 151232 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node501](classes/Node501.md) | None<br/>| 198462 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node502](classes/Node502.md) | None<br/>| 18113 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node506](classes/Node506.md) | None<br/>| 23765 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node507](classes/Node507.md) | None<br/>| 8847 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node508](classes/Node508.md) | None<br/>| 380 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node510](classes/Node510.md) | None<br/>| 329237 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node512](classes/Node512.md) | None<br/>| 20115 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node513](classes/Node513.md) | None<br/>| 86645 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node515](classes/Node515.md) | None<br/>| 31220 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node517](classes/Node517.md) | None<br/>| 1318 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node518](classes/Node518.md) | None<br/>| 368761 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node519](classes/Node519.md) | None<br/>| 80 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node521](classes/Node521.md) | None<br/>| 26083 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Node523](classes/Node523.md) | None<br/>| 13343 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAirProgram](classes/Fio-epa-frsAirProgram.md) | ENVIRONMENTAL PROGRAMS THAT REGULATE OR MONITOR AIR EMISSIONS FROM AREA, STATIONARY, AND MOBILE SOURCES, AS REQUIRED BY THE CLEAN AIR ACT<br/>| 34 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAnimalOperation](classes/Fio-epa-frsAnimalOperation.md) | ENVIRONMENTAL PROGRAMS RELATED TO ANIMAL OPERATIONS E.G LIVESTOCK WASTE CONTROL<br/>| 4 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAssistanceSupportProgram](classes/Fio-epa-frsAssistanceSupportProgram.md) | ENVIRONMENTAL PROGRAMS THAT PROVIDE ASSISTANCE TO THE REGULATED COMMUNITY AND THE GENERAL PUBLIC (E.G., ENVIRONMENTAL GRANTS, OUTREACH ACTIVITIES) OR ACTIVITIES THAT PROVIDE SUPPORT ACROSS ENVIRONMENTAL PROGRAMS.<br/>| 6 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsChemicalReleaseProgram](classes/Fio-epa-frsChemicalReleaseProgram.md) | ENVIRONMENTAL PROGRAMS THAT REGULATE OR MONITOR CHEMICALS RELEASED TO THE ENVIRONMENT (E.G., TOXIC RELEASE INVENTORY, RELEASE ASSESSMENTS).<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsChemicalStorageProgram](classes/Fio-epa-frsChemicalStorageProgram.md) | ENVIRONMENTAL PROGRAMS THAT REGULATE OR MONITOR THE STORAGE OF CHEMICALS (E.G., RISK MANAGEMENT PROGRAM, SUPERFUND AMENDMENTS AND REAUTHORIZATION ACT (SARA) TITLE III PROGRAM).<br/>| 5 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsChemicalstorageprograms](classes/Fio-epa-frsChemicalstorageprograms.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsCoastalOceanProgram](classes/Fio-epa-frsCoastalOceanProgram.md) | ENVIRONMENTAL PROGRAMS THAT IMPROVE THE QUALITY OF COASTAL AND MARINE ECOSYSTEMS AND PROTECT BEACHES, COAST, AND OCEAN RESOURCES FROM POLLUTION.<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsComplianceInterest](classes/Fio-epa-frsComplianceInterest.md) | None<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsComplianceRecord](classes/Fio-epa-frsComplianceRecord.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsComplianceSystem](classes/Fio-epa-frsComplianceSystem.md) | None<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsDrinkingWaterProgram](classes/Fio-epa-frsDrinkingWaterProgram.md) | ENVIRONMENTAL PROGRAMS THAT PROTECT THE QUALITY OF DRINKING WATER IN THE UNITED STATES, AS REQUIRED BY THE SAFE DRINKING WATER ACT.<br/>| 5 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsEcologyOperation](classes/Fio-epa-frsEcologyOperation.md) | PROGRAMS THAT CONCENTRATE ON ECOLOGICAL SYSTEMS SUCH AS FOREST AND TREE EXPERTISE<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsElectronicPermitSystem](classes/Fio-epa-frsElectronicPermitSystem.md) | ELECTRONIC PERMIT SYSTEM<br/>| 8 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsEnforcementActivity](classes/Fio-epa-frsEnforcementActivity.md) | A record that tracks a specific legal, corrective or assistance action taken against a facility<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsEnforcementInterest](classes/Fio-epa-frsEnforcementInterest.md) | None<br/>| 5 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsEnforcementSystem](classes/Fio-epa-frsEnforcementSystem.md) | None<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsEnforcementTrackingRecord](classes/Fio-epa-frsEnforcementTrackingRecord.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsEnvironmentalInterestByProgram](classes/Fio-epa-frsEnvironmentalInterestByProgram.md) | None<br/>| 7 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsEnvironmentalInterestByRecordType](classes/Fio-epa-frsEnvironmentalInterestByRecordType.md) | Interest classification based on the main subject of the record and what type of activity or entity it identifies.<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsEnvironmentalInterestType](classes/Fio-epa-frsEnvironmentalInterestType.md) | The environmental permit or regulatory program type that applies to the facility site<br/>| 5 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsEPA-PFAS-Facility](classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools based on industry.<br/>| 23623 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsFacilitySiteIdentification](classes/Fio-epa-frsFacilitySiteIdentification.md) | INCLUDES SYSTEMS THAT MAINTAIN BASIC IDENTIFICATION INFORMATION ABOUT FACILITIES/SITES AND LINKAGES TO ENVIRONMENTAL PERMITS AND PROGRAMS AT THE STATE, TRIBAL AND NATIONAL LEVEL.<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsFacilityType](classes/Fio-epa-frsFacilityType.md) | Type of Facility as defined by EPA FRS facility type controlled vocabulary<br/>| 14 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsFRS-Facility](classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service<br/>| 802699 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsGrantSystem](classes/Fio-epa-frsGrantSystem.md) | None<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsGroundWaterProgram](classes/Fio-epa-frsGroundWaterProgram.md) | ENVIRONMENTAL PROGRAMS DESIGNED TO PROTECT GROUND WATER (E.G., UNDERGROUND INJECTION CONTROL (UIC),  MINERAL EXPLORATION).<br/>| 4 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsHazardousWasteProgram](classes/Fio-epa-frsHazardousWasteProgram.md) | ENVIRONMENTAL PROGRAMS THAT REGULATE HAZARDOUS WASTE, INCLUDING THE GENERATION, TRANSPORTATION, TREATMENT, STORAGE, AND DISPOSAL OF HAZARDOUS WASTE, AS REQUIRED BY THE RESOURCE CONSERVATION AND RECOVERY ACT (RCRA).<br/>| 23 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsHealthSafetyProgram](classes/Fio-epa-frsHealthSafetyProgram.md) | PROGRAMS DESIGNED TO REDUCE HAZARDS AND PREVENT INJURIES, ILLNESSES AND DEATHS IN THE WORKPLACE.<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsLegacySystem](classes/Fio-epa-frsLegacySystem.md) | None<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsLegalEnforcementActivities](classes/Fio-epa-frsLegalEnforcementActivities.md) | LEGAL OR ENFORCEMENT ACTIVITIES IN SUPPORT OF OTHER ENVIRONMENTAL PROGRAMS.<br/>| 5 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsMonitoringRecord](classes/Fio-epa-frsMonitoringRecord.md) | A record that monitors a facility on an ongoing basis<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsPermitInterest](classes/Fio-epa-frsPermitInterest.md) | Environmental Interests that create records that are permits or licenses<br/>| 16 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsPermitRecord](classes/Fio-epa-frsPermitRecord.md) | A record that tracks a permit or license awarded to the facility<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsPermitSystem](classes/Fio-epa-frsPermitSystem.md) | None<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsPesticidesProgram](classes/Fio-epa-frsPesticidesProgram.md) | ENVIRONMENTAL PROGRAMS THAT MONITOR BUSINESSES, GOVERNMENT AGENCIES, AND INDIVIDUALS THAT HANDLE, STORE, SELL, AND/OR APPLY PESITICIDES.<br/>| 5 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsProgramInformationSystem](classes/Fio-epa-frsProgramInformationSystem.md) | An Information System maintained for an environmental program<br/>| 10 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsProjectRecord](classes/Fio-epa-frsProjectRecord.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsProjectSystem](classes/Fio-epa-frsProjectSystem.md) | None<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsRadiationProtectionProgram](classes/Fio-epa-frsRadiationProtectionProgram.md) | ENVIRONMENTAL PROGRAMS DESIGNED TO PROTECT PEOPLE AND THE ENVIRONMENT FROM HARMFUL EXPOSURE TO RADIATION<br/>| 7 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsRecord](classes/Fio-epa-frsRecord.md) | None<br/>| 128 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsRegistrationRecord](classes/Fio-epa-frsRegistrationRecord.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsRegistryInterest](classes/Fio-epa-frsRegistryInterest.md) | None<br/>| 4 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsRegistrySystem](classes/Fio-epa-frsRegistrySystem.md) | None<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsRemediationRedevelopmentProgram](classes/Fio-epa-frsRemediationRedevelopmentProgram.md) | ENVIRONMENTAL PROGRAMS AIMED AT CLEANING UP AND/OR REDEVELOPING UNCONTROLLED OR ABANDONED PLACES WHERE HAZARDOUS WASTE MAY BE LOCATED POSSIBLY AFFECTING LOCAL ECOSYSTEMS OR PEOPLE.<br/>| 17 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsReportingInterest](classes/Fio-epa-frsReportingInterest.md) | None<br/>| 6 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsReportingRecord](classes/Fio-epa-frsReportingRecord.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsReportingSystem](classes/Fio-epa-frsReportingSystem.md) | None<br/>| 21 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsRiskInterest](classes/Fio-epa-frsRiskInterest.md) | None<br/>| 4 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsRiskPlanRecord](classes/Fio-epa-frsRiskPlanRecord.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsSiteInterest](classes/Fio-epa-frsSiteInterest.md) | None<br/>| 16 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsSiteRecord](classes/Fio-epa-frsSiteRecord.md) | A record that monitors a site, beyond specific ownership of one organization and their activities, e.g. superfund site, air monitoring site<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsSiteSystem](classes/Fio-epa-frsSiteSystem.md) | None<br/>| 7 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsSolidWasteProgram](classes/Fio-epa-frsSolidWasteProgram.md) | ENVIRONMENTAL PROGRAMS THAT REGULATE SOLID WASTES (E.G., COMPOST SITES, LANDFILLS, TRANSFER STATIONS).<br/>| 17 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsStateSystem](classes/Fio-epa-frsStateSystem.md) | None<br/>| 48 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsStateTrackingRecord](classes/Fio-epa-frsStateTrackingRecord.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsStationSystem](classes/Fio-epa-frsStationSystem.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsSupplementalRecord](classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies something other than the facility itself (e.g. permit, license, incident, enforcement action records)<br/>| 147231 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsTribalSystem](classes/Fio-epa-frsTribalSystem.md) | None<br/>| 6 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsTribalTrackingRecord](classes/Fio-epa-frsTribalTrackingRecord.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsUndergroundStorageTankProgram](classes/Fio-epa-frsUndergroundStorageTankProgram.md) | ENVIRONMENTAL PROGRAMS DESIGNED TO REDUCE THE CHANCE OF RELEASES FROM UNDERGROUND STORAGE TANKS (USTS), DETECT LEAKS AND SPILLS WHEN THEY DO OCCUR, AND SECURE PROMPT CLEANUP<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsWasteWaterProgram](classes/Fio-epa-frsWasteWaterProgram.md) | ENVIRONMENTAL PROGRAMS THAT REGULATE DISCHARGES OF POLLUTANTS TO WATERS OF THE UNITED STATES, AS REQUIRED BY THE CLEAN WATER ACT.<br/>| 29 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsWaterResourcesProgram](classes/Fio-epa-frsWaterResourcesProgram.md) | ENVIRONMENTAL PROGRAMS THAT MANAGE WATER RESOURCES TO MEET THE NEEDS OF THE NATURAL ENVIRONMENT AND HUMAN COMMUNITIES, INCLUDING WATERSHED MANAGEMENT, STREAM FLOWS, WATER RIGHTS, WELL DRILLING, USE OF WATER SUPPLIES, AND DAM SAFETY.<br/>| 4 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[FioFacility](classes/FioFacility.md) | Any physical building, building complex or site (e.g. an airstrip, a mine, or superfund site) at which a commercial or institutional activity occurs.<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[FioIndustry](classes/FioIndustry.md) | A distinct group of productive or profit-making enterprises.<br/>| 736 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[NaicsNAICS-Industry](classes/NaicsNAICS-Industry.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[NaicsNAICS-IndustryCode](classes/NaicsNAICS-IndustryCode.md) | None<br/>| 1701 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[NaicsNAICS-IndustryGroup](classes/NaicsNAICS-IndustryGroup.md) | None<br/>| 308 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[NaicsNAICS-IndustrySector](classes/NaicsNAICS-IndustrySector.md) | None<br/>| 24 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[NaicsNAICS-IndustrySubsector](classes/NaicsNAICS-IndustrySubsector.md) | None<br/>| 96 | 
| [ProvAgent](classes/ProvAgent.md) | An agent is something that bears some form of responsibility for an activity taking place, for the existence of an entity, or for another agent's activity.<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency](classes/Fio-epa-frsAgency.md) | Federal Agency as identified in EPA Facility Registry Service<br/>| 54 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.Agriculture](classes/Fio-epa-frsAgency.Agriculture.md) | None<br/>| 10 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.Commerce](classes/Fio-epa-frsAgency.Commerce.md) | None<br/>| 6 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.Congress](classes/Fio-epa-frsAgency.Congress.md) | None<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.Defense](classes/Fio-epa-frsAgency.Defense.md) | None<br/>| 19 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.Energy](classes/Fio-epa-frsAgency.Energy.md) | None<br/>| 27 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.HealthandHumanServices](classes/Fio-epa-frsAgency.HealthandHumanServices.md) | None<br/>| 6 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.HomelandSecurity](classes/Fio-epa-frsAgency.HomelandSecurity.md) | None<br/>| 11 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.HousingandUrbanDevelopment](classes/Fio-epa-frsAgency.HousingandUrbanDevelopment.md) | None<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.Interior](classes/Fio-epa-frsAgency.Interior.md) | None<br/>| 10 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.Judicial](classes/Fio-epa-frsAgency.Judicial.md) | None<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.Justice](classes/Fio-epa-frsAgency.Justice.md) | None<br/>| 6 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.Labor](classes/Fio-epa-frsAgency.Labor.md) | None<br/>| 4 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.State](classes/Fio-epa-frsAgency.State.md) | None<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.Transportation](classes/Fio-epa-frsAgency.Transportation.md) | None<br/>| 10 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.Treasury](classes/Fio-epa-frsAgency.Treasury.md) | None<br/>| 4 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Fio-epa-frsAgency.VeteransAffairs](classes/Fio-epa-frsAgency.VeteransAffairs.md) | None<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[FioOrganization](classes/FioOrganization.md) | <br/>|  | 
| [RdfsResource](classes/RdfsResource.md) | The class resource, everything.<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfsLiteral](classes/RdfsLiteral.md) | The class of literal values, eg. textual strings and integers.<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlRational](classes/OwlRational.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlReal](classes/OwlReal.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdAnyURI](classes/XsdAnyURI.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdBase64Binary](classes/XsdBase64Binary.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdBoolean](classes/XsdBoolean.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdByte](classes/XsdByte.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdDateTime](classes/XsdDateTime.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdDecimal](classes/XsdDecimal.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdDouble](classes/XsdDouble.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdFloat](classes/XsdFloat.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdHexBinary](classes/XsdHexBinary.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdInt](classes/XsdInt.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdInteger](classes/XsdInteger.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdLanguage](classes/XsdLanguage.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdLong](classes/XsdLong.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdName](classes/XsdName.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNCName](classes/XsdNCName.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNegativeInteger](classes/XsdNegativeInteger.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNMTOKEN](classes/XsdNMTOKEN.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNonNegativeInteger](classes/XsdNonNegativeInteger.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNonPositiveInteger](classes/XsdNonPositiveInteger.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNormalizedString](classes/XsdNormalizedString.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdPositiveInteger](classes/XsdPositiveInteger.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdShort](classes/XsdShort.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdToken](classes/XsdToken.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdUnsignedByte](classes/XsdUnsignedByte.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdUnsignedInt](classes/XsdUnsignedInt.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdUnsignedLong](classes/XsdUnsignedLong.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdUnsignedShort](classes/XsdUnsignedShort.md) | None<br/>|  | 
| [XsdDate](classes/XsdDate.md) | None<br/>|  | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [dct_decription](slots/dct_decription.md) | <br/>No occurrences of this slot in the graph.|  |
| [dct_decscription](slots/dct_decscription.md) | <br/>No occurrences of this slot in the graph.|  |
| [fio_epa_frs_fromSystem](slots/fio_epa_frs_fromSystem.md) | <br/>| 1231696 |
| [fio_epa_frs_hasEnvironmentalInterest](slots/fio_epa_frs_hasEnvironmentalInterest.md) | <br/>| 1418297 |
| [fio_epa_frs_hasFRSId](slots/fio_epa_frs_hasFRSId.md) | has Identifier in EPA Facility Registry Service<br/>| 529535 |
| [fio_epa_frs_hasMonitoringRecord](slots/fio_epa_frs_hasMonitoringRecord.md) | <br/>No occurrences of this slot in the graph.|  |
| [fio_epa_frs_hasRecord](slots/fio_epa_frs_hasRecord.md) | <br/>| 1475331 |
| [fio_epa_frs_hasSupplementalRecord](slots/fio_epa_frs_hasSupplementalRecord.md) | <br/>| 244147 |
| [fio_epa_frs_ofFacilityType](slots/fio_epa_frs_ofFacilityType.md) | <br/>| 1336346 |
| [fio_epa_frs_ofInterestType](slots/fio_epa_frs_ofInterestType.md) | <br/>| 1321543 |
| [fio_epa_frs_ofPrimaryIndustry](slots/fio_epa_frs_ofPrimaryIndustry.md) | <br/>| 248235 |
| [fio_epa_frs_ofSecondaryIndustry](slots/fio_epa_frs_ofSecondaryIndustry.md) | <br/>| 24317 |
| [fio_epa_frs_partOf](slots/fio_epa_frs_partOf.md) | <br/>| 3 |
| [fio_epa_frs_replacedBy](slots/fio_epa_frs_replacedBy.md) | <br/>| 4 |
| [fio_hasFacility](slots/fio_hasFacility.md) | <br/>No occurrences of this slot in the graph.|  |
| [fio_ofIndustry](slots/fio_ofIndustry.md) | A relation between an entity and the industry it is classified under<br/>| 1815886 |
| [fio_ofYear](slots/fio_ofYear.md) | A relation between an industry code and the schema year it belongs to<br/>| 2129 |
| [fio_ownedBy](slots/fio_ownedBy.md) | <br/>| 1477 |
| [fio_sameCode](slots/fio_sameCode.md) | <br/>No occurrences of this slot in the graph.|  |
| [fio_subcodeOf](slots/fio_subcodeOf.md) | A hierarchical relation between an industry and its parent industry<br/>| 7847 |
| [fio_yearDeprecated](slots/fio_yearDeprecated.md) | A relation between an industry code and the schema year it was deprecated and...<br/>No occurrences of this slot in the graph.|  |
| [owl_imports](slots/owl_imports.md) | <br/>No occurrences of this slot in the graph.|  |
| [rdf__1](slots/rdf__1.md) | <br/>No occurrences of this slot in the graph.|  |
| [rdf_langRange](slots/rdf_langRange.md) | <br/>No occurrences of this slot in the graph.|  |
| [xsd_length](slots/xsd_length.md) | <br/>No occurrences of this slot in the graph.|  |
| [xsd_maxExclusive](slots/xsd_maxExclusive.md) | <br/>No occurrences of this slot in the graph.|  |
| [xsd_maxLength](slots/xsd_maxLength.md) | <br/>No occurrences of this slot in the graph.|  |
| [xsd_minExclusive](slots/xsd_minExclusive.md) | <br/>No occurrences of this slot in the graph.|  |
| [xsd_minLength](slots/xsd_minLength.md) | <br/>No occurrences of this slot in the graph.|  |






## Types

| Type | Description |
| --- | --- |
| [OwlRational](types/OwlRational.md) |  |
| [OwlReal](types/OwlReal.md) |  |
| [XsdAnyURI](types/XsdAnyURI.md) |  |
| [XsdBase64Binary](types/XsdBase64Binary.md) |  |
| [XsdBoolean](types/XsdBoolean.md) |  |
| [XsdByte](types/XsdByte.md) |  |
| [XsdDate](types/XsdDate.md) |  |
| [XsdDateTime](types/XsdDateTime.md) |  |
| [XsdDecimal](types/XsdDecimal.md) |  |
| [XsdDouble](types/XsdDouble.md) |  |
| [XsdFloat](types/XsdFloat.md) |  |
| [XsdHexBinary](types/XsdHexBinary.md) |  |
| [XsdInt](types/XsdInt.md) |  |
| [XsdInteger](types/XsdInteger.md) |  |
| [XsdLanguage](types/XsdLanguage.md) |  |
| [XsdLong](types/XsdLong.md) |  |
| [XsdName](types/XsdName.md) |  |
| [XsdNCName](types/XsdNCName.md) |  |
| [XsdNegativeInteger](types/XsdNegativeInteger.md) |  |
| [XsdNMTOKEN](types/XsdNMTOKEN.md) |  |
| [XsdNonNegativeInteger](types/XsdNonNegativeInteger.md) |  |
| [XsdNonPositiveInteger](types/XsdNonPositiveInteger.md) |  |
| [XsdNormalizedString](types/XsdNormalizedString.md) |  |
| [XsdPositiveInteger](types/XsdPositiveInteger.md) |  |
| [XsdShort](types/XsdShort.md) |  |
| [XsdToken](types/XsdToken.md) |  |
| [XsdUnsignedByte](types/XsdUnsignedByte.md) |  |
| [XsdUnsignedInt](types/XsdUnsignedInt.md) |  |
| [XsdUnsignedLong](types/XsdUnsignedLong.md) |  |
| [XsdUnsignedShort](types/XsdUnsignedShort.md) |  |





## IRI prefixes

* dc: http://purl.org/dc/elements/1.1/
* dcgeoid: https://datacommons.org/browser/geoId/
* dct: http://purl.org/dc/terms/
* fio: http://w3id.org/fio/v1/fio#
* fio-epa-frs: http://w3id.org/fio/v1/epa-frs#
* geo: http://www.opengis.net/ont/geosparql#
* kwgo: http://stko-kwg.geog.ucsb.edu/lod/ontology/
* kwgr: http://stko-kwg.geog.ucsb.edu/lod/resource/
* linkml: https://w3id.org/linkml/
* naics: http://w3id.org/fio/v1/naics#
* okn: https://purl.org/okn/
* okns: https://purl.org/okn/schema/
* owl: http://www.w3.org/2002/07/owl#
* prov: http://www.w3.org/ns/prov#
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* sdos: https://schema.org/
* xsd: http://www.w3.org/2001/XMLSchema#
