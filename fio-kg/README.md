# fiokg

The facility registry service ontology developed as part of the AIKnowsPFAS and SAWGraph projects.



## Schema Diagram

```mermaid
erDiagram
DcamVocabularyEncodingScheme {
    date dct_issued  
    string rdfs_label  
    string rdfs_comment  
    uri rdfs_seeAlso  
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
    string rdfs_label  
    string rdfs_comment  
    date dct_issued  
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
    uri rdfs_seeAlso  
    string rdfs_label  
    string rdfs_comment  
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
    string rdfs_label  
    string rdfs_comment  
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
    uri rdfs_seeAlso  
    string rdfs_label  
    string rdfs_comment  
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
    decimal time_weeks  
    decimal time_months  
    decimal time_hours  
    decimal time_years  
    string rdfs_label  
    decimal time_days  
    decimal time_seconds  
    decimal time_minutes  
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
SkosCollection {

}
SkosConcept {

}
SkosConceptScheme {

}
SkosOrderedCollection {

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
    string dct_title  
    string vaem_withAttributionTo  
    uri vaem_latestPublishedVersion  
    uri vaem_usesNonImportedResource  
    uri vaem_turtleFileURL  
    string vaem_owner  
    string vaem_revision  
    uri vaem_rdfxmlFileURL  
    string vaem_intent  
    string vaem_namespacePrefix  
    string rdfs_label  
    string vaem_title  
    string vaem_description  
    uri vaem_previousPublishedVersion  
    uri vaem_logo  
    string vaem_name  
    date dct_modified  
}
VaemGraphRole {
    string rdfs_label  
    string vaem_filePrefix  
    string dct_description  
}
VaemParty {
    string rdfs_label  
    uri vaem_url  
    string vaem_name  
}
VaemViewpoint {

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
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
}
SdosBoatReservation {

}
SdosBoatTerminal {

}
SdosBoatTrip {

}
SdosBodyMeasurementTypeEnumeration {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosBodyOfWater {

}
SdosBone {

}
SdosBook {

}
SdosBookFormatType {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
}
SdosBookSeries {

}
SdosBookStore {

}
SdosBookmarkAction {

}
SdosBoolean {
    string rdfs_comment  
    string rdfs_label  
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
    uri sdos_contributor  
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
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
    uri sdos_contributor  
    string rdfs_comment  
    string rdfs_label  
    uri sdos_sameAs  
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
    uri sdos_contributor  
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
}
SdosDigitalPlatformEnumeration {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    uri sdos_contributor  
    string rdfs_comment  
    string rdfs_label  
}
SdosDrug {

}
SdosDrugClass {

}
SdosDrugCost {

}
SdosDrugCostCategory {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
}
SdosDrugLegalStatus {

}
SdosDrugPregnancyCategory {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
}
SdosDrugPrescriptionStatus {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
}
SdosDrugStrength {

}
SdosDryCleaningOrLaundry {

}
SdosDuration {

}
SdosEUEnergyEfficiencyEnumeration {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosEventReservation {

}
SdosEventSeries {

}
SdosEventStatusType {
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosGamePlayMode {
    string rdfs_comment  
    string rdfs_label  
}
SdosGameServer {

}
SdosGameServerStatus {
    string rdfs_comment  
    string rdfs_label  
}
SdosGardenStore {

}
SdosGasStation {

}
SdosGatedResidenceCommunity {

}
SdosGenderType {
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    uri sdos_source  
    uri sdos_isPartOf  
    string rdfs_comment  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosIncentiveStatus {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosIncentiveType {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosIndividualPhysician {

}
SdosIndividualProduct {

}
SdosInfectiousAgentClass {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
}
SdosItemList {

}
SdosItemListOrderType {
    string rdfs_comment  
    string rdfs_label  
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
    uri sdos_source  
    uri sdos_isPartOf  
    uri sdos_contributor  
    string rdfs_comment  
}
SdosLegalService {

}
SdosLegalValueLevel {
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
    uri sdos_contributor  
    string rdfs_comment  
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
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosMeasurementTypeEnumeration {

}
SdosMediaEnumeration {

}
SdosMediaGallery {

}
SdosMediaManipulationRatingEnumeration {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
}
SdosMedicalEntity {

}
SdosMedicalEnumeration {

}
SdosMedicalEvidenceLevel {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
}
SdosMedicalGuideline {

}
SdosMedicalGuidelineContraindication {

}
SdosMedicalGuidelineRecommendation {

}
SdosMedicalImagingTechnique {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
}
SdosMedicalIndication {

}
SdosMedicalIntangible {

}
SdosMedicalObservationalStudy {

}
SdosMedicalObservationalStudyDesign {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
}
SdosMedicalOrganization {

}
SdosMedicalProcedure {

}
SdosMedicalProcedureType {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
}
SdosMedicalWebPage {

}
SdosMedicineSystem {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    uri sdos_contributor  
    string rdfs_comment  
    string rdfs_label  
}
SdosMusicAlbumReleaseType {
    uri sdos_contributor  
    string rdfs_comment  
    string rdfs_label  
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
    uri sdos_contributor  
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
}
SdosPaymentService {

}
SdosPaymentStatusType {
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
}
SdosPhysicalExam {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosPriceSpecification {

}
SdosPriceTypeEnumeration {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    uri sdos_source  
    uri sdos_isPartOf  
    string rdfs_comment  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
}
SdosResumeAction {

}
SdosReturnAction {

}
SdosReturnFeesEnumeration {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosReturnLabelSourceEnumeration {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosReturnMethodEnumeration {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    uri sdos_contributor  
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosURL {

}
SdosUSNonprofitType {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosWearableSizeGroupEnumeration {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
}
SdosWearableSizeSystemEnumeration {
    string rdfs_comment  
    string rdfs_label  
    uri sdos_source  
    uri sdos_isPartOf  
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
VaemCatalogEntry {
    string rdfs_label  
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
    string voag_pointOfContact  
    string vaem_name  
    uri voag_url  
}
VoagAttributionLogo {
    string voag_width  
    string voag_height  
    string vaem_description  
    string rdfs_label  
    uri voag_image  
    string voag_caption  
}
VoagCatalog {

}
VoagChangeFrequency {
    string rdfs_label  
}
VoagChangeManagementProcess {

}
VoagChangeType {
    string rdfs_label  
}
VoagConcurrenceEvent {

}
VoagConfidentialityLevel {
    string vaem_description  
    string rdfs_label  
    integer dtype_order  
}
VoagCreativeCommonsJurisdiction {

}
VoagCreativeCommonsPermission {
    string vaem_description  
    string rdfs_label  
}
VoagCreativeCommonsProhibition {
    string vaem_description  
    string rdfs_label  
}
VoagCreativeCommonsRequirement {
    uri vaem_url  
    string vaem_description  
    string rdfs_label  
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
}
VoagGovernanceEvent {

}
VoagGovernanceProcess {

}
VoagGovernanceProtocol {

}
VoagGovernanceRole {
    string rdfs_label  
}
VoagGovernedObject {

}
VoagGovernedService {

}
VoagGraph {

}
VoagIcon {
    string voag_width  
    string voag_height  
    string vaem_description  
    string rdfs_label  
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
    string vaem_description  
    string rdfs_label  
}
VoagLicenseModel {
    string rdfs_label  
}
VoagLogo {
    string voag_width  
    string voag_height  
    string vaem_description  
    string rdfs_label  
    uri voag_image  
    string voag_caption  
}
VoagMaturity {
    string rdfs_label  
}
VoagNonConcurrenceEvent {

}
VoagOrganization {

}
VoagOrganizationLogo {
    string voag_width  
    string voag_height  
    string vaem_description  
    string rdfs_label  
    uri voag_image  
    string voag_caption  
}
VoagParty {

}
VoagPedigree {
    string rdfs_label  
}
VoagPerson {

}
VoagPriorityValue {
    string rdfs_label  
}
VoagProcess {

}
VoagProductLogo {
    string voag_width  
    string voag_height  
    string rdfs_label  
    uri voag_image  
    string voag_caption  
    string vaem_description  
}
VoagProvenance {
    string rdfs_label  
}
VoagPublicationStatus {
    string rdfs_label  
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
    string rdfs_label  
    uri qudt_hasDimensionVector  
    uri qudt_hasQuantityKind  
    uri qudt_dbpediaMatch  
    string qudt_iec61360Code  
    decimal qudt_conversionMultiplierSN  
    double qudt_conversionMultiplierSN  
    string dct_description  
    string qudt_symbol  
    string qudt_udunitsCode  
    uri qudt_informativeReference  
    uri qudt_applicableSystem  
    decimal qudt_conversionMultiplier  
    string qudt_uneceCommonCode  
    uri qudt_omUnit  
    uri rdfs_seeAlso  
    uri qudt_isoNormativeReference  
    string vaem_todo  
    qudt_LatexString qudt_latexDefinition  
    uri qudt_siExactMatch  
    qudt_LatexString qudt_expression  
    string qudt_expression  
    string qudt_plainTextDescription  
    double qudt_conversionOffsetSN  
    string rdfs_comment  
    qudt_UCUMcs qudt_ucumCode  
    string qudt_ucumCode  
    uri qudt_derivedUnitOfSystem  
    uri qudt_qkdvNumerator  
    string qudt_siUnitsExpression  
    uri qudt_definedUnitOfSystem  
    decimal qudt_factorUnitScalar  
    uri qudt_derivedCoherentUnitOfSystem  
    decimal qudt_conversionOffset  
    uri qudt_qkdvDenominator  
    qudt_LatexString qudt_latexSymbol  
    string qudt_altSymbol  
    boolean qudt_deprecated  
}
QudtAspect {

}
QudtAspectClass {
    string rdfs_comment  
    string rdfs_label  
}
QudtBaseDimensionMagnitude {

}
QudtBinaryPrefix {
    string rdfs_label  
    string dct_description  
    decimal qudt_prefixMultiplier  
    string qudt_symbol  
    double qudt_prefixMultiplierSN  
    qudt_UCUMcs qudt_ucumCode  
    string qudt_ucumCode  
}
QudtBitEncodingType {
    string rdfs_label  
    integer qudt_bits  
}
QudtBooleanEncodingType {
    string rdfs_label  
    integer qudt_bits  
    integer qudt_bytes  
}
QudtByteEncodingType {
    integer qudt_bytes  
    string rdfs_label  
}
QudtCardinalityType {
    string rdfs_label  
    string dtype_literal  
    string dct_description  
    uri qudt_informativeReference  
}
QudtCharEncodingType {
    integer qudt_bytes  
    string rdfs_label  
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
    uri qudt_dbpediaMatch  
    qudt_LatexString qudt_expression  
    string qudt_expression  
    uri qudt_hasQuantityKind  
    string qudt_iec61360Code  
    string qudt_plainTextDescription  
    string qudt_udunitsCode  
    uri qudt_applicableSystem  
    qudt_UCUMcs qudt_ucumCode  
    string qudt_ucumCode  
    decimal qudt_conversionMultiplier  
    uri qudt_informativeReference  
    string qudt_uneceCommonCode  
    string rdfs_label  
    uri qudt_hasDimensionVector  
    decimal qudt_conversionMultiplierSN  
    double qudt_conversionMultiplierSN  
    string dct_description  
    string qudt_symbol  
    string qudt_altSymbol  
    boolean qudt_deprecated  
    uri qudt_omUnit  
    uri rdfs_seeAlso  
    uri qudt_isoNormativeReference  
    string vaem_todo  
    qudt_LatexString qudt_latexDefinition  
    uri qudt_siExactMatch  
    double qudt_conversionOffsetSN  
    string rdfs_comment  
    uri qudt_derivedUnitOfSystem  
    uri qudt_qkdvNumerator  
    string qudt_siUnitsExpression  
    uri qudt_definedUnitOfSystem  
    decimal qudt_factorUnitScalar  
    uri qudt_derivedCoherentUnitOfSystem  
    decimal qudt_conversionOffset  
    uri qudt_qkdvDenominator  
    qudt_LatexString qudt_latexSymbol  
}
QudtCountingUnit {
    uri qudt_omUnit  
    uri qudt_dbpediaMatch  
    uri qudt_hasQuantityKind  
    string qudt_iec61360Code  
    string qudt_plainTextDescription  
    double qudt_conversionOffsetSN  
    uri qudt_applicableSystem  
    qudt_UCUMcs qudt_ucumCode  
    string qudt_ucumCode  
    decimal qudt_conversionMultiplier  
    decimal qudt_factorUnitScalar  
    uri qudt_informativeReference  
    string qudt_uneceCommonCode  
    string rdfs_label  
    uri qudt_hasDimensionVector  
    decimal qudt_conversionMultiplierSN  
    double qudt_conversionMultiplierSN  
    decimal qudt_conversionOffset  
    string dct_description  
    string qudt_symbol  
    string qudt_udunitsCode  
    uri rdfs_seeAlso  
    uri qudt_isoNormativeReference  
    string vaem_todo  
    qudt_LatexString qudt_latexDefinition  
    uri qudt_siExactMatch  
    qudt_LatexString qudt_expression  
    string qudt_expression  
    string rdfs_comment  
    uri qudt_derivedUnitOfSystem  
    uri qudt_qkdvNumerator  
    string qudt_siUnitsExpression  
    uri qudt_definedUnitOfSystem  
    uri qudt_derivedCoherentUnitOfSystem  
    uri qudt_qkdvDenominator  
    qudt_LatexString qudt_latexSymbol  
    string qudt_altSymbol  
    boolean qudt_deprecated  
}
QudtCurrencyUnit {
    qudt_LatexString qudt_expression  
    string qudt_expression  
    string rdfs_label  
    uri qudt_omUnit  
    integer qudt_currencyExponent  
    uri qudt_hasDimensionVector  
    uri qudt_hasQuantityKind  
    string qudt_currencyNumber  
    uri qudt_dbpediaMatch  
    string qudt_currencyCode  
    qudt_UCUMcs qudt_ucumCode  
    string qudt_ucumCode  
    decimal qudt_conversionMultiplierSN  
    double qudt_conversionMultiplierSN  
    string qudt_symbol  
    string qudt_altSymbol  
    uri qudt_informativeReference  
    decimal qudt_conversionMultiplier  
    string qudt_iec61360Code  
    string dct_description  
    string qudt_udunitsCode  
    uri qudt_applicableSystem  
    string qudt_uneceCommonCode  
    uri rdfs_seeAlso  
    uri qudt_isoNormativeReference  
    string vaem_todo  
    qudt_LatexString qudt_latexDefinition  
    uri qudt_siExactMatch  
    string qudt_plainTextDescription  
    double qudt_conversionOffsetSN  
    string rdfs_comment  
    uri qudt_derivedUnitOfSystem  
    uri qudt_qkdvNumerator  
    string qudt_siUnitsExpression  
    uri qudt_definedUnitOfSystem  
    decimal qudt_factorUnitScalar  
    uri qudt_derivedCoherentUnitOfSystem  
    decimal qudt_conversionOffset  
    uri qudt_qkdvDenominator  
    qudt_LatexString qudt_latexSymbol  
    boolean qudt_deprecated  
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
}
QudtDecimalPrefix {
    string rdfs_label  
    uri qudt_dbpediaMatch  
    string dct_description  
    decimal qudt_prefixMultiplier  
    double qudt_prefixMultiplierSN  
    uri qudt_siExactMatch  
    string qudt_symbol  
    uri qudt_informativeReference  
    qudt_UCUMcs qudt_ucumCode  
    string qudt_ucumCode  
}
QudtDerivedUnit {
    uri qudt_omUnit  
    uri rdfs_seeAlso  
    uri qudt_isoNormativeReference  
    uri qudt_dbpediaMatch  
    qudt_LatexString qudt_latexDefinition  
    uri qudt_siExactMatch  
    qudt_LatexString qudt_expression  
    string qudt_expression  
    uri qudt_hasQuantityKind  
    string qudt_iec61360Code  
    string qudt_plainTextDescription  
    double qudt_conversionOffsetSN  
    string qudt_udunitsCode  
    string rdfs_comment  
    uri qudt_applicableSystem  
    qudt_UCUMcs qudt_ucumCode  
    string qudt_ucumCode  
    decimal qudt_conversionMultiplier  
    uri qudt_derivedUnitOfSystem  
    uri qudt_qkdvNumerator  
    string qudt_siUnitsExpression  
    uri qudt_definedUnitOfSystem  
    rdf_HTML qudt_guidance  
    decimal qudt_factorUnitScalar  
    uri qudt_informativeReference  
    string qudt_uneceCommonCode  
    string rdfs_label  
    uri qudt_hasDimensionVector  
    decimal qudt_conversionMultiplierSN  
    double qudt_conversionMultiplierSN  
    uri qudt_derivedCoherentUnitOfSystem  
    decimal qudt_conversionOffset  
    uri qudt_qkdvDenominator  
    string dct_description  
    string vaem_comment  
    string qudt_symbol  
    qudt_LatexString qudt_latexSymbol  
    string qudt_altSymbol  
    boolean qudt_deprecated  
    string vaem_todo  
}
QudtDimensionlessUnit {
    string rdfs_label  
    uri qudt_hasDimensionVector  
    uri qudt_hasQuantityKind  
    uri qudt_dbpediaMatch  
    string qudt_iec61360Code  
    decimal qudt_conversionMultiplierSN  
    double qudt_conversionMultiplierSN  
    string dct_description  
    string qudt_symbol  
    string qudt_udunitsCode  
    uri qudt_informativeReference  
    uri qudt_applicableSystem  
    decimal qudt_conversionMultiplier  
    string qudt_uneceCommonCode  
    uri qudt_omUnit  
    uri rdfs_seeAlso  
    uri qudt_isoNormativeReference  
    string vaem_todo  
    qudt_LatexString qudt_latexDefinition  
    uri qudt_siExactMatch  
    qudt_LatexString qudt_expression  
    string qudt_expression  
    string qudt_plainTextDescription  
    double qudt_conversionOffsetSN  
    string rdfs_comment  
    qudt_UCUMcs qudt_ucumCode  
    string qudt_ucumCode  
    uri qudt_derivedUnitOfSystem  
    uri qudt_qkdvNumerator  
    string qudt_siUnitsExpression  
    uri qudt_definedUnitOfSystem  
    decimal qudt_factorUnitScalar  
    uri qudt_derivedCoherentUnitOfSystem  
    decimal qudt_conversionOffset  
    uri qudt_qkdvDenominator  
    qudt_LatexString qudt_latexSymbol  
    string qudt_altSymbol  
    boolean qudt_deprecated  
}
QudtDiscipline {

}
QudtEncoding {

}
QudtEndianType {
    string rdfs_label  
    string dtype_literal  
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
    string rdfs_label  
}
QudtIntegerEncodingType {
    integer qudt_bytes  
    string rdfs_label  
}
QudtIntervalScale {

}
QudtLogarithmicUnit {
    string rdfs_label  
    uri qudt_hasDimensionVector  
    uri qudt_hasQuantityKind  
    uri qudt_dbpediaMatch  
    string qudt_iec61360Code  
    qudt_UCUMcs qudt_ucumCode  
    string qudt_ucumCode  
    decimal qudt_conversionMultiplierSN  
    double qudt_conversionMultiplierSN  
    string dct_description  
    uri qudt_siExactMatch  
    string qudt_symbol  
    uri qudt_informativeReference  
    uri qudt_applicableSystem  
    decimal qudt_conversionMultiplier  
    string qudt_uneceCommonCode  
    string qudt_udunitsCode  
    uri qudt_omUnit  
    uri rdfs_seeAlso  
    uri qudt_isoNormativeReference  
    string vaem_todo  
    qudt_LatexString qudt_latexDefinition  
    qudt_LatexString qudt_expression  
    string qudt_expression  
    string qudt_plainTextDescription  
    double qudt_conversionOffsetSN  
    string rdfs_comment  
    uri qudt_derivedUnitOfSystem  
    uri qudt_qkdvNumerator  
    string qudt_siUnitsExpression  
    uri qudt_definedUnitOfSystem  
    decimal qudt_factorUnitScalar  
    uri qudt_derivedCoherentUnitOfSystem  
    decimal qudt_conversionOffset  
    uri qudt_qkdvDenominator  
    qudt_LatexString qudt_latexSymbol  
    string qudt_altSymbol  
    boolean qudt_deprecated  
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
}
QudtOrdinalScale {

}
QudtOrganization {

}
QudtPhysicalConstant {

}
QudtPlaneAngleUnit {
    string rdfs_label  
    uri qudt_hasDimensionVector  
    uri qudt_hasQuantityKind  
    uri qudt_dbpediaMatch  
    string qudt_iec61360Code  
    decimal qudt_conversionMultiplierSN  
    double qudt_conversionMultiplierSN  
    string dct_description  
    string qudt_symbol  
    string qudt_udunitsCode  
    uri qudt_informativeReference  
    uri qudt_applicableSystem  
    decimal qudt_conversionMultiplier  
    string qudt_uneceCommonCode  
    uri qudt_omUnit  
    uri rdfs_seeAlso  
    uri qudt_isoNormativeReference  
    string vaem_todo  
    qudt_LatexString qudt_latexDefinition  
    uri qudt_siExactMatch  
    qudt_LatexString qudt_expression  
    string qudt_expression  
    string qudt_plainTextDescription  
    double qudt_conversionOffsetSN  
    string rdfs_comment  
    qudt_UCUMcs qudt_ucumCode  
    string qudt_ucumCode  
    uri qudt_derivedUnitOfSystem  
    uri qudt_qkdvNumerator  
    string qudt_siUnitsExpression  
    uri qudt_definedUnitOfSystem  
    decimal qudt_factorUnitScalar  
    uri qudt_derivedCoherentUnitOfSystem  
    decimal qudt_conversionOffset  
    uri qudt_qkdvDenominator  
    qudt_LatexString qudt_latexSymbol  
    string qudt_altSymbol  
    boolean qudt_deprecated  
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
}
QudtSolidAngleUnit {
    string rdfs_label  
    uri qudt_hasDimensionVector  
    uri qudt_hasQuantityKind  
    uri qudt_dbpediaMatch  
    string qudt_iec61360Code  
    decimal qudt_conversionMultiplierSN  
    double qudt_conversionMultiplierSN  
    string dct_description  
    string qudt_symbol  
    string qudt_udunitsCode  
    uri qudt_informativeReference  
    uri qudt_applicableSystem  
    decimal qudt_conversionMultiplier  
    string qudt_uneceCommonCode  
    uri qudt_omUnit  
    uri rdfs_seeAlso  
    uri qudt_isoNormativeReference  
    string vaem_todo  
    qudt_LatexString qudt_latexDefinition  
    uri qudt_siExactMatch  
    qudt_LatexString qudt_expression  
    string qudt_expression  
    string qudt_plainTextDescription  
    double qudt_conversionOffsetSN  
    string rdfs_comment  
    qudt_UCUMcs qudt_ucumCode  
    string qudt_ucumCode  
    uri qudt_derivedUnitOfSystem  
    uri qudt_qkdvNumerator  
    string qudt_siUnitsExpression  
    uri qudt_definedUnitOfSystem  
    decimal qudt_factorUnitScalar  
    uri qudt_derivedCoherentUnitOfSystem  
    decimal qudt_conversionOffset  
    uri qudt_qkdvDenominator  
    qudt_LatexString qudt_latexSymbol  
    string qudt_altSymbol  
    boolean qudt_deprecated  
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
    uri qudt_omUnit  
    uri rdfs_seeAlso  
    uri qudt_isoNormativeReference  
    string vaem_todo  
    uri qudt_dbpediaMatch  
    qudt_LatexString qudt_latexDefinition  
    uri qudt_siExactMatch  
    qudt_LatexString qudt_expression  
    string qudt_expression  
    uri qudt_hasQuantityKind  
    string qudt_iec61360Code  
    string qudt_plainTextDescription  
    double qudt_conversionOffsetSN  
    string qudt_udunitsCode  
    string rdfs_comment  
    uri qudt_applicableSystem  
    qudt_UCUMcs qudt_ucumCode  
    string qudt_ucumCode  
    decimal qudt_conversionMultiplier  
    uri qudt_derivedUnitOfSystem  
    uri qudt_qkdvNumerator  
    string qudt_siUnitsExpression  
    uri qudt_definedUnitOfSystem  
    decimal qudt_factorUnitScalar  
    uri qudt_informativeReference  
    string qudt_uneceCommonCode  
    string rdfs_label  
    uri qudt_hasDimensionVector  
    decimal qudt_conversionMultiplierSN  
    double qudt_conversionMultiplierSN  
    uri qudt_derivedCoherentUnitOfSystem  
    decimal qudt_conversionOffset  
    uri qudt_qkdvDenominator  
    string dct_description  
    string qudt_symbol  
    qudt_LatexString qudt_latexSymbol  
    string qudt_altSymbol  
    boolean qudt_deprecated  
}
QudtUserQuantityKind {

}
QudtVerifiable {

}
XsdString {

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
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
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
    string rdfs_comment  
    string rdfs_label  
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
B1d70f10e8204578c89c5f678467193ea {
    string dct_description  
    string rdfs_label  
}
B3a5aa76705834f507db6d3c7d90d63b8 {
    string dct_description  
    datetime prov_startedAtTime  
    string rdfs_label  
}
B43f2153f8fa51cc860da104aa4b996c7 {
    string rdfs_label  
}
B51b8d66516b28a1c54f8d745ede947b9 {
    string dct_description  
    datetime prov_startedAtTime  
    string rdfs_label  
}
B5debef6666ba27aa225105865fd22d6c {
    string dct_description  
    datetime prov_endedAtTime  
    datetime prov_startedAtTime  
    string rdfs_label  
}
B671ac9cd6796151f919e5affbe3cc5f9 {
    string dct_description  
    datetime prov_endedAtTime  
    datetime prov_startedAtTime  
    string rdfs_label  
}
B707e8df015ee2912f85cf2fec8dc4718 {
    string rdfs_label  
}
B912c2f2722265f457d11b52388b1def0 {
    string dct_description  
    datetime prov_endedAtTime  
    datetime prov_startedAtTime  
    string rdfs_label  
}
B9968aab18e1237453b5cbb15df1c74b9 {
    string dct_description  
    datetime prov_endedAtTime  
    datetime prov_startedAtTime  
    string rdfs_label  
}
B9d449a3503d8291d6acf9c5a93d5670f {

}
Ba0ffbf1a7a548fac1e61d3eceada03dd {
    string dct_description  
    datetime prov_endedAtTime  
    datetime prov_startedAtTime  
    string rdfs_label  
}
Bd6303cfa8c86e776b8e226496bd342eb {

}
Bdbdbfbd4ef20ffc37226553d96831226 {
    string dct_description  
    datetime prov_endedAtTime  
    datetime prov_startedAtTime  
    string rdfs_label  
}
Be082c2fc952b5eb7e355834fa6af4865 {
    string dct_description  
    datetime prov_endedAtTime  
    datetime prov_startedAtTime  
    string rdfs_label  
}
Be0e551f6155d8e99ee967119022af97d {
    string rdfs_label  
}
Bea9d030ae5649d7f06d536c2a467e56f {
    string dct_description  
    datetime prov_endedAtTime  
    datetime prov_startedAtTime  
    string rdfs_label  
}
Bf0c649c8d760a3559d3d5e5b1f68a59f {
    string dct_description  
    datetime prov_endedAtTime  
    datetime prov_startedAtTime  
    string rdfs_label  
}
Bf906a89c08306329b89456f1d101a6bf {
    string dct_description  
    datetime prov_startedAtTime  
    string rdfs_label  
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
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsAnimalOperation {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsAssistanceSupportProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsChemicalReleaseProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsChemicalStorageProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsChemicalstorageprograms {

}
Fio-epa-frsCoastalOceanProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsComplianceInterest {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsComplianceRecord {

}
Fio-epa-frsComplianceSystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsDrinkingWaterProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsEPA-PFAS-Facility {
    date dct_modified  
    string dct_title  
    string rdfs_label  
    string fio_epa_frs_hasFRSId  
}
Fio-epa-frsEcologyOperation {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsElectronicPermitSystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsEnforcementActivity {

}
Fio-epa-frsEnforcementInterest {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsEnforcementSystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsEnforcementTrackingRecord {

}
Fio-epa-frsEnvironmentalInterestByProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsEnvironmentalInterestByRecordType {

}
Fio-epa-frsEnvironmentalInterestType {
    string rdfs_label  
}
Fio-epa-frsFRS-Facility {
    string dct_description  
    datetime prov_endedAtTime  
    date dct_modified  
    string dct_title  
    string rdfs_label  
    datetime prov_startedAtTime  
    string fio_epa_frs_hasFRSId  
}
Fio-epa-frsFacilitySiteIdentification {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsFacilityType {
    string rdfs_label  
}
Fio-epa-frsGrantSystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsGroundWaterProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsHazardousWasteProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsHealthSafetyProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsLegacySystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsLegalEnforcementActivities {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsMonitoringRecord {

}
Fio-epa-frsPermitInterest {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsPermitRecord {

}
Fio-epa-frsPermitSystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsPesticidesProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsProgramInformationSystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsProjectRecord {

}
Fio-epa-frsProjectSystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsRadiationProtectionProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsRecord {

}
Fio-epa-frsRegistrationRecord {

}
Fio-epa-frsRegistryInterest {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsRegistrySystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsRemediationRedevelopmentProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsReportingInterest {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsReportingRecord {

}
Fio-epa-frsReportingSystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsRiskInterest {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsRiskPlanRecord {

}
Fio-epa-frsSiteInterest {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsSiteRecord {

}
Fio-epa-frsSiteSystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsSolidWasteProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsStateSystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsStateTrackingRecord {

}
Fio-epa-frsStationSystem {

}
Fio-epa-frsSupplementalRecord {
    string dct_description  
    datetime prov_endedAtTime  
    datetime prov_startedAtTime  
    string rdfs_label  
}
Fio-epa-frsTribalSystem {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsTribalTrackingRecord {

}
Fio-epa-frsUndergroundStorageTankProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsWasteWaterProgram {
    string dct_description  
    string rdfs_label  
}
Fio-epa-frsWaterResourcesProgram {
    string dct_description  
    string rdfs_label  
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
    date fio_ofYear  
    string rdfs_label  
}
NaicsNAICS-IndustryGroup {
    date fio_ofYear  
    string rdfs_label  
}
NaicsNAICS-IndustrySector {
    date fio_ofYear  
    string rdfs_label  
}
NaicsNAICS-IndustrySubsector {
    date fio_ofYear  
    string rdfs_label  
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

DcamVocabularyEncodingScheme ||--|o RdfsLiteral : "dct_issued"
DcamVocabularyEncodingScheme ||--|o RdfsLiteral : "rdfs_label"
DcamVocabularyEncodingScheme ||--|o RdfsLiteral : "rdfs_comment"
DcamVocabularyEncodingScheme ||--|o RdfsResource : "rdfs_seeAlso"
DcamVocabularyEncodingScheme ||--|o OwlOntology : "rdfs_isDefinedBy"
DcamVocabularyEncodingScheme ||--|o RdfsResource : "rdfs_isDefinedBy"
DctAgentClass ||--|o RdfsLiteral : "rdfs_label"
DctAgentClass ||--|o RdfsLiteral : "rdfs_comment"
DctAgentClass ||--|o RdfsLiteral : "dct_issued"
DctAgentClass ||--|o OwlOntology : "rdfs_isDefinedBy"
DctAgentClass ||--|o RdfsResource : "rdfs_isDefinedBy"
OwlDataRange ||--|o OwlOntology : "rdfs_isDefinedBy"
OwlDataRange ||--|o RdfsResource : "rdfs_isDefinedBy"
OwlDataRange ||--|o RdfsClass : "rdfs_subClassOf"
OwlDataRange ||--|o RdfsResource : "rdfs_seeAlso"
OwlDataRange ||--|o RdfsLiteral : "rdfs_label"
OwlDataRange ||--|o RdfsLiteral : "rdfs_comment"
RdfList ||--|o RdfsLiteral : "rdfs_label"
RdfList ||--|o RdfsLiteral : "rdfs_comment"
RdfList ||--|o OwlOntology : "rdfs_isDefinedBy"
RdfList ||--|o RdfsResource : "rdfs_isDefinedBy"
RdfsDatatype ||--|o OwlOntology : "rdfs_isDefinedBy"
RdfsDatatype ||--|o RdfsResource : "rdfs_isDefinedBy"
RdfsDatatype ||--|o RdfsClass : "rdfs_subClassOf"
RdfsDatatype ||--|o RdfsResource : "rdfs_seeAlso"
RdfsDatatype ||--|o RdfsLiteral : "rdfs_label"
RdfsDatatype ||--|o RdfsLiteral : "rdfs_comment"
TimeDayOfWeek ||--|o RdfsLiteral : "rdfs_label"
TimeTemporalUnit ||--|o RdfsLiteral : "rdfs_label"
VaemGraphMetaData ||--|o VaemGraphRole : "vaem_hasGraphRole"
VaemGraphMetaData ||--|o VaemParty : "vaem_hasOwner"
VaemGraphMetaData ||--|o RdfsLiteral : "dct_title"
VaemGraphMetaData ||--|o OwlAnnotationProperty : "vaem_usesNonImportedResource"
VaemGraphMetaData ||--|o RdfsResource : "vaem_usesNonImportedResource"
VaemGraphMetaData ||--|o RdfsLiteral : "dct_created"
VaemGraphMetaData ||--|o VaemParty : "vaem_hasSteward"
VaemGraphMetaData ||--|o RdfsLiteral : "rdfs_label"
VaemGraphMetaData ||--|o OwlOntology : "rdfs_isDefinedBy"
VaemGraphMetaData ||--|o RdfsResource : "rdfs_isDefinedBy"
VaemGraphMetaData ||--|o RdfsLiteral : "dct_modified"
VaemGraphRole ||--|o RdfsLiteral : "rdfs_label"
VaemGraphRole ||--|o OwlOntology : "rdfs_isDefinedBy"
VaemGraphRole ||--|o RdfsResource : "rdfs_isDefinedBy"
VaemParty ||--|o RdfsLiteral : "rdfs_label"
VaemParty ||--|o OwlOntology : "rdfs_isDefinedBy"
VaemParty ||--|o RdfsResource : "rdfs_isDefinedBy"
SdosActionStatusType ||--|o RdfsLiteral : "rdfs_comment"
SdosActionStatusType ||--|o RdfsLiteral : "rdfs_label"
SdosAdultOrientedEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosAdultOrientedEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosAdultOrientedEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosAdultOrientedEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosBoardingPolicyType ||--|o RdfsLiteral : "rdfs_comment"
SdosBoardingPolicyType ||--|o RdfsLiteral : "rdfs_label"
SdosBodyMeasurementTypeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosBodyMeasurementTypeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosBodyMeasurementTypeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosBodyMeasurementTypeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosBookFormatType ||--|o RdfsLiteral : "rdfs_comment"
SdosBookFormatType ||--|o RdfsLiteral : "rdfs_label"
SdosBookFormatType ||--|o SdosURL : "sdos_isPartOf"
SdosBookFormatType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosBoolean ||--|o RdfsLiteral : "rdfs_comment"
SdosBoolean ||--|o RdfsLiteral : "rdfs_label"
SdosCarUsageType ||--|o SdosOrganization : "sdos_contributor"
SdosCarUsageType ||--|o SdosPerson : "sdos_contributor"
SdosCarUsageType ||--|o RdfsLiteral : "rdfs_comment"
SdosCarUsageType ||--|o RdfsLiteral : "rdfs_label"
SdosCarUsageType ||--|o SdosURL : "sdos_isPartOf"
SdosCarUsageType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosCertificationStatusEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosCertificationStatusEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosCertificationStatusEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosCertificationStatusEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosContactPointOption ||--|o RdfsLiteral : "rdfs_comment"
SdosContactPointOption ||--|o RdfsLiteral : "rdfs_label"
SdosDataType ||--|o RdfsLiteral : "rdfs_comment"
SdosDataType ||--|o RdfsLiteral : "rdfs_label"
SdosDayOfWeek ||--|o SdosOrganization : "sdos_contributor"
SdosDayOfWeek ||--|o SdosPerson : "sdos_contributor"
SdosDayOfWeek ||--|o RdfsLiteral : "rdfs_comment"
SdosDayOfWeek ||--|o RdfsLiteral : "rdfs_label"
SdosDayOfWeek ||--|o SdosURL : "sdos_sameAs"
SdosDeliveryMethod ||--|o SdosOrganization : "sdos_contributor"
SdosDeliveryMethod ||--|o SdosPerson : "sdos_contributor"
SdosDeliveryMethod ||--|o RdfsLiteral : "rdfs_comment"
SdosDeliveryMethod ||--|o RdfsLiteral : "rdfs_label"
SdosDigitalDocumentPermissionType ||--|o RdfsLiteral : "rdfs_comment"
SdosDigitalDocumentPermissionType ||--|o RdfsLiteral : "rdfs_label"
SdosDigitalPlatformEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosDigitalPlatformEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosDigitalPlatformEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosDigitalPlatformEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosDriveWheelConfigurationValue ||--|o SdosOrganization : "sdos_contributor"
SdosDriveWheelConfigurationValue ||--|o SdosPerson : "sdos_contributor"
SdosDriveWheelConfigurationValue ||--|o RdfsLiteral : "rdfs_comment"
SdosDriveWheelConfigurationValue ||--|o RdfsLiteral : "rdfs_label"
SdosDrugCostCategory ||--|o RdfsLiteral : "rdfs_comment"
SdosDrugCostCategory ||--|o RdfsLiteral : "rdfs_label"
SdosDrugCostCategory ||--|o SdosURL : "sdos_isPartOf"
SdosDrugCostCategory ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosDrugPregnancyCategory ||--|o RdfsLiteral : "rdfs_comment"
SdosDrugPregnancyCategory ||--|o RdfsLiteral : "rdfs_label"
SdosDrugPregnancyCategory ||--|o SdosURL : "sdos_isPartOf"
SdosDrugPregnancyCategory ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosDrugPrescriptionStatus ||--|o RdfsLiteral : "rdfs_comment"
SdosDrugPrescriptionStatus ||--|o RdfsLiteral : "rdfs_label"
SdosDrugPrescriptionStatus ||--|o SdosURL : "sdos_isPartOf"
SdosDrugPrescriptionStatus ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosEUEnergyEfficiencyEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosEUEnergyEfficiencyEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosEUEnergyEfficiencyEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosEUEnergyEfficiencyEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosEnergyStarEnergyEfficiencyEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosEnergyStarEnergyEfficiencyEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosEnergyStarEnergyEfficiencyEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosEnergyStarEnergyEfficiencyEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosEventAttendanceModeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosEventAttendanceModeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosEventAttendanceModeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosEventAttendanceModeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosEventStatusType ||--|o RdfsLiteral : "rdfs_comment"
SdosEventStatusType ||--|o RdfsLiteral : "rdfs_label"
SdosFulfillmentTypeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosFulfillmentTypeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosFulfillmentTypeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosFulfillmentTypeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosGameAvailabilityEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosGameAvailabilityEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosGameAvailabilityEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosGameAvailabilityEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosGamePlayMode ||--|o RdfsLiteral : "rdfs_comment"
SdosGamePlayMode ||--|o RdfsLiteral : "rdfs_label"
SdosGameServerStatus ||--|o RdfsLiteral : "rdfs_comment"
SdosGameServerStatus ||--|o RdfsLiteral : "rdfs_label"
SdosGenderType ||--|o RdfsLiteral : "rdfs_comment"
SdosGenderType ||--|o RdfsLiteral : "rdfs_label"
SdosGovernmentBenefitsType ||--|o RdfsLiteral : "rdfs_comment"
SdosGovernmentBenefitsType ||--|o RdfsLiteral : "rdfs_label"
SdosGovernmentBenefitsType ||--|o SdosURL : "sdos_isPartOf"
SdosGovernmentBenefitsType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosHealthAspectEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosHealthAspectEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosHealthAspectEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosHealthAspectEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosIPTCDigitalSourceEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosIPTCDigitalSourceEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosIPTCDigitalSourceEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosIPTCDigitalSourceEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosIncentiveQualifiedExpenseType ||--|o RdfsLiteral : "rdfs_comment"
SdosIncentiveQualifiedExpenseType ||--|o RdfsLiteral : "rdfs_label"
SdosIncentiveQualifiedExpenseType ||--|o SdosURL : "sdos_isPartOf"
SdosIncentiveQualifiedExpenseType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosIncentiveStatus ||--|o RdfsLiteral : "rdfs_comment"
SdosIncentiveStatus ||--|o RdfsLiteral : "rdfs_label"
SdosIncentiveStatus ||--|o SdosURL : "sdos_isPartOf"
SdosIncentiveStatus ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosIncentiveType ||--|o RdfsLiteral : "rdfs_comment"
SdosIncentiveType ||--|o RdfsLiteral : "rdfs_label"
SdosIncentiveType ||--|o SdosURL : "sdos_isPartOf"
SdosIncentiveType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosInfectiousAgentClass ||--|o RdfsLiteral : "rdfs_comment"
SdosInfectiousAgentClass ||--|o RdfsLiteral : "rdfs_label"
SdosInfectiousAgentClass ||--|o SdosURL : "sdos_isPartOf"
SdosInfectiousAgentClass ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosItemAvailability ||--|o RdfsLiteral : "rdfs_comment"
SdosItemAvailability ||--|o RdfsLiteral : "rdfs_label"
SdosItemListOrderType ||--|o RdfsLiteral : "rdfs_comment"
SdosItemListOrderType ||--|o RdfsLiteral : "rdfs_label"
SdosLegalForceStatus ||--|o RdfsLiteral : "rdfs_label"
SdosLegalForceStatus ||--|o SdosURL : "sdos_isPartOf"
SdosLegalForceStatus ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosLegalForceStatus ||--|o SdosOrganization : "sdos_contributor"
SdosLegalForceStatus ||--|o SdosPerson : "sdos_contributor"
SdosLegalForceStatus ||--|o RdfsLiteral : "rdfs_comment"
SdosLegalValueLevel ||--|o RdfsLiteral : "rdfs_label"
SdosLegalValueLevel ||--|o SdosURL : "sdos_isPartOf"
SdosLegalValueLevel ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosLegalValueLevel ||--|o SdosOrganization : "sdos_contributor"
SdosLegalValueLevel ||--|o SdosPerson : "sdos_contributor"
SdosLegalValueLevel ||--|o RdfsLiteral : "rdfs_comment"
SdosMapCategoryType ||--|o RdfsLiteral : "rdfs_comment"
SdosMapCategoryType ||--|o RdfsLiteral : "rdfs_label"
SdosMeasurementMethodEnum ||--|o RdfsLiteral : "rdfs_comment"
SdosMeasurementMethodEnum ||--|o RdfsLiteral : "rdfs_label"
SdosMeasurementMethodEnum ||--|o SdosURL : "sdos_isPartOf"
SdosMeasurementMethodEnum ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMediaManipulationRatingEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosMediaManipulationRatingEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosMediaManipulationRatingEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosMediaManipulationRatingEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalAudienceType ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalAudienceType ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalAudienceType ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalAudienceType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalDevicePurpose ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalDevicePurpose ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalDevicePurpose ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalDevicePurpose ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalEvidenceLevel ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalEvidenceLevel ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalEvidenceLevel ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalEvidenceLevel ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalImagingTechnique ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalImagingTechnique ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalImagingTechnique ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalImagingTechnique ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalObservationalStudyDesign ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalObservationalStudyDesign ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalObservationalStudyDesign ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalObservationalStudyDesign ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalProcedureType ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalProcedureType ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalProcedureType ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalProcedureType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalSpecialty ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalSpecialty ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalSpecialty ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalSpecialty ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalSpecialty ||--|o SdosMerchantReturnEnumeration : "sdos_supersededBy"
SdosMedicalSpecialty ||--|o SdosEnumeration : "sdos_supersededBy"
SdosMedicalSpecialty ||--|o SdosProperty : "sdos_supersededBy"
SdosMedicalSpecialty ||--|o SdosMedicalSpecialty : "sdos_supersededBy"
SdosMedicalSpecialty ||--|o SdosClass : "sdos_supersededBy"
SdosMedicalSpecialty ||--|o RdfsClass : "rdfs_subClassOf"
SdosMedicalStudyStatus ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalStudyStatus ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalStudyStatus ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalStudyStatus ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicalTrialDesign ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicalTrialDesign ||--|o RdfsLiteral : "rdfs_label"
SdosMedicalTrialDesign ||--|o SdosURL : "sdos_isPartOf"
SdosMedicalTrialDesign ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMedicineSystem ||--|o RdfsLiteral : "rdfs_comment"
SdosMedicineSystem ||--|o RdfsLiteral : "rdfs_label"
SdosMedicineSystem ||--|o SdosURL : "sdos_isPartOf"
SdosMedicineSystem ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMerchantReturnEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosMerchantReturnEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosMerchantReturnEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosMerchantReturnEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosMusicAlbumProductionType ||--|o SdosOrganization : "sdos_contributor"
SdosMusicAlbumProductionType ||--|o SdosPerson : "sdos_contributor"
SdosMusicAlbumProductionType ||--|o RdfsLiteral : "rdfs_comment"
SdosMusicAlbumProductionType ||--|o RdfsLiteral : "rdfs_label"
SdosMusicAlbumReleaseType ||--|o SdosOrganization : "sdos_contributor"
SdosMusicAlbumReleaseType ||--|o SdosPerson : "sdos_contributor"
SdosMusicAlbumReleaseType ||--|o RdfsLiteral : "rdfs_comment"
SdosMusicAlbumReleaseType ||--|o RdfsLiteral : "rdfs_label"
SdosMusicReleaseFormatType ||--|o SdosOrganization : "sdos_contributor"
SdosMusicReleaseFormatType ||--|o SdosPerson : "sdos_contributor"
SdosMusicReleaseFormatType ||--|o RdfsLiteral : "rdfs_comment"
SdosMusicReleaseFormatType ||--|o RdfsLiteral : "rdfs_label"
SdosNLNonprofitType ||--|o RdfsLiteral : "rdfs_comment"
SdosNLNonprofitType ||--|o RdfsLiteral : "rdfs_label"
SdosNLNonprofitType ||--|o SdosURL : "sdos_isPartOf"
SdosNLNonprofitType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosOfferItemCondition ||--|o RdfsLiteral : "rdfs_comment"
SdosOfferItemCondition ||--|o RdfsLiteral : "rdfs_label"
SdosOrderStatus ||--|o RdfsLiteral : "rdfs_comment"
SdosOrderStatus ||--|o RdfsLiteral : "rdfs_label"
SdosPaymentMethodType ||--|o RdfsLiteral : "rdfs_comment"
SdosPaymentMethodType ||--|o RdfsLiteral : "rdfs_label"
SdosPaymentStatusType ||--|o RdfsLiteral : "rdfs_comment"
SdosPaymentStatusType ||--|o RdfsLiteral : "rdfs_label"
SdosPhysicalActivityCategory ||--|o RdfsLiteral : "rdfs_comment"
SdosPhysicalActivityCategory ||--|o RdfsLiteral : "rdfs_label"
SdosPhysicalActivityCategory ||--|o SdosURL : "sdos_isPartOf"
SdosPhysicalActivityCategory ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosPhysicalExam ||--|o RdfsLiteral : "rdfs_comment"
SdosPhysicalExam ||--|o RdfsLiteral : "rdfs_label"
SdosPhysicalExam ||--|o SdosURL : "sdos_isPartOf"
SdosPhysicalExam ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosPriceComponentTypeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosPriceComponentTypeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosPriceComponentTypeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosPriceComponentTypeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosPriceTypeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosPriceTypeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosPriceTypeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosPriceTypeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosProductReturnEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosProductReturnEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosProductReturnEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosProductReturnEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosProductReturnEnumeration ||--|o SdosMerchantReturnEnumeration : "sdos_supersededBy"
SdosProductReturnEnumeration ||--|o SdosEnumeration : "sdos_supersededBy"
SdosProductReturnEnumeration ||--|o SdosProperty : "sdos_supersededBy"
SdosProductReturnEnumeration ||--|o SdosMedicalSpecialty : "sdos_supersededBy"
SdosProductReturnEnumeration ||--|o SdosClass : "sdos_supersededBy"
SdosPurchaseType ||--|o RdfsLiteral : "rdfs_comment"
SdosPurchaseType ||--|o RdfsLiteral : "rdfs_label"
SdosPurchaseType ||--|o SdosURL : "sdos_isPartOf"
SdosPurchaseType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosRefundTypeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosRefundTypeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosRefundTypeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosRefundTypeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosReservationStatusType ||--|o RdfsLiteral : "rdfs_comment"
SdosReservationStatusType ||--|o RdfsLiteral : "rdfs_label"
SdosRestrictedDiet ||--|o RdfsLiteral : "rdfs_comment"
SdosRestrictedDiet ||--|o RdfsLiteral : "rdfs_label"
SdosReturnFeesEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosReturnFeesEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosReturnFeesEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosReturnFeesEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosReturnLabelSourceEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosReturnLabelSourceEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosReturnLabelSourceEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosReturnLabelSourceEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosReturnMethodEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosReturnMethodEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosReturnMethodEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosReturnMethodEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosRsvpResponseType ||--|o RdfsLiteral : "rdfs_comment"
SdosRsvpResponseType ||--|o RdfsLiteral : "rdfs_label"
SdosSizeSystemEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosSizeSystemEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosSizeSystemEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosSizeSystemEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosSteeringPositionValue ||--|o SdosOrganization : "sdos_contributor"
SdosSteeringPositionValue ||--|o SdosPerson : "sdos_contributor"
SdosSteeringPositionValue ||--|o RdfsLiteral : "rdfs_comment"
SdosSteeringPositionValue ||--|o RdfsLiteral : "rdfs_label"
SdosTierBenefitEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosTierBenefitEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosTierBenefitEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosTierBenefitEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosUKNonprofitType ||--|o RdfsLiteral : "rdfs_comment"
SdosUKNonprofitType ||--|o RdfsLiteral : "rdfs_label"
SdosUKNonprofitType ||--|o SdosURL : "sdos_isPartOf"
SdosUKNonprofitType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosUSNonprofitType ||--|o RdfsLiteral : "rdfs_comment"
SdosUSNonprofitType ||--|o RdfsLiteral : "rdfs_label"
SdosUSNonprofitType ||--|o SdosURL : "sdos_isPartOf"
SdosUSNonprofitType ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosWearableMeasurementTypeEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosWearableMeasurementTypeEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosWearableMeasurementTypeEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosWearableMeasurementTypeEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosWearableSizeGroupEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosWearableSizeGroupEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosWearableSizeGroupEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosWearableSizeGroupEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
SdosWearableSizeSystemEnumeration ||--|o RdfsLiteral : "rdfs_comment"
SdosWearableSizeSystemEnumeration ||--|o RdfsLiteral : "rdfs_label"
SdosWearableSizeSystemEnumeration ||--|o SdosURL : "sdos_isPartOf"
SdosWearableSizeSystemEnumeration ||--|o SdosCreativeWork : "sdos_isPartOf"
AdmsSemanticAssetDistribution ||--|o SkosConcept : "adms_status"
RdfDatatypeProperty ||--|o RdfsClass : "rdfs_domain"
RdfDatatypeProperty ||--|o RdfsLiteral : "rdfs_comment"
RdfDatatypeProperty ||--|o RdfsLiteral : "rdfs_label"
VaemCatalogEntry ||--|o OwlOntology : "rdfs_isDefinedBy"
VaemCatalogEntry ||--|o RdfsResource : "rdfs_isDefinedBy"
VaemCatalogEntry ||--|o RdfsLiteral : "rdfs_label"
VoagAttribution ||--|o RdfsLiteral : "rdfs_label"
VoagAttribution ||--|o VoagLogo : "voag_hasLogo"
VoagAttribution ||--|o VoagAttributionLogo : "voag_hasLogo"
VoagAttribution ||--|o VoagOrganizationLogo : "voag_hasLogo"
VoagAttribution ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagAttribution ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagAttributionLogo ||--|o RdfsLiteral : "rdfs_label"
VoagAttributionLogo ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagAttributionLogo ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagChangeFrequency ||--|o XsdAnySimpleType : "dtype_value"
VoagChangeFrequency ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagChangeFrequency ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagChangeFrequency ||--|o RdfsLiteral : "rdfs_label"
VoagChangeType ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagChangeType ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagChangeType ||--|o RdfsLiteral : "rdfs_label"
VoagConfidentialityLevel ||--|o RdfsLiteral : "rdfs_label"
VoagConfidentialityLevel ||--|o XsdAnySimpleType : "dtype_code"
VoagConfidentialityLevel ||--|o XsdAnySimpleType : "dtype_value"
VoagConfidentialityLevel ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagConfidentialityLevel ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagCreativeCommonsPermission ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagCreativeCommonsPermission ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagCreativeCommonsPermission ||--|o RdfsLiteral : "rdfs_label"
VoagCreativeCommonsProhibition ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagCreativeCommonsProhibition ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagCreativeCommonsProhibition ||--|o RdfsLiteral : "rdfs_label"
VoagCreativeCommonsRequirement ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagCreativeCommonsRequirement ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagCreativeCommonsRequirement ||--|o RdfsLiteral : "rdfs_label"
VoagGovernance ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagGovernance ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagGovernance ||--|o RdfsLiteral : "rdfs_label"
VoagGovernanceRole ||--|o XsdAnySimpleType : "dtype_value"
VoagGovernanceRole ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagGovernanceRole ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagGovernanceRole ||--|o RdfsLiteral : "rdfs_label"
VoagIcon ||--|o RdfsLiteral : "rdfs_label"
VoagIcon ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagIcon ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagIssueStatus ||--|o XsdAnySimpleType : "dtype_value"
VoagIssueStatus ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagIssueStatus ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagIssueStatus ||--|o RdfsLiteral : "rdfs_label"
VoagLicenseModel ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagLicenseModel ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagLicenseModel ||--|o RdfsLiteral : "rdfs_label"
VoagLogo ||--|o RdfsLiteral : "rdfs_label"
VoagLogo ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagLogo ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagMaturity ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagMaturity ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagMaturity ||--|o RdfsLiteral : "rdfs_label"
VoagOrganizationLogo ||--|o RdfsLiteral : "rdfs_label"
VoagOrganizationLogo ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagOrganizationLogo ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagPedigree ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagPedigree ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagPedigree ||--|o RdfsLiteral : "rdfs_label"
VoagPriorityValue ||--|o XsdAnySimpleType : "dtype_value"
VoagPriorityValue ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagPriorityValue ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagPriorityValue ||--|o RdfsLiteral : "rdfs_label"
VoagProductLogo ||--|o RdfsLiteral : "rdfs_label"
VoagProductLogo ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagProductLogo ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagProvenance ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagProvenance ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagProvenance ||--|o RdfsLiteral : "rdfs_label"
VoagPublicationStatus ||--|o XsdAnySimpleType : "dtype_value"
VoagPublicationStatus ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagPublicationStatus ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagPublicationStatus ||--|o RdfsLiteral : "rdfs_label"
VoagSchemaGraph ||--|o OwlOntology : "rdfs_isDefinedBy"
VoagSchemaGraph ||--|o RdfsResource : "rdfs_isDefinedBy"
VoagSchemaGraph ||--|o RdfsLiteral : "rdfs_label"
QudtAngleUnit ||--|o RdfsLiteral : "rdfs_label"
QudtAngleUnit ||--|o QudtQuantityKindDimensionVector : "qudt_hasDimensionVector"
QudtAngleUnit ||--|o QudtQuantityKind : "qudt_hasQuantityKind"
QudtAngleUnit ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtAngleUnit ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtAngleUnit ||--|o RdfsResource : "rdfs_seeAlso"
QudtAngleUnit ||--|o QudtDerivedUnit : "qudt_scalingOf"
QudtAngleUnit ||--|o QudtUnit : "qudt_scalingOf"
QudtAngleUnit ||--|o QudtCountingUnit : "qudt_scalingOf"
QudtAngleUnit ||--|o QudtCurrencyUnit : "qudt_scalingOf"
QudtAngleUnit ||--|o QudtBinaryPrefix : "qudt_prefix"
QudtAngleUnit ||--|o QudtPrefix : "qudt_prefix"
QudtAngleUnit ||--|o QudtDecimalPrefix : "qudt_prefix"
QudtAngleUnit ||--|o RdfsLiteral : "rdfs_comment"
QudtAngleUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvNumerator"
QudtAngleUnit ||--|o QudtDecimalPrefix : "qudt_exactMatch"
QudtAngleUnit ||--|o QudtUnit : "qudt_exactMatch"
QudtAngleUnit ||--|o QudtContextualUnit : "qudt_exactMatch"
QudtAngleUnit ||--|o QudtDerivedUnit : "qudt_exactMatch"
QudtAngleUnit ||--|o QudtCountingUnit : "qudt_exactMatch"
QudtAngleUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvDenominator"
QudtAngleUnit ||--|o ProvEntity : "prov_wasDerivedFrom"
QudtAspectClass ||--|o RdfsLiteral : "rdfs_comment"
QudtAspectClass ||--|o RdfsLiteral : "rdfs_label"
QudtAspectClass ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtAspectClass ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtAspectClass ||--|o RdfsClass : "rdfs_subClassOf"
QudtBinaryPrefix ||--|o RdfsLiteral : "rdfs_label"
QudtBinaryPrefix ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtBinaryPrefix ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtBitEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtBitEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtBitEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtBooleanEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtBooleanEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtBooleanEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtByteEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtByteEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtByteEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtCardinalityType ||--|o RdfsLiteral : "rdfs_label"
QudtCardinalityType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtCardinalityType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtCharEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtCharEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtCharEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtContextualUnit ||--|o QudtDerivedUnit : "qudt_scalingOf"
QudtContextualUnit ||--|o QudtUnit : "qudt_scalingOf"
QudtContextualUnit ||--|o QudtCountingUnit : "qudt_scalingOf"
QudtContextualUnit ||--|o QudtCurrencyUnit : "qudt_scalingOf"
QudtContextualUnit ||--|o QudtQuantityKind : "qudt_hasQuantityKind"
QudtContextualUnit ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtContextualUnit ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtContextualUnit ||--|o RdfsLiteral : "rdfs_label"
QudtContextualUnit ||--|o QudtDecimalPrefix : "qudt_exactMatch"
QudtContextualUnit ||--|o QudtUnit : "qudt_exactMatch"
QudtContextualUnit ||--|o QudtContextualUnit : "qudt_exactMatch"
QudtContextualUnit ||--|o QudtDerivedUnit : "qudt_exactMatch"
QudtContextualUnit ||--|o QudtCountingUnit : "qudt_exactMatch"
QudtContextualUnit ||--|o QudtQuantityKindDimensionVector : "qudt_hasDimensionVector"
QudtContextualUnit ||--|o RdfsResource : "rdfs_seeAlso"
QudtContextualUnit ||--|o QudtBinaryPrefix : "qudt_prefix"
QudtContextualUnit ||--|o QudtPrefix : "qudt_prefix"
QudtContextualUnit ||--|o QudtDecimalPrefix : "qudt_prefix"
QudtContextualUnit ||--|o RdfsLiteral : "rdfs_comment"
QudtContextualUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvNumerator"
QudtContextualUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvDenominator"
QudtContextualUnit ||--|o ProvEntity : "prov_wasDerivedFrom"
QudtCountingUnit ||--|o QudtDerivedUnit : "qudt_scalingOf"
QudtCountingUnit ||--|o QudtUnit : "qudt_scalingOf"
QudtCountingUnit ||--|o QudtCountingUnit : "qudt_scalingOf"
QudtCountingUnit ||--|o QudtCurrencyUnit : "qudt_scalingOf"
QudtCountingUnit ||--|o QudtBinaryPrefix : "qudt_prefix"
QudtCountingUnit ||--|o QudtPrefix : "qudt_prefix"
QudtCountingUnit ||--|o QudtDecimalPrefix : "qudt_prefix"
QudtCountingUnit ||--|o QudtQuantityKind : "qudt_hasQuantityKind"
QudtCountingUnit ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtCountingUnit ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtCountingUnit ||--|o RdfsLiteral : "rdfs_label"
QudtCountingUnit ||--|o QudtDecimalPrefix : "qudt_exactMatch"
QudtCountingUnit ||--|o QudtUnit : "qudt_exactMatch"
QudtCountingUnit ||--|o QudtContextualUnit : "qudt_exactMatch"
QudtCountingUnit ||--|o QudtDerivedUnit : "qudt_exactMatch"
QudtCountingUnit ||--|o QudtCountingUnit : "qudt_exactMatch"
QudtCountingUnit ||--|o QudtQuantityKindDimensionVector : "qudt_hasDimensionVector"
QudtCountingUnit ||--|o RdfsResource : "rdfs_seeAlso"
QudtCountingUnit ||--|o RdfsLiteral : "rdfs_comment"
QudtCountingUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvNumerator"
QudtCountingUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvDenominator"
QudtCountingUnit ||--|o ProvEntity : "prov_wasDerivedFrom"
QudtCurrencyUnit ||--|o RdfsLiteral : "rdfs_label"
QudtCurrencyUnit ||--|o QudtQuantityKindDimensionVector : "qudt_hasDimensionVector"
QudtCurrencyUnit ||--|o QudtQuantityKind : "qudt_hasQuantityKind"
QudtCurrencyUnit ||--|o QudtBinaryPrefix : "qudt_prefix"
QudtCurrencyUnit ||--|o QudtPrefix : "qudt_prefix"
QudtCurrencyUnit ||--|o QudtDecimalPrefix : "qudt_prefix"
QudtCurrencyUnit ||--|o QudtDerivedUnit : "qudt_scalingOf"
QudtCurrencyUnit ||--|o QudtUnit : "qudt_scalingOf"
QudtCurrencyUnit ||--|o QudtCountingUnit : "qudt_scalingOf"
QudtCurrencyUnit ||--|o QudtCurrencyUnit : "qudt_scalingOf"
QudtCurrencyUnit ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtCurrencyUnit ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtCurrencyUnit ||--|o RdfsResource : "rdfs_seeAlso"
QudtCurrencyUnit ||--|o RdfsLiteral : "rdfs_comment"
QudtCurrencyUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvNumerator"
QudtCurrencyUnit ||--|o QudtDecimalPrefix : "qudt_exactMatch"
QudtCurrencyUnit ||--|o QudtUnit : "qudt_exactMatch"
QudtCurrencyUnit ||--|o QudtContextualUnit : "qudt_exactMatch"
QudtCurrencyUnit ||--|o QudtDerivedUnit : "qudt_exactMatch"
QudtCurrencyUnit ||--|o QudtCountingUnit : "qudt_exactMatch"
QudtCurrencyUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvDenominator"
QudtCurrencyUnit ||--|o ProvEntity : "prov_wasDerivedFrom"
QudtDateTimeStringEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtDateTimeStringEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtDateTimeStringEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtDecimalPrefix ||--|o RdfsLiteral : "rdfs_label"
QudtDecimalPrefix ||--|o QudtDecimalPrefix : "qudt_exactMatch"
QudtDecimalPrefix ||--|o QudtUnit : "qudt_exactMatch"
QudtDecimalPrefix ||--|o QudtContextualUnit : "qudt_exactMatch"
QudtDecimalPrefix ||--|o QudtDerivedUnit : "qudt_exactMatch"
QudtDecimalPrefix ||--|o QudtCountingUnit : "qudt_exactMatch"
QudtDecimalPrefix ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtDecimalPrefix ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtDerivedUnit ||--|o RdfsResource : "rdfs_seeAlso"
QudtDerivedUnit ||--|o QudtDerivedUnit : "qudt_scalingOf"
QudtDerivedUnit ||--|o QudtUnit : "qudt_scalingOf"
QudtDerivedUnit ||--|o QudtCountingUnit : "qudt_scalingOf"
QudtDerivedUnit ||--|o QudtCurrencyUnit : "qudt_scalingOf"
QudtDerivedUnit ||--|o QudtBinaryPrefix : "qudt_prefix"
QudtDerivedUnit ||--|o QudtPrefix : "qudt_prefix"
QudtDerivedUnit ||--|o QudtDecimalPrefix : "qudt_prefix"
QudtDerivedUnit ||--|o QudtQuantityKind : "qudt_hasQuantityKind"
QudtDerivedUnit ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtDerivedUnit ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtDerivedUnit ||--|o RdfsLiteral : "rdfs_comment"
QudtDerivedUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvNumerator"
QudtDerivedUnit ||--|o RdfsLiteral : "rdfs_label"
QudtDerivedUnit ||--|o QudtDecimalPrefix : "qudt_exactMatch"
QudtDerivedUnit ||--|o QudtUnit : "qudt_exactMatch"
QudtDerivedUnit ||--|o QudtContextualUnit : "qudt_exactMatch"
QudtDerivedUnit ||--|o QudtDerivedUnit : "qudt_exactMatch"
QudtDerivedUnit ||--|o QudtCountingUnit : "qudt_exactMatch"
QudtDerivedUnit ||--|o QudtQuantityKindDimensionVector : "qudt_hasDimensionVector"
QudtDerivedUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvDenominator"
QudtDerivedUnit ||--|o ProvEntity : "prov_wasDerivedFrom"
QudtDimensionlessUnit ||--|o RdfsLiteral : "rdfs_label"
QudtDimensionlessUnit ||--|o QudtQuantityKindDimensionVector : "qudt_hasDimensionVector"
QudtDimensionlessUnit ||--|o QudtQuantityKind : "qudt_hasQuantityKind"
QudtDimensionlessUnit ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtDimensionlessUnit ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtDimensionlessUnit ||--|o RdfsResource : "rdfs_seeAlso"
QudtDimensionlessUnit ||--|o QudtDerivedUnit : "qudt_scalingOf"
QudtDimensionlessUnit ||--|o QudtUnit : "qudt_scalingOf"
QudtDimensionlessUnit ||--|o QudtCountingUnit : "qudt_scalingOf"
QudtDimensionlessUnit ||--|o QudtCurrencyUnit : "qudt_scalingOf"
QudtDimensionlessUnit ||--|o QudtBinaryPrefix : "qudt_prefix"
QudtDimensionlessUnit ||--|o QudtPrefix : "qudt_prefix"
QudtDimensionlessUnit ||--|o QudtDecimalPrefix : "qudt_prefix"
QudtDimensionlessUnit ||--|o RdfsLiteral : "rdfs_comment"
QudtDimensionlessUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvNumerator"
QudtDimensionlessUnit ||--|o QudtDecimalPrefix : "qudt_exactMatch"
QudtDimensionlessUnit ||--|o QudtUnit : "qudt_exactMatch"
QudtDimensionlessUnit ||--|o QudtContextualUnit : "qudt_exactMatch"
QudtDimensionlessUnit ||--|o QudtDerivedUnit : "qudt_exactMatch"
QudtDimensionlessUnit ||--|o QudtCountingUnit : "qudt_exactMatch"
QudtDimensionlessUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvDenominator"
QudtDimensionlessUnit ||--|o ProvEntity : "prov_wasDerivedFrom"
QudtEndianType ||--|o RdfsLiteral : "rdfs_label"
QudtEndianType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtEndianType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtFloatingPointEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtFloatingPointEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtFloatingPointEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtIntegerEncodingType ||--|o RdfsLiteral : "rdfs_label"
QudtIntegerEncodingType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtIntegerEncodingType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtLogarithmicUnit ||--|o RdfsLiteral : "rdfs_label"
QudtLogarithmicUnit ||--|o QudtQuantityKindDimensionVector : "qudt_hasDimensionVector"
QudtLogarithmicUnit ||--|o QudtQuantityKind : "qudt_hasQuantityKind"
QudtLogarithmicUnit ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtLogarithmicUnit ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtLogarithmicUnit ||--|o RdfsResource : "rdfs_seeAlso"
QudtLogarithmicUnit ||--|o QudtDerivedUnit : "qudt_scalingOf"
QudtLogarithmicUnit ||--|o QudtUnit : "qudt_scalingOf"
QudtLogarithmicUnit ||--|o QudtCountingUnit : "qudt_scalingOf"
QudtLogarithmicUnit ||--|o QudtCurrencyUnit : "qudt_scalingOf"
QudtLogarithmicUnit ||--|o QudtBinaryPrefix : "qudt_prefix"
QudtLogarithmicUnit ||--|o QudtPrefix : "qudt_prefix"
QudtLogarithmicUnit ||--|o QudtDecimalPrefix : "qudt_prefix"
QudtLogarithmicUnit ||--|o RdfsLiteral : "rdfs_comment"
QudtLogarithmicUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvNumerator"
QudtLogarithmicUnit ||--|o QudtDecimalPrefix : "qudt_exactMatch"
QudtLogarithmicUnit ||--|o QudtUnit : "qudt_exactMatch"
QudtLogarithmicUnit ||--|o QudtContextualUnit : "qudt_exactMatch"
QudtLogarithmicUnit ||--|o QudtDerivedUnit : "qudt_exactMatch"
QudtLogarithmicUnit ||--|o QudtCountingUnit : "qudt_exactMatch"
QudtLogarithmicUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvDenominator"
QudtLogarithmicUnit ||--|o ProvEntity : "prov_wasDerivedFrom"
QudtOrderedType ||--|o RdfsLiteral : "rdfs_label"
QudtOrderedType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtOrderedType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtPlaneAngleUnit ||--|o RdfsLiteral : "rdfs_label"
QudtPlaneAngleUnit ||--|o QudtQuantityKindDimensionVector : "qudt_hasDimensionVector"
QudtPlaneAngleUnit ||--|o QudtQuantityKind : "qudt_hasQuantityKind"
QudtPlaneAngleUnit ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtPlaneAngleUnit ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtPlaneAngleUnit ||--|o RdfsResource : "rdfs_seeAlso"
QudtPlaneAngleUnit ||--|o QudtDerivedUnit : "qudt_scalingOf"
QudtPlaneAngleUnit ||--|o QudtUnit : "qudt_scalingOf"
QudtPlaneAngleUnit ||--|o QudtCountingUnit : "qudt_scalingOf"
QudtPlaneAngleUnit ||--|o QudtCurrencyUnit : "qudt_scalingOf"
QudtPlaneAngleUnit ||--|o QudtBinaryPrefix : "qudt_prefix"
QudtPlaneAngleUnit ||--|o QudtPrefix : "qudt_prefix"
QudtPlaneAngleUnit ||--|o QudtDecimalPrefix : "qudt_prefix"
QudtPlaneAngleUnit ||--|o RdfsLiteral : "rdfs_comment"
QudtPlaneAngleUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvNumerator"
QudtPlaneAngleUnit ||--|o QudtDecimalPrefix : "qudt_exactMatch"
QudtPlaneAngleUnit ||--|o QudtUnit : "qudt_exactMatch"
QudtPlaneAngleUnit ||--|o QudtContextualUnit : "qudt_exactMatch"
QudtPlaneAngleUnit ||--|o QudtDerivedUnit : "qudt_exactMatch"
QudtPlaneAngleUnit ||--|o QudtCountingUnit : "qudt_exactMatch"
QudtPlaneAngleUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvDenominator"
QudtPlaneAngleUnit ||--|o ProvEntity : "prov_wasDerivedFrom"
QudtSignednessType ||--|o RdfsLiteral : "rdfs_label"
QudtSignednessType ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtSignednessType ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtSolidAngleUnit ||--|o RdfsLiteral : "rdfs_label"
QudtSolidAngleUnit ||--|o QudtQuantityKindDimensionVector : "qudt_hasDimensionVector"
QudtSolidAngleUnit ||--|o QudtQuantityKind : "qudt_hasQuantityKind"
QudtSolidAngleUnit ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtSolidAngleUnit ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtSolidAngleUnit ||--|o RdfsResource : "rdfs_seeAlso"
QudtSolidAngleUnit ||--|o QudtDerivedUnit : "qudt_scalingOf"
QudtSolidAngleUnit ||--|o QudtUnit : "qudt_scalingOf"
QudtSolidAngleUnit ||--|o QudtCountingUnit : "qudt_scalingOf"
QudtSolidAngleUnit ||--|o QudtCurrencyUnit : "qudt_scalingOf"
QudtSolidAngleUnit ||--|o QudtBinaryPrefix : "qudt_prefix"
QudtSolidAngleUnit ||--|o QudtPrefix : "qudt_prefix"
QudtSolidAngleUnit ||--|o QudtDecimalPrefix : "qudt_prefix"
QudtSolidAngleUnit ||--|o RdfsLiteral : "rdfs_comment"
QudtSolidAngleUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvNumerator"
QudtSolidAngleUnit ||--|o QudtDecimalPrefix : "qudt_exactMatch"
QudtSolidAngleUnit ||--|o QudtUnit : "qudt_exactMatch"
QudtSolidAngleUnit ||--|o QudtContextualUnit : "qudt_exactMatch"
QudtSolidAngleUnit ||--|o QudtDerivedUnit : "qudt_exactMatch"
QudtSolidAngleUnit ||--|o QudtCountingUnit : "qudt_exactMatch"
QudtSolidAngleUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvDenominator"
QudtSolidAngleUnit ||--|o ProvEntity : "prov_wasDerivedFrom"
QudtUnit ||--|o RdfsResource : "rdfs_seeAlso"
QudtUnit ||--|o QudtDerivedUnit : "qudt_scalingOf"
QudtUnit ||--|o QudtUnit : "qudt_scalingOf"
QudtUnit ||--|o QudtCountingUnit : "qudt_scalingOf"
QudtUnit ||--|o QudtCurrencyUnit : "qudt_scalingOf"
QudtUnit ||--|o QudtBinaryPrefix : "qudt_prefix"
QudtUnit ||--|o QudtPrefix : "qudt_prefix"
QudtUnit ||--|o QudtDecimalPrefix : "qudt_prefix"
QudtUnit ||--|o QudtQuantityKind : "qudt_hasQuantityKind"
QudtUnit ||--|o OwlOntology : "rdfs_isDefinedBy"
QudtUnit ||--|o RdfsResource : "rdfs_isDefinedBy"
QudtUnit ||--|o RdfsLiteral : "rdfs_comment"
QudtUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvNumerator"
QudtUnit ||--|o RdfsLiteral : "rdfs_label"
QudtUnit ||--|o QudtDecimalPrefix : "qudt_exactMatch"
QudtUnit ||--|o QudtUnit : "qudt_exactMatch"
QudtUnit ||--|o QudtContextualUnit : "qudt_exactMatch"
QudtUnit ||--|o QudtDerivedUnit : "qudt_exactMatch"
QudtUnit ||--|o QudtCountingUnit : "qudt_exactMatch"
QudtUnit ||--|o QudtQuantityKindDimensionVector : "qudt_hasDimensionVector"
QudtUnit ||--|o QudtQuantityKindDimensionVector : "qudt_qkdvDenominator"
QudtUnit ||--|o ProvEntity : "prov_wasDerivedFrom"
KwgoAirPollutant ||--|o RdfsLiteral : "rdfs_label"
KwgoBlueskyWildfireObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoCensusObservableProperty ||--|o RdfsLiteral : "rdfs_comment"
KwgoCensusObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoCensusObservableProperty ||--|o OwlOntology : "rdfs_isDefinedBy"
KwgoCensusObservableProperty ||--|o RdfsResource : "rdfs_isDefinedBy"
KwgoClimateObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoCroplandObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoDroughtIntensity ||--|o RdfsLiteral : "rdfs_label"
KwgoFireCause ||--|o RdfsLiteral : "rdfs_label"
KwgoHelipadAvailability ||--|o RdfsLiteral : "rdfs_label"
KwgoHospitalStatus ||--|o RdfsLiteral : "rdfs_label"
KwgoHospitalType ||--|o RdfsLiteral : "rdfs_label"
KwgoImpactObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoLSADArea ||--|o RdfsLiteral : "rdfs_comment"
KwgoLSADArea ||--|o RdfsLiteral : "rdfs_label"
KwgoMTBSFireObservableProperty ||--|o RdfsLiteral : "rdfs_comment"
KwgoMTBSFireObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoMagnitudeObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoNIFCFireObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoPublicHealthObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoRoadType ||--|o RdfsLiteral : "rdfs_label"
KwgoSmokePlumeObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoSoilMapUnitObservableProperty ||--|o RdfsLiteral : "rdfs_comment"
KwgoSoilMapUnitObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoStormTrackObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoStormTrackletObservableProperty ||--|o RdfsLiteral : "rdfs_label"
KwgoVulnerabilityObservableProperty ||--|o RdfsLiteral : "rdfs_label"
B1d70f10e8204578c89c5f678467193ea ||--|o RdfsLiteral : "dct_identifier"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o OwlThing : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
B1d70f10e8204578c89c5f678467193ea ||--|o OwlThing : "owl_sameAs"
B1d70f10e8204578c89c5f678467193ea ||--|o RdfsLiteral : "rdfs_label"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o OwlThing : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
B1d70f10e8204578c89c5f678467193ea ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o RdfsLiteral : "dct_identifier"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o OwlThing : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o OwlThing : "owl_sameAs"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o RdfsLiteral : "rdfs_label"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
B3a5aa76705834f507db6d3c7d90d63b8 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o OwlThing : "fio_ofIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o FioIndustry : "fio_ofIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o OwlNamedIndividual : "fio_ofIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o RdfsLiteral : "dct_identifier"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o OwlThing : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o OwlThing : "owl_sameAs"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o RdfsLiteral : "rdfs_label"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o OwlThing : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
B43f2153f8fa51cc860da104aa4b996c7 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o OwlThing : "fio_ofIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o FioIndustry : "fio_ofIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o OwlNamedIndividual : "fio_ofIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o RdfsLiteral : "dct_identifier"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o OwlThing : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o OwlThing : "owl_sameAs"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o RdfsLiteral : "rdfs_label"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o OwlThing : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
B51b8d66516b28a1c54f8d745ede947b9 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o OwlThing : "fio_ofIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o FioIndustry : "fio_ofIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o OwlNamedIndividual : "fio_ofIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o RdfsLiteral : "dct_identifier"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o OwlThing : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
B5debef6666ba27aa225105865fd22d6c ||--|o OwlThing : "owl_sameAs"
B5debef6666ba27aa225105865fd22d6c ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o RdfsLiteral : "rdfs_label"
B5debef6666ba27aa225105865fd22d6c ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o OwlThing : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
B5debef6666ba27aa225105865fd22d6c ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o OwlThing : "fio_ofIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o FioIndustry : "fio_ofIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o OwlNamedIndividual : "fio_ofIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o RdfsLiteral : "dct_identifier"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o OwlThing : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o OwlThing : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o OwlThing : "owl_sameAs"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o RdfsLiteral : "rdfs_label"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
B671ac9cd6796151f919e5affbe3cc5f9 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o OwlThing : "fio_ofIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o FioIndustry : "fio_ofIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o OwlNamedIndividual : "fio_ofIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o RdfsLiteral : "dct_identifier"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o OwlThing : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o OwlThing : "owl_sameAs"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o RdfsLiteral : "rdfs_label"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
B707e8df015ee2912f85cf2fec8dc4718 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o OwlThing : "fio_ofIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o FioIndustry : "fio_ofIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o OwlNamedIndividual : "fio_ofIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o RdfsLiteral : "dct_identifier"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o OwlThing : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o OwlThing : "owl_sameAs"
B912c2f2722265f457d11b52388b1def0 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
B912c2f2722265f457d11b52388b1def0 ||--|o RdfsLiteral : "rdfs_label"
B912c2f2722265f457d11b52388b1def0 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o OwlThing : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
B912c2f2722265f457d11b52388b1def0 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o RdfsLiteral : "dct_identifier"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o OwlThing : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o OwlThing : "owl_sameAs"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o RdfsLiteral : "rdfs_label"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o OwlThing : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
B9968aab18e1237453b5cbb15df1c74b9 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o OwlThing : "fio_ofIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o FioIndustry : "fio_ofIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o OwlNamedIndividual : "fio_ofIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o RdfsLiteral : "dct_identifier"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o OwlThing : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o OwlThing : "owl_sameAs"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o RdfsLiteral : "rdfs_label"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Ba0ffbf1a7a548fac1e61d3eceada03dd ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o OwlThing : "fio_ofIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o FioIndustry : "fio_ofIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o OwlNamedIndividual : "fio_ofIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o RdfsLiteral : "dct_identifier"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o OwlThing : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o OwlThing : "owl_sameAs"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o RdfsLiteral : "rdfs_label"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Bdbdbfbd4ef20ffc37226553d96831226 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o RdfsLiteral : "dct_identifier"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o OwlThing : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o OwlThing : "owl_sameAs"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o RdfsLiteral : "rdfs_label"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o OwlThing : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Be082c2fc952b5eb7e355834fa6af4865 ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o OwlThing : "fio_ofIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o FioIndustry : "fio_ofIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o OwlNamedIndividual : "fio_ofIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o RdfsLiteral : "dct_identifier"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o OwlThing : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Be0e551f6155d8e99ee967119022af97d ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o OwlThing : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
Be0e551f6155d8e99ee967119022af97d ||--|o OwlThing : "owl_sameAs"
Be0e551f6155d8e99ee967119022af97d ||--|o RdfsLiteral : "rdfs_label"
Be0e551f6155d8e99ee967119022af97d ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Be0e551f6155d8e99ee967119022af97d ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o RdfsLiteral : "dct_identifier"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o OwlThing : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o OwlThing : "owl_sameAs"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o RdfsLiteral : "rdfs_label"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Bea9d030ae5649d7f06d536c2a467e56f ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o OwlThing : "fio_ofIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o FioIndustry : "fio_ofIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o OwlNamedIndividual : "fio_ofIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o RdfsLiteral : "dct_identifier"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o OwlThing : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o OwlThing : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o OwlThing : "owl_sameAs"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o RdfsLiteral : "rdfs_label"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Bf0c649c8d760a3559d3d5e5b1f68a59f ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o OwlThing : "fio_ofIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o FioIndustry : "fio_ofIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o OwlNamedIndividual : "fio_ofIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Bf906a89c08306329b89456f1d101a6bf ||--|o RdfsLiteral : "dct_identifier"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o OwlThing : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o OwlThing : "owl_sameAs"
Bf906a89c08306329b89456f1d101a6bf ||--|o RdfsLiteral : "rdfs_label"
Bf906a89c08306329b89456f1d101a6bf ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o OwlThing : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Bf906a89c08306329b89456f1d101a6bf ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
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
Fio-epa-frsAirProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAirProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAnimalOperation ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAnimalOperation ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsAssistanceSupportProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsAssistanceSupportProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsChemicalReleaseProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsChemicalReleaseProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsChemicalStorageProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsChemicalStorageProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsCoastalOceanProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsCoastalOceanProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsComplianceInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsComplianceInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsComplianceSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsComplianceSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsDrinkingWaterProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsDrinkingWaterProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "dct_created"
Fio-epa-frsEPA-PFAS-Facility ||--|o SdosPostalAddress : "sdos_address"
Fio-epa-frsEPA-PFAS-Facility ||--|o SdosText : "sdos_address"
Fio-epa-frsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlThing : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o FioIndustry : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "dct_identifier"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "dct_modified"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "dct_title"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEPA-PFAS-Facility ||--|o GeoGeometry : "geo_hasGeometry"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "dct_date"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlThing : "fio-epa-frs_ofFacilityType"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsFacilityType : "fio-epa-frs_ofFacilityType"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "fio-epa-frs_hasFRSId"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Commerce : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Interior : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Justice : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Transportation : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.HealthandHumanServices : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Energy : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Defense : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.Agriculture : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.VeteransAffairs : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsAgency.HomelandSecurity : "fio_ownedBy"
Fio-epa-frsEPA-PFAS-Facility ||--|o RdfsLiteral : "dct_alternative"
Fio-epa-frsEPA-PFAS-Facility ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o OwlThing : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
Fio-epa-frsEPA-PFAS-Facility ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
Fio-epa-frsEcologyOperation ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsEcologyOperation ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsElectronicPermitSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsElectronicPermitSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEnforcementInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsEnforcementInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEnforcementSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsEnforcementSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEnvironmentalInterestByProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsEnvironmentalInterestByProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEnvironmentalInterestType ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsEnvironmentalInterestType ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "dct_created"
Fio-epa-frsFRS-Facility ||--|o SdosPostalAddress : "sdos_address"
Fio-epa-frsFRS-Facility ||--|o SdosText : "sdos_address"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o FioIndustry : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "dct_identifier"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "dct_modified"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "dct_title"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsFRS-Facility ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsFRS-Facility ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsFRS-Facility ||--|o GeoGeometry : "geo_hasGeometry"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "dct_date"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_ofFacilityType"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsFacilityType : "fio-epa-frs_ofFacilityType"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "fio-epa-frs_hasFRSId"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Commerce : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Interior : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Justice : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Transportation : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.HealthandHumanServices : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Energy : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Defense : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o OwlNamedIndividual : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.Agriculture : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.VeteransAffairs : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsAgency.HomelandSecurity : "fio_ownedBy"
Fio-epa-frsFRS-Facility ||--|o RdfsLiteral : "dct_alternative"
Fio-epa-frsFRS-Facility ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o OwlThing : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
Fio-epa-frsFRS-Facility ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
Fio-epa-frsFacilitySiteIdentification ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsFacilitySiteIdentification ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsFacilityType ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsFacilityType ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsGrantSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsGrantSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsGroundWaterProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsGroundWaterProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsHazardousWasteProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsHazardousWasteProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsHealthSafetyProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsHealthSafetyProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsLegacySystem ||--|o OwlThing : "fio-epa-frs_replacedBy"
Fio-epa-frsLegacySystem ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsLegacySystem ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsLegacySystem ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsLegacySystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsLegacySystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsLegalEnforcementActivities ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsLegalEnforcementActivities ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsPermitInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsPermitInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsPermitSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsPermitSystem ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_partOf"
Fio-epa-frsPermitSystem ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_partOf"
Fio-epa-frsPermitSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsPesticidesProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsPesticidesProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsProgramInformationSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsProgramInformationSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsProjectSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsProjectSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsRadiationProtectionProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsRadiationProtectionProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o OwlThing : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o FioIndustry : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o OwlNamedIndividual : "fio_ofIndustry"
Fio-epa-frsRecord ||--|o RdfsLiteral : "dct_identifier"
Fio-epa-frsRecord ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o OwlThing : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Fio-epa-frsRecord ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsRecord ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsRecord ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsRecord ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o OwlThing : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRecord ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsRegistryInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsRegistryInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsRegistrySystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsRegistrySystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsRemediationRedevelopmentProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsRemediationRedevelopmentProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsReportingInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsReportingInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsReportingSystem ||--|o OwlThing : "fio-epa-frs_replacedBy"
Fio-epa-frsReportingSystem ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsReportingSystem ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsReportingSystem ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsReportingSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsReportingSystem ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_partOf"
Fio-epa-frsReportingSystem ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_partOf"
Fio-epa-frsReportingSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsRiskInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsRiskInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsSiteInterest ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsSiteInterest ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsSiteSystem ||--|o OwlThing : "fio-epa-frs_replacedBy"
Fio-epa-frsSiteSystem ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsSiteSystem ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsSiteSystem ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_replacedBy"
Fio-epa-frsSiteSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsSiteSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsSolidWasteProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsSolidWasteProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsStateSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsStateSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustrySubsector : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustrySector : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o FioIndustry : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o OwlNamedIndividual : "fio_ofIndustry"
Fio-epa-frsSupplementalRecord ||--|o RdfsLiteral : "dct_identifier"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_hasEnvironmentalInterest"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsStateSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsReportingSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsGrantSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsComplianceSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnforcementSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRegistrySystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSiteSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsPermitSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsTribalSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsProjectSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsProgramInformationSystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsLegacySystem : "fio-epa-frs_fromSystem"
Fio-epa-frsSupplementalRecord ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Be0e551f6155d8e99ee967119022af97d : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o B707e8df015ee2912f85cf2fec8dc4718 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o B3a5aa76705834f507db6d3c7d90d63b8 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Be082c2fc952b5eb7e355834fa6af4865 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o B43f2153f8fa51cc860da104aa4b996c7 : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Bea9d030ae5649d7f06d536c2a467e56f : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Bf906a89c08306329b89456f1d101a6bf : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRecord : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o B51b8d66516b28a1c54f8d745ede947b9 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o B912c2f2722265f457d11b52388b1def0 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Bdbdbfbd4ef20ffc37226553d96831226 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o B5debef6666ba27aa225105865fd22d6c : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Bf0c649c8d760a3559d3d5e5b1f68a59f : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Ba0ffbf1a7a548fac1e61d3eceada03dd : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o B9968aab18e1237453b5cbb15df1c74b9 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSupplementalRecord : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o B1d70f10e8204578c89c5f678467193ea : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsFRS-Facility : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o B671ac9cd6796151f919e5affbe3cc5f9 : "fio-epa-frs_hasSupplementalRecord"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o FioIndustry : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o OwlNamedIndividual : "fio-epa-frs_ofSecondaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustryGroup : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustrySubsector : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustrySector : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o NaicsNAICS-IndustryCode : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o FioIndustry : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o OwlNamedIndividual : "fio-epa-frs_ofPrimaryIndustry"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnforcementInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRiskInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRemediationRedevelopmentProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsElectronicPermitSystem : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsCoastalOceanProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsAnimalOperation : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsUndergroundStorageTankProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnvironmentalInterestByProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsComplianceInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsPesticidesProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsChemicalReleaseProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsAirProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRegistryInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsRadiationProtectionProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsHazardousWasteProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsFacilitySiteIdentification : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSiteInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsHealthSafetyProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsWasteWaterProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsAssistanceSupportProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o OwlThing : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsChemicalStorageProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsReportingInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsLegalEnforcementActivities : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsEnvironmentalInterestType : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsSolidWasteProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsPermitInterest : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsWaterResourcesProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsGroundWaterProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsSupplementalRecord ||--|o Fio-epa-frsDrinkingWaterProgram : "fio-epa-frs_ofInterestType"
Fio-epa-frsTribalSystem ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsTribalSystem ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsUndergroundStorageTankProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsUndergroundStorageTankProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsWasteWaterProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsWasteWaterProgram ||--|o RdfsLiteral : "rdfs_label"
Fio-epa-frsWaterResourcesProgram ||--|o OwlThing : "owl_sameAs"
Fio-epa-frsWaterResourcesProgram ||--|o RdfsLiteral : "rdfs_label"
FioIndustry ||--|o OwlThing : "owl_sameAs"
KwgoS2CellLevel13 ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustryCode ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-IndustryCode ||--|o RdfsLiteral : "dct_identifier"
NaicsNAICS-IndustryCode ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustryCode ||--|o RdfsLiteral : "rdfs_label"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o OwlThing : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustryCode : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o FioIndustry : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o OwlNamedIndividual : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-IndustryGroup ||--|o RdfsLiteral : "dct_identifier"
NaicsNAICS-IndustryGroup ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustryGroup ||--|o RdfsLiteral : "rdfs_label"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o OwlThing : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustryCode : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o FioIndustry : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o OwlNamedIndividual : "fio_subcodeOf"
NaicsNAICS-IndustrySector ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-IndustrySector ||--|o RdfsLiteral : "dct_identifier"
NaicsNAICS-IndustrySector ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustrySector ||--|o RdfsLiteral : "rdfs_label"
NaicsNAICS-IndustrySubsector ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-IndustrySubsector ||--|o RdfsLiteral : "dct_identifier"
NaicsNAICS-IndustrySubsector ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustrySubsector ||--|o RdfsLiteral : "rdfs_label"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o OwlThing : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustryCode : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o FioIndustry : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o OwlNamedIndividual : "fio_subcodeOf"

```



