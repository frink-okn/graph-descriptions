# climatemodelskg





## Schema Diagram

```mermaid
erDiagram
HttpsClimatepub4kg.github.ioOntology#Activity {
    string neo4j_uuid  
    string neo4j_names  
    string neo4j_name  
}
HttpsClimatepub4kg.github.ioOntology#City {
    string neo4j_longitude  
    string neo4j_asciiname  
    string neo4j_population  
    string neo4j_elevation  
    string neo4j_dem  
    string neo4j_alternatenames  
    string neo4j_modification_date  
    string neo4j_country_code  
    string neo4j_latitude  
    string neo4j_admin2_code  
    string neo4j_timezone  
    string neo4j_feature_class  
    string neo4j_feature_code  
    string neo4j_uuid  
    string neo4j_admin3_code  
    string neo4j_admin1_code  
    string neo4j_admin4_code  
    string neo4j_geonameid  
    string neo4j_name  
    string neo4j_cc2  
}
HttpsClimatepub4kg.github.ioOntology#Continent {
    string neo4j_uuid  
    string neo4j_iso  
    string neo4j_name  
    string neo4j_geonameid  
}
HttpsClimatepub4kg.github.ioOntology#Country {
    string neo4j_population  
    string neo4j_postal_code_format  
    string neo4j_currencyname  
    string neo4j_neighbours  
    string neo4j_languages  
    string neo4j_tld  
    string neo4j_east  
    string neo4j_isonumeric  
    string neo4j_phone  
    string neo4j_south  
    string neo4j_west  
    string neo4j_north  
    string neo4j_equivalent_fips_code  
    string neo4j_area_sqkm  
    string neo4j_iso3  
    string neo4j_iso  
    string neo4j_uuid  
    string neo4j_currencycode  
    string neo4j_postal_code_regex  
    string neo4j_continent  
    string neo4j_geonameid  
    string neo4j_capital  
    string neo4j_name  
    string neo4j_fips  
    string neo4j_country  
}
HttpsClimatepub4kg.github.ioOntology#CountrySubdivision {
    string neo4j_east  
    string neo4j_asciiname  
    string neo4j_south  
    string neo4j_geonameid  
    string neo4j_code  
    string neo4j_west  
    string neo4j_name  
    string neo4j_uuid  
    string neo4j_north  
}
HttpsClimatepub4kg.github.ioOntology#Domain {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#Ensemble {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#Experiment {
    string neo4j_experiment_title  
    string neo4j_names  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#ExperimentFamily {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#Field {
    string neo4j_paper_id  
    string neo4j_uuid  
    string neo4j_name  
}
HttpsClimatepub4kg.github.ioOntology#Forcing {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#Frequency {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#Innovation {
    string neo4j_paper_id  
    string neo4j_uuid  
    string neo4j_name  
}
HttpsClimatepub4kg.github.ioOntology#Institute {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#Instrument {
    string neo4j_added_from_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Keyword {
    string neo4j_uuid  
    string neo4j_name  
}
HttpsClimatepub4kg.github.ioOntology#MIPEra {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#Member {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#Method {
    string neo4j_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Metric {
    string neo4j_uuid  
    string neo4j_added_from_paper_id  
    string neo4j_name  
}
HttpsClimatepub4kg.github.ioOntology#Model {
    string neo4j_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#NaturalHazard {
    string neo4j_added_from_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#NoCountryRegion {
    string neo4j_longitude  
    string neo4j_asciiname  
    string neo4j_population  
    string neo4j_elevation  
    string neo4j_dem  
    string neo4j_alternatenames  
    string neo4j_modification_date  
    string neo4j_country_code  
    string neo4j_latitude  
    string neo4j_admin2_code  
    string neo4j_timezone  
    string neo4j_feature_class  
    string neo4j_feature_code  
    string neo4j_uuid  
    string neo4j_admin3_code  
    string neo4j_admin1_code  
    string neo4j_admin4_code  
    string neo4j_geonameid  
    string neo4j_name  
    string neo4j_cc2  
}
HttpsClimatepub4kg.github.ioOntology#ObservationalDataset {
    string neo4j_uuid  
    string neo4j_name  
}
HttpsClimatepub4kg.github.ioOntology#OceanCirculation {
    string neo4j_added_from_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Paper {
    string neo4j_id  
    string neo4j_title  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#PhysicalFeature {
    string neo4j_added_from_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#PhysicalScheme {
    string neo4j_added_from_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Platform {
    string neo4j_added_from_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Problem {
    string neo4j_paper_id  
    string neo4j_uuid  
    string neo4j_name  
}
HttpsClimatepub4kg.github.ioOntology#Project {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#RCM {
    string neo4j_names  
    string neo4j_rcm_version  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Realm {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#Resolution {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#Result {
    string neo4j_uuid  
    string neo4j_name  
}
HttpsClimatepub4kg.github.ioOntology#SimulationType {
    string neo4j_added_from_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Source {
    string neo4j_names  
    string neo4j_uuid  
    string neo4j_name  
}
HttpsClimatepub4kg.github.ioOntology#SourceComponent {
    string neo4j_added_from_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#SourceType {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#SubExperiment {
    string neo4j_uuid  
    string neo4j_name  
    string neo4j_names  
}
HttpsClimatepub4kg.github.ioOntology#Task {
    string neo4j_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Teleconnection {
    string neo4j_added_from_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#Variable {
    string neo4j_names  
    string neo4j_cf_standard_name  
    string neo4j_variable_units  
    string neo4j_name  
    string neo4j_variable_long_name  
    string neo4j_uuid  
}
HttpsClimatepub4kg.github.ioOntology#WaterBodies {
    string neo4j_east  
    string neo4j_south  
    string neo4j_geonameid  
    string neo4j_west  
    string neo4j_name  
    string neo4j_uuid  
    string neo4j_Name  
    string neo4j_north  
}
HttpsClimatepub4kg.github.ioOntology#WeatherEvent {
    string neo4j_added_from_paper_id  
    string neo4j_name  
    string neo4j_uuid  
}

HttpsClimatepub4kg.github.ioOntology#Activity ||--|o HttpsClimatepub4kg.github.ioOntology#Project : "https___climatepub4kg.github.io_ontology#PART_OF_PROJECT"
HttpsClimatepub4kg.github.ioOntology#Activity ||--|o HttpsClimatepub4kg.github.ioOntology#Realm : "https___climatepub4kg.github.io_ontology#FOCUSES_ON_REALM"
HttpsClimatepub4kg.github.ioOntology#City ||--|o HttpsClimatepub4kg.github.ioOntology#Country : "https___climatepub4kg.github.io_ontology#IN_COUNTRY"
HttpsClimatepub4kg.github.ioOntology#Country ||--|o HttpsClimatepub4kg.github.ioOntology#Continent : "https___climatepub4kg.github.io_ontology#IN_CONTINENT"
HttpsClimatepub4kg.github.ioOntology#CountrySubdivision ||--|o HttpsClimatepub4kg.github.ioOntology#Country : "https___climatepub4kg.github.io_ontology#IN_COUNTRY"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#Forcing : "https___climatepub4kg.github.io_ontology#USES_FORCING"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#Institute : "https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#SubExperiment : "https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#Project : "https___climatepub4kg.github.io_ontology#PART_OF_PROJECT"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#Resolution : "https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#Ensemble : "https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER"
HttpsClimatepub4kg.github.ioOntology#Experiment ||--|o HttpsClimatepub4kg.github.ioOntology#Realm : "https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM"
HttpsClimatepub4kg.github.ioOntology#ExperimentFamily ||--|o HttpsClimatepub4kg.github.ioOntology#Experiment : "https___climatepub4kg.github.io_ontology#INCLUDES_EXPERIMENT"
HttpsClimatepub4kg.github.ioOntology#Institute ||--|o HttpsClimatepub4kg.github.ioOntology#Project : "https___climatepub4kg.github.io_ontology#PARTICIPATED_IN"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#Innovation : "https___climatepub4kg.github.io_ontology#METHOD_HAS_INNOVATION"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#Problem : "https___climatepub4kg.github.io_ontology#METHOD_SOLVES_PROBLEM"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#Result : "https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#Task : "https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#ObservationalDataset : "https___climatepub4kg.github.io_ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#METHOD_USES_METRIC"
HttpsClimatepub4kg.github.ioOntology#Method ||--|o HttpsClimatepub4kg.github.ioOntology#Model : "https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL"
HttpsClimatepub4kg.github.ioOntology#Model ||--|o HttpsClimatepub4kg.github.ioOntology#Source : "https___climatepub4kg.github.io_ontology#CORRESPONDS_TO"
HttpsClimatepub4kg.github.ioOntology#Model ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC"
HttpsClimatepub4kg.github.ioOntology#Model ||--|o HttpsClimatepub4kg.github.ioOntology#Result : "https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT"
HttpsClimatepub4kg.github.ioOntology#Model ||--|o HttpsClimatepub4kg.github.ioOntology#Task : "https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK"
HttpsClimatepub4kg.github.ioOntology#Model ||--|o HttpsClimatepub4kg.github.ioOntology#ObservationalDataset : "https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET"
HttpsClimatepub4kg.github.ioOntology#Model ||--|o HttpsClimatepub4kg.github.ioOntology#Problem : "https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Innovation : "https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#ObservationalDataset : "https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Method : "https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Result : "https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Problem : "https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Keyword : "https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Field : "https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Model : "https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Instrument : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Platform : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Project : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Member : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#ExperimentFamily : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Institute : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Continent : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Activity : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#PhysicalScheme : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#SourceComponent : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#NoCountryRegion : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Experiment : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Realm : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#MIPEra : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#SourceType : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Teleconnection : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#NaturalHazard : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Resolution : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#OceanCirculation : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#SimulationType : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#WeatherEvent : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#PhysicalFeature : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Country : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#City : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Variable : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Source : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#WaterBodies : "https___climatepub4kg.github.io_ontology#PAPER_MENTIONS"
HttpsClimatepub4kg.github.ioOntology#Paper ||--|o HttpsClimatepub4kg.github.ioOntology#Task : "https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK"
HttpsClimatepub4kg.github.ioOntology#Project ||--|o HttpsClimatepub4kg.github.ioOntology#Domain : "https___climatepub4kg.github.io_ontology#COVERS_DOMAIN"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Variable : "https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Domain : "https___climatepub4kg.github.io_ontology#COVERS_DOMAIN"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Experiment : "https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Source : "https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Project : "https___climatepub4kg.github.io_ontology#PART_OF_PROJECT"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Continent : "https___climatepub4kg.github.io_ontology#COVERS_REGION"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : "https___climatepub4kg.github.io_ontology#COVERS_REGION"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#NoCountryRegion : "https___climatepub4kg.github.io_ontology#COVERS_REGION"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#City : "https___climatepub4kg.github.io_ontology#COVERS_REGION"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#Country : "https___climatepub4kg.github.io_ontology#COVERS_REGION"
HttpsClimatepub4kg.github.ioOntology#RCM ||--|o HttpsClimatepub4kg.github.ioOntology#WaterBodies : "https___climatepub4kg.github.io_ontology#COVERS_REGION"
HttpsClimatepub4kg.github.ioOntology#Result ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#HAS_METRIC"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Institute : "https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Experiment : "https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#SimulationType : "https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Member : "https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Project : "https___climatepub4kg.github.io_ontology#PART_OF_PROJECT"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#PhysicalFeature : "https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Realm : "https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Variable : "https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#PhysicalScheme : "https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Ensemble : "https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#MIPEra : "https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#SourceComponent : "https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Source : "https___climatepub4kg.github.io_ontology#INHERITED_FROM"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Frequency : "https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#SourceComponent : "https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Source : "https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#SourceType : "https___climatepub4kg.github.io_ontology#IS_OF_TYPE"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Activity : "https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY"
HttpsClimatepub4kg.github.ioOntology#Source ||--|o HttpsClimatepub4kg.github.ioOntology#Resolution : "https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION"
HttpsClimatepub4kg.github.ioOntology#SourceComponent ||--|o HttpsClimatepub4kg.github.ioOntology#Variable : "https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE"
HttpsClimatepub4kg.github.ioOntology#SourceComponent ||--|o HttpsClimatepub4kg.github.ioOntology#SourceComponent : "https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION"
HttpsClimatepub4kg.github.ioOntology#SourceComponent ||--|o HttpsClimatepub4kg.github.ioOntology#Source : "https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION"
HttpsClimatepub4kg.github.ioOntology#SourceComponent ||--|o HttpsClimatepub4kg.github.ioOntology#SourceComponent : "https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT"
HttpsClimatepub4kg.github.ioOntology#SourceComponent ||--|o HttpsClimatepub4kg.github.ioOntology#Realm : "https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM"
HttpsClimatepub4kg.github.ioOntology#Task ||--|o HttpsClimatepub4kg.github.ioOntology#Problem : "https___climatepub4kg.github.io_ontology#TASK_FACES_PROBLEM"
HttpsClimatepub4kg.github.ioOntology#Task ||--|o HttpsClimatepub4kg.github.ioOntology#ObservationalDataset : "https___climatepub4kg.github.io_ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET"
HttpsClimatepub4kg.github.ioOntology#Task ||--|o HttpsClimatepub4kg.github.ioOntology#Metric : "https___climatepub4kg.github.io_ontology#TASK_USES_METRIC"
HttpsClimatepub4kg.github.ioOntology#Variable ||--|o HttpsClimatepub4kg.github.ioOntology#Resolution : "https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION"

```



