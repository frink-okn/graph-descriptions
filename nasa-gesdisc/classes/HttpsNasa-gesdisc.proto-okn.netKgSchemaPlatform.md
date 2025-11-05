

# Class: No class (type) name specified (https___nasa-gesdisc.proto-okn.net_kg_schema_Platform)


_No class (type) description specified_






This class occurs 451 times.


URI: [https://nasa-gesdisc.proto-okn.net/kg/schema/Platform](https://nasa-gesdisc.proto-okn.net/kg/schema/Platform)






```mermaid
 classDiagram
    class HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform
    click HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform href "../HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform"
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : dct_subject
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform --> "0..1" String : dct_subject
    click String href "../String"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : https___nasa_gesdisc.proto_okn.net_kg_schema_globalId
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform --> "0..1" String : https___nasa_gesdisc.proto_okn.net_kg_schema_globalId
    click String href "../String"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_INSTRUMENT
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform --> "0..1" HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument : https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_INSTRUMENT
    click HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument href "../HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : https___nasa_gesdisc.proto_okn.net_kg_schema_Type
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform --> "0..1" String : https___nasa_gesdisc.proto_okn.net_kg_schema_Type
    click String href "../String"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform : rdfs_label
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform --> "0..1" String : rdfs_label
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_globalId](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_globalId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 451 |
| [dct_subject](../slots/dct_subject.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 378 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 451 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_Type](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_Type.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 444 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_INSTRUMENT](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_INSTRUMENT.md) | 0..1 <br/> [HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument.md) | No slot (predicate) description specified <br/>  | direct | 2526 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset.md) | [https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_PLATFORM](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_PLATFORM.md) | range | [HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform.md) |
| [RdfStatement](../classes/RdfStatement.md) | [rdf_subject](../slots/rdf_subject.md) | any_of[range] | [HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform.md) |
| [RdfStatement](../classes/RdfStatement.md) | [rdf_object](../slots/rdf_object.md) | any_of[range] | [HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 451
description: No class (type) description specified
title: No class (type) name specified
from_schema: nasa-gesdisc
rank: 1000
slots:
- https___nasa-gesdisc.proto-okn.net_kg_schema_globalId
- dct_subject
- rdfs_label
- https___nasa-gesdisc.proto-okn.net_kg_schema_Type
- https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_INSTRUMENT
slot_usage:
  dct_subject:
    name: dct_subject
    annotations:
      string:
        tag: string
        value: 378
  https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_INSTRUMENT:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_INSTRUMENT
    annotations:
      https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument:
        tag: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
        value: 2526
  https___nasa-gesdisc.proto-okn.net_kg_schema_Type:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_Type
    annotations:
      string:
        tag: string
        value: 444
  https___nasa-gesdisc.proto-okn.net_kg_schema_globalId:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_globalId
    annotations:
      string:
        tag: string
        value: 451
  rdfs_label:
    name: rdfs_label
    annotations:
      string:
        tag: string
        value: 451
class_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/Platform

```
</details>

### Induced

<details>

```yaml
name: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 451
description: No class (type) description specified
title: No class (type) name specified
from_schema: nasa-gesdisc
rank: 1000
slot_usage:
  dct_subject:
    name: dct_subject
    annotations:
      string:
        tag: string
        value: 378
  https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_INSTRUMENT:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_INSTRUMENT
    annotations:
      https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument:
        tag: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
        value: 2526
  https___nasa-gesdisc.proto-okn.net_kg_schema_Type:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_Type
    annotations:
      string:
        tag: string
        value: 444
  https___nasa-gesdisc.proto-okn.net_kg_schema_globalId:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_globalId
    annotations:
      string:
        tag: string
        value: 451
  rdfs_label:
    name: rdfs_label
    annotations:
      string:
        tag: string
        value: 451
attributes:
  https___nasa-gesdisc.proto-okn.net_kg_schema_globalId:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_globalId
    annotations:
      string:
        tag: string
        value: 451
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: dcf602c1-0e51-55f1-97fb-dbfb8a704c0f
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/0
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - object:
        example_object: dd0ff369-99bb-5ea4-87e8-769ead7dd7c2
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/10000
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    - object:
        example_object: 3133f2fc-268e-50c1-ba3d-ded48c82484b
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/34483
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
    - object:
        example_object: 46b38de5-bd0d-5055-a829-27b9bd736e7a
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/6821
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
    - object:
        example_object: 7540d35b-6334-52e4-a566-a6b56529bef1
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7018
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Project
    - object:
        example_object: 5a0c4d6a-8696-5c21-a821-63301ab32ffa
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7369
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    - object:
        example_object: f4d62d70-809d-5264-97c2-9fee6f7e54c0
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7820
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
    alias: https___nasa_gesdisc.proto_okn.net_kg_schema_globalId
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Project
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    - https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
    range: string
  dct_subject:
    name: dct_subject
    annotations:
      string:
        tag: string
        value: 378
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: ERS-1 Gridded Level 3 Enhanced Resolution Sigma-0 from BYU
        example_object_type: string
        example_predicate: dct:subject
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/0
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - object:
        example_object: N/A
        example_object_type: string
        example_predicate: dct:subject
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/6821
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
    - object:
        example_object: Scatterometry Climate Record Pathfinder
        example_object_type: string
        example_predicate: dct:subject
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7018
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Project
    - object:
        example_object: European Remote Sensing Satellite-1
        example_object_type: string
        example_predicate: dct:subject
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7369
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    - object:
        example_object: Active Microwave Instrument
        example_object_type: string
        example_predicate: dct:subject
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7820
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: dct:subject
    alias: dct_subject
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Project
    range: string
  rdfs_label:
    name: rdfs_label
    annotations:
      string:
        tag: string
        value: 451
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: ERS-1_BYU_L3_OW_SIGMA0_ENHANCED
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/0
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - object:
        example_object: DATA ANALYSIS AND VISUALIZATION
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/34483
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
    - object:
        example_object: BYU/SCP
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/6821
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
    - object:
        example_object: SCP
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7018
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Project
    - object:
        example_object: ERS-1
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7369
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    - object:
        example_object: AMI
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7820
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Project
    - https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
    range: string
  https___nasa-gesdisc.proto-okn.net_kg_schema_Type:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_Type
    annotations:
      string:
        tag: string
        value: 444
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Earth Observation Satellites
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/Type
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7369
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/Type
    alias: https___nasa_gesdisc.proto_okn.net_kg_schema_Type
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    range: string
  https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_INSTRUMENT:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_INSTRUMENT
    annotations:
      https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument:
        tag: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
        value: 2526
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: https://nasa-gesdisc.proto-okn.net/kg/node/7820
        example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/HAS_INSTRUMENT
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7369
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/HAS_INSTRUMENT
    alias: https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_INSTRUMENT
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    range: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
class_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/Platform

```
</details>