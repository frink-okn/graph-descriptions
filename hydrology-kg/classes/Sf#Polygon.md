

# Class: Sf#Polygon




This class occurs 10656 times.


URI: [sf:#Polygon](http://www.opengis.net/ont/sf#Polygon)






```mermaid
 classDiagram
    class Sf#Polygon
    click Sf#Polygon href "../Sf#Polygon"
      Sf#Polygon : geo_asWKT
        
          
    
    
    Sf#Polygon --> "0..1" GeoWktLiteral : geo_asWKT
    click GeoWktLiteral href "../GeoWktLiteral"

        
      Sf#Polygon : owl_sameAs
        
          
    
    
    Sf#Polygon --> "0..1" OwlThing : owl_sameAs
    click OwlThing href "../OwlThing"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md) | The property that determines that two given individuals are equal <br/> No occurrences of this slot in the graph. | direct | 31968 |
| [geo_asWKT](../slots/geo_asWKT.md) | 0..1 <br/> [GeoWktLiteral](../types/GeoWktLiteral.md) | The WKT serialization of a Geometry <br/> source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-as-wkt-literal<br/>source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-as-wkt-literal<br/>source: http://www.opengis.net/ont/geosparql#<br/>source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-as-wkt-literal<br/>source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-as-wkt-literal<br/>description: The WKT serialization of a Geometry<br/>No occurrences of this slot in the graph. | direct | 10673 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sf_#Polygon
from_schema: okns:hydrology-kg
rank: 1000
slots:
- owl_sameAs
- geo_asWKT
class_uri: sf:#Polygon

```
</details>

### Induced

<details>

```yaml
name: sf_#Polygon
from_schema: okns:hydrology-kg
rank: 1000
attributes:
  owl_sameAs:
    name: owl_sameAs
    description: The property that determines that two given individuals are equal.
    title: sameAs
    comments:
    - No occurrences of this slot in the graph.
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2002/07/owl#
    domain: owl_Thing
    slot_uri: owl:sameAs
    alias: owl_sameAs
    owner: sf_#Polygon
    domain_of:
    - http___gwml2.org_def_gwml2#GW_Aquifer
    - http___gwml2.org_def_gwml2#GW_AquiferSystem
    - http___nhdplusv2.spatialai.org_v1_nhdplusv2#FlowPathLength
    - hyf__HY_ElementaryFlowPath
    - hyf__HY_Lake
    - hyf__HY_WaterBody
    - il_isgs_ISGS-Well
    - il_isgs_WellDepthInFt
    - il_isgs_WellPurpose
    - il_isgs_WellYield
    - kwgo_S2Cell_Level13
    - me_mgs_MGS-Well
    - me_mgs_WellDepthInFt
    - me_mgs_WellOverburdenThicknessInFt
    - me_mgs_WellType
    - me_mgs_WellUse
    - owl_DataProperty
    - sf_#MultiPolygon
    - sf_#Polygon
    - us_sdwis_PWS-ServiceArea
    - us_sdwis_PWS-ServiceAreaType
    - us_sdwis_PWS-SourceWaterType
    - us_sdwis_PWS-SubFeatureActivity
    - us_sdwis_PWS-SubFeatureType
    - us_sdwis_PublicWaterSystem-CWS
    - us_sdwis_PublicWaterSystem-GW
    - us_sdwis_PublicWaterSystem-NTNCWS
    - us_sdwis_PublicWaterSystem-SW
    - us_sdwis_PublicWaterSystem-TNCWS
    range: owl_Thing
  geo_asWKT:
    name: geo_asWKT
    description: The WKT serialization of a Geometry
    comments:
    - 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-as-wkt-literal'
    - 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-as-wkt-literal'
    - 'source: http://www.opengis.net/ont/geosparql#'
    - 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-as-wkt-literal'
    - 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-as-wkt-literal'
    - 'description: The WKT serialization of a Geometry'
    - No occurrences of this slot in the graph.
    from_schema: okns:geo
    source: http://www.opengis.net/ont/geosparql#
    domain: geo_Geometry
    slot_uri: geo:asWKT
    alias: geo_asWKT
    owner: sf_#Polygon
    domain_of:
    - sf_#MultiPolygon
    - sf_#Polygon
    subproperty_of: geo_hasSerialization
    range: geo_wktLiteral
class_uri: sf:#Polygon

```
</details>