## Imports


* linkml:types
* okns:extended_types



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
| [neo4j_added_from_paper_id](slots/neo4j_added_from_paper_id.md) | <br/>| 2204 |
| [neo4j_admin1_code](slots/neo4j_admin1_code.md) | <br/>| 36784 |
| [neo4j_admin2_code](slots/neo4j_admin2_code.md) | <br/>| 36784 |
| [neo4j_admin3_code](slots/neo4j_admin3_code.md) | <br/>| 36784 |
| [neo4j_admin4_code](slots/neo4j_admin4_code.md) | <br/>| 36784 |
| [neo4j_alternatenames](slots/neo4j_alternatenames.md) | <br/>| 36784 |
| [neo4j_area_sqkm](slots/neo4j_area_sqkm.md) | <br/>| 252 |
| [neo4j_asciiname](slots/neo4j_asciiname.md) | <br/>| 40677 |
| [neo4j_capital](slots/neo4j_capital.md) | <br/>| 252 |
| [neo4j_cc2](slots/neo4j_cc2.md) | <br/>| 36784 |
| [neo4j_cf_standard_name](slots/neo4j_cf_standard_name.md) | <br/>| 2401 |
| [neo4j_code](slots/neo4j_code.md) | <br/>| 3893 |
| [neo4j_continent](slots/neo4j_continent.md) | <br/>| 252 |
| [neo4j_country](slots/neo4j_country.md) | <br/>| 252 |
| [neo4j_country_code](slots/neo4j_country_code.md) | <br/>| 36784 |
| [neo4j_currencycode](slots/neo4j_currencycode.md) | <br/>| 252 |
| [neo4j_currencyname](slots/neo4j_currencyname.md) | <br/>| 252 |
| [neo4j_dem](slots/neo4j_dem.md) | <br/>| 36784 |
| [neo4j_east](slots/neo4j_east.md) | <br/>| 4268 |
| [neo4j_elevation](slots/neo4j_elevation.md) | <br/>| 36784 |
| [neo4j_equivalent_fips_code](slots/neo4j_equivalent_fips_code.md) | <br/>| 252 |
| [neo4j_experiment_title](slots/neo4j_experiment_title.md) | <br/>| 261 |
| [neo4j_feature_class](slots/neo4j_feature_class.md) | <br/>| 36784 |
| [neo4j_feature_code](slots/neo4j_feature_code.md) | <br/>| 36784 |
| [neo4j_fips](slots/neo4j_fips.md) | <br/>| 252 |
| [neo4j_geonameid](slots/neo4j_geonameid.md) | <br/>| 41059 |
| [neo4j_id](slots/neo4j_id.md) | <br/>| 38 |
| [neo4j_iso](slots/neo4j_iso.md) | <br/>| 259 |
| [neo4j_iso3](slots/neo4j_iso3.md) | <br/>| 252 |
| [neo4j_isonumeric](slots/neo4j_isonumeric.md) | <br/>| 252 |
| [neo4j_languages](slots/neo4j_languages.md) | <br/>| 252 |
| [neo4j_latitude](slots/neo4j_latitude.md) | <br/>| 36784 |
| [neo4j_longitude](slots/neo4j_longitude.md) | <br/>| 36784 |
| [neo4j_modification_date](slots/neo4j_modification_date.md) | <br/>| 36784 |
| [neo4j_Name](slots/neo4j_Name.md) | <br/>| 123 |
| [neo4j_name](slots/neo4j_name.md) | <br/>| 55709 |
| [neo4j_names](slots/neo4j_names.md) | <br/>| 10876 |
| [neo4j_neighbours](slots/neo4j_neighbours.md) | <br/>| 252 |
| [neo4j_north](slots/neo4j_north.md) | <br/>| 4268 |
| [neo4j_paper_id](slots/neo4j_paper_id.md) | <br/>| 204 |
| [neo4j_phone](slots/neo4j_phone.md) | <br/>| 252 |
| [neo4j_population](slots/neo4j_population.md) | <br/>| 37036 |
| [neo4j_postal_code_format](slots/neo4j_postal_code_format.md) | <br/>| 252 |
| [neo4j_postal_code_regex](slots/neo4j_postal_code_regex.md) | <br/>| 252 |
| [neo4j_rcm_version](slots/neo4j_rcm_version.md) | <br/>| 42 |
| [neo4j_south](slots/neo4j_south.md) | <br/>| 4268 |
| [neo4j_timezone](slots/neo4j_timezone.md) | <br/>| 36784 |
| [neo4j_title](slots/neo4j_title.md) | <br/>| 38 |
| [neo4j_tld](slots/neo4j_tld.md) | <br/>| 252 |
| [neo4j_uuid](slots/neo4j_uuid.md) | <br/>| 55709 |
| [neo4j_variable_long_name](slots/neo4j_variable_long_name.md) | <br/>| 2899 |
| [neo4j_variable_units](slots/neo4j_variable_units.md) | <br/>| 2906 |
| [neo4j_west](slots/neo4j_west.md) | <br/>| 4268 |









## IRI prefixes

* linkml: https://w3id.org/linkml/
* neo4j: neo4j://graph.schema#
* okn: https://purl.org/okn/
* okns: https://purl.org/okn/schema/
