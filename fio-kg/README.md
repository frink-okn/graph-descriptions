# Facilities and Industries Ontology

The facilities and industries ontology developed as part of the AIKnowsPFAS and SAWGraph projects.



## Schema Diagram

```mermaid
erDiagram
B0 {

}
B1 {
    string usfrs_hasECRMId  
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri usfrs_rblc_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_eps_Industry  
    uri usfrs_caaIndustry  
    string usfrs_hasEGGRTId  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_cedri_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMEEFISId  
    string usfrs_hasCAMDBSId  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    uri geo_hasGeometry  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    string usfrs_hasEISId  
    string usfrs_hasOSHAOISId  
    uri usfrs_rmp_Industry  
    uri usfrs_eis_Industry  
    uri kwgo_spatialRelation  
    uri usfrs_ncdb_Industry  
    uri fio_ofAgency  
    string usfrs_hasNJNJEMSId  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    uri usfrs_ecrm_Industry  
    uri usfrs_aces_Industry  
    string usfrs_hasFRSId  
    uri usfrs_npdes_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    string usfrs_hasAIRId  
    uri usfrs_epcraIndustry  
    uri kwgo_sfWithin  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_environmentalInterestType  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_tris_Industry  
    uri usfrs_mn_tempo_Industry  
    uri usfrs_fifraIndustry  
}
FioAgency {
    uri rdfs_label  
    string rdfs_label  
}
FioCompany {
    uri rdfs_label  
    string rdfs_label  
}
FioFacility {
    string usfrs_hasECRMId  
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri usfrs_rblc_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_eps_Industry  
    uri usfrs_caaIndustry  
    string usfrs_hasEGGRTId  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_cedri_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMEEFISId  
    string usfrs_hasCAMDBSId  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    uri geo_hasGeometry  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    string usfrs_hasEISId  
    string usfrs_hasOSHAOISId  
    uri usfrs_rmp_Industry  
    uri usfrs_eis_Industry  
    uri kwgo_spatialRelation  
    uri usfrs_ncdb_Industry  
    uri fio_ofAgency  
    string usfrs_hasNJNJEMSId  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    uri usfrs_ecrm_Industry  
    uri usfrs_aces_Industry  
    string usfrs_hasFRSId  
    uri usfrs_npdes_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    string usfrs_hasAIRId  
    uri usfrs_epcraIndustry  
    uri kwgo_sfWithin  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_environmentalInterestType  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_tris_Industry  
    uri usfrs_mn_tempo_Industry  
    uri usfrs_fifraIndustry  
}
FioIndustry {
    uri rdfs_label  
    string rdfs_label  
    uri fio_subcodeOf  
    uri owl_sameAs  
}
GeoFeature {

}
GeoGeometry {

}
GeoSpatialObject {

}
KwgoAdministrativeRegion {

}
KwgoCell {

}
KwgoClimateDivision {

}
KwgoFederalJudicalDistrict {

}
KwgoForecastRegion {

}
KwgoNationalWeatherZone {

}
KwgoNielsenMarketZone {

}
KwgoRegion {

}
KwgoRoadSegment {

}
KwgoS2Cell {

}
KwgoStatisticalArea {

}
KwgoZipCodeArea {

}
NaicsNAICS-Industry {
    uri rdfs_label  
    string rdfs_label  
    uri fio_subcodeOf  
    uri owl_sameAs  
}
NaicsNAICS-IndustryCode {
    uri rdfs_label  
    string rdfs_label  
    uri fio_subcodeOf  
    uri owl_sameAs  
}
NaicsNAICS-IndustryGroup {
    uri rdfs_label  
    string rdfs_label  
    uri fio_subcodeOf  
    uri owl_sameAs  
}
NaicsNAICS-IndustrySector {
    uri rdfs_label  
    string rdfs_label  
    uri owl_sameAs  
    uri fio_subcodeOf  
}
NaicsNAICS-IndustrySubsector {
    uri rdfs_label  
    string rdfs_label  
    uri fio_subcodeOf  
    uri owl_sameAs  
}
OwlAllDifferent {
    uri owl_sameAs  
}
OwlAllDisjointClasses {
    uri owl_sameAs  
}
OwlAllDisjointProperties {
    uri owl_sameAs  
}
OwlAnnotation {
    uri owl_sameAs  
}
OwlAnnotationProperty {

}
OwlAsymmetricProperty {

}
OwlAxiom {
    uri owl_sameAs  
}
OwlClass {

}
OwlDataRange {

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
    uri rdfs_label  
    string rdfs_label  
    uri fio_subcodeOf  
    uri owl_sameAs  
}
OwlNegativePropertyAssertion {
    uri owl_sameAs  
}
OwlNothing {
    uri rdfs_label  
    string rdfs_label  
    uri fio_subcodeOf  
    uri owl_sameAs  
}
OwlObjectProperty {

}
OwlOntology {
    uri owl_sameAs  
}
OwlOntologyProperty {

}
OwlReflexiveProperty {

}
OwlRestriction {
    uri owl_someValuesFrom  
    uri owl_onProperty  
}
OwlSymmetricProperty {

}
OwlThing {
    uri rdfs_label  
    string rdfs_label  
    uri fio_subcodeOf  
    uri owl_sameAs  
}
OwlTransitiveProperty {

}
OwlRational {

}
OwlReal {

}
ProvOrganization {
    uri rdfs_label  
    string rdfs_label  
}
RdfAlt {

}
RdfBag {

}
RdfList {
    uri owl_sameAs  
}
RdfPlainLiteral {

}
RdfProperty {

}
RdfSeq {

}
RdfStatement {

}
RdfXMLLiteral {

}
RdfsClass {

}
RdfsContainer {

}
RdfsContainerMembershipProperty {

}
RdfsDatatype {

}
RdfsLiteral {

}
RdfsResource {
    uri owl_sameAs  
}
UsfrsBarge-Facility {
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_caaIndustry  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    uri geo_hasGeometry  
    uri kwgo_spatialRelation  
    string usfrs_hasRCRAINFOId  
    string usfrs_hasFRSId  
    string usfrs_hasAIRId  
    uri usfrs_epcraIndustry  
    uri kwgo_sfWithin  
    string usfrs_environmentalInterestType  
    uri usfrs_tris_Industry  
    string usfrs_hasECRMId  
    uri usfrs_cwaIndustry  
    uri usfrs_rblc_Industry  
    uri usfrs_eps_Industry  
    string usfrs_hasEGGRTId  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_me_efis_Industry  
    uri usfrs_cedri_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMEEFISId  
    string usfrs_hasCAMDBSId  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    string usfrs_hasEISId  
    string usfrs_hasOSHAOISId  
    uri usfrs_rmp_Industry  
    uri usfrs_eis_Industry  
    uri usfrs_ncdb_Industry  
    uri fio_ofAgency  
    string usfrs_hasNJNJEMSId  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_stateIndustry  
    uri usfrs_ecrm_Industry  
    uri usfrs_aces_Industry  
    uri usfrs_npdes_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_mn_tempo_Industry  
    uri usfrs_fifraIndustry  
}
UsfrsBrownfieldsSite-Facility {
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_caaIndustry  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMEEFISId  
    string usfrs_hasCAMDBSId  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    uri geo_hasGeometry  
    string usfrs_hasEISId  
    string usfrs_hasOSHAOISId  
    uri kwgo_spatialRelation  
    uri usfrs_ncdb_Industry  
    uri usfrs_eis_Industry  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    string usfrs_hasFRSId  
    uri usfrs_npdes_Industry  
    string usfrs_hasAIRId  
    uri usfrs_epcraIndustry  
    uri kwgo_sfWithin  
    string usfrs_environmentalInterestType  
    uri usfrs_tris_Industry  
    uri usfrs_fifraIndustry  
    string usfrs_hasECRMId  
    uri usfrs_rblc_Industry  
    uri usfrs_eps_Industry  
    string usfrs_hasEGGRTId  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_cedri_Industry  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    uri usfrs_rmp_Industry  
    uri fio_ofAgency  
    string usfrs_hasNJNJEMSId  
    uri usfrs_ssts_Industry  
    uri usfrs_ecrm_Industry  
    uri usfrs_aces_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_mn_tempo_Industry  
}
UsfrsContaminatedSite-Facility {
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_caaIndustry  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMEEFISId  
    uri usfrs_secondaryIndustry  
    string usfrs_hasOSHAOISId  
    uri kwgo_spatialRelation  
    uri usfrs_ncdb_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    string usfrs_hasFRSId  
    uri usfrs_npdes_Industry  
    string usfrs_hasAIRId  
    uri kwgo_sfWithin  
    string usfrs_environmentalInterestType  
    uri geo_hasGeometry  
    uri usfrs_fifraIndustry  
    string usfrs_hasECRMId  
    uri usfrs_rblc_Industry  
    uri usfrs_eps_Industry  
    string usfrs_hasEGGRTId  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_cedri_Industry  
    string usfrs_hasCAMDBSId  
    string usfrs_hasTRISId  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    string usfrs_hasEISId  
    uri usfrs_rmp_Industry  
    uri usfrs_eis_Industry  
    uri fio_ofAgency  
    string usfrs_hasNJNJEMSId  
    uri usfrs_camdbs_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_ecrm_Industry  
    uri usfrs_aces_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    uri usfrs_epcraIndustry  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_tris_Industry  
    uri usfrs_mn_tempo_Industry  
}
UsfrsContaminationAddressed-Facility {
    string usfrs_hasFRSId  
    uri rdfs_label  
    string rdfs_label  
    uri kwgo_spatialRelation  
    uri kwgo_sfWithin  
    uri geo_hasGeometry  
    string usfrs_hasECRMId  
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri usfrs_rblc_Industry  
    uri usfrs_eps_Industry  
    uri usfrs_caaIndustry  
    string usfrs_hasEGGRTId  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_cedri_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMEEFISId  
    string usfrs_hasCAMDBSId  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    string usfrs_hasEISId  
    string usfrs_hasOSHAOISId  
    uri usfrs_rmp_Industry  
    uri usfrs_eis_Industry  
    uri usfrs_ncdb_Industry  
    uri fio_ofAgency  
    string usfrs_hasNJNJEMSId  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    uri usfrs_ecrm_Industry  
    uri usfrs_aces_Industry  
    uri usfrs_npdes_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    string usfrs_hasAIRId  
    uri usfrs_epcraIndustry  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_environmentalInterestType  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_tris_Industry  
    uri usfrs_mn_tempo_Industry  
    uri usfrs_fifraIndustry  
}
UsfrsEPA-PFAS-Facility {
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri usfrs_rblc_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_eps_Industry  
    uri usfrs_caaIndustry  
    string usfrs_hasEGGRTId  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_cedri_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMEEFISId  
    string usfrs_hasCAMDBSId  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    uri geo_hasGeometry  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    string usfrs_hasEISId  
    string usfrs_hasOSHAOISId  
    uri usfrs_rmp_Industry  
    uri kwgo_spatialRelation  
    uri usfrs_eis_Industry  
    uri usfrs_ncdb_Industry  
    uri fio_ofAgency  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    uri usfrs_aces_Industry  
    string usfrs_hasFRSId  
    uri usfrs_npdes_Industry  
    string usfrs_hasCEDRIId  
    string usfrs_hasAIRId  
    uri usfrs_epcraIndustry  
    uri kwgo_sfWithin  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_environmentalInterestType  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_tris_Industry  
    uri usfrs_mn_tempo_Industry  
    uri usfrs_fifraIndustry  
    string usfrs_hasECRMId  
    uri usfrs_nj_njems_Industry  
    string usfrs_hasNJNJEMSId  
    uri usfrs_ecrm_Industry  
    uri usfrs_nv_fp_Industry  
}
UsfrsFRS-Facility {
    string usfrs_hasECRMId  
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri usfrs_rblc_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_eps_Industry  
    uri usfrs_caaIndustry  
    string usfrs_hasEGGRTId  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_cedri_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMEEFISId  
    string usfrs_hasCAMDBSId  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    uri geo_hasGeometry  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    string usfrs_hasEISId  
    string usfrs_hasOSHAOISId  
    uri usfrs_rmp_Industry  
    uri usfrs_eis_Industry  
    uri kwgo_spatialRelation  
    uri usfrs_ncdb_Industry  
    uri fio_ofAgency  
    string usfrs_hasNJNJEMSId  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    uri usfrs_ecrm_Industry  
    uri usfrs_aces_Industry  
    string usfrs_hasFRSId  
    uri usfrs_npdes_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    string usfrs_hasAIRId  
    uri usfrs_epcraIndustry  
    uri kwgo_sfWithin  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_environmentalInterestType  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_tris_Industry  
    uri usfrs_mn_tempo_Industry  
    uri usfrs_fifraIndustry  
}
UsfrsFederal-Facility {
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_eps_Industry  
    uri usfrs_caaIndustry  
    uri usfrs_oh_core_Industry  
    string usfrs_hasEGGRTId  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_rcrainfo_Industry  
    string usfrs_hasMEEFISId  
    string usfrs_hasCAMDBSId  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    uri geo_hasGeometry  
    uri fio_ofAgency  
    string usfrs_hasEISId  
    string usfrs_hasOSHAOISId  
    uri usfrs_rmp_Industry  
    uri usfrs_eis_Industry  
    uri kwgo_spatialRelation  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    uri usfrs_aces_Industry  
    string usfrs_hasFRSId  
    uri usfrs_npdes_Industry  
    string usfrs_hasAIRId  
    uri usfrs_epcraIndustry  
    uri kwgo_sfWithin  
    string usfrs_hasICISId  
    string usfrs_environmentalInterestType  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_tris_Industry  
    uri usfrs_fifraIndustry  
    string usfrs_hasECRMId  
    uri usfrs_rblc_Industry  
    uri usfrs_nj_njems_Industry  
    uri usfrs_cedri_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    uri usfrs_ncdb_Industry  
    string usfrs_hasNJNJEMSId  
    uri usfrs_ecrm_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    string usfrs_hasEIA860Id  
    uri usfrs_mn_tempo_Industry  
}
UsfrsMonitoringStation-Facility {
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_caaIndustry  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_rcrainfo_Industry  
    string usfrs_hasMEEFISId  
    uri usfrs_secondaryIndustry  
    uri fio_ofAgency  
    string usfrs_hasEISId  
    uri usfrs_rmp_Industry  
    uri kwgo_spatialRelation  
    uri usfrs_eis_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    string usfrs_hasFRSId  
    uri usfrs_npdes_Industry  
    string usfrs_hasAIRId  
    uri kwgo_sfWithin  
    string usfrs_hasICISId  
    string usfrs_environmentalInterestType  
    string usfrs_hasRMPId  
    uri geo_hasGeometry  
    string usfrs_hasECRMId  
    uri usfrs_rblc_Industry  
    uri usfrs_eps_Industry  
    string usfrs_hasEGGRTId  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_cedri_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasCAMDBSId  
    string usfrs_hasTRISId  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    string usfrs_hasOSHAOISId  
    uri usfrs_ncdb_Industry  
    string usfrs_hasNJNJEMSId  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_ecrm_Industry  
    uri usfrs_aces_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    uri usfrs_epcraIndustry  
    string usfrs_hasEIA860Id  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    uri usfrs_tris_Industry  
    uri usfrs_mn_tempo_Industry  
    uri usfrs_fifraIndustry  
}
UsfrsPortable-Facility {
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_caaIndustry  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    string usfrs_hasMEEFISId  
    string usfrs_hasEISId  
    uri kwgo_spatialRelation  
    uri usfrs_eis_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasFRSId  
    uri usfrs_npdes_Industry  
    string usfrs_hasAIRId  
    uri kwgo_sfWithin  
    string usfrs_environmentalInterestType  
    uri geo_hasGeometry  
    string usfrs_hasECRMId  
    uri usfrs_icis_Industry  
    uri usfrs_rblc_Industry  
    uri usfrs_eps_Industry  
    string usfrs_hasEGGRTId  
    uri usfrs_oh_core_Industry  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_cedri_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasCAMDBSId  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    string usfrs_hasOSHAOISId  
    uri usfrs_rmp_Industry  
    uri usfrs_ncdb_Industry  
    uri fio_ofAgency  
    string usfrs_hasNJNJEMSId  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    string usfrs_hasRCRAINFOId  
    uri usfrs_ecrm_Industry  
    uri usfrs_aces_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    uri usfrs_epcraIndustry  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_tris_Industry  
    uri usfrs_mn_tempo_Industry  
    uri usfrs_fifraIndustry  
}
UsfrsPotentiallyContaminatedSite-Facility {
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_caaIndustry  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    uri geo_hasGeometry  
    string usfrs_hasEISId  
    string usfrs_hasOSHAOISId  
    uri usfrs_rmp_Industry  
    uri usfrs_eis_Industry  
    uri kwgo_spatialRelation  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    string usfrs_hasFRSId  
    uri usfrs_npdes_Industry  
    string usfrs_hasAIRId  
    uri usfrs_epcraIndustry  
    uri kwgo_sfWithin  
    string usfrs_environmentalInterestType  
    string usfrs_hasRMPId  
    uri usfrs_tris_Industry  
    uri usfrs_fifraIndustry  
    string usfrs_hasECRMId  
    uri usfrs_rblc_Industry  
    uri usfrs_eps_Industry  
    string usfrs_hasEGGRTId  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_cedri_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMEEFISId  
    string usfrs_hasCAMDBSId  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    uri usfrs_ncdb_Industry  
    uri fio_ofAgency  
    string usfrs_hasNJNJEMSId  
    uri usfrs_camdbs_Industry  
    uri usfrs_ecrm_Industry  
    uri usfrs_aces_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    uri usfrs_mn_tempo_Industry  
}
UsfrsStationary-Facility {
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri usfrs_rblc_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_eps_Industry  
    uri usfrs_caaIndustry  
    string usfrs_hasEGGRTId  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_cedri_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMEEFISId  
    string usfrs_hasCAMDBSId  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    uri geo_hasGeometry  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    string usfrs_hasEISId  
    string usfrs_hasOSHAOISId  
    uri usfrs_rmp_Industry  
    uri usfrs_eis_Industry  
    uri kwgo_spatialRelation  
    uri usfrs_ncdb_Industry  
    uri fio_ofAgency  
    string usfrs_hasNJNJEMSId  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    uri usfrs_aces_Industry  
    string usfrs_hasFRSId  
    uri usfrs_npdes_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    string usfrs_hasAIRId  
    uri usfrs_epcraIndustry  
    uri kwgo_sfWithin  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_environmentalInterestType  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_tris_Industry  
    uri usfrs_mn_tempo_Industry  
    uri usfrs_fifraIndustry  
    string usfrs_hasECRMId  
    uri usfrs_ecrm_Industry  
}
UsfrsWaterSystem-Facility {
    uri usfrs_cwaIndustry  
    string usfrs_hasFRSId  
    uri usfrs_npdes_Industry  
    uri rdfs_label  
    string rdfs_label  
    uri kwgo_spatialRelation  
    uri kwgo_sfWithin  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri geo_hasGeometry  
    string usfrs_hasECRMId  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri usfrs_rblc_Industry  
    uri usfrs_eps_Industry  
    uri usfrs_caaIndustry  
    string usfrs_hasEGGRTId  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_cedri_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMEEFISId  
    string usfrs_hasCAMDBSId  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    string usfrs_hasEISId  
    string usfrs_hasOSHAOISId  
    uri usfrs_rmp_Industry  
    uri usfrs_eis_Industry  
    uri usfrs_ncdb_Industry  
    uri fio_ofAgency  
    string usfrs_hasNJNJEMSId  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    uri usfrs_ecrm_Industry  
    uri usfrs_aces_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    string usfrs_hasAIRId  
    uri usfrs_epcraIndustry  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_environmentalInterestType  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_tris_Industry  
    uri usfrs_mn_tempo_Industry  
    uri usfrs_fifraIndustry  
}
UsfrsWaterfrontFacility-Facility {
    string usfrs_hasFRSId  
    string usfrs_hasEISId  
    uri rdfs_label  
    string rdfs_label  
    uri usfrs_eis_Industry  
    uri kwgo_spatialRelation  
    uri kwgo_sfWithin  
    uri usfrs_caaIndustry  
    string usfrs_environmentalInterestType  
    uri fio_ofIndustry  
    uri usfrs_primaryIndustry  
    uri geo_hasGeometry  
    string usfrs_hasECRMId  
    uri usfrs_cwaIndustry  
    uri usfrs_air_Industry  
    uri usfrs_icis_Industry  
    uri usfrs_rblc_Industry  
    uri usfrs_eps_Industry  
    string usfrs_hasEGGRTId  
    uri usfrs_oh_core_Industry  
    string usfrs_hasAIRSAFSId  
    uri usfrs_nj_njems_Industry  
    uri usfrs_e_ggrt_Industry  
    string usfrs_hasNPDESId  
    uri usfrs_me_efis_Industry  
    uri usfrs_airs_afs_Industry  
    uri usfrs_cedri_Industry  
    uri usfrs_rcrainfo_Industry  
    uri usfrs_tscaIndustry  
    string usfrs_hasMEEFISId  
    string usfrs_hasCAMDBSId  
    uri usfrs_secondaryIndustry  
    string usfrs_hasTRISId  
    string usfrs_hasMNTEMPOId  
    uri usfrs_eia_860_Industry  
    string usfrs_hasOSHAOISId  
    uri usfrs_rmp_Industry  
    uri usfrs_ncdb_Industry  
    uri fio_ofAgency  
    string usfrs_hasNJNJEMSId  
    uri usfrs_camdbs_Industry  
    uri usfrs_osha_ois_Industry  
    uri usfrs_ssts_Industry  
    uri usfrs_stateIndustry  
    string usfrs_hasRCRAINFOId  
    uri usfrs_ecrm_Industry  
    uri usfrs_aces_Industry  
    uri usfrs_npdes_Industry  
    string usfrs_hasCEDRIId  
    uri usfrs_nv_fp_Industry  
    string usfrs_hasAIRId  
    uri usfrs_epcraIndustry  
    string usfrs_hasICISId  
    string usfrs_hasEIA860Id  
    string usfrs_hasACESId  
    string usfrs_hasEPSId  
    string usfrs_hasRMPId  
    uri usfrs_tris_Industry  
    uri usfrs_mn_tempo_Industry  
    uri usfrs_fifraIndustry  
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
XsdDateTimeStamp {

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
XsdString {

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
XsdGYear {

}
GeoWktLiteral {

}

B1 ||--|o FioIndustry : "usfrs_cwaIndustry"
B1 ||--|o OwlThing : "usfrs_cwaIndustry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
B1 ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
B1 ||--|o FioIndustry : "usfrs_air-Industry"
B1 ||--|o OwlThing : "usfrs_air-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_air-Industry"
B1 ||--|o FioIndustry : "usfrs_icis-Industry"
B1 ||--|o OwlThing : "usfrs_icis-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
B1 ||--|o FioIndustry : "usfrs_eps-Industry"
B1 ||--|o OwlThing : "usfrs_eps-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
B1 ||--|o FioIndustry : "usfrs_caaIndustry"
B1 ||--|o OwlThing : "usfrs_caaIndustry"
B1 ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
B1 ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
B1 ||--|o FioIndustry : "fio_ofIndustry"
B1 ||--|o OwlThing : "fio_ofIndustry"
B1 ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
B1 ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
B1 ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
B1 ||--|o OwlNamedIndividual : "fio_ofIndustry"
B1 ||--|o FioIndustry : "usfrs_primaryIndustry"
B1 ||--|o OwlThing : "usfrs_primaryIndustry"
B1 ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
B1 ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
B1 ||--|o FioIndustry : "usfrs_nj-njems-Industry"
B1 ||--|o OwlThing : "usfrs_nj-njems-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
B1 ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
B1 ||--|o OwlThing : "usfrs_e-ggrt-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
B1 ||--|o FioIndustry : "usfrs_me-efis-Industry"
B1 ||--|o OwlThing : "usfrs_me-efis-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
B1 ||--|o FioIndustry : "usfrs_airs-afs-Industry"
B1 ||--|o OwlThing : "usfrs_airs-afs-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
B1 ||--|o FioIndustry : "usfrs_cedri-Industry"
B1 ||--|o OwlThing : "usfrs_cedri-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
B1 ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
B1 ||--|o OwlThing : "usfrs_rcrainfo-Industry"
B1 ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
B1 ||--|o FioIndustry : "usfrs_secondaryIndustry"
B1 ||--|o OwlThing : "usfrs_secondaryIndustry"
B1 ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
B1 ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
B1 ||--|o FioIndustry : "usfrs_eia-860-Industry"
B1 ||--|o OwlThing : "usfrs_eia-860-Industry"
B1 ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
B1 ||--|o FioIndustry : "usfrs_rmp-Industry"
B1 ||--|o OwlThing : "usfrs_rmp-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
B1 ||--|o FioIndustry : "usfrs_eis-Industry"
B1 ||--|o OwlThing : "usfrs_eis-Industry"
B1 ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
B1 ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
B1 ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
B1 ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
B1 ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
B1 ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
B1 ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
B1 ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
B1 ||--|o FioFacility : "kwgo_spatialRelation"
B1 ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
B1 ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
B1 ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
B1 ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
B1 ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
B1 ||--|o B1 : "kwgo_spatialRelation"
B1 ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
B1 ||--|o ProvOrganization : "fio_ofAgency"
B1 ||--|o FioAgency : "fio_ofAgency"
B1 ||--|o FioIndustry : "usfrs_camdbs-Industry"
B1 ||--|o OwlThing : "usfrs_camdbs-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
B1 ||--|o FioIndustry : "usfrs_osha-ois-Industry"
B1 ||--|o OwlThing : "usfrs_osha-ois-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
B1 ||--|o FioIndustry : "usfrs_stateIndustry"
B1 ||--|o OwlThing : "usfrs_stateIndustry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
B1 ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
B1 ||--|o FioIndustry : "usfrs_aces-Industry"
B1 ||--|o OwlThing : "usfrs_aces-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
B1 ||--|o FioIndustry : "usfrs_npdes-Industry"
B1 ||--|o OwlThing : "usfrs_npdes-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
B1 ||--|o FioIndustry : "usfrs_epcraIndustry"
B1 ||--|o OwlThing : "usfrs_epcraIndustry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
B1 ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
B1 ||--|o FioIndustry : "usfrs_tris-Industry"
B1 ||--|o OwlThing : "usfrs_tris-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
B1 ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
B1 ||--|o OwlThing : "usfrs_mn-tempo-Industry"
B1 ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
B1 ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
B1 ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
FioFacility ||--|o FioIndustry : "usfrs_cwaIndustry"
FioFacility ||--|o OwlThing : "usfrs_cwaIndustry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
FioFacility ||--|o FioIndustry : "usfrs_air-Industry"
FioFacility ||--|o OwlThing : "usfrs_air-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
FioFacility ||--|o FioIndustry : "usfrs_icis-Industry"
FioFacility ||--|o OwlThing : "usfrs_icis-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
FioFacility ||--|o FioIndustry : "usfrs_eps-Industry"
FioFacility ||--|o OwlThing : "usfrs_eps-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
FioFacility ||--|o FioIndustry : "usfrs_caaIndustry"
FioFacility ||--|o OwlThing : "usfrs_caaIndustry"
FioFacility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
FioFacility ||--|o FioIndustry : "fio_ofIndustry"
FioFacility ||--|o OwlThing : "fio_ofIndustry"
FioFacility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
FioFacility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
FioFacility ||--|o OwlNamedIndividual : "fio_ofIndustry"
FioFacility ||--|o FioIndustry : "usfrs_primaryIndustry"
FioFacility ||--|o OwlThing : "usfrs_primaryIndustry"
FioFacility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
FioFacility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
FioFacility ||--|o OwlThing : "usfrs_nj-njems-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
FioFacility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
FioFacility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
FioFacility ||--|o FioIndustry : "usfrs_me-efis-Industry"
FioFacility ||--|o OwlThing : "usfrs_me-efis-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
FioFacility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
FioFacility ||--|o OwlThing : "usfrs_airs-afs-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
FioFacility ||--|o FioIndustry : "usfrs_cedri-Industry"
FioFacility ||--|o OwlThing : "usfrs_cedri-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
FioFacility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
FioFacility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
FioFacility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
FioFacility ||--|o FioIndustry : "usfrs_secondaryIndustry"
FioFacility ||--|o OwlThing : "usfrs_secondaryIndustry"
FioFacility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
FioFacility ||--|o FioIndustry : "usfrs_eia-860-Industry"
FioFacility ||--|o OwlThing : "usfrs_eia-860-Industry"
FioFacility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
FioFacility ||--|o FioIndustry : "usfrs_rmp-Industry"
FioFacility ||--|o OwlThing : "usfrs_rmp-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
FioFacility ||--|o FioIndustry : "usfrs_eis-Industry"
FioFacility ||--|o OwlThing : "usfrs_eis-Industry"
FioFacility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
FioFacility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
FioFacility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
FioFacility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
FioFacility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
FioFacility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
FioFacility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
FioFacility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
FioFacility ||--|o FioFacility : "kwgo_spatialRelation"
FioFacility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
FioFacility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
FioFacility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
FioFacility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
FioFacility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
FioFacility ||--|o B1 : "kwgo_spatialRelation"
FioFacility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
FioFacility ||--|o ProvOrganization : "fio_ofAgency"
FioFacility ||--|o FioAgency : "fio_ofAgency"
FioFacility ||--|o FioIndustry : "usfrs_camdbs-Industry"
FioFacility ||--|o OwlThing : "usfrs_camdbs-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
FioFacility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
FioFacility ||--|o OwlThing : "usfrs_osha-ois-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
FioFacility ||--|o FioIndustry : "usfrs_stateIndustry"
FioFacility ||--|o OwlThing : "usfrs_stateIndustry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
FioFacility ||--|o FioIndustry : "usfrs_aces-Industry"
FioFacility ||--|o OwlThing : "usfrs_aces-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
FioFacility ||--|o FioIndustry : "usfrs_npdes-Industry"
FioFacility ||--|o OwlThing : "usfrs_npdes-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
FioFacility ||--|o FioIndustry : "usfrs_epcraIndustry"
FioFacility ||--|o OwlThing : "usfrs_epcraIndustry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
FioFacility ||--|o FioIndustry : "usfrs_tris-Industry"
FioFacility ||--|o OwlThing : "usfrs_tris-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
FioFacility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
FioFacility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
FioFacility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
FioFacility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
FioFacility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
FioIndustry ||--|o XsdGYear : "fio_ofYear"
FioIndustry ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
FioIndustry ||--|o FioIndustry : "fio_subcodeOf"
FioIndustry ||--|o OwlThing : "fio_subcodeOf"
FioIndustry ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
FioIndustry ||--|o NaicsNAICS-Industry : "fio_subcodeOf"
FioIndustry ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
FioIndustry ||--|o OwlNamedIndividual : "fio_subcodeOf"
FioIndustry ||--|o FioIndustry : "owl_sameAs"
FioIndustry ||--|o OwlThing : "owl_sameAs"
FioIndustry ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
FioIndustry ||--|o RdfsResource : "owl_sameAs"
FioIndustry ||--|o RdfList : "owl_sameAs"
FioIndustry ||--|o NaicsNAICS-Industry : "owl_sameAs"
FioIndustry ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
FioIndustry ||--|o OwlNamedIndividual : "owl_sameAs"
NaicsNAICS-Industry ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-Industry ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
NaicsNAICS-Industry ||--|o FioIndustry : "fio_subcodeOf"
NaicsNAICS-Industry ||--|o OwlThing : "fio_subcodeOf"
NaicsNAICS-Industry ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
NaicsNAICS-Industry ||--|o NaicsNAICS-Industry : "fio_subcodeOf"
NaicsNAICS-Industry ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
NaicsNAICS-Industry ||--|o OwlNamedIndividual : "fio_subcodeOf"
NaicsNAICS-Industry ||--|o FioIndustry : "owl_sameAs"
NaicsNAICS-Industry ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-Industry ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
NaicsNAICS-Industry ||--|o RdfsResource : "owl_sameAs"
NaicsNAICS-Industry ||--|o RdfList : "owl_sameAs"
NaicsNAICS-Industry ||--|o NaicsNAICS-Industry : "owl_sameAs"
NaicsNAICS-Industry ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
NaicsNAICS-Industry ||--|o OwlNamedIndividual : "owl_sameAs"
NaicsNAICS-IndustryCode ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o FioIndustry : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o OwlThing : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-Industry : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o OwlNamedIndividual : "fio_subcodeOf"
NaicsNAICS-IndustryCode ||--|o FioIndustry : "owl_sameAs"
NaicsNAICS-IndustryCode ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
NaicsNAICS-IndustryCode ||--|o RdfsResource : "owl_sameAs"
NaicsNAICS-IndustryCode ||--|o RdfList : "owl_sameAs"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-Industry : "owl_sameAs"
NaicsNAICS-IndustryCode ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
NaicsNAICS-IndustryCode ||--|o OwlNamedIndividual : "owl_sameAs"
NaicsNAICS-IndustryGroup ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o FioIndustry : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o OwlThing : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-Industry : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o OwlNamedIndividual : "fio_subcodeOf"
NaicsNAICS-IndustryGroup ||--|o FioIndustry : "owl_sameAs"
NaicsNAICS-IndustryGroup ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
NaicsNAICS-IndustryGroup ||--|o RdfsResource : "owl_sameAs"
NaicsNAICS-IndustryGroup ||--|o RdfList : "owl_sameAs"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-Industry : "owl_sameAs"
NaicsNAICS-IndustryGroup ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
NaicsNAICS-IndustryGroup ||--|o OwlNamedIndividual : "owl_sameAs"
NaicsNAICS-IndustrySector ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-IndustrySector ||--|o FioIndustry : "owl_sameAs"
NaicsNAICS-IndustrySector ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustrySector ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
NaicsNAICS-IndustrySector ||--|o RdfsResource : "owl_sameAs"
NaicsNAICS-IndustrySector ||--|o RdfList : "owl_sameAs"
NaicsNAICS-IndustrySector ||--|o NaicsNAICS-Industry : "owl_sameAs"
NaicsNAICS-IndustrySector ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
NaicsNAICS-IndustrySector ||--|o OwlNamedIndividual : "owl_sameAs"
NaicsNAICS-IndustrySector ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
NaicsNAICS-IndustrySector ||--|o FioIndustry : "fio_subcodeOf"
NaicsNAICS-IndustrySector ||--|o OwlThing : "fio_subcodeOf"
NaicsNAICS-IndustrySector ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
NaicsNAICS-IndustrySector ||--|o NaicsNAICS-Industry : "fio_subcodeOf"
NaicsNAICS-IndustrySector ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
NaicsNAICS-IndustrySector ||--|o OwlNamedIndividual : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o XsdGYear : "fio_ofYear"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o FioIndustry : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o OwlThing : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-Industry : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o OwlNamedIndividual : "fio_subcodeOf"
NaicsNAICS-IndustrySubsector ||--|o FioIndustry : "owl_sameAs"
NaicsNAICS-IndustrySubsector ||--|o OwlThing : "owl_sameAs"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
NaicsNAICS-IndustrySubsector ||--|o RdfsResource : "owl_sameAs"
NaicsNAICS-IndustrySubsector ||--|o RdfList : "owl_sameAs"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-Industry : "owl_sameAs"
NaicsNAICS-IndustrySubsector ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
NaicsNAICS-IndustrySubsector ||--|o OwlNamedIndividual : "owl_sameAs"
OwlAllDifferent ||--|o FioIndustry : "owl_sameAs"
OwlAllDifferent ||--|o OwlThing : "owl_sameAs"
OwlAllDifferent ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
OwlAllDifferent ||--|o RdfsResource : "owl_sameAs"
OwlAllDifferent ||--|o RdfList : "owl_sameAs"
OwlAllDifferent ||--|o NaicsNAICS-Industry : "owl_sameAs"
OwlAllDifferent ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
OwlAllDifferent ||--|o OwlNamedIndividual : "owl_sameAs"
OwlAllDisjointClasses ||--|o FioIndustry : "owl_sameAs"
OwlAllDisjointClasses ||--|o OwlThing : "owl_sameAs"
OwlAllDisjointClasses ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
OwlAllDisjointClasses ||--|o RdfsResource : "owl_sameAs"
OwlAllDisjointClasses ||--|o RdfList : "owl_sameAs"
OwlAllDisjointClasses ||--|o NaicsNAICS-Industry : "owl_sameAs"
OwlAllDisjointClasses ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
OwlAllDisjointClasses ||--|o OwlNamedIndividual : "owl_sameAs"
OwlAllDisjointProperties ||--|o FioIndustry : "owl_sameAs"
OwlAllDisjointProperties ||--|o OwlThing : "owl_sameAs"
OwlAllDisjointProperties ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
OwlAllDisjointProperties ||--|o RdfsResource : "owl_sameAs"
OwlAllDisjointProperties ||--|o RdfList : "owl_sameAs"
OwlAllDisjointProperties ||--|o NaicsNAICS-Industry : "owl_sameAs"
OwlAllDisjointProperties ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
OwlAllDisjointProperties ||--|o OwlNamedIndividual : "owl_sameAs"
OwlAnnotation ||--|o FioIndustry : "owl_sameAs"
OwlAnnotation ||--|o OwlThing : "owl_sameAs"
OwlAnnotation ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
OwlAnnotation ||--|o RdfsResource : "owl_sameAs"
OwlAnnotation ||--|o RdfList : "owl_sameAs"
OwlAnnotation ||--|o NaicsNAICS-Industry : "owl_sameAs"
OwlAnnotation ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
OwlAnnotation ||--|o OwlNamedIndividual : "owl_sameAs"
OwlAxiom ||--|o FioIndustry : "owl_sameAs"
OwlAxiom ||--|o OwlThing : "owl_sameAs"
OwlAxiom ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
OwlAxiom ||--|o RdfsResource : "owl_sameAs"
OwlAxiom ||--|o RdfList : "owl_sameAs"
OwlAxiom ||--|o NaicsNAICS-Industry : "owl_sameAs"
OwlAxiom ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
OwlAxiom ||--|o OwlNamedIndividual : "owl_sameAs"
OwlNamedIndividual ||--|o XsdGYear : "fio_ofYear"
OwlNamedIndividual ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
OwlNamedIndividual ||--|o FioIndustry : "fio_subcodeOf"
OwlNamedIndividual ||--|o OwlThing : "fio_subcodeOf"
OwlNamedIndividual ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
OwlNamedIndividual ||--|o NaicsNAICS-Industry : "fio_subcodeOf"
OwlNamedIndividual ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
OwlNamedIndividual ||--|o OwlNamedIndividual : "fio_subcodeOf"
OwlNamedIndividual ||--|o FioIndustry : "owl_sameAs"
OwlNamedIndividual ||--|o OwlThing : "owl_sameAs"
OwlNamedIndividual ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
OwlNamedIndividual ||--|o RdfsResource : "owl_sameAs"
OwlNamedIndividual ||--|o RdfList : "owl_sameAs"
OwlNamedIndividual ||--|o NaicsNAICS-Industry : "owl_sameAs"
OwlNamedIndividual ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
OwlNamedIndividual ||--|o OwlNamedIndividual : "owl_sameAs"
OwlNegativePropertyAssertion ||--|o FioIndustry : "owl_sameAs"
OwlNegativePropertyAssertion ||--|o OwlThing : "owl_sameAs"
OwlNegativePropertyAssertion ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
OwlNegativePropertyAssertion ||--|o RdfsResource : "owl_sameAs"
OwlNegativePropertyAssertion ||--|o RdfList : "owl_sameAs"
OwlNegativePropertyAssertion ||--|o NaicsNAICS-Industry : "owl_sameAs"
OwlNegativePropertyAssertion ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
OwlNegativePropertyAssertion ||--|o OwlNamedIndividual : "owl_sameAs"
OwlNothing ||--|o XsdGYear : "fio_ofYear"
OwlNothing ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
OwlNothing ||--|o FioIndustry : "fio_subcodeOf"
OwlNothing ||--|o OwlThing : "fio_subcodeOf"
OwlNothing ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
OwlNothing ||--|o NaicsNAICS-Industry : "fio_subcodeOf"
OwlNothing ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
OwlNothing ||--|o OwlNamedIndividual : "fio_subcodeOf"
OwlNothing ||--|o FioIndustry : "owl_sameAs"
OwlNothing ||--|o OwlThing : "owl_sameAs"
OwlNothing ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
OwlNothing ||--|o RdfsResource : "owl_sameAs"
OwlNothing ||--|o RdfList : "owl_sameAs"
OwlNothing ||--|o NaicsNAICS-Industry : "owl_sameAs"
OwlNothing ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
OwlNothing ||--|o OwlNamedIndividual : "owl_sameAs"
OwlOntology ||--|o FioIndustry : "owl_sameAs"
OwlOntology ||--|o OwlThing : "owl_sameAs"
OwlOntology ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
OwlOntology ||--|o RdfsResource : "owl_sameAs"
OwlOntology ||--|o RdfList : "owl_sameAs"
OwlOntology ||--|o NaicsNAICS-Industry : "owl_sameAs"
OwlOntology ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
OwlOntology ||--|o OwlNamedIndividual : "owl_sameAs"
OwlRestriction ||--|o OwlClass : "owl_someValuesFrom"
OwlRestriction ||--|o RdfsClass : "owl_someValuesFrom"
OwlRestriction ||--|o OwlObjectProperty : "owl_onProperty"
OwlRestriction ||--|o RdfProperty : "owl_onProperty"
OwlThing ||--|o XsdGYear : "fio_ofYear"
OwlThing ||--|o NaicsNAICS-IndustrySubsector : "fio_subcodeOf"
OwlThing ||--|o FioIndustry : "fio_subcodeOf"
OwlThing ||--|o OwlThing : "fio_subcodeOf"
OwlThing ||--|o NaicsNAICS-IndustryGroup : "fio_subcodeOf"
OwlThing ||--|o NaicsNAICS-Industry : "fio_subcodeOf"
OwlThing ||--|o NaicsNAICS-IndustrySector : "fio_subcodeOf"
OwlThing ||--|o OwlNamedIndividual : "fio_subcodeOf"
OwlThing ||--|o FioIndustry : "owl_sameAs"
OwlThing ||--|o OwlThing : "owl_sameAs"
OwlThing ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
OwlThing ||--|o RdfsResource : "owl_sameAs"
OwlThing ||--|o RdfList : "owl_sameAs"
OwlThing ||--|o NaicsNAICS-Industry : "owl_sameAs"
OwlThing ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
OwlThing ||--|o OwlNamedIndividual : "owl_sameAs"
RdfList ||--|o FioIndustry : "owl_sameAs"
RdfList ||--|o OwlThing : "owl_sameAs"
RdfList ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
RdfList ||--|o RdfsResource : "owl_sameAs"
RdfList ||--|o RdfList : "owl_sameAs"
RdfList ||--|o NaicsNAICS-Industry : "owl_sameAs"
RdfList ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
RdfList ||--|o OwlNamedIndividual : "owl_sameAs"
RdfsResource ||--|o FioIndustry : "owl_sameAs"
RdfsResource ||--|o OwlThing : "owl_sameAs"
RdfsResource ||--|o NaicsNAICS-IndustryCode : "owl_sameAs"
RdfsResource ||--|o RdfsResource : "owl_sameAs"
RdfsResource ||--|o RdfList : "owl_sameAs"
RdfsResource ||--|o NaicsNAICS-Industry : "owl_sameAs"
RdfsResource ||--|o NaicsNAICS-IndustrySector : "owl_sameAs"
RdfsResource ||--|o OwlNamedIndividual : "owl_sameAs"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsBarge-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsBarge-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsBarge-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsBarge-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsBarge-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsBarge-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsBarge-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsBarge-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsBarge-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsBrownfieldsSite-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsBrownfieldsSite-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsBrownfieldsSite-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsBrownfieldsSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsBrownfieldsSite-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsContaminatedSite-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsContaminatedSite-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsContaminatedSite-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsContaminatedSite-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
UsfrsContaminationAddressed-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsContaminationAddressed-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsContaminationAddressed-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsContaminationAddressed-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsContaminationAddressed-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsContaminationAddressed-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsEPA-PFAS-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsEPA-PFAS-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsEPA-PFAS-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
UsfrsEPA-PFAS-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsEPA-PFAS-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsEPA-PFAS-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsFRS-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsFRS-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsFRS-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsFRS-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsFRS-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsFRS-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsFRS-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsFRS-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsFRS-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsFederal-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsFederal-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsFederal-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsFederal-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsFederal-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsFederal-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsFederal-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsFederal-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsFederal-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsMonitoringStation-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsMonitoringStation-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsMonitoringStation-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsMonitoringStation-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsMonitoringStation-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsMonitoringStation-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsPortable-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsPortable-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsPortable-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsPortable-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsPortable-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsPortable-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsPortable-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsPortable-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsPortable-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsPotentiallyContaminatedSite-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsStationary-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsStationary-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsStationary-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsStationary-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsStationary-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsStationary-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsStationary-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsStationary-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsStationary-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsWaterSystem-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsWaterSystem-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsWaterSystem-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsWaterSystem-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsWaterSystem-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsWaterSystem-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsWaterSystem-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_eis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_eis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_eis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_eis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsFederal-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsBrownfieldsSite-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsFRS-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsWaterfrontFacility-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsWaterSystem-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsContaminationAddressed-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsStationary-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o FioFacility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsMonitoringStation-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsPortable-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsBarge-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsPotentiallyContaminatedSite-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o B1 : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o UsfrsEPA-PFAS-Facility : "kwgo_spatialRelation"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_caaIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_caaIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_caaIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_caaIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_caaIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_caaIndustry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "fio_ofIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "fio_ofIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryGroup : "fio_ofIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "fio_ofIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "fio_ofIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "fio_ofIndustry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_primaryIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_primaryIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_primaryIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_primaryIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_primaryIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_primaryIndustry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_cwaIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_cwaIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cwaIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_cwaIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_cwaIndustry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_air-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_air-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_air-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_air-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_air-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_icis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_icis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_icis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_icis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_icis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_eps-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_eps-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eps-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_eps-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_eps-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_nj-njems-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_nj-njems-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_nj-njems-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_nj-njems-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_nj-njems-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_e-ggrt-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_e-ggrt-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_e-ggrt-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_e-ggrt-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_e-ggrt-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_me-efis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_me-efis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_me-efis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_me-efis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_me-efis-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_airs-afs-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_airs-afs-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_airs-afs-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_airs-afs-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_airs-afs-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_cedri-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_cedri-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_cedri-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_cedri-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_cedri-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_rcrainfo-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_rcrainfo-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_rcrainfo-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rcrainfo-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_rcrainfo-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_rcrainfo-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_secondaryIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_secondaryIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_secondaryIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_secondaryIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_secondaryIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_secondaryIndustry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_eia-860-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_eia-860-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryGroup : "usfrs_eia-860-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_eia-860-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_eia-860-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_eia-860-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_rmp-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_rmp-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_rmp-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_rmp-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_rmp-Industry"
UsfrsWaterfrontFacility-Facility ||--|o ProvOrganization : "fio_ofAgency"
UsfrsWaterfrontFacility-Facility ||--|o FioAgency : "fio_ofAgency"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_camdbs-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_camdbs-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_camdbs-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_camdbs-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_camdbs-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_osha-ois-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_osha-ois-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_osha-ois-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_osha-ois-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_osha-ois-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_stateIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_stateIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_stateIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_stateIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_stateIndustry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_aces-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_aces-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_aces-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_aces-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_aces-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_npdes-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_npdes-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_npdes-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_npdes-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_npdes-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_epcraIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_epcraIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_epcraIndustry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_epcraIndustry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_epcraIndustry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_tris-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_tris-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_tris-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_tris-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_tris-Industry"
UsfrsWaterfrontFacility-Facility ||--|o FioIndustry : "usfrs_mn-tempo-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlThing : "usfrs_mn-tempo-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-IndustryCode : "usfrs_mn-tempo-Industry"
UsfrsWaterfrontFacility-Facility ||--|o NaicsNAICS-Industry : "usfrs_mn-tempo-Industry"
UsfrsWaterfrontFacility-Facility ||--|o OwlNamedIndividual : "usfrs_mn-tempo-Industry"

```



