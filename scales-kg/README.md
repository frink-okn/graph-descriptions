# scales

No schema description specified



## Schema Diagram

```mermaid
erDiagram
HttpRelease.niem.govNiemDomainsJxdm7.2Arrest {
    string niem50_LocaleCensusBlockID  
    date niem50_ActivityDate  
}
HttpRelease.niem.govNiemDomainsJxdm7.2ArrestCharge {
    string http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSeverityLevelCode  
    string http___fbi.gov_cjis_nibrs_2023.0_NIBRSReportCategoryCode  
    string http___fbi.gov_cjis_nibrs_2023.0_OffenseUCRCode  
    string http___release.niem.gov_niem_domains_jxdm_7.2_ChargeDispositionCategoryText  
    string http___release.niem.gov_niem_domains_jxdm_7.2_ChargeText  
}
HttpRelease.niem.govNiemDomainsJxdm7.2Attorney {
    string http___release.niem.gov_niem_domains_jxdm_7.2_CaseOfficialRoleText  
    string niem50_PersonFullName  
    string niem50_ContactMailingAddress  
}
HttpRelease.niem.govNiemDomainsJxdm7.2Booking {
    date niem50_ActivityDate  
}
HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty {
    string niem50_PersonRaceText  
    uri scales_isReferenceToEntity  
    string http___release.niem.gov_niem_domains_jxdm_7.2_PersonSexCode  
    string niem50_EntityName  
    string http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText  
    string niem50_PersonFullName  
    string scales_hasExtraInfo  
    string scales_hasHighestOffenseLevelTerminated  
    string scales_hasHighestOffenseLevelOpening  
}
HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney {
    string http___release.niem.gov_niem_domains_jxdm_7.2_CaseOfficialRoleText  
    string niem50_PersonFullName  
    string niem50_ContactMailingAddress  
}
HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney {
    string niem50_PersonFullName  
    string http___release.niem.gov_niem_domains_jxdm_7.2_CaseOfficialRoleText  
    string niem50_ContactMailingAddress  
}
HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty {
    string niem50_EntityName  
    string http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText  
    string scales_hasExtraInfo  
}
HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge {
    string niem50_PersonFullName  
}
HttpRelease.niem.govNiemDomainsJxdm7.2Charge {
    string http___fbi.gov_cjis_nibrs_2023.0OffenseUCRCode  
    string scales_hasChargeType  
    string http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSeverityLevelCode  
    string http___fbi.gov_cjis_nibrs_2023.0NIBRSReportCategoryCode  
    string http___release.niem.gov_niem_domains_jxdm_7.2_DrugCategoryCode  
    float http___release.niem.gov_niem_domains_jxdm_7.2_BondAmount  
    string http___release.niem.gov_niem_domains_jxdm_7.2_BondType  
    string http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSequenceID  
    string http___release.niem.gov_niem_domains_jxdm_7.2_ChargeText  
    string http___release.niem.gov_niem_domains_jxdm_7.2_ChargeDisposition  
}
HttpRelease.niem.govNiemDomainsJxdm7.2Court {
    string scales_isInCircuit  
    string http___release.niem.gov_niem_codes_fips_5.0_CountyCode  
    string http___release.niem.gov_niem_domains_jxdm_7.2_CourtCategoryCode  
    string http___release.niem.gov_niem_domains_jxdm_7.2_CourtName  
    string niem50_AddressPostalCode  
}
HttpRelease.niem.govNiemDomainsJxdm7.2Judge {
    string niem50_PersonRaceText  
    string niem50_PersonSexText  
    date scales_hasCommissionDate  
    double scales_hasFJCNodeID  
    string scales_appointedByParty  
    string http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText  
    string niem50_PersonFullName  
    string scales_hasUVAJudgeDirID  
}
HttpRelease.niem.govNiemDomainsJxdm7.2LawEnforcementOfficial {
    string niem50_PersonID  
}
HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction {
    date http___release.niem.gov_niem_domains_jxdm_7.2_RegisterActionDate  
    string http___release.niem.gov_niem_domains_jxdm_7.2_RegisterActionDescriptionText  
    uri scales_DocketEntry  
}
HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions {
    uri scales_DocketEntry  
}
HttpRelease.niem.govNiemDomainsJxdm7.2Release {
    date niem50_ActivityDate  
}
HttpRelease.niem.govNiemDomainsJxdm7.2Sentence {
    string http___release.niem.gov_niem_domains_jxdm_7.2_SentenceDescriptionText  
}
HttpRelease.niem.govNiemDomainsJxdm7.2SentenceTerm {
    xsd_duration http___release.niem.gov_niem_domains_jxdm_7.2_TermDuration  
}
Niem50Person {
    string niem50_PersonRaceText  
    xsd_gYear scales_BirthYear  
    string http___release.niem.gov_niem_domains_jxdm_7.2_PersonSexCode  
}
ScalesCivilCase {
    string scales_hasIdbTdateuse  
    date niem50_StartDate  
    string http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText  
    string scales_hasIdbStatuscd  
    string scales_hasIdbDistrict  
    string scales_hasIdbDocket  
    double scales_hasIdbJudgment  
    double scales_hasIdbTapeyear  
    string scales_hasIdbSubsect  
    string scales_hasIdbDjoined  
    string scales_hasIdbTrmarb  
    string scales_hasIdbTribegan  
    string scales_hasIdbTrialend  
    string niem50_CaseDocketID  
    string scales_hasIdbMdldock  
    double scales_hasIdbDemanded  
    string scales_hasIdbNos  
    double scales_hasIdbOrigin  
    double scales_hasIdbTrclact  
    double scales_hasIdbCounty  
    string scales_hasIdbOffice  
    string scales_hasIdbSection  
    string scales_hasIdbTransoff  
    string niem50_CaseSubCategoryText  
    string scales_hasIdbFdateuse  
    string scales_hasIdbJury  
    integer scales_hasIdbJury  
    double scales_hasIdbResidenc  
    double scales_hasIdbTransdoc  
    uri scales_hasRelatedCase  
    string scales_hasIdbDef  
    datetime scales_hasIdbFiledate  
    string scales_hasIdbTransorg  
    string scales_hasIdbPlt  
    string scales_hasIdbArbit  
    double scales_hasIdbAmtrec  
    uri http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge  
    string niem50_StatusDescriptionText  
    boolean scales_hasIdbIs_stub  
    double scales_hasIdbJuris  
    double scales_hasIdbCircuit  
    double scales_hasIdbProcprog  
    string scales_hasIdbIfp  
    date niem50_EndDate  
    string niem50_CaseGeneralCategoryText  
    string niem50_JurisdictionText  
    double scales_hasIdbProse  
    datetime scales_hasIdbTermdate  
    string scales_hasIdbTitl  
    string http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt  
    double scales_hasIdbNoj  
    string scales_hasIdbTransdat  
    double scales_hasIdbClassact  
    double scales_hasIdbDisp  
    string scales_hasIdbPretrial  
}
ScalesCriminalCase {
    integer scales_hasIdbTranoff  
    string scales_hasIdbPriscd3  
    double scales_hasIdbFiscalyr  
    double scales_hasIdbFineamt4  
    double scales_hasIdbTcounsel  
    double scales_hasIdbFcounsel  
    string scales_hasIdbSentdate  
    string scales_hasIdbTermoff  
    integer scales_hasIdbTermoff  
    double scales_hasIdbTapeyear  
    string scales_hasIdbTypemag  
    double scales_hasIdbD2toffcd2  
    string scales_hasIdbCaslgky  
    double scales_hasIdbCtpnwof  
    string niem50_CaseDocketID  
    double scales_hasIdbProbmon4  
    double scales_hasIdbMagdef  
    string scales_hasIdbFgstrtdate  
    double scales_hasIdbCtpn  
    string scales_hasIdbTsev3  
    integer scales_hasIdbTsev3  
    double scales_hasIdbFineamt3  
    string scales_hasIdbTsev5  
    integer scales_hasIdbTsev5  
    double scales_hasIdbDisp2  
    double scales_hasIdbReopseq  
    double scales_hasIdbProbmon1  
    string scales_hasIdbFtitle4  
    string scales_hasIdbFtitle2  
    string scales_hasIdbDispdate  
    double scales_hasIdbFineamt1  
    string scales_hasIdbProbcd1  
    string scales_hasIdbLoaddate  
    double scales_hasIdbPristim2  
    double scales_hasIdbD2foffcd4  
    double scales_hasIdbSupvrel4  
    double scales_hasIdbFoffcd5  
    date niem50_EndDate  
    double scales_hasIdbFoffcd3  
    datetime scales_hasIdbTermdate  
    double scales_hasIdbProbmon2  
    string scales_hasIdbDocket  
    string scales_hasIdbFsev2  
    string scales_hasIdbFtitle3  
    string scales_hasIdbTtitle3  
    string scales_hasIdbTypetrn  
    integer scales_hasIdbTypetrn  
    string scales_hasIdbTtitle2  
    string scales_hasIdbFtitle1  
    string scales_hasIdbFgenddate  
    double scales_hasIdbCtfilr  
    string scales_hasIdbOffice  
    double scales_hasIdbPristot  
    double scales_hasIdbPristim4  
    double scales_hasIdbProbmon3  
    string scales_hasIdbAppdate  
    double scales_hasIdbFofflvl5  
    string scales_hasIdbTrandist  
    integer scales_hasIdbTrandist  
    double scales_hasIdbCttrtrn  
    string scales_hasIdbFsev5  
    integer scales_hasIdbFsev5  
    uri http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge  
    string niem50_StatusDescriptionText  
    double scales_hasIdbSupvrel2  
    double scales_hasIdbMagdock  
    double scales_hasIdbToffcd1  
    double scales_hasIdbFineamt5  
    double scales_hasIdbDisp5  
    double scales_hasIdbSupvrel5  
    string scales_hasIdbTtitle5  
    integer scales_hasIdbTtitle5  
    double scales_hasIdbD2toffcd5  
    string scales_hasIdbFugstat  
    string scales_hasIdbProbcd2  
    integer scales_hasIdbProbcd2  
    string scales_hasIdbTsev1  
    double scales_hasIdbCtfil  
    string niem50_JurisdictionText  
    double scales_hasIdbToffcd3  
    double scales_hasIdbVer  
    date niem50_StartDate  
    double scales_hasIdbPristim1  
    string scales_hasIdbFsev4  
    integer scales_hasIdbFsev4  
    double scales_hasIdbCtfilwor  
    double scales_hasIdbTrandock  
    double scales_hasIdbCttr  
    double scales_hasIdbD2foffcd2  
    string scales_hasIdbDistrict  
    double scales_hasIdbFofflvl2  
    double scales_hasIdbFineamt2  
    double scales_hasIdbFofflvl4  
    double scales_hasIdbTofflvl3  
    string scales_hasIdbFtitle5  
    double scales_hasIdbTofflvl1  
    double scales_hasIdbCounty  
    double scales_hasIdbCttrwor  
    string scales_hasIdbTsev4  
    integer scales_hasIdbTsev4  
    double scales_hasIdbToffcd4  
    string scales_hasIdbDeflgky  
    double scales_hasIdbD2toffcd4  
    double scales_hasIdbToffcd2  
    uri scales_hasRelatedCase  
    double scales_hasIdbPristim5  
    double scales_hasIdbFoffcd1  
    double scales_hasIdbTofflvl2  
    datetime scales_hasIdbFiledate  
    string scales_hasIdbUpdate  
    double scales_hasIdbD2foffcd1  
    double scales_hasIdbFinetot  
    double scales_hasIdbTofflvl4  
    string scales_hasIdbAppcd  
    string scales_hasIdbPriscd4  
    integer scales_hasIdbPriscd4  
    double scales_hasIdbCircuit  
    double scales_hasIdbCttrr  
    string scales_hasIdbTypereg  
    double scales_hasIdbD2toffcd1  
    string scales_hasIdbFsev1  
    string http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt  
    string scales_hasIdbPriscd5  
    integer scales_hasIdbPriscd5  
    double scales_hasIdbInt1  
    double scales_hasIdbTofflvl5  
    double scales_hasIdbCtdef  
    string scales_hasIdbProbcd3  
    integer scales_hasIdbProbcd3  
    double scales_hasIdbFofflvl1  
    string scales_hasIdbProcdate  
    double scales_hasIdbDefno  
    double scales_hasIdbInt2  
    string scales_hasIdbTsev2  
    integer scales_hasIdbTsev2  
    string scales_hasIdbStatuscd  
    double scales_hasIdbSupvrel1  
    double scales_hasIdbCtfiltrn  
    double scales_hasIdbFoffcd4  
    double scales_hasIdbD2foffcd3  
    double scales_hasIdbProbtot  
    string scales_hasIdbTtitle1  
    double scales_hasIdbTrandef  
    double scales_hasIdbD2toffcd3  
    string scales_hasIdbPriscd1  
    double scales_hasIdbD2foffcd5  
    string scales_hasIdbProbcd4  
    integer scales_hasIdbProbcd4  
    double scales_hasIdbDisp1  
    double scales_hasIdbProccd  
    string scales_hasIdbProbcd5  
    integer scales_hasIdbProbcd5  
    double scales_hasIdbSupvrel3  
    double scales_hasIdbInt3  
    string scales_hasIdbPriscd2  
    string scales_hasIdbFsev3  
    double scales_hasIdbProbmon5  
    double scales_hasIdbFofflvl3  
    double scales_hasIdbDisp4  
    double scales_hasIdbFoffcd2  
    string scales_hasIdbTtitle4  
    string niem50_CaseGeneralCategoryText  
    double scales_hasIdbDisp3  
    double scales_hasIdbToffcd5  
    boolean scales_hasIdbIs_stub  
    double scales_hasIdbPristim3  
}
ScalesFirm {
    string niem50_OrganizationName  
}
ScalesParty {
    uri scales_isInstanceOfEntity  
    string niem50_EntityName  
    string niem50_PersonFullName  
    string http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText  
    string scales_hasExtraInfo  
}

HttpRelease.niem.govNiemDomainsJxdm7.2Arrest ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2LawEnforcementOfficial : "http___release.niem.gov_niem_domains_jxdm_7.2_ArrestOfficial"
HttpRelease.niem.govNiemDomainsJxdm7.2Arrest ||--|o Niem50Person : "http___release.niem.gov_niem_domains_jxdm_7.2_ArrestSubject"
HttpRelease.niem.govNiemDomainsJxdm7.2Arrest ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2ArrestCharge : "http___release.niem.gov_niem_domains_jxdm_7.2_ArrestCharge"
HttpRelease.niem.govNiemDomainsJxdm7.2Attorney ||--|o ScalesFirm : "scales_Firm"
HttpRelease.niem.govNiemDomainsJxdm7.2Booking ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2Release : "http___release.niem.gov_niem_domains_jxdm_7.2_BookingRelease"
HttpRelease.niem.govNiemDomainsJxdm7.2Booking ||--|o ScalesCriminalCase : "scales_BookingCase"
HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2Booking : "http___release.niem.gov_niem_domains_jxdm_7.2_SubjectBooking"
HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2Charge : "http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge"
HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney"
HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney ||--|o ScalesFirm : "scales_Firm"
HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney ||--|o ScalesFirm : "scales_Firm"
HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney"
HttpRelease.niem.govNiemDomainsJxdm7.2Charge ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty : "http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSubject"
HttpRelease.niem.govNiemDomainsJxdm7.2Charge ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2Booking : "http___release.niem.gov_niem_domains_jxdm_7.2_ChargeBooking"
HttpRelease.niem.govNiemDomainsJxdm7.2Charge ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2Sentence : "http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSentence"
HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2Sentence : "http___release.niem.gov_niem_domains_jxdm_7.2_Sentence"
HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction : "scales_DocketEntry"
HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction : "scales_DocketEntry"
HttpRelease.niem.govNiemDomainsJxdm7.2Sentence ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2SentenceTerm : "http___release.niem.gov_niem_domains_jxdm_7.2_SentenceTerm"
ScalesCivilCase ||--|o ScalesParty : "scales_Party"
ScalesCivilCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty"
ScalesCivilCase ||--|o ScalesParty : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty"
ScalesCivilCase ||--|o ScalesCivilCase : "scales_hasMemberCase"
ScalesCivilCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions : "scales_DocketTable"
ScalesCivilCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction : "scales_DocketTable"
ScalesCivilCase ||--|o ScalesCivilCase : "scales_hasRelatedCase"
ScalesCivilCase ||--|o ScalesCriminalCase : "scales_hasRelatedCase"
ScalesCivilCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty"
ScalesCivilCase ||--|o ScalesParty : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty"
ScalesCivilCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge"
ScalesCivilCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2Court : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt"
ScalesCriminalCase ||--|o ScalesCivilCase : "scales_hasMemberCase"
ScalesCriminalCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge"
ScalesCriminalCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2Charge : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge"
ScalesCriminalCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions : "scales_DocketTable"
ScalesCriminalCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction : "scales_DocketTable"
ScalesCriminalCase ||--|o ScalesCivilCase : "scales_hasRelatedCase"
ScalesCriminalCase ||--|o ScalesCriminalCase : "scales_hasRelatedCase"
ScalesCriminalCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty"
ScalesCriminalCase ||--|o ScalesParty : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty"
ScalesCriminalCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2Court : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt"
ScalesCriminalCase ||--|o ScalesParty : "scales_Party"
ScalesCriminalCase ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty"
ScalesCriminalCase ||--|o ScalesParty : "http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty"
ScalesParty ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2Charge : "http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge"
ScalesParty ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2Sentence : "http___release.niem.gov_niem_domains_jxdm_7.2_Sentence"
ScalesParty ||--|o HttpRelease.niem.govNiemDomainsJxdm7.2Attorney : "http___release.niem.gov_niem_domains_jxdm_7.2_Attorney"

```



