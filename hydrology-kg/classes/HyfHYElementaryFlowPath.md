

# Class: HyfHYElementaryFlowPath




This class occurs 434501 times.


URI: [hyf:HY_ElementaryFlowPath](https://www.opengis.net/def/schema/hy_features/hyf/HY_ElementaryFlowPath)






```mermaid
 classDiagram
    class HyfHYElementaryFlowPath
    click HyfHYElementaryFlowPath href "../HyfHYElementaryFlowPath"
      HyfHYFlowPath <|-- HyfHYElementaryFlowPath
        click HyfHYFlowPath href "../HyfHYFlowPath"
      
      HyfHYElementaryFlowPath : dct_title
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" Any : dct_title
    click Any href "../Any"

        
      HyfHYElementaryFlowPath : geo_defaultGeometry
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" GeoGeometry : geo_defaultGeometry
    click GeoGeometry href "../GeoGeometry"

        
      HyfHYElementaryFlowPath : geo_hasGeometry
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" GeoGeometry : geo_hasGeometry
    click GeoGeometry href "../GeoGeometry"

        
      HyfHYElementaryFlowPath : http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasCOMID
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" String : http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasCOMID
    click String href "../String"

        
      HyfHYElementaryFlowPath : http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFCODE
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" String : http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFCODE
    click String href "../String"

        
      HyfHYElementaryFlowPath : http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFlowPathLength
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" Any : http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFlowPathLength
    click Any href "../Any"

        
      HyfHYElementaryFlowPath : http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFTYPE
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" String : http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFTYPE
    click String href "../String"

        
      HyfHYElementaryFlowPath : http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasReachCode
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" String : http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasReachCode
    click String href "../String"

        
      HyfHYElementaryFlowPath : hyf_downstreamFlowPath
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" Any : hyf_downstreamFlowPath
    click Any href "../Any"

        
      HyfHYElementaryFlowPath : hyf_downstreamFlowPathTC
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" Any : hyf_downstreamFlowPathTC
    click Any href "../Any"

        
      HyfHYElementaryFlowPath : hyf_upstreamWaterBody
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" Any : hyf_upstreamWaterBody
    click Any href "../Any"

        
      HyfHYElementaryFlowPath : kwgo_sfCrosses
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" Any : kwgo_sfCrosses
    click Any href "../Any"

        
      HyfHYElementaryFlowPath : kwgo_sfTouches
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" Any : kwgo_sfTouches
    click Any href "../Any"

        
      HyfHYElementaryFlowPath : kwgo_sfWithin
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" Any : kwgo_sfWithin
    click Any href "../Any"

        
      HyfHYElementaryFlowPath : kwgo_spatialRelation
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" Any : kwgo_spatialRelation
    click Any href "../Any"

        
      HyfHYElementaryFlowPath : owl_sameAs
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" OwlThing : owl_sameAs
    click OwlThing href "../OwlThing"

        
      HyfHYElementaryFlowPath : rdfs_label
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      HyfHYElementaryFlowPath : sdos_name
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" SdosText : sdos_name
    click SdosText href "../SdosText"

        
      HyfHYElementaryFlowPath : spatial_connectedTo
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" Any : spatial_connectedTo
    click Any href "../Any"

        
      HyfHYElementaryFlowPath : spatial_spatiallyRelatedTo
        
          
    
    
    HyfHYElementaryFlowPath --> "0..1" Any : spatial_spatiallyRelatedTo
    click Any href "../Any"

        
      
```





## Inheritance
* [HyfHYCatchmentRealization](../classes/HyfHYCatchmentRealization.md)
    * [HyfHYFlowPath](../classes/HyfHYFlowPath.md)
        * **HyfHYElementaryFlowPath**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md) | The property that determines that two given individuals are equal <br/>  | direct | 869002 |
| [http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasCOMID](../slots/http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasCOMID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 434501 |
| [hyf_upstreamWaterBody](../slots/hyf_upstreamWaterBody.md) | 0..1 <br/> [Any](../classes/Any.md) | identifies another waterbody immediately upstream, allowing network navigatio... <br/>  | direct | 1730938 |
| [http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFCODE](../slots/http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFCODE.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 434501 |
| [kwgo_sfTouches](../slots/kwgo_sfTouches.md) | 0..1 <br/> [Any](../classes/Any.md) | KWG's spatial touches relation <br/>  | direct | 103440 |
| [http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFlowPathLength](../slots/http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFlowPathLength.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpNhdplusv2.spatialai.orgV1Nhdplusv2#FlowPathLength](../classes/HttpNhdplusv2.spatialai.orgV1Nhdplusv2#FlowPathLength.md) |  <br/>  | direct | 869002 |
| [dct_title](../slots/dct_title.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md) | A name given to the resource <br/>  | direct | 204608 |
| [kwgo_sfCrosses](../slots/kwgo_sfCrosses.md) | 0..1 <br/> [Any](../classes/Any.md) | KWG's spatial comment relation <br/>  | direct | 1415399 |
| [hyf_downstreamFlowPathTC](../slots/hyf_downstreamFlowPathTC.md) | 0..1 <br/> [GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HyfHYCatchmentRealization](../classes/HyfHYCatchmentRealization.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[HttpHyfo.spatialai.orgV1Hyfo#WaterFeatureRepresentation](../classes/HttpHyfo.spatialai.orgV1Hyfo#WaterFeatureRepresentation.md)&nbsp;or&nbsp;<br />[B805a9e7d30eaabcb686b8ce670ed1e95](../classes/B805a9e7d30eaabcb686b8ce670ed1e95.md)&nbsp;or&nbsp;<br />[HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md)&nbsp;or&nbsp;<br />[HyfHYFlowPath](../classes/HyfHYFlowPath.md) |  <br/>  | direct | 815606014 |
| [http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasReachCode](../slots/http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasReachCode.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 434501 |
| [kwgo_spatialRelation](../slots/kwgo_spatialRelation.md) | 0..1 <br/> [Any](../classes/Any.md) | KWG's general spatial relation <br/>  | direct | 1599339 |
| [sdos_name](../slots/sdos_name.md) | 0..1 <br/> [SdosText](../classes/SdosText.md) | The name of the item <br/>  | direct | 204608 |
| [geo_hasGeometry](../slots/geo_hasGeometry.md) | 0..1 <br/> [GeoGeometry](../classes/GeoGeometry.md) | A spatial representation for a given Feature <br/> source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties<br/>source: http://www.opengis.net/ont/geosparql#<br/>source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties<br/>description: A spatial representation for a given Feature. | direct | 869002 |
| [hyf_downstreamFlowPath](../slots/hyf_downstreamFlowPath.md) | 0..1 <br/> [GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HyfHYCatchmentRealization](../classes/HyfHYCatchmentRealization.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[HttpHyfo.spatialai.orgV1Hyfo#WaterFeatureRepresentation](../classes/HttpHyfo.spatialai.orgV1Hyfo#WaterFeatureRepresentation.md)&nbsp;or&nbsp;<br />[B805a9e7d30eaabcb686b8ce670ed1e95](../classes/B805a9e7d30eaabcb686b8ce670ed1e95.md)&nbsp;or&nbsp;<br />[HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md)&nbsp;or&nbsp;<br />[HyfHYFlowPath](../classes/HyfHYFlowPath.md) |  <br/>  | direct | 1730938 |
| [geo_defaultGeometry](../slots/geo_defaultGeometry.md) | 0..1 <br/> [GeoGeometry](../classes/GeoGeometry.md) | The default Geometry to be used in spatial calculations <br/> source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties<br/>source: http://www.opengis.net/ont/geosparql#<br/>description: The default Geometry to be used in spatial calculations. It is usually the most detailed Geometry. | direct | 869002 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 204608 |
| [http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFTYPE](../slots/http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFTYPE.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 434501 |
| [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | 0..1 <br/> [UsSdwisPublicWaterSystem-GW](../classes/UsSdwisPublicWaterSystem-GW.md)&nbsp;or&nbsp;<br />[HttpGwml2.orgDefGwml2#GWAquiferSystem](../classes/HttpGwml2.orgDefGwml2#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-SW](../classes/UsSdwisPublicWaterSystem-SW.md)&nbsp;or&nbsp;<br />[UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md)&nbsp;or&nbsp;<br />[HttpGwml2.orgDefGwml2#GWAquifer](../classes/HttpGwml2.orgDefGwml2#GWAquifer.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HyfHYWaterBody](../classes/HyfHYWaterBody.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-NTNCWS](../classes/UsSdwisPublicWaterSystem-NTNCWS.md)&nbsp;or&nbsp;<br />[MeMgsMGS-Well](../classes/MeMgsMGS-Well.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)&nbsp;or&nbsp;<br />[B805a9e7d30eaabcb686b8ce670ed1e95](../classes/B805a9e7d30eaabcb686b8ce670ed1e95.md)&nbsp;or&nbsp;<br />[HyfHYHydroFeature](../classes/HyfHYHydroFeature.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion3](../classes/KwgoAdministrativeRegion3.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-CWS](../classes/UsSdwisPublicWaterSystem-CWS.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[HyfHYLake](../classes/HyfHYLake.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-TNCWS](../classes/UsSdwisPublicWaterSystem-TNCWS.md)&nbsp;or&nbsp;<br />[KwgoRegion](../classes/KwgoRegion.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion](../classes/KwgoAdministrativeRegion.md) |  <br/>  | direct | 1599339 |
| [spatial_connectedTo](../slots/spatial_connectedTo.md) | 0..1 <br/> [UsSdwisPublicWaterSystem-GW](../classes/UsSdwisPublicWaterSystem-GW.md)&nbsp;or&nbsp;<br />[HttpGwml2.orgDefGwml2#GWAquiferSystem](../classes/HttpGwml2.orgDefGwml2#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-SW](../classes/UsSdwisPublicWaterSystem-SW.md)&nbsp;or&nbsp;<br />[UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md)&nbsp;or&nbsp;<br />[HttpGwml2.orgDefGwml2#GWAquifer](../classes/HttpGwml2.orgDefGwml2#GWAquifer.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HyfHYWaterBody](../classes/HyfHYWaterBody.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-NTNCWS](../classes/UsSdwisPublicWaterSystem-NTNCWS.md)&nbsp;or&nbsp;<br />[MeMgsMGS-Well](../classes/MeMgsMGS-Well.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)&nbsp;or&nbsp;<br />[B805a9e7d30eaabcb686b8ce670ed1e95](../classes/B805a9e7d30eaabcb686b8ce670ed1e95.md)&nbsp;or&nbsp;<br />[HyfHYHydroFeature](../classes/HyfHYHydroFeature.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion3](../classes/KwgoAdministrativeRegion3.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-CWS](../classes/UsSdwisPublicWaterSystem-CWS.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[HyfHYLake](../classes/HyfHYLake.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-TNCWS](../classes/UsSdwisPublicWaterSystem-TNCWS.md)&nbsp;or&nbsp;<br />[KwgoRegion](../classes/KwgoRegion.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion](../classes/KwgoAdministrativeRegion.md) |  <br/>  | direct | 1599339 |
| [kwgo_sfWithin](../slots/kwgo_sfWithin.md) | 0..1 <br/> [Any](../classes/Any.md) | KWG's spatial within relation <br/>  | direct | 80500 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [B805a9e7d30eaabcb686b8ce670ed1e95](../classes/B805a9e7d30eaabcb686b8ce670ed1e95.md) | [hyf_downstreamFlowPathTC](../slots/hyf_downstreamFlowPathTC.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [B805a9e7d30eaabcb686b8ce670ed1e95](../classes/B805a9e7d30eaabcb686b8ce670ed1e95.md) | [hyf_downstreamFlowPath](../slots/hyf_downstreamFlowPath.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [B805a9e7d30eaabcb686b8ce670ed1e95](../classes/B805a9e7d30eaabcb686b8ce670ed1e95.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [B805a9e7d30eaabcb686b8ce670ed1e95](../classes/B805a9e7d30eaabcb686b8ce670ed1e95.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [HttpGwml2.orgDefGwml2#GWAquifer](../classes/HttpGwml2.orgDefGwml2#GWAquifer.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [HttpGwml2.orgDefGwml2#GWAquifer](../classes/HttpGwml2.orgDefGwml2#GWAquifer.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [HttpGwml2.orgDefGwml2#GWAquiferSystem](../classes/HttpGwml2.orgDefGwml2#GWAquiferSystem.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [HttpGwml2.orgDefGwml2#GWAquiferSystem](../classes/HttpGwml2.orgDefGwml2#GWAquiferSystem.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) | [hyf_downstreamFlowPathTC](../slots/hyf_downstreamFlowPathTC.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) | [hyf_downstreamFlowPath](../slots/hyf_downstreamFlowPath.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [UsSdwisPublicWaterSystem-CWS](../classes/UsSdwisPublicWaterSystem-CWS.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [UsSdwisPublicWaterSystem-CWS](../classes/UsSdwisPublicWaterSystem-CWS.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [UsSdwisPublicWaterSystem-GW](../classes/UsSdwisPublicWaterSystem-GW.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [UsSdwisPublicWaterSystem-GW](../classes/UsSdwisPublicWaterSystem-GW.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [UsSdwisPublicWaterSystem-NTNCWS](../classes/UsSdwisPublicWaterSystem-NTNCWS.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [UsSdwisPublicWaterSystem-NTNCWS](../classes/UsSdwisPublicWaterSystem-NTNCWS.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [UsSdwisPublicWaterSystem-SW](../classes/UsSdwisPublicWaterSystem-SW.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [UsSdwisPublicWaterSystem-SW](../classes/UsSdwisPublicWaterSystem-SW.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [UsSdwisPublicWaterSystem-TNCWS](../classes/UsSdwisPublicWaterSystem-TNCWS.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |
| [UsSdwisPublicWaterSystem-TNCWS](../classes/UsSdwisPublicWaterSystem-TNCWS.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: hyf_HY_ElementaryFlowPath
from_schema: okns:hydrology-kg
rank: 1000
is_a: hyf_HY_FlowPath
slots:
- owl_sameAs
- http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasCOMID
- hyf_upstreamWaterBody
- http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFCODE
- kwgo_sfTouches
- http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFlowPathLength
- dct_title
- kwgo_sfCrosses
- hyf_downstreamFlowPathTC
- http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasReachCode
- kwgo_spatialRelation
- sdos_name
- geo_hasGeometry
- hyf_downstreamFlowPath
- geo_defaultGeometry
- rdfs_label
- http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFTYPE
- spatial_spatiallyRelatedTo
- spatial_connectedTo
- kwgo_sfWithin
class_uri: hyf:HY_ElementaryFlowPath

```
</details>

### Induced

<details>

```yaml
name: hyf_HY_ElementaryFlowPath
from_schema: okns:hydrology-kg
rank: 1000
is_a: hyf_HY_FlowPath
attributes:
  owl_sameAs:
    name: owl_sameAs
    description: The property that determines that two given individuals are equal.
    title: sameAs
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2002/07/owl#
    domain: owl_Thing
    slot_uri: owl:sameAs
    alias: owl_sameAs
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - http___gwml2.org_def_gwml2#GW_Aquifer
    - http___gwml2.org_def_gwml2#GW_AquiferSystem
    - http___nhdplusv2.spatialai.org_v1_nhdplusv2#FlowPathLength
    - hyf_HY_ElementaryFlowPath
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
  http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasCOMID:
    name: http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasCOMID
    from_schema: okns:hydrology-kg
    rank: 1000
    slot_uri: http://nhdplusv2.spatialai.org/v1/nhdplusv2#hasCOMID
    alias: http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasCOMID
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - hyf_HY_ElementaryFlowPath
    range: string
  hyf_upstreamWaterBody:
    name: hyf_upstreamWaterBody
    description: identifies another waterbody immediately upstream, allowing network
      navigation without knowing an inflow or outflow of the catchment realized by
      the waterbody.
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:hyf
    slot_uri: hyf:upstreamWaterBody
    alias: hyf_upstreamWaterBody
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - hyf_HY_ElementaryFlowPath
    range: Any
  http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFCODE:
    name: http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFCODE
    from_schema: okns:hydrology-kg
    rank: 1000
    slot_uri: http://nhdplusv2.spatialai.org/v1/nhdplusv2#hasFCODE
    alias: http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFCODE
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - hyf_HY_ElementaryFlowPath
    range: string
  kwgo_sfTouches:
    name: kwgo_sfTouches
    description: KWG's spatial touches relation
    title: touches (simple feature)
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:kwg
    slot_uri: kwgo:sfTouches
    alias: kwgo_sfTouches
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - hyf_HY_ElementaryFlowPath
    subproperty_of: kwgo_spatialRelation
    range: Any
  http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFlowPathLength:
    name: http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFlowPathLength
    from_schema: okns:hydrology-kg
    rank: 1000
    slot_uri: http://nhdplusv2.spatialai.org/v1/nhdplusv2#hasFlowPathLength
    alias: http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFlowPathLength
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - hyf_HY_ElementaryFlowPath
    range: Any
    any_of:
    - range: owl_Thing
    - range: http___nhdplusv2.spatialai.org_v1_nhdplusv2#FlowPathLength
  dct_title:
    name: dct_title
    description: A name given to the resource.
    title: Title
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:title
    alias: dct_title
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - vaem_GraphMetaData
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - hyf_HY_ElementaryFlowPath
    subproperty_of: dc_title
    range: Any
    any_of:
    - range: string
    - range: rdfs_Literal
  kwgo_sfCrosses:
    name: kwgo_sfCrosses
    description: KWG's spatial comment relation
    title: crosses (simple feature)
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:kwg
    slot_uri: kwgo:sfCrosses
    alias: kwgo_sfCrosses
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - hyf_HY_ElementaryFlowPath
    - kwgo_S2Cell_Level13
    subproperty_of: kwgo_spatialRelation
    range: Any
  hyf_downstreamFlowPathTC:
    name: hyf_downstreamFlowPathTC
    title: No slot (predicate) name specified -- this slot is noted as a subproperty
      of another slot in this graph but has not itself been defined.
    from_schema: okns:hydrology-kg
    rank: 1000
    slot_uri: hyf:downstreamFlowPathTC
    alias: hyf_downstreamFlowPathTC
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - hyf_HY_ElementaryFlowPath
    transitive: true
    union_of:
    - geo_Feature
    - owl_Thing
    - hyf_HY_CatchmentRealization
    - geo_SpatialObject
    - http___hyfo.spatialai.org_v1_hyfo#WaterFeatureRepresentation
    - hyf_HY_FlowPath
    range: Any
    any_of:
    - range: geo_Feature
    - range: owl_Thing
    - range: hyf_HY_CatchmentRealization
    - range: geo_SpatialObject
    - range: http___hyfo.spatialai.org_v1_hyfo#WaterFeatureRepresentation
    - range: __B805a9e7d30eaabcb686b8ce670ed1e95
    - range: hyf_HY_ElementaryFlowPath
    - range: hyf_HY_FlowPath
  http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasReachCode:
    name: http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasReachCode
    from_schema: okns:hydrology-kg
    rank: 1000
    slot_uri: http://nhdplusv2.spatialai.org/v1/nhdplusv2#hasReachCode
    alias: http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasReachCode
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - hyf_HY_ElementaryFlowPath
    range: string
  kwgo_spatialRelation:
    name: kwgo_spatialRelation
    description: KWG's general spatial relation
    title: spatial relation
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:kwg
    slot_uri: kwgo:spatialRelation
    alias: kwgo_spatialRelation
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - http___gwml2.org_def_gwml2#GW_Aquifer
    - http___gwml2.org_def_gwml2#GW_AquiferSystem
    - hyf_HY_ElementaryFlowPath
    - kwgo_S2Cell_Level13
    - me_mgs_MGS-Well
    - us_sdwis_PWS-ServiceArea
    - us_sdwis_PublicWaterSystem-CWS
    - us_sdwis_PublicWaterSystem-GW
    - us_sdwis_PublicWaterSystem-NTNCWS
    - us_sdwis_PublicWaterSystem-SW
    - us_sdwis_PublicWaterSystem-TNCWS
    range: Any
  sdos_name:
    name: sdos_name
    description: The name of the item.
    title: name
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:sdo
    exact_mappings:
    - http://purl.org/dc/terms/title
    domain: sdos_Thing
    slot_uri: sdos:name
    alias: sdos_name
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - hyf_HY_ElementaryFlowPath
    subproperty_of: rdfs_label
    range: sdos_Text
  geo_hasGeometry:
    name: geo_hasGeometry
    description: A spatial representation for a given Feature.
    title: No slot (predicate) name specified -- this slot is noted as a subproperty
      of another slot in this graph but has not itself been defined.
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties'
    - 'source: http://www.opengis.net/ont/geosparql#'
    - 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties'
    - 'description: A spatial representation for a given Feature.'
    from_schema: okns:geo
    source: http://www.opengis.net/ont/geosparql#
    domain: geo_Feature
    slot_uri: geo:hasGeometry
    alias: geo_hasGeometry
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - http___gwml2.org_def_gwml2#GW_Aquifer
    - http___gwml2.org_def_gwml2#GW_AquiferSystem
    - hyf_HY_ElementaryFlowPath
    - il_isgs_ISGS-Well
    - me_mgs_MGS-Well
    - us_sdwis_PWS-ServiceArea
    range: geo_Geometry
  hyf_downstreamFlowPath:
    name: hyf_downstreamFlowPath
    from_schema: okns:hydrology-kg
    rank: 1000
    slot_uri: hyf:downstreamFlowPath
    alias: hyf_downstreamFlowPath
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - hyf_HY_ElementaryFlowPath
    subproperty_of: hyf_downstreamFlowPathTC
    inverse: hyf_upstreamWaterBody
    union_of:
    - geo_Feature
    - owl_Thing
    - hyf_HY_CatchmentRealization
    - geo_SpatialObject
    - http___hyfo.spatialai.org_v1_hyfo#WaterFeatureRepresentation
    - hyf_HY_FlowPath
    range: Any
    any_of:
    - range: geo_Feature
    - range: owl_Thing
    - range: hyf_HY_CatchmentRealization
    - range: geo_SpatialObject
    - range: http___hyfo.spatialai.org_v1_hyfo#WaterFeatureRepresentation
    - range: __B805a9e7d30eaabcb686b8ce670ed1e95
    - range: hyf_HY_ElementaryFlowPath
    - range: hyf_HY_FlowPath
  geo_defaultGeometry:
    name: geo_defaultGeometry
    description: The default Geometry to be used in spatial calculations. It is usually
      the most detailed Geometry.
    notes:
    - Duplicate properties defaultGeometry and hasDefaultGeometry exist because of
      an inconsistency between ontology and documentation in GeoSPARQL 1.0. Only hasDefaultGeometry
      is described in the documention.
    - No occurrences of this slot in the graph.
    comments:
    - 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties'
    - 'source: http://www.opengis.net/ont/geosparql#'
    - 'description: The default Geometry to be used in spatial calculations. It is
      usually the most detailed Geometry.'
    from_schema: okns:geo
    source: http://www.opengis.net/ont/geosparql#
    exact_mappings:
    - http://www.opengis.net/ont/geosparql#hasDefaultGeometry
    domain: geo_Feature
    slot_uri: geo:defaultGeometry
    alias: geo_defaultGeometry
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - http___gwml2.org_def_gwml2#GW_Aquifer
    - http___gwml2.org_def_gwml2#GW_AquiferSystem
    - hyf_HY_ElementaryFlowPath
    subproperty_of: geo_hasGeometry
    range: geo_Geometry
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - rdf_List
    - rdfs_Datatype
    - dcam_VocabularyEncodingScheme
    - dct_AgentClass
    - qudt_AspectClass
    - qudt_BinaryPrefix
    - qudt_BitEncodingType
    - qudt_BooleanEncodingType
    - qudt_ByteEncodingType
    - qudt_CardinalityType
    - qudt_CharEncodingType
    - qudt_ContextualUnit
    - qudt_CountingUnit
    - qudt_CurrencyUnit
    - qudt_DateTimeStringEncodingType
    - qudt_DecimalPrefix
    - qudt_DerivedUnit
    - qudt_DimensionlessUnit
    - qudt_EndianType
    - qudt_FloatingPointEncodingType
    - qudt_IntegerEncodingType
    - qudt_LogarithmicUnit
    - qudt_OrderedType
    - qudt_SignednessType
    - qudt_Unit
    - sdos_ActionStatusType
    - sdos_AdultOrientedEnumeration
    - sdos_BoardingPolicyType
    - sdos_BodyMeasurementTypeEnumeration
    - sdos_BookFormatType
    - sdos_Boolean
    - sdos_CarUsageType
    - sdos_CertificationStatusEnumeration
    - sdos_ContactPointOption
    - sdos_DataType
    - sdos_DayOfWeek
    - sdos_DeliveryMethod
    - sdos_DigitalDocumentPermissionType
    - sdos_DigitalPlatformEnumeration
    - sdos_DriveWheelConfigurationValue
    - sdos_DrugCostCategory
    - sdos_DrugPregnancyCategory
    - sdos_DrugPrescriptionStatus
    - sdos_EUEnergyEfficiencyEnumeration
    - sdos_EnergyStarEnergyEfficiencyEnumeration
    - sdos_EventAttendanceModeEnumeration
    - sdos_EventStatusType
    - sdos_FulfillmentTypeEnumeration
    - sdos_GameAvailabilityEnumeration
    - sdos_GamePlayMode
    - sdos_GameServerStatus
    - sdos_GenderType
    - sdos_GovernmentBenefitsType
    - sdos_HealthAspectEnumeration
    - sdos_IPTCDigitalSourceEnumeration
    - sdos_IncentiveQualifiedExpenseType
    - sdos_IncentiveStatus
    - sdos_IncentiveType
    - sdos_InfectiousAgentClass
    - sdos_ItemAvailability
    - sdos_ItemListOrderType
    - sdos_LegalForceStatus
    - sdos_LegalValueLevel
    - sdos_MapCategoryType
    - sdos_MeasurementMethodEnum
    - sdos_MediaManipulationRatingEnumeration
    - sdos_MedicalAudienceType
    - sdos_MedicalDevicePurpose
    - sdos_MedicalEvidenceLevel
    - sdos_MedicalImagingTechnique
    - sdos_MedicalObservationalStudyDesign
    - sdos_MedicalProcedureType
    - sdos_MedicalSpecialty
    - sdos_MedicalStudyStatus
    - sdos_MedicalTrialDesign
    - sdos_MedicineSystem
    - sdos_MerchantReturnEnumeration
    - sdos_MusicAlbumProductionType
    - sdos_MusicAlbumReleaseType
    - sdos_MusicReleaseFormatType
    - sdos_NLNonprofitType
    - sdos_OfferItemCondition
    - sdos_OrderStatus
    - sdos_PaymentMethodType
    - sdos_PaymentStatusType
    - sdos_PhysicalActivityCategory
    - sdos_PhysicalExam
    - sdos_PriceComponentTypeEnumeration
    - sdos_PriceTypeEnumeration
    - sdos_ProductReturnEnumeration
    - sdos_PurchaseType
    - sdos_RefundTypeEnumeration
    - sdos_ReservationStatusType
    - sdos_RestrictedDiet
    - sdos_ReturnFeesEnumeration
    - sdos_ReturnLabelSourceEnumeration
    - sdos_ReturnMethodEnumeration
    - sdos_RsvpResponseType
    - sdos_SizeSystemEnumeration
    - sdos_SteeringPositionValue
    - sdos_TierBenefitEnumeration
    - sdos_UKNonprofitType
    - sdos_USNonprofitType
    - sdos_WearableMeasurementTypeEnumeration
    - sdos_WearableSizeGroupEnumeration
    - sdos_WearableSizeSystemEnumeration
    - vaem_GraphMetaData
    - vaem_GraphRole
    - vaem_Party
    - time_DayOfWeek
    - time_TemporalUnit
    - rdf_DatatypeProperty
    - vaem_CatalogEntry
    - voag_Attribution
    - voag_AttributionLogo
    - voag_ChangeFrequency
    - voag_ChangeType
    - voag_ConfidentialityLevel
    - voag_CreativeCommonsPermission
    - voag_CreativeCommonsProhibition
    - voag_CreativeCommonsRequirement
    - voag_Governance
    - voag_GovernanceRole
    - voag_Icon
    - voag_IssueStatus
    - voag_LicenseModel
    - voag_Logo
    - voag_Maturity
    - voag_OrganizationLogo
    - voag_Pedigree
    - voag_PriorityValue
    - voag_ProductLogo
    - voag_Provenance
    - voag_PublicationStatus
    - voag_SchemaGraph
    - kwgo_AirPollutant
    - kwgo_BlueskyWildfireObservableProperty
    - kwgo_CensusObservableProperty
    - kwgo_ClimateObservableProperty
    - kwgo_CroplandObservableProperty
    - kwgo_DroughtIntensity
    - kwgo_FireCause
    - kwgo_HelipadAvailability
    - kwgo_HospitalStatus
    - kwgo_HospitalType
    - kwgo_ImpactObservableProperty
    - kwgo_LSADArea
    - kwgo_MTBSFireObservableProperty
    - kwgo_MagnitudeObservableProperty
    - kwgo_NIFCFireObservableProperty
    - kwgo_PublicHealthObservableProperty
    - kwgo_RoadType
    - kwgo_SmokePlumeObservableProperty
    - kwgo_SoilMapUnitObservableProperty
    - kwgo_StormTrackObservableProperty
    - kwgo_StormTrackletObservableProperty
    - kwgo_VulnerabilityObservableProperty
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - http___gwml2.org_def_gwml2#GW_Aquifer
    - http___gwml2.org_def_gwml2#GW_AquiferSystem
    - hyf_HY_ElementaryFlowPath
    - il_isgs_ISGS-Well
    - il_isgs_WellPurpose
    - me_mgs_MGS-Well
    - us_sdwis_PWS-ServiceAreaType
    - us_sdwis_PWS-SubFeatureActivity
    - us_sdwis_PWS-SubFeatureType
    - us_sdwis_PublicWaterSystem-CWS
    - us_sdwis_PublicWaterSystem-GW
    - us_sdwis_PublicWaterSystem-NTNCWS
    - us_sdwis_PublicWaterSystem-SW
    - us_sdwis_PublicWaterSystem-TNCWS
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
  http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFTYPE:
    name: http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFTYPE
    from_schema: okns:hydrology-kg
    rank: 1000
    slot_uri: http://nhdplusv2.spatialai.org/v1/nhdplusv2#hasFTYPE
    alias: http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFTYPE
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - hyf_HY_ElementaryFlowPath
    range: string
  spatial_spatiallyRelatedTo:
    name: spatial_spatiallyRelatedTo
    title: topological connection (spatial contact) (sawgraph)
    from_schema: okns:hydrology-kg
    exact_mappings:
    - http://stko-kwg.geog.ucsb.edu/lod/ontology/spatialRelation
    rank: 1000
    slot_uri: spatial:spatiallyRelatedTo
    alias: spatial_spatiallyRelatedTo
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - http___gwml2.org_def_gwml2#GW_Aquifer
    - http___gwml2.org_def_gwml2#GW_AquiferSystem
    - hyf_HY_ElementaryFlowPath
    - kwgo_S2Cell_Level13
    - me_mgs_MGS-Well
    - us_sdwis_PWS-ServiceArea
    - us_sdwis_PublicWaterSystem-CWS
    - us_sdwis_PublicWaterSystem-GW
    - us_sdwis_PublicWaterSystem-NTNCWS
    - us_sdwis_PublicWaterSystem-SW
    - us_sdwis_PublicWaterSystem-TNCWS
    subproperty_of: kwgo_spatialRelation
    union_of:
    - owl_Thing
    - geo_SpatialObject
    range: Any
    any_of:
    - range: us_sdwis_PublicWaterSystem-GW
    - range: http___gwml2.org_def_gwml2#GW_AquiferSystem
    - range: us_sdwis_PublicWaterSystem-SW
    - range: us_sdwis_PWS-ServiceArea
    - range: http___gwml2.org_def_gwml2#GW_Aquifer
    - range: owl_Thing
    - range: hyf_HY_WaterBody
    - range: us_sdwis_PublicWaterSystem-NTNCWS
    - range: me_mgs_MGS-Well
    - range: kwgo_S2Cell_Level13
    - range: __B805a9e7d30eaabcb686b8ce670ed1e95
    - range: hyf_HY_HydroFeature
    - range: kwgo_AdministrativeRegion_3
    - range: us_sdwis_PublicWaterSystem-CWS
    - range: geo_Feature
    - range: hyf_HY_Lake
    - range: geo_SpatialObject
    - range: hyf_HY_ElementaryFlowPath
    - range: kwgo_AdministrativeRegion_2
    - range: us_sdwis_PublicWaterSystem-TNCWS
    - range: kwgo_Region
    - range: kwgo_AdministrativeRegion
  spatial_connectedTo:
    name: spatial_connectedTo
    title: topological connection (spatial contact) (sawgraph)
    from_schema: okns:hydrology-kg
    rank: 1000
    slot_uri: spatial:connectedTo
    alias: spatial_connectedTo
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - http___gwml2.org_def_gwml2#GW_Aquifer
    - http___gwml2.org_def_gwml2#GW_AquiferSystem
    - hyf_HY_ElementaryFlowPath
    - kwgo_S2Cell_Level13
    - me_mgs_MGS-Well
    - us_sdwis_PWS-ServiceArea
    - us_sdwis_PublicWaterSystem-CWS
    - us_sdwis_PublicWaterSystem-GW
    - us_sdwis_PublicWaterSystem-NTNCWS
    - us_sdwis_PublicWaterSystem-SW
    - us_sdwis_PublicWaterSystem-TNCWS
    subproperty_of: kwgo_spatialRelation
    union_of:
    - owl_Thing
    - geo_SpatialObject
    range: Any
    any_of:
    - range: us_sdwis_PublicWaterSystem-GW
    - range: http___gwml2.org_def_gwml2#GW_AquiferSystem
    - range: us_sdwis_PublicWaterSystem-SW
    - range: us_sdwis_PWS-ServiceArea
    - range: http___gwml2.org_def_gwml2#GW_Aquifer
    - range: owl_Thing
    - range: hyf_HY_WaterBody
    - range: us_sdwis_PublicWaterSystem-NTNCWS
    - range: me_mgs_MGS-Well
    - range: kwgo_S2Cell_Level13
    - range: __B805a9e7d30eaabcb686b8ce670ed1e95
    - range: hyf_HY_HydroFeature
    - range: kwgo_AdministrativeRegion_3
    - range: us_sdwis_PublicWaterSystem-CWS
    - range: geo_Feature
    - range: hyf_HY_Lake
    - range: geo_SpatialObject
    - range: hyf_HY_ElementaryFlowPath
    - range: kwgo_AdministrativeRegion_2
    - range: us_sdwis_PublicWaterSystem-TNCWS
    - range: kwgo_Region
    - range: kwgo_AdministrativeRegion
  kwgo_sfWithin:
    name: kwgo_sfWithin
    description: KWG's spatial within relation
    title: within (simple feature)
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:kwg
    slot_uri: kwgo:sfWithin
    alias: kwgo_sfWithin
    owner: hyf_HY_ElementaryFlowPath
    domain_of:
    - __B805a9e7d30eaabcb686b8ce670ed1e95
    - http___gwml2.org_def_gwml2#GW_Aquifer
    - hyf_HY_ElementaryFlowPath
    - kwgo_S2Cell_Level13
    - me_mgs_MGS-Well
    subproperty_of: kwgo_spatialRelation
    range: Any
class_uri: hyf:HY_ElementaryFlowPath

```
</details>