## Imports


* okns:dc
* linkml:types
* okns:owl-rdf-rdfs
* okns:prov
* okns:time
* okns:extended_types
* okns:kwg
* okns:geo
* okns:sdo



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [B9d449a3503d8291d6acf9c5a93d5670f](classes/B9d449a3503d8291d6acf9c5a93d5670f.md) | None<br/>|  | 
| [Bd6303cfa8c86e776b8e226496bd342eb](classes/Bd6303cfa8c86e776b8e226496bd342eb.md) | None<br/>|  | 
| [KwgoS2CellLevel13](classes/KwgoS2CellLevel13.md) | None<br/>| 249509 | 
| [OwlThing](classes/OwlThing.md) | The class of OWL individuals.<br/>| 731252 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[B1d70f10e8204578c89c5f678467193ea](classes/B1d70f10e8204578c89c5f678467193ea.md) | None<br/>| 8847 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[B3a5aa76705834f507db6d3c7d90d63b8](classes/B3a5aa76705834f507db6d3c7d90d63b8.md) | None<br/>| 80 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[B43f2153f8fa51cc860da104aa4b996c7](classes/B43f2153f8fa51cc860da104aa4b996c7.md) | None<br/>| 368761 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[B51b8d66516b28a1c54f8d745ede947b9](classes/B51b8d66516b28a1c54f8d745ede947b9.md) | None<br/>| 1318 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[B5debef6666ba27aa225105865fd22d6c](classes/B5debef6666ba27aa225105865fd22d6c.md) | None<br/>| 165107 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[B671ac9cd6796151f919e5affbe3cc5f9](classes/B671ac9cd6796151f919e5affbe3cc5f9.md) | None<br/>| 198462 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[B707e8df015ee2912f85cf2fec8dc4718](classes/B707e8df015ee2912f85cf2fec8dc4718.md) | None<br/>| 23765 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[B912c2f2722265f457d11b52388b1def0](classes/B912c2f2722265f457d11b52388b1def0.md) | None<br/>| 151232 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[B9968aab18e1237453b5cbb15df1c74b9](classes/B9968aab18e1237453b5cbb15df1c74b9.md) | None<br/>| 26083 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Ba0ffbf1a7a548fac1e61d3eceada03dd](classes/Ba0ffbf1a7a548fac1e61d3eceada03dd.md) | None<br/>| 20115 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Bdbdbfbd4ef20ffc37226553d96831226](classes/Bdbdbfbd4ef20ffc37226553d96831226.md) | None<br/>| 86645 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Be082c2fc952b5eb7e355834fa6af4865](classes/Be082c2fc952b5eb7e355834fa6af4865.md) | None<br/>| 13343 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Be0e551f6155d8e99ee967119022af97d](classes/Be0e551f6155d8e99ee967119022af97d.md) | None<br/>| 31220 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Bea9d030ae5649d7f06d536c2a467e56f](classes/Bea9d030ae5649d7f06d536c2a467e56f.md) | None<br/>| 380 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Bf0c649c8d760a3559d3d5e5b1f68a59f](classes/Bf0c649c8d760a3559d3d5e5b1f68a59f.md) | None<br/>| 329237 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Bf906a89c08306329b89456f1d101a6bf](classes/Bf906a89c08306329b89456f1d101a6bf.md) | None<br/>| 18113 | 
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