## Imports


* linkml:types



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Arrest](classes/HttpRelease.niem.govNiemDomainsJxdm7.2Arrest.md) | No class (type) description specified<br/>| 83347 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2ArrestCharge](classes/HttpRelease.niem.govNiemDomainsJxdm7.2ArrestCharge.md) | No class (type) description specified<br/>| 83347 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2Attorney](classes/HttpRelease.niem.govNiemDomainsJxdm7.2Attorney.md) | No class (type) description specified<br/>| 537560 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2Booking](classes/HttpRelease.niem.govNiemDomainsJxdm7.2Booking.md) | No class (type) description specified<br/>| 363466 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified<br/>| 2949712 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney](classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney.md) | No class (type) description specified<br/>| 2823772 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney](classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney.md) | No class (type) description specified<br/>| 2755161 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | No class (type) description specified<br/>| 1337860 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge](classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge.md) | No class (type) description specified<br/>| 3207790 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | No class (type) description specified<br/>| 2908749 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2Court](classes/HttpRelease.niem.govNiemDomainsJxdm7.2Court.md) | No class (type) description specified<br/>| 94 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2Judge](classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md) | No class (type) description specified<br/>| 5385 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2LawEnforcementOfficial](classes/HttpRelease.niem.govNiemDomainsJxdm7.2LawEnforcementOfficial.md) | No class (type) description specified<br/>| 2016 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) | No class (type) description specified<br/>| 28776887 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) | No class (type) description specified<br/>| 4160501 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2Release](classes/HttpRelease.niem.govNiemDomainsJxdm7.2Release.md) | No class (type) description specified<br/>| 347084 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2Sentence](classes/HttpRelease.niem.govNiemDomainsJxdm7.2Sentence.md) | No class (type) description specified<br/>| 356094 | 
| [HttpRelease.niem.govNiemDomainsJxdm7.2SentenceTerm](classes/HttpRelease.niem.govNiemDomainsJxdm7.2SentenceTerm.md) | No class (type) description specified<br/>| 462 | 
| [Niem50Person](classes/Niem50Person.md) | No class (type) description specified<br/>| 83347 | 
| [ScalesCivilCase](classes/ScalesCivilCase.md) | No class (type) description specified<br/>| 1795343 | 
| [ScalesCriminalCase](classes/ScalesCriminalCase.md) | No class (type) description specified<br/>| 2368748 | 
| [ScalesFirm](classes/ScalesFirm.md) | No class (type) description specified<br/>| 2929549 | 
| [ScalesParty](classes/ScalesParty.md) | No class (type) description specified<br/>| 7362525 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [http___fbi.gov_cjis_nibrs_2023.0_NIBRSReportCategoryCode](slots/http___fbi.gov_cjis_nibrs_2023.0_NIBRSReportCategoryCode.md) | No slot (predicate) description specified<br/>| 39440 |
| [http___fbi.gov_cjis_nibrs_2023.0_OffenseUCRCode](slots/http___fbi.gov_cjis_nibrs_2023.0_OffenseUCRCode.md) | No slot (predicate) description specified<br/>| 76331 |
| [http___fbi.gov_cjis_nibrs_2023.0NIBRSReportCategoryCode](slots/http___fbi.gov_cjis_nibrs_2023.0NIBRSReportCategoryCode.md) | No slot (predicate) description specified<br/>| 1421122 |
| [http___fbi.gov_cjis_nibrs_2023.0OffenseUCRCode](slots/http___fbi.gov_cjis_nibrs_2023.0OffenseUCRCode.md) | No slot (predicate) description specified<br/>| 848072 |
| [http___release.niem.gov_niem_codes_fips_5.0_CountyCode](slots/http___release.niem.gov_niem_codes_fips_5.0_CountyCode.md) | No slot (predicate) description specified<br/>| 3035 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ArrestCharge](slots/http___release.niem.gov_niem_domains_jxdm_7.2_ArrestCharge.md) | No slot (predicate) description specified<br/>| 83347 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ArrestOfficial](slots/http___release.niem.gov_niem_domains_jxdm_7.2_ArrestOfficial.md) | No slot (predicate) description specified<br/>| 84716 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ArrestSubject](slots/http___release.niem.gov_niem_domains_jxdm_7.2_ArrestSubject.md) | No slot (predicate) description specified<br/>| 83347 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_Attorney](slots/http___release.niem.gov_niem_domains_jxdm_7.2_Attorney.md) | No slot (predicate) description specified<br/>| 537560 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_BondAmount](slots/http___release.niem.gov_niem_domains_jxdm_7.2_BondAmount.md) | No slot (predicate) description specified<br/>| 99402 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_BondType](slots/http___release.niem.gov_niem_domains_jxdm_7.2_BondType.md) | No slot (predicate) description specified<br/>| 105383 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_BookingRelease](slots/http___release.niem.gov_niem_domains_jxdm_7.2_BookingRelease.md) | No slot (predicate) description specified<br/>| 347084 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_Case](slots/http___release.niem.gov_niem_domains_jxdm_7.2_Case.md) | No slot (predicate) description specified<br/>| 864700 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge](slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge.md) | No slot (predicate) description specified<br/>| 607725 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt](slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt.md) | No slot (predicate) description specified<br/>| 4072490 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty](slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty.md) | No slot (predicate) description specified<br/>| 6231746 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney](slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney.md) | No slot (predicate) description specified<br/>| 2823772 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney](slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney.md) | No slot (predicate) description specified<br/>| 2755161 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty](slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty.md) | No slot (predicate) description specified<br/>| 4892601 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge](slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge.md) | No slot (predicate) description specified<br/>| 4424121 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseOfficialRoleText](slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseOfficialRoleText.md) | No slot (predicate) description specified<br/>| 1713199 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ChargeBooking](slots/http___release.niem.gov_niem_domains_jxdm_7.2_ChargeBooking.md) | No slot (predicate) description specified<br/>| 363466 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ChargeDisposition](slots/http___release.niem.gov_niem_domains_jxdm_7.2_ChargeDisposition.md) | No slot (predicate) description specified<br/>| 389366 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ChargeDispositionCategoryText](slots/http___release.niem.gov_niem_domains_jxdm_7.2_ChargeDispositionCategoryText.md) | No slot (predicate) description specified<br/>| 94272 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSentence](slots/http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSentence.md) | No slot (predicate) description specified<br/>| 244007 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSequenceID](slots/http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSequenceID.md) | No slot (predicate) description specified<br/>| 389366 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSeverityLevelCode](slots/http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSeverityLevelCode.md) | No slot (predicate) description specified<br/>| 444717 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSubject](slots/http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSubject.md) | No slot (predicate) description specified<br/>| 363466 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ChargeText](slots/http___release.niem.gov_niem_domains_jxdm_7.2_ChargeText.md) | No slot (predicate) description specified<br/>| 3374647 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CourtCategoryCode](slots/http___release.niem.gov_niem_domains_jxdm_7.2_CourtCategoryCode.md) | No slot (predicate) description specified<br/>| 94 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CourtName](slots/http___release.niem.gov_niem_domains_jxdm_7.2_CourtName.md) | No slot (predicate) description specified<br/>| 94 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_DrugCategoryCode](slots/http___release.niem.gov_niem_domains_jxdm_7.2_DrugCategoryCode.md) | No slot (predicate) description specified<br/>| 45 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText](slots/http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText.md) | No slot (predicate) description specified<br/>| 5385 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText](slots/http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText.md) | No slot (predicate) description specified<br/>| 11629280 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge](slots/http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge.md) | No slot (predicate) description specified<br/>| 2908749 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_PersonSexCode](slots/http___release.niem.gov_niem_domains_jxdm_7.2_PersonSexCode.md) | No slot (predicate) description specified<br/>| 448932 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_RegisterActionDate](slots/http___release.niem.gov_niem_domains_jxdm_7.2_RegisterActionDate.md) | No slot (predicate) description specified<br/>| 58361062 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_RegisterActionDescriptionText](slots/http___release.niem.gov_niem_domains_jxdm_7.2_RegisterActionDescriptionText.md) | No slot (predicate) description specified<br/>| 58359685 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_Sentence](slots/http___release.niem.gov_niem_domains_jxdm_7.2_Sentence.md) | No slot (predicate) description specified<br/>| 675670 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_SentenceDescriptionText](slots/http___release.niem.gov_niem_domains_jxdm_7.2_SentenceDescriptionText.md) | No slot (predicate) description specified<br/>| 356094 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_SentenceTerm](slots/http___release.niem.gov_niem_domains_jxdm_7.2_SentenceTerm.md) | No slot (predicate) description specified<br/>| 356094 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText](slots/http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText.md) | No slot (predicate) description specified<br/>| 718593 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_SubjectBooking](slots/http___release.niem.gov_niem_domains_jxdm_7.2_SubjectBooking.md) | No slot (predicate) description specified<br/>| 363466 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_TermDuration](slots/http___release.niem.gov_niem_domains_jxdm_7.2_TermDuration.md) | No slot (predicate) description specified<br/>| 462 |
| [niem50_ActivityDate](slots/niem50_ActivityDate.md) | No slot (predicate) description specified<br/>| 904252 |
| [niem50_AddressPostalCode](slots/niem50_AddressPostalCode.md) | No slot (predicate) description specified<br/>| 40932 |
| [niem50_AdministrativeID](slots/niem50_AdministrativeID.md) | No slot (predicate) description specified<br/>| 30414852 |
| [niem50_CaseDocketID](slots/niem50_CaseDocketID.md) | No slot (predicate) description specified<br/>| 4164091 |
| [niem50_CaseGeneralCategoryText](slots/niem50_CaseGeneralCategoryText.md) | No slot (predicate) description specified<br/>| 4072490 |
| [niem50_CaseSubCategoryText](slots/niem50_CaseSubCategoryText.md) | No slot (predicate) description specified<br/>| 1863523 |
| [niem50_ContactMailingAddress](slots/niem50_ContactMailingAddress.md) | No slot (predicate) description specified<br/>| 3083592 |
| [niem50_EndDate](slots/niem50_EndDate.md) | No slot (predicate) description specified<br/>| 3828523 |
| [niem50_EntityName](slots/niem50_EntityName.md) | No slot (predicate) description specified<br/>| 4241878 |
| [niem50_JurisdictionText](slots/niem50_JurisdictionText.md) | No slot (predicate) description specified<br/>| 3926555 |
| [niem50_LocaleCensusBlockID](slots/niem50_LocaleCensusBlockID.md) | No slot (predicate) description specified<br/>| 71598 |
| [niem50_OrganizationName](slots/niem50_OrganizationName.md) | No slot (predicate) description specified<br/>| 2929547 |
| [niem50_PersonFullName](slots/niem50_PersonFullName.md) | No slot (predicate) description specified<br/>| 17954252 |
| [niem50_PersonID](slots/niem50_PersonID.md) | No slot (predicate) description specified<br/>| 2020 |
| [niem50_PersonRaceText](slots/niem50_PersonRaceText.md) | No slot (predicate) description specified<br/>| 450612 |
| [niem50_PersonSexText](slots/niem50_PersonSexText.md) | No slot (predicate) description specified<br/>| 3762 |
| [niem50_StartDate](slots/niem50_StartDate.md) | No slot (predicate) description specified<br/>| 4072490 |
| [niem50_StatusDescriptionText](slots/niem50_StatusDescriptionText.md) | No slot (predicate) description specified<br/>| 4072490 |
| [scales_appointedByParty](slots/scales_appointedByParty.md) | No slot (predicate) description specified<br/>| 3912 |
| [scales_assignedToDefendant](slots/scales_assignedToDefendant.md) | No slot (predicate) description specified<br/>| 53962 |
| [scales_BirthYear](slots/scales_BirthYear.md) | No slot (predicate) description specified<br/>| 91623 |
| [scales_BookingCase](slots/scales_BookingCase.md) | No slot (predicate) description specified<br/>| 218359 |
| [scales_DocketEntry](slots/scales_DocketEntry.md) | No slot (predicate) description specified<br/>| 58334996 |
| [scales_DocketTable](slots/scales_DocketTable.md) | No slot (predicate) description specified<br/>| 4160501 |
| [scales_Firm](slots/scales_Firm.md) | No slot (predicate) description specified<br/>| 2929549 |
| [scales_hasChargeType](slots/scales_hasChargeType.md) | No slot (predicate) description specified<br/>| 389366 |
| [scales_hasCommissionDate](slots/scales_hasCommissionDate.md) | No slot (predicate) description specified<br/>| 4257 |
| [scales_hasExtraInfo](slots/scales_hasExtraInfo.md) | No slot (predicate) description specified<br/>| 861769 |
| [scales_hasFJCNodeID](slots/scales_hasFJCNodeID.md) | No slot (predicate) description specified<br/>| 3855 |
| [scales_hasHighestOffenseLevelOpening](slots/scales_hasHighestOffenseLevelOpening.md) | No slot (predicate) description specified<br/>| 159337 |
| [scales_hasHighestOffenseLevelTerminated](slots/scales_hasHighestOffenseLevelTerminated.md) | No slot (predicate) description specified<br/>| 69523 |
| [scales_hasIdbAmtrec](slots/scales_hasIdbAmtrec.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbAppcd](slots/scales_hasIdbAppcd.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbAppdate](slots/scales_hasIdbAppdate.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbArbit](slots/scales_hasIdbArbit.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbCaslgky](slots/scales_hasIdbCaslgky.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbCircuit](slots/scales_hasIdbCircuit.md) | No slot (predicate) description specified<br/>| 824286 |
| [scales_hasIdbClassact](slots/scales_hasIdbClassact.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbCounty](slots/scales_hasIdbCounty.md) | No slot (predicate) description specified<br/>| 824286 |
| [scales_hasIdbCtdef](slots/scales_hasIdbCtdef.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbCtfil](slots/scales_hasIdbCtfil.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbCtfilr](slots/scales_hasIdbCtfilr.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbCtfiltrn](slots/scales_hasIdbCtfiltrn.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbCtfilwor](slots/scales_hasIdbCtfilwor.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbCtpn](slots/scales_hasIdbCtpn.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbCtpnwof](slots/scales_hasIdbCtpnwof.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbCttr](slots/scales_hasIdbCttr.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbCttrr](slots/scales_hasIdbCttrr.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbCttrtrn](slots/scales_hasIdbCttrtrn.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbCttrwor](slots/scales_hasIdbCttrwor.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbD2foffcd1](slots/scales_hasIdbD2foffcd1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbD2foffcd2](slots/scales_hasIdbD2foffcd2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbD2foffcd3](slots/scales_hasIdbD2foffcd3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbD2foffcd4](slots/scales_hasIdbD2foffcd4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbD2foffcd5](slots/scales_hasIdbD2foffcd5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbD2toffcd1](slots/scales_hasIdbD2toffcd1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbD2toffcd2](slots/scales_hasIdbD2toffcd2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbD2toffcd3](slots/scales_hasIdbD2toffcd3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbD2toffcd4](slots/scales_hasIdbD2toffcd4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbD2toffcd5](slots/scales_hasIdbD2toffcd5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbDef](slots/scales_hasIdbDef.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbDeflgky](slots/scales_hasIdbDeflgky.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbDefno](slots/scales_hasIdbDefno.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbDemanded](slots/scales_hasIdbDemanded.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbDisp](slots/scales_hasIdbDisp.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbDisp1](slots/scales_hasIdbDisp1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbDisp2](slots/scales_hasIdbDisp2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbDisp3](slots/scales_hasIdbDisp3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbDisp4](slots/scales_hasIdbDisp4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbDisp5](slots/scales_hasIdbDisp5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbDispdate](slots/scales_hasIdbDispdate.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbDistrict](slots/scales_hasIdbDistrict.md) | No slot (predicate) description specified<br/>| 824286 |
| [scales_hasIdbDjoined](slots/scales_hasIdbDjoined.md) | No slot (predicate) description specified<br/>| 275529 |
| [scales_hasIdbDocket](slots/scales_hasIdbDocket.md) | No slot (predicate) description specified<br/>| 824286 |
| [scales_hasIdbFcounsel](slots/scales_hasIdbFcounsel.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFdateuse](slots/scales_hasIdbFdateuse.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbFgenddate](slots/scales_hasIdbFgenddate.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFgstrtdate](slots/scales_hasIdbFgstrtdate.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFiledate](slots/scales_hasIdbFiledate.md) | No slot (predicate) description specified<br/>| 824286 |
| [scales_hasIdbFineamt1](slots/scales_hasIdbFineamt1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFineamt2](slots/scales_hasIdbFineamt2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFineamt3](slots/scales_hasIdbFineamt3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFineamt4](slots/scales_hasIdbFineamt4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFineamt5](slots/scales_hasIdbFineamt5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFinetot](slots/scales_hasIdbFinetot.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFiscalyr](slots/scales_hasIdbFiscalyr.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFoffcd1](slots/scales_hasIdbFoffcd1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFoffcd2](slots/scales_hasIdbFoffcd2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFoffcd3](slots/scales_hasIdbFoffcd3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFoffcd4](slots/scales_hasIdbFoffcd4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFoffcd5](slots/scales_hasIdbFoffcd5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFofflvl1](slots/scales_hasIdbFofflvl1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFofflvl2](slots/scales_hasIdbFofflvl2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFofflvl3](slots/scales_hasIdbFofflvl3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFofflvl4](slots/scales_hasIdbFofflvl4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFofflvl5](slots/scales_hasIdbFofflvl5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFsev1](slots/scales_hasIdbFsev1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFsev2](slots/scales_hasIdbFsev2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFsev3](slots/scales_hasIdbFsev3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFsev4](slots/scales_hasIdbFsev4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFsev5](slots/scales_hasIdbFsev5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFtitle1](slots/scales_hasIdbFtitle1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFtitle2](slots/scales_hasIdbFtitle2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFtitle3](slots/scales_hasIdbFtitle3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFtitle4](slots/scales_hasIdbFtitle4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFtitle5](slots/scales_hasIdbFtitle5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbFugstat](slots/scales_hasIdbFugstat.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbIfp](slots/scales_hasIdbIfp.md) | No slot (predicate) description specified<br/>| 702500 |
| [scales_hasIdbInt1](slots/scales_hasIdbInt1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbInt2](slots/scales_hasIdbInt2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbInt3](slots/scales_hasIdbInt3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbIs_stub](slots/scales_hasIdbIs_stub.md) | No slot (predicate) description specified<br/>| 824286 |
| [scales_hasIdbJudgment](slots/scales_hasIdbJudgment.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbJuris](slots/scales_hasIdbJuris.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbJury](slots/scales_hasIdbJury.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbLoaddate](slots/scales_hasIdbLoaddate.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbMagdef](slots/scales_hasIdbMagdef.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbMagdock](slots/scales_hasIdbMagdock.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbMdldock](slots/scales_hasIdbMdldock.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbNoj](slots/scales_hasIdbNoj.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbNos](slots/scales_hasIdbNos.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbOffice](slots/scales_hasIdbOffice.md) | No slot (predicate) description specified<br/>| 824286 |
| [scales_hasIdbOrigin](slots/scales_hasIdbOrigin.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbPlt](slots/scales_hasIdbPlt.md) | No slot (predicate) description specified<br/>| 702493 |
| [scales_hasIdbPretrial](slots/scales_hasIdbPretrial.md) | No slot (predicate) description specified<br/>| 41491 |
| [scales_hasIdbPriscd1](slots/scales_hasIdbPriscd1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbPriscd2](slots/scales_hasIdbPriscd2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbPriscd3](slots/scales_hasIdbPriscd3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbPriscd4](slots/scales_hasIdbPriscd4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbPriscd5](slots/scales_hasIdbPriscd5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbPristim1](slots/scales_hasIdbPristim1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbPristim2](slots/scales_hasIdbPristim2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbPristim3](slots/scales_hasIdbPristim3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbPristim4](slots/scales_hasIdbPristim4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbPristim5](slots/scales_hasIdbPristim5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbPristot](slots/scales_hasIdbPristot.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProbcd1](slots/scales_hasIdbProbcd1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProbcd2](slots/scales_hasIdbProbcd2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProbcd3](slots/scales_hasIdbProbcd3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProbcd4](slots/scales_hasIdbProbcd4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProbcd5](slots/scales_hasIdbProbcd5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProbmon1](slots/scales_hasIdbProbmon1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProbmon2](slots/scales_hasIdbProbmon2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProbmon3](slots/scales_hasIdbProbmon3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProbmon4](slots/scales_hasIdbProbmon4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProbmon5](slots/scales_hasIdbProbmon5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProbtot](slots/scales_hasIdbProbtot.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProccd](slots/scales_hasIdbProccd.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProcdate](slots/scales_hasIdbProcdate.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbProcprog](slots/scales_hasIdbProcprog.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbProse](slots/scales_hasIdbProse.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbReopseq](slots/scales_hasIdbReopseq.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbResidenc](slots/scales_hasIdbResidenc.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbSection](slots/scales_hasIdbSection.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbSentdate](slots/scales_hasIdbSentdate.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbStatuscd](slots/scales_hasIdbStatuscd.md) | No slot (predicate) description specified<br/>| 824285 |
| [scales_hasIdbSubsect](slots/scales_hasIdbSubsect.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbSupvrel1](slots/scales_hasIdbSupvrel1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbSupvrel2](slots/scales_hasIdbSupvrel2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbSupvrel3](slots/scales_hasIdbSupvrel3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbSupvrel4](slots/scales_hasIdbSupvrel4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbSupvrel5](slots/scales_hasIdbSupvrel5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTapeyear](slots/scales_hasIdbTapeyear.md) | No slot (predicate) description specified<br/>| 824286 |
| [scales_hasIdbTcounsel](slots/scales_hasIdbTcounsel.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTdateuse](slots/scales_hasIdbTdateuse.md) | No slot (predicate) description specified<br/>| 662201 |
| [scales_hasIdbTermdate](slots/scales_hasIdbTermdate.md) | No slot (predicate) description specified<br/>| 712609 |
| [scales_hasIdbTermoff](slots/scales_hasIdbTermoff.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTitl](slots/scales_hasIdbTitl.md) | No slot (predicate) description specified<br/>| 325292 |
| [scales_hasIdbToffcd1](slots/scales_hasIdbToffcd1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbToffcd2](slots/scales_hasIdbToffcd2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbToffcd3](slots/scales_hasIdbToffcd3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbToffcd4](slots/scales_hasIdbToffcd4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbToffcd5](slots/scales_hasIdbToffcd5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTofflvl1](slots/scales_hasIdbTofflvl1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTofflvl2](slots/scales_hasIdbTofflvl2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTofflvl3](slots/scales_hasIdbTofflvl3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTofflvl4](slots/scales_hasIdbTofflvl4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTofflvl5](slots/scales_hasIdbTofflvl5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTrandef](slots/scales_hasIdbTrandef.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTrandist](slots/scales_hasIdbTrandist.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTrandock](slots/scales_hasIdbTrandock.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTranoff](slots/scales_hasIdbTranoff.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTransdat](slots/scales_hasIdbTransdat.md) | No slot (predicate) description specified<br/>| 6137 |
| [scales_hasIdbTransdoc](slots/scales_hasIdbTransdoc.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbTransoff](slots/scales_hasIdbTransoff.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbTransorg](slots/scales_hasIdbTransorg.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbTrclact](slots/scales_hasIdbTrclact.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbTrialend](slots/scales_hasIdbTrialend.md) | No slot (predicate) description specified<br/>| 4417 |
| [scales_hasIdbTribegan](slots/scales_hasIdbTribegan.md) | No slot (predicate) description specified<br/>| 3565 |
| [scales_hasIdbTrmarb](slots/scales_hasIdbTrmarb.md) | No slot (predicate) description specified<br/>| 702501 |
| [scales_hasIdbTsev1](slots/scales_hasIdbTsev1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTsev2](slots/scales_hasIdbTsev2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTsev3](slots/scales_hasIdbTsev3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTsev4](slots/scales_hasIdbTsev4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTsev5](slots/scales_hasIdbTsev5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTtitle1](slots/scales_hasIdbTtitle1.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTtitle2](slots/scales_hasIdbTtitle2.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTtitle3](slots/scales_hasIdbTtitle3.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTtitle4](slots/scales_hasIdbTtitle4.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTtitle5](slots/scales_hasIdbTtitle5.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTypemag](slots/scales_hasIdbTypemag.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTypereg](slots/scales_hasIdbTypereg.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbTypetrn](slots/scales_hasIdbTypetrn.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbUpdate](slots/scales_hasIdbUpdate.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIdbVer](slots/scales_hasIdbVer.md) | No slot (predicate) description specified<br/>| 121785 |
| [scales_hasIfpJudgeAttribution](slots/scales_hasIfpJudgeAttribution.md) | No slot (predicate) description specified<br/>| 175903 |
| [scales_hasIfpLabel](slots/scales_hasIfpLabel.md) | No slot (predicate) description specified<br/>| 197166 |
| [scales_hasMemberCase](slots/scales_hasMemberCase.md) | No slot (predicate) description specified<br/>| 83603 |
| [scales_hasReferenceToOtherEntry](slots/scales_hasReferenceToOtherEntry.md) | No slot (predicate) description specified<br/>| 10618350 |
| [scales_hasRelatedCase](slots/scales_hasRelatedCase.md) | No slot (predicate) description specified<br/>| 125197 |
| [scales_hasUVAJudgeDirID](slots/scales_hasUVAJudgeDirID.md) | No slot (predicate) description specified<br/>| 988 |
| [scales_isInCircuit](slots/scales_isInCircuit.md) | No slot (predicate) description specified<br/>| 94 |
| [scales_isInstanceOfEntity](slots/scales_isInstanceOfEntity.md) | No slot (predicate) description specified<br/>| 7057563 |
| [scales_isReferenceToEntity](slots/scales_isReferenceToEntity.md) | No slot (predicate) description specified<br/>| 363466 |
| [scales_OntologyLabel](slots/scales_OntologyLabel.md) | No slot (predicate) description specified<br/>| 37622932 |
| [scales_Party](slots/scales_Party.md) | No slot (predicate) description specified<br/>| 380643 |






## Types

| Type | Description |
| --- | --- |
| [XsdDuration](types/XsdDuration.md) | No class (type) description specified |
| [XsdGYear](types/XsdGYear.md) | No class (type) description specified |





## IRI prefixes

* linkml: https://w3id.org/linkml/
* niem50: http://release.niem.gov/niem/niem-core/5.0/
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* scales: http://schemas.scales-okn.org/rdf/scales#
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
* schema: http://schema.org/
