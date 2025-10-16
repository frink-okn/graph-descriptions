# nikg





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
PhilaBlockGroup {

}
PhilaCensusTract {

}
PhilaIncident {
    boolean phila_is_fatal  
    string phila_OffenderWound  
    boolean phila_OffenderDeceased  
    uri phila_OffenderSex  
    boolean phila_OfficerInvolved  
    boolean phila_OffenderInjured  
    http___qudt.org_vocab_unit_YR phila_age_of  
    string phila_OffenderRace  
    uri phila_OffenderRace  
}
PhilaLocation {

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
PhilaBlockGroup ||--|o PhilaCensusTract : "phila_belongs_to"
PhilaIncident ||--|o RdfsLiteral : "dct_date"
PhilaIncident ||--|o PhilaCensusTract : "phila_happened_at"

```



## Imports


* okns:extended_types
* linkml:types
* okns:dc



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [PhilaBlockGroup](classes/PhilaBlockGroup.md) | None<br/>| 8 | 
| [PhilaCensusTract](classes/PhilaCensusTract.md) | None<br/>| 361 | 
| [PhilaIncident](classes/PhilaIncident.md) | None<br/>| 15328 | 
| [PhilaLocation](classes/PhilaLocation.md) | None<br/>| 9131 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [phila_age_of](slots/phila_age_of.md) | <br/>| 15093 |
| [phila_belongs_to](slots/phila_belongs_to.md) | <br/>| 1250 |
| [phila_happened_at](slots/phila_happened_at.md) | <br/>| 15328 |
| [phila_is_fatal](slots/phila_is_fatal.md) | <br/>| 15205 |
| [phila_OffenderDeceased](slots/phila_OffenderDeceased.md) | <br/>| 15328 |
| [phila_OffenderInjured](slots/phila_OffenderInjured.md) | <br/>| 15328 |
| [phila_OffenderRace](slots/phila_OffenderRace.md) | <br/>| 15205 |
| [phila_OffenderSex](slots/phila_OffenderSex.md) | <br/>| 15328 |
| [phila_OffenderWound](slots/phila_OffenderWound.md) | <br/>| 15200 |
| [phila_OfficerInvolved](slots/phila_OfficerInvolved.md) | <br/>| 15328 |






## Types

| Type | Description |
| --- | --- |
| [HttpQudt.orgVocabUnitYR](types/HttpQudt.orgVocabUnitYR.md) |  |





## IRI prefixes

* dct: http://purl.org/dc/terms/
* linkml: https://w3id.org/linkml/
* okn: https://purl.org/okn/
* okns: https://purl.org/okn/schema/
* phila: https://metadata.phila.gov/
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* wd: http://www.wikidata.org/entity/
