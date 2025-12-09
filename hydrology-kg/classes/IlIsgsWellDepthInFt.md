

# Class: IlIsgsWellDepthInFt




This class occurs 376687 times.


URI: [il_isgs:WellDepthInFt](http://sawgraph.spatialai.org/v1/il-isgs#WellDepthInFt)






```mermaid
 classDiagram
    class IlIsgsWellDepthInFt
    click IlIsgsWellDepthInFt href "../IlIsgsWellDepthInFt"
      OwlThing <|-- IlIsgsWellDepthInFt
        click OwlThing href "../OwlThing"
      
      IlIsgsWellDepthInFt : owl_sameAs
        
          
    
    
    IlIsgsWellDepthInFt --> "0..1" OwlThing : owl_sameAs
    click OwlThing href "../OwlThing"

        
      IlIsgsWellDepthInFt : qudt_numericValue
        
          
    
    
    IlIsgsWellDepthInFt --> "0..1" QudtNumericUnion : qudt_numericValue
    click QudtNumericUnion href "../QudtNumericUnion"

        
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * **IlIsgsWellDepthInFt**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [qudt_numericValue](../slots/qudt_numericValue.md) | 0..1 <br/> [QudtNumericUnion](../types/QudtNumericUnion.md) |  <br/>  | direct | 376687 |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md) | The property that determines that two given individuals are equal <br/>  | direct | 376687 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IlIsgsISGS-Well](../classes/IlIsgsISGS-Well.md) | [il_isgs_wellDepth](../slots/il_isgs_wellDepth.md) | range | [IlIsgsWellDepthInFt](../classes/IlIsgsWellDepthInFt.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: il_isgs_WellDepthInFt
from_schema: okns:hydrology-kg
rank: 1000
is_a: owl_Thing
slots:
- qudt_numericValue
- owl_sameAs
class_uri: il_isgs:WellDepthInFt

```
</details>

### Induced

<details>

```yaml
name: il_isgs_WellDepthInFt
from_schema: okns:hydrology-kg
rank: 1000
is_a: owl_Thing
attributes:
  qudt_numericValue:
    name: qudt_numericValue
    title: numeric value
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:qudt
    source: http://qudt.org/schema/qudt
    slot_uri: qudt:numericValue
    alias: qudt_numericValue
    owner: il_isgs_WellDepthInFt
    domain_of:
    - il_isgs_WellDepthInFt
    - il_isgs_WellYield
    - me_mgs_WellDepthInFt
    - me_mgs_WellOverburdenThicknessInFt
    range: qudt_NumericUnion
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
    owner: il_isgs_WellDepthInFt
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
class_uri: il_isgs:WellDepthInFt

```
</details>