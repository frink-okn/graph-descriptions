

# Class: Administrative Region (kwgo_AdministrativeRegion)


_Source - Global Administrative area database (GADM) (https://gadm.org/data.html)_






This class occurs 2225 times.


URI: [kwgo:AdministrativeRegion](http://stko-kwg.geog.ucsb.edu/lod/ontology/AdministrativeRegion)






```mermaid
 classDiagram
    class KwgoAdministrativeRegion
    click KwgoAdministrativeRegion href "../KwgoAdministrativeRegion"
      GeoFeature <|-- KwgoAdministrativeRegion
        click GeoFeature href "../GeoFeature"
      

      KwgoAdministrativeRegion <|-- KwgoAdministrativeRegion0
        click KwgoAdministrativeRegion0 href "../KwgoAdministrativeRegion0"
      KwgoAdministrativeRegion <|-- KwgoAdministrativeRegion1
        click KwgoAdministrativeRegion1 href "../KwgoAdministrativeRegion1"
      KwgoAdministrativeRegion <|-- KwgoAdministrativeRegion2
        click KwgoAdministrativeRegion2 href "../KwgoAdministrativeRegion2"
      KwgoAdministrativeRegion <|-- KwgoAdministrativeRegion4
        click KwgoAdministrativeRegion4 href "../KwgoAdministrativeRegion4"
      KwgoAdministrativeRegion <|-- KwgoAdministrativeRegion5
        click KwgoAdministrativeRegion5 href "../KwgoAdministrativeRegion5"
      KwgoAdministrativeRegion <|-- KwgoAdministrativeRegion6
        click KwgoAdministrativeRegion6 href "../KwgoAdministrativeRegion6"
      
      
      
```





## Inheritance
* [GeoSpatialObject](../classes/GeoSpatialObject.md)
    * [GeoFeature](../classes/GeoFeature.md)
        * **KwgoAdministrativeRegion**
            * [KwgoAdministrativeRegion0](../classes/KwgoAdministrativeRegion0.md)
            * [KwgoAdministrativeRegion1](../classes/KwgoAdministrativeRegion1.md)
            * [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md)
            * [KwgoAdministrativeRegion4](../classes/KwgoAdministrativeRegion4.md)
            * [KwgoAdministrativeRegion5](../classes/KwgoAdministrativeRegion5.md)
            * [KwgoAdministrativeRegion6](../classes/KwgoAdministrativeRegion6.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [KwgoAdministrativeRegion](../classes/KwgoAdministrativeRegion.md) |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [KwgoAdministrativeRegion](../classes/KwgoAdministrativeRegion.md) |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [KwgoAdministrativeRegion](../classes/KwgoAdministrativeRegion.md) |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [KwgoAdministrativeRegion](../classes/KwgoAdministrativeRegion.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [KwgoAdministrativeRegion](../classes/KwgoAdministrativeRegion.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [KwgoAdministrativeRegion](../classes/KwgoAdministrativeRegion.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: kwgo_AdministrativeRegion
description: Source - Global Administrative area database (GADM) (https://gadm.org/data.html)
title: Administrative Region
from_schema: okns:kwg
is_a: geo_Feature
class_uri: kwgo:AdministrativeRegion

```
</details>

### Induced

<details>

```yaml
name: kwgo_AdministrativeRegion
description: Source - Global Administrative area database (GADM) (https://gadm.org/data.html)
title: Administrative Region
from_schema: okns:kwg
is_a: geo_Feature
class_uri: kwgo:AdministrativeRegion

```
</details>