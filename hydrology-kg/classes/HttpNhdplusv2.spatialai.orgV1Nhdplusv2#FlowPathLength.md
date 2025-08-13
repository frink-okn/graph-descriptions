

# Class: HttpNhdplusv2.spatialai.orgV1Nhdplusv2#FlowPathLength




This class occurs 434501 times.


URI: [http://nhdplusv2.spatialai.org/v1/nhdplusv2#FlowPathLength](http://nhdplusv2.spatialai.org/v1/nhdplusv2#FlowPathLength)






```mermaid
 classDiagram
    class HttpNhdplusv2.spatialai.orgV1Nhdplusv2#FlowPathLength
    click HttpNhdplusv2.spatialai.orgV1Nhdplusv2#FlowPathLength href "../HttpNhdplusv2.spatialai.orgV1Nhdplusv2#FlowPathLength"
      HttpNhdplusv2.spatialai.orgV1Nhdplusv2#FlowPathLength : owl_sameAs
        
          
    
    
    HttpNhdplusv2.spatialai.orgV1Nhdplusv2#FlowPathLength --> "0..1" OwlThing : owl_sameAs
    click OwlThing href "../OwlThing"

        
      HttpNhdplusv2.spatialai.orgV1Nhdplusv2#FlowPathLength : qudt_quantityValue
        
          
    
    
    HttpNhdplusv2.spatialai.orgV1Nhdplusv2#FlowPathLength --> "0..1" QudtQuantityValue : qudt_quantityValue
    click QudtQuantityValue href "../QudtQuantityValue"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [qudt_quantityValue](../slots/qudt_quantityValue.md) | 0..1 <br/> [QudtQuantityValue](../classes/QudtQuantityValue.md) |  <br/> No occurrences of this slot in the graph. | direct | 869002 |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md) | The property that determines that two given individuals are equal <br/> No occurrences of this slot in the graph. | direct | 869002 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) | [http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFlowPathLength](../slots/http___nhdplusv2.spatialai.org_v1_nhdplusv2#hasFlowPathLength.md) | any_of[range] | [HttpNhdplusv2.spatialai.orgV1Nhdplusv2#FlowPathLength](../classes/HttpNhdplusv2.spatialai.orgV1Nhdplusv2#FlowPathLength.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___nhdplusv2.spatialai.org_v1_nhdplusv2#FlowPathLength
from_schema: okns:hydrology-kg
exact_mappings:
- http://nhdplusv2.spatialai.org/v1/nhdplusv2#FlowPathLength
rank: 1000
slots:
- qudt_quantityValue
- owl_sameAs
class_uri: http://nhdplusv2.spatialai.org/v1/nhdplusv2#FlowPathLength

```
</details>

### Induced

<details>

```yaml
name: http___nhdplusv2.spatialai.org_v1_nhdplusv2#FlowPathLength
from_schema: okns:hydrology-kg
exact_mappings:
- http://nhdplusv2.spatialai.org/v1/nhdplusv2#FlowPathLength
rank: 1000
attributes:
  qudt_quantityValue:
    name: qudt_quantityValue
    title: quantity value
    comments:
    - No occurrences of this slot in the graph.
    from_schema: okns:qudt
    source: http://qudt.org/schema/qudt
    slot_uri: qudt:quantityValue
    alias: qudt_quantityValue
    owner: http___nhdplusv2.spatialai.org_v1_nhdplusv2#FlowPathLength
    domain_of:
    - http___nhdplusv2.spatialai.org_v1_nhdplusv2#FlowPathLength
    range: qudt_QuantityValue
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
    owner: http___nhdplusv2.spatialai.org_v1_nhdplusv2#FlowPathLength
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
class_uri: http://nhdplusv2.spatialai.org/v1/nhdplusv2#FlowPathLength

```
</details>