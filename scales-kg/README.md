# No schema name specified

No schema description specified



## Schema Diagram

```mermaid
erDiagram
Jxdm72Case {
    integer niem50_CaseDocketID  
    string niem50_CaseDocketID  
    uri jxdm72_RegisterOfActions  
}
Jxdm72Charge {
    string scales_hasBondType  
    integer jxdm72_ChargeIdentification  
    string jxdm72_ChargeDescriptionText  
    string jxdm72_ChargeSeverityText  
}
Jxdm72ChargeInstrument {
    date niem50_DocumentFiledDate  
    string niem50_DocumentStatus  
    date niem50_DocumentEffectiveDate  
    string niem50_DocumentDescriptionText  
}
Jxdm72Court {
    string jxdm72_CourtCategoryCode  
    string scales_isInCircuit  
    string http___releaseniemgov_niem_codes_fips_50_CountyCode  
    string jxdm72_CourtName  
    string niem50_AddressPostalCode  
}
Jxdm72DetentionFacility {
    string niem50_AddressState  
    string niem50_FacilityDescriptionText  
    string niem50_FacilityName  
    string niem50_AddressCountyName  
    integer niem50_AdministrationId  
    string niem50_AddressCityName  
}
Jxdm72Judge {
    string jxdm72_JudicialOfficialCategoryText  
    date scales_hasCommissionDate  
    string niem50_PersonRaceText  
    string scales_hasUVAJudgeDirID  
    string niem50_PersonFullName  
    string niem50_PersonSexText  
    double scales_hasFJCNodeID  
    string scales_appointedByParty  
}
Jxdm72RegisterAction {
    date jxdm72_RegisterActionDate  
    string jxdm72_RegisterActionDescriptionText  
}
Jxdm72RegisterOfActions {

}
ScalesCase {
    string niem50_CaseSubCategoryText  
    date niem50_EndDate  
    uri rdf_Type  
    string niem50_CaseGeneralCategoryText  
    string niem50_JurisdictionText  
    uri jxdm72_CaseCharge  
    uri jxdm72_CaseDefendantParty  
    string jxdm72_StatuteKeywordText  
    uri jxdm72_RegisterOfActions  
    string niem50_StatusDescriptionText  
    date niem50_StartDate  
    uri jxdm72_CaseInitiatingParty  
    uri scales_Party  
    uri scales_hasRelatedCase  
    integer niem50_CaseDocketID  
    string niem50_CaseDocketID  
    uri jxdm72_CaseJudge  
}

Jxdm72Case ||--|o Jxdm72RegisterOfActions : "jxdm72_RegisterOfActions"
Jxdm72Charge ||--|o Jxdm72ChargeInstrument : "jxdm72_ChargeInstrument"
Jxdm72Charge ||--|o Jxdm72Case : "scales_ChargeCase"
ScalesCase ||--|o Jxdm72Court : "jxdm72_CaseCourt"
ScalesCase ||--|o ScalesCase : "scales_hasMemberCase"
ScalesCase ||--|o Jxdm72RegisterOfActions : "jxdm72_RegisterOfActions"
ScalesCase ||--|o ScalesCase : "scales_hasRelatedCase"

```



## Classes

