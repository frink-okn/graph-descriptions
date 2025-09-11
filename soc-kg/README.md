# sockg





## Schema Diagram

```mermaid
erDiagram
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
WgsPoint {

}
WgsSpatialThing {

}
EventEvent {

}
EventFactor {

}
EventProduct {

}
BiboAcademicArticle {

}
BiboArticle {

}
BiboAudioDocument {

}
BiboAudioVisualDocument {

}
BiboBill {

}
BiboBook {

}
BiboBookSection {

}
BiboBrief {

}
BiboChapter {

}
BiboCode {

}
BiboCollectedDocument {

}
BiboCollection {

}
BiboConference {

}
BiboCourtReporter {

}
BiboDocument {

}
BiboDocumentPart {

}
BiboDocumentStatus {
    string rdfs_label  
    string rdfs_comment  
}
BiboEditedBook {

}
BiboEmail {

}
BiboEvent {

}
BiboExcerpt {

}
BiboFilm {

}
BiboHearing {

}
BiboImage {

}
BiboInterview {

}
BiboIssue {

}
BiboJournal {

}
BiboLegalCaseDocument {

}
BiboLegalDecision {

}
BiboLegalDocument {

}
BiboLegislation {

}
BiboLetter {

}
BiboMagazine {

}
BiboManual {

}
BiboManuscript {

}
BiboMap {

}
BiboMultiVolumeBook {

}
BiboNewspaper {

}
BiboNote {

}
BiboPatent {

}
BiboPerformance {

}
BiboPeriodical {

}
BiboPersonalCommunication {

}
BiboPersonalCommunicationDocument {

}
BiboProceedings {

}
BiboQuote {

}
BiboReferenceSource {

}
BiboReport {

}
BiboSeries {

}
BiboSlide {

}
BiboSlideshow {

}
BiboStandard {

}
BiboStatute {

}
BiboThesis {

}
BiboThesisDegree {
    string rdfs_label  
    string rdfs_comment  
}
BiboWebpage {

}
BiboWebsite {

}
BiboWorkshop {

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
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Abstract {
    string http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_correspondingAuthor  
    string rdfs_label  
    date dct_issued  
    string dct_title  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ActiveIngredient {
    string coso_casNumber  
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment {
    date http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_startDate  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AmendmentPlacement {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AmendmentType {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AnimalClass {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AnimalSpecies {
    string rdfs_label  
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassCarbohydrate {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassEnergy {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassMineral {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BookChapter {
    string http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_correspondingAuthor  
    string rdfs_label  
    date dct_issued  
    string dct_title  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BroadleafOrGrass {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278CoverCrop {
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Cultivar {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278CuttingHeight {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Equipment {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit {
    date http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_endDate  
    date http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_startDate  
    boolean http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_inferred  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitUrl  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278FertilizerAmendment {
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278FundingSource {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingManagement {
    date http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_endDate  
    date http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_startDate  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingPlants {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingRate {
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStageManagement {

}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestFraction {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestedFraction {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Irrigation {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle {
    string http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_correspondingAuthor  
    string rdfs_label  
    date dct_issued  
    string dct_title  
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location {
    string rdfs_label  
    string dct_description  
    date http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_endDate  
    date http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_startDate  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278LossesOrDeposition {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement {

}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278NutrientEfficiency {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278OtherEvents {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Parameter {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PesticidePlacement {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PesticideTarget {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantFraction {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingManagement {
    date http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_startDate  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingMethod {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PopularArticle {
    string http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_correspondingAuthor  
    string rdfs_label  
    date dct_issued  
    string dct_title  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Proceedings {
    string http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_correspondingAuthor  
    string rdfs_label  
    date dct_issued  
    string dct_title  
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Project {
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ProjectScenario {
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Report {
    string http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_correspondingAuthor  
    string rdfs_label  
    date dct_issued  
    string dct_title  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueManagement {
    date http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_startDate  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueMeasurement {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueRemoval {
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Rotation {
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site {

}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilBiologicalSample {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilChemicalSample {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilCover {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilPhysicalSample {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SpeciesMix {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278StartStopInterval {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SurfaceOrLeaching {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Thesis {
    string http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_correspondingAuthor  
    string rdfs_label  
    date dct_issued  
    string dct_title  
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Tillage {
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageEvent {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageManagement {
    date http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_startDate  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageMethod {
    string rdfs_label  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Timing {
    string dct_description  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment {
    string dct_description  
    boolean http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_organicManagement  
    boolean http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_tileDrainage  
    boolean http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_irrigation  
    date http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_startDate  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityArea {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278YieldNutrientUptake {
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit  
    uri http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment  
}
HttpsIdir.uta.eduSockg-ontologyDocs#Abstract {

}
HttpsIdir.uta.eduSockg-ontologyDocs#ActiveIngredient {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Amendment {

}
HttpsIdir.uta.eduSockg-ontologyDocs#AmendmentPlacement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#AnimalClass {

}
HttpsIdir.uta.eduSockg-ontologyDocs#AnimalSpecies {

}
HttpsIdir.uta.eduSockg-ontologyDocs#BiomassAnalysis {

}
HttpsIdir.uta.eduSockg-ontologyDocs#BiomassCarbohydrate {

}
HttpsIdir.uta.eduSockg-ontologyDocs#BiomassEnergy {

}
HttpsIdir.uta.eduSockg-ontologyDocs#BiomassMineral {

}
HttpsIdir.uta.eduSockg-ontologyDocs#BookChapter {

}
HttpsIdir.uta.eduSockg-ontologyDocs#BroadleafOrGrass {

}
HttpsIdir.uta.eduSockg-ontologyDocs#ChamberPlacement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#CoverCrop {

}
HttpsIdir.uta.eduSockg-ontologyDocs#CropRelatedMeasurement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Cultivar {

}
HttpsIdir.uta.eduSockg-ontologyDocs#CuttingHeight {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Equipment {

}
HttpsIdir.uta.eduSockg-ontologyDocs#ErosionMeasurement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#ExperimentalUnit {

}
HttpsIdir.uta.eduSockg-ontologyDocs#FertilizerAmendment {

}
HttpsIdir.uta.eduSockg-ontologyDocs#FundingSource {

}
HttpsIdir.uta.eduSockg-ontologyDocs#GHGFlux {

}
HttpsIdir.uta.eduSockg-ontologyDocs#GasNutrientLoss {

}
HttpsIdir.uta.eduSockg-ontologyDocs#GrazingManagement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#GrazingPlants {

}
HttpsIdir.uta.eduSockg-ontologyDocs#GrazingRate {

}
HttpsIdir.uta.eduSockg-ontologyDocs#GrowthStage {

}
HttpsIdir.uta.eduSockg-ontologyDocs#GrowthStageManagement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#GrowthStageRelatedMeasurement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#HarvestFraction {

}
HttpsIdir.uta.eduSockg-ontologyDocs#HarvestedFraction {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Irrigation {

}
HttpsIdir.uta.eduSockg-ontologyDocs#JournalArticle {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Location {

}
HttpsIdir.uta.eduSockg-ontologyDocs#LossesOrDeposition {

}
HttpsIdir.uta.eduSockg-ontologyDocs#MeasurableEntity {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Measurement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#NutrientEfficiency {

}
HttpsIdir.uta.eduSockg-ontologyDocs#OtherEvents {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Parameter {

}
HttpsIdir.uta.eduSockg-ontologyDocs#PesticidePlacement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#PesticideTarget {

}
HttpsIdir.uta.eduSockg-ontologyDocs#PlantFraction {

}
HttpsIdir.uta.eduSockg-ontologyDocs#PlantFractionRelatedMeasurement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#PlantingManagement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#PlantingMethod {

}
HttpsIdir.uta.eduSockg-ontologyDocs#PopularArticle {

}
HttpsIdir.uta.eduSockg-ontologyDocs#PossiblySimulatedMeasurement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Proceedings {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Project {

}
HttpsIdir.uta.eduSockg-ontologyDocs#ProjectScenario {

}
HttpsIdir.uta.eduSockg-ontologyDocs#QualityMeasurement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Report {

}
HttpsIdir.uta.eduSockg-ontologyDocs#ResidueManagement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#ResidueMeasurement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#ResidueRemoval {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Rotation {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Sample {

}
HttpsIdir.uta.eduSockg-ontologyDocs#SimulationModel {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Site {

}
HttpsIdir.uta.eduSockg-ontologyDocs#SoilBiologicalSample {

}
HttpsIdir.uta.eduSockg-ontologyDocs#SoilChemicalSample {

}
HttpsIdir.uta.eduSockg-ontologyDocs#SoilCover {

}
HttpsIdir.uta.eduSockg-ontologyDocs#SoilPhysicalSample {

}
HttpsIdir.uta.eduSockg-ontologyDocs#SoilSample {

}
HttpsIdir.uta.eduSockg-ontologyDocs#SpeciesMix {

}
HttpsIdir.uta.eduSockg-ontologyDocs#StartStopInterval {

}
HttpsIdir.uta.eduSockg-ontologyDocs#SurfaceOrLeaching {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Thesis {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Tillage {

}
HttpsIdir.uta.eduSockg-ontologyDocs#TillageEvent {

}
HttpsIdir.uta.eduSockg-ontologyDocs#TillageManagement {

}
HttpsIdir.uta.eduSockg-ontologyDocs#TillageMethod {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Timing {

}
HttpsIdir.uta.eduSockg-ontologyDocs#Treatment {

}
HttpsIdir.uta.eduSockg-ontologyDocs#WaterQualityArea {

}
HttpsIdir.uta.eduSockg-ontologyDocs#WaterQualityConcentration {

}
HttpsIdir.uta.eduSockg-ontologyDocs#WeatherObservation {

}
HttpsIdir.uta.eduSockg-ontologyDocs#WindErosionArea {

}
HttpsIdir.uta.eduSockg-ontologyDocs#YieldNutrientUptake {

}
HttpsLod.nal.usda.govNalt7140 {
    string rdfs_label  
}
KwgoS2CellLevel13 {

}

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
TimeDayOfWeek ||--|o RdfsLiteral : "rdfs_label"
TimeTemporalUnit ||--|o RdfsLiteral : "rdfs_label"
BiboDocumentStatus ||--|o RdfsLiteral : "rdfs_label"
BiboDocumentStatus ||--|o RdfsLiteral : "rdfs_comment"
BiboThesisDegree ||--|o RdfsLiteral : "rdfs_label"
BiboThesisDegree ||--|o RdfsLiteral : "rdfs_comment"
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
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Abstract ||--|o RdfsLiteral : "dct_bibliographicCitation"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Abstract ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Abstract ||--|o RdfsLiteral : "dct_issued"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Abstract ||--|o RdfsLiteral : "dct_title"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ActiveIngredient ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PesticideTarget : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasPesticideTarget"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ActiveIngredient : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasPesticideActiveIngredient"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PesticidePlacement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_withPesticidePlacement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AmendmentType : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasAmendmentType"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Irrigation : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesIrrigation"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AmendmentPlacement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_withPlacement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AmendmentPlacement ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AmendmentType ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AnimalClass ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AnimalSpecies ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassCarbohydrate ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantFraction : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasPlantFraction"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassCarbohydrate ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassCarbohydrate ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassCarbohydrate ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassCarbohydrate ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassCarbohydrate ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassCarbohydrate ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassEnergy ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantFraction : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasPlantFraction"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassEnergy ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassEnergy ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassEnergy ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassEnergy ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassEnergy ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassEnergy ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassMineral ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantFraction : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasPlantFraction"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassMineral ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassMineral ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassMineral ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassMineral ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassMineral ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassMineral ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BookChapter ||--|o RdfsLiteral : "dct_bibliographicCitation"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BookChapter ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BookChapter ||--|o RdfsLiteral : "dct_issued"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BookChapter ||--|o RdfsLiteral : "dct_title"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BroadleafOrGrass ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Cultivar ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278CuttingHeight ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Equipment ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueManagement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_unitHasResidueManagement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStageManagement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_unitHasGrowthStageManagement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingManagement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_unitHasPlantingManagement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingManagement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_unitHasGrazingManagement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageManagement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_unitHasTillageManagement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_unitHasAmendment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit ||--|o RdfsLiteral : "dct_identifier"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278FundingSource ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278StartStopInterval : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_withStartStopInterval"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesModel"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AnimalSpecies : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasAnimalSpecies"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AnimalClass : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasAnimalClass"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278OtherEvents : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasOtherEvents"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingPlants ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SpeciesMix : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasSpeciesMix"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingPlants ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingPlants ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingPlants ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingPlants ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BroadleafOrGrass : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasBroadleafOrGrass"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingPlants ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingPlants ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStageManagement ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStageManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStageManagement ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestFraction ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantFraction : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasPlantFraction"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestFraction ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestFraction ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestFraction ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestFraction ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestFraction ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestFraction ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestedFraction ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Irrigation ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle ||--|o RdfsLiteral : "dct_bibliographicCitation"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle ||--|o RdfsLiteral : "dct_issued"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle ||--|o RdfsLiteral : "dct_title"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle ||--|o RdfsLiteral : "dct_identifier"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278FundingSource : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fundedBy"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site : "spatial_connectedTo"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location : "spatial_connectedTo"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o KwgoAdministrativeRegion2 : "spatial_connectedTo"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o KwgoS2CellLevel13 : "spatial_connectedTo"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BookChapter : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_cites"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PopularArticle : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_cites"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Report : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_cites"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o DctBibliographicResource : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_cites"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Proceedings : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_cites"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Abstract : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_cites"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Thesis : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_cites"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_cites"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o GeoGeometry : "geo_hasGeometry"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location ||--|o RdfsLiteral : "dct_identifier"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278LossesOrDeposition ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement ||--|o QudtQuantityValue : "qudt_quantityValue"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Parameter : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_of"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278NutrientEfficiency ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantFraction : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasPlantFraction"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278NutrientEfficiency ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278NutrientEfficiency ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278NutrientEfficiency ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278NutrientEfficiency ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278NutrientEfficiency ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278NutrientEfficiency ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278OtherEvents ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Parameter ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PesticidePlacement ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PesticideTarget ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantFraction ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Cultivar : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCultivar"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingManagement ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingMethod : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesPlantingMethod"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingMethod ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PopularArticle ||--|o RdfsLiteral : "dct_bibliographicCitation"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PopularArticle ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PopularArticle ||--|o RdfsLiteral : "dct_issued"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PopularArticle ||--|o RdfsLiteral : "dct_title"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Proceedings ||--|o RdfsLiteral : "dct_bibliographicCitation"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Proceedings ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Proceedings ||--|o RdfsLiteral : "dct_issued"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Proceedings ||--|o RdfsLiteral : "dct_title"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Report ||--|o RdfsLiteral : "dct_bibliographicCitation"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Report ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Report ||--|o RdfsLiteral : "dct_issued"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Report ||--|o RdfsLiteral : "dct_title"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278CuttingHeight : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_withCuttingHeight"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueManagement ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Equipment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesEquipment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueMeasurement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueMeasurement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueMeasurement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueMeasurement ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueMeasurement ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueMeasurement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestedFraction : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasHarvestedFraction"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueMeasurement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site ||--|o SdosText : "sdos_postalCode"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site : "spatial_connectedTo"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location : "spatial_connectedTo"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site ||--|o KwgoAdministrativeRegion2 : "spatial_connectedTo"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site ||--|o KwgoS2CellLevel13 : "spatial_connectedTo"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site ||--|o RdfsLiteral : "dct_identifier"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilBiologicalSample ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilBiologicalSample ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilBiologicalSample ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilBiologicalSample ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilBiologicalSample ||--|o QudtQuantityValue : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_lowerDepth"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilBiologicalSample ||--|o QudtQuantityValue : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_upperDepth"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilChemicalSample ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilChemicalSample ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilChemicalSample ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesModel"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilChemicalSample ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilChemicalSample ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilChemicalSample ||--|o QudtQuantityValue : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_lowerDepth"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilChemicalSample ||--|o QudtQuantityValue : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_upperDepth"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilCover ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Timing : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasTiming"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilCover ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilCover ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilCover ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilCover ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilPhysicalSample ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilPhysicalSample ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilPhysicalSample ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesModel"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilPhysicalSample ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilPhysicalSample ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilPhysicalSample ||--|o QudtQuantityValue : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_lowerDepth"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilPhysicalSample ||--|o QudtQuantityValue : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_upperDepth"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SpeciesMix ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278StartStopInterval ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SurfaceOrLeaching ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Thesis ||--|o RdfsLiteral : "dct_bibliographicCitation"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Thesis ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Thesis ||--|o RdfsLiteral : "dct_issued"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Thesis ||--|o RdfsLiteral : "dct_title"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageEvent ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageEvent : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasTillageEvent"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageManagement ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageMethod : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTillageMethod"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageManagement ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageMethod ||--|o RdfsLiteral : "rdfs_label"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStageManagement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_treatmentHasGrowthStageManagement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_treatmentHasAmendment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingManagement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_treatmentHasPlantingManagement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ProjectScenario : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasProjectScenario"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AnimalSpecies : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasAnimalSpecies"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingManagement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_treatmentHasGrazingManagement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueManagement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_treatmentHasResidueManagement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueRemoval : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesResidueRemoval"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Rotation : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasRotation"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278FertilizerAmendment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesFertilizerAmendment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Project : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromProject"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingRate : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrazingRate"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o RdfsLiteral : "dct_identifier"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278CoverCrop : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesCoverCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Tillage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasTillage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageManagement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_treatmentHasTillageManagement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityArea ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278LossesOrDeposition : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasLossesOrDeposition"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityArea ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityArea ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityArea ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityArea ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityArea ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SurfaceOrLeaching : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasSurfaceOrLeaching"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278StartStopInterval : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_withStartStopInterval"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesModel"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SurfaceOrLeaching : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasSurfaceOrLeaching"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278LossesOrDeposition : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasLossesOrDeposition"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278StartStopInterval : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_withStartStopInterval"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesModel"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278YieldNutrientUptake ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantFraction : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasPlantFraction"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278YieldNutrientUptake ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_fromUnit"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278YieldNutrientUptake ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_usesTreatment"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278YieldNutrientUptake ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasGrowthStage"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278YieldNutrientUptake ||--|o RdfsLiteral : "dct_date"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278YieldNutrientUptake ||--|o HttpsLod.nal.usda.govNalt7140 : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasCrop"
HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278YieldNutrientUptake ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement : "http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_hasMeasurement"
HttpsLod.nal.usda.govNalt7140 ||--|o RdfsLiteral : "rdfs_label"
KwgoS2CellLevel13 ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site : "spatial_connectedTo"
KwgoS2CellLevel13 ||--|o HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location : "spatial_connectedTo"
KwgoS2CellLevel13 ||--|o KwgoAdministrativeRegion2 : "spatial_connectedTo"
KwgoS2CellLevel13 ||--|o KwgoS2CellLevel13 : "spatial_connectedTo"

```



