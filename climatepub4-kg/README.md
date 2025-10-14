# climatemodelskg





## Schema Diagram

```mermaid
erDiagram
HttpsClimatepub4kg.github.ioOntology#Activity {
    string neo4j_names  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#City {
    string neo4j_asciiname  
    string neo4j_dem  
    string neo4j_cc2  
    string neo4j_feature_class  
    string neo4j_alternatenames  
    string neo4j_elevation  
    string neo4j_longitude  
    string neo4j_geonameid  
    string neo4j_timezone  
    string neo4j_latitude  
    string neo4j_admin1_code  
    string neo4j_modification_date  
    string neo4j_name  
    string neo4j_admin2_code  
    string neo4j_country_code  
    string neo4j_admin3_code  
    string neo4j_uuid  
    string neo4j_population  
    string neo4j_admin4_code  
    string neo4j_feature_code  
}
HttpsClimatepub4kg.github.ioOntology#Continent {
    string neo4j_name  
    string neo4j_iso  
    string neo4j_geonameid  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Country {
    string neo4j_country  
    string neo4j_area_sqkm  
    string neo4j_south  
    string neo4j_postal_code_regex  
    string neo4j_phone  
    string neo4j_west  
    string neo4j_currencyname  
    string neo4j_iso3  
    string neo4j_neighbours  
    string neo4j_fips  
    string neo4j_postal_code_format  
    string neo4j_isonumeric  
    string neo4j_languages  
    string neo4j_tld  
    string neo4j_currencycode  
    string neo4j_iso  
    string neo4j_geonameid  
    string neo4j_east  
    string neo4j_equivalent_fips_code  
    string neo4j_north  
    string neo4j_name  
    string neo4j_capital  
    string neo4j_uuid  
    string neo4j_population  
    string neo4j_continent  
}
HttpsClimatepub4kg.github.ioOntology#CountrySubdivision {
    string neo4j_code  
    string neo4j_north  
    string neo4j_asciiname  
    string neo4j_south  
    string neo4j_name  
    string neo4j_west  
    string neo4j_uuid  
    string neo4j_geonameid  
    string neo4j_east  
}
HttpsClimatepub4kg.github.ioOntology#Domain {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Ensemble {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Experiment {
    string neo4j_names  
    string neo4j_name  
    string neo4j_uuid  
    string neo4j_experiment_title  
}
HttpsClimatepub4kg.github.ioOntology#ExperimentFamily {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Field {
    string neo4j_name  
    string neo4j_paper_id  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Forcing {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Frequency {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Innovation {
    string neo4j_name  
    string neo4j_paper_id  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Institute {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Instrument {
    string neo4j_name  
    string neo4j_added_from_paper_id  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Keyword {
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#MIPEra {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Member {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Method {
    string neo4j_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Metric {
    string neo4j_name  
    string neo4j_added_from_paper_id  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Model {
    string neo4j_name  
    string neo4j_uuid  
    string neo4j_paper_id  
}
HttpsClimatepub4kg.github.ioOntology#NaturalHazard {
    string neo4j_name  
    string neo4j_added_from_paper_id  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#NoCountryRegion {
    string neo4j_asciiname  
    string neo4j_dem  
    string neo4j_cc2  
    string neo4j_feature_class  
    string neo4j_alternatenames  
    string neo4j_elevation  
    string neo4j_longitude  
    string neo4j_geonameid  
    string neo4j_timezone  
    string neo4j_latitude  
    string neo4j_admin1_code  
    string neo4j_modification_date  
    string neo4j_name  
    string neo4j_admin2_code  
    string neo4j_country_code  
    string neo4j_admin3_code  
    string neo4j_uuid  
    string neo4j_population  
    string neo4j_admin4_code  
    string neo4j_feature_code  
}
HttpsClimatepub4kg.github.ioOntology#ObservationalDataset {
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#OceanCirculation {
    string neo4j_name  
    string neo4j_added_from_paper_id  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Paper {
    string neo4j_title  
    string neo4j_name  
    string neo4j_uuid  
    string neo4j_id  
}
HttpsClimatepub4kg.github.ioOntology#PhysicalFeature {
    string neo4j_name  
    string neo4j_added_from_paper_id  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#PhysicalScheme {
    string neo4j_name  
    string neo4j_added_from_paper_id  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Platform {
    string neo4j_name  
    string neo4j_added_from_paper_id  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Problem {
    string neo4j_name  
    string neo4j_paper_id  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Project {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#RCM {
    string neo4j_names  
    string neo4j_rcm_version  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Realm {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Resolution {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Result {
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#SimulationType {
    string neo4j_name  
    string neo4j_added_from_paper_id  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Source {
    string neo4j_names  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#SourceComponent {
    string neo4j_name  
    string neo4j_uuid  
    string neo4j_added_from_paper_id  
}
HttpsClimatepub4kg.github.ioOntology#SourceType {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#SubExperiment {
    string neo4j_name  
    string neo4j_names  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Task {
    string neo4j_name  
    string neo4j_uuid  
    string neo4j_paper_id  
}
HttpsClimatepub4kg.github.ioOntology#Teleconnection {
    string neo4j_name  
    string neo4j_added_from_paper_id  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Variable {
    string neo4j_names  
    string neo4j_variable_long_name  
    string neo4j_name  
    string neo4j_cf_standard_name  
    string neo4j_uuid  
    string neo4j_variable_units  
}
HttpsClimatepub4kg.github.ioOntology#WaterBodies {
    string neo4j_north  
    string neo4j_south  
    string neo4j_name  
    string neo4j_west  
    string neo4j_uuid  
    string neo4j_Name  
    string neo4j_geonameid  
    string neo4j_east  
}
HttpsClimatepub4kg.github.ioOntology#WeatherEvent {
    string neo4j_name  
    string neo4j_added_from_paper_id  
    string neo4j_uuid  
}
Neo4jActivity {

}
Neo4jCity {

}
Neo4jContinent {

}
Neo4jCountry {

}
Neo4jCountrySubdivision {

}
Neo4jDomain {

}
Neo4jEnsemble {

}
Neo4jExperiment {

}
Neo4jExperimentFamily {

}
Neo4jField {

}
Neo4jForcing {

}
Neo4jFrequency {

}
Neo4jGridLabel {

}
Neo4jInnovation {

}
Neo4jInstitute {

}
Neo4jInstrument {

}
Neo4jKeyword {

}
Neo4jMIPEra {

}
Neo4jMember {

}
Neo4jMethod {

}
Neo4jMetric {

}
Neo4jModel {

}
Neo4jNaturalHazardType {

}
Neo4jNaturalHazard {

}
Neo4jNoCountryRegion {

}
Neo4jObservationalDataset {

}
Neo4jOceanCirculation {

}
Neo4jPaper {

}
Neo4jPhysicalFeature {

}
Neo4jPhysicalScheme {

}
Neo4jPlatform {

}
Neo4jProblem {

}
Neo4jProject {

}
Neo4jRCM {

}
Neo4jRealm {

}
Neo4jResolution {

}
Neo4jResult {

}
Neo4jSimulationType {

}
Neo4jSource {

}
Neo4jSourceComponent {

}
Neo4jSourceType {

}
Neo4jSubExperiment {

}
Neo4jTask {

}
Neo4jTeleconnection {

}
Neo4jVariable {

}
Neo4jWaterBodies {

}
Neo4jWeatherEvent {

}
Neo4jGraphConfig {

}
Neo4jMapDef {

}
Neo4jMapNs {

}
Neo4jNsPrefDef {

}

HttpsClimatepub4kg.github.ioOntology#Activity ||--|o HttpsClimatepub4kg.github.ioOntology#Realm : "https___climatepub4kg.github.io_ontology#FOCUSES_ON_REALM"
HttpsClimatepub4kg.github.ioOntology#Activity ||--|o HttpsClimatepub4kg.github.ioOntology#Project : "https___climatepub4kg.github.io_ontology#PART_OF_PROJECT"
HttpsClimatepub4kg.github.ioOntology#City ||--|o HttpsClimatepub4kg.github.ioOntology#Country : "https___climatepub4kg.github.io_ontology#IN_COUNTRY"
HttpsClimatepub4kg.github.ioOntology#Country ||--|o HttpsClimatepub4kg.github.ioOntology#Continent : "https___climatepub4kg.github.io_ontology#IN_CONTINENT"
HttpsClimatepub4kg.github.ioOntology#CountrySubdivision ||--|o HttpsClimatepub4kg.github.ioOntology#Country : "https___climatepub4kg.github.io_ontology#IN_COUNTRY"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#Resolution : "https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#Project : "https___climatepub4kg.github.io_ontology#PART_OF_PROJECT"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#SubExperiment : "https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#Forcing : "https___climatepub4kg.github.io_ontology#USES_FORCING"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#Realm : "https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#Ensemble : "https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#Institute : "https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE"
HttpsClimatepub4kg.github.ioOntology#ExperimentFamily ||--|o HttpsClimatepub4kg.github.ioOntology#Experiment : "https___climatepub4kg.github.io_ontology#INCLUDES_EXPERIMENT"
HttpsClimatepub4kg.github.ioOntology#Institute ||--|o HttpsClimatepub4kg.github.ioOntology#Project : "https___climatepub4kg.github.io_ontology#PARTICIPATED_IN"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#Task : "https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#Innovation : "https___climatepub4kg.github.io_ontology#METHOD_HAS_INNOVATION"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#ObservationalDataset : "https___climatepub4kg.github.io_ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#Problem : "https___climatepub4kg.github.io_ontology#METHOD_SOLVES_PROBLEM"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#METHOD_USES_METRIC"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#Result : "https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#Model : "https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL"
HttpsClimatepub4kg.github.ioOntology#Model ||--|o HttpsClimatepub4kg.github.ioOntology#ObservationalDataset : "https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET"
HttpsClimatepub4kg.github.ioOntology#Model ||--|o HttpsClimatepub4kg.github.ioOntology#Problem : "https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM"
HttpsClimatepub4kg.github.ioOntology#Model ||--|o HttpsClimatepub4kg.github.ioOntology#Task : "https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK"
HttpsClimatepub4kg.github.ioOntology#Model ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC"
HttpsClimatepub4kg.github.ioOntology#Model ||--|o HttpsClimatepub4kg.github.ioOntology#Result : "https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT"
HttpsClimatepub4kg.github.ioOntology#Model ||--|o HttpsClimatepub4kg.github.ioOntology#Source : "https___climatepub4kg.github.io_ontology#CORRESPONDS_TO"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Innovation : "https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Field : "https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Method : "https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Task : "https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#ObservationalDataset : "https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Teleconnection : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#SourceComponent : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Realm : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Resolution : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Project : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Continent : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Experiment : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Source : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#WaterBodies : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Platform : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#SimulationType : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Activity : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#NaturalHazard : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#ExperimentFamily : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Variable : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#WeatherEvent : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#City : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#SourceType : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#PhysicalFeature : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#NoCountryRegion : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#MIPEra : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Institute : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#PhysicalScheme : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Instrument : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Member : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#OceanCirculation : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Country : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Problem : "https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Model : "https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Result : "https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Keyword : "https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD"
HttpsClimatepub4kg.github.ioOntology#Project ||--|o HttpsClimatepub4kg.github.ioOntology#Domain : "https___climatepub4kg.github.io_ontology#COVERS_DOMAIN"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Project : "https___climatepub4kg.github.io_ontology#PART_OF_PROJECT"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Domain : "https___climatepub4kg.github.io_ontology#COVERS_DOMAIN"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#WaterBodies : "https___climatepub4kg.github.io_ontology#COVERS_REGION"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#NoCountryRegion : "https___climatepub4kg.github.io_ontology#COVERS_REGION"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#City : "https___climatepub4kg.github.io_ontology#COVERS_REGION"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Country : "https___climatepub4kg.github.io_ontology#COVERS_REGION"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Continent : "https___climatepub4kg.github.io_ontology#COVERS_REGION"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : "https___climatepub4kg.github.io_ontology#COVERS_REGION"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Source : "https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Variable : "https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Experiment : "https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT"
HttpsClimatepub4kg.github.ioOntology#Result ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#SimulationType : "https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#HAS_METRIC"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Member : "https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Frequency : "https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Activity : "https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#MIPEra : "https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#SourceType : "https___climatepub4kg.github.io_ontology#IS_OF_TYPE"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Resolution : "https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Project : "https___climatepub4kg.github.io_ontology#PART_OF_PROJECT"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#SourceComponent : "https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Institute : "https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#PhysicalFeature : "https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Experiment : "https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Realm : "https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#PhysicalScheme : "https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Ensemble : "https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Source : "https___climatepub4kg.github.io_ontology#INHERITED_FROM"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Variable : "https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Source : "https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#SourceComponent : "https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION"
HttpsClimatepub4kg.github.ioOntology#SourceComponent ||--|o HttpsClimatepub4kg.github.ioOntology#Realm : "https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM"
HttpsClimatepub4kg.github.ioOntology#SourceComponent ||--|o HttpsClimatepub4kg.github.ioOntology#Variable : "https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE"
HttpsClimatepub4kg.github.ioOntology#SourceComponent ||--|o HttpsClimatepub4kg.github.ioOntology#Source : "https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION"
HttpsClimatepub4kg.github.ioOntology#SourceComponent ||--|o HttpsClimatepub4kg.github.ioOntology#SourceComponent : "https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION"
HttpsClimatepub4kg.github.ioOntology#SourceComponent ||--|o HttpsClimatepub4kg.github.ioOntology#SourceComponent : "https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT"
HttpsClimatepub4kg.github.ioOntology#Task ||--|o HttpsClimatepub4kg.github.ioOntology#Problem : "https___climatepub4kg.github.io_ontology#TASK_FACES_PROBLEM"
HttpsClimatepub4kg.github.ioOntology#Task ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#TASK_USES_METRIC"
HttpsClimatepub4kg.github.ioOntology#Task ||--|o HttpsClimatepub4kg.github.ioOntology#ObservationalDataset : "https___climatepub4kg.github.io_ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET"
HttpsClimatepub4kg.github.ioOntology#Variable ||--|o HttpsClimatepub4kg.github.ioOntology#Resolution : "https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION"

```