| Class | Description |
| --- | --- |
| [Jxdm72Case](classes/Jxdm72Case.md) | No class (type) description specified<br/>Class with 96011 occurrences.| 
| [Jxdm72Charge](classes/Jxdm72Charge.md) | No class (type) description specified<br/>Class with 218359 occurrences.| 
| [Jxdm72ChargeInstrument](classes/Jxdm72ChargeInstrument.md) | No class (type) description specified<br/>Class with 86007 occurrences.| 
| [Jxdm72Court](classes/Jxdm72Court.md) | No class (type) description specified<br/>Class with 94 occurrences.| 
| [Jxdm72DetentionFacility](classes/Jxdm72DetentionFacility.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [Jxdm72Judge](classes/Jxdm72Judge.md) | No class (type) description specified<br/>Class with 5385 occurrences.| 
| [Jxdm72RegisterAction](classes/Jxdm72RegisterAction.md) | No class (type) description specified<br/>Class with 94929 occurrences.| 
| [Jxdm72RegisterOfActions](classes/Jxdm72RegisterOfActions.md) | No class (type) description specified<br/>Class with 94929 occurrences.| 
| [ScalesCase](classes/ScalesCase.md) | No class (type) description specified<br/>Class with 2 occurrences.| 





## Slots

| Slot | Description |
| --- | --- |
| [http___release.niem.gov_niem_codes_fips_5.0_#CountyCode](slots/http___release.niem.gov_niem_codes_fips_5.0_#CountyCode.md) | No slot (predicate) description specified<br/>3035 occurrences with untyped subjects and object type string.|
| [http___release.niem.gov_niem_codes_fips_5.0_CountyCode](slots/http___release.niem.gov_niem_codes_fips_5.0_CountyCode.md) | No slot (predicate) description specified<br/>3035 occurrences with subject type jxdm72_Court and object type string.|
| [http___schemas.scales_okn.org_rdf_ijp#hasFJCNodeID](slots/http___schemas.scales_okn.org_rdf_ijp#hasFJCNodeID.md) | No slot (predicate) description specified<br/>3855 occurrences with untyped subjects and object type double.|
| [http___schemas.scales_okn.org_rdf_ijp#hasUVAJudgeDirID](slots/http___schemas.scales_okn.org_rdf_ijp#hasUVAJudgeDirID.md) | No slot (predicate) description specified<br/>988 occurrences with untyped subjects and object type string.|
| [jxdm72_Attorney](slots/jxdm72_Attorney.md) | No slot (predicate) description specified<br/>386063 occurrences with untyped subjects and object type uri.|
| [jxdm72_BailBondAmount](slots/jxdm72_BailBondAmount.md) | No slot (predicate) description specified<br/>72999 occurrences with untyped subjects and object type uri.|
| [jxdm72_BailBondChargeAssociation](slots/jxdm72_BailBondChargeAssociation.md) | No slot (predicate) description specified<br/>216422 occurrences with untyped subjects and object type jxdm72_Charge.|
| [jxdm72_Case](slots/jxdm72_Case.md) | No slot (predicate) description specified<br/>266314 occurrences with untyped subjects and object type scales_Case.|
| [jxdm72_CaseCharge](slots/jxdm72_CaseCharge.md) | No slot (predicate) description specified<br/>213743 occurrences with subject type scales_Case and object type uri.|
| [jxdm72_CaseCourt](slots/jxdm72_CaseCourt.md) | No slot (predicate) description specified<br/>143 occurrences with subject type scales_Case and object type jxdm72_Court.|
| [jxdm72_CaseDefendantParty](slots/jxdm72_CaseDefendantParty.md) | No slot (predicate) description specified<br/>1852839 occurrences with subject type scales_Case and object type uri.|
| [jxdm72_CaseDefenseAttorney](slots/jxdm72_CaseDefenseAttorney.md) | No slot (predicate) description specified<br/>1890518 occurrences with untyped subjects and object type uri.|
| [jxdm72_CaseInitiatingAttorney](slots/jxdm72_CaseInitiatingAttorney.md) | No slot (predicate) description specified<br/>1854513 occurrences with untyped subjects and object type uri.|
| [jxdm72_CaseInitiatingParty](slots/jxdm72_CaseInitiatingParty.md) | No slot (predicate) description specified<br/>920509 occurrences with subject type scales_Case and object type uri.|
| [jxdm72_CaseJudge](slots/jxdm72_CaseJudge.md) | No slot (predicate) description specified<br/>837266 occurrences with subject type scales_Case and object type uri.|
| [jxdm72_CaseOfficialRoleText](slots/jxdm72_CaseOfficialRoleText.md) | No slot (predicate) description specified<br/>1119175 occurrences with untyped subjects and object type string.|
| [jxdm72_ChargeDescriptionText](slots/jxdm72_ChargeDescriptionText.md) | No slot (predicate) description specified<br/>218535 occurrences with subject type jxdm72_Charge and object type string.|
| [jxdm72_ChargeDisposition](slots/jxdm72_ChargeDisposition.md) | No slot (predicate) description specified<br/>213743 occurrences with untyped subjects and object type string.|
| [jxdm72_ChargeIdentification](slots/jxdm72_ChargeIdentification.md) | No slot (predicate) description specified<br/>218359 occurrences with subject type jxdm72_Charge and object type integer.|
| [jxdm72_ChargeInstrument](slots/jxdm72_ChargeInstrument.md) | No slot (predicate) description specified<br/>199210 occurrences with subject type jxdm72_Charge and object type jxdm72_ChargeInstrument.|
| [jxdm72_ChargeSequenceID](slots/jxdm72_ChargeSequenceID.md) | No slot (predicate) description specified<br/>213743 occurrences with untyped subjects and object type string.|
| [jxdm72_ChargeSeverityText](slots/jxdm72_ChargeSeverityText.md) | No slot (predicate) description specified<br/>218372 occurrences with subject type jxdm72_Charge and object type string.|
| [jxdm72_ChargeText](slots/jxdm72_ChargeText.md) | No slot (predicate) description specified<br/>213743 occurrences with untyped subjects and object type string.|
| [jxdm72_CourtCategoryCode](slots/jxdm72_CourtCategoryCode.md) | No slot (predicate) description specified<br/>94 occurrences with subject type jxdm72_Court and object type string.<br/>94 occurrences with untyped subjects and object type string.|
| [jxdm72_CourtName](slots/jxdm72_CourtName.md) | No slot (predicate) description specified<br/>94 occurrences with subject type jxdm72_Court and object type string.<br/>94 occurrences with untyped subjects and object type string.|
| [jxdm72_JudicialOfficialCategoryText](slots/jxdm72_JudicialOfficialCategoryText.md) | No slot (predicate) description specified<br/>5385 occurrences with subject type jxdm72_Judge and object type string.<br/>5385 occurrences with untyped subjects and object type string.|
| [jxdm72_ParticipantRoleCategoryText](slots/jxdm72_ParticipantRoleCategoryText.md) | No slot (predicate) description specified<br/>2993003 occurrences with untyped subjects and object type string.|
| [jxdm72_PersonCharge](slots/jxdm72_PersonCharge.md) | No slot (predicate) description specified<br/>213743 occurrences with untyped subjects and object type uri.|
| [jxdm72_RegisterAction](slots/jxdm72_RegisterAction.md) | No slot (predicate) description specified<br/>19671603 occurrences with untyped subjects and object type uri.|
| [jxdm72_RegisterActionDate](slots/jxdm72_RegisterActionDate.md) | No slot (predicate) description specified<br/>421518 occurrences with subject type jxdm72_RegisterAction and object type date.<br/>19671603 occurrences with untyped subjects and object type date.|
| [jxdm72_RegisterActionDescriptionText](slots/jxdm72_RegisterActionDescriptionText.md) | No slot (predicate) description specified<br/>561095 occurrences with subject type jxdm72_RegisterAction and object type string.<br/>19671841 occurrences with untyped subjects and object type string.|
| [jxdm72_RegisterOfActions](slots/jxdm72_RegisterOfActions.md) | No slot (predicate) description specified<br/>581243 occurrences with subject type scales_Case and object type uri.<br/>94929 occurrences with subject type jxdm72_Case and object type jxdm72_RegisterOfActions.|
| [jxdm72_StatuteKeywordText](slots/jxdm72_StatuteKeywordText.md) | No slot (predicate) description specified<br/>2680 occurrences with subject type scales_Case and object type string.|
| [niem50_#AddressPostalCode](slots/niem50_#AddressPostalCode.md) | No slot (predicate) description specified<br/>40932 occurrences with untyped subjects and object type string.|
| [niem50_AddressCityName](slots/niem50_AddressCityName.md) | No slot (predicate) description specified<br/>1 occurrences with subject type jxdm72_DetentionFacility and object type string.|
| [niem50_AddressCountyName](slots/niem50_AddressCountyName.md) | No slot (predicate) description specified<br/>1 occurrences with subject type jxdm72_DetentionFacility and object type string.|
| [niem50_AddressPostalCode](slots/niem50_AddressPostalCode.md) | No slot (predicate) description specified<br/>40932 occurrences with subject type jxdm72_Court and object type string.|
| [niem50_AddressState](slots/niem50_AddressState.md) | No slot (predicate) description specified<br/>1 occurrences with subject type jxdm72_DetentionFacility and object type string.|
| [niem50_AdministrationId](slots/niem50_AdministrationId.md) | No slot (predicate) description specified<br/>1 occurrences with subject type jxdm72_DetentionFacility and object type integer.|
| [niem50_AdministrativeID](slots/niem50_AdministrativeID.md) | No slot (predicate) description specified<br/>19671603 occurrences with untyped subjects and object type string.|
| [niem50_Amount](slots/niem50_Amount.md) | No slot (predicate) description specified<br/>73497 occurrences with untyped subjects and object type float.|
| [niem50_CaseDocketID](slots/niem50_CaseDocketID.md) | No slot (predicate) description specified<br/>272547 occurrences with subject type scales_Case and object type string.<br/>96011 occurrences with subject type jxdm72_Case and object type integer.|
| [niem50_CaseGeneralCategoryText](slots/niem50_CaseGeneralCategoryText.md) | No slot (predicate) description specified<br/>2 occurrences with subject type scales_Case and object type string.|
| [niem50_CaseSubCategoryText](slots/niem50_CaseSubCategoryText.md) | No slot (predicate) description specified<br/>104 occurrences with subject type scales_Case and object type string.|
| [niem50_ContactMailingAddress](slots/niem50_ContactMailingAddress.md) | No slot (predicate) description specified<br/>2023829 occurrences with untyped subjects and object type string.|
| [niem50_DocumentDescriptionText](slots/niem50_DocumentDescriptionText.md) | No slot (predicate) description specified<br/>94949 occurrences with subject type jxdm72_ChargeInstrument and object type string.|
| [niem50_DocumentEffectiveDate](slots/niem50_DocumentEffectiveDate.md) | No slot (predicate) description specified<br/>92142 occurrences with subject type jxdm72_ChargeInstrument and object type date.|
| [niem50_DocumentFiledDate](slots/niem50_DocumentFiledDate.md) | No slot (predicate) description specified<br/>86007 occurrences with subject type jxdm72_ChargeInstrument and object type date.|
| [niem50_DocumentStatus](slots/niem50_DocumentStatus.md) | No slot (predicate) description specified<br/>101588 occurrences with subject type jxdm72_ChargeInstrument and object type string.|
| [niem50_EndDate](slots/niem50_EndDate.md) | No slot (predicate) description specified<br/>9629 occurrences with subject type scales_Case and object type date.|
| [niem50_EntityName](slots/niem50_EntityName.md) | No slot (predicate) description specified<br/>3004657 occurrences with untyped subjects and object type string.|
| [niem50_FacilityDescriptionText](slots/niem50_FacilityDescriptionText.md) | No slot (predicate) description specified<br/>1 occurrences with subject type jxdm72_DetentionFacility and object type string.|
| [niem50_FacilityName](slots/niem50_FacilityName.md) | No slot (predicate) description specified<br/>1 occurrences with subject type jxdm72_DetentionFacility and object type string.|
| [niem50_JurisdictionText](slots/niem50_JurisdictionText.md) | No slot (predicate) description specified<br/>32 occurrences with subject type scales_Case and object type string.|
| [niem50_OrganizationName](slots/niem50_OrganizationName.md) | No slot (predicate) description specified<br/>1920883 occurrences with untyped subjects and object type string.|
| [niem50_PersonFullName](slots/niem50_PersonFullName.md) | No slot (predicate) description specified<br/>4973752 occurrences with untyped subjects and object type string.<br/>5385 occurrences with subject type jxdm72_Judge and object type string.|
| [niem50_PersonRaceText](slots/niem50_PersonRaceText.md) | No slot (predicate) description specified<br/>3762 occurrences with subject type jxdm72_Judge and object type string.|
| [niem50_PersonSexText](slots/niem50_PersonSexText.md) | No slot (predicate) description specified<br/>3762 occurrences with subject type jxdm72_Judge and object type string.|
| [niem50_StartDate](slots/niem50_StartDate.md) | No slot (predicate) description specified<br/>6852 occurrences with subject type scales_Case and object type date.|
| [niem50_StatusDescriptionText](slots/niem50_StatusDescriptionText.md) | No slot (predicate) description specified<br/>4 occurrences with subject type scales_Case and object type string.|
| [rdf_Type](slots/rdf_Type.md) | No slot (predicate) description specified<br/>10426705 occurrences with untyped subjects and object type uri.<br/>2 occurrences with subject type scales_Case and object type uri.|
| [scales_appointedByParty](slots/scales_appointedByParty.md) | No slot (predicate) description specified<br/>3912 occurrences with subject type jxdm72_Judge and object type string.|
| [scales_assignedToDefendant](slots/scales_assignedToDefendant.md) | No slot (predicate) description specified<br/>28750 occurrences with untyped subjects and object type uri.|
| [scales_ChargeCase](slots/scales_ChargeCase.md) | No slot (predicate) description specified<br/>218359 occurrences with subject type jxdm72_Charge and object type jxdm72_Case.|
| [scales_Firm](slots/scales_Firm.md) | No slot (predicate) description specified<br/>1920886 occurrences with untyped subjects and object type uri.|
| [scales_hasBondType](slots/scales_hasBondType.md) | No slot (predicate) description specified<br/>76888 occurrences with subject type jxdm72_Charge and object type string.|
| [scales_hasChargeType](slots/scales_hasChargeType.md) | No slot (predicate) description specified<br/>213743 occurrences with untyped subjects and object type string.|
| [scales_hasCommissionDate](slots/scales_hasCommissionDate.md) | No slot (predicate) description specified<br/>4257 occurrences with subject type jxdm72_Judge and object type date.|
| [scales_hasExtraInfo](slots/scales_hasExtraInfo.md) | No slot (predicate) description specified<br/>625618 occurrences with untyped subjects and object type string.|
| [scales_hasFJCNodeID](slots/scales_hasFJCNodeID.md) | No slot (predicate) description specified<br/>3855 occurrences with subject type jxdm72_Judge and object type double.|
| [scales_hasHighestOffenseLevelOpening](slots/scales_hasHighestOffenseLevelOpening.md) | No slot (predicate) description specified<br/>93222 occurrences with untyped subjects and object type string.|
| [scales_hasHighestOffenseLevelTerminated](slots/scales_hasHighestOffenseLevelTerminated.md) | No slot (predicate) description specified<br/>38306 occurrences with untyped subjects and object type string.|
| [scales_hasJudgeReference](slots/scales_hasJudgeReference.md) | No slot (predicate) description specified<br/>6256896 occurrences with untyped subjects and object type jxdm72_Judge.<br/>23177 occurrences with untyped subjects and object type uri.|
| [scales_hasMemberCase](slots/scales_hasMemberCase.md) | No slot (predicate) description specified<br/>2 occurrences with subject type scales_Case and object type scales_Case.<br/>1 occurrences with untyped subjects and object type scales_Case.|
| [scales_hasPartyReferenceInExtraInfo](slots/scales_hasPartyReferenceInExtraInfo.md) | No slot (predicate) description specified<br/>111441 occurrences with untyped subjects and object type uri.|
| [scales_hasReferenceToOtherEntry](slots/scales_hasReferenceToOtherEntry.md) | No slot (predicate) description specified<br/>7002793 occurrences with untyped subjects and object type uri.|
| [scales_hasRelatedCase](slots/scales_hasRelatedCase.md) | No slot (predicate) description specified<br/>4 occurrences with subject type scales_Case and object type scales_Case.<br/>1 occurrences with subject type scales_Case and object type uri.|
| [scales_hasUVAJudgeDirID](slots/scales_hasUVAJudgeDirID.md) | No slot (predicate) description specified<br/>988 occurrences with subject type jxdm72_Judge and object type string.|
| [scales_isInCircuit](slots/scales_isInCircuit.md) | No slot (predicate) description specified<br/>94 occurrences with subject type jxdm72_Court and object type string.<br/>94 occurrences with untyped subjects and object type string.|
| [scales_isInstanceOfEntity](slots/scales_isInstanceOfEntity.md) | No slot (predicate) description specified<br/>939873 occurrences with untyped subjects and object type uri.<br/>715622 occurrences with untyped subjects and object type jxdm72_Judge.|
| [scales_Party](slots/scales_Party.md) | No slot (predicate) description specified<br/>231186 occurrences with subject type scales_Case and object type uri.|









## IRI prefixes

* jxdm72: http://release.niem.gov/niem/domains/jxdm/7.2/#
* linkml: https://w3id.org/linkml/
* niem50: http://release.niem.gov/niem/niem-core/5.0/
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* scales: http://schemas.scales-okn.org/rdf/scales#
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
* schema: http://schema.org/
