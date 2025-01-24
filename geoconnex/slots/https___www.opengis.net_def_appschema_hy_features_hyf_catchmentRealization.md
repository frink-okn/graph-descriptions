

# Slot: https___www.opengis.net_def_appschema_hy_features_hyf_catchmentRealization


_No slot (predicate) description specified_





URI: [https://www.opengis.net/def/appschema/hy_features/hyf/catchmentRealization](https://www.opengis.net/def/appschema/hy_features/hyf/catchmentRealization)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYCatchment](../classes/HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYCatchment.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYHydrometricNetwork](../classes/HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYHydrometricNetwork.md)&nbsp;or&nbsp;<br />[HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYCatchmentDivide](../classes/HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYCatchmentDivide.md)&nbsp;or&nbsp;<br />[HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYHydrographicNetwork](../classes/HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYHydrographicNetwork.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment → https___www.opengis.net_def_appschema_hy_features_hyf_HY_CatchmentDivide | https://geoconnex.us/SELFIE/usgs/huc/huc12obs/070900020601 | https://www.opengis.net/def/appschema/hy_features/hyf/catchmentRealization | https://geoconnex.us/SELFIE/usgs/hucboundary/huc12obs/070900020601 |
| https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment → https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork | https://geoconnex.us/SELFIE/usgs/huc/huc12obs/070900020601 | https://www.opengis.net/def/appschema/hy_features/hyf/catchmentRealization | https://geoconnex.us/SELFIE/usgs/hydrometricnetwork/huc12obs/070900020601 |
| https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment → https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrographicNetwork | https://geoconnex.us/SELFIE/usgs/huc/huc12obs/070900020601 | https://www.opengis.net/def/appschema/hy_features/hyf/catchmentRealization | https://geoconnex.us/SELFIE/usgs/nhdplusflowline/huc12obs/070900020601 |


## Comments

* 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type https___www.opengis.net_def_appschema_hy_features_hyf_HY_CatchmentDivide.
* 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork.
* 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrographicNetwork.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | https://www.opengis.net/def/appschema/hy_features/hyf/catchmentRealization |
| native | geoconnex/:https___www.opengis.net_def_appschema_hy_features_hyf_catchmentRealization |




## LinkML Source

<details>
```yaml
name: https___www.opengis.net_def_appschema_hy_features_hyf_catchmentRealization
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
  and object type https___www.opengis.net_def_appschema_hy_features_hyf_HY_CatchmentDivide.
- 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
  and object type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork.
- 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
  and object type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrographicNetwork.
examples:
- description: https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
    → https___www.opengis.net_def_appschema_hy_features_hyf_HY_CatchmentDivide
  object:
    example_object: https://geoconnex.us/SELFIE/usgs/hucboundary/huc12obs/070900020601
    example_predicate: https://www.opengis.net/def/appschema/hy_features/hyf/catchmentRealization
    example_subject: https://geoconnex.us/SELFIE/usgs/huc/huc12obs/070900020601
- description: https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
    → https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork
  object:
    example_object: https://geoconnex.us/SELFIE/usgs/hydrometricnetwork/huc12obs/070900020601
    example_predicate: https://www.opengis.net/def/appschema/hy_features/hyf/catchmentRealization
    example_subject: https://geoconnex.us/SELFIE/usgs/huc/huc12obs/070900020601
- description: https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
    → https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrographicNetwork
  object:
    example_object: https://geoconnex.us/SELFIE/usgs/nhdplusflowline/huc12obs/070900020601
    example_predicate: https://www.opengis.net/def/appschema/hy_features/hyf/catchmentRealization
    example_subject: https://geoconnex.us/SELFIE/usgs/huc/huc12obs/070900020601
from_schema: geoconnex
rank: 1000
slot_uri: https://www.opengis.net/def/appschema/hy_features/hyf/catchmentRealization
alias: https___www.opengis.net_def_appschema_hy_features_hyf_catchmentRealization
domain_of:
- https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
range: Any
any_of:
- range: https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork
- range: https___www.opengis.net_def_appschema_hy_features_hyf_HY_CatchmentDivide
- range: https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrographicNetwork

```
</details>