## Imports


* okns:extended_types
* linkml:types



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#Activity](classes/HttpsClimatepub4kg.github.ioOntology#Activity.md) | None<br/>| 26 | 
| [HttpsClimatepub4kg.github.ioOntology#City](classes/HttpsClimatepub4kg.github.ioOntology#City.md) | None<br/>| 30062 | 
| [HttpsClimatepub4kg.github.ioOntology#Continent](classes/HttpsClimatepub4kg.github.ioOntology#Continent.md) | None<br/>| 7 | 
| [HttpsClimatepub4kg.github.ioOntology#Country](classes/HttpsClimatepub4kg.github.ioOntology#Country.md) | None<br/>| 252 | 
| [HttpsClimatepub4kg.github.ioOntology#CountrySubdivision](classes/HttpsClimatepub4kg.github.ioOntology#CountrySubdivision.md) | None<br/>| 3893 | 
| [HttpsClimatepub4kg.github.ioOntology#Domain](classes/HttpsClimatepub4kg.github.ioOntology#Domain.md) | None<br/>| 39 | 
| [HttpsClimatepub4kg.github.ioOntology#Ensemble](classes/HttpsClimatepub4kg.github.ioOntology#Ensemble.md) | None<br/>| 552 | 
| [HttpsClimatepub4kg.github.ioOntology#Experiment](classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) | None<br/>| 481 | 
| [HttpsClimatepub4kg.github.ioOntology#ExperimentFamily](classes/HttpsClimatepub4kg.github.ioOntology#ExperimentFamily.md) | None<br/>| 9 | 
| [HttpsClimatepub4kg.github.ioOntology#Field](classes/HttpsClimatepub4kg.github.ioOntology#Field.md) | None<br/>| 15 | 
| [HttpsClimatepub4kg.github.ioOntology#Forcing](classes/HttpsClimatepub4kg.github.ioOntology#Forcing.md) | None<br/>| 204 | 
| [HttpsClimatepub4kg.github.ioOntology#Frequency](classes/HttpsClimatepub4kg.github.ioOntology#Frequency.md) | None<br/>| 16 | 
| [HttpsClimatepub4kg.github.ioOntology#Innovation](classes/HttpsClimatepub4kg.github.ioOntology#Innovation.md) | None<br/>| 38 | 
| [HttpsClimatepub4kg.github.ioOntology#Institute](classes/HttpsClimatepub4kg.github.ioOntology#Institute.md) | None<br/>| 132 | 
| [HttpsClimatepub4kg.github.ioOntology#Instrument](classes/HttpsClimatepub4kg.github.ioOntology#Instrument.md) | None<br/>| 49 | 
| [HttpsClimatepub4kg.github.ioOntology#Keyword](classes/HttpsClimatepub4kg.github.ioOntology#Keyword.md) | None<br/>| 85 | 
| [HttpsClimatepub4kg.github.ioOntology#Member](classes/HttpsClimatepub4kg.github.ioOntology#Member.md) | None<br/>| 5929 | 
| [HttpsClimatepub4kg.github.ioOntology#Method](classes/HttpsClimatepub4kg.github.ioOntology#Method.md) | None<br/>| 38 | 
| [HttpsClimatepub4kg.github.ioOntology#Metric](classes/HttpsClimatepub4kg.github.ioOntology#Metric.md) | None<br/>| 699 | 
| [HttpsClimatepub4kg.github.ioOntology#MIPEra](classes/HttpsClimatepub4kg.github.ioOntology#MIPEra.md) | None<br/>| 4 | 
| [HttpsClimatepub4kg.github.ioOntology#Model](classes/HttpsClimatepub4kg.github.ioOntology#Model.md) | None<br/>| 37 | 
| [HttpsClimatepub4kg.github.ioOntology#NaturalHazard](classes/HttpsClimatepub4kg.github.ioOntology#NaturalHazard.md) | None<br/>| 16 | 
| [HttpsClimatepub4kg.github.ioOntology#NoCountryRegion](classes/HttpsClimatepub4kg.github.ioOntology#NoCountryRegion.md) | None<br/>| 6722 | 
| [HttpsClimatepub4kg.github.ioOntology#ObservationalDataset](classes/HttpsClimatepub4kg.github.ioOntology#ObservationalDataset.md) | None<br/>| 99 | 
| [HttpsClimatepub4kg.github.ioOntology#OceanCirculation](classes/HttpsClimatepub4kg.github.ioOntology#OceanCirculation.md) | None<br/>| 113 | 
| [HttpsClimatepub4kg.github.ioOntology#Paper](classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | None<br/>| 38 | 
| [HttpsClimatepub4kg.github.ioOntology#PhysicalFeature](classes/HttpsClimatepub4kg.github.ioOntology#PhysicalFeature.md) | None<br/>| 281 | 
| [HttpsClimatepub4kg.github.ioOntology#PhysicalScheme](classes/HttpsClimatepub4kg.github.ioOntology#PhysicalScheme.md) | None<br/>| 700 | 
| [HttpsClimatepub4kg.github.ioOntology#Platform](classes/HttpsClimatepub4kg.github.ioOntology#Platform.md) | None<br/>| 27 | 
| [HttpsClimatepub4kg.github.ioOntology#Problem](classes/HttpsClimatepub4kg.github.ioOntology#Problem.md) | None<br/>| 38 | 
| [HttpsClimatepub4kg.github.ioOntology#Project](classes/HttpsClimatepub4kg.github.ioOntology#Project.md) | None<br/>| 33 | 
| [HttpsClimatepub4kg.github.ioOntology#RCM](classes/HttpsClimatepub4kg.github.ioOntology#RCM.md) | None<br/>| 42 | 
| [HttpsClimatepub4kg.github.ioOntology#Realm](classes/HttpsClimatepub4kg.github.ioOntology#Realm.md) | None<br/>| 14 | 
| [HttpsClimatepub4kg.github.ioOntology#Resolution](classes/HttpsClimatepub4kg.github.ioOntology#Resolution.md) | None<br/>| 15 | 
| [HttpsClimatepub4kg.github.ioOntology#Result](classes/HttpsClimatepub4kg.github.ioOntology#Result.md) | None<br/>| 607 | 
| [HttpsClimatepub4kg.github.ioOntology#SimulationType](classes/HttpsClimatepub4kg.github.ioOntology#SimulationType.md) | None<br/>| 76 | 
| [HttpsClimatepub4kg.github.ioOntology#Source](classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | None<br/>| 394 | 
| [HttpsClimatepub4kg.github.ioOntology#SourceComponent](classes/HttpsClimatepub4kg.github.ioOntology#SourceComponent.md) | None<br/>| 559 | 
| [HttpsClimatepub4kg.github.ioOntology#SourceType](classes/HttpsClimatepub4kg.github.ioOntology#SourceType.md) | None<br/>| 16 | 
| [HttpsClimatepub4kg.github.ioOntology#SubExperiment](classes/HttpsClimatepub4kg.github.ioOntology#SubExperiment.md) | None<br/>| 63 | 
| [HttpsClimatepub4kg.github.ioOntology#Task](classes/HttpsClimatepub4kg.github.ioOntology#Task.md) | None<br/>| 38 | 
| [HttpsClimatepub4kg.github.ioOntology#Teleconnection](classes/HttpsClimatepub4kg.github.ioOntology#Teleconnection.md) | None<br/>| 121 | 
| [HttpsClimatepub4kg.github.ioOntology#Variable](classes/HttpsClimatepub4kg.github.ioOntology#Variable.md) | None<br/>| 2907 | 
| [HttpsClimatepub4kg.github.ioOntology#WaterBodies](classes/HttpsClimatepub4kg.github.ioOntology#WaterBodies.md) | None<br/>| 123 | 
| [HttpsClimatepub4kg.github.ioOntology#WeatherEvent](classes/HttpsClimatepub4kg.github.ioOntology#WeatherEvent.md) | None<br/>| 100 | 
| [Neo4jGraphConfig](classes/Neo4jGraphConfig.md) | None<br/>|  | 
| [Neo4jMapDef](classes/Neo4jMapDef.md) | None<br/>|  | 
| [Neo4jMapNs](classes/Neo4jMapNs.md) | None<br/>|  | 
| [Neo4jNsPrefDef](classes/Neo4jNsPrefDef.md) | None<br/>|  | 
| [Neo4jActivity](classes/Neo4jActivity.md) | None<br/>|  | 
| [Neo4jCity](classes/Neo4jCity.md) | None<br/>|  | 
| [Neo4jContinent](classes/Neo4jContinent.md) | None<br/>|  | 
| [Neo4jCountry](classes/Neo4jCountry.md) | None<br/>|  | 
| [Neo4jCountrySubdivision](classes/Neo4jCountrySubdivision.md) | None<br/>|  | 
| [Neo4jDomain](classes/Neo4jDomain.md) | None<br/>|  | 
| [Neo4jEnsemble](classes/Neo4jEnsemble.md) | None<br/>|  | 
| [Neo4jExperiment](classes/Neo4jExperiment.md) | None<br/>|  | 
| [Neo4jExperimentFamily](classes/Neo4jExperimentFamily.md) | None<br/>|  | 
| [Neo4jField](classes/Neo4jField.md) | None<br/>|  | 
| [Neo4jForcing](classes/Neo4jForcing.md) | None<br/>|  | 
| [Neo4jFrequency](classes/Neo4jFrequency.md) | None<br/>|  | 
| [Neo4jGridLabel](classes/Neo4jGridLabel.md) | None<br/>|  | 
| [Neo4jInnovation](classes/Neo4jInnovation.md) | None<br/>|  | 
| [Neo4jInstitute](classes/Neo4jInstitute.md) | None<br/>|  | 
| [Neo4jInstrument](classes/Neo4jInstrument.md) | None<br/>|  | 
| [Neo4jKeyword](classes/Neo4jKeyword.md) | None<br/>|  | 
| [Neo4jMember](classes/Neo4jMember.md) | None<br/>|  | 
| [Neo4jMethod](classes/Neo4jMethod.md) | None<br/>|  | 
| [Neo4jMetric](classes/Neo4jMetric.md) | None<br/>|  | 
| [Neo4jMIPEra](classes/Neo4jMIPEra.md) | None<br/>|  | 
| [Neo4jModel](classes/Neo4jModel.md) | None<br/>|  | 
| [Neo4jNaturalHazard](classes/Neo4jNaturalHazard.md) | None<br/>|  | 
| [Neo4jNaturalHazardType](classes/Neo4jNaturalHazardType.md) | None<br/>|  | 
| [Neo4jNoCountryRegion](classes/Neo4jNoCountryRegion.md) | None<br/>|  | 
| [Neo4jObservationalDataset](classes/Neo4jObservationalDataset.md) | None<br/>|  | 
| [Neo4jOceanCirculation](classes/Neo4jOceanCirculation.md) | None<br/>|  | 
| [Neo4jPaper](classes/Neo4jPaper.md) | None<br/>|  | 
| [Neo4jPhysicalFeature](classes/Neo4jPhysicalFeature.md) | None<br/>|  | 
| [Neo4jPhysicalScheme](classes/Neo4jPhysicalScheme.md) | None<br/>|  | 
| [Neo4jPlatform](classes/Neo4jPlatform.md) | None<br/>|  | 
| [Neo4jProblem](classes/Neo4jProblem.md) | None<br/>|  | 
| [Neo4jProject](classes/Neo4jProject.md) | None<br/>|  | 
| [Neo4jRCM](classes/Neo4jRCM.md) | None<br/>|  | 
| [Neo4jRealm](classes/Neo4jRealm.md) | None<br/>|  | 
| [Neo4jResolution](classes/Neo4jResolution.md) | None<br/>|  | 
| [Neo4jResult](classes/Neo4jResult.md) | None<br/>|  | 
| [Neo4jSimulationType](classes/Neo4jSimulationType.md) | None<br/>|  | 
| [Neo4jSource](classes/Neo4jSource.md) | None<br/>|  | 
| [Neo4jSourceComponent](classes/Neo4jSourceComponent.md) | None<br/>|  | 
| [Neo4jSourceType](classes/Neo4jSourceType.md) | None<br/>|  | 
| [Neo4jSubExperiment](classes/Neo4jSubExperiment.md) | None<br/>|  | 
| [Neo4jTask](classes/Neo4jTask.md) | None<br/>|  | 
| [Neo4jTeleconnection](classes/Neo4jTeleconnection.md) | None<br/>|  | 
| [Neo4jVariable](classes/Neo4jVariable.md) | None<br/>|  | 
| [Neo4jWaterBodies](classes/Neo4jWaterBodies.md) | None<br/>|  | 
| [Neo4jWeatherEvent](classes/Neo4jWeatherEvent.md) | None<br/>|  | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM](slots/https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM.md) | <br/>| 3820 |
| [https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER](slots/https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER.md) | <br/>| 11903 |
| [https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA](slots/https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA.md) | <br/>| 318 |
| [https___climatepub4kg.github.io_ontology#CORRESPONDS_TO](slots/https___climatepub4kg.github.io_ontology#CORRESPONDS_TO.md) | <br/>| 15 |
| [https___climatepub4kg.github.io_ontology#COVERS_DOMAIN](slots/https___climatepub4kg.github.io_ontology#COVERS_DOMAIN.md) | <br/>| 125 |
| [https___climatepub4kg.github.io_ontology#COVERS_REGION](slots/https___climatepub4kg.github.io_ontology#COVERS_REGION.md) | <br/>| 397621 |
| [https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE](slots/https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE.md) | <br/>| 139 |
| [https___climatepub4kg.github.io_ontology#FOCUSES_ON_REALM](slots/https___climatepub4kg.github.io_ontology#FOCUSES_ON_REALM.md) | <br/>| 170 |
| [https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY](slots/https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY.md) | <br/>| 623 |
| [https___climatepub4kg.github.io_ontology#HAS_METRIC](slots/https___climatepub4kg.github.io_ontology#HAS_METRIC.md) | <br/>| 49 |
| [https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE](slots/https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE.md) | <br/>| 43 |
| [https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE](slots/https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE.md) | <br/>| 37 |
| [https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT](slots/https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT.md) | <br/>| 504 |
| [https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION](slots/https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION.md) | <br/>| 6708 |
| [https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT](slots/https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT.md) | <br/>| 72 |
| [https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION](slots/https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION.md) | <br/>| 44 |
| [https___climatepub4kg.github.io_ontology#IN_CONTINENT](slots/https___climatepub4kg.github.io_ontology#IN_CONTINENT.md) | <br/>| 210 |
| [https___climatepub4kg.github.io_ontology#IN_COUNTRY](slots/https___climatepub4kg.github.io_ontology#IN_COUNTRY.md) | <br/>| 33923 |
| [https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER](slots/https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER.md) | <br/>| 3069 |
| [https___climatepub4kg.github.io_ontology#INCLUDES_EXPERIMENT](slots/https___climatepub4kg.github.io_ontology#INCLUDES_EXPERIMENT.md) | <br/>| 328 |
| [https___climatepub4kg.github.io_ontology#INHERITED_FROM](slots/https___climatepub4kg.github.io_ontology#INHERITED_FROM.md) | <br/>| 2 |
| [https___climatepub4kg.github.io_ontology#IS_OF_TYPE](slots/https___climatepub4kg.github.io_ontology#IS_OF_TYPE.md) | <br/>| 295 |
| [https___climatepub4kg.github.io_ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](slots/https___climatepub4kg.github.io_ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | <br/>| 127 |
| [https___climatepub4kg.github.io_ontology#METHOD_HAS_INNOVATION](slots/https___climatepub4kg.github.io_ontology#METHOD_HAS_INNOVATION.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT](slots/https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT.md) | <br/>| 669 |
| [https___climatepub4kg.github.io_ontology#METHOD_SOLVES_PROBLEM](slots/https___climatepub4kg.github.io_ontology#METHOD_SOLVES_PROBLEM.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#METHOD_USES_METRIC](slots/https___climatepub4kg.github.io_ontology#METHOD_USES_METRIC.md) | <br/>| 438 |
| [https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL](slots/https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK](slots/https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](slots/https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | <br/>| 127 |
| [https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT](slots/https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT.md) | <br/>| 669 |
| [https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM](slots/https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC](slots/https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC.md) | <br/>| 438 |
| [https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK](slots/https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD](slots/https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD](slots/https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](slots/https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | <br/>| 127 |
| [https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION](slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD](slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD.md) | <br/>| 176 |
| [https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL](slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT](slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT.md) | <br/>| 669 |
| [https___climatepub4kg.github.io_ontology#PAPER_MENTIONS](slots/https___climatepub4kg.github.io_ontology#PAPER_MENTIONS.md) | <br/>| 4462 |
| [https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM](slots/https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC](slots/https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC.md) | <br/>| 438 |
| [https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK](slots/https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE](slots/https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE.md) | <br/>| 53 |
| [https___climatepub4kg.github.io_ontology#PART_OF_PROJECT](slots/https___climatepub4kg.github.io_ontology#PART_OF_PROJECT.md) | <br/>| 1048 |
| [https___climatepub4kg.github.io_ontology#PARTICIPATED_IN](slots/https___climatepub4kg.github.io_ontology#PARTICIPATED_IN.md) | <br/>| 213 |
| [https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE](slots/https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE.md) | <br/>| 2762 |
| [https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE](slots/https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE.md) | <br/>| 503 |
| [https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE](slots/https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE.md) | <br/>| 30757 |
| [https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC](slots/https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC.md) | <br/>| 724 |
| [https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY](slots/https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY.md) | <br/>| 828 |
| [https___climatepub4kg.github.io_ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](slots/https___climatepub4kg.github.io_ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | <br/>| 127 |
| [https___climatepub4kg.github.io_ontology#TASK_FACES_PROBLEM](slots/https___climatepub4kg.github.io_ontology#TASK_FACES_PROBLEM.md) | <br/>| 38 |
| [https___climatepub4kg.github.io_ontology#TASK_USES_METRIC](slots/https___climatepub4kg.github.io_ontology#TASK_USES_METRIC.md) | <br/>| 438 |
| [https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT](slots/https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT.md) | <br/>| 2019 |
| [https___climatepub4kg.github.io_ontology#USES_FORCING](slots/https___climatepub4kg.github.io_ontology#USES_FORCING.md) | <br/>| 986 |
| [https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME](slots/https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME.md) | <br/>| 89 |
| [neo4j__applyNeo4jNaming](slots/neo4j__applyNeo4jNaming.md) | <br/>|  |
| [neo4j__classLabel](slots/neo4j__classLabel.md) | <br/>|  |
| [neo4j__classNamePropName](slots/neo4j__classNamePropName.md) | <br/>|  |
| [neo4j__dataTypePropertyLabel](slots/neo4j__dataTypePropertyLabel.md) | <br/>|  |
| [neo4j__domainRel](slots/neo4j__domainRel.md) | <br/>|  |
| [neo4j__handleMultival](slots/neo4j__handleMultival.md) | <br/>|  |
| [neo4j__handleRDFTypes](slots/neo4j__handleRDFTypes.md) | <br/>|  |
| [neo4j__handleVocabUris](slots/neo4j__handleVocabUris.md) | <br/>|  |
| [neo4j__IN](slots/neo4j__IN.md) | <br/>|  |
| [neo4j__keepCustomDataTypes](slots/neo4j__keepCustomDataTypes.md) | <br/>|  |
| [neo4j__keepLangTag](slots/neo4j__keepLangTag.md) | <br/>|  |
| [neo4j__key](slots/neo4j__key.md) | <br/>|  |
| [neo4j__local](slots/neo4j__local.md) | <br/>|  |
| [neo4j__ns](slots/neo4j__ns.md) | <br/>|  |
| [neo4j__objectPropertyLabel](slots/neo4j__objectPropertyLabel.md) | <br/>|  |
| [neo4j__prefix](slots/neo4j__prefix.md) | <br/>|  |
| [neo4j__rangeRel](slots/neo4j__rangeRel.md) | <br/>|  |
| [neo4j__relNamePropName](slots/neo4j__relNamePropName.md) | <br/>|  |
| [neo4j__subClassOfRel](slots/neo4j__subClassOfRel.md) | <br/>|  |
| [neo4j__subPropertyOfRel](slots/neo4j__subPropertyOfRel.md) | <br/>|  |
| [neo4j_added_from_paper_id](slots/neo4j_added_from_paper_id.md) | <br/>| 2204 |
| [neo4j_admin1_code](slots/neo4j_admin1_code.md) | <br/>| 36784 |
| [neo4j_admin2_code](slots/neo4j_admin2_code.md) | <br/>| 36784 |
| [neo4j_admin3_code](slots/neo4j_admin3_code.md) | <br/>| 36784 |
| [neo4j_admin4_code](slots/neo4j_admin4_code.md) | <br/>| 36784 |
| [neo4j_alternatenames](slots/neo4j_alternatenames.md) | <br/>| 36784 |
| [neo4j_APPLIES_TO_REALM](slots/neo4j_APPLIES_TO_REALM.md) | <br/>|  |
| [neo4j_area_sqkm](slots/neo4j_area_sqkm.md) | <br/>| 252 |
| [neo4j_asciiname](slots/neo4j_asciiname.md) | <br/>| 40677 |
| [neo4j_ASSOCIATED_WITH_MEMBER](slots/neo4j_ASSOCIATED_WITH_MEMBER.md) | <br/>|  |
| [neo4j_BELONGS_TO_MIP_ERA](slots/neo4j_BELONGS_TO_MIP_ERA.md) | <br/>|  |
| [neo4j_capital](slots/neo4j_capital.md) | <br/>| 252 |
| [neo4j_cc2](slots/neo4j_cc2.md) | <br/>| 36784 |
| [neo4j_cf_standard_name](slots/neo4j_cf_standard_name.md) | <br/>| 2401 |
| [neo4j_climid](slots/neo4j_climid.md) | <br/>|  |
| [neo4j_clm](slots/neo4j_clm.md) | <br/>|  |
| [neo4j_code](slots/neo4j_code.md) | <br/>| 3893 |
| [neo4j_continent](slots/neo4j_continent.md) | <br/>| 252 |
| [neo4j_CORRESPONDS_TO](slots/neo4j_CORRESPONDS_TO.md) | <br/>|  |
| [neo4j_country](slots/neo4j_country.md) | <br/>| 252 |
| [neo4j_country_code](slots/neo4j_country_code.md) | <br/>| 36784 |
| [neo4j_COVERS_DOMAIN](slots/neo4j_COVERS_DOMAIN.md) | <br/>|  |
| [neo4j_COVERS_REGION](slots/neo4j_COVERS_REGION.md) | <br/>|  |
| [neo4j_currencycode](slots/neo4j_currencycode.md) | <br/>| 252 |
| [neo4j_currencyname](slots/neo4j_currencyname.md) | <br/>| 252 |
| [neo4j_dem](slots/neo4j_dem.md) | <br/>| 36784 |
| [neo4j_DRIVEN_BY_SOURCE](slots/neo4j_DRIVEN_BY_SOURCE.md) | <br/>|  |
| [neo4j_east](slots/neo4j_east.md) | <br/>| 4268 |
| [neo4j_elevation](slots/neo4j_elevation.md) | <br/>| 36784 |
| [neo4j_equivalent_fips_code](slots/neo4j_equivalent_fips_code.md) | <br/>| 252 |
| [neo4j_experiment_title](slots/neo4j_experiment_title.md) | <br/>| 261 |
| [neo4j_feature_class](slots/neo4j_feature_class.md) | <br/>| 36784 |
| [neo4j_feature_code](slots/neo4j_feature_code.md) | <br/>| 36784 |
| [neo4j_fips](slots/neo4j_fips.md) | <br/>| 252 |
| [neo4j_FOCUSES_ON_REALM](slots/neo4j_FOCUSES_ON_REALM.md) | <br/>|  |
| [neo4j_GENERATED_BY_ACTIVITY](slots/neo4j_GENERATED_BY_ACTIVITY.md) | <br/>|  |
| [neo4j_geonameid](slots/neo4j_geonameid.md) | <br/>| 41059 |
| [neo4j_HAS_METRIC](slots/neo4j_HAS_METRIC.md) | <br/>|  |
| [neo4j_HAS_PHYSICAL_FEATURE](slots/neo4j_HAS_PHYSICAL_FEATURE.md) | <br/>|  |
| [neo4j_HAS_SIMULATION_TYPE](slots/neo4j_HAS_SIMULATION_TYPE.md) | <br/>|  |
| [neo4j_HAS_SOURCE_COMPONENT](slots/neo4j_HAS_SOURCE_COMPONENT.md) | <br/>|  |
| [neo4j_HAS_SPATIAL_RESOLUTION](slots/neo4j_HAS_SPATIAL_RESOLUTION.md) | <br/>|  |
| [neo4j_HAS_SUB_EXPERIMENT](slots/neo4j_HAS_SUB_EXPERIMENT.md) | <br/>|  |
| [neo4j_HAS_SUBSEQUENT_VERSION](slots/neo4j_HAS_SUBSEQUENT_VERSION.md) | <br/>|  |
| [neo4j_id](slots/neo4j_id.md) | <br/>| 38 |
| [neo4j_IN_CONTINENT](slots/neo4j_IN_CONTINENT.md) | <br/>|  |
| [neo4j_IN_COUNTRY](slots/neo4j_IN_COUNTRY.md) | <br/>|  |
| [neo4j_INCLUDES_ENSEMBLE_MEMBER](slots/neo4j_INCLUDES_ENSEMBLE_MEMBER.md) | <br/>|  |
| [neo4j_INCLUDES_EXPERIMENT](slots/neo4j_INCLUDES_EXPERIMENT.md) | <br/>|  |
| [neo4j_INHERITED_FROM](slots/neo4j_INHERITED_FROM.md) | <br/>|  |
| [neo4j_IS_OF_TYPE](slots/neo4j_IS_OF_TYPE.md) | <br/>|  |
| [neo4j_iso](slots/neo4j_iso.md) | <br/>| 259 |
| [neo4j_iso3](slots/neo4j_iso3.md) | <br/>| 252 |
| [neo4j_isonumeric](slots/neo4j_isonumeric.md) | <br/>| 252 |
| [neo4j_languages](slots/neo4j_languages.md) | <br/>| 252 |
| [neo4j_latitude](slots/neo4j_latitude.md) | <br/>| 36784 |
| [neo4j_longitude](slots/neo4j_longitude.md) | <br/>| 36784 |
| [neo4j_METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](slots/neo4j_METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | <br/>|  |
| [neo4j_METHOD_HAS_INNOVATION](slots/neo4j_METHOD_HAS_INNOVATION.md) | <br/>|  |
| [neo4j_METHOD_HAS_RESULT](slots/neo4j_METHOD_HAS_RESULT.md) | <br/>|  |
| [neo4j_METHOD_SOLVES_PROBLEM](slots/neo4j_METHOD_SOLVES_PROBLEM.md) | <br/>|  |
| [neo4j_METHOD_USES_METRIC](slots/neo4j_METHOD_USES_METRIC.md) | <br/>|  |
| [neo4j_METHOD_USES_MODEL](slots/neo4j_METHOD_USES_MODEL.md) | <br/>|  |
| [neo4j_METHOD_WORKS_ON_TASK](slots/neo4j_METHOD_WORKS_ON_TASK.md) | <br/>|  |
| [neo4j_MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](slots/neo4j_MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | <br/>|  |
| [neo4j_MODEL_HAS_RESULT](slots/neo4j_MODEL_HAS_RESULT.md) | <br/>|  |
| [neo4j_MODEL_SOLVES_PROBLEM](slots/neo4j_MODEL_SOLVES_PROBLEM.md) | <br/>|  |
| [neo4j_MODEL_USES_METRIC](slots/neo4j_MODEL_USES_METRIC.md) | <br/>|  |
| [neo4j_MODEL_WORKS_FOR_TASK](slots/neo4j_MODEL_WORKS_FOR_TASK.md) | <br/>|  |
| [neo4j_modification_date](slots/neo4j_modification_date.md) | <br/>| 36784 |
| [neo4j_Name](slots/neo4j_Name.md) | <br/>| 123 |
| [neo4j_name](slots/neo4j_name.md) | <br/>| 55709 |
| [neo4j_names](slots/neo4j_names.md) | <br/>| 10876 |
| [neo4j_neighbours](slots/neo4j_neighbours.md) | <br/>| 252 |
| [neo4j_north](slots/neo4j_north.md) | <br/>| 4268 |
| [neo4j_PAPER_APPLIES_METHOD](slots/neo4j_PAPER_APPLIES_METHOD.md) | <br/>|  |
| [neo4j_PAPER_BELONGS_TO_FIELD](slots/neo4j_PAPER_BELONGS_TO_FIELD.md) | <br/>|  |
| [neo4j_PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](slots/neo4j_PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | <br/>|  |
| [neo4j_PAPER_HAS_INNOVATION](slots/neo4j_PAPER_HAS_INNOVATION.md) | <br/>|  |
| [neo4j_PAPER_HAS_KEYWORD](slots/neo4j_PAPER_HAS_KEYWORD.md) | <br/>|  |
| [neo4j_PAPER_HAS_MODEL](slots/neo4j_PAPER_HAS_MODEL.md) | <br/>|  |
| [neo4j_PAPER_HAS_RESULT](slots/neo4j_PAPER_HAS_RESULT.md) | <br/>|  |
| [neo4j_paper_id](slots/neo4j_paper_id.md) | <br/>| 204 |
| [neo4j_PAPER_MENTIONS](slots/neo4j_PAPER_MENTIONS.md) | <br/>|  |
| [neo4j_PAPER_SOLVES_PROBLEM](slots/neo4j_PAPER_SOLVES_PROBLEM.md) | <br/>|  |
| [neo4j_PAPER_USES_METRIC](slots/neo4j_PAPER_USES_METRIC.md) | <br/>|  |
| [neo4j_PAPER_WORKS_ON_TASK](slots/neo4j_PAPER_WORKS_ON_TASK.md) | <br/>|  |
| [neo4j_PART_OF_ENSEMBLE](slots/neo4j_PART_OF_ENSEMBLE.md) | <br/>|  |
| [neo4j_PART_OF_PROJECT](slots/neo4j_PART_OF_PROJECT.md) | <br/>|  |
| [neo4j_PARTICIPATED_IN](slots/neo4j_PARTICIPATED_IN.md) | <br/>|  |
| [neo4j_PERFORMED_BY_INSTITUTE](slots/neo4j_PERFORMED_BY_INSTITUTE.md) | <br/>|  |
| [neo4j_phone](slots/neo4j_phone.md) | <br/>| 252 |
| [neo4j_population](slots/neo4j_population.md) | <br/>| 37036 |
| [neo4j_postal_code_format](slots/neo4j_postal_code_format.md) | <br/>| 252 |
| [neo4j_postal_code_regex](slots/neo4j_postal_code_regex.md) | <br/>| 252 |
| [neo4j_PRODUCED_BY_INSTITUTE](slots/neo4j_PRODUCED_BY_INSTITUTE.md) | <br/>|  |
| [neo4j_PRODUCES_VARIABLE](slots/neo4j_PRODUCES_VARIABLE.md) | <br/>|  |
| [neo4j_rcm_version](slots/neo4j_rcm_version.md) | <br/>| 42 |
| [neo4j_RESULT_HAS_METRIC](slots/neo4j_RESULT_HAS_METRIC.md) | <br/>|  |
| [neo4j_SAMPLED_AT_FREQUENCY](slots/neo4j_SAMPLED_AT_FREQUENCY.md) | <br/>|  |
| [neo4j_south](slots/neo4j_south.md) | <br/>| 4268 |
| [neo4j_TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](slots/neo4j_TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | <br/>|  |
| [neo4j_TASK_FACES_PROBLEM](slots/neo4j_TASK_FACES_PROBLEM.md) | <br/>|  |
| [neo4j_TASK_USES_METRIC](slots/neo4j_TASK_USES_METRIC.md) | <br/>|  |
| [neo4j_timezone](slots/neo4j_timezone.md) | <br/>| 36784 |
| [neo4j_title](slots/neo4j_title.md) | <br/>| 38 |
| [neo4j_tld](slots/neo4j_tld.md) | <br/>| 252 |
| [neo4j_USED_IN_EXPERIMENT](slots/neo4j_USED_IN_EXPERIMENT.md) | <br/>|  |
| [neo4j_USES_FORCING](slots/neo4j_USES_FORCING.md) | <br/>|  |
| [neo4j_USES_PHYSICAL_SCHEME](slots/neo4j_USES_PHYSICAL_SCHEME.md) | <br/>|  |
| [neo4j_uuid](slots/neo4j_uuid.md) | <br/>| 55709 |
| [neo4j_variable_long_name](slots/neo4j_variable_long_name.md) | <br/>| 2899 |
| [neo4j_variable_units](slots/neo4j_variable_units.md) | <br/>| 2906 |
| [neo4j_west](slots/neo4j_west.md) | <br/>| 4268 |









## IRI prefixes

* linkml: https://w3id.org/linkml/
* neo4j: neo4j://graph.schema#
* okn: https://purl.org/okn/
* okns: https://purl.org/okn/schema/
* owl: http://www.w3.org/2002/07/owl#
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
* schema: http://schema.org/
