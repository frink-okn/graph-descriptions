

# Class: No class (type) name specified (http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation)


_No class (type) description specified_





URI: [http://www.opengeospatial.org/standards/waterml2/hy_features/HY_HydroLocation](http://www.opengeospatial.org/standards/waterml2/hy_features/HY_HydroLocation)






```mermaid
 classDiagram
    class HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation
    click HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation href "../HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation"
      HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation : geo_hasGeometry
        
          
    
    
    HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation --> "0..1" Any : geo_hasGeometry
    click Any href "../Any"

        
      HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation : http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath
        
          
    
    
    HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation --> "0..1" Uri : http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath
    click Uri href "../Uri"

        
      HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation : http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocationType
        
          
    
    
    HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation --> "0..1" Uri : http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocationType
    click Uri href "../Uri"

        
      HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation : hyf_HY_HydroLocationType
        
          
    
    
    HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation --> "0..1" String : hyf_HY_HydroLocationType
    click String href "../String"

        
      HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation : schema_geo
        
          
    
    
    HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation --> "0..1" Any : schema_geo
    click Any href "../Any"

        
      HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation : schema_geoWithin
        
          
    
    
    HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation --> "0..1" Any : schema_geoWithin
    click Any href "../Any"

        
      HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation : schema_identifier
        
          
    
    
    HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation --> "0..1" Any : schema_identifier
    click Any href "../Any"

        
      HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation : schema_name
        
          
    
    
    HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation --> "0..1" String : schema_name
    click String href "../String"

        
      HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation : schema_subjectOf
        
          
    
    
    HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation --> "0..1" Any : schema_subjectOf
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [geo_hasGeometry](../slots/geo_hasGeometry.md) | 0..1 <br/> [Sf#LineString](../classes/Sf#LineString.md)&nbsp;or&nbsp;<br />[Sf#Point](../classes/Sf#Point.md)&nbsp;or&nbsp;<br />[Sf#GeometryCollection](../classes/Sf#GeometryCollection.md)&nbsp;or&nbsp;<br />[Sf#MultiPolygon](../classes/Sf#MultiPolygon.md)&nbsp;or&nbsp;<br />[Sf#Polygon](../classes/Sf#Polygon.md) | No slot (predicate) description specified <br/> 319697 occurrences with subject type schema_Place and object type sf_#MultiPolygon.<br/>101786 occurrences with subject type schema_Place and object type sf_#LineString.<br/>32790 occurrences with subject type schema_Place and object type sf_#Polygon.<br/>200617 occurrences with subject type schema_Place and object type sf_#Point.<br/>387017 occurrences with subject type hyf__HY_HydroLocation and object type sf_#Point.<br/>10247 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type sf_#Point.<br/>5 occurrences with subject type schema_Place and object type sf_#GeometryCollection. | direct |
| [schema_geo](../slots/schema_geo.md) | 0..1 <br/> [SchemaGeoShape](../classes/SchemaGeoShape.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[SchemaGeoCoordinates](../classes/SchemaGeoCoordinates.md) | No slot (predicate) description specified <br/> 427661 occurrences with subject type schema_Place and object type schema_GeoShape.<br/>1944 occurrences with subject type schema_Place and object type uri.<br/>6 occurrences with untyped subjects and object type schema:GeoCoordinates.<br/>200804 occurrences with subject type schema_Place and object type schema_GeoCoordinates.<br/>10247 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type schema_GeoCoordinates.<br/>385003 occurrences with subject type hyf__HY_HydroLocation and object type schema_GeoCoordinates. | direct |
| [schema_name](../slots/schema_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 28216 occurrences with subject type schema_Dataset and object type string.<br/>56432 occurrences with subject type schema_DataDownload and object type string.<br/>41703 occurrences with subject type schema_GovernmentOrganization and object type string.<br/>28216 occurrences with subject type schema_PropertyValue and object type string.<br/>45727 occurrences with untyped subjects and object type string.<br/>243268 occurrences with subject type schema_Place and object type string.<br/>201357 occurrences with subject type hyf__HY_HydroLocation and object type string.<br/>2741 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type string.<br/>247 occurrences with subject type schema_Organization and object type string.<br/>165029 occurrences with subject type schema_CreativeWork and object type string. | direct |
| [http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath](../slots/http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) | No slot (predicate) description specified <br/> 2536 occurrences with subject type schema_Place and object type uri.<br/>3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type uri. | direct |
| [schema_identifier](../slots/schema_identifier.md) | 0..1 <br/> [xsd:string](xsd:string)&nbsp;or&nbsp;<br />[SchemaPropertyValue](../classes/SchemaPropertyValue.md) | No slot (predicate) description specified <br/> 40988 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type schema_PropertyValue.<br/>247 occurrences with subject type schema_Organization and object type schema_PropertyValue.<br/>165029 occurrences with subject type schema_CreativeWork and object type string.<br/>13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_PropertyValue. | direct |
| [schema_geoWithin](../slots/schema_geoWithin.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)&nbsp;or&nbsp;<br />[SchemaPlace](../classes/SchemaPlace.md) | No slot (predicate) description specified <br/> 53554 occurrences with subject type schema_Place and object type schema_Place.<br/>2536 occurrences with subject type schema_Place and object type uri.<br/>2014 occurrences with subject type hyf__HY_HydroLocation and object type string.<br/>3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type schema_Place.<br/>3075 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type uri. | direct |
| [hyf_HY_HydroLocationType](../slots/hyf_HY_HydroLocationType.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 42 occurrences with subject type hyf__HY_HydroLocation and object type string.<br/>1617371 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type string. | direct |
| [schema_subjectOf](../slots/schema_subjectOf.md) | 0..1 <br/> [SchemaDataset](../classes/SchemaDataset.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI) | No slot (predicate) description specified <br/> 78891 occurrences with subject type schema_Place and object type uri.<br/>8804 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type uri.<br/>185645 occurrences with subject type hyf__HY_HydroLocation and object type uri.<br/>28216 occurrences with subject type hyf__HY_HydroLocation and object type schema_Dataset. | direct |
| [http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocationType](../slots/http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocationType.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) | No slot (predicate) description specified <br/> 3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type uri. | direct |









## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://www.opengeospatial.org/standards/waterml2/hy_features/HY_HydroLocation |
| native | geoconnex/:HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 1620787 occurrences.
from_schema: geoconnex
rank: 1000
slots:
- geo_hasGeometry
- schema_geo
- schema_name
- http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath
- schema_identifier
- schema_geoWithin
- hyf_HY_HydroLocationType
- schema_subjectOf
- http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocationType
class_uri: http://www.opengeospatial.org/standards/waterml2/hy_features/HY_HydroLocation

```
</details>

### Induced

<details>
```yaml
name: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 1620787 occurrences.
from_schema: geoconnex
rank: 1000
attributes:
  geo_hasGeometry:
    name: geo_hasGeometry
    description: No slot (predicate) description specified
    comments:
    - 319697 occurrences with subject type schema_Place and object type sf_#MultiPolygon.
    - 101786 occurrences with subject type schema_Place and object type sf_#LineString.
    - 32790 occurrences with subject type schema_Place and object type sf_#Polygon.
    - 200617 occurrences with subject type schema_Place and object type sf_#Point.
    - 387017 occurrences with subject type hyf__HY_HydroLocation and object type sf_#Point.
    - 10247 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
      and object type sf_#Point.
    - 5 occurrences with subject type schema_Place and object type sf_#GeometryCollection.
    examples:
    - description: schema_Place → sf_#MultiPolygon
      object:
        example_object: https://gleaner.io/xid/genid/crht3s93cv0c73e1d15g
        example_predicate: geo:hasGeometry
        example_subject: https://geoconnex.us/ref/ua10/98263
    - description: schema_Place → sf_#LineString
      object:
        example_object: https://gleaner.io/xid/genid/cks4khsip8tc7lvlbq90
        example_predicate: geo:hasGeometry
        example_subject: https://geoconnex.us/ref/mainstems/99895
    - description: schema_Place → sf_#Polygon
      object:
        example_object: _:b783557
        example_predicate: geo:hasGeometry
        example_subject: https://geoconnex.us/ref/pws/WY5680103
    - description: schema_Place → sf_#Point
      object:
        example_object: _:b842331
        example_predicate: geo:hasGeometry
        example_subject: https://sta.geoconnex.dev/collections/WQIE-WQP/Datastreams/items/'007ab627-00bf-f48c-a27c-d1af60f4e3c6'
    - description: hyf__HY_HydroLocation → sf_#Point
      object:
        example_object: _:b850485
        example_predicate: geo:hasGeometry
        example_subject: https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900'
    - description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
        → sf_#Point
      object:
        example_object: https://gleaner.io/xid/genid/ckh8pd4ip8t5ksin2050
        example_predicate: geo:hasGeometry
        example_subject: https://geoconnex.us/ornl/hydrosource/dams/999
    - description: schema_Place → sf_#GeometryCollection
      object:
        example_object: _:b163095
        example_predicate: geo:hasGeometry
        example_subject: https://geoconnex.us/ref/pws/SC0720003
    from_schema: geoconnex
    rank: 1000
    slot_uri: geo:hasGeometry
    alias: geo_hasGeometry
    owner: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    domain_of:
    - http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    - hyf__HY_HydroLocation
    - schema_Place
    range: Any
    any_of:
    - range: sf_#LineString
    - range: sf_#Point
    - range: sf_#GeometryCollection
    - range: sf_#MultiPolygon
    - range: sf_#Polygon
  schema_geo:
    name: schema_geo
    description: No slot (predicate) description specified
    comments:
    - 427661 occurrences with subject type schema_Place and object type schema_GeoShape.
    - 1944 occurrences with subject type schema_Place and object type uri.
    - 6 occurrences with untyped subjects and object type schema:GeoCoordinates.
    - 200804 occurrences with subject type schema_Place and object type schema_GeoCoordinates.
    - 10247 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
      and object type schema_GeoCoordinates.
    - 385003 occurrences with subject type hyf__HY_HydroLocation and object type schema_GeoCoordinates.
    examples:
    - description: schema_Place → schema_GeoShape
      object:
        example_object: https://gleaner.io/xid/genid/crht3s93cv0c73e1d160
        example_predicate: schema:geo
        example_subject: https://geoconnex.us/ref/ua10/98263
    - description: schema_Place → uri
      object:
        example_object: _:b1546204
        example_predicate: schema:geo
        example_subject: https://geoconnex.us/ref/hu02/01
    - description: None → schema_GeoCoordinates
      object:
        example_object: https://gleaner.io/xid/genid/cl2fdb4ip8tadg8qd0u0
        example_predicate: schema:geo
        example_subject: https://gleaner.io/xid/genid/cl2fdb4ip8tadg8qd0ug
    - description: schema_Place → schema_GeoCoordinates
      object:
        example_object: _:b842332
        example_predicate: schema:geo
        example_subject: https://sta.geoconnex.dev/collections/WQIE-WQP/Datastreams/items/'007ab627-00bf-f48c-a27c-d1af60f4e3c6'
    - description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
        → schema_GeoCoordinates
      object:
        example_object: https://gleaner.io/xid/genid/ckh8pd4ip8t5ksin205g
        example_predicate: schema:geo
        example_subject: https://geoconnex.us/ornl/hydrosource/dams/999
    - description: hyf__HY_HydroLocation → schema_GeoCoordinates
      object:
        example_object: _:b850486
        example_predicate: schema:geo
        example_subject: https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900'
    from_schema: geoconnex
    rank: 1000
    slot_uri: schema:geo
    alias: schema_geo
    owner: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    domain_of:
    - http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    - hyf__HY_HydroLocation
    - schema_Place
    range: Any
    any_of:
    - range: schema_GeoShape
    - range: uri
    - range: schema_GeoCoordinates
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
    owner: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
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
  http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath:
    name: http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath
    description: No slot (predicate) description specified
    comments:
    - 2536 occurrences with subject type schema_Place and object type uri.
    - 3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
      and object type uri.
    examples:
    - description: schema_Place → uri
      object:
        example_object: https://geoconnex.us/nhdplusv2/comid/10017314
        example_predicate: http://www.opengeospatial.org/standards/waterml2/hy_features/flowpath
        example_subject: https://geoconnex.us/ca-gage-assessment/gages/09423350
    - description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
        → uri
      object:
        example_object: https://geoconnex.us/nhdplusv2/comid/NA
        example_predicate: http://www.opengeospatial.org/standards/waterml2/hy_features/flowpath
        example_subject: https://geoconnex.us/ornl/hydrosource/dams/1
    from_schema: geoconnex
    rank: 1000
    slot_uri: http://www.opengeospatial.org/standards/waterml2/hy_features/flowpath
    alias: http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath
    owner: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    domain_of:
    - http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    - schema_Place
    range: uri
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
    owner: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    domain_of:
    - http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    - hyf__HY_HydroLocation
    - schema_CreativeWork
    - schema_Organization
    range: Any
    any_of:
    - range: string
    - range: schema_PropertyValue
  schema_geoWithin:
    name: schema_geoWithin
    description: No slot (predicate) description specified
    comments:
    - 53554 occurrences with subject type schema_Place and object type schema_Place.
    - 2536 occurrences with subject type schema_Place and object type uri.
    - 2014 occurrences with subject type hyf__HY_HydroLocation and object type string.
    - 3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
      and object type schema_Place.
    - 3075 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
      and object type uri.
    examples:
    - description: schema_Place → schema_Place
      object:
        example_object: https://geoconnex.us/ref/states/56
        example_predicate: schema:geoWithin
        example_subject: https://geoconnex.us/ref/pws/WY5680122
    - description: schema_Place → uri
      object:
        example_object: https://geoconnex.us/nhdplusv2/huc12/150301020203
        example_predicate: schema:geoWithin
        example_subject: https://geoconnex.us/ca-gage-assessment/gages/09423350
    - description: hyf__HY_HydroLocation → string
      object:
        example_object: https://geoconnex.us/ref/hu08/03170008
        example_predicate: schema:geoWithin
        example_subject: https://geoconnex.us/iow/demo/AL00017
    - description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
        → schema_Place
      object:
        example_object: https://geoconnex.us/ref/states/53
        example_predicate: schema:geoWithin
        example_subject: https://geoconnex.us/ornl/hydrosource/dams/999
    - description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
        → uri
      object:
        example_object: https://geoconnex.us/nhdplusv2/huc12/102000000000
        example_predicate: schema:geoWithin
        example_subject: https://geoconnex.us/ornl/hydrosource/dams/1
    from_schema: geoconnex
    rank: 1000
    slot_uri: schema:geoWithin
    alias: schema_geoWithin
    owner: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    domain_of:
    - http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    - hyf__HY_HydroLocation
    - schema_Place
    range: Any
    any_of:
    - range: uri
    - range: string
    - range: schema_Place
  hyf_HY_HydroLocationType:
    name: hyf_HY_HydroLocationType
    description: No slot (predicate) description specified
    comments:
    - 42 occurrences with subject type hyf__HY_HydroLocation and object type string.
    - 1617371 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
      and object type string.
    examples:
    - description: hyf__HY_HydroLocation → string
      object:
        example_object: hydrometricStation
        example_predicate: hyf:HY_HydroLocationType
        example_subject: https://geoconnex.us/ref/gages/1000482
    - description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
        → string
      object:
        example_object: hydrometricStation
        example_predicate: hyf:HY_HydroLocationType
        example_subject: https://waterdata.usgs.gov/monitoring-location/00000000/
    from_schema: geoconnex
    rank: 1000
    slot_uri: hyf:HY_HydroLocationType
    alias: hyf_HY_HydroLocationType
    owner: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    domain_of:
    - http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    - hyf__HY_HydroLocation
    range: string
  schema_subjectOf:
    name: schema_subjectOf
    description: No slot (predicate) description specified
    comments:
    - 78891 occurrences with subject type schema_Place and object type uri.
    - 8804 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
      and object type uri.
    - 185645 occurrences with subject type hyf__HY_HydroLocation and object type uri.
    - 28216 occurrences with subject type hyf__HY_HydroLocation and object type schema_Dataset.
    examples:
    - description: schema_Place → uri
      object:
        example_object: https://geonames.usgs.gov/apex/f?p=gnispq:3:::NO::P3_FID:2730131
        example_predicate: schema:subjectOf
        example_subject: https://geoconnex.us/ref/hu02/01
    - description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
        → uri
      object:
        example_object: https://hydrosource.ornl.gov/dataset/existing-hydropower-assets-eha-capacity-factor-plant-database-2005-2019
        example_predicate: schema:subjectOf
        example_subject: https://geoconnex.us/ornl/hydrosource/dams/1
    - description: hyf__HY_HydroLocation → uri
      object:
        example_object: _:b1159177
        example_predicate: schema:subjectOf
        example_subject: https://geoconnex.us/ref/gages/1000001
    - description: hyf__HY_HydroLocation → schema_Dataset
      object:
        example_object: _:b939199
        example_predicate: schema:subjectOf
        example_subject: https://sta.geoconnex.dev/collections/USGS/Things/items/'USGS-625632151172901'
    from_schema: geoconnex
    rank: 1000
    slot_uri: schema:subjectOf
    alias: schema_subjectOf
    owner: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    domain_of:
    - http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    - hyf__HY_HydroLocation
    - schema_Place
    range: Any
    any_of:
    - range: schema_Dataset
    - range: uri
  http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocationType:
    name: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocationType
    description: No slot (predicate) description specified
    comments:
    - 3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
      and object type uri.
    examples:
    - description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
        → uri
      object:
        example_object: http://www.opengeospatial.org/standards/waterml2/hy_features/dam
        example_predicate: http://www.opengeospatial.org/standards/waterml2/hy_features/HY_HydroLocationType
        example_subject: https://geoconnex.us/ornl/hydrosource/dams/1
    from_schema: geoconnex
    rank: 1000
    slot_uri: http://www.opengeospatial.org/standards/waterml2/hy_features/HY_HydroLocationType
    alias: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocationType
    owner: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    domain_of:
    - http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    range: uri
class_uri: http://www.opengeospatial.org/standards/waterml2/hy_features/HY_HydroLocation

```
</details>