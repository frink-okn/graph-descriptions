# climatemodelskg

This ontology defines the entities and relationships for the Knowledge Graph exported from Neo4j.



## Schema Diagram

```mermaid
erDiagram
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
SkosCollection {

}
SkosConcept {

}
SkosConceptScheme {

}
SkosOrderedCollection {

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
HttpTemplekg.orgOntologyExperiment {
    string http___templekg.org_ontology_wikidata_description  
    string http___templekg.org_ontology_wikidata_ids  
    string dct_description  
    string http___templekg.org_ontology_UUID  
    string http___templekg.org_ontology_tier  
    string http___templekg.org_ontology_start_year  
    string http___templekg.org_ontology_end_year  
    string http___templekg.org_ontology_experiment  
    string rdfs_label  
}
HttpTemplekg.orgOntologyGreeting {
    string http___templekg.org_ontology_content  
}
HttpTemplekg.orgOntologyInstrument {
    string http___templekg.org_ontology_wikidata_description  
    string http___templekg.org_ontology_wikidata_ids  
    string dct_description  
    string http___templekg.org_ontology_collapsed_uuids  
    string http___templekg.org_ontology_UUID  
    string rdfs_label  
}
HttpTemplekg.orgOntologyLocation {
    string http___templekg.org_ontology_wikidata_description  
    string http___templekg.org_ontology_wikidata_ids  
    string dct_description  
    string http___templekg.org_ontology_collapsed_uuids  
    string http___templekg.org_ontology_UUID  
    string rdfs_label  
}
HttpTemplekg.orgOntologyModel {
    string http___templekg.org_ontology_wikidata_description  
    string http___templekg.org_ontology_wikidata_ids  
    string dct_description  
    string http___templekg.org_ontology_UUID  
    string rdfs_label  
}
HttpTemplekg.orgOntologyNaturalHazard {
    string http___templekg.org_ontology_wikidata_description  
    string http___templekg.org_ontology_wikidata_ids  
    string dct_description  
    string http___templekg.org_ontology_UUID  
    string rdfs_label  
}
HttpTemplekg.orgOntologyOceanCirculation {
    string http___templekg.org_ontology_wikidata_description  
    string http___templekg.org_ontology_wikidata_ids  
    string dct_description  
    string http___templekg.org_ontology_UUID  
    string rdfs_label  
}
HttpTemplekg.orgOntologyOthers {
    string http___templekg.org_ontology_wikidata_description  
    string http___templekg.org_ontology_wikidata_ids  
    string dct_description  
    string http___templekg.org_ontology_collapsed_uuids  
    string http___templekg.org_ontology_UUID  
    string rdfs_label  
}
HttpTemplekg.orgOntologyPaper {
    string http___templekg.org_ontology_authors  
    string http___templekg.org_ontology_UUID  
    string http___templekg.org_ontology_doi  
    string rdfs_label  
    string http___templekg.org_ontology_pub_date  
}
HttpTemplekg.orgOntologyPlatform {
    string http___templekg.org_ontology_wikidata_description  
    string http___templekg.org_ontology_wikidata_ids  
    string dct_description  
    string http___templekg.org_ontology_collapsed_uuids  
    string http___templekg.org_ontology_UUID  
    string rdfs_label  
}
HttpTemplekg.orgOntologyProvider {
    string http___templekg.org_ontology_wikidata_description  
    string http___templekg.org_ontology_wikidata_ids  
    string dct_description  
    string http___templekg.org_ontology_collapsed_uuids  
    string http___templekg.org_ontology_UUID  
    string rdfs_label  
}
HttpTemplekg.orgOntologyTeleconnection {
    string http___templekg.org_ontology_wikidata_description  
    string http___templekg.org_ontology_wikidata_ids  
    string dct_description  
    string http___templekg.org_ontology_UUID  
    string rdfs_label  
}
HttpTemplekg.orgOntologyVariable {
    string http___templekg.org_ontology_wikidata_description  
    string http___templekg.org_ontology_wikidata_ids  
    string dct_description  
    string http___templekg.org_ontology_collapsed_uuids  
    string http___templekg.org_ontology_UUID  
    string rdfs_label  
}
HttpTemplekg.orgOntologyWeatherEvent {
    string http___templekg.org_ontology_wikidata_description  
    string http___templekg.org_ontology_wikidata_ids  
    string dct_description  
    string http___templekg.org_ontology_collapsed_uuids  
    string http___templekg.org_ontology_UUID  
    string rdfs_label  
}

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
DcamVocabularyEncodingScheme ||--|o RdfsResource : "rdfs_seeAlso"
DcamVocabularyEncodingScheme ||--|o RdfsLiteral : "rdfs_label"
DcamVocabularyEncodingScheme ||--|o RdfsLiteral : "rdfs_comment"
DcamVocabularyEncodingScheme ||--|o RdfsLiteral : "dct_issued"
DcamVocabularyEncodingScheme ||--|o OwlOntology : "rdfs_isDefinedBy"
DcamVocabularyEncodingScheme ||--|o RdfsResource : "rdfs_isDefinedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyExperiment ||--|o SdosProject : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyExperiment ||--|o SdosProject : "http___templekg.org_ontology_HasActivity"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyExperiment ||--|o SdosProject : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o SdosProject : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyExperiment ||--|o SdosProject : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyExperiment ||--|o SdosProject : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_HasAdditionalAllowedModelComponents"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o SdosProject : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o SdosProject : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_HasRequiredModelComponents"
HttpTemplekg.orgOntologyExperiment ||--|o SdosProject : "http___templekg.org_ontology_HasProjectName"
HttpTemplekg.orgOntologyExperiment ||--|o ProvLocation : "prov_atLocation"
HttpTemplekg.orgOntologyExperiment ||--|o SdosProject : "http___templekg.org_ontology_HasParentActivity"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyExperiment ||--|o SdosProject : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyExperiment ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyExperiment ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_HasParentExperiment"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiLocatedOnAstronomicalBody"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiElementSymbol"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiElementSymbol"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiContinent"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyInstrument ||--|o ProvLocation : "prov_atLocation"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiReplaces"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiReplaces"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiReplaces"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMeasures"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiMeasures"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiCreator"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiCreator"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiParticipant"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiParticipant"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiParticipant"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyInstrument ||--|o SdosProject : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyInstrument ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMediaType"
HttpTemplekg.orgOntologyInstrument ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiCategoryContains"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiReplacedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiReplacedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiReplacedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPortOfRegistry"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiLocatedOnAstronomicalBody"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiMemberOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiMemberOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiMemberOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMemberOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiBasinCountry"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiBasinCountry"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiBasinCountry"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiContinent"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyLocation ||--|o ProvLocation : "prov_atLocation"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiReplaces"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiReplaces"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiReplaces"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiParticipant"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiParticipant"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiParticipant"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyLocation ||--|o SdosProject : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyLocation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyLocation ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_HasActivityParticipation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiIsTheStudyOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiIsTheStudyOf"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_WikiIsTheStudyOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_HasLicenseInfo"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_HasModelComponent"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_HasProjectName"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyModel ||--|o ProvLocation : "prov_atLocation"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_HasInstitution"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyModel ||--|o SdosProject : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyModel ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyModel ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyNaturalHazard ||--|o SdosProject : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o SdosProject : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o SdosProject : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o SdosProject : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyNaturalHazard ||--|o SdosProject : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o SdosProject : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o SdosProject : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o ProvLocation : "prov_atLocation"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o SdosProject : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyNaturalHazard ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyNaturalHazard ||--|o SdosProject : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyNaturalHazard ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o SdosProject : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o SdosProject : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o SdosProject : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o SdosProject : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o SdosProject : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o ProvLocation : "prov_atLocation"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOceanCirculation ||--|o SdosProject : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o SdosProject : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOceanCirculation ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOceanCirculation ||--|o SdosProject : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOceanCirculation ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_HasRegion"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiIsTheStudyOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiIsTheStudyOf"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiIsTheStudyOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiReplacedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiReplacedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiReplacedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiName"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHabitat"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHabitat"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiChemicalFormula"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiChemicalFormula"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiMemberOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiMemberOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiMemberOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMemberOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiPdbLigandId"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiPdbLigandId"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiElementSymbol"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiElementSymbol"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiContinent"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_HasProjectName"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyOthers ||--|o ProvLocation : "prov_atLocation"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiAssociatedHazard"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiReplaces"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiReplaces"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiReplaces"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMeasures"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiMeasures"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiBasedOn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiBasedOn"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_HasInstitution"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDerivativeWork"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_HasSourceType"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiParticipant"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiParticipant"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiParticipant"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyOthers ||--|o SdosProject : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyOthers ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMediaType"
HttpTemplekg.orgOntologyOthers ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o SdosProject : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_Mention"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyPaper : "http___templekg.org_ontology_CITED"
HttpTemplekg.orgOntologyPaper ||--|o HttpTemplekg.orgOntologyPaper : "http___templekg.org_ontology_SIM"
HttpTemplekg.orgOntologyPaper ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_MountedOn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiExpressedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiContinent"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyPlatform ||--|o ProvLocation : "prov_atLocation"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDepicts"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiBasedOn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiBasedOn"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyPlatform ||--|o SdosProject : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyPlatform ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyPlatform ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiReplacedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiReplacedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiReplacedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiUses"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasSubsidiary"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasSubsidiary"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasSubsidiary"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiHasSubsidiary"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasSubsidiary"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasSubsidiary"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiOperator"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiMemberOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiMemberOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiMemberOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMemberOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiInfluencedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiBasinCountry"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiBasinCountry"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiBasinCountry"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiContinent"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiAppliesToJurisdiction"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiAppliesToJurisdiction"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyProvider ||--|o ProvLocation : "prov_atLocation"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiReplaces"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiReplaces"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiReplaces"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiCreator"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiCreator"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiBasedOn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiBasedOn"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasUse"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiParticipant"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiParticipant"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiParticipant"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDerivativeWork"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyProvider ||--|o SdosProject : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyProvider ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMediaType"
HttpTemplekg.orgOntologyProvider ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o SdosProject : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o SdosProject : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInonPhysicalFeature"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o SdosProject : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o SdosProject : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyTeleconnection ||--|o SdosProject : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o SdosProject : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o SdosProject : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyTeleconnection ||--|o SdosProject : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyTeleconnection ||--|o ProvLocation : "prov_atLocation"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o SdosProject : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyTeleconnection ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyTeleconnection ||--|o SdosProject : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyTeleconnection ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ProvidedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiNamedAfter"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPartOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiPlaceOfPublication"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiCapital"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiChild"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiMadeFromMaterial"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiStudiedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiContinent"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiCountryOfCitizenship"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_HasProjectName"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiAssociatedHazard"
HttpTemplekg.orgOntologyVariable ||--|o ProvLocation : "prov_atLocation"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiFollowedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiHasPartsOfTheClass"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFollows"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiOppositeOf"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiDifferentFrom"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiFileExtension"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasCause"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyVariable ||--|o SdosProject : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyVariable ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyVariable ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o SdosProject : "http___templekg.org_ontology_WikiInstanceOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o SdosProject : "http___templekg.org_ontology_ComparedTo"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o SdosProject : "http___templekg.org_ontology_WikiSubclassOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o SdosProject : "http___templekg.org_ontology_ValidatedBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o SdosProject : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_UsedIn"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o SdosProject : "http___templekg.org_ontology_TargetsLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o SdosProject : "http___templekg.org_ontology_RunBy"
HttpTemplekg.orgOntologyWeatherEvent ||--|o ProvLocation : "prov_atLocation"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o SdosProject : "http___templekg.org_ontology_ChildOf"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyModel : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyExperiment : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOceanCirculation : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyWeatherEvent ||--|o SdosProject : "http___templekg.org_ontology_Outputs"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyPlatform : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyWeatherEvent : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyTeleconnection : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyVariable : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyProvider : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyWeatherEvent ||--|o SdosProject : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyLocation : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasParts"
HttpTemplekg.orgOntologyWeatherEvent ||--|o RdfsLiteral : "rdfs_label"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyNaturalHazard : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyWeatherEvent ||--|o SdosProject : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyInstrument : "http___templekg.org_ontology_WikiHasEffect"
HttpTemplekg.orgOntologyWeatherEvent ||--|o HttpTemplekg.orgOntologyOthers : "http___templekg.org_ontology_WikiHasEffect"

```