## Classes

| Class | Description | Occurrences |
| --- | --- | --- || [B0](classes/B0.md) | No class (type) description specified<br/>| 0 | 
| [B1](classes/B1.md) | No class (type) description specified<br/>| 300936 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[FioFacility](classes/FioFacility.md) | No class (type) description specified<br/>| 300936 | 

| [FioIndustry](classes/FioIndustry.md) | No class (type) description specified<br/>| 2129 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[NaicsNAICS-Industry](classes/NaicsNAICS-Industry.md) | No class (type) description specified<br/>| 2129 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[NaicsNAICS-IndustryCode](classes/NaicsNAICS-IndustryCode.md) | No class (type) description specified<br/>| 1701 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[NaicsNAICS-IndustryGroup](classes/NaicsNAICS-IndustryGroup.md) | No class (type) description specified<br/>| 308 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[NaicsNAICS-IndustrySector](classes/NaicsNAICS-IndustrySector.md) | No class (type) description specified<br/>| 24 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[NaicsNAICS-IndustrySubsector](classes/NaicsNAICS-IndustrySubsector.md) | No class (type) description specified<br/>| 96 | 
| [GeoFeature](classes/GeoFeature.md) | No class (type) description specified<br/>| 0 | 
| [GeoGeometry](classes/GeoGeometry.md) | No class (type) description specified<br/>| 0 | 
| [GeoSpatialObject](classes/GeoSpatialObject.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[KwgoAdministrativeRegion](classes/KwgoAdministrativeRegion.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[KwgoClimateDivision](classes/KwgoClimateDivision.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[KwgoFederalJudicalDistrict](classes/KwgoFederalJudicalDistrict.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[KwgoNationalWeatherZone](classes/KwgoNationalWeatherZone.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[KwgoNielsenMarketZone](classes/KwgoNielsenMarketZone.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[KwgoRoadSegment](classes/KwgoRoadSegment.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[KwgoS2Cell](classes/KwgoS2Cell.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[KwgoStatisticalArea](classes/KwgoStatisticalArea.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[KwgoZipCodeArea](classes/KwgoZipCodeArea.md) | No class (type) description specified<br/>| 0 | 
| [GeoWktLiteral](classes/GeoWktLiteral.md) | No class (type) description specified<br/>| 0 | 
| [KwgoCell](classes/KwgoCell.md) | No class (type) description specified<br/>| 0 | 
| [KwgoForecastRegion](classes/KwgoForecastRegion.md) | No class (type) description specified<br/>| 0 | 
| [KwgoRegion](classes/KwgoRegion.md) | No class (type) description specified<br/>| 0 | 
| [OwlObjectProperty](classes/OwlObjectProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAsymmetricProperty](classes/OwlAsymmetricProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlInverseFunctionalProperty](classes/OwlInverseFunctionalProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlIrreflexiveProperty](classes/OwlIrreflexiveProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlReflexiveProperty](classes/OwlReflexiveProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlSymmetricProperty](classes/OwlSymmetricProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlTransitiveProperty](classes/OwlTransitiveProperty.md) | No class (type) description specified<br/>| 0 | 
| [OwlThing](classes/OwlThing.md) | No class (type) description specified<br/>| 2127 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlNamedIndividual](classes/OwlNamedIndividual.md) | No class (type) description specified<br/>| 2125 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlNothing](classes/OwlNothing.md) | No class (type) description specified<br/>| 0 | 
| [ProvOrganization](classes/ProvOrganization.md) | No class (type) description specified<br/>| 15 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[FioAgency](classes/FioAgency.md) | No class (type) description specified<br/>| 15 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[FioCompany](classes/FioCompany.md) | No class (type) description specified<br/>| 0 | 
| [RdfList](classes/RdfList.md) | No class (type) description specified<br/>| 1 | 
| [RdfProperty](classes/RdfProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAnnotationProperty](classes/OwlAnnotationProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlDatatypeProperty](classes/OwlDatatypeProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlDeprecatedProperty](classes/OwlDeprecatedProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlFunctionalProperty](classes/OwlFunctionalProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlOntologyProperty](classes/OwlOntologyProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfsContainerMembershipProperty](classes/RdfsContainerMembershipProperty.md) | No class (type) description specified<br/>| 0 | 
| [RdfStatement](classes/RdfStatement.md) | No class (type) description specified<br/>| 0 | 
| [RdfsClass](classes/RdfsClass.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlClass](classes/OwlClass.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlRestriction](classes/OwlRestriction.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlDeprecatedClass](classes/OwlDeprecatedClass.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfsDatatype](classes/RdfsDatatype.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlDataRange](classes/OwlDataRange.md) | No class (type) description specified<br/>| 0 | 
| [RdfsContainer](classes/RdfsContainer.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfAlt](classes/RdfAlt.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfBag](classes/RdfBag.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfSeq](classes/RdfSeq.md) | No class (type) description specified<br/>| 0 | 
| [RdfsLiteral](classes/RdfsLiteral.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlRational](classes/OwlRational.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlReal](classes/OwlReal.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfPlainLiteral](classes/RdfPlainLiteral.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfXMLLiteral](classes/RdfXMLLiteral.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdAnyURI](classes/XsdAnyURI.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdBase64Binary](classes/XsdBase64Binary.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdBoolean](classes/XsdBoolean.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdByte](classes/XsdByte.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdDateTime](classes/XsdDateTime.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdDateTimeStamp](classes/XsdDateTimeStamp.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdDecimal](classes/XsdDecimal.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdDouble](classes/XsdDouble.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdFloat](classes/XsdFloat.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdHexBinary](classes/XsdHexBinary.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdInt](classes/XsdInt.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdInteger](classes/XsdInteger.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdLanguage](classes/XsdLanguage.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdLong](classes/XsdLong.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdName](classes/XsdName.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNCName](classes/XsdNCName.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNegativeInteger](classes/XsdNegativeInteger.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNMTOKEN](classes/XsdNMTOKEN.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNonNegativeInteger](classes/XsdNonNegativeInteger.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNonPositiveInteger](classes/XsdNonPositiveInteger.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNormalizedString](classes/XsdNormalizedString.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdPositiveInteger](classes/XsdPositiveInteger.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdShort](classes/XsdShort.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdString](classes/XsdString.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdToken](classes/XsdToken.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdUnsignedByte](classes/XsdUnsignedByte.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdUnsignedInt](classes/XsdUnsignedInt.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdUnsignedLong](classes/XsdUnsignedLong.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdUnsignedShort](classes/XsdUnsignedShort.md) | No class (type) description specified<br/>| 0 | 
| [RdfsResource](classes/RdfsResource.md) | No class (type) description specified<br/>| 34 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAllDifferent](classes/OwlAllDifferent.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAllDisjointClasses](classes/OwlAllDisjointClasses.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAllDisjointProperties](classes/OwlAllDisjointProperties.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAnnotation](classes/OwlAnnotation.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAxiom](classes/OwlAxiom.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlNegativePropertyAssertion](classes/OwlNegativePropertyAssertion.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlOntology](classes/OwlOntology.md) | No class (type) description specified<br/>| 0 | 
| [UsfrsFRS-Facility](classes/UsfrsFRS-Facility.md) | No class (type) description specified<br/>| 300936 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsBarge-Facility](classes/UsfrsBarge-Facility.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsBrownfieldsSite-Facility](classes/UsfrsBrownfieldsSite-Facility.md) | No class (type) description specified<br/>| 3566 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsContaminatedSite-Facility](classes/UsfrsContaminatedSite-Facility.md) | No class (type) description specified<br/>| 94 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsContaminationAddressed-Facility](classes/UsfrsContaminationAddressed-Facility.md) | No class (type) description specified<br/>| 10 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsEPA-PFAS-Facility](classes/UsfrsEPA-PFAS-Facility.md) | No class (type) description specified<br/>| 8681 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsFederal-Facility](classes/UsfrsFederal-Facility.md) | No class (type) description specified<br/>| 1208 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsMonitoringStation-Facility](classes/UsfrsMonitoringStation-Facility.md) | No class (type) description specified<br/>| 788 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsPortable-Facility](classes/UsfrsPortable-Facility.md) | No class (type) description specified<br/>| 276 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsPotentiallyContaminatedSite-Facility](classes/UsfrsPotentiallyContaminatedSite-Facility.md) | No class (type) description specified<br/>| 854 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsStationary-Facility](classes/UsfrsStationary-Facility.md) | No class (type) description specified<br/>| 246338 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsWaterfrontFacility-Facility](classes/UsfrsWaterfrontFacility-Facility.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsWaterSystem-Facility](classes/UsfrsWaterSystem-Facility.md) | No class (type) description specified<br/>| 43116 | 
| [XsdDate](classes/XsdDate.md) | No class (type) description specified<br/>| 0 | 
| [XsdGYear](classes/XsdGYear.md) | No class (type) description specified<br/>| 0 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [dct_contributor](slots/dct_contributor.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [dct_created](slots/dct_created.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [dct_creator](slots/dct_creator.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [dct_description](slots/dct_description.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [dct_issued](slots/dct_issued.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [dct_modified](slots/dct_modified.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [dct_publisher](slots/dct_publisher.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [dct_source](slots/dct_source.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [dct_title](slots/dct_title.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [fio_hasName](slots/fio_hasName.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [fio_hasParentCompany](slots/fio_hasParentCompany.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [fio_ofAgency](slots/fio_ofAgency.md) | No slot (predicate) description specified<br/>| 44 |
| [fio_ofIndustry](slots/fio_ofIndustry.md) | No slot (predicate) description specified<br/>| 139509 |
| [fio_ofYear](slots/fio_ofYear.md) | No slot (predicate) description specified<br/>| 2125 |
| [fio_subcodeOf](slots/fio_subcodeOf.md) | No slot (predicate) description specified<br/>| 5815 |
| [geo_asWKT](slots/geo_asWKT.md) | No slot (predicate) description specified<br/>| 210390 |
| [geo_defaultGeometry](slots/geo_defaultGeometry.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [geo_hasGeometry](slots/geo_hasGeometry.md) | No slot (predicate) description specified<br/>| 210390 |
| [hsdo_domainIncludes](slots/hsdo_domainIncludes.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [hsdo_rangeIncludes](slots/hsdo_rangeIncludes.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [kwgo_sfContains](slots/kwgo_sfContains.md) | No slot (predicate) description specified<br/>| 716825 |
| [kwgo_sfEquals](slots/kwgo_sfEquals.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [kwgo_sfOverlaps](slots/kwgo_sfOverlaps.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [kwgo_sfTouches](slots/kwgo_sfTouches.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [kwgo_sfWithin](slots/kwgo_sfWithin.md) | No slot (predicate) description specified<br/>| 716825 |
| [kwgo_spatialRelation](slots/kwgo_spatialRelation.md) | No slot (predicate) description specified<br/>| 1433650 |
| [owl_allValuesFrom](slots/owl_allValuesFrom.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_annotatedProperty](slots/owl_annotatedProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_annotatedSource](slots/owl_annotatedSource.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_annotatedTarget](slots/owl_annotatedTarget.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_assertionProperty](slots/owl_assertionProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_backwardCompatibleWith](slots/owl_backwardCompatibleWith.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_bottomDataProperty](slots/owl_bottomDataProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_bottomObjectProperty](slots/owl_bottomObjectProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_cardinality](slots/owl_cardinality.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_complementOf](slots/owl_complementOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_datatypeComplementOf](slots/owl_datatypeComplementOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_deprecated](slots/owl_deprecated.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_differentFrom](slots/owl_differentFrom.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_disjointUnionOf](slots/owl_disjointUnionOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_disjointWith](slots/owl_disjointWith.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_distinctMembers](slots/owl_distinctMembers.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_equivalentClass](slots/owl_equivalentClass.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_equivalentProperty](slots/owl_equivalentProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_hasKey](slots/owl_hasKey.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_hasSelf](slots/owl_hasSelf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_hasValue](slots/owl_hasValue.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_imports](slots/owl_imports.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_incompatibleWith](slots/owl_incompatibleWith.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_intersectionOf](slots/owl_intersectionOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_inverseOf](slots/owl_inverseOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_maxCardinality](slots/owl_maxCardinality.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_maxQualifiedCardinality](slots/owl_maxQualifiedCardinality.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_members](slots/owl_members.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_minCardinality](slots/owl_minCardinality.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_minQualifiedCardinality](slots/owl_minQualifiedCardinality.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_onClass](slots/owl_onClass.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_onDataRange](slots/owl_onDataRange.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_onDatatype](slots/owl_onDatatype.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_oneOf](slots/owl_oneOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_onProperties](slots/owl_onProperties.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_onProperty](slots/owl_onProperty.md) | No slot (predicate) description specified<br/>| 1 |
| [owl_priorVersion](slots/owl_priorVersion.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_propertyChainAxiom](slots/owl_propertyChainAxiom.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_propertyDisjointWith](slots/owl_propertyDisjointWith.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_qualifiedCardinality](slots/owl_qualifiedCardinality.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_sameAs](slots/owl_sameAs.md) | No slot (predicate) description specified<br/>| 529 |
| [owl_someValuesFrom](slots/owl_someValuesFrom.md) | No slot (predicate) description specified<br/>| 1 |
| [owl_sourceIndividual](slots/owl_sourceIndividual.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_targetIndividual](slots/owl_targetIndividual.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_targetValue](slots/owl_targetValue.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_topDataProperty](slots/owl_topDataProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_topObjectProperty](slots/owl_topObjectProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_unionOf](slots/owl_unionOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_versionInfo](slots/owl_versionInfo.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_versionIRI](slots/owl_versionIRI.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_withRestrictions](slots/owl_withRestrictions.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [psys_transitiveOver](slots/psys_transitiveOver.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf__1](slots/rdf__1.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_first](slots/rdf_first.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_langRange](slots/rdf_langRange.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_object](slots/rdf_object.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_predicate](slots/rdf_predicate.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_rest](slots/rdf_rest.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_subject](slots/rdf_subject.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_type](slots/rdf_type.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_value](slots/rdf_value.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_comment](slots/rdfs_comment.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_domain](slots/rdfs_domain.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_isDefinedBy](slots/rdfs_isDefinedBy.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_label](slots/rdfs_label.md) | No slot (predicate) description specified<br/>| 303061 |
| [rdfs_member](slots/rdfs_member.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_range](slots/rdfs_range.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_seeAlso](slots/rdfs_seeAlso.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_subClassOf](slots/rdfs_subClassOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_subPropertyOf](slots/rdfs_subPropertyOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [skos_definition](slots/skos_definition.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [skos_description](slots/skos_description.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [skos_editorialNote](slots/skos_editorialNote.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [skos_example](slots/skos_example.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [skos_note](slots/skos_note.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [skos_prefLabel](slots/skos_prefLabel.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [usfrs_aces_Industry](slots/usfrs_aces_Industry.md) | No slot (predicate) description specified<br/>| 247 |
| [usfrs_air_Industry](slots/usfrs_air_Industry.md) | No slot (predicate) description specified<br/>| 45688 |
| [usfrs_airs_afs_Industry](slots/usfrs_airs_afs_Industry.md) | No slot (predicate) description specified<br/>| 52374 |
| [usfrs_caaIndustry](slots/usfrs_caaIndustry.md) | Clean Air Act (Air) programs Industry Code<br/>| 78228 |
| [usfrs_camdbs_Industry](slots/usfrs_camdbs_Industry.md) | CAM (Compliance Assurance Monitoring) database system Industry Code<br/>| 298 |
| [usfrs_cedri_Industry](slots/usfrs_cedri_Industry.md) | Compliance and Emissions data reporting Interface Industry Code<br/>| 38 |
| [usfrs_cerclaIndustry](slots/usfrs_cerclaIndustry.md) | Comprehensive Environmental Response, Compensation and Liability Act Industry...<br/>No occurrences of this slot in the graph.| 0 |
| [usfrs_cwaIndustry](slots/usfrs_cwaIndustry.md) | Clean Water Act programs Industry Code<br/>| 9272 |
| [usfrs_e_ggrt_Industry](slots/usfrs_e_ggrt_Industry.md) | Electronic Greenhous Gas Reporting Tool Industry Code<br/>| 534 |
| [usfrs_ecrm_Industry](slots/usfrs_ecrm_Industry.md) | No slot (predicate) description specified<br/>| 1 |
| [usfrs_eia_860_Industry](slots/usfrs_eia_860_Industry.md) | Energy Information Administration-860 database Industry Code<br/>| 23 |
| [usfrs_eis_Industry](slots/usfrs_eis_Industry.md) | Emissions Inventory System Industry Code<br/>| 15675 |
| [usfrs_environmentalInterestType](slots/usfrs_environmentalInterestType.md) | No slot (predicate) description specified<br/>| 100661 |
| [usfrs_epcraIndustry](slots/usfrs_epcraIndustry.md) | Emergency Planning and Community Right-to-Know Act Industry Code<br/>| 10472 |
| [usfrs_eps_Industry](slots/usfrs_eps_Industry.md) | Electronic Permit System Industry Code<br/>| 29 |
| [usfrs_fifraIndustry](slots/usfrs_fifraIndustry.md) | Federal Insecticide, Fungicide and Rodenticide Act Industry Code<br/>| 2331 |
| [usfrs_hasACESId](slots/usfrs_hasACESId.md) | No slot (predicate) description specified<br/>| 80 |
| [usfrs_hasAIRId](slots/usfrs_hasAIRId.md) | No slot (predicate) description specified<br/>| 22529 |
| [usfrs_hasAirId](slots/usfrs_hasAirId.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [usfrs_hasAIRSAFSId](slots/usfrs_hasAIRSAFSId.md) | No slot (predicate) description specified<br/>| 26613 |
| [usfrs_hasCAMDBSId](slots/usfrs_hasCAMDBSId.md) | No slot (predicate) description specified<br/>| 200 |
| [usfrs_hasCEDRIId](slots/usfrs_hasCEDRIId.md) | No slot (predicate) description specified<br/>| 38 |
| [usfrs_hasECRMId](slots/usfrs_hasECRMId.md) | No slot (predicate) description specified<br/>| 1 |
| [usfrs_hasEGGRTId](slots/usfrs_hasEGGRTId.md) | No slot (predicate) description specified<br/>| 497 |
| [usfrs_hasEIA860Id](slots/usfrs_hasEIA860Id.md) | No slot (predicate) description specified<br/>| 23 |
| [usfrs_hasEISId](slots/usfrs_hasEISId.md) | No slot (predicate) description specified<br/>| 15807 |
| [usfrs_hasEPSId](slots/usfrs_hasEPSId.md) | No slot (predicate) description specified<br/>| 29 |
| [usfrs_hasFRSId](slots/usfrs_hasFRSId.md) | No slot (predicate) description specified<br/>| 300920 |
| [usfrs_hasICISId](slots/usfrs_hasICISId.md) | No slot (predicate) description specified<br/>| 1065 |
| [usfrs_hasMEEFISId](slots/usfrs_hasMEEFISId.md) | No slot (predicate) description specified<br/>| 1723 |
| [usfrs_hasMNTEMPOId](slots/usfrs_hasMNTEMPOId.md) | No slot (predicate) description specified<br/>| 6 |
| [usfrs_hasNJNJEMSId](slots/usfrs_hasNJNJEMSId.md) | No slot (predicate) description specified<br/>| 4 |
| [usfrs_hasNPDESId](slots/usfrs_hasNPDESId.md) | No slot (predicate) description specified<br/>| 112 |
| [usfrs_hasOSHAOISId](slots/usfrs_hasOSHAOISId.md) | No slot (predicate) description specified<br/>| 10004 |
| [usfrs_hasRCRAId](slots/usfrs_hasRCRAId.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [usfrs_hasRCRAINFOId](slots/usfrs_hasRCRAINFOId.md) | No slot (predicate) description specified<br/>| 30246 |
| [usfrs_hasRMPId](slots/usfrs_hasRMPId.md) | No slot (predicate) description specified<br/>| 1951 |
| [usfrs_hasSDWAId](slots/usfrs_hasSDWAId.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [usfrs_hasTRIId](slots/usfrs_hasTRIId.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [usfrs_hasTRISId](slots/usfrs_hasTRISId.md) | No slot (predicate) description specified<br/>| 6452 |
| [usfrs_icis_Industry](slots/usfrs_icis_Industry.md) | Integrated Compliance Information System Industry Code<br/>| 4984 |
| [usfrs_me_efis_Industry](slots/usfrs_me_efis_Industry.md) | No slot (predicate) description specified<br/>| 3567 |
| [usfrs_mn_tempo_Industry](slots/usfrs_mn_tempo_Industry.md) | No slot (predicate) description specified<br/>| 25 |
| [usfrs_ncdb_Industry](slots/usfrs_ncdb_Industry.md) | National Compliance Database System (pesticide/ toxic substances programs) In...<br/>| 536 |
| [usfrs_nj_njems_Industry](slots/usfrs_nj_njems_Industry.md) | No slot (predicate) description specified<br/>| 6 |
| [usfrs_npdes_Industry](slots/usfrs_npdes_Industry.md) | National Pollutant Discharge Elimination system Industry Code<br/>| 9272 |
| [usfrs_nv_fp_Industry](slots/usfrs_nv_fp_Industry.md) | No slot (predicate) description specified<br/>| 1 |
| [usfrs_odaIndustry](slots/usfrs_odaIndustry.md) | Ocean Dumping Act Industry Code<br/>No occurrences of this slot in the graph.| 0 |
| [usfrs_oh_core_Industry](slots/usfrs_oh_core_Industry.md) | No slot (predicate) description specified<br/>| 14161 |
| [usfrs_osha_ois_Industry](slots/usfrs_osha_ois_Industry.md) | Occupational Safety and Health Administration Information System Industry Cod...<br/>| 7604 |
| [usfrs_primaryIndustry](slots/usfrs_primaryIndustry.md) | No slot (predicate) description specified<br/>| 129450 |
| [usfrs_rblc_Industry](slots/usfrs_rblc_Industry.md) | RACT/BACT/LAER CLEARINGHOUSE Industry Code<br/>| 126 |
| [usfrs_rcraIndustry](slots/usfrs_rcraIndustry.md) | Resource Conservation and Recovery Act (Hazardous Waste) programs Industry Co...<br/>No occurrences of this slot in the graph.| 0 |
| [usfrs_rcrainfo](slots/usfrs_rcrainfo.md) | Resource Conservation and Recovery Act Information System Industry Code<br/>No occurrences of this slot in the graph.| 0 |
| [usfrs_rcrainfo_Industry](slots/usfrs_rcrainfo_Industry.md) | No slot (predicate) description specified<br/>| 32902 |
| [usfrs_rmp_Industry](slots/usfrs_rmp_Industry.md) | Risk Management Plan Industry Code<br/>| 2347 |
| [usfrs_sdwaIndustry](slots/usfrs_sdwaIndustry.md) | Safe Drinking Water Act programs Industry Code<br/>No occurrences of this slot in the graph.| 0 |
| [usfrs_secondaryIndustry](slots/usfrs_secondaryIndustry.md) | No slot (predicate) description specified<br/>| 6999 |
| [usfrs_ssts_Industry](slots/usfrs_ssts_Industry.md) | Section Seven Tracking System (pesticides programs) Industry Code<br/>| 1797 |
| [usfrs_stateIndustry](slots/usfrs_stateIndustry.md) | State programs Industry Code<br/>| 3567 |
| [usfrs_tris_Industry](slots/usfrs_tris_Industry.md) | Toxic Release Inventory program Industry Code<br/>| 10472 |
| [usfrs_tscaIndustry](slots/usfrs_tscaIndustry.md) | Toxic Substances Control Act Industry Code<br/>| 536 |
| [xsd_length](slots/xsd_length.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_maxExclusive](slots/xsd_maxExclusive.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_maxInclusive](slots/xsd_maxInclusive.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_maxLength](slots/xsd_maxLength.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_minExclusive](slots/xsd_minExclusive.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_minInclusive](slots/xsd_minInclusive.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_minLength](slots/xsd_minLength.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_pattern](slots/xsd_pattern.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |









## IRI prefixes

* dct: http://purl.org/dc/terms/
* fio: http://sawgraph.spatialai.org/v1/fio#
* geo: http://www.opengis.net/ont/geosparql#
* hsdo: http://schema.org/
* kwgo: http://stko-kwg.geog.ucsb.edu/lod/ontology/
* kwgr: http://stko-kwg.geog.ucsb.edu/lod/resource/
* linkml: https://w3id.org/linkml/
* naics: http://sawgraph.spatialai.org/v1/fio/naics#
* owl: http://www.w3.org/2002/07/owl#
* prov: http://www.w3.org/ns/prov#
* psys: http://proton.semanticweb.org/protonsys#
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* skos: http://www.w3.org/2004/02/skos/core#
* usfrs: http://sawgraph.spatialai.org/v1/us-frs#
* usfrsdata: http://sawgraph.spatialai.org/v1/us-frs-data#
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
* schema: http://schema.org/
