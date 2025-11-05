

# Slot: topological connection (spatial contact) (sawgraph) (spatial_connectedTo)




This slot occurs 2322 times.


URI: [spatial:connectedTo](http://purl.org/spatialai/spatial/spatial-full#connectedTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#Site](../classes/HttpsIdir.uta.eduSockg-ontology#Site.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |  |  no  |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#Site](../classes/HttpsIdir.uta.eduSockg-ontology#Site.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md)







## LinkML Source

<details>

```yaml
name: spatial_connectedTo
title: topological connection (spatial contact) (sawgraph)
from_schema: okns:soc-kg
rank: 1000
slot_uri: spatial:connectedTo
alias: spatial_connectedTo
domain_of:
- https___idir.uta.edu_sockg-ontology#Location
- https___idir.uta.edu_sockg-ontology#Site
- kwgo_S2Cell_Level13
subproperty_of: spatial_spatiallyRelatedTo
range: Any
any_of:
- range: kwgo_AdministrativeRegion_2
- range: https___idir.uta.edu_sockg-ontology#Site
- range: kwgo_S2Cell_Level13
- range: https___idir.uta.edu_sockg-ontology#Location

```
</details>