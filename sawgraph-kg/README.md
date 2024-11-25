# The PFAS specific concepts that extend ContaminOSO

the Contaminant Observation and Samples Ontology (ContaminOSO) developed as part of the AIKnowsPFAS and SAWGraph projects.

URI: sawgraph-kg

Name: sawgraph-kg



## Schema Diagram

```mermaid
erDiagram
Any {

}
ContaminosoAggregateContaminantMeasurement {
    uri qudt_quantityValue  
}
ContaminosoAnalysisMethod {

}
ContaminosoContaminantConcentrationMeasurement {

}
ContaminosoContaminantMeasurement {
    uri qudt_quantityValue  
}
ContaminosoContaminantObservation {
    date contaminoso_analysisDate  
    date contaminoso_sampleTime  
    uri contaminoso_hasTemporalCoverage  
    date sosa_resultTime  
    uri contaminoso_hasAggregationPeriod  
    string http___sawgraph.spatialai.org_v1_us_epa_ghg#GHG_Subpart  
    date contaminoso_sampledTime  
}
ContaminosoContaminantVolumeMeasurement {

}
ContaminosoFeature {
    string usfrs_hasGHGId  
    date ussdwis_lastReport  
    string ussdwis_pwsName  
    string ussdwis_hasPWSID  
    date ussdwis_firstReport  
    string ussdwis_hasOwnership  
    string ussdwis_sizeCategory  
    string ussdwis_primarySource  
    string ilisgs_hasOwner  
    integer ussdwis_populationServed  
    string ussdwis_hasActivity  
    string ilisgs_hasISWSId  
    string ussdwis_hasName  
    date ussdwis_deactivationDate  
    integer ussdwis_serviceConnections  
}
ContaminosoMaterialSample {
    string meegad_sampleID  
    string ussdwis_sampleID  
}
ContaminosoMaterialType {

}
ContaminosoMaximumConcentration {

}
ContaminosoMinimumConcentration {

}
ContaminosoObservationAnnotation {

}
ContaminosoPoint {
    string ussdwis_SamplePointID  
    integer meegad_samplePointNumber  
    string meegad_samplePointWebName  
}
ContaminosoReleaseContaminantObservation {

}
ContaminosoReleaseFeature {

}
ContaminosoReleasePoint {

}
ContaminosoResultQualifier {
    string meegad_parameterGroup  
}
ContaminosoSampleAnnotation {

}
ContaminosoSampleContaminantObservation {

}
ContaminosoSampleMaterialType {

}
ContaminosoSamplePoint {

}
ContaminosoSampledFeature {

}
ContaminosoSampledFeaure {

}
ContaminosoSingleContaminantMeasurement {

}
ContaminosoSingleContaminantObservation {

}
ContaminosoSubstance {
    string http___sawgraph.spatialai.org_v1_us_epa_ghg#chemicalFormula  
    string http___sawgraph.spatialai.org_v1_me_egad_data#dep_chemicalID  
    string contaminoso_substanceID  
    string meegad_parameterName  
    string http___sawgraph.spatialai.org_v1_us_epa_ghg#casNumber  
    string meegad_parameterAbbreviation  
    string contaminoso_casNumber  
}
GeoFeature {

}
GeoGeometry {

}
GeoSpatialObject {

}
GeoDggsLiteral {

}
GeoGeoJSONLiteral {

}
GeoGmlLiteral {

}
GeoKmlLiteral {

}
GeoWktLiteral {

}
HttpQudt.orgVocabUnitUnit {

}
HttpSawgraph.spatialai.orgV1Stad#Quantity {
    uri https___qudt.org_schema_qudt_unit  
    float https___qudt.org_schema_qudt_numericValue  
}
HttpSawgraph.spatialai.orgV1Stad#SingleData {
    uri https___qudt.org_schema_qudt_unit  
    float https___qudt.org_schema_qudt_numericValue  
}
HttpSawgraph.spatialai.orgV1Stad#StatisticalAggregateData {
    uri https___qudt.org_schema_qudt_unit  
    float https___qudt.org_schema_qudt_numericValue  
}
HttpSawgraph.spatialai.orgV1Stad#StatisticalQuantityKind {

}
HttpSawgraph.spatialai.orgV1Us-epa-ghg#Amount {
    uri https___qudt.org_schema_qudt_unit  
    float https___qudt.org_schema_qudt_numericValue  
}
HttpSawgraph.spatialai.orgV1Us-epa-ghg#Chemical {

}
HttpSawgraph.spatialai.orgV1Us-epa-ghg#Measurement {

}
HttpSawgraph.spatialai.orgV1Us-epa-ghg#ReleaseObservation {

}
HttpStko-kwg.geog.ucsb.eduLodOntologyS2CellLevel13 {

}
HttpWww.opengis.netOntSf#Point {

}
HttpsQudt.orgSchemaQudtQuantityValue {

}
IlisgsISGS-Well {

}
IlisgsWellDepthInFt {
    float https___qudt.org_schema_qudt_numericValue  
    uri https___qudt.org_schema_qudt_unit  
}
IlisgsWellPurpose {

}
IlisgsWellYield {
    uri https___qudt.org_schema_qudt_unit  
    float https___qudt.org_schema_qudt_numericValue  
}
MeegadEGAD-AggregatePFAS-Concentration {

}
MeegadEGAD-AnalysisMethod {

}
MeegadEGAD-LabQualifier {
    string meegad_parameterGroup  
}
MeegadEGAD-MethodDetectionLimit {

}
MeegadEGAD-PFAS-Observation {

}
MeegadEGAD-PFAS-ParameterName {

}
MeegadEGAD-ReportingLimit {

}
MeegadEGAD-ResultType {

}
MeegadEGAD-Sample {

}
MeegadEGAD-SampleCollectionMethod {

}
MeegadEGAD-SampleDetailedLocation {

}
MeegadEGAD-SampleMaterialType {

}
MeegadEGAD-SamplePoint {

}
MeegadEGAD-SamplePointType {

}
MeegadEGAD-SampleTreatmentStatus {

}
MeegadEGAD-SampledFeature {

}
MeegadEGAD-SinglePFAS-Concentration {

}
MeegadEGAD-Site {
    string http___sawgraph.spatialai.org_v1_sdwis#pwsidNumber  
    integer meegad_siteNumber  
    string meegad_siteName  
}
MeegadEGAD-SiteType {
    string http___www.w3.org_2008_05_skos#definition  
}
MeegadEGAD-ValidationLevel {
    string meegad_parameterGroup  
}
MeegadEGAD-ValidationQualifier {
    string meegad_parameterGroup  
}
MemgsMGS-Well {

}
MemgsWellDepthInFt {
    uri https___qudt.org_schema_qudt_unit  
    float https___qudt.org_schema_qudt_numericValue  
}
MemgsWellOverburdenThicknessInFt {
    uri https___qudt.org_schema_qudt_unit  
    float https___qudt.org_schema_qudt_numericValue  
}
MemgsWellType {

}
MemgsWellUse {

}
OwlNamedIndividual {

}
PfasAggregatePFASAmountMeasurement {

}
PfasAggregatePFASConcentrationMeasurement {

}
PfasAnalysisMethod {

}
PfasMethodDetectionLimit {
    string meegad_parameterGroup  
}
PfasPFAS-ConcentrationMeasurement {

}
PfasPFAS-ContaminantObservation {

}
PfasPFAS-ReleaseContaminantObservation {

}
PfasPFAS-SampleContaminantObservation {

}
PfasPFAS-VolumeMeasurement {

}
PfasQuantitationLimit {
    string meegad_parameterGroup  
}
PfasReportingLimit {
    string meegad_parameterGroup  
}
PfasSinglePFASConcentrationMeasurement {

}
ProvOrganization {

}
RdfList {

}
SosaFeatureOfInterest {

}
SosaObservableProperty {

}
SosaObservation {

}
SosaProcedure {

}
SosaResult {

}
SosaSample {

}
UsfrsFRS-Facility {

}
UssdwisAmount {
    uri https___qudt.org_schema_qudt_unit  
    float https___qudt.org_schema_qudt_numericValue  
}
UssdwisCombinedDistributionSystem {

}
UssdwisPWS-Observation {

}
UssdwisPWS-PFAS {

}
UssdwisPWS-PFASConcentration {

}
UssdwisPWS-Sample {

}
UssdwisPWS-SamplePoint {

}
UssdwisPublicWaterSystem {

}
UssdwisPublicWaterSystem-CWS {

}
UssdwisPublicWaterSystem-GW {

}
UssdwisPublicWaterSystem-NTNCWS {

}
UssdwisPublicWaterSystem-SW {

}
UssdwisPublicWaterSystem-TNCWS {

}
UssdwisSampledFeature {

}

ContaminosoAggregateContaminantMeasurement ||--|o Any : "meegad_validationQualifier"
ContaminosoAggregateContaminantMeasurement ||--|o ContaminosoResultQualifier : "meegad_labQualifier"
ContaminosoAggregateContaminantMeasurement ||--|o Any : "contaminoso_resultAnnotation"
ContaminosoAggregateContaminantMeasurement ||--|o Any : "meegad_validationLevel"
ContaminosoAggregateContaminantMeasurement ||--|o HttpSawgraph.spatialai.orgV1Stad#Quantity : "https___qudt.org_schema_qudt_quantityKind"
ContaminosoAggregateContaminantMeasurement ||--|o Any : "rdfs_label"
ContaminosoContaminantMeasurement ||--|o Any : "meegad_validationQualifier"
ContaminosoContaminantMeasurement ||--|o ContaminosoResultQualifier : "meegad_labQualifier"
ContaminosoContaminantMeasurement ||--|o Any : "contaminoso_resultAnnotation"
ContaminosoContaminantMeasurement ||--|o Any : "meegad_validationLevel"
ContaminosoContaminantMeasurement ||--|o UssdwisAmount : "https___qudt.org_schema_qudt_quantityValue"
ContaminosoContaminantMeasurement ||--|o Any : "rdfs_label"
ContaminosoContaminantObservation ||--|o ContaminosoAggregateContaminantMeasurement : "contaminoso_hasResult"
ContaminosoContaminantObservation ||--|o MeegadEGAD-AnalysisMethod : "contaminoso_analysisMethod"
ContaminosoContaminantObservation ||--|o ContaminosoFeature : "contaminoso_hasFeatureOfInterest"
ContaminosoContaminantObservation ||--|o ProvOrganization : "contaminoso_analyzedBy"
ContaminosoContaminantObservation ||--|o ContaminosoFeature : "sosa_hasFeatureOfInterest"
ContaminosoContaminantObservation ||--|o ContaminosoMaterialSample : "meegad_analyzedSample"
ContaminosoContaminantObservation ||--|o ContaminosoFeature : "contaminoso_fromSampledFeature"
ContaminosoContaminantObservation ||--|o Any : "contaminoso_analyzedSample"
ContaminosoContaminantObservation ||--|o Any : "contaminoso_ofSubstance"
ContaminosoContaminantObservation ||--|o Any : "sosa_hasResult"
ContaminosoContaminantObservation ||--|o Any : "rdfs_label"
ContaminosoContaminantObservation ||--|o ContaminosoPoint : "contaminoso_observedAtSamplePoint"
ContaminosoContaminantObservation ||--|o Any : "contaminoso_sampledFeature"
ContaminosoContaminantObservation ||--|o ContaminosoObservationAnnotation : "meegad_resultType"
ContaminosoContaminantObservation ||--|o Any : "sosa_observedProperty"
ContaminosoContaminantObservation ||--|o ContaminosoObservationAnnotation : "contaminoso_observationAnnotation"
ContaminosoFeature ||--|o MeegadEGAD-SamplePointType : "meegad_sampledFeatureType"
ContaminosoFeature ||--|o Any : "http___stko-kwg.geog.ucsb.edu_lod_ontology_spatialRelation"
ContaminosoFeature ||--|o ContaminosoFeature : "ussdwis_inCombinedSystem"
ContaminosoFeature ||--|o Any : "geo_hasGeometry"
ContaminosoFeature ||--|o IlisgsWellPurpose : "ilisgs_wellPurpose"
ContaminosoFeature ||--|o Any : "rdfs_label"
ContaminosoFeature ||--|o GeoGeometry : "geo_hasDefaultGeometry"
ContaminosoFeature ||--|o IlisgsWellDepthInFt : "ilisgs_wellDepth"
ContaminosoFeature ||--|o IlisgsWellYield : "ilisgs_wellYield"
ContaminosoFeature ||--|o GeoGeometry : "geo_defaultGeometry"
ContaminosoFeature ||--|o Any : "http___stko-kwg.geog.ucsb.edu_lod_ontology_sfWithin"
ContaminosoFeature ||--|o GeoWktLiteral : "geo_hasSerialization"
ContaminosoMaterialSample ||--|o Any : "meegad_sampleCollectionMethod"
ContaminosoMaterialSample ||--|o Any : "contaminoso_ofSampleMaterialType"
ContaminosoMaterialSample ||--|o Any : "contaminoso_sampleAnnotation"
ContaminosoMaterialSample ||--|o Any : "meegad_sampleTreatmentStatus"
ContaminosoMaterialSample ||--|o Any : "contaminoso_fromSamplePoint"
ContaminosoMaterialSample ||--|o Any : "meegad_sampleCollectionLocation"
ContaminosoMaterialSample ||--|o Any : "rdfs_label"
ContaminosoMaterialType ||--|o Any : "rdfs_label"
ContaminosoObservationAnnotation ||--|o Any : "rdfs_label"
ContaminosoPoint ||--|o MeegadEGAD-SamplePointType : "meegad_samplePointType"
ContaminosoPoint ||--|o MeegadEGAD-Site : "meegad_associatedSite"
ContaminosoPoint ||--|o Any : "http___stko-kwg.geog.ucsb.edu_lod_ontology_spatialRelation"
ContaminosoPoint ||--|o ContaminosoFeature : "contaminoso_pointFromFeature"
ContaminosoPoint ||--|o Any : "geo_hasGeometry"
ContaminosoPoint ||--|o Any : "http___stko-kwg.geog.ucsb.edu_lod_ontology_sfWithin"
ContaminosoPoint ||--|o Any : "rdfs_label"
ContaminosoPoint ||--|o GeoGeometry : "geo_hasDefaultGeometry"
ContaminosoPoint ||--|o GeoWktLiteral : "geo_hasSerialization"
ContaminosoReleaseFeature ||--|o GeoWktLiteral : "geo_hasSerialization"
ContaminosoReleasePoint ||--|o GeoWktLiteral : "geo_hasSerialization"
ContaminosoResultQualifier ||--|o ContaminosoResultQualifier : "meegad_reportingLimit"
ContaminosoResultQualifier ||--|o ContaminosoResultQualifier : "meegad_methodDetectionLimit"
ContaminosoResultQualifier ||--|o Any : "contaminoso_resultAnnotation"
ContaminosoResultQualifier ||--|o Any : "rdfs_label"
ContaminosoResultQualifier ||--|o Any : "qudt_numericValue"
ContaminosoSampleAnnotation ||--|o Any : "rdfs_label"
ContaminosoSamplePoint ||--|o GeoWktLiteral : "geo_hasSerialization"
ContaminosoSampledFeaure ||--|o GeoWktLiteral : "geo_hasSerialization"
ContaminosoSubstance ||--|o Any : "rdfs_label"
GeoFeature ||--|o GeoWktLiteral : "geo_hasSerialization"
GeoGeometry ||--|o GeoWktLiteral : "geo_hasSerialization"
GeoGeometry ||--|o GeoWktLiteral : "geo_asWKT"
GeoSpatialObject ||--|o GeoWktLiteral : "geo_hasSerialization"
HttpQudt.orgVocabUnitUnit ||--|o Any : "rdfs_label"
HttpStko-kwg.geog.ucsb.eduLodOntologyS2CellLevel13 ||--|o Any : "http___stko-kwg.geog.ucsb.edu_lod_ontology_spatialRelation"
HttpStko-kwg.geog.ucsb.eduLodOntologyS2CellLevel13 ||--|o Any : "http___stko-kwg.geog.ucsb.edu_lod_ontology_sfContains"
IlisgsISGS-Well ||--|o GeoWktLiteral : "geo_hasSerialization"
IlisgsWellPurpose ||--|o Any : "rdfs_label"
MeegadEGAD-AnalysisMethod ||--|o Any : "rdfs_label"
MeegadEGAD-LabQualifier ||--|o ContaminosoResultQualifier : "meegad_reportingLimit"
MeegadEGAD-LabQualifier ||--|o ContaminosoResultQualifier : "meegad_methodDetectionLimit"
MeegadEGAD-LabQualifier ||--|o Any : "contaminoso_resultAnnotation"
MeegadEGAD-LabQualifier ||--|o Any : "rdfs_label"
MeegadEGAD-LabQualifier ||--|o Any : "qudt_numericValue"
MeegadEGAD-ResultType ||--|o Any : "rdfs_label"
MeegadEGAD-SampleCollectionMethod ||--|o Any : "rdfs_label"
MeegadEGAD-SampleDetailedLocation ||--|o Any : "rdfs_label"
MeegadEGAD-SampleMaterialType ||--|o Any : "rdfs_label"
MeegadEGAD-SamplePoint ||--|o GeoWktLiteral : "geo_hasSerialization"
MeegadEGAD-SamplePointType ||--|o Any : "rdfs_label"
MeegadEGAD-SampleTreatmentStatus ||--|o Any : "rdfs_label"
MeegadEGAD-Site ||--|o Any : "http___stko-kwg.geog.ucsb.edu_lod_ontology_spatialRelation"
MeegadEGAD-Site ||--|o Any : "geo_hasGeometry"
MeegadEGAD-Site ||--|o Any : "http___stko-kwg.geog.ucsb.edu_lod_ontology_sfWithin"
MeegadEGAD-Site ||--|o Any : "rdfs_label"
MeegadEGAD-Site ||--|o GeoGeometry : "geo_hasDefaultGeometry"
MeegadEGAD-SiteType ||--|o Any : "rdfs_label"
MeegadEGAD-ValidationLevel ||--|o ContaminosoResultQualifier : "meegad_reportingLimit"
MeegadEGAD-ValidationLevel ||--|o ContaminosoResultQualifier : "meegad_methodDetectionLimit"
MeegadEGAD-ValidationLevel ||--|o Any : "contaminoso_resultAnnotation"
MeegadEGAD-ValidationLevel ||--|o Any : "rdfs_label"
MeegadEGAD-ValidationLevel ||--|o Any : "qudt_numericValue"
MeegadEGAD-ValidationQualifier ||--|o ContaminosoResultQualifier : "meegad_reportingLimit"
MeegadEGAD-ValidationQualifier ||--|o ContaminosoResultQualifier : "meegad_methodDetectionLimit"
MeegadEGAD-ValidationQualifier ||--|o Any : "contaminoso_resultAnnotation"
MeegadEGAD-ValidationQualifier ||--|o Any : "rdfs_label"
MeegadEGAD-ValidationQualifier ||--|o Any : "qudt_numericValue"
MemgsMGS-Well ||--|o GeoWktLiteral : "geo_hasSerialization"
PfasMethodDetectionLimit ||--|o ContaminosoResultQualifier : "meegad_reportingLimit"
PfasMethodDetectionLimit ||--|o ContaminosoResultQualifier : "meegad_methodDetectionLimit"
PfasMethodDetectionLimit ||--|o Any : "contaminoso_resultAnnotation"
PfasMethodDetectionLimit ||--|o Any : "rdfs_label"
PfasMethodDetectionLimit ||--|o Any : "qudt_numericValue"
PfasQuantitationLimit ||--|o ContaminosoResultQualifier : "meegad_reportingLimit"
PfasQuantitationLimit ||--|o ContaminosoResultQualifier : "meegad_methodDetectionLimit"
PfasQuantitationLimit ||--|o Any : "contaminoso_resultAnnotation"
PfasQuantitationLimit ||--|o Any : "rdfs_label"
PfasQuantitationLimit ||--|o Any : "qudt_numericValue"
PfasReportingLimit ||--|o ContaminosoResultQualifier : "meegad_reportingLimit"
PfasReportingLimit ||--|o ContaminosoResultQualifier : "meegad_methodDetectionLimit"
PfasReportingLimit ||--|o Any : "contaminoso_resultAnnotation"
PfasReportingLimit ||--|o Any : "rdfs_label"
PfasReportingLimit ||--|o Any : "qudt_numericValue"
ProvOrganization ||--|o Any : "rdfs_label"
UsfrsFRS-Facility ||--|o GeoWktLiteral : "geo_hasSerialization"
UssdwisCombinedDistributionSystem ||--|o GeoWktLiteral : "geo_hasSerialization"
UssdwisPWS-SamplePoint ||--|o GeoWktLiteral : "geo_hasSerialization"
UssdwisPublicWaterSystem ||--|o GeoWktLiteral : "geo_hasSerialization"
UssdwisPublicWaterSystem-CWS ||--|o GeoWktLiteral : "geo_hasSerialization"
UssdwisPublicWaterSystem-GW ||--|o GeoWktLiteral : "geo_hasSerialization"
UssdwisPublicWaterSystem-NTNCWS ||--|o GeoWktLiteral : "geo_hasSerialization"
UssdwisPublicWaterSystem-SW ||--|o GeoWktLiteral : "geo_hasSerialization"
UssdwisPublicWaterSystem-TNCWS ||--|o GeoWktLiteral : "geo_hasSerialization"

```


