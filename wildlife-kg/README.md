# wildlifekn

No schema description specified



## Schema Diagram

```mermaid
erDiagram
HttpsWildlife.proto-okn.netKgSchemaAmphibianName {
    string rdfs_label  
}
HttpsWildlife.proto-okn.netKgSchemaBirdName {
    string rdfs_label  
}
HttpsWildlife.proto-okn.netKgSchemaLocation {
    string rdfs_label  
}
RdfStatement {
    uri schema_subjectOf  
    datetime dct_date  
    date dct_date  
    integer https___wildlife.proto_okn.net_kg_schema_observed_times  
    uri rdf_predicate  
}

HttpsWildlife.proto-okn.netKgSchemaAmphibianName ||--|o HttpsWildlife.proto-okn.netKgSchemaLocation : "https___wildlife.proto-okn.net_kg_schema_OBSERVED_AT"
HttpsWildlife.proto-okn.netKgSchemaBirdName ||--|o HttpsWildlife.proto-okn.netKgSchemaLocation : "https___wildlife.proto-okn.net_kg_schema_OBSERVED_AT"
RdfStatement ||--|o HttpsWildlife.proto-okn.netKgSchemaBirdName : "rdf_subject"
RdfStatement ||--|o HttpsWildlife.proto-okn.netKgSchemaAmphibianName : "rdf_subject"
RdfStatement ||--|o HttpsWildlife.proto-okn.netKgSchemaLocation : "rdf_object"

```



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [HttpsWildlife.proto-okn.netKgSchemaAmphibianName](classes/HttpsWildlife.proto-okn.netKgSchemaAmphibianName.md) | No class (type) description specified<br/>| 97 | 
| [HttpsWildlife.proto-okn.netKgSchemaBirdName](classes/HttpsWildlife.proto-okn.netKgSchemaBirdName.md) | No class (type) description specified<br/>| 303 | 
| [HttpsWildlife.proto-okn.netKgSchemaLocation](classes/HttpsWildlife.proto-okn.netKgSchemaLocation.md) | No class (type) description specified<br/>| 657 | 
| [RdfStatement](classes/RdfStatement.md) | No class (type) description specified<br/>| 5205 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [dct_date](slots/dct_date.md) | No slot (predicate) description specified<br/>| 5205 |
| [https___wildlife.proto_okn.net_kg_schema_OBSERVED_AT](slots/https___wildlife.proto_okn.net_kg_schema_OBSERVED_AT.md) | No slot (predicate) description specified<br/>| 5205 |
| [https___wildlife.proto_okn.net_kg_schema_observed_times](slots/https___wildlife.proto_okn.net_kg_schema_observed_times.md) | No slot (predicate) description specified<br/>| 5205 |
| [rdf_object](slots/rdf_object.md) | No slot (predicate) description specified<br/>| 5205 |
| [rdf_predicate](slots/rdf_predicate.md) | No slot (predicate) description specified<br/>| 5205 |
| [rdf_subject](slots/rdf_subject.md) | No slot (predicate) description specified<br/>| 5205 |
| [rdfs_label](slots/rdfs_label.md) | No slot (predicate) description specified<br/>| 1057 |
| [schema_subjectOf](slots/schema_subjectOf.md) | A CreativeWork or Event about this Thing<br/>| 5205 |









## IRI prefixes

* dct: http://purl.org/dc/terms/
* linkml: https://w3id.org/linkml/
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* schema: https://schema.org/
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
