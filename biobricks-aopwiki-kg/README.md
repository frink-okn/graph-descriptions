# biobricks-aopwiki





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
SkosCollection {

}
SkosConcept {

}
SkosConceptScheme {

}
SkosOrderedCollection {

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
EdamData1025 {
    string edam_data_2298  
    uri rdfs_seeAlso  
    string edam_data_1033  
    string edam_data_1027  
    string edam_data_2291  
}
EdamData1027 {
    string edam_data_1027  
}
EdamData1033 {
    string edam_data_1033  
}
EdamData2291 {
    uri rdfs_seeAlso  
    string edam_data_2291  
}
EdamData2298 {
    string edam_data_2298  
}
HttpAopkb.orgAopOntology#AdverseOutcomePathway {
    string obo_PATO_0000047  
    string http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25725  
    string http___aopkb.org_aop_ontology#LifeStageContext  
    string edam_operation_3799  
    date dct_modified  
    uri rdfs_seeAlso  
    string http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25217  
    string http___aopkb.org_aop_ontology#AopContext  
    string http___aopkb.org_aop_ontology#has_evidence  
    string http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C48192  
    string rdfs_label  
    string http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25688  
}
HttpAopkb.orgAopOntology#CellTypeContext {

}
HttpAopkb.orgAopOntology#KeyEvent {
    string obo_PATO_0000047  
    string obo_PATO_0000001  
    string obo_MMO_0000000  
    string http___purl.bioontology.org_ontology_NCBITAXON_131567  
    string http___aopkb.org_aop_ontology#LifeStageContext  
    string http___aopkb.org_aop_ontology#CellTypeContext  
    uri rdfs_seeAlso  
    string obo_PATO_0001241  
    uri obo_PATO_0001241  
    string http___aopkb.org_aop_ontology#OrganContext  
    string http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25664  
    string rdfs_label  
}
HttpAopkb.orgAopOntology#KeyEventRelationship {
    string http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C71478  
    uri rdfs_seeAlso  
    string http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C80263  
    string rdfs_label  
    string edam_data_2042  
    date dct_modified  
}
HttpAopkb.orgAopOntology#OrganContext {

}
HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 {
    string rdfs_label  
    date dct_modified  
    string http___aopkb.org_aop_ontology#has_chemical_entity  
}
HttpPurl.bioontology.orgOntologyNCBITAXON131567 {

}
HttpSemanticscience.orgResourceCHEMINF000000 {
    uri http___semanticscience.org_resource_CHEMINF_000059  
    uri http___semanticscience.org_resource_CHEMINF_000568  
    string http___semanticscience.org_resource_CHEMINF_000446  
}
HttpSemanticscience.orgResourceCHEMINF000140 {
    string http___semanticscience.org_resource_CHEMINF_000140  
}
HttpSemanticscience.orgResourceCHEMINF000405 {
    string http___semanticscience.org_resource_CHEMINF_000405  
}
HttpSemanticscience.orgResourceCHEMINF000406 {
    string http___semanticscience.org_resource_CHEMINF_000406  
}
HttpSemanticscience.orgResourceCHEMINF000407 {
    string http___semanticscience.org_resource_CHEMINF_000407  
}
HttpSemanticscience.orgResourceCHEMINF000408 {
    string http___semanticscience.org_resource_CHEMINF_000408  
}
HttpSemanticscience.orgResourceCHEMINF000409 {
    string http___semanticscience.org_resource_CHEMINF_000409  
}
HttpSemanticscience.orgResourceCHEMINF000412 {
    string http___semanticscience.org_resource_CHEMINF_000412  
}
HttpSemanticscience.orgResourceCHEMINF000446 {
    uri http___semanticscience.org_resource_CHEMINF_000059  
    uri http___semanticscience.org_resource_CHEMINF_000568  
    string http___semanticscience.org_resource_CHEMINF_000446  
}
HttpSemanticscience.orgResourceCHEMINF000564 {
    string http___semanticscience.org_resource_CHEMINF_000564  
}
HttpSemanticscience.orgResourceCHEMINF000567 {
    string http___semanticscience.org_resource_CHEMINF_000567  
}
OboGO0008150 {

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
EdamData1025 ||--|o RdfsResource : "rdfs_seeAlso"
EdamData1025 ||--|o OwlThing : "owl_sameAs"
EdamData2291 ||--|o RdfsResource : "rdfs_seeAlso"
EdamData2291 ||--|o OwlThing : "owl_sameAs"
HttpAopkb.orgAopOntology#AdverseOutcomePathway ||--|o HttpAopkb.orgAopOntology#KeyEvent : "http___aopkb.org_aop_ontology#has_key_event"
HttpAopkb.orgAopOntology#AdverseOutcomePathway ||--|o HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 : "http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571"
HttpAopkb.orgAopOntology#AdverseOutcomePathway ||--|o HttpAopkb.orgAopOntology#KeyEventRelationship : "http___aopkb.org_aop_ontology#has_key_event_relationship"
HttpAopkb.orgAopOntology#AdverseOutcomePathway ||--|o RdfsLiteral : "dct_alternative"
HttpAopkb.orgAopOntology#AdverseOutcomePathway ||--|o RdfsLiteral : "dct_modified"
HttpAopkb.orgAopOntology#AdverseOutcomePathway ||--|o HttpAopkb.orgAopOntology#KeyEvent : "http___aopkb.org_aop_ontology#has_adverse_outcome"
HttpAopkb.orgAopOntology#AdverseOutcomePathway ||--|o RdfsResource : "rdfs_seeAlso"
HttpAopkb.orgAopOntology#AdverseOutcomePathway ||--|o FoafDocument : "foaf_page"
HttpAopkb.orgAopOntology#AdverseOutcomePathway ||--|o HttpAopkb.orgAopOntology#KeyEvent : "http___aopkb.org_aop_ontology#has_molecular_initiating_event"
HttpAopkb.orgAopOntology#AdverseOutcomePathway ||--|o RdfsLiteral : "rdfs_label"
HttpAopkb.orgAopOntology#AdverseOutcomePathway ||--|o RdfsLiteral : "dct_created"
HttpAopkb.orgAopOntology#KeyEvent ||--|o RdfsLiteral : "dct_alternative"
HttpAopkb.orgAopOntology#KeyEvent ||--|o OboGO0008150 : "obo_GO_0008150"
HttpAopkb.orgAopOntology#KeyEvent ||--|o HttpPurl.bioontology.orgOntologyNCBITAXON131567 : "http___purl.bioontology.org_ontology_NCBITAXON_131567"
HttpAopkb.orgAopOntology#KeyEvent ||--|o EdamData1025 : "edam_data_1025"
HttpAopkb.orgAopOntology#KeyEvent ||--|o EdamData2298 : "edam_data_1025"
HttpAopkb.orgAopOntology#KeyEvent ||--|o HttpAopkb.orgAopOntology#CellTypeContext : "http___aopkb.org_aop_ontology#CellTypeContext"
HttpAopkb.orgAopOntology#KeyEvent ||--|o RdfsResource : "rdfs_seeAlso"
HttpAopkb.orgAopOntology#KeyEvent ||--|o OboGO0008150 : "obo_PATO_0001241"
HttpAopkb.orgAopOntology#KeyEvent ||--|o HttpAopkb.orgAopOntology#CellTypeContext : "obo_PATO_0001241"
HttpAopkb.orgAopOntology#KeyEvent ||--|o HttpAopkb.orgAopOntology#OrganContext : "obo_PATO_0001241"
HttpAopkb.orgAopOntology#KeyEvent ||--|o FoafDocument : "foaf_page"
HttpAopkb.orgAopOntology#KeyEvent ||--|o HttpAopkb.orgAopOntology#OrganContext : "http___aopkb.org_aop_ontology#OrganContext"
HttpAopkb.orgAopOntology#KeyEvent ||--|o RdfsLiteral : "rdfs_label"
HttpAopkb.orgAopOntology#KeyEventRelationship ||--|o RdfsResource : "rdfs_seeAlso"
HttpAopkb.orgAopOntology#KeyEventRelationship ||--|o FoafDocument : "foaf_page"
HttpAopkb.orgAopOntology#KeyEventRelationship ||--|o HttpAopkb.orgAopOntology#KeyEvent : "http___aopkb.org_aop_ontology#has_upstream_key_event"
HttpAopkb.orgAopOntology#KeyEventRelationship ||--|o RdfsLiteral : "rdfs_label"
HttpAopkb.orgAopOntology#KeyEventRelationship ||--|o HttpAopkb.orgAopOntology#KeyEvent : "http___aopkb.org_aop_ontology#has_downstream_key_event"
HttpAopkb.orgAopOntology#KeyEventRelationship ||--|o RdfsLiteral : "dct_modified"
HttpAopkb.orgAopOntology#KeyEventRelationship ||--|o EdamData1025 : "edam_data_1025"
HttpAopkb.orgAopOntology#KeyEventRelationship ||--|o EdamData2298 : "edam_data_1025"
HttpAopkb.orgAopOntology#KeyEventRelationship ||--|o RdfsLiteral : "dct_created"
HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 ||--|o FoafDocument : "foaf_page"
HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 ||--|o RdfsLiteral : "rdfs_label"
HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 ||--|o RdfsLiteral : "dct_modified"
HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 ||--|o HttpSemanticscience.orgResourceCHEMINF000000 : "http___aopkb.org_aop_ontology#has_chemical_entity"
HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 ||--|o HttpSemanticscience.orgResourceCHEMINF000446 : "http___aopkb.org_aop_ontology#has_chemical_entity"
HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 ||--|o RdfsLiteral : "dct_created"
HttpSemanticscience.orgResourceCHEMINF000000 ||--|o RdfsLiteral : "dct_alternative"
HttpSemanticscience.orgResourceCHEMINF000446 ||--|o RdfsLiteral : "dct_alternative"

```



## Imports


* okns:dc
* linkml:types
* okns:owl-rdf-rdfs
* okns:foaf
* okns:skos
* okns:extended_types



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [EdamData1025](classes/EdamData1025.md) | None<br/>| 12500 | 
| [EdamData1027](classes/EdamData1027.md) | None<br/>| 1518 | 
| [EdamData1033](classes/EdamData1033.md) | None<br/>| 1478 | 
| [EdamData2291](classes/EdamData2291.md) | None<br/>| 7883 | 
| [EdamData2298](classes/EdamData2298.md) | None<br/>| 1621 | 
| [HttpAopkb.orgAopOntology#AdverseOutcomePathway](classes/HttpAopkb.orgAopOntology#AdverseOutcomePathway.md) | None<br/>| 493 | 
| [HttpAopkb.orgAopOntology#CellTypeContext](classes/HttpAopkb.orgAopOntology#CellTypeContext.md) | None<br/>| 69 | 
| [HttpAopkb.orgAopOntology#KeyEvent](classes/HttpAopkb.orgAopOntology#KeyEvent.md) | None<br/>| 1469 | 
| [HttpAopkb.orgAopOntology#KeyEventRelationship](classes/HttpAopkb.orgAopOntology#KeyEventRelationship.md) | None<br/>| 2060 | 
| [HttpAopkb.orgAopOntology#OrganContext](classes/HttpAopkb.orgAopOntology#OrganContext.md) | None<br/>| 83 | 
| [HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571](classes/HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571.md) | None<br/>| 658 | 
| [HttpPurl.bioontology.orgOntologyNCBITAXON131567](classes/HttpPurl.bioontology.orgOntologyNCBITAXON131567.md) | None<br/>| 166 | 
| [HttpSemanticscience.orgResourceCHEMINF000000](classes/HttpSemanticscience.orgResourceCHEMINF000000.md) | None<br/>| 391 | 
| [HttpSemanticscience.orgResourceCHEMINF000140](classes/HttpSemanticscience.orgResourceCHEMINF000140.md) | None<br/>| 403 | 
| [HttpSemanticscience.orgResourceCHEMINF000405](classes/HttpSemanticscience.orgResourceCHEMINF000405.md) | None<br/>| 406 | 
| [HttpSemanticscience.orgResourceCHEMINF000406](classes/HttpSemanticscience.orgResourceCHEMINF000406.md) | None<br/>| 210 | 
| [HttpSemanticscience.orgResourceCHEMINF000407](classes/HttpSemanticscience.orgResourceCHEMINF000407.md) | None<br/>| 799 | 
| [HttpSemanticscience.orgResourceCHEMINF000408](classes/HttpSemanticscience.orgResourceCHEMINF000408.md) | None<br/>| 408 | 
| [HttpSemanticscience.orgResourceCHEMINF000409](classes/HttpSemanticscience.orgResourceCHEMINF000409.md) | None<br/>| 302 | 
| [HttpSemanticscience.orgResourceCHEMINF000412](classes/HttpSemanticscience.orgResourceCHEMINF000412.md) | None<br/>| 333 | 
| [HttpSemanticscience.orgResourceCHEMINF000446](classes/HttpSemanticscience.orgResourceCHEMINF000446.md) | None<br/>| 391 | 
| [HttpSemanticscience.orgResourceCHEMINF000564](classes/HttpSemanticscience.orgResourceCHEMINF000564.md) | None<br/>| 34 | 
| [HttpSemanticscience.orgResourceCHEMINF000567](classes/HttpSemanticscience.orgResourceCHEMINF000567.md) | None<br/>| 402 | 
| [OboGO0008150](classes/OboGO0008150.md) | None<br/>| 504 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [edam_data_1025](slots/edam_data_1025.md) | <br/>| 5976 |
| [edam_data_1027](slots/edam_data_1027.md) | <br/>| 1518 |
| [edam_data_1033](slots/edam_data_1033.md) | <br/>| 1478 |
| [edam_data_2042](slots/edam_data_2042.md) | <br/>| 613 |
| [edam_data_2291](slots/edam_data_2291.md) | <br/>| 7883 |
| [edam_data_2298](slots/edam_data_2298.md) | <br/>| 1621 |
| [edam_operation_3799](slots/edam_operation_3799.md) | <br/>| 117 |
| [http___aopkb.org_aop_ontology#AopContext](slots/http___aopkb.org_aop_ontology#AopContext.md) | <br/>| 158 |
| [http___aopkb.org_aop_ontology#CellTypeContext](slots/http___aopkb.org_aop_ontology#CellTypeContext.md) | <br/>| 407 |
| [http___aopkb.org_aop_ontology#has_adverse_outcome](slots/http___aopkb.org_aop_ontology#has_adverse_outcome.md) | <br/>| 532 |
| [http___aopkb.org_aop_ontology#has_chemical_entity](slots/http___aopkb.org_aop_ontology#has_chemical_entity.md) | <br/>| 403 |
| [http___aopkb.org_aop_ontology#has_downstream_key_event](slots/http___aopkb.org_aop_ontology#has_downstream_key_event.md) | <br/>| 2060 |
| [http___aopkb.org_aop_ontology#has_evidence](slots/http___aopkb.org_aop_ontology#has_evidence.md) | <br/>| 143 |
| [http___aopkb.org_aop_ontology#has_key_event](slots/http___aopkb.org_aop_ontology#has_key_event.md) | <br/>| 3103 |
| [http___aopkb.org_aop_ontology#has_key_event_relationship](slots/http___aopkb.org_aop_ontology#has_key_event_relationship.md) | <br/>| 2778 |
| [http___aopkb.org_aop_ontology#has_molecular_initiating_event](slots/http___aopkb.org_aop_ontology#has_molecular_initiating_event.md) | <br/>| 457 |
| [http___aopkb.org_aop_ontology#has_upstream_key_event](slots/http___aopkb.org_aop_ontology#has_upstream_key_event.md) | <br/>| 2060 |
| [http___aopkb.org_aop_ontology#LifeStageContext](slots/http___aopkb.org_aop_ontology#LifeStageContext.md) | <br/>| 740 |
| [http___aopkb.org_aop_ontology#OrganContext](slots/http___aopkb.org_aop_ontology#OrganContext.md) | <br/>| 288 |
| [http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25217](slots/http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25217.md) | <br/>| 140 |
| [http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25664](slots/http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25664.md) | <br/>| 1469 |
| [http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25688](slots/http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25688.md) | <br/>| 138 |
| [http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25725](slots/http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25725.md) | <br/>| 104 |
| [http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C48192](slots/http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C48192.md) | <br/>| 148 |
| [http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571](slots/http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571.md) | <br/>| 603 |
| [http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C71478](slots/http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C71478.md) | <br/>| 515 |
| [http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C80263](slots/http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C80263.md) | <br/>| 623 |
| [http___purl.bioontology.org_ontology_NCBITAXON_131567](slots/http___purl.bioontology.org_ontology_NCBITAXON_131567.md) | <br/>| 1199 |
| [http___semanticscience.org_resource_CHEMINF_000059](slots/http___semanticscience.org_resource_CHEMINF_000059.md) | <br/>| 375 |
| [http___semanticscience.org_resource_CHEMINF_000140](slots/http___semanticscience.org_resource_CHEMINF_000140.md) | <br/>| 403 |
| [http___semanticscience.org_resource_CHEMINF_000405](slots/http___semanticscience.org_resource_CHEMINF_000405.md) | <br/>| 406 |
| [http___semanticscience.org_resource_CHEMINF_000406](slots/http___semanticscience.org_resource_CHEMINF_000406.md) | <br/>| 210 |
| [http___semanticscience.org_resource_CHEMINF_000407](slots/http___semanticscience.org_resource_CHEMINF_000407.md) | <br/>| 799 |
| [http___semanticscience.org_resource_CHEMINF_000408](slots/http___semanticscience.org_resource_CHEMINF_000408.md) | <br/>| 408 |
| [http___semanticscience.org_resource_CHEMINF_000409](slots/http___semanticscience.org_resource_CHEMINF_000409.md) | <br/>| 302 |
| [http___semanticscience.org_resource_CHEMINF_000412](slots/http___semanticscience.org_resource_CHEMINF_000412.md) | <br/>| 333 |
| [http___semanticscience.org_resource_CHEMINF_000446](slots/http___semanticscience.org_resource_CHEMINF_000446.md) | <br/>| 391 |
| [http___semanticscience.org_resource_CHEMINF_000564](slots/http___semanticscience.org_resource_CHEMINF_000564.md) | <br/>| 34 |
| [http___semanticscience.org_resource_CHEMINF_000567](slots/http___semanticscience.org_resource_CHEMINF_000567.md) | <br/>| 402 |
| [http___semanticscience.org_resource_CHEMINF_000568](slots/http___semanticscience.org_resource_CHEMINF_000568.md) | <br/>| 391 |
| [obo_GO_0008150](slots/obo_GO_0008150.md) | <br/>| 848 |
| [obo_MMO_0000000](slots/obo_MMO_0000000.md) | <br/>| 513 |
| [obo_PATO_0000001](slots/obo_PATO_0000001.md) | <br/>| 883 |
| [obo_PATO_0000047](slots/obo_PATO_0000047.md) | <br/>| 716 |
| [obo_PATO_0001241](slots/obo_PATO_0001241.md) | <br/>| 705 |









## IRI prefixes

* dc: http://purl.org/dc/elements/1.1/
* dct: http://purl.org/dc/terms/
* edam: http://edamontology.org/
* foaf: http://xmlns.com/foaf/0.1/
* linkml: https://w3id.org/linkml/
* obo: http://purl.obolibrary.org/obo/
* okn: https://purl.org/okn/
* okns: https://purl.org/okn/schema/
* owl: http://www.w3.org/2002/07/owl#
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* skos: http://www.w3.org/2004/02/skos/core#
* void: http://rdfs.org/ns/void#
