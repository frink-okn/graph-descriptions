# RuralKG Ontology

An ontology which serves the schema for the cross-domain knowledge graph (Rural-KG) to integrate health and justice data for rural resilience.

URI: rural-kg

Name: rural-kg



## Schema Diagram

```mermaid
erDiagram
RuralAdministrativeareaAdministrativeArea {

}
RuralAdministrativeareaCity {
    integer rural_administrativearea_ranking  
    float rural_administrativearea_longitude  
    string rural_administrativearea_name  
    float rural_administrativearea_latitude  
}
RuralAdministrativeareaCounty {
    string rural_administrativearea_fips  
    string rural_administrativearea_name  
}
RuralAdministrativeareaState {
    string rural_administrativearea_abbreviation  
    string rural_administrativearea_fips  
    string rural_administrativearea_name  
}
RuralMentalhealthserviceMentalHealth {

}
RuralMentalhealthserviceMentalHealthService {
    string rural_mentalhealthservice_description  
    string rural_mentalhealthservice_code  
    integer rural_mentalhealthservice_year  
    string rural_mentalhealthservice_name  
}
RuralMentalhealthserviceMentalHealthServiceCategory {
    string rural_mentalhealthservice_code  
    string rural_mentalhealthservice_name  
    integer rural_mentalhealthservice_year  
}
RuralSettlementtypeCountyStatus {
    integer rural_settlementtype_year  
    integer rural_settlementtype_population  
}
RuralSettlementtypeRUCC {
    string rural_settlementtype_code  
    integer rural_settlementtype_year  
    string rural_settlementtype_description  
}
RuralSettlementtypeSettlementType {

}
RuralSubstanceabuseSubstance {
    string rural_substanceabuse_name  
    integer rural_substanceabuse_year  
    string rural_substanceabuse_sourceDataset  
    string rural_substanceabuse_code  
}
RuralSubstanceabuseSubstanceAbuse {

}
RuralSubstanceabuseSubstanceRelatedIncident {
    string rural_substanceabuse_name  
    string rural_substanceabuse_sourceDataset  
    integer rural_substanceabuse_year  
}
RuralTreatmentproviderTreatmentProvider {
    uri rural_treatmentprovider_inCity  
    string rural_treatmentprovider_name  
    string rural_treatmentprovider_alias  
    string rural_treatmentprovider_address  
    string rural_treatmentprovider_phone  
    string rural_treatmentprovider_zipcode  
}

RuralAdministrativeareaCity ||--|o RuralAdministrativeareaCounty : "rural_administrativearea_primaryCounty"
RuralAdministrativeareaState ||--|o RuralAdministrativeareaCounty : "rural_administrativearea_containsPlace"
RuralMentalhealthserviceMentalHealthServiceCategory ||--|o RuralMentalhealthserviceMentalHealthService : "rural_mentalhealthservice_containsService"
RuralSettlementtypeCountyStatus ||--|o RuralAdministrativeareaCounty : "rural_settlementtype_censusCounty"
RuralSettlementtypeCountyStatus ||--|o RuralSettlementtypeRUCC : "rural_settlementtype_hasRUCC"
RuralTreatmentproviderTreatmentProvider ||--|o RuralMentalhealthserviceMentalHealthService : "rural_treatmentprovider_providesService"
RuralTreatmentproviderTreatmentProvider ||--|o RuralAdministrativeareaCity : "rural_treatmentprovider_inCity"

```


## IRI prefixes

* linkml: https://w3id.org/linkml/
* rural: http://sail.ua.edu/ruralkg/
* xsd: http://www.w3.org/2001/XMLSchema#



## Classes