## Imports


* okns:bibo
* okns:kwg
* okns:qudt
* okns:geo
* okns:extended_types
* okns:sdo
* okns:dc
* linkml:types
* okns:owl-rdf-rdfs



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [DctBibliographicResource](classes/DctBibliographicResource.md) | A book, article, or other documentary resource.<br/>| 14 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#Abstract](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Abstract.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#BookChapter](classes/HttpsIdir.uta.eduSockg-ontologyDocs#BookChapter.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#JournalArticle](classes/HttpsIdir.uta.eduSockg-ontologyDocs#JournalArticle.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#PopularArticle](classes/HttpsIdir.uta.eduSockg-ontologyDocs#PopularArticle.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#Proceedings](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Proceedings.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#Report](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Report.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#Thesis](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Thesis.md) | None<br/>|  | 
| [GeoSpatialObject](classes/GeoSpatialObject.md) | Anything spatial (being or having a shape, position or an extent).<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[GeoFeature](classes/GeoFeature.md) | A discrete spatial phenomenon in a universe of discourse.<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#ExperimentalUnit](classes/HttpsIdir.uta.eduSockg-ontologyDocs#ExperimentalUnit.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#Location](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Location.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#Site](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Site.md) | None<br/>|  | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Abstract](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Abstract.md) | None<br/>| 3 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ActiveIngredient](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ActiveIngredient.md) | None<br/>| 84 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Amendment.md) | None<br/>| 47106 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AmendmentPlacement](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AmendmentPlacement.md) | None<br/>| 10 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AmendmentType](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AmendmentType.md) | None<br/>| 73 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AnimalClass](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AnimalClass.md) | None<br/>| 4 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AnimalSpecies](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278AnimalSpecies.md) | None<br/>| 3 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassCarbohydrate](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassCarbohydrate.md) | None<br/>| 1367 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassEnergy](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassEnergy.md) | None<br/>| 799 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassMineral](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BiomassMineral.md) | None<br/>| 6739 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BookChapter](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BookChapter.md) | None<br/>| 2 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BroadleafOrGrass](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BroadleafOrGrass.md) | None<br/>| 2 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278CoverCrop](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278CoverCrop.md) | None<br/>| 8 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Cultivar](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Cultivar.md) | None<br/>| 308 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278CuttingHeight](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278CuttingHeight.md) | None<br/>| 17 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Equipment](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Equipment.md) | None<br/>| 12 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit.md) | None<br/>| 3863 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278FertilizerAmendment](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278FertilizerAmendment.md) | None<br/>| 4 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278FundingSource](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278FundingSource.md) | None<br/>| 7 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GasNutrientLoss.md) | None<br/>| 2231 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingManagement](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingManagement.md) | None<br/>| 1951 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingPlants](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingPlants.md) | None<br/>| 6996 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingRate](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrazingRate.md) | None<br/>| 3 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStage.md) | None<br/>| 33 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStageManagement](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278GrowthStageManagement.md) | None<br/>| 5148 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestedFraction](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestedFraction.md) | None<br/>| 12 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestFraction](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278HarvestFraction.md) | None<br/>| 9470 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Irrigation](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Irrigation.md) | None<br/>| 4 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle.md) | None<br/>| 149 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location.md) | None<br/>| 58 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278LossesOrDeposition](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278LossesOrDeposition.md) | None<br/>| 2 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Measurement.md) | None<br/>| 911199 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278NutrientEfficiency](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278NutrientEfficiency.md) | None<br/>| 5159 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278OtherEvents](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278OtherEvents.md) | None<br/>| 2 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Parameter](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Parameter.md) | None<br/>| 135 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PesticidePlacement](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PesticidePlacement.md) | None<br/>| 5 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PesticideTarget](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PesticideTarget.md) | None<br/>| 38 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantFraction](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantFraction.md) | None<br/>| 29 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingManagement](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingManagement.md) | None<br/>| 23728 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingMethod](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PlantingMethod.md) | None<br/>| 6 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PopularArticle](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PopularArticle.md) | None<br/>| 1 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Proceedings](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Proceedings.md) | None<br/>| 3 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Project](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Project.md) | None<br/>| 3 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ProjectScenario](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ProjectScenario.md) | None<br/>| 19 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Report](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Report.md) | None<br/>| 1 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueManagement](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueManagement.md) | None<br/>| 3334 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueMeasurement](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueMeasurement.md) | None<br/>| 18512 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueRemoval](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ResidueRemoval.md) | None<br/>| 3 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Rotation](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Rotation.md) | None<br/>| 66 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SimulationModel.md) | None<br/>| 12 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site.md) | None<br/>| 60 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilBiologicalSample](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilBiologicalSample.md) | None<br/>| 18273 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilChemicalSample](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilChemicalSample.md) | None<br/>| 54269 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilCover](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilCover.md) | None<br/>| 1034 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilPhysicalSample](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SoilPhysicalSample.md) | None<br/>| 28237 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SpeciesMix](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SpeciesMix.md) | None<br/>| 7 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278StartStopInterval](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278StartStopInterval.md) | None<br/>| 3 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SurfaceOrLeaching](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278SurfaceOrLeaching.md) | None<br/>| 2 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Thesis](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Thesis.md) | None<br/>| 4 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Tillage](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Tillage.md) | None<br/>| 8 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageEvent](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageEvent.md) | None<br/>| 18 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageManagement](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageManagement.md) | None<br/>| 27450 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageMethod](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278TillageMethod.md) | None<br/>| 61 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Timing](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Timing.md) | None<br/>| 7 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment.md) | None<br/>| 769 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityArea](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityArea.md) | None<br/>| 681 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WaterQualityConcentration.md) | None<br/>| 2305 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278WindErosionArea.md) | None<br/>| 34 | 
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278YieldNutrientUptake](classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278YieldNutrientUptake.md) | None<br/>| 704 | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#ActiveIngredient](classes/HttpsIdir.uta.eduSockg-ontologyDocs#ActiveIngredient.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#AmendmentPlacement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#AmendmentPlacement.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#AnimalClass](classes/HttpsIdir.uta.eduSockg-ontologyDocs#AnimalClass.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#AnimalSpecies](classes/HttpsIdir.uta.eduSockg-ontologyDocs#AnimalSpecies.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#BroadleafOrGrass](classes/HttpsIdir.uta.eduSockg-ontologyDocs#BroadleafOrGrass.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#ChamberPlacement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#ChamberPlacement.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#CoverCrop](classes/HttpsIdir.uta.eduSockg-ontologyDocs#CoverCrop.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#Cultivar](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Cultivar.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#CuttingHeight](classes/HttpsIdir.uta.eduSockg-ontologyDocs#CuttingHeight.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#Equipment](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Equipment.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#FertilizerAmendment](classes/HttpsIdir.uta.eduSockg-ontologyDocs#FertilizerAmendment.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#FundingSource](classes/HttpsIdir.uta.eduSockg-ontologyDocs#FundingSource.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#GrazingRate](classes/HttpsIdir.uta.eduSockg-ontologyDocs#GrazingRate.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#GrowthStage](classes/HttpsIdir.uta.eduSockg-ontologyDocs#GrowthStage.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#HarvestedFraction](classes/HttpsIdir.uta.eduSockg-ontologyDocs#HarvestedFraction.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#Irrigation](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Irrigation.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#LossesOrDeposition](classes/HttpsIdir.uta.eduSockg-ontologyDocs#LossesOrDeposition.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#MeasurableEntity](classes/HttpsIdir.uta.eduSockg-ontologyDocs#MeasurableEntity.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#Amendment](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Amendment.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#GrazingManagement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#GrazingManagement.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#GrowthStageManagement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#GrowthStageManagement.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#PlantingManagement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#PlantingManagement.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#ResidueManagement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#ResidueManagement.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#Sample](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Sample.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#CropRelatedMeasurement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#CropRelatedMeasurement.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#GHGFlux](classes/HttpsIdir.uta.eduSockg-ontologyDocs#GHGFlux.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#SoilCover](classes/HttpsIdir.uta.eduSockg-ontologyDocs#SoilCover.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#ErosionMeasurement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#ErosionMeasurement.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#GrowthStageRelatedMeasurement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#GrowthStageRelatedMeasurement.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#GrazingPlants](classes/HttpsIdir.uta.eduSockg-ontologyDocs#GrazingPlants.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#ResidueMeasurement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#ResidueMeasurement.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#PlantFractionRelatedMeasurement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#PlantFractionRelatedMeasurement.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#BiomassAnalysis](classes/HttpsIdir.uta.eduSockg-ontologyDocs#BiomassAnalysis.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#BiomassCarbohydrate](classes/HttpsIdir.uta.eduSockg-ontologyDocs#BiomassCarbohydrate.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#BiomassEnergy](classes/HttpsIdir.uta.eduSockg-ontologyDocs#BiomassEnergy.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#BiomassMineral](classes/HttpsIdir.uta.eduSockg-ontologyDocs#BiomassMineral.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#HarvestFraction](classes/HttpsIdir.uta.eduSockg-ontologyDocs#HarvestFraction.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#NutrientEfficiency](classes/HttpsIdir.uta.eduSockg-ontologyDocs#NutrientEfficiency.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#PossiblySimulatedMeasurement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#PossiblySimulatedMeasurement.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#SoilSample](classes/HttpsIdir.uta.eduSockg-ontologyDocs#SoilSample.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#SoilBiologicalSample](classes/HttpsIdir.uta.eduSockg-ontologyDocs#SoilBiologicalSample.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#SoilChemicalSample](classes/HttpsIdir.uta.eduSockg-ontologyDocs#SoilChemicalSample.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#SoilPhysicalSample](classes/HttpsIdir.uta.eduSockg-ontologyDocs#SoilPhysicalSample.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#WindErosionArea](classes/HttpsIdir.uta.eduSockg-ontologyDocs#WindErosionArea.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#YieldNutrientUptake](classes/HttpsIdir.uta.eduSockg-ontologyDocs#YieldNutrientUptake.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#QualityMeasurement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#QualityMeasurement.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#GasNutrientLoss](classes/HttpsIdir.uta.eduSockg-ontologyDocs#GasNutrientLoss.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#WaterQualityArea](classes/HttpsIdir.uta.eduSockg-ontologyDocs#WaterQualityArea.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#WaterQualityConcentration](classes/HttpsIdir.uta.eduSockg-ontologyDocs#WaterQualityConcentration.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#TillageManagement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#TillageManagement.md) | None<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpsIdir.uta.eduSockg-ontologyDocs#WeatherObservation](classes/HttpsIdir.uta.eduSockg-ontologyDocs#WeatherObservation.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#Measurement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Measurement.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#OtherEvents](classes/HttpsIdir.uta.eduSockg-ontologyDocs#OtherEvents.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#Parameter](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Parameter.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#PesticidePlacement](classes/HttpsIdir.uta.eduSockg-ontologyDocs#PesticidePlacement.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#PesticideTarget](classes/HttpsIdir.uta.eduSockg-ontologyDocs#PesticideTarget.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#PlantFraction](classes/HttpsIdir.uta.eduSockg-ontologyDocs#PlantFraction.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#PlantingMethod](classes/HttpsIdir.uta.eduSockg-ontologyDocs#PlantingMethod.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#Project](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Project.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#ProjectScenario](classes/HttpsIdir.uta.eduSockg-ontologyDocs#ProjectScenario.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#ResidueRemoval](classes/HttpsIdir.uta.eduSockg-ontologyDocs#ResidueRemoval.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#Rotation](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Rotation.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#SimulationModel](classes/HttpsIdir.uta.eduSockg-ontologyDocs#SimulationModel.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#SpeciesMix](classes/HttpsIdir.uta.eduSockg-ontologyDocs#SpeciesMix.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#StartStopInterval](classes/HttpsIdir.uta.eduSockg-ontologyDocs#StartStopInterval.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#SurfaceOrLeaching](classes/HttpsIdir.uta.eduSockg-ontologyDocs#SurfaceOrLeaching.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#Tillage](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Tillage.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#TillageEvent](classes/HttpsIdir.uta.eduSockg-ontologyDocs#TillageEvent.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#TillageMethod](classes/HttpsIdir.uta.eduSockg-ontologyDocs#TillageMethod.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#Timing](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Timing.md) | None<br/>|  | 
| [HttpsIdir.uta.eduSockg-ontologyDocs#Treatment](classes/HttpsIdir.uta.eduSockg-ontologyDocs#Treatment.md) | None<br/>|  | 
| [HttpsLod.nal.usda.govNalt7140](classes/HttpsLod.nal.usda.govNalt7140.md) | None<br/>| 48 | 
| [KwgoS2CellLevel13](classes/KwgoS2CellLevel13.md) | None<br/>| 1069 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [coso_casNumber](slots/coso_casNumber.md) | <br/>| 84 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_cites](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_cites.md) | <br/>| 177 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_correspondingAuthor](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_correspondingAuthor.md) | <br/>| 136 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_endDate](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_endDate.md) | <br/>| 3974 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromProject](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromProject.md) | <br/>| 935 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fromUnit.md) | <br/>| 156810 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fundedBy](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_fundedBy.md) | <br/>| 54 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasAmendmentType](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasAmendmentType.md) | <br/>| 25357 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasAnimalClass](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasAnimalClass.md) | <br/>| 1833 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasAnimalSpecies](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasAnimalSpecies.md) | <br/>| 1954 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasBroadleafOrGrass](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasBroadleafOrGrass.md) | <br/>| 6996 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasCrop](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasCrop.md) | <br/>| 149843 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasCultivar](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasCultivar.md) | <br/>| 20926 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasGrazingRate](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasGrazingRate.md) | <br/>| 20 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasGrowthStage](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasGrowthStage.md) | <br/>| 56789 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasHarvestedFraction](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasHarvestedFraction.md) | <br/>| 18154 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasLossesOrDeposition](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasLossesOrDeposition.md) | <br/>| 149 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasMeasurement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasMeasurement.md) | <br/>| 911199 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasOtherEvents](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasOtherEvents.md) | <br/>| 4 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasPesticideActiveIngredient](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasPesticideActiveIngredient.md) | <br/>| 16104 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasPesticideTarget](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasPesticideTarget.md) | <br/>| 12841 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasPlantFraction](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasPlantFraction.md) | <br/>| 24130 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasProjectScenario](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasProjectScenario.md) | <br/>| 826 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasRotation](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasRotation.md) | <br/>| 761 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasSpeciesMix](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasSpeciesMix.md) | <br/>| 6996 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasSurfaceOrLeaching](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasSurfaceOrLeaching.md) | <br/>| 2986 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasTillage](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasTillage.md) | <br/>| 711 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasTillageEvent](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasTillageEvent.md) | <br/>| 27450 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasTiming](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasTiming.md) | <br/>| 1034 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasTreatment](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_hasTreatment.md) | <br/>| 769 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_inferred](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_inferred.md) | <br/>| 3863 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_irrigation](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_irrigation.md) | <br/>| 774 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_lowerDepth](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_lowerDepth.md) | <br/>| 100779 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_of](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_of.md) | <br/>| 911199 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_organicManagement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_organicManagement.md) | <br/>| 769 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_startDate](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_startDate.md) | <br/>| 107758 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_tileDrainage](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_tileDrainage.md) | <br/>| 438 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_treatmentHasAmendment](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_treatmentHasAmendment.md) | <br/>| 47106 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_treatmentHasGrazingManagement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_treatmentHasGrazingManagement.md) | <br/>| 1951 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_treatmentHasGrowthStageManagement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_treatmentHasGrowthStageManagement.md) | <br/>| 5148 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_treatmentHasPlantingManagement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_treatmentHasPlantingManagement.md) | <br/>| 23728 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_treatmentHasResidueManagement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_treatmentHasResidueManagement.md) | <br/>| 3334 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_treatmentHasTillageManagement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_treatmentHasTillageManagement.md) | <br/>| 27450 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitHasAmendment](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitHasAmendment.md) | <br/>| 47106 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitHasGrazingManagement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitHasGrazingManagement.md) | <br/>| 1951 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitHasGrowthStageManagement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitHasGrowthStageManagement.md) | <br/>| 5148 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitHasPlantingManagement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitHasPlantingManagement.md) | <br/>| 23728 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitHasResidueManagement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitHasResidueManagement.md) | <br/>| 3334 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitHasTillageManagement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitHasTillageManagement.md) | <br/>| 27449 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitUrl](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_unitUrl.md) | <br/>| 23 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_upperDepth](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_upperDepth.md) | <br/>| 100779 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesCoverCrop](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesCoverCrop.md) | <br/>| 194 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesEquipment](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesEquipment.md) | <br/>| 3070 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesFertilizerAmendment](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesFertilizerAmendment.md) | <br/>| 653 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesIrrigation](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesIrrigation.md) | <br/>| 6063 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesModel](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesModel.md) | <br/>| 923 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesPlantingMethod](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesPlantingMethod.md) | <br/>| 22592 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesResidueRemoval](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesResidueRemoval.md) | <br/>| 769 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTillageMethod](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTillageMethod.md) | <br/>| 24709 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_usesTreatment.md) | <br/>| 156810 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_withCuttingHeight](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_withCuttingHeight.md) | <br/>| 2954 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_withPesticidePlacement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_withPesticidePlacement.md) | <br/>| 9498 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_withPlacement](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_withPlacement.md) | <br/>| 24794 |
| [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_withStartStopInterval](slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_withStartStopInterval.md) | <br/>| 1722 |
| [https___idir.uta.edu_sockg_ontology_docs#badValueFlag](slots/https___idir.uta.edu_sockg_ontology_docs#badValueFlag.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#cites](slots/https___idir.uta.edu_sockg_ontology_docs#cites.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#correspondingAuthor](slots/https___idir.uta.edu_sockg_ontology_docs#correspondingAuthor.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#endDate](slots/https___idir.uta.edu_sockg_ontology_docs#endDate.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#fromProject](slots/https___idir.uta.edu_sockg_ontology_docs#fromProject.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#fromUnit](slots/https___idir.uta.edu_sockg_ontology_docs#fromUnit.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#fundedBy](slots/https___idir.uta.edu_sockg_ontology_docs#fundedBy.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasAnimalClass](slots/https___idir.uta.edu_sockg_ontology_docs#hasAnimalClass.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasAnimalSpecies](slots/https___idir.uta.edu_sockg_ontology_docs#hasAnimalSpecies.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasBroadleafOrGrass](slots/https___idir.uta.edu_sockg_ontology_docs#hasBroadleafOrGrass.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasChamberPlacement](slots/https___idir.uta.edu_sockg_ontology_docs#hasChamberPlacement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasCrop](slots/https___idir.uta.edu_sockg_ontology_docs#hasCrop.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasCultivar](slots/https___idir.uta.edu_sockg_ontology_docs#hasCultivar.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasGrazingRate](slots/https___idir.uta.edu_sockg_ontology_docs#hasGrazingRate.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasGrowthStage](slots/https___idir.uta.edu_sockg_ontology_docs#hasGrowthStage.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasHarvestedFraction](slots/https___idir.uta.edu_sockg_ontology_docs#hasHarvestedFraction.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasLossesOrDeposition](slots/https___idir.uta.edu_sockg_ontology_docs#hasLossesOrDeposition.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasMeasurement](slots/https___idir.uta.edu_sockg_ontology_docs#hasMeasurement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasOtherEvents](slots/https___idir.uta.edu_sockg_ontology_docs#hasOtherEvents.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasPesticideActiveIngredient](slots/https___idir.uta.edu_sockg_ontology_docs#hasPesticideActiveIngredient.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasPesticideTarget](slots/https___idir.uta.edu_sockg_ontology_docs#hasPesticideTarget.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasPlantFraction](slots/https___idir.uta.edu_sockg_ontology_docs#hasPlantFraction.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasProjectScenario](slots/https___idir.uta.edu_sockg_ontology_docs#hasProjectScenario.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasRotation](slots/https___idir.uta.edu_sockg_ontology_docs#hasRotation.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasSpeciesMix](slots/https___idir.uta.edu_sockg_ontology_docs#hasSpeciesMix.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasStandardDeviation](slots/https___idir.uta.edu_sockg_ontology_docs#hasStandardDeviation.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasSurfaceOrLeaching](slots/https___idir.uta.edu_sockg_ontology_docs#hasSurfaceOrLeaching.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasTillage](slots/https___idir.uta.edu_sockg_ontology_docs#hasTillage.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasTillageEvent](slots/https___idir.uta.edu_sockg_ontology_docs#hasTillageEvent.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasTiming](slots/https___idir.uta.edu_sockg_ontology_docs#hasTiming.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#hasTreatment](slots/https___idir.uta.edu_sockg_ontology_docs#hasTreatment.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#inferred](slots/https___idir.uta.edu_sockg_ontology_docs#inferred.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#irrigation](slots/https___idir.uta.edu_sockg_ontology_docs#irrigation.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#isInterpolated](slots/https___idir.uta.edu_sockg_ontology_docs#isInterpolated.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#lowerDepth](slots/https___idir.uta.edu_sockg_ontology_docs#lowerDepth.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#of](slots/https___idir.uta.edu_sockg_ontology_docs#of.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#organicManagement](slots/https___idir.uta.edu_sockg_ontology_docs#organicManagement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#startDate](slots/https___idir.uta.edu_sockg_ontology_docs#startDate.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#tileDrainage](slots/https___idir.uta.edu_sockg_ontology_docs#tileDrainage.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#treatmentHasAmendment](slots/https___idir.uta.edu_sockg_ontology_docs#treatmentHasAmendment.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#treatmentHasGrazingManagement](slots/https___idir.uta.edu_sockg_ontology_docs#treatmentHasGrazingManagement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#treatmentHasGrowthStageManagement](slots/https___idir.uta.edu_sockg_ontology_docs#treatmentHasGrowthStageManagement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#treatmentHasPlantingManagement](slots/https___idir.uta.edu_sockg_ontology_docs#treatmentHasPlantingManagement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#treatmentHasResidueManagement](slots/https___idir.uta.edu_sockg_ontology_docs#treatmentHasResidueManagement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#treatmentHasTillageManagement](slots/https___idir.uta.edu_sockg_ontology_docs#treatmentHasTillageManagement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#unitHasAmendment](slots/https___idir.uta.edu_sockg_ontology_docs#unitHasAmendment.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#unitHasGrazingManagement](slots/https___idir.uta.edu_sockg_ontology_docs#unitHasGrazingManagement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#unitHasGrowthStageManagement](slots/https___idir.uta.edu_sockg_ontology_docs#unitHasGrowthStageManagement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#unitHasPlantingManagement](slots/https___idir.uta.edu_sockg_ontology_docs#unitHasPlantingManagement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#unitHasResidueManagement](slots/https___idir.uta.edu_sockg_ontology_docs#unitHasResidueManagement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#unitHasTillageManagement](slots/https___idir.uta.edu_sockg_ontology_docs#unitHasTillageManagement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#unitUrl](slots/https___idir.uta.edu_sockg_ontology_docs#unitUrl.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#upperDepth](slots/https___idir.uta.edu_sockg_ontology_docs#upperDepth.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#usesCoverCrop](slots/https___idir.uta.edu_sockg_ontology_docs#usesCoverCrop.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#usesEquipment](slots/https___idir.uta.edu_sockg_ontology_docs#usesEquipment.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#usesFertilizerAmendment](slots/https___idir.uta.edu_sockg_ontology_docs#usesFertilizerAmendment.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#usesIrrigation](slots/https___idir.uta.edu_sockg_ontology_docs#usesIrrigation.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#usesModel](slots/https___idir.uta.edu_sockg_ontology_docs#usesModel.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#usesPlantingMethod](slots/https___idir.uta.edu_sockg_ontology_docs#usesPlantingMethod.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#usesResidueRemoval](slots/https___idir.uta.edu_sockg_ontology_docs#usesResidueRemoval.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#usesTillageMethod](slots/https___idir.uta.edu_sockg_ontology_docs#usesTillageMethod.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#usesTreatment](slots/https___idir.uta.edu_sockg_ontology_docs#usesTreatment.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#weatherAt](slots/https___idir.uta.edu_sockg_ontology_docs#weatherAt.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#withCuttingHeight](slots/https___idir.uta.edu_sockg_ontology_docs#withCuttingHeight.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#withPesticidePlacement](slots/https___idir.uta.edu_sockg_ontology_docs#withPesticidePlacement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#withPlacement](slots/https___idir.uta.edu_sockg_ontology_docs#withPlacement.md) | <br/>No occurrences of this slot in the graph.|  |
| [https___idir.uta.edu_sockg_ontology_docs#withStartStopInterval](slots/https___idir.uta.edu_sockg_ontology_docs#withStartStopInterval.md) | <br/>No occurrences of this slot in the graph.|  |
| [sdos_isPrimaryContact](slots/sdos_isPrimaryContact.md) | <br/>| 140 |
| [sdos_role](slots/sdos_role.md) | <br/>| 151 |
| [spatial_connectedTo](slots/spatial_connectedTo.md) | <br/>| 2322 |
| [spatial_spatiallyRelatedTo](slots/spatial_spatiallyRelatedTo.md) | <br/>No occurrences of this slot in the graph.|  |









## IRI prefixes

* bibo: http://purl.org/ontology/bibo/
* coso: http://w3id.org/coso/v1/contaminoso#
* dcgeoid: https://datacommons.org/browser/geoId/
* dct: http://purl.org/dc/terms/
* geo: http://www.opengis.net/ont/geosparql#
* kwgo: http://stko-kwg.geog.ucsb.edu/lod/ontology/
* kwgr: http://stko-kwg.geog.ucsb.edu/lod/resource/
* linkml: https://w3id.org/linkml/
* okn: https://purl.org/okn/
* okns: https://purl.org/okn/schema/
* owl: http://www.w3.org/2002/07/owl#
* qudt: http://qudt.org/schema/qudt/
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* sdos: https://schema.org/
* spatial: http://purl.org/spatialai/spatial/spatial-full#
* xsd: http://www.w3.org/2001/XMLSchema#
