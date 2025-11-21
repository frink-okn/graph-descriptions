

# Class: Region (kwgo_Region)


_A geographic entity created by the selection of characteristics that are relevant to an area of interest. It can have geometries including point, polyline and polygon._






This class occurs 2345 times.


URI: [kwgo:Region](http://stko-kwg.geog.ucsb.edu/lod/ontology/Region)






```mermaid
 classDiagram
    class KwgoRegion
    click KwgoRegion href "../KwgoRegion"
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [KwgoRegion](../classes/KwgoRegion.md) |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [KwgoRegion](../classes/KwgoRegion.md) |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [KwgoRegion](../classes/KwgoRegion.md) |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [KwgoRegion](../classes/KwgoRegion.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [KwgoRegion](../classes/KwgoRegion.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [KwgoRegion](../classes/KwgoRegion.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: kwgo_Region
description: A geographic entity created by the selection of characteristics that
  are relevant to an area of interest. It can have geometries including point, polyline
  and polygon.
title: Region
from_schema: okns:kwg
class_uri: kwgo:Region

```
</details>

### Induced

<details>

```yaml
name: kwgo_Region
description: A geographic entity created by the selection of characteristics that
  are relevant to an area of interest. It can have geometries including point, polyline
  and polygon.
title: Region
from_schema: okns:kwg
class_uri: kwgo:Region

```
</details>