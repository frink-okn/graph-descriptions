# nasa-gesdisc-kg

No schema description specified



## Schema Diagram

```mermaid
erDiagram
HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter {
    string https___nasa_gesdisc.proto_okn.net_kg_schema_globalId  
    string dct_subject  
    string rdfs_label  
    uri https___nasa_gesdisc.proto_okn.net_kg_schema_url  
}
HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset {
    string https___nasa_gesdisc.proto_okn.net_kg_schema_globalId  
    decimal https___nasa_gesdisc.proto_okn.net_kg_schema_nwCorner_latitude  
    string dct_subject  
    decimal https___nasa_gesdisc.proto_okn.net_kg_schema_nwCorner_longitude  
    float https___nasa_gesdisc.proto_okn.net_kg_schema_pagerank_publication_dataset  
    string https___nasa_gesdisc.proto_okn.net_kg_schema_seCorner_crs  
    string https___nasa_gesdisc.proto_okn.net_kg_schema_temporalFrequency  
    string https___nasa_gesdisc.proto_okn.net_kg_schema_nwCorner_crs  
    string https___nasa_gesdisc.proto_okn.net_kg_schema_cmrId  
    string https___nasa_gesdisc.proto_okn.net_kg_schema_daac  
    string schema_abstract  
    string rdfs_label  
    uri https___nasa_gesdisc.proto_okn.net_kg_schema_landingPageUrl  
    decimal https___nasa_gesdisc.proto_okn.net_kg_schema_seCorner_longitude  
    string dct_identifier  
    decimal https___nasa_gesdisc.proto_okn.net_kg_schema_seCorner_latitude  
    datetime dct_date  
}
HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument {
    string dct_subject  
    string https___nasa_gesdisc.proto_okn.net_kg_schema_globalId  
    string rdfs_label  
}
HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform {
    string https___nasa_gesdisc.proto_okn.net_kg_schema_globalId  
    string dct_subject  
    string rdfs_label  
    string https___nasa_gesdisc.proto_okn.net_kg_schema_Type  
}
HttpsNasa-gesdisc.proto-okn.netKgSchemaProject {
    string dct_subject  
    string https___nasa_gesdisc.proto_okn.net_kg_schema_globalId  
    string rdfs_label  
}
HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication {
    string https___nasa_gesdisc.proto_okn.net_kg_schema_globalId  
    float https___nasa_gesdisc.proto_okn.net_kg_schema_pagerank_publication_dataset  
    string schema_abstract  
    string dct_identifier  
    integer http___www.w3.org_2006_time#year  
    string schema_title  
}
HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword {
    string rdfs_label  
    string https___nasa_gesdisc.proto_okn.net_kg_schema_globalId  
}
RdfStatement {
    uri rdf_predicate  
}

HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset : "https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_DATASET"
HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaProject : "https___nasa-gesdisc.proto-okn.net_kg_schema_OF_PROJECT"
HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : "https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_PLATFORM"
HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword : "https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_SCIENCEKEYWORD"
HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument : "https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_INSTRUMENT"
HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword : "https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA"
HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : "https___nasa-gesdisc.proto-okn.net_kg_schema_CITES"
HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset : "https___nasa-gesdisc.proto-okn.net_kg_schema_USES_DATASET"
HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword : "https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_SUBCATEGORY"
RdfStatement ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : "rdf_subject"
RdfStatement ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword : "rdf_subject"
RdfStatement ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset : "rdf_subject"
RdfStatement ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter : "rdf_subject"
RdfStatement ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : "rdf_subject"
RdfStatement ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument : "rdf_object"
RdfStatement ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaProject : "rdf_object"
RdfStatement ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : "rdf_object"
RdfStatement ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword : "rdf_object"
RdfStatement ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset : "rdf_object"
RdfStatement ||--|o HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : "rdf_object"

```



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter](classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter.md) | No class (type) description specified<br/>| 197 | 
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset](classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset.md) | No class (type) description specified<br/>| 6821 | 
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument](classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument.md) | No class (type) description specified<br/>| 897 | 
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform](classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform.md) | No class (type) description specified<br/>| 451 | 
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaProject](classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaProject.md) | No class (type) description specified<br/>| 351 | 
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication](classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication.md) | No class (type) description specified<br/>| 135352 | 
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword](classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword.md) | No class (type) description specified<br/>| 1609 | 
| [RdfStatement](classes/RdfStatement.md) | No class (type) description specified<br/>| 406515 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [dct_date](slots/dct_date.md) | No slot (predicate) description specified<br/>| 10817 |
| [dct_identifier](slots/dct_identifier.md) | No slot (predicate) description specified<br/>| 142173 |
| [dct_subject](slots/dct_subject.md) | No slot (predicate) description specified<br/>| 8521 |
| [http___www.w3.org_2006_time#year](slots/http___www.w3.org_2006_time#year.md) | No slot (predicate) description specified<br/>| 135348 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_CITES](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_CITES.md) | No slot (predicate) description specified<br/>| 208429 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_cmrId](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_cmrId.md) | No slot (predicate) description specified<br/>| 6821 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_daac](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_daac.md) | No slot (predicate) description specified<br/>| 6821 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_globalId](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_globalId.md) | No slot (predicate) description specified<br/>| 145678 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA.md) | No slot (predicate) description specified<br/>| 119695 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_DATASET](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_DATASET.md) | No slot (predicate) description specified<br/>| 9834 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_INSTRUMENT](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_INSTRUMENT.md) | No slot (predicate) description specified<br/>| 2526 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_PLATFORM](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_PLATFORM.md) | No slot (predicate) description specified<br/>| 10398 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_SCIENCEKEYWORD](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_SCIENCEKEYWORD.md) | No slot (predicate) description specified<br/>| 21571 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_SUBCATEGORY](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_SUBCATEGORY.md) | No slot (predicate) description specified<br/>| 1823 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_landingPageUrl](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_landingPageUrl.md) | No slot (predicate) description specified<br/>| 3190 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_nwCorner_crs](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_nwCorner_crs.md) | No slot (predicate) description specified<br/>| 5721 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_nwCorner_latitude](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_nwCorner_latitude.md) | No slot (predicate) description specified<br/>| 5721 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_nwCorner_longitude](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_nwCorner_longitude.md) | No slot (predicate) description specified<br/>| 5721 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_OF_PROJECT](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_OF_PROJECT.md) | No slot (predicate) description specified<br/>| 6378 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_pagerank_publication_dataset](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_pagerank_publication_dataset.md) | No slot (predicate) description specified<br/>| 142173 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_seCorner_crs](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_seCorner_crs.md) | No slot (predicate) description specified<br/>| 5721 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_seCorner_latitude](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_seCorner_latitude.md) | No slot (predicate) description specified<br/>| 5721 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_seCorner_longitude](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_seCorner_longitude.md) | No slot (predicate) description specified<br/>| 5721 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_temporalFrequency](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_temporalFrequency.md) | No slot (predicate) description specified<br/>| 6821 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_Type](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_Type.md) | No slot (predicate) description specified<br/>| 444 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_url](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_url.md) | No slot (predicate) description specified<br/>| 197 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_USES_DATASET](slots/https___nasa_gesdisc.proto_okn.net_kg_schema_USES_DATASET.md) | No slot (predicate) description specified<br/>| 25861 |
| [rdf_object](slots/rdf_object.md) | No slot (predicate) description specified<br/>| 406515 |
| [rdf_predicate](slots/rdf_predicate.md) | No slot (predicate) description specified<br/>| 406515 |
| [rdf_subject](slots/rdf_subject.md) | No slot (predicate) description specified<br/>| 406515 |
| [rdfs_label](slots/rdfs_label.md) | No slot (predicate) description specified<br/>| 10326 |
| [schema_abstract](slots/schema_abstract.md) | An abstract is a short description that summarizes a [[CreativeWork]]<br/>| 141462 |
| [schema_title](slots/schema_title.md) | The title of the job<br/>| 135343 |









## IRI prefixes

* dct: http://purl.org/dc/terms/
* linkml: https://w3id.org/linkml/
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* schema: https://schema.org/
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