| Class | Description |
| --- | --- |
| [RuralAdministrativeareaAdministrativeArea](classes/RuralAdministrativeareaAdministrativeArea.md) | None<br/>| 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RuralAdministrativeareaCity](classes/RuralAdministrativeareaCity.md) | City entities within a county or state.<br/>| 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RuralAdministrativeareaCounty](classes/RuralAdministrativeareaCounty.md) | Defines counties within a state.<br/>| 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RuralAdministrativeareaState](classes/RuralAdministrativeareaState.md) | Represents individual states within U.S.<br/>| 
| [RuralMentalhealthserviceMentalHealth](classes/RuralMentalhealthserviceMentalHealth.md) | Mental health services, sourcing from services defined in National Directory Of Mental Health Treatment Facilities.<br/>| 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RuralMentalhealthserviceMentalHealthService](classes/RuralMentalhealthserviceMentalHealthService.md) | Specific mental health services offered.<br/>| 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RuralMentalhealthserviceMentalHealthServiceCategory](classes/RuralMentalhealthserviceMentalHealthServiceCategory.md) | Categories of mental health services.<br/>| 
| [RuralSettlementtypeSettlementType](classes/RuralSettlementtypeSettlementType.md) | None<br/>| 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RuralSettlementtypeCountyStatus](classes/RuralSettlementtypeCountyStatus.md) | Status of a county in terms of rural or urban classification.<br/>| 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RuralSettlementtypeRUCC](classes/RuralSettlementtypeRUCC.md) | Rural-Urban Continuum Code classification.<br/>| 
| [RuralSubstanceabuseSubstanceAbuse](classes/RuralSubstanceabuseSubstanceAbuse.md) | Categories of substance type and related incident types, extracted from National Survey on Drug Use and Health (NSDUH).<br/>| 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RuralSubstanceabuseSubstance](classes/RuralSubstanceabuseSubstance.md) | Types of substances that can be abused.<br/>| 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RuralSubstanceabuseSubstanceRelatedIncident](classes/RuralSubstanceabuseSubstanceRelatedIncident.md) | Types of incidents related to substance abuse.<br/>| 
| [RuralTreatmentproviderTreatmentProvider](classes/RuralTreatmentproviderTreatmentProvider.md) | Entities that provide treatment services, sourcing from National Directory Of Mental Health Treatment Facilities.<br/>| 





## Slots

| Slot | Description |
| --- | --- |
| [rural_administrativearea_abbreviation](slots/rural_administrativearea_abbreviation.md) | No slot description provided<br/>56 occurrences with subject type rural_administrativearea_State and object type string.|
| [rural_administrativearea_containsPlace](slots/rural_administrativearea_containsPlace.md) | No slot description provided<br/>3253 occurrences with subject type rural_administrativearea_State and object type rural_administrativearea_County.|
| [rural_administrativearea_fips](slots/rural_administrativearea_fips.md) | No slot description provided<br/>3253 occurrences with subject type rural_administrativearea_County and object type string.<br/>56 occurrences with subject type rural_administrativearea_State and object type string.|
| [rural_administrativearea_latitude](slots/rural_administrativearea_latitude.md) | No slot description provided<br/>31120 occurrences with subject type rural_administrativearea_City and object type float.|
| [rural_administrativearea_longitude](slots/rural_administrativearea_longitude.md) | No slot description provided<br/>31120 occurrences with subject type rural_administrativearea_City and object type float.|
| [rural_administrativearea_name](slots/rural_administrativearea_name.md) | No slot description provided<br/>31120 occurrences with subject type rural_administrativearea_City and object type string.<br/>3253 occurrences with subject type rural_administrativearea_County and object type string.<br/>56 occurrences with subject type rural_administrativearea_State and object type string.|
| [rural_administrativearea_primaryCounty](slots/rural_administrativearea_primaryCounty.md) | No slot description provided<br/>31120 occurrences with subject type rural_administrativearea_City and object type rural_administrativearea_County.|
| [rural_administrativearea_ranking](slots/rural_administrativearea_ranking.md) | No slot description provided<br/>31120 occurrences with subject type rural_administrativearea_City and object type integer.|
| [rural_mentalhealthservice_code](slots/rural_mentalhealthservice_code.md) | No slot description provided<br/>176 occurrences with subject type rural_mentalhealthservice_MentalHealthService and object type string.<br/>21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory and object type string.|
| [rural_mentalhealthservice_containsService](slots/rural_mentalhealthservice_containsService.md) | No slot description provided<br/>176 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory and object type rural_mentalhealthservice_MentalHealthService.|
| [rural_mentalhealthservice_description](slots/rural_mentalhealthservice_description.md) | No slot description provided<br/>176 occurrences with subject type rural_mentalhealthservice_MentalHealthService and object type string.|
| [rural_mentalhealthservice_name](slots/rural_mentalhealthservice_name.md) | No slot description provided<br/>176 occurrences with subject type rural_mentalhealthservice_MentalHealthService and object type string.<br/>21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory and object type string.|
| [rural_mentalhealthservice_year](slots/rural_mentalhealthservice_year.md) | No slot description provided<br/>176 occurrences with subject type rural_mentalhealthservice_MentalHealthService and object type integer.<br/>21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory and object type integer.|
| [rural_settlementtype_censusCounty](slots/rural_settlementtype_censusCounty.md) | No slot description provided<br/>3234 occurrences with subject type rural_settlementtype_CountyStatus and object type rural_administrativearea_County.|
| [rural_settlementtype_code](slots/rural_settlementtype_code.md) | No slot description provided<br/>10 occurrences with subject type rural_settlementtype_RUCC and object type string.|
| [rural_settlementtype_description](slots/rural_settlementtype_description.md) | No slot description provided<br/>10 occurrences with subject type rural_settlementtype_RUCC and object type string.|
| [rural_settlementtype_hasRUCC](slots/rural_settlementtype_hasRUCC.md) | No slot description provided<br/>3234 occurrences with subject type rural_settlementtype_CountyStatus and object type rural_settlementtype_RUCC.|
| [rural_settlementtype_population](slots/rural_settlementtype_population.md) | No slot description provided<br/>3234 occurrences with subject type rural_settlementtype_CountyStatus and object type integer.|
| [rural_settlementtype_year](slots/rural_settlementtype_year.md) | No slot description provided<br/>3234 occurrences with subject type rural_settlementtype_CountyStatus and object type integer.<br/>10 occurrences with subject type rural_settlementtype_RUCC and object type integer.|
| [rural_substanceabuse_code](slots/rural_substanceabuse_code.md) | No slot description provided<br/>25 occurrences with subject type rural_substanceabuse_Substance and object type string.|
| [rural_substanceabuse_name](slots/rural_substanceabuse_name.md) | No slot description provided<br/>25 occurrences with subject type rural_substanceabuse_Substance and object type string.<br/>17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and object type string.|
| [rural_substanceabuse_sourceDataset](slots/rural_substanceabuse_sourceDataset.md) | No slot description provided<br/>17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and object type string.<br/>25 occurrences with subject type rural_substanceabuse_Substance and object type string.|
| [rural_substanceabuse_year](slots/rural_substanceabuse_year.md) | No slot description provided<br/>25 occurrences with subject type rural_substanceabuse_Substance and object type integer.<br/>17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and object type integer.|
| [rural_treatmentprovider_address](slots/rural_treatmentprovider_address.md) | No slot description provided<br/>9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type string.|
| [rural_treatmentprovider_alias](slots/rural_treatmentprovider_alias.md) | No slot description provided<br/>9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type string.|
| [rural_treatmentprovider_inCity](slots/rural_treatmentprovider_inCity.md) | No slot description provided<br/>8117 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type rural_administrativearea_City.<br/>920 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type uri.|
| [rural_treatmentprovider_name](slots/rural_treatmentprovider_name.md) | No slot description provided<br/>9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type string.|
| [rural_treatmentprovider_phone](slots/rural_treatmentprovider_phone.md) | No slot description provided<br/>9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type string.|
| [rural_treatmentprovider_providesService](slots/rural_treatmentprovider_providesService.md) | No slot description provided<br/>442841 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type rural_mentalhealthservice_MentalHealthService.|
| [rural_treatmentprovider_zipcode](slots/rural_treatmentprovider_zipcode.md) | No slot description provided<br/>9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type string.|







