

# Class: Administrative Region Level 2 (kwgo_AdministrativeRegion_2)


_Administrative Region Level 2 - state/province/equivalent level_






This class occurs 118 times.


URI: [kwgo:AdministrativeRegion_2](http://stko-kwg.geog.ucsb.edu/lod/ontology/AdministrativeRegion_2)






```mermaid
 classDiagram
    class KwgoAdministrativeRegion2
    click KwgoAdministrativeRegion2 href "../KwgoAdministrativeRegion2"
      KwgoAdministrativeRegion <|-- KwgoAdministrativeRegion2
        click KwgoAdministrativeRegion href "../KwgoAdministrativeRegion"
      
      
```





## Inheritance
* [GeoSpatialObject](../classes/GeoSpatialObject.md)
    * [GeoFeature](../classes/GeoFeature.md)
        * [KwgoAdministrativeRegion](../classes/KwgoAdministrativeRegion.md)
            * **KwgoAdministrativeRegion2**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md) |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md) |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md) |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md) |






## Comments

* description: Source - Global Administrative area database (GADM) (https://gadm.org/data.html)






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: kwgo_AdministrativeRegion_2
description: Administrative Region Level 2 - state/province/equivalent level
title: Administrative Region Level 2
comments:
- 'description: Source - Global Administrative area database (GADM) (https://gadm.org/data.html)'
from_schema: okns:kwg
is_a: kwgo_AdministrativeRegion
class_uri: kwgo:AdministrativeRegion_2

```
</details>

### Induced

<details>

```yaml
name: kwgo_AdministrativeRegion_2
description: Administrative Region Level 2 - state/province/equivalent level
title: Administrative Region Level 2
comments:
- 'description: Source - Global Administrative area database (GADM) (https://gadm.org/data.html)'
from_schema: okns:kwg
is_a: kwgo_AdministrativeRegion
class_uri: kwgo:AdministrativeRegion_2

```
</details>