## Classes

| Class | Description |
| --- | --- |
| [Any](classes/Any.md) | None |
| [ContaminosoAnalysisMethod](classes/ContaminosoAnalysisMethod.md) | TODO -- tell the world what this class (type) describes. |
| [ContaminosoMaterialType](classes/ContaminosoMaterialType.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-SampleMaterialType](classes/MeegadEGAD-SampleMaterialType.md) | TODO -- tell the world what this class (type) describes. |
| [ContaminosoObservationAnnotation](classes/ContaminosoObservationAnnotation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-ResultType](classes/MeegadEGAD-ResultType.md) | TODO -- tell the world what this class (type) describes. |
| [ContaminosoResultQualifier](classes/ContaminosoResultQualifier.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-LabQualifier](classes/MeegadEGAD-LabQualifier.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-ValidationLevel](classes/MeegadEGAD-ValidationLevel.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-ValidationQualifier](classes/MeegadEGAD-ValidationQualifier.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[PfasMethodDetectionLimit](classes/PfasMethodDetectionLimit.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[PfasQuantitationLimit](classes/PfasQuantitationLimit.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[PfasReportingLimit](classes/PfasReportingLimit.md) | TODO -- tell the world what this class (type) describes. |
| [ContaminosoSampleAnnotation](classes/ContaminosoSampleAnnotation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-SampleCollectionMethod](classes/MeegadEGAD-SampleCollectionMethod.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-SampleDetailedLocation](classes/MeegadEGAD-SampleDetailedLocation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-SampleTreatmentStatus](classes/MeegadEGAD-SampleTreatmentStatus.md) | TODO -- tell the world what this class (type) describes. |
| [ContaminosoSampleMaterialType](classes/ContaminosoSampleMaterialType.md) | TODO -- tell the world what this class (type) describes. |
| [GeoDggsLiteral](classes/GeoDggsLiteral.md) | TODO -- tell the world what this class (type) describes. |
| [GeoGeoJSONLiteral](classes/GeoGeoJSONLiteral.md) | TODO -- tell the world what this class (type) describes. |
| [GeoGmlLiteral](classes/GeoGmlLiteral.md) | TODO -- tell the world what this class (type) describes. |
| [GeoKmlLiteral](classes/GeoKmlLiteral.md) | TODO -- tell the world what this class (type) describes. |
| [GeoSpatialObject](classes/GeoSpatialObject.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoFeature](classes/ContaminosoFeature.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoPoint](classes/ContaminosoPoint.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoReleaseFeature](classes/ContaminosoReleaseFeature.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoReleasePoint](classes/ContaminosoReleasePoint.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoSampledFeaure](classes/ContaminosoSampledFeaure.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoSamplePoint](classes/ContaminosoSamplePoint.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[GeoFeature](classes/GeoFeature.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[GeoGeometry](classes/GeoGeometry.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[IlisgsISGS-Well](classes/IlisgsISGS-Well.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-SamplePoint](classes/MeegadEGAD-SamplePoint.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MemgsMGS-Well](classes/MemgsMGS-Well.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UsfrsFRS-Facility](classes/UsfrsFRS-Facility.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisCombinedDistributionSystem](classes/UssdwisCombinedDistributionSystem.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisPublicWaterSystem](classes/UssdwisPublicWaterSystem.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisPublicWaterSystem-CWS](classes/UssdwisPublicWaterSystem-CWS.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisPublicWaterSystem-GW](classes/UssdwisPublicWaterSystem-GW.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisPublicWaterSystem-NTNCWS](classes/UssdwisPublicWaterSystem-NTNCWS.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisPublicWaterSystem-SW](classes/UssdwisPublicWaterSystem-SW.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisPublicWaterSystem-TNCWS](classes/UssdwisPublicWaterSystem-TNCWS.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisPWS-SamplePoint](classes/UssdwisPWS-SamplePoint.md) | TODO -- tell the world what this class (type) describes. |
| [GeoWktLiteral](classes/GeoWktLiteral.md) | TODO -- tell the world what this class (type) describes. |
| [HttpQudt.orgVocabUnitUnit](classes/HttpQudt.orgVocabUnitUnit.md) | TODO -- tell the world what this class (type) describes. |
| [HttpSawgraph.spatialai.orgV1Stad#Quantity](classes/HttpSawgraph.spatialai.orgV1Stad#Quantity.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpSawgraph.spatialai.orgV1Stad#SingleData](classes/HttpSawgraph.spatialai.orgV1Stad#SingleData.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[IlisgsWellDepthInFt](classes/IlisgsWellDepthInFt.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[IlisgsWellYield](classes/IlisgsWellYield.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MemgsWellDepthInFt](classes/MemgsWellDepthInFt.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MemgsWellOverburdenThicknessInFt](classes/MemgsWellOverburdenThicknessInFt.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpSawgraph.spatialai.orgV1Stad#StatisticalAggregateData](classes/HttpSawgraph.spatialai.orgV1Stad#StatisticalAggregateData.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpSawgraph.spatialai.orgV1Us-epa-ghg#Amount](classes/HttpSawgraph.spatialai.orgV1Us-epa-ghg#Amount.md) | TODO -- tell the world what this class (type) describes. |
| [HttpSawgraph.spatialai.orgV1Stad#StatisticalQuantityKind](classes/HttpSawgraph.spatialai.orgV1Stad#StatisticalQuantityKind.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoMaximumConcentration](classes/ContaminosoMaximumConcentration.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoMinimumConcentration](classes/ContaminosoMinimumConcentration.md) | TODO -- tell the world what this class (type) describes. |
| [HttpStko-kwg.geog.ucsb.eduLodOntologyS2CellLevel13](classes/HttpStko-kwg.geog.ucsb.eduLodOntologyS2CellLevel13.md) | TODO -- tell the world what this class (type) describes. |
| [HttpWww.opengis.netOntSf#Point](classes/HttpWww.opengis.netOntSf#Point.md) | TODO -- tell the world what this class (type) describes. |
| [HttpsQudt.orgSchemaQudtQuantityValue](classes/HttpsQudt.orgSchemaQudtQuantityValue.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-MethodDetectionLimit](classes/MeegadEGAD-MethodDetectionLimit.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-ReportingLimit](classes/MeegadEGAD-ReportingLimit.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisAmount](classes/UssdwisAmount.md) | TODO -- tell the world what this class (type) describes. |
| [IlisgsWellPurpose](classes/IlisgsWellPurpose.md) | TODO -- tell the world what this class (type) describes. |
| [MeegadEGAD-SamplePointType](classes/MeegadEGAD-SamplePointType.md) | TODO -- tell the world what this class (type) describes. |
| [MeegadEGAD-Site](classes/MeegadEGAD-Site.md) | TODO -- tell the world what this class (type) describes. |
| [MeegadEGAD-SiteType](classes/MeegadEGAD-SiteType.md) | TODO -- tell the world what this class (type) describes. |
| [MemgsWellType](classes/MemgsWellType.md) | TODO -- tell the world what this class (type) describes. |
| [MemgsWellUse](classes/MemgsWellUse.md) | TODO -- tell the world what this class (type) describes. |
| [OwlNamedIndividual](classes/OwlNamedIndividual.md) | TODO -- tell the world what this class (type) describes. |
| [ProvOrganization](classes/ProvOrganization.md) | TODO -- tell the world what this class (type) describes. |
| [RdfList](classes/RdfList.md) | TODO -- tell the world what this class (type) describes. |
| [SosaFeatureOfInterest](classes/SosaFeatureOfInterest.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoSampledFeature](classes/ContaminosoSampledFeature.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-SampledFeature](classes/MeegadEGAD-SampledFeature.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisSampledFeature](classes/UssdwisSampledFeature.md) | TODO -- tell the world what this class (type) describes. |
| [SosaObservableProperty](classes/SosaObservableProperty.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoSubstance](classes/ContaminosoSubstance.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpSawgraph.spatialai.orgV1Us-epa-ghg#Chemical](classes/HttpSawgraph.spatialai.orgV1Us-epa-ghg#Chemical.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-PFAS-ParameterName](classes/MeegadEGAD-PFAS-ParameterName.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisPWS-PFAS](classes/UssdwisPWS-PFAS.md) | TODO -- tell the world what this class (type) describes. |
| [SosaObservation](classes/SosaObservation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoContaminantObservation](classes/ContaminosoContaminantObservation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoReleaseContaminantObservation](classes/ContaminosoReleaseContaminantObservation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoSampleContaminantObservation](classes/ContaminosoSampleContaminantObservation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoSingleContaminantObservation](classes/ContaminosoSingleContaminantObservation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpSawgraph.spatialai.orgV1Us-epa-ghg#ReleaseObservation](classes/HttpSawgraph.spatialai.orgV1Us-epa-ghg#ReleaseObservation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-PFAS-Observation](classes/MeegadEGAD-PFAS-Observation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[PfasPFAS-ContaminantObservation](classes/PfasPFAS-ContaminantObservation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[PfasPFAS-ReleaseContaminantObservation](classes/PfasPFAS-ReleaseContaminantObservation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[PfasPFAS-SampleContaminantObservation](classes/PfasPFAS-SampleContaminantObservation.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisPWS-Observation](classes/UssdwisPWS-Observation.md) | TODO -- tell the world what this class (type) describes. |
| [SosaProcedure](classes/SosaProcedure.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-AnalysisMethod](classes/MeegadEGAD-AnalysisMethod.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[PfasAnalysisMethod](classes/PfasAnalysisMethod.md) | TODO -- tell the world what this class (type) describes. |
| [SosaResult](classes/SosaResult.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoAggregateContaminantMeasurement](classes/ContaminosoAggregateContaminantMeasurement.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoContaminantConcentrationMeasurement](classes/ContaminosoContaminantConcentrationMeasurement.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoContaminantMeasurement](classes/ContaminosoContaminantMeasurement.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoContaminantVolumeMeasurement](classes/ContaminosoContaminantVolumeMeasurement.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoSingleContaminantMeasurement](classes/ContaminosoSingleContaminantMeasurement.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[HttpSawgraph.spatialai.orgV1Us-epa-ghg#Measurement](classes/HttpSawgraph.spatialai.orgV1Us-epa-ghg#Measurement.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-AggregatePFAS-Concentration](classes/MeegadEGAD-AggregatePFAS-Concentration.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-SinglePFAS-Concentration](classes/MeegadEGAD-SinglePFAS-Concentration.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[PfasAggregatePFASAmountMeasurement](classes/PfasAggregatePFASAmountMeasurement.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[PfasAggregatePFASConcentrationMeasurement](classes/PfasAggregatePFASConcentrationMeasurement.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[PfasPFAS-ConcentrationMeasurement](classes/PfasPFAS-ConcentrationMeasurement.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[PfasPFAS-VolumeMeasurement](classes/PfasPFAS-VolumeMeasurement.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[PfasSinglePFASConcentrationMeasurement](classes/PfasSinglePFASConcentrationMeasurement.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisPWS-PFASConcentration](classes/UssdwisPWS-PFASConcentration.md) | TODO -- tell the world what this class (type) describes. |
| [SosaSample](classes/SosaSample.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ContaminosoMaterialSample](classes/ContaminosoMaterialSample.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[MeegadEGAD-Sample](classes/MeegadEGAD-Sample.md) | TODO -- tell the world what this class (type) describes. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[UssdwisPWS-Sample](classes/UssdwisPWS-Sample.md) | TODO -- tell the world what this class (type) describes. |



## Slots

| Slot | Description |
| --- | --- |
| [contaminoso_analysisDate](slots/contaminoso_analysisDate.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_analysisMethod](slots/contaminoso_analysisMethod.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_analyzedBy](slots/contaminoso_analyzedBy.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_analyzedSample](slots/contaminoso_analyzedSample.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_casNumber](slots/contaminoso_casNumber.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_fromSampledFeature](slots/contaminoso_fromSampledFeature.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_fromSamplePoint](slots/contaminoso_fromSamplePoint.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_hasAggregationPeriod](slots/contaminoso_hasAggregationPeriod.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_hasFeatureOfInterest](slots/contaminoso_hasFeatureOfInterest.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_hasResult](slots/contaminoso_hasResult.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_hasTemporalCoverage](slots/contaminoso_hasTemporalCoverage.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_mUnit](slots/contaminoso_mUnit.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_mValue](slots/contaminoso_mValue.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_observationAnnotation](slots/contaminoso_observationAnnotation.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_observedAnalyte](slots/contaminoso_observedAnalyte.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_observedAtSamplePoint](slots/contaminoso_observedAtSamplePoint.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_ofSampleMaterialType](slots/contaminoso_ofSampleMaterialType.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_ofSubstance](slots/contaminoso_ofSubstance.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_pointFromFeature](slots/contaminoso_pointFromFeature.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_resultAnnotation](slots/contaminoso_resultAnnotation.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_resultQualifier](slots/contaminoso_resultQualifier.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_sampleAnnotation](slots/contaminoso_sampleAnnotation.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_sampledFeature](slots/contaminoso_sampledFeature.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_sampledTime](slots/contaminoso_sampledTime.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_sampleTime](slots/contaminoso_sampleTime.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_substanceID](slots/contaminoso_substanceID.md) | TODO -- tell the world what this slot (predicate) describes |
| [contaminoso_usedProcedure](slots/contaminoso_usedProcedure.md) | TODO -- tell the world what this slot (predicate) describes |
| [dct_contributor](slots/dct_contributor.md) | TODO -- tell the world what this slot (predicate) describes |
| [dct_created](slots/dct_created.md) | TODO -- tell the world what this slot (predicate) describes |
| [dct_creator](slots/dct_creator.md) | TODO -- tell the world what this slot (predicate) describes |
| [dct_description](slots/dct_description.md) | TODO -- tell the world what this slot (predicate) describes |
| [dct_issued](slots/dct_issued.md) | TODO -- tell the world what this slot (predicate) describes |
| [dct_license](slots/dct_license.md) | TODO -- tell the world what this slot (predicate) describes |
| [dct_modified](slots/dct_modified.md) | TODO -- tell the world what this slot (predicate) describes |
| [dct_publisher](slots/dct_publisher.md) | TODO -- tell the world what this slot (predicate) describes |
| [dct_replaces](slots/dct_replaces.md) | TODO -- tell the world what this slot (predicate) describes |
| [dct_rights](slots/dct_rights.md) | TODO -- tell the world what this slot (predicate) describes |
| [dct_source](slots/dct_source.md) | TODO -- tell the world what this slot (predicate) describes |
| [dct_title](slots/dct_title.md) | TODO -- tell the world what this slot (predicate) describes |
| [geo_asWKT](slots/geo_asWKT.md) | TODO -- tell the world what this slot (predicate) describes |
| [geo_defaultGeometry](slots/geo_defaultGeometry.md) | TODO -- tell the world what this slot (predicate) describes |
| [geo_hasDefaultGeometry](slots/geo_hasDefaultGeometry.md) | TODO -- tell the world what this slot (predicate) describes |
| [geo_hasGeometry](slots/geo_hasGeometry.md) | TODO -- tell the world what this slot (predicate) describes |
| [geo_hasSerialization](slots/geo_hasSerialization.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___proton.semanticweb.org_protonsys#transitiveOver](slots/http___proton.semanticweb.org_protonsys#transitiveOver.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___purl.org_vocab_vann_preferredNamespacePrefix](slots/http___purl.org_vocab_vann_preferredNamespacePrefix.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___purl.org_vocab_vann_preferredNamespaceUri](slots/http___purl.org_vocab_vann_preferredNamespaceUri.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___sawgraph.spatialai.org_v1_me_egad_data#dep_chemicalID](slots/http___sawgraph.spatialai.org_v1_me_egad_data#dep_chemicalID.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___sawgraph.spatialai.org_v1_sdwis#pwsidNumber](slots/http___sawgraph.spatialai.org_v1_sdwis#pwsidNumber.md) | Uniquely identifies the water system within a specific state |
| [http___sawgraph.spatialai.org_v1_us_epa_ghg#casNumber](slots/http___sawgraph.spatialai.org_v1_us_epa_ghg#casNumber.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___sawgraph.spatialai.org_v1_us_epa_ghg#chemicalFormula](slots/http___sawgraph.spatialai.org_v1_us_epa_ghg#chemicalFormula.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___sawgraph.spatialai.org_v1_us_epa_ghg#GHG_Subpart](slots/http___sawgraph.spatialai.org_v1_us_epa_ghg#GHG_Subpart.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___stko_kwg.geog.ucsb.edu_lod_ontology_sfContains](slots/http___stko_kwg.geog.ucsb.edu_lod_ontology_sfContains.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___stko_kwg.geog.ucsb.edu_lod_ontology_sfOverlaps](slots/http___stko_kwg.geog.ucsb.edu_lod_ontology_sfOverlaps.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___stko_kwg.geog.ucsb.edu_lod_ontology_sfTouches](slots/http___stko_kwg.geog.ucsb.edu_lod_ontology_sfTouches.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___stko_kwg.geog.ucsb.edu_lod_ontology_sfWithin](slots/http___stko_kwg.geog.ucsb.edu_lod_ontology_sfWithin.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___stko_kwg.geog.ucsb.edu_lod_ontology_spatialRelation](slots/http___stko_kwg.geog.ucsb.edu_lod_ontology_spatialRelation.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___www.w3.org_2008_05_skos#definition](slots/http___www.w3.org_2008_05_skos#definition.md) | TODO -- tell the world what this slot (predicate) describes |
| [https___qudt.org_schema_qudt_numericValue](slots/https___qudt.org_schema_qudt_numericValue.md) | TODO -- tell the world what this slot (predicate) describes |
| [https___qudt.org_schema_qudt_quantityKind](slots/https___qudt.org_schema_qudt_quantityKind.md) | TODO -- tell the world what this slot (predicate) describes |
| [https___qudt.org_schema_qudt_quantityValue](slots/https___qudt.org_schema_qudt_quantityValue.md) | TODO -- tell the world what this slot (predicate) describes |
| [https___qudt.org_schema_qudt_unit](slots/https___qudt.org_schema_qudt_unit.md) | TODO -- tell the world what this slot (predicate) describes |
| [ilisgs_hasISWSId](slots/ilisgs_hasISWSId.md) | TODO -- tell the world what this slot (predicate) describes |
| [ilisgs_hasOwner](slots/ilisgs_hasOwner.md) | TODO -- tell the world what this slot (predicate) describes |
| [ilisgs_wellDepth](slots/ilisgs_wellDepth.md) | TODO -- tell the world what this slot (predicate) describes |
| [ilisgs_wellPurpose](slots/ilisgs_wellPurpose.md) | TODO -- tell the world what this slot (predicate) describes |
| [ilisgs_wellYield](slots/ilisgs_wellYield.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_analyzedSample](slots/meegad_analyzedSample.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_associatedSite](slots/meegad_associatedSite.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_dep_chemicalID](slots/meegad_dep_chemicalID.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_labQualifier](slots/meegad_labQualifier.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_methodDetectionLimit](slots/meegad_methodDetectionLimit.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_parameterAbbreviation](slots/meegad_parameterAbbreviation.md) | Abbreviation of the PFAS parameter (single chemical or aggregate set of chemi... |
| [meegad_parameterGroup](slots/meegad_parameterGroup.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_parameterName](slots/meegad_parameterName.md) | Name of the PFAS parameter (single chemical or aggregate set of chemicals) me... |
| [meegad_reportingLimit](slots/meegad_reportingLimit.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_resultType](slots/meegad_resultType.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_sampleCollectionLocation](slots/meegad_sampleCollectionLocation.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_sampleCollectionMethod](slots/meegad_sampleCollectionMethod.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_sampledFeatureType](slots/meegad_sampledFeatureType.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_sampleID](slots/meegad_sampleID.md) | Sample identifier in the EGAD dataset from the state of Maine |
| [meegad_samplePointNumber](slots/meegad_samplePointNumber.md) | Sample point number in the EGAD dataset from the state of Maine |
| [meegad_samplePointType](slots/meegad_samplePointType.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_samplePointWebName](slots/meegad_samplePointWebName.md) | Sample point web name in the EGAD dataset from the state of Maine |
| [meegad_sampleTreatmentStatus](slots/meegad_sampleTreatmentStatus.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_siteName](slots/meegad_siteName.md) | Site name in the EGAD dataset from the state of Maine |
| [meegad_siteNumber](slots/meegad_siteNumber.md) | Site number in the EGAD dataset from the state of Maine |
| [meegad_siteType](slots/meegad_siteType.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_validationLevel](slots/meegad_validationLevel.md) | TODO -- tell the world what this slot (predicate) describes |
| [meegad_validationQualifier](slots/meegad_validationQualifier.md) | TODO -- tell the world what this slot (predicate) describes |
| [memgs_hasUse](slots/memgs_hasUse.md) | TODO -- tell the world what this slot (predicate) describes |
| [memgs_ofWellType](slots/memgs_ofWellType.md) | TODO -- tell the world what this slot (predicate) describes |
| [memgs_wellDepth](slots/memgs_wellDepth.md) | TODO -- tell the world what this slot (predicate) describes |
| [memgs_wellOverburden](slots/memgs_wellOverburden.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_allValuesFrom](slots/owl_allValuesFrom.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_differentFrom](slots/owl_differentFrom.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_disjointWith](slots/owl_disjointWith.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_equivalentClass](slots/owl_equivalentClass.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_equivalentProperty](slots/owl_equivalentProperty.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_imports](slots/owl_imports.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_inverseOf](slots/owl_inverseOf.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_onProperty](slots/owl_onProperty.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_propertyDisjointWith](slots/owl_propertyDisjointWith.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_subPropertyOf](slots/owl_subPropertyOf.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_topObjectProperty](slots/owl_topObjectProperty.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_versionInfo](slots/owl_versionInfo.md) | TODO -- tell the world what this slot (predicate) describes |
| [owl_versionIRI](slots/owl_versionIRI.md) | TODO -- tell the world what this slot (predicate) describes |
| [qudt_numericValue](slots/qudt_numericValue.md) | TODO -- tell the world what this slot (predicate) describes |
| [qudt_quantityValue](slots/qudt_quantityValue.md) | TODO -- tell the world what this slot (predicate) describes |
| [qudt_unit](slots/qudt_unit.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1](slots/rdf__1.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf_first](slots/rdf_first.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf_object](slots/rdf_object.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf_predicate](slots/rdf_predicate.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf_rest](slots/rdf_rest.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf_subject](slots/rdf_subject.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf_value](slots/rdf_value.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdfs_comment](slots/rdfs_comment.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdfs_domain](slots/rdfs_domain.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdfs_isDefinedBy](slots/rdfs_isDefinedBy.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdfs_label](slots/rdfs_label.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdfs_range](slots/rdfs_range.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdfs_seeAlso](slots/rdfs_seeAlso.md) | TODO -- tell the world what this slot (predicate) describes |
| [schema_affiliation](slots/schema_affiliation.md) | TODO -- tell the world what this slot (predicate) describes |
| [schema_email](slots/schema_email.md) | TODO -- tell the world what this slot (predicate) describes |
| [schema_name](slots/schema_name.md) | TODO -- tell the world what this slot (predicate) describes |
| [schema_url](slots/schema_url.md) | TODO -- tell the world what this slot (predicate) describes |
| [skos_definition](slots/skos_definition.md) | TODO -- tell the world what this slot (predicate) describes |
| [skos_example](slots/skos_example.md) | TODO -- tell the world what this slot (predicate) describes |
| [skos_note](slots/skos_note.md) | TODO -- tell the world what this slot (predicate) describes |
| [skos_prefLabel](slots/skos_prefLabel.md) | TODO -- tell the world what this slot (predicate) describes |
| [skos_scopeNote](slots/skos_scopeNote.md) | TODO -- tell the world what this slot (predicate) describes |
| [sosa_hasFeatureOfInterest](slots/sosa_hasFeatureOfInterest.md) | TODO -- tell the world what this slot (predicate) describes |
| [sosa_hasResult](slots/sosa_hasResult.md) | TODO -- tell the world what this slot (predicate) describes |
| [sosa_isSampleOf](slots/sosa_isSampleOf.md) | TODO -- tell the world what this slot (predicate) describes |
| [sosa_observedProperty](slots/sosa_observedProperty.md) | TODO -- tell the world what this slot (predicate) describes |
| [sosa_resultTime](slots/sosa_resultTime.md) | TODO -- tell the world what this slot (predicate) describes |
| [usfrs_hasGHGId](slots/usfrs_hasGHGId.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_deactivationDate](slots/ussdwis_deactivationDate.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_firstReport](slots/ussdwis_firstReport.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_hasActivity](slots/ussdwis_hasActivity.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_hasName](slots/ussdwis_hasName.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_hasOwnership](slots/ussdwis_hasOwnership.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_hasPWSID](slots/ussdwis_hasPWSID.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_inCombinedSystem](slots/ussdwis_inCombinedSystem.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_lastReport](slots/ussdwis_lastReport.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_populationServed](slots/ussdwis_populationServed.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_primarySource](slots/ussdwis_primarySource.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_pwsName](slots/ussdwis_pwsName.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_sampleID](slots/ussdwis_sampleID.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_SamplePointID](slots/ussdwis_SamplePointID.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_serviceConnections](slots/ussdwis_serviceConnections.md) | TODO -- tell the world what this slot (predicate) describes |
| [ussdwis_sizeCategory](slots/ussdwis_sizeCategory.md) | TODO -- tell the world what this slot (predicate) describes |


## Enumerations

| Enumeration | Description |
| --- | --- |


## Types

| Type | Description |
| --- | --- |


## Subsets

| Subset | Description |
| --- | --- |