## Imports


* okns:prov
* okns:sdo
* okns:owl-rdf-rdfs
* okns:dc
* linkml:types



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [HttpTemplekg.orgOntologyExperiment](classes/HttpTemplekg.orgOntologyExperiment.md) | None<br/>| 335 | 
| [HttpTemplekg.orgOntologyGreeting](classes/HttpTemplekg.orgOntologyGreeting.md) | None<br/>| 2 | 
| [HttpTemplekg.orgOntologyInstrument](classes/HttpTemplekg.orgOntologyInstrument.md) | None<br/>| 2020 | 
| [HttpTemplekg.orgOntologyLocation](classes/HttpTemplekg.orgOntologyLocation.md) | None<br/>| 624 | 
| [HttpTemplekg.orgOntologyModel](classes/HttpTemplekg.orgOntologyModel.md) | None<br/>| 442 | 
| [HttpTemplekg.orgOntologyNaturalHazard](classes/HttpTemplekg.orgOntologyNaturalHazard.md) | None<br/>| 24 | 
| [HttpTemplekg.orgOntologyOceanCirculation](classes/HttpTemplekg.orgOntologyOceanCirculation.md) | None<br/>| 29 | 
| [HttpTemplekg.orgOntologyOthers](classes/HttpTemplekg.orgOntologyOthers.md) | None<br/>| 3358 | 
| [HttpTemplekg.orgOntologyPaper](classes/HttpTemplekg.orgOntologyPaper.md) | None<br/>| 500 | 
| [HttpTemplekg.orgOntologyPlatform](classes/HttpTemplekg.orgOntologyPlatform.md) | None<br/>| 1214 | 
| [HttpTemplekg.orgOntologyProvider](classes/HttpTemplekg.orgOntologyProvider.md) | None<br/>| 3770 | 
| [HttpTemplekg.orgOntologyTeleconnection](classes/HttpTemplekg.orgOntologyTeleconnection.md) | None<br/>| 27 | 
| [HttpTemplekg.orgOntologyVariable](classes/HttpTemplekg.orgOntologyVariable.md) | None<br/>| 1501 | 
| [HttpTemplekg.orgOntologyWeatherEvent](classes/HttpTemplekg.orgOntologyWeatherEvent.md) | None<br/>| 89 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [http___templekg.org_ontology_authors](slots/http___templekg.org_ontology_authors.md) | <br/>| 486 |
| [http___templekg.org_ontology_ChildOf](slots/http___templekg.org_ontology_ChildOf.md) | <br/>| 46537 |
| [http___templekg.org_ontology_CITED](slots/http___templekg.org_ontology_CITED.md) | <br/>| 117 |
| [http___templekg.org_ontology_collapsed_uuids](slots/http___templekg.org_ontology_collapsed_uuids.md) | <br/>| 607 |
| [http___templekg.org_ontology_ComparedTo](slots/http___templekg.org_ontology_ComparedTo.md) | <br/>| 1267 |
| [http___templekg.org_ontology_content](slots/http___templekg.org_ontology_content.md) | <br/>| 2 |
| [http___templekg.org_ontology_doi](slots/http___templekg.org_ontology_doi.md) | <br/>| 475 |
| [http___templekg.org_ontology_end_year](slots/http___templekg.org_ontology_end_year.md) | <br/>| 322 |
| [http___templekg.org_ontology_experiment](slots/http___templekg.org_ontology_experiment.md) | <br/>| 322 |
| [http___templekg.org_ontology_HasActivity](slots/http___templekg.org_ontology_HasActivity.md) | <br/>| 334 |
| [http___templekg.org_ontology_HasActivityParticipation](slots/http___templekg.org_ontology_HasActivityParticipation.md) | <br/>| 685 |
| [http___templekg.org_ontology_HasAdditionalAllowedModelComponents](slots/http___templekg.org_ontology_HasAdditionalAllowedModelComponents.md) | <br/>| 706 |
| [http___templekg.org_ontology_HasInstitution](slots/http___templekg.org_ontology_HasInstitution.md) | <br/>| 257 |
| [http___templekg.org_ontology_HasLicenseInfo](slots/http___templekg.org_ontology_HasLicenseInfo.md) | <br/>| 131 |
| [http___templekg.org_ontology_HasModelComponent](slots/http___templekg.org_ontology_HasModelComponent.md) | <br/>| 677 |
| [http___templekg.org_ontology_HasParentActivity](slots/http___templekg.org_ontology_HasParentActivity.md) | <br/>| 251 |
| [http___templekg.org_ontology_HasParentExperiment](slots/http___templekg.org_ontology_HasParentExperiment.md) | <br/>| 251 |
| [http___templekg.org_ontology_HasProjectName](slots/http___templekg.org_ontology_HasProjectName.md) | <br/>| 2118 |
| [http___templekg.org_ontology_HasRegion](slots/http___templekg.org_ontology_HasRegion.md) | <br/>| 109 |
| [http___templekg.org_ontology_HasRequiredModelComponents](slots/http___templekg.org_ontology_HasRequiredModelComponents.md) | <br/>| 430 |
| [http___templekg.org_ontology_HasSourceType](slots/http___templekg.org_ontology_HasSourceType.md) | <br/>| 106 |
| [http___templekg.org_ontology_Mention](slots/http___templekg.org_ontology_Mention.md) | <br/>| 22181 |
| [http___templekg.org_ontology_MountedOn](slots/http___templekg.org_ontology_MountedOn.md) | <br/>| 73 |
| [http___templekg.org_ontology_Outputs](slots/http___templekg.org_ontology_Outputs.md) | <br/>| 730 |
| [http___templekg.org_ontology_ProvidedBy](slots/http___templekg.org_ontology_ProvidedBy.md) | <br/>| 508 |
| [http___templekg.org_ontology_pub_date](slots/http___templekg.org_ontology_pub_date.md) | <br/>| 363 |
| [http___templekg.org_ontology_RunBy](slots/http___templekg.org_ontology_RunBy.md) | <br/>| 269 |
| [http___templekg.org_ontology_SIM](slots/http___templekg.org_ontology_SIM.md) | <br/>| 1068 |
| [http___templekg.org_ontology_start_year](slots/http___templekg.org_ontology_start_year.md) | <br/>| 322 |
| [http___templekg.org_ontology_TargetsLocation](slots/http___templekg.org_ontology_TargetsLocation.md) | <br/>| 3246 |
| [http___templekg.org_ontology_test_property](slots/http___templekg.org_ontology_test_property.md) | <br/>| 1 |
| [http___templekg.org_ontology_tier](slots/http___templekg.org_ontology_tier.md) | <br/>| 322 |
| [http___templekg.org_ontology_UsedIn](slots/http___templekg.org_ontology_UsedIn.md) | <br/>| 1137 |
| [http___templekg.org_ontology_UUID](slots/http___templekg.org_ontology_UUID.md) | <br/>| 15877 |
| [http___templekg.org_ontology_ValidatedBy](slots/http___templekg.org_ontology_ValidatedBy.md) | <br/>| 285 |
| [http___templekg.org_ontology_WikiAppliesToJurisdiction](slots/http___templekg.org_ontology_WikiAppliesToJurisdiction.md) | <br/>| 3 |
| [http___templekg.org_ontology_WikiAssociatedHazard](slots/http___templekg.org_ontology_WikiAssociatedHazard.md) | <br/>| 2 |
| [http___templekg.org_ontology_WikiBasedOn](slots/http___templekg.org_ontology_WikiBasedOn.md) | <br/>| 10 |
| [http___templekg.org_ontology_WikiBasinCountry](slots/http___templekg.org_ontology_WikiBasinCountry.md) | <br/>| 204 |
| [http___templekg.org_ontology_WikiCapital](slots/http___templekg.org_ontology_WikiCapital.md) | <br/>| 25 |
| [http___templekg.org_ontology_WikiCategoryContains](slots/http___templekg.org_ontology_WikiCategoryContains.md) | <br/>| 1 |
| [http___templekg.org_ontology_WikiChemicalFormula](slots/http___templekg.org_ontology_WikiChemicalFormula.md) | <br/>| 7 |
| [http___templekg.org_ontology_WikiChild](slots/http___templekg.org_ontology_WikiChild.md) | <br/>| 83 |
| [http___templekg.org_ontology_WikiContinent](slots/http___templekg.org_ontology_WikiContinent.md) | <br/>| 326 |
| [http___templekg.org_ontology_WikiCountryOfCitizenship](slots/http___templekg.org_ontology_WikiCountryOfCitizenship.md) | <br/>| 130 |
| [http___templekg.org_ontology_WikiCreator](slots/http___templekg.org_ontology_WikiCreator.md) | <br/>| 2 |
| [http___templekg.org_ontology_wikidata_description](slots/http___templekg.org_ontology_wikidata_description.md) | <br/>| 3864 |
| [http___templekg.org_ontology_wikidata_ids](slots/http___templekg.org_ontology_wikidata_ids.md) | <br/>| 4018 |
| [http___templekg.org_ontology_WikiDepicts](slots/http___templekg.org_ontology_WikiDepicts.md) | <br/>| 12 |
| [http___templekg.org_ontology_WikiDerivativeWork](slots/http___templekg.org_ontology_WikiDerivativeWork.md) | <br/>| 3 |
| [http___templekg.org_ontology_WikiDesignedBy](slots/http___templekg.org_ontology_WikiDesignedBy.md) | <br/>| 1 |
| [http___templekg.org_ontology_WikiDifferentFrom](slots/http___templekg.org_ontology_WikiDifferentFrom.md) | <br/>| 180 |
| [http___templekg.org_ontology_WikiElementSymbol](slots/http___templekg.org_ontology_WikiElementSymbol.md) | <br/>| 7 |
| [http___templekg.org_ontology_WikiExpressedIn](slots/http___templekg.org_ontology_WikiExpressedIn.md) | <br/>| 1 |
| [http___templekg.org_ontology_WikiFileExtension](slots/http___templekg.org_ontology_WikiFileExtension.md) | <br/>| 12 |
| [http___templekg.org_ontology_WikiFollowedBy](slots/http___templekg.org_ontology_WikiFollowedBy.md) | <br/>| 253 |
| [http___templekg.org_ontology_WikiFollows](slots/http___templekg.org_ontology_WikiFollows.md) | <br/>| 252 |
| [http___templekg.org_ontology_WikiHabitat](slots/http___templekg.org_ontology_WikiHabitat.md) | <br/>| 12 |
| [http___templekg.org_ontology_WikiHasCause](slots/http___templekg.org_ontology_WikiHasCause.md) | <br/>| 54 |
| [http___templekg.org_ontology_WikiHasEffect](slots/http___templekg.org_ontology_WikiHasEffect.md) | <br/>| 46 |
| [http___templekg.org_ontology_WikiHasParts](slots/http___templekg.org_ontology_WikiHasParts.md) | <br/>| 872 |
| [http___templekg.org_ontology_WikiHasPartsOfTheClass](slots/http___templekg.org_ontology_WikiHasPartsOfTheClass.md) | <br/>| 20 |
| [http___templekg.org_ontology_WikiHasSubsidiary](slots/http___templekg.org_ontology_WikiHasSubsidiary.md) | <br/>| 9 |
| [http___templekg.org_ontology_WikiHasUse](slots/http___templekg.org_ontology_WikiHasUse.md) | <br/>| 60 |
| [http___templekg.org_ontology_WikiInfluencedBy](slots/http___templekg.org_ontology_WikiInfluencedBy.md) | <br/>| 13 |
| [http___templekg.org_ontology_WikiInstanceOf](slots/http___templekg.org_ontology_WikiInstanceOf.md) | <br/>| 622 |
| [http___templekg.org_ontology_WikiIsTheStudyOf](slots/http___templekg.org_ontology_WikiIsTheStudyOf.md) | <br/>| 10 |
| [http___templekg.org_ontology_WikiLocatedInonPhysicalFeature](slots/http___templekg.org_ontology_WikiLocatedInonPhysicalFeature.md) | <br/>| 132 |
| [http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater](slots/http___templekg.org_ontology_WikiLocatedInOrNextToBodyOfWater.md) | <br/>| 306 |
| [http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity](slots/http___templekg.org_ontology_WikiLocatedInTheAdministrativeTerritorialEntity.md) | <br/>| 226 |
| [http___templekg.org_ontology_WikiLocatedOnAstronomicalBody](slots/http___templekg.org_ontology_WikiLocatedOnAstronomicalBody.md) | <br/>| 3 |
| [http___templekg.org_ontology_WikiLocation](slots/http___templekg.org_ontology_WikiLocation.md) | <br/>| 27 |
| [http___templekg.org_ontology_WikiMadeFromMaterial](slots/http___templekg.org_ontology_WikiMadeFromMaterial.md) | <br/>| 33 |
| [http___templekg.org_ontology_WikiMeasures](slots/http___templekg.org_ontology_WikiMeasures.md) | <br/>| 6 |
| [http___templekg.org_ontology_WikiMediaType](slots/http___templekg.org_ontology_WikiMediaType.md) | <br/>| 14 |
| [http___templekg.org_ontology_WikiMemberOf](slots/http___templekg.org_ontology_WikiMemberOf.md) | <br/>| 361 |
| [http___templekg.org_ontology_WikiName](slots/http___templekg.org_ontology_WikiName.md) | <br/>| 1 |
| [http___templekg.org_ontology_WikiNamedAfter](slots/http___templekg.org_ontology_WikiNamedAfter.md) | <br/>| 65 |
| [http___templekg.org_ontology_WikiOperator](slots/http___templekg.org_ontology_WikiOperator.md) | <br/>| 77 |
| [http___templekg.org_ontology_WikiOppositeOf](slots/http___templekg.org_ontology_WikiOppositeOf.md) | <br/>| 45 |
| [http___templekg.org_ontology_WikiParticipant](slots/http___templekg.org_ontology_WikiParticipant.md) | <br/>| 35 |
| [http___templekg.org_ontology_WikiPartOf](slots/http___templekg.org_ontology_WikiPartOf.md) | <br/>| 728 |
| [http___templekg.org_ontology_WikiPdbLigandId](slots/http___templekg.org_ontology_WikiPdbLigandId.md) | <br/>| 5 |
| [http___templekg.org_ontology_WikiPlaceOfPublication](slots/http___templekg.org_ontology_WikiPlaceOfPublication.md) | <br/>| 110 |
| [http___templekg.org_ontology_WikiPortOfRegistry](slots/http___templekg.org_ontology_WikiPortOfRegistry.md) | <br/>| 4 |
| [http___templekg.org_ontology_WikiReplacedBy](slots/http___templekg.org_ontology_WikiReplacedBy.md) | <br/>| 4 |
| [http___templekg.org_ontology_WikiReplaces](slots/http___templekg.org_ontology_WikiReplaces.md) | <br/>| 35 |
| [http___templekg.org_ontology_WikiStudiedIn](slots/http___templekg.org_ontology_WikiStudiedIn.md) | <br/>| 43 |
| [http___templekg.org_ontology_WikiSubclassOf](slots/http___templekg.org_ontology_WikiSubclassOf.md) | <br/>| 360 |
| [http___templekg.org_ontology_WikiUses](slots/http___templekg.org_ontology_WikiUses.md) | <br/>| 30 |









## IRI prefixes

* dct: http://purl.org/dc/terms/
* linkml: https://w3id.org/linkml/
* okn: https://purl.org/okn/
* okns: https://purl.org/okn/schema/
* owl: http://www.w3.org/2002/07/owl#
* prov: http://www.w3.org/ns/prov#
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* sdos: https://schema.org/
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
* schema: http://schema.org/
