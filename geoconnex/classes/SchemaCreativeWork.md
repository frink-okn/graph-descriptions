

# Class: CreativeWork (schema_CreativeWork)


_The most generic kind of creative work, including books, movies, photographs, software programs, etc._





URI: [schema:CreativeWork](https://schema.org/CreativeWork)






```mermaid
 classDiagram
    class SchemaCreativeWork
    click SchemaCreativeWork href "../SchemaCreativeWork"
      SchemaCreativeWork : schema_identifier
        
          
    
    
    SchemaCreativeWork --> "0..1" Any : schema_identifier
    click Any href "../Any"

        
      SchemaCreativeWork : schema_name
        
          
    
    
    SchemaCreativeWork --> "0..1" String : schema_name
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [schema_name](../slots/schema_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 28216 occurrences with subject type schema_Dataset and object type string.<br/>56432 occurrences with subject type schema_DataDownload and object type string.<br/>41703 occurrences with subject type schema_GovernmentOrganization and object type string.<br/>28216 occurrences with subject type schema_PropertyValue and object type string.<br/>45727 occurrences with untyped subjects and object type string.<br/>243268 occurrences with subject type schema_Place and object type string.<br/>201357 occurrences with subject type hyf__HY_HydroLocation and object type string.<br/>2741 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type string.<br/>247 occurrences with subject type schema_Organization and object type string.<br/>165029 occurrences with subject type schema_CreativeWork and object type string. | direct |
| [schema_identifier](../slots/schema_identifier.md) | 0..1 <br/> [xsd:string](xsd:string)&nbsp;or&nbsp;<br />[SchemaPropertyValue](../classes/SchemaPropertyValue.md) | No slot (predicate) description specified <br/> 40988 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type schema_PropertyValue.<br/>247 occurrences with subject type schema_Organization and object type schema_PropertyValue.<br/>165029 occurrences with subject type schema_CreativeWork and object type string.<br/>13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_PropertyValue. | direct |










## Examples

| Value |
| --- |
| https://gleaner.io/xid/genid/cksjodsip8t6t2qulttg |


## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:CreativeWork |
| native | geoconnex/:SchemaCreativeWork |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: schema_CreativeWork
conforms_to: No schema conformance document specified
description: The most generic kind of creative work, including books, movies, photographs,
  software programs, etc.
title: CreativeWork
notes:
- Class with 165029 occurrences.
examples:
- value: https://gleaner.io/xid/genid/cksjodsip8t6t2qulttg
from_schema: geoconnex
rank: 1000
slots:
- schema_name
- schema_identifier
class_uri: schema:CreativeWork

```
</details>

### Induced

<details>
```yaml
name: schema_CreativeWork
conforms_to: No schema conformance document specified
description: The most generic kind of creative work, including books, movies, photographs,
  software programs, etc.
title: CreativeWork
notes:
- Class with 165029 occurrences.
examples:
- value: https://gleaner.io/xid/genid/cksjodsip8t6t2qulttg
from_schema: geoconnex
rank: 1000
attributes:
  schema_name:
    name: schema_name
    description: No slot (predicate) description specified
    comments:
    - 28216 occurrences with subject type schema_Dataset and object type string.
    - 56432 occurrences with subject type schema_DataDownload and object type string.
    - 41703 occurrences with subject type schema_GovernmentOrganization and object
      type string.
    - 28216 occurrences with subject type schema_PropertyValue and object type string.
    - 45727 occurrences with untyped subjects and object type string.
    - 243268 occurrences with subject type schema_Place and object type string.
    - 201357 occurrences with subject type hyf__HY_HydroLocation and object type string.
    - 2741 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
      and object type string.
    - 247 occurrences with subject type schema_Organization and object type string.
    - 165029 occurrences with subject type schema_CreativeWork and object type string.
    examples:
    - description: schema_Dataset → string
      object:
        example_object: USGS-293229091230800
        example_predicate: schema:name
        example_subject: _:b1000000
    - description: schema_DataDownload → string
      object:
        example_object: USGS SensorThings API
        example_predicate: schema:name
        example_subject: _:b1000004
    - description: schema_GovernmentOrganization → string
      object:
        example_object: U.S. Geological Survey Water Data for the Nation
        example_predicate: schema:name
        example_subject: _:b1000006
    - description: schema_PropertyValue → string
      object:
        example_object: Gage height
        example_predicate: schema:name
        example_subject: _:b1000007
    - description: None → string
      object:
        example_object: Mancos River at Anitas Flat Below Mancos CO
        example_predicate: schema:name
        example_subject: _:b1548067
    - description: schema_Place → string
      object:
        example_object: New England Region
        example_predicate: schema:name
        example_subject: https://geoconnex.us/ref/hu02/01
    - description: hyf__HY_HydroLocation → string
      object:
        example_object: BIG CREEK
        example_predicate: schema:name
        example_subject: https://geoconnex.us/iow/demo/AL00017
    - description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
        → string
      object:
        example_object: ALCOVA
        example_predicate: schema:name
        example_subject: https://geoconnex.us/ornl/hydrosource/dams/1
    - description: schema_Organization → string
      object:
        example_object: CUAHSI_CUAHSI_HIS_CRWA_ids__0
        example_predicate: schema:name
        example_subject: https://gleaner.io/id/org/CUAHSI_CUAHSI_HIS_CRWA_ids__0
    - description: schema_CreativeWork → string
      object:
        example_object: HUC12 Pour Points
        example_predicate: schema:name
        example_subject: https://gleaner.io/xid/genid/cksjodsip8t6t2qulttg
    from_schema: geoconnex
    rank: 1000
    slot_uri: schema:name
    alias: schema_name
    owner: schema_CreativeWork
    domain_of:
    - http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    - hyf__HY_HydroLocation
    - schema_CreativeWork
    - schema_DataDownload
    - schema_Dataset
    - schema_GovernmentOrganization
    - schema_Organization
    - schema_Place
    - schema_PropertyValue
    range: string
  schema_identifier:
    name: schema_identifier
    description: No slot (predicate) description specified
    comments:
    - 40988 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
      and object type schema_PropertyValue.
    - 247 occurrences with subject type schema_Organization and object type schema_PropertyValue.
    - 165029 occurrences with subject type schema_CreativeWork and object type string.
    - 13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_PropertyValue.
    examples:
    - description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
        → schema_PropertyValue
      object:
        example_object: https://gleaner.io/xid/genid/ckh8pd4ip8t5ksin207g
        example_predicate: schema:identifier
        example_subject: https://geoconnex.us/ornl/hydrosource/dams/999
    - description: schema_Organization → schema_PropertyValue
      object:
        example_object: https://gleaner.io/genid/geoconnex
        example_predicate: schema:identifier
        example_subject: https://gleaner.io/id/org/wade_wade__9
    - description: schema_CreativeWork → string
      object:
        example_object: huc12pp
        example_predicate: schema:identifier
        example_subject: https://gleaner.io/xid/genid/cksjodsip8t6t2qulttg
    - description: hyf__HY_HydroLocation → schema_PropertyValue
      object:
        example_object: _:b850487
        example_predicate: schema:identifier
        example_subject: https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900'
    from_schema: geoconnex
    rank: 1000
    slot_uri: schema:identifier
    alias: schema_identifier
    owner: schema_CreativeWork
    domain_of:
    - http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    - hyf__HY_HydroLocation
    - schema_CreativeWork
    - schema_Organization
    range: Any
    any_of:
    - range: string
    - range: schema_PropertyValue
class_uri: schema:CreativeWork

```
</details>