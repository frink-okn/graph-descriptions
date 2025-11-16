

# Class: MeMgsWellUse




This class occurs 13 times.


URI: [me_mgs:WellUse](http://sawgraph.spatialai.org/v1/me-mgs#WellUse)






```mermaid
 classDiagram
    class MeMgsWellUse
    click MeMgsWellUse href "../MeMgsWellUse"
      OwlThing <|-- MeMgsWellUse
        click OwlThing href "../OwlThing"
      
      MeMgsWellUse : owl_sameAs
        
          
    
    
    MeMgsWellUse --> "0..1" OwlThing : owl_sameAs
    click OwlThing href "../OwlThing"

        
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * **MeMgsWellUse**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md) | The property that determines that two given individuals are equal <br/>  | direct | 13 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) | [me_mgs_hasUse](../slots/me_mgs_hasUse.md) | any_of[range] | [MeMgsWellUse](../classes/MeMgsWellUse.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: me_mgs_WellUse
from_schema: okns:hydrology-kg
rank: 1000
is_a: owl_Thing
slots:
- owl_sameAs
class_uri: me_mgs:WellUse

```
</details>

### Induced

<details>

```yaml
name: me_mgs_WellUse
from_schema: okns:hydrology-kg
rank: 1000
is_a: owl_Thing
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
    owner: me_mgs_WellUse
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
class_uri: me_mgs:WellUse

```
</details>