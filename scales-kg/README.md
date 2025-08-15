# scales





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
SkosCollection {

}
SkosConcept {

}
SkosConceptScheme {

}
SkosOrderedCollection {

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
Jxdm72Arrest {
    date niem50_ActivityDate  
    string niem50_LocaleCensusBlockID  
}
Jxdm72ArrestCharge {
    string jxdm72_DrugCategoryCode  
    string jxdm72_ChargeDispositionCategoryText  
    string jxdm72_ChargeText  
    string nibrs_NIBRSReportCategoryCode  
    string nibrs_OffenseUCRCode  
    string jxdm72_ChargeSeverityLevelCode  
}
Jxdm72Attorney {
    string jxdm72_CaseOfficialRoleText  
    string niem50_PersonFullName  
    string niem50_ContactMailingAddress  
}
Jxdm72Booking {
    date niem50_ActivityDate  
}
Jxdm72BookingFacility {
    string http___release.niem.gov_niem_codes_fips_5.0_CountyCode  
    string niem50_CourtPostalCode  
    string niem50_FacilityName  
}
Jxdm72CaseDefendantParty {
    string niem50_PersonFullName  
    string jxdm72_ParticipantRoleCategoryText  
    uri scales_isInstanceOfEntity  
    string scales_hasHighestOffenseLevelOpening  
    string niem50_PersonRaceText  
    string scales_hasHighestOffenseLevelTerminated  
    string jxdm72_PersonSexCode  
    string scales_hasExtraInfo  
    string niem50_EntityName  
}
Jxdm72CaseDefenseAttorney {
    string jxdm72_CaseOfficialRoleText  
    string niem50_PersonFullName  
    string niem50_ContactMailingAddress  
}
Jxdm72CaseInitiatingAttorney {
    string jxdm72_CaseOfficialRoleText  
    string niem50_ContactMailingAddress  
    string niem50_PersonFullName  
}
Jxdm72CaseInitiatingParty {
    string scales_hasExtraInfo  
    string jxdm72_ParticipantRoleCategoryText  
    string niem50_EntityName  
}
Jxdm72CaseJudge {
    string niem50_PersonFullName  
}
Jxdm72Charge {
    string jxdm72_DrugCategoryCode  
    string jxdm72_ChargeDisposition  
    string jxdm72_ChargeText  
    string jxdm72_ChargeSequenceID  
    string nibrs_NIBRSReportCategoryCode  
    string nibrs_OffenseUCRCode  
    string jxdm72_ChargeSeverityLevelCode  
    string scales_hasChargeType  
    float jxdm72_BondAmount  
    string jxdm72_BondType  
}
Jxdm72Court {
    string niem50_CourtName  
    string jxdm72_CourtCategoryCode  
    string jxdm72_CourtName  
    string scales_isInCircuit  
    string http___release.niem.gov_niem_codes_fips_5.0_CountyCode  
    string niem50_CourtPostalCode  
    string niem50_AddressPostalCode  
}
Jxdm72Judge {
    string niem50_PersonFullName  
    string scales_appointedByParty  
    string niem50_PersonRaceText  
    string niem50_PersonSexText  
    double scales_hasFJCNodeID  
    string jxdm72_JudicialOfficialCategoryText  
    date scales_hasCommissionDate  
    string scales_hasUVAJudgeDirID  
}
Jxdm72LawEnforcementOfficial {
    string niem50_PersonID  
}
Jxdm72RegisterAction {
    string jxdm72_RegisterActionDescriptionText  
    uri scales_DocketEntry  
    date jxdm72_RegisterActionDate  
}
Jxdm72RegisterOfActions {
    uri scales_DocketEntry  
}
Jxdm72Release {
    date niem50_ActivityDate  
}
Jxdm72Sentence {
    string jxdm72_SentenceDescriptionText  
}
Jxdm72SentenceTerm {

}
Niem50Person {
    string niem50_PersonRaceText  
    string jxdm72_PersonSexCode  
}
ScalesCivilCase {
    string niem50_JurisdictionText  
    string scales_hasIdbDocket  
    double scales_hasIdbJudgment  
    double scales_hasIdbTapeyear  
    date niem50_StartDate  
    double scales_hasIdbCircuit  
    string scales_hasIdbNos  
    string scales_hasIdbDistrict  
    double scales_hasIdbResidenc  
    string scales_hasIdbPretrial  
    string scales_hasIdbDef  
    double scales_hasIdbDemanded  
    boolean scales_hasIdbIs_stub  
    string scales_hasIdbMdldock  
    datetime scales_hasIdbFiledate  
    string scales_hasIdbTrialend  
    datetime scales_hasIdbTermdate  
    string niem50_CaseSubCategoryText  
    string scales_hasIdbSection  
    string jxdm72_StatuteKeywordText  
    integer scales_hasIdbJury  
    string scales_hasIdbJury  
    date niem50_EndDate  
    uri jxdm72_CaseJudge  
    double scales_hasIdbJuris  
    double scales_hasIdbDisp  
    string scales_hasIdbIfp  
    string scales_hasIdbTrmarb  
    string scales_hasIdbStatuscd  
    double scales_hasIdbProse  
    string scales_hasIdbOffice  
    double scales_hasIdbTrclact  
    double scales_hasIdbOrigin  
    double scales_hasIdbTransdoc  
    string niem50_CaseGeneralCategoryText  
    string scales_hasIdbTransorg  
    uri scales_hasRelatedCase  
    string niem50_CaseDocketID  
    double scales_hasIdbCounty  
    double scales_hasIdbAmtrec  
    double scales_hasIdbProcprog  
    double scales_hasIdbNoj  
    string scales_hasIdbTitl  
    string scales_hasIdbArbit  
    string scales_hasIdbSubsect  
    string scales_hasIdbDjoined  
    string scales_hasIdbTransoff  
    string scales_hasIdbFdateuse  
    double scales_hasIdbClassact  
    string scales_hasIdbTribegan  
    string scales_hasIdbTdateuse  
    string niem50_StatusDescriptionText  
    string jxdm72_CaseCourt  
    string scales_hasIdbTransdat  
    string scales_hasIdbPlt  
}
ScalesCriminalCase {
    string scales_hasIdbFtitle4  
    string scales_hasIdbCaslgky  
    double scales_hasIdbFofflvl1  
    double scales_hasIdbFinetot  
    integer scales_hasIdbPriscd5  
    string scales_hasIdbPriscd5  
    double scales_hasIdbCircuit  
    double scales_hasIdbFofflvl3  
    double scales_hasIdbFofflvl4  
    double scales_hasIdbCtfil  
    string scales_hasIdbFtitle5  
    double scales_hasIdbReopseq  
    integer scales_hasIdbFsev5  
    string scales_hasIdbFsev5  
    string scales_hasIdbProcdate  
    datetime scales_hasIdbTermdate  
    double scales_hasIdbFoffcd3  
    integer scales_hasIdbTermoff  
    string scales_hasIdbTermoff  
    double scales_hasIdbProbmon5  
    double scales_hasIdbFineamt1  
    string scales_hasIdbPriscd3  
    double scales_hasIdbInt3  
    double scales_hasIdbFofflvl2  
    double scales_hasIdbDisp2  
    string scales_hasIdbTtitle3  
    string scales_hasIdbStatuscd  
    double scales_hasIdbCtpn  
    double scales_hasIdbSupvrel1  
    string scales_hasIdbOffice  
    double scales_hasIdbSupvrel3  
    double scales_hasIdbD2foffcd2  
    integer scales_hasIdbTsev4  
    string scales_hasIdbTsev4  
    double scales_hasIdbProccd  
    string scales_hasIdbPriscd1  
    double scales_hasIdbCounty  
    double scales_hasIdbFineamt3  
    double scales_hasIdbPristim3  
    integer scales_hasIdbProbcd2  
    string scales_hasIdbProbcd2  
    string jxdm72_CaseCourt  
    double scales_hasIdbMagdock  
    integer scales_hasIdbFsev4  
    string scales_hasIdbFsev4  
    double scales_hasIdbMagdef  
    double scales_hasIdbTrandef  
    double scales_hasIdbTapeyear  
    string scales_hasIdbTypemag  
    double scales_hasIdbFoffcd1  
    integer scales_hasIdbProbcd3  
    string scales_hasIdbProbcd3  
    double scales_hasIdbCtfilr  
    double scales_hasIdbFcounsel  
    double scales_hasIdbFiscalyr  
    string scales_hasIdbTsev1  
    double scales_hasIdbSupvrel2  
    double scales_hasIdbToffcd1  
    double scales_hasIdbDisp1  
    double scales_hasIdbTofflvl4  
    double scales_hasIdbD2foffcd3  
    double scales_hasIdbPristim4  
    double scales_hasIdbCttrwor  
    integer scales_hasIdbTypetrn  
    string scales_hasIdbTypetrn  
    string scales_hasIdbFgstrtdate  
    double scales_hasIdbPristot  
    double scales_hasIdbDisp4  
    double scales_hasIdbProbmon4  
    double scales_hasIdbD2toffcd2  
    double scales_hasIdbVer  
    double scales_hasIdbCtfilwor  
    double scales_hasIdbPristim1  
    integer scales_hasIdbProbcd4  
    string scales_hasIdbProbcd4  
    string scales_hasIdbFtitle2  
    double scales_hasIdbProbtot  
    string scales_hasIdbAppcd  
    double scales_hasIdbD2foffcd4  
    double scales_hasIdbFoffcd2  
    string scales_hasIdbTtitle4  
    uri scales_hasRelatedCase  
    string niem50_CaseDocketID  
    double scales_hasIdbSupvrel5  
    double scales_hasIdbCtfiltrn  
    string scales_hasIdbTtitle1  
    double scales_hasIdbProbmon3  
    integer scales_hasIdbTsev2  
    string scales_hasIdbTsev2  
    double scales_hasIdbD2toffcd5  
    string scales_hasIdbDocket  
    string scales_hasIdbFtitle3  
    double scales_hasIdbPristim5  
    double scales_hasIdbTofflvl1  
    string scales_hasIdbDistrict  
    double scales_hasIdbToffcd2  
    string scales_hasIdbFsev2  
    integer scales_hasIdbTranoff  
    double scales_hasIdbTcounsel  
    double scales_hasIdbD2foffcd1  
    string scales_hasIdbDispdate  
    string scales_hasIdbFtitle1  
    double scales_hasIdbToffcd3  
    double scales_hasIdbFoffcd4  
    string scales_hasIdbAppdate  
    integer scales_hasIdbProbcd5  
    string scales_hasIdbProbcd5  
    string scales_hasIdbTypereg  
    date niem50_EndDate  
    integer scales_hasIdbTrandist  
    string scales_hasIdbTrandist  
    integer scales_hasIdbTsev5  
    string scales_hasIdbTsev5  
    integer scales_hasIdbTtitle5  
    string scales_hasIdbTtitle5  
    double scales_hasIdbInt1  
    string niem50_CaseGeneralCategoryText  
    string scales_hasIdbDeflgky  
    integer scales_hasIdbTsev3  
    string scales_hasIdbTsev3  
    double scales_hasIdbCttrtrn  
    double scales_hasIdbDisp3  
    double scales_hasIdbFineamt5  
    double scales_hasIdbFoffcd5  
    string scales_hasIdbProbcd1  
    double scales_hasIdbD2foffcd5  
    double scales_hasIdbCtpnwof  
    string scales_hasIdbFugstat  
    string niem50_StatusDescriptionText  
    double scales_hasIdbTofflvl2  
    double scales_hasIdbTofflvl5  
    double scales_hasIdbDefno  
    string niem50_JurisdictionText  
    double scales_hasIdbCttrr  
    double scales_hasIdbProbmon1  
    double scales_hasIdbTofflvl3  
    string scales_hasIdbPriscd2  
    date niem50_StartDate  
    double scales_hasIdbSupvrel4  
    string scales_hasIdbFsev1  
    double scales_hasIdbInt2  
    integer scales_hasIdbPriscd4  
    string scales_hasIdbPriscd4  
    boolean scales_hasIdbIs_stub  
    datetime scales_hasIdbFiledate  
    double scales_hasIdbToffcd5  
    double scales_hasIdbFineamt4  
    double scales_hasIdbDisp5  
    double scales_hasIdbD2toffcd4  
    double scales_hasIdbTrandock  
    double scales_hasIdbCttr  
    string scales_hasIdbUpdate  
    uri jxdm72_CaseJudge  
    double scales_hasIdbFofflvl5  
    string scales_hasIdbLoaddate  
    double scales_hasIdbD2toffcd3  
    string scales_hasIdbFgenddate  
    string scales_hasIdbTtitle2  
    double scales_hasIdbFineamt2  
    double scales_hasIdbPristim2  
    double scales_hasIdbCtdef  
    double scales_hasIdbToffcd4  
    double scales_hasIdbProbmon2  
    string scales_hasIdbSentdate  
    string scales_hasIdbFsev3  
    double scales_hasIdbD2toffcd1  
}
ScalesFirm {
    string niem50_OrganizationName  
}
ScalesParty {
    string niem50_PersonFullName  
    string jxdm72_ParticipantRoleCategoryText  
    uri scales_isInstanceOfEntity  
    string scales_hasExtraInfo  
    string niem50_EntityName  
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
TimeDayOfWeek ||--|o RdfsLiteral : "rdfs_label"
TimeTemporalUnit ||--|o RdfsLiteral : "rdfs_label"
Jxdm72Arrest ||--|o Jxdm72LawEnforcementOfficial : "jxdm72_ArrestOfficial"
Jxdm72Attorney ||--|o ScalesFirm : "scales_Firm"
Jxdm72Booking ||--|o Jxdm72BookingFacility : "jxdm72_BookingFacility"
Jxdm72Booking ||--|o ScalesCriminalCase : "scales_BookingCase"
Jxdm72Booking ||--|o Jxdm72Release : "jxdm72_BookingRelease"
Jxdm72CaseDefendantParty ||--|o Jxdm72Charge : "jxdm72_PersonCharge"
Jxdm72CaseDefendantParty ||--|o Jxdm72CaseDefenseAttorney : "jxdm72_CaseDefenseAttorney"
Jxdm72CaseDefendantParty ||--|o Jxdm72Booking : "jxdm72_SubjectBooking"
Jxdm72CaseDefenseAttorney ||--|o ScalesFirm : "scales_Firm"
Jxdm72CaseInitiatingAttorney ||--|o ScalesFirm : "scales_Firm"
Jxdm72CaseInitiatingParty ||--|o Jxdm72CaseInitiatingAttorney : "jxdm72_CaseInitiatingAttorney"
Jxdm72Charge ||--|o Jxdm72Booking : "jxdm72_ChargeBooking"
Jxdm72Charge ||--|o Jxdm72CaseDefendantParty : "jxdm72_ChargeSubject"
Jxdm72Charge ||--|o Jxdm72Sentence : "jxdm72_ChargeSentence"
Jxdm72RegisterAction ||--|o Jxdm72RegisterAction : "scales_DocketEntry"
Jxdm72RegisterAction ||--|o Jxdm72Sentence : "jxdm72_Sentence"
Jxdm72RegisterOfActions ||--|o Jxdm72RegisterAction : "scales_DocketEntry"
Jxdm72Sentence ||--|o Jxdm72SentenceTerm : "jxdm72_SentenceTerm"
Jxdm72SentenceTerm ||--|o XsdDuration : "jxdm72_TermDuration"
Niem50Person ||--|o XsdGYear : "scales_BirthYear"
ScalesCivilCase ||--|o ScalesCivilCase : "scales_hasMemberCase"
ScalesCivilCase ||--|o Jxdm72CaseInitiatingParty : "jxdm72_CaseInitiatingParty"
ScalesCivilCase ||--|o ScalesParty : "jxdm72_CaseInitiatingParty"
ScalesCivilCase ||--|o Jxdm72CaseJudge : "jxdm72_CaseJudge"
ScalesCivilCase ||--|o Jxdm72RegisterOfActions : "scales_DocketTable"
ScalesCivilCase ||--|o Jxdm72RegisterAction : "scales_DocketTable"
ScalesCivilCase ||--|o ScalesParty : "scales_Party"
ScalesCivilCase ||--|o ScalesCivilCase : "scales_hasRelatedCase"
ScalesCivilCase ||--|o ScalesCriminalCase : "scales_hasRelatedCase"
ScalesCivilCase ||--|o Jxdm72CaseDefendantParty : "jxdm72_CaseDefendantParty"
ScalesCivilCase ||--|o ScalesParty : "jxdm72_CaseDefendantParty"
ScalesCivilCase ||--|o Jxdm72Court : "jxdm72_CaseCourt"
ScalesCriminalCase ||--|o Jxdm72Court : "jxdm72_CaseCourt"
ScalesCriminalCase ||--|o Jxdm72Charge : "jxdm72_CaseCharge"
ScalesCriminalCase ||--|o Jxdm72CaseInitiatingParty : "jxdm72_CaseInitiatingParty"
ScalesCriminalCase ||--|o ScalesParty : "jxdm72_CaseInitiatingParty"
ScalesCriminalCase ||--|o Jxdm72RegisterOfActions : "scales_DocketTable"
ScalesCriminalCase ||--|o Jxdm72RegisterAction : "scales_DocketTable"
ScalesCriminalCase ||--|o ScalesCivilCase : "scales_hasRelatedCase"
ScalesCriminalCase ||--|o ScalesCriminalCase : "scales_hasRelatedCase"
ScalesCriminalCase ||--|o ScalesCivilCase : "scales_hasMemberCase"
ScalesCriminalCase ||--|o Jxdm72CaseJudge : "jxdm72_CaseJudge"
ScalesCriminalCase ||--|o ScalesParty : "scales_Party"
ScalesCriminalCase ||--|o Jxdm72CaseDefendantParty : "jxdm72_CaseDefendantParty"
ScalesCriminalCase ||--|o ScalesParty : "jxdm72_CaseDefendantParty"
ScalesParty ||--|o Jxdm72Attorney : "jxdm72_Attorney"
ScalesParty ||--|o Jxdm72Charge : "jxdm72_PersonCharge"
ScalesParty ||--|o Jxdm72Sentence : "jxdm72_Sentence"

```



## Imports


* okns:time
* linkml:types



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [Jxdm72Arrest](classes/Jxdm72Arrest.md) | None<br/>| 83347 | 
| [Jxdm72ArrestCharge](classes/Jxdm72ArrestCharge.md) | None<br/>| 137904 | 
| [Jxdm72Attorney](classes/Jxdm72Attorney.md) | None<br/>| 537560 | 
| [Jxdm72Booking](classes/Jxdm72Booking.md) | None<br/>| 363466 | 
| [Jxdm72BookingFacility](classes/Jxdm72BookingFacility.md) | None<br/>| 1 | 
| [Jxdm72CaseDefendantParty](classes/Jxdm72CaseDefendantParty.md) | None<br/>| 2949712 | 
| [Jxdm72CaseDefenseAttorney](classes/Jxdm72CaseDefenseAttorney.md) | None<br/>| 2823772 | 
| [Jxdm72CaseInitiatingAttorney](classes/Jxdm72CaseInitiatingAttorney.md) | None<br/>| 2755161 | 
| [Jxdm72CaseInitiatingParty](classes/Jxdm72CaseInitiatingParty.md) | None<br/>| 1337860 | 
| [Jxdm72CaseJudge](classes/Jxdm72CaseJudge.md) | None<br/>| 3207790 | 
| [Jxdm72Charge](classes/Jxdm72Charge.md) | None<br/>| 3285242 | 
| [Jxdm72Court](classes/Jxdm72Court.md) | None<br/>| 95 | 
| [Jxdm72Judge](classes/Jxdm72Judge.md) | None<br/>| 5385 | 
| [Jxdm72LawEnforcementOfficial](classes/Jxdm72LawEnforcementOfficial.md) | None<br/>| 2016 | 
| [Jxdm72RegisterAction](classes/Jxdm72RegisterAction.md) | None<br/>| 28776887 | 
| [Jxdm72RegisterOfActions](classes/Jxdm72RegisterOfActions.md) | None<br/>| 4160501 | 
| [Jxdm72Release](classes/Jxdm72Release.md) | None<br/>| 347084 | 
| [Jxdm72Sentence](classes/Jxdm72Sentence.md) | None<br/>| 356094 | 
| [Jxdm72SentenceTerm](classes/Jxdm72SentenceTerm.md) | None<br/>| 462 | 
| [Niem50Person](classes/Niem50Person.md) | None<br/>| 137904 | 
| [ScalesCivilCase](classes/ScalesCivilCase.md) | None<br/>| 1795343 | 
| [ScalesCriminalCase](classes/ScalesCriminalCase.md) | None<br/>| 2368748 | 
| [ScalesFirm](classes/ScalesFirm.md) | None<br/>| 2929549 | 
| [ScalesParty](classes/ScalesParty.md) | None<br/>| 7362525 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [http___release.niem.gov_niem_codes_fips_5.0_CountyCode](slots/http___release.niem.gov_niem_codes_fips_5.0_CountyCode.md) | <br/>| 3037 |
| [jxdm72_ArrestOfficial](slots/jxdm72_ArrestOfficial.md) | <br/>| 84716 |
| [jxdm72_Attorney](slots/jxdm72_Attorney.md) | <br/>| 537560 |
| [jxdm72_BondAmount](slots/jxdm72_BondAmount.md) | <br/>| 99402 |
| [jxdm72_BondType](slots/jxdm72_BondType.md) | <br/>| 105383 |
| [jxdm72_BookingFacility](slots/jxdm72_BookingFacility.md) | <br/>| 363466 |
| [jxdm72_BookingRelease](slots/jxdm72_BookingRelease.md) | <br/>| 347084 |
| [jxdm72_Case](slots/jxdm72_Case.md) | <br/>| 864700 |
| [jxdm72_CaseCharge](slots/jxdm72_CaseCharge.md) | <br/>| 607725 |
| [jxdm72_CaseCourt](slots/jxdm72_CaseCourt.md) | <br/>| 4164091 |
| [jxdm72_CaseDefendantParty](slots/jxdm72_CaseDefendantParty.md) | <br/>| 6231746 |
| [jxdm72_CaseDefenseAttorney](slots/jxdm72_CaseDefenseAttorney.md) | <br/>| 2823772 |
| [jxdm72_CaseInitiatingAttorney](slots/jxdm72_CaseInitiatingAttorney.md) | <br/>| 2755161 |
| [jxdm72_CaseInitiatingParty](slots/jxdm72_CaseInitiatingParty.md) | <br/>| 4892601 |
| [jxdm72_CaseJudge](slots/jxdm72_CaseJudge.md) | <br/>| 4424121 |
| [jxdm72_CaseOfficialRoleText](slots/jxdm72_CaseOfficialRoleText.md) | <br/>| 1713199 |
| [jxdm72_ChargeBooking](slots/jxdm72_ChargeBooking.md) | <br/>| 363466 |
| [jxdm72_ChargeDisposition](slots/jxdm72_ChargeDisposition.md) | <br/>| 389366 |
| [jxdm72_ChargeDispositionCategoryText](slots/jxdm72_ChargeDispositionCategoryText.md) | <br/>| 138625 |
| [jxdm72_ChargeSentence](slots/jxdm72_ChargeSentence.md) | <br/>| 244007 |
| [jxdm72_ChargeSequenceID](slots/jxdm72_ChargeSequenceID.md) | <br/>| 389366 |
| [jxdm72_ChargeSeverityLevelCode](slots/jxdm72_ChargeSeverityLevelCode.md) | <br/>| 495206 |
| [jxdm72_ChargeSubject](slots/jxdm72_ChargeSubject.md) | <br/>| 363466 |
| [jxdm72_ChargeText](slots/jxdm72_ChargeText.md) | <br/>| 3442649 |
| [jxdm72_CourtCategoryCode](slots/jxdm72_CourtCategoryCode.md) | <br/>| 95 |
| [jxdm72_CourtName](slots/jxdm72_CourtName.md) | <br/>| 94 |
| [jxdm72_DrugCategoryCode](slots/jxdm72_DrugCategoryCode.md) | <br/>| 133125 |
| [jxdm72_JudicialOfficialCategoryText](slots/jxdm72_JudicialOfficialCategoryText.md) | <br/>| 5385 |
| [jxdm72_ParticipantRoleCategoryText](slots/jxdm72_ParticipantRoleCategoryText.md) | <br/>| 11629280 |
| [jxdm72_PersonCharge](slots/jxdm72_PersonCharge.md) | <br/>| 3340425 |
| [jxdm72_PersonSexCode](slots/jxdm72_PersonSexCode.md) | <br/>| 500447 |
| [jxdm72_RegisterActionDate](slots/jxdm72_RegisterActionDate.md) | <br/>| 58361062 |
| [jxdm72_RegisterActionDescriptionText](slots/jxdm72_RegisterActionDescriptionText.md) | <br/>| 58359696 |
| [jxdm72_Sentence](slots/jxdm72_Sentence.md) | <br/>| 675670 |
| [jxdm72_SentenceDescriptionText](slots/jxdm72_SentenceDescriptionText.md) | <br/>| 356094 |
| [jxdm72_SentenceTerm](slots/jxdm72_SentenceTerm.md) | <br/>| 356094 |
| [jxdm72_StatuteKeywordText](slots/jxdm72_StatuteKeywordText.md) | <br/>| 718593 |
| [jxdm72_SubjectBooking](slots/jxdm72_SubjectBooking.md) | <br/>| 363466 |
| [jxdm72_TermDuration](slots/jxdm72_TermDuration.md) | <br/>| 462 |
| [nibrs_NIBRSReportCategoryCode](slots/nibrs_NIBRSReportCategoryCode.md) | <br/>| 1670109 |
| [nibrs_OffenseUCRCode](slots/nibrs_OffenseUCRCode.md) | <br/>| 1150517 |
| [niem50_ActivityDate](slots/niem50_ActivityDate.md) | <br/>| 904252 |
| [niem50_AddressPostalCode](slots/niem50_AddressPostalCode.md) | <br/>| 40932 |
| [niem50_AdministrativeID](slots/niem50_AdministrativeID.md) | <br/>| 30414852 |
| [niem50_CaseDocketID](slots/niem50_CaseDocketID.md) | <br/>| 4164091 |
| [niem50_CaseGeneralCategoryText](slots/niem50_CaseGeneralCategoryText.md) | <br/>| 4072490 |
| [niem50_CaseSubCategoryText](slots/niem50_CaseSubCategoryText.md) | <br/>| 1863523 |
| [niem50_ContactMailingAddress](slots/niem50_ContactMailingAddress.md) | <br/>| 3083592 |
| [niem50_CourtName](slots/niem50_CourtName.md) | <br/>| 1 |
| [niem50_CourtPostalCode](slots/niem50_CourtPostalCode.md) | <br/>| 2 |
| [niem50_EndDate](slots/niem50_EndDate.md) | <br/>| 3828523 |
| [niem50_EntityName](slots/niem50_EntityName.md) | <br/>| 4241878 |
| [niem50_FacilityName](slots/niem50_FacilityName.md) | <br/>| 1 |
| [niem50_JurisdictionText](slots/niem50_JurisdictionText.md) | <br/>| 3926555 |
| [niem50_LocaleCensusBlockID](slots/niem50_LocaleCensusBlockID.md) | <br/>| 71598 |
| [niem50_OrganizationName](slots/niem50_OrganizationName.md) | <br/>| 2929547 |
| [niem50_PersonFullName](slots/niem50_PersonFullName.md) | <br/>| 17954252 |
| [niem50_PersonID](slots/niem50_PersonID.md) | <br/>| 2020 |
| [niem50_PersonRaceText](slots/niem50_PersonRaceText.md) | <br/>| 504197 |
| [niem50_PersonSexText](slots/niem50_PersonSexText.md) | <br/>| 3762 |
| [niem50_StartDate](slots/niem50_StartDate.md) | <br/>| 4072490 |
| [niem50_StatusDescriptionText](slots/niem50_StatusDescriptionText.md) | <br/>| 4072490 |
| [scales_appointedByParty](slots/scales_appointedByParty.md) | <br/>| 3912 |
| [scales_assignedToDefendant](slots/scales_assignedToDefendant.md) | <br/>| 53962 |
| [scales_BirthYear](slots/scales_BirthYear.md) | <br/>| 137257 |
| [scales_BookingCase](slots/scales_BookingCase.md) | <br/>| 218359 |
| [scales_DocketEntry](slots/scales_DocketEntry.md) | <br/>| 58334996 |
| [scales_DocketTable](slots/scales_DocketTable.md) | <br/>| 4160501 |
| [scales_Firm](slots/scales_Firm.md) | <br/>| 2929549 |
| [scales_hasChargeType](slots/scales_hasChargeType.md) | <br/>| 389366 |
| [scales_hasCommissionDate](slots/scales_hasCommissionDate.md) | <br/>| 4257 |
| [scales_hasExtraInfo](slots/scales_hasExtraInfo.md) | <br/>| 861769 |
| [scales_hasFJCNodeID](slots/scales_hasFJCNodeID.md) | <br/>| 3855 |
| [scales_hasHighestOffenseLevelOpening](slots/scales_hasHighestOffenseLevelOpening.md) | <br/>| 159337 |
| [scales_hasHighestOffenseLevelTerminated](slots/scales_hasHighestOffenseLevelTerminated.md) | <br/>| 69523 |
| [scales_hasIdbAmtrec](slots/scales_hasIdbAmtrec.md) | <br/>| 702501 |
| [scales_hasIdbAppcd](slots/scales_hasIdbAppcd.md) | <br/>| 121785 |
| [scales_hasIdbAppdate](slots/scales_hasIdbAppdate.md) | <br/>| 121785 |
| [scales_hasIdbArbit](slots/scales_hasIdbArbit.md) | <br/>| 702501 |
| [scales_hasIdbCaslgky](slots/scales_hasIdbCaslgky.md) | <br/>| 121785 |
| [scales_hasIdbCircuit](slots/scales_hasIdbCircuit.md) | <br/>| 824286 |
| [scales_hasIdbClassact](slots/scales_hasIdbClassact.md) | <br/>| 702501 |
| [scales_hasIdbCounty](slots/scales_hasIdbCounty.md) | <br/>| 824286 |
| [scales_hasIdbCtdef](slots/scales_hasIdbCtdef.md) | <br/>| 121785 |
| [scales_hasIdbCtfil](slots/scales_hasIdbCtfil.md) | <br/>| 121785 |
| [scales_hasIdbCtfilr](slots/scales_hasIdbCtfilr.md) | <br/>| 121785 |
| [scales_hasIdbCtfiltrn](slots/scales_hasIdbCtfiltrn.md) | <br/>| 121785 |
| [scales_hasIdbCtfilwor](slots/scales_hasIdbCtfilwor.md) | <br/>| 121785 |
| [scales_hasIdbCtpn](slots/scales_hasIdbCtpn.md) | <br/>| 121785 |
| [scales_hasIdbCtpnwof](slots/scales_hasIdbCtpnwof.md) | <br/>| 121785 |
| [scales_hasIdbCttr](slots/scales_hasIdbCttr.md) | <br/>| 121785 |
| [scales_hasIdbCttrr](slots/scales_hasIdbCttrr.md) | <br/>| 121785 |
| [scales_hasIdbCttrtrn](slots/scales_hasIdbCttrtrn.md) | <br/>| 121785 |
| [scales_hasIdbCttrwor](slots/scales_hasIdbCttrwor.md) | <br/>| 121785 |
| [scales_hasIdbD2foffcd1](slots/scales_hasIdbD2foffcd1.md) | <br/>| 121785 |
| [scales_hasIdbD2foffcd2](slots/scales_hasIdbD2foffcd2.md) | <br/>| 121785 |
| [scales_hasIdbD2foffcd3](slots/scales_hasIdbD2foffcd3.md) | <br/>| 121785 |
| [scales_hasIdbD2foffcd4](slots/scales_hasIdbD2foffcd4.md) | <br/>| 121785 |
| [scales_hasIdbD2foffcd5](slots/scales_hasIdbD2foffcd5.md) | <br/>| 121785 |
| [scales_hasIdbD2toffcd1](slots/scales_hasIdbD2toffcd1.md) | <br/>| 121785 |
| [scales_hasIdbD2toffcd2](slots/scales_hasIdbD2toffcd2.md) | <br/>| 121785 |
| [scales_hasIdbD2toffcd3](slots/scales_hasIdbD2toffcd3.md) | <br/>| 121785 |
| [scales_hasIdbD2toffcd4](slots/scales_hasIdbD2toffcd4.md) | <br/>| 121785 |
| [scales_hasIdbD2toffcd5](slots/scales_hasIdbD2toffcd5.md) | <br/>| 121785 |
| [scales_hasIdbDef](slots/scales_hasIdbDef.md) | <br/>| 702501 |
| [scales_hasIdbDeflgky](slots/scales_hasIdbDeflgky.md) | <br/>| 121785 |
| [scales_hasIdbDefno](slots/scales_hasIdbDefno.md) | <br/>| 121785 |
| [scales_hasIdbDemanded](slots/scales_hasIdbDemanded.md) | <br/>| 702501 |
| [scales_hasIdbDisp](slots/scales_hasIdbDisp.md) | <br/>| 702501 |
| [scales_hasIdbDisp1](slots/scales_hasIdbDisp1.md) | <br/>| 121785 |
| [scales_hasIdbDisp2](slots/scales_hasIdbDisp2.md) | <br/>| 121785 |
| [scales_hasIdbDisp3](slots/scales_hasIdbDisp3.md) | <br/>| 121785 |
| [scales_hasIdbDisp4](slots/scales_hasIdbDisp4.md) | <br/>| 121785 |
| [scales_hasIdbDisp5](slots/scales_hasIdbDisp5.md) | <br/>| 121785 |
| [scales_hasIdbDispdate](slots/scales_hasIdbDispdate.md) | <br/>| 121785 |
| [scales_hasIdbDistrict](slots/scales_hasIdbDistrict.md) | <br/>| 824286 |
| [scales_hasIdbDjoined](slots/scales_hasIdbDjoined.md) | <br/>| 275529 |
| [scales_hasIdbDocket](slots/scales_hasIdbDocket.md) | <br/>| 824286 |
| [scales_hasIdbFcounsel](slots/scales_hasIdbFcounsel.md) | <br/>| 121785 |
| [scales_hasIdbFdateuse](slots/scales_hasIdbFdateuse.md) | <br/>| 702501 |
| [scales_hasIdbFgenddate](slots/scales_hasIdbFgenddate.md) | <br/>| 121785 |
| [scales_hasIdbFgstrtdate](slots/scales_hasIdbFgstrtdate.md) | <br/>| 121785 |
| [scales_hasIdbFiledate](slots/scales_hasIdbFiledate.md) | <br/>| 824286 |
| [scales_hasIdbFineamt1](slots/scales_hasIdbFineamt1.md) | <br/>| 121785 |
| [scales_hasIdbFineamt2](slots/scales_hasIdbFineamt2.md) | <br/>| 121785 |
| [scales_hasIdbFineamt3](slots/scales_hasIdbFineamt3.md) | <br/>| 121785 |
| [scales_hasIdbFineamt4](slots/scales_hasIdbFineamt4.md) | <br/>| 121785 |
| [scales_hasIdbFineamt5](slots/scales_hasIdbFineamt5.md) | <br/>| 121785 |
| [scales_hasIdbFinetot](slots/scales_hasIdbFinetot.md) | <br/>| 121785 |
| [scales_hasIdbFiscalyr](slots/scales_hasIdbFiscalyr.md) | <br/>| 121785 |
| [scales_hasIdbFoffcd1](slots/scales_hasIdbFoffcd1.md) | <br/>| 121785 |
| [scales_hasIdbFoffcd2](slots/scales_hasIdbFoffcd2.md) | <br/>| 121785 |
| [scales_hasIdbFoffcd3](slots/scales_hasIdbFoffcd3.md) | <br/>| 121785 |
| [scales_hasIdbFoffcd4](slots/scales_hasIdbFoffcd4.md) | <br/>| 121785 |
| [scales_hasIdbFoffcd5](slots/scales_hasIdbFoffcd5.md) | <br/>| 121785 |
| [scales_hasIdbFofflvl1](slots/scales_hasIdbFofflvl1.md) | <br/>| 121785 |
| [scales_hasIdbFofflvl2](slots/scales_hasIdbFofflvl2.md) | <br/>| 121785 |
| [scales_hasIdbFofflvl3](slots/scales_hasIdbFofflvl3.md) | <br/>| 121785 |
| [scales_hasIdbFofflvl4](slots/scales_hasIdbFofflvl4.md) | <br/>| 121785 |
| [scales_hasIdbFofflvl5](slots/scales_hasIdbFofflvl5.md) | <br/>| 121785 |
| [scales_hasIdbFsev1](slots/scales_hasIdbFsev1.md) | <br/>| 121785 |
| [scales_hasIdbFsev2](slots/scales_hasIdbFsev2.md) | <br/>| 121785 |
| [scales_hasIdbFsev3](slots/scales_hasIdbFsev3.md) | <br/>| 121785 |
| [scales_hasIdbFsev4](slots/scales_hasIdbFsev4.md) | <br/>| 121785 |
| [scales_hasIdbFsev5](slots/scales_hasIdbFsev5.md) | <br/>| 121785 |
| [scales_hasIdbFtitle1](slots/scales_hasIdbFtitle1.md) | <br/>| 121785 |
| [scales_hasIdbFtitle2](slots/scales_hasIdbFtitle2.md) | <br/>| 121785 |
| [scales_hasIdbFtitle3](slots/scales_hasIdbFtitle3.md) | <br/>| 121785 |
| [scales_hasIdbFtitle4](slots/scales_hasIdbFtitle4.md) | <br/>| 121785 |
| [scales_hasIdbFtitle5](slots/scales_hasIdbFtitle5.md) | <br/>| 121785 |
| [scales_hasIdbFugstat](slots/scales_hasIdbFugstat.md) | <br/>| 121785 |
| [scales_hasIdbIfp](slots/scales_hasIdbIfp.md) | <br/>| 702500 |
| [scales_hasIdbInt1](slots/scales_hasIdbInt1.md) | <br/>| 121785 |
| [scales_hasIdbInt2](slots/scales_hasIdbInt2.md) | <br/>| 121785 |
| [scales_hasIdbInt3](slots/scales_hasIdbInt3.md) | <br/>| 121785 |
| [scales_hasIdbIs_stub](slots/scales_hasIdbIs_stub.md) | <br/>| 824286 |
| [scales_hasIdbJudgment](slots/scales_hasIdbJudgment.md) | <br/>| 702501 |
| [scales_hasIdbJuris](slots/scales_hasIdbJuris.md) | <br/>| 702501 |
| [scales_hasIdbJury](slots/scales_hasIdbJury.md) | <br/>| 702501 |
| [scales_hasIdbLoaddate](slots/scales_hasIdbLoaddate.md) | <br/>| 121785 |
| [scales_hasIdbMagdef](slots/scales_hasIdbMagdef.md) | <br/>| 121785 |
| [scales_hasIdbMagdock](slots/scales_hasIdbMagdock.md) | <br/>| 121785 |
| [scales_hasIdbMdldock](slots/scales_hasIdbMdldock.md) | <br/>| 702501 |
| [scales_hasIdbNoj](slots/scales_hasIdbNoj.md) | <br/>| 702501 |
| [scales_hasIdbNos](slots/scales_hasIdbNos.md) | <br/>| 702501 |
| [scales_hasIdbOffice](slots/scales_hasIdbOffice.md) | <br/>| 824286 |
| [scales_hasIdbOrigin](slots/scales_hasIdbOrigin.md) | <br/>| 702501 |
| [scales_hasIdbPlt](slots/scales_hasIdbPlt.md) | <br/>| 702493 |
| [scales_hasIdbPretrial](slots/scales_hasIdbPretrial.md) | <br/>| 41491 |
| [scales_hasIdbPriscd1](slots/scales_hasIdbPriscd1.md) | <br/>| 121785 |
| [scales_hasIdbPriscd2](slots/scales_hasIdbPriscd2.md) | <br/>| 121785 |
| [scales_hasIdbPriscd3](slots/scales_hasIdbPriscd3.md) | <br/>| 121785 |
| [scales_hasIdbPriscd4](slots/scales_hasIdbPriscd4.md) | <br/>| 121785 |
| [scales_hasIdbPriscd5](slots/scales_hasIdbPriscd5.md) | <br/>| 121785 |
| [scales_hasIdbPristim1](slots/scales_hasIdbPristim1.md) | <br/>| 121785 |
| [scales_hasIdbPristim2](slots/scales_hasIdbPristim2.md) | <br/>| 121785 |
| [scales_hasIdbPristim3](slots/scales_hasIdbPristim3.md) | <br/>| 121785 |
| [scales_hasIdbPristim4](slots/scales_hasIdbPristim4.md) | <br/>| 121785 |
| [scales_hasIdbPristim5](slots/scales_hasIdbPristim5.md) | <br/>| 121785 |
| [scales_hasIdbPristot](slots/scales_hasIdbPristot.md) | <br/>| 121785 |
| [scales_hasIdbProbcd1](slots/scales_hasIdbProbcd1.md) | <br/>| 121785 |
| [scales_hasIdbProbcd2](slots/scales_hasIdbProbcd2.md) | <br/>| 121785 |
| [scales_hasIdbProbcd3](slots/scales_hasIdbProbcd3.md) | <br/>| 121785 |
| [scales_hasIdbProbcd4](slots/scales_hasIdbProbcd4.md) | <br/>| 121785 |
| [scales_hasIdbProbcd5](slots/scales_hasIdbProbcd5.md) | <br/>| 121785 |
| [scales_hasIdbProbmon1](slots/scales_hasIdbProbmon1.md) | <br/>| 121785 |
| [scales_hasIdbProbmon2](slots/scales_hasIdbProbmon2.md) | <br/>| 121785 |
| [scales_hasIdbProbmon3](slots/scales_hasIdbProbmon3.md) | <br/>| 121785 |
| [scales_hasIdbProbmon4](slots/scales_hasIdbProbmon4.md) | <br/>| 121785 |
| [scales_hasIdbProbmon5](slots/scales_hasIdbProbmon5.md) | <br/>| 121785 |
| [scales_hasIdbProbtot](slots/scales_hasIdbProbtot.md) | <br/>| 121785 |
| [scales_hasIdbProccd](slots/scales_hasIdbProccd.md) | <br/>| 121785 |
| [scales_hasIdbProcdate](slots/scales_hasIdbProcdate.md) | <br/>| 121785 |
| [scales_hasIdbProcprog](slots/scales_hasIdbProcprog.md) | <br/>| 702501 |
| [scales_hasIdbProse](slots/scales_hasIdbProse.md) | <br/>| 702501 |
| [scales_hasIdbReopseq](slots/scales_hasIdbReopseq.md) | <br/>| 121785 |
| [scales_hasIdbResidenc](slots/scales_hasIdbResidenc.md) | <br/>| 702501 |
| [scales_hasIdbSection](slots/scales_hasIdbSection.md) | <br/>| 702501 |
| [scales_hasIdbSentdate](slots/scales_hasIdbSentdate.md) | <br/>| 121785 |
| [scales_hasIdbStatuscd](slots/scales_hasIdbStatuscd.md) | <br/>| 824285 |
| [scales_hasIdbSubsect](slots/scales_hasIdbSubsect.md) | <br/>| 702501 |
| [scales_hasIdbSupvrel1](slots/scales_hasIdbSupvrel1.md) | <br/>| 121785 |
| [scales_hasIdbSupvrel2](slots/scales_hasIdbSupvrel2.md) | <br/>| 121785 |
| [scales_hasIdbSupvrel3](slots/scales_hasIdbSupvrel3.md) | <br/>| 121785 |
| [scales_hasIdbSupvrel4](slots/scales_hasIdbSupvrel4.md) | <br/>| 121785 |
| [scales_hasIdbSupvrel5](slots/scales_hasIdbSupvrel5.md) | <br/>| 121785 |
| [scales_hasIdbTapeyear](slots/scales_hasIdbTapeyear.md) | <br/>| 824286 |
| [scales_hasIdbTcounsel](slots/scales_hasIdbTcounsel.md) | <br/>| 121785 |
| [scales_hasIdbTdateuse](slots/scales_hasIdbTdateuse.md) | <br/>| 662201 |
| [scales_hasIdbTermdate](slots/scales_hasIdbTermdate.md) | <br/>| 712609 |
| [scales_hasIdbTermoff](slots/scales_hasIdbTermoff.md) | <br/>| 121785 |
| [scales_hasIdbTitl](slots/scales_hasIdbTitl.md) | <br/>| 325292 |
| [scales_hasIdbToffcd1](slots/scales_hasIdbToffcd1.md) | <br/>| 121785 |
| [scales_hasIdbToffcd2](slots/scales_hasIdbToffcd2.md) | <br/>| 121785 |
| [scales_hasIdbToffcd3](slots/scales_hasIdbToffcd3.md) | <br/>| 121785 |
| [scales_hasIdbToffcd4](slots/scales_hasIdbToffcd4.md) | <br/>| 121785 |
| [scales_hasIdbToffcd5](slots/scales_hasIdbToffcd5.md) | <br/>| 121785 |
| [scales_hasIdbTofflvl1](slots/scales_hasIdbTofflvl1.md) | <br/>| 121785 |
| [scales_hasIdbTofflvl2](slots/scales_hasIdbTofflvl2.md) | <br/>| 121785 |
| [scales_hasIdbTofflvl3](slots/scales_hasIdbTofflvl3.md) | <br/>| 121785 |
| [scales_hasIdbTofflvl4](slots/scales_hasIdbTofflvl4.md) | <br/>| 121785 |
| [scales_hasIdbTofflvl5](slots/scales_hasIdbTofflvl5.md) | <br/>| 121785 |
| [scales_hasIdbTrandef](slots/scales_hasIdbTrandef.md) | <br/>| 121785 |
| [scales_hasIdbTrandist](slots/scales_hasIdbTrandist.md) | <br/>| 121785 |
| [scales_hasIdbTrandock](slots/scales_hasIdbTrandock.md) | <br/>| 121785 |
| [scales_hasIdbTranoff](slots/scales_hasIdbTranoff.md) | <br/>| 121785 |
| [scales_hasIdbTransdat](slots/scales_hasIdbTransdat.md) | <br/>| 6137 |
| [scales_hasIdbTransdoc](slots/scales_hasIdbTransdoc.md) | <br/>| 702501 |
| [scales_hasIdbTransoff](slots/scales_hasIdbTransoff.md) | <br/>| 702501 |
| [scales_hasIdbTransorg](slots/scales_hasIdbTransorg.md) | <br/>| 702501 |
| [scales_hasIdbTrclact](slots/scales_hasIdbTrclact.md) | <br/>| 702501 |
| [scales_hasIdbTrialend](slots/scales_hasIdbTrialend.md) | <br/>| 4417 |
| [scales_hasIdbTribegan](slots/scales_hasIdbTribegan.md) | <br/>| 3565 |
| [scales_hasIdbTrmarb](slots/scales_hasIdbTrmarb.md) | <br/>| 702501 |
| [scales_hasIdbTsev1](slots/scales_hasIdbTsev1.md) | <br/>| 121785 |
| [scales_hasIdbTsev2](slots/scales_hasIdbTsev2.md) | <br/>| 121785 |
| [scales_hasIdbTsev3](slots/scales_hasIdbTsev3.md) | <br/>| 121785 |
| [scales_hasIdbTsev4](slots/scales_hasIdbTsev4.md) | <br/>| 121785 |
| [scales_hasIdbTsev5](slots/scales_hasIdbTsev5.md) | <br/>| 121785 |
| [scales_hasIdbTtitle1](slots/scales_hasIdbTtitle1.md) | <br/>| 121785 |
| [scales_hasIdbTtitle2](slots/scales_hasIdbTtitle2.md) | <br/>| 121785 |
| [scales_hasIdbTtitle3](slots/scales_hasIdbTtitle3.md) | <br/>| 121785 |
| [scales_hasIdbTtitle4](slots/scales_hasIdbTtitle4.md) | <br/>| 121785 |
| [scales_hasIdbTtitle5](slots/scales_hasIdbTtitle5.md) | <br/>| 121785 |
| [scales_hasIdbTypemag](slots/scales_hasIdbTypemag.md) | <br/>| 121785 |
| [scales_hasIdbTypereg](slots/scales_hasIdbTypereg.md) | <br/>| 121785 |
| [scales_hasIdbTypetrn](slots/scales_hasIdbTypetrn.md) | <br/>| 121785 |
| [scales_hasIdbUpdate](slots/scales_hasIdbUpdate.md) | <br/>| 121785 |
| [scales_hasIdbVer](slots/scales_hasIdbVer.md) | <br/>| 121785 |
| [scales_hasIfpJudgeAttribution](slots/scales_hasIfpJudgeAttribution.md) | <br/>| 175903 |
| [scales_hasIfpLabel](slots/scales_hasIfpLabel.md) | <br/>| 197166 |
| [scales_hasMemberCase](slots/scales_hasMemberCase.md) | <br/>| 83603 |
| [scales_hasReferenceToOtherEntry](slots/scales_hasReferenceToOtherEntry.md) | <br/>| 10618350 |
| [scales_hasRelatedCase](slots/scales_hasRelatedCase.md) | <br/>| 125197 |
| [scales_hasUVAJudgeDirID](slots/scales_hasUVAJudgeDirID.md) | <br/>| 988 |
| [scales_isInCircuit](slots/scales_isInCircuit.md) | <br/>| 94 |
| [scales_isInstanceOfEntity](slots/scales_isInstanceOfEntity.md) | <br/>| 7421029 |
| [scales_OntologyLabel](slots/scales_OntologyLabel.md) | <br/>| 37622932 |
| [scales_Party](slots/scales_Party.md) | <br/>| 380643 |









## IRI prefixes

* jxdm72: http://release.niem.gov/niem/domains/jxdm/7.2/
* linkml: https://w3id.org/linkml/
* nibrs: http://fbi.gov/cjis/nibrs/2023.0/
* niem50: http://release.niem.gov/niem/niem-core/5.0/
* okn: https://purl.org/okn/
* okns: https://purl.org/okn/schema/
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* scales: http://schemas.scales-okn.org/rdf/scales#
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
* schema: http://schema.org/
