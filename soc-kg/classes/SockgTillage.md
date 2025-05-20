

# Class: No class (entity type) name specified (sockg_Tillage)


_Tillage refers to the agricultural preparation of soil through mechanical agitation, including activities such as plowing, stirring, and overturning. This process is essential for seedbed preparation, incorporating organic matter, and controlling weeds in crop production._






This class occurs 27137 times.


URI: [sockg:Tillage](https://idir.uta.edu/sockg-ontology/docs/Tillage)






```mermaid
 classDiagram
    class SockgTillage
    click SockgTillage href "../SockgTillage"
      SockgTillage : rdfs_seeAlso
        
          
    
    
    SockgTillage --> "0..1" Uri : rdfs_seeAlso
    click Uri href "../Uri"

        
      SockgTillage : sockg_mgtTillage_UID
        
          
    
    
    SockgTillage --> "0..1" String : sockg_mgtTillage_UID
    click String href "../String"

        
      SockgTillage : sockg_startDate
        
          
    
    
    SockgTillage --> "0..1" Any : sockg_startDate
    click Any href "../Any"

        
      SockgTillage : sockg_tillageEvent
        
          
    
    
    SockgTillage --> "0..1" String : sockg_tillageEvent
    click String href "../String"

        
      SockgTillage : sockg_tillageEventDepth_cm
        
          
    
    
    SockgTillage --> "0..1" Double : sockg_tillageEventDepth_cm
    click Double href "../Double"

        
      SockgTillage : sockg_tillageEventMethod
        
          
    
    
    SockgTillage --> "0..1" String : sockg_tillageEventMethod
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [rdfs_seeAlso](../slots/rdfs_seeAlso.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified <br/>  | direct | 27137 |
| [sockg_tillageEventMethod](../slots/sockg_tillageEventMethod.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 24342 |
| [sockg_tillageEvent](../slots/sockg_tillageEvent.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 27137 |
| [sockg_mgtTillage_UID](../slots/sockg_mgtTillage_UID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 27137 |
| [sockg_tillageEventDepth_cm](../slots/sockg_tillageEventDepth_cm.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 26709 |
| [sockg_startDate](../slots/sockg_startDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 27137 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | [sockg_hasTillage](../slots/sockg_hasTillage.md) | range | [SockgTillage](../classes/SockgTillage.md) |
| [SockgTillage](../classes/SockgTillage.md) | [sockg_mgtTillage_UID](../slots/sockg_mgtTillage_UID.md) | domain | [SockgTillage](../classes/SockgTillage.md) |






## See Also

* [https://lod.nal.usda.gov/nalt/25207](https://lod.nal.usda.gov/nalt/25207)






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sockg_Tillage
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 27137
description: Tillage refers to the agricultural preparation of soil through mechanical
  agitation, including activities such as plowing, stirring, and overturning. This
  process is essential for seedbed preparation, incorporating organic matter, and
  controlling weeds in crop production.
title: No class (entity type) name specified
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/25207
rank: 1000
slots:
- rdfs_seeAlso
- sockg_tillageEventMethod
- sockg_tillageEvent
- sockg_mgtTillage_UID
- sockg_tillageEventDepth_cm
- sockg_startDate
slot_usage:
  rdfs_seeAlso:
    name: rdfs_seeAlso
    annotations:
      uri:
        tag: uri
        value: 27137
  sockg_mgtTillage_UID:
    name: sockg_mgtTillage_UID
    annotations:
      string:
        tag: string
        value: 27137
  sockg_startDate:
    name: sockg_startDate
    annotations:
      string:
        tag: string
        value: 27137
  sockg_tillageEvent:
    name: sockg_tillageEvent
    annotations:
      string:
        tag: string
        value: 27137
  sockg_tillageEventDepth_cm:
    name: sockg_tillageEventDepth_cm
    annotations:
      double:
        tag: double
        value: 26709
  sockg_tillageEventMethod:
    name: sockg_tillageEventMethod
    annotations:
      string:
        tag: string
        value: 24342
class_uri: sockg:Tillage

```
</details>

### Induced

<details>

```yaml
name: sockg_Tillage
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 27137
description: Tillage refers to the agricultural preparation of soil through mechanical
  agitation, including activities such as plowing, stirring, and overturning. This
  process is essential for seedbed preparation, incorporating organic matter, and
  controlling weeds in crop production.
title: No class (entity type) name specified
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/25207
rank: 1000
slot_usage:
  rdfs_seeAlso:
    name: rdfs_seeAlso
    annotations:
      uri:
        tag: uri
        value: 27137
  sockg_mgtTillage_UID:
    name: sockg_mgtTillage_UID
    annotations:
      string:
        tag: string
        value: 27137
  sockg_startDate:
    name: sockg_startDate
    annotations:
      string:
        tag: string
        value: 27137
  sockg_tillageEvent:
    name: sockg_tillageEvent
    annotations:
      string:
        tag: string
        value: 27137
  sockg_tillageEventDepth_cm:
    name: sockg_tillageEventDepth_cm
    annotations:
      double:
        tag: double
        value: 26709
  sockg_tillageEventMethod:
    name: sockg_tillageEventMethod
    annotations:
      string:
        tag: string
        value: 24342
attributes:
  rdfs_seeAlso:
    name: rdfs_seeAlso
    annotations:
      uri:
        tag: uri
        value: 27137
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: https://lod.nal.usda.gov/nalt/4605
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/0
        example_subject_type: sockg_Amendment
    - object:
        example_object: https://lod.nal.usda.gov/nalt/5859
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/100000
        example_subject_type: sockg_GasSample
    - object:
        example_object: https://lod.nal.usda.gov/nalt/281219
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/163960
        example_subject_type: sockg_Grazing
    - object:
        example_object: https://lod.nal.usda.gov/nalt/4377260
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/170955
        example_subject_type: sockg_GrazingManagementEvent
    - object:
        example_object: https://lod.nal.usda.gov/nalt/131626
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/172906
        example_subject_type: sockg_Harvest
    - object:
        example_object: https://lod.nal.usda.gov/nalt/281219
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/191262
        example_subject_type: sockg_HarvestFraction
    - object:
        example_object: https://lod.nal.usda.gov/nalt/13189
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/203523
        example_subject_type: sockg_Organization
    - object:
        example_object: https://lod.nal.usda.gov/nalt/3927
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/203632
        example_subject_type: sockg_Pesticide
    - object:
        example_object: https://lod.nal.usda.gov/nalt/849
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/227674
        example_subject_type: sockg_ResidueManagementEvent
    - object:
        example_object: https://lod.nal.usda.gov/nalt/30158
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/230982
        example_subject_type: sockg_Rotation
    - object:
        example_object: https://lod.nal.usda.gov/nalt/302328
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/231056
        example_subject_type: sockg_Site
    - object:
        example_object: https://lod.nal.usda.gov/nalt/2726
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/235229
        example_subject_type: sockg_SoilBiologicalSample
    - object:
        example_object: https://lod.nal.usda.gov/nalt/7974
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/253451
        example_subject_type: sockg_SoilChemicalSample
    - object:
        example_object: https://lod.nal.usda.gov/nalt/302328
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/307284
        example_subject_type: sockg_SoilCover
    - object:
        example_object: https://lod.nal.usda.gov/nalt/5143
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/308318
        example_subject_type: sockg_SoilPhysicalSample
    - object:
        example_object: https://lod.nal.usda.gov/nalt/5430914
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/336400
        example_subject_type: sockg_State
    - object:
        example_object: https://lod.nal.usda.gov/nalt/7140
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/336419
        example_subject_type: sockg_Tillage
    - object:
        example_object: https://lod.nal.usda.gov/nalt/28616
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/363556
        example_subject_type: sockg_Treatment
    - object:
        example_object: https://lod.nal.usda.gov/nalt/2717
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/37796
        example_subject_type: sockg_BioMassCarbohydrate
    - object:
        example_object: https://lod.nal.usda.gov/nalt/7140
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/39163
        example_subject_type: sockg_BioMassEnergy
    - object:
        example_object: https://lod.nal.usda.gov/nalt/281219
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/39962
        example_subject_type: sockg_BioMassMineral
    - object:
        example_object: https://lod.nal.usda.gov/nalt/2714
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/439235
        example_subject_type: sockg_WeatherObservation
    - object:
        example_object: https://lod.nal.usda.gov/nalt/7485997
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/46864
        example_subject_type: sockg_City
    - object:
        example_object: https://lod.nal.usda.gov/nalt/2217129
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/46904
        example_subject_type: sockg_County
    - object:
        example_object: https://lod.nal.usda.gov/nalt/302328
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/46937
        example_subject_type: sockg_CropGrowthStage
    - object:
        example_object: https://lod.nal.usda.gov/nalt/976
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/51906
        example_subject_type: sockg_Experiment
    - object:
        example_object: https://lod.nal.usda.gov/nalt/9183
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/51937
        example_subject_type: sockg_ExperimentalUnit
    - object:
        example_object: https://lod.nal.usda.gov/nalt/7259
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/55800
        example_subject_type: sockg_Field
    - object:
        example_object: https://lod.nal.usda.gov/nalt/7140
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/200732
        example_subject_type: sockg_NutrientEfficiency
    - object:
        example_object: https://lod.nal.usda.gov/nalt/35067
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/203534
        example_subject_type: sockg_Person
    - object:
        example_object: https://lod.nal.usda.gov/nalt/5630
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/203988
        example_subject_type: sockg_PlantingEvent
    - object:
        example_object: https://lod.nal.usda.gov/nalt/61097
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/227438
        example_subject_type: sockg_Project
    - object:
        example_object: https://lod.nal.usda.gov/nalt/305490
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/227447
        example_subject_type: sockg_Publication
    - object:
        example_object: https://lod.nal.usda.gov/nalt/48678
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/227609
        example_subject_type: sockg_ResearchUnit
    - object:
        example_object: https://lod.nal.usda.gov/nalt/33020
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/231116
        example_subject_type: sockg_Soil
    - object:
        example_object: https://lod.nal.usda.gov/nalt/7140
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/364326
        example_subject_type: sockg_WaterQualityArea
    - object:
        example_object: https://lod.nal.usda.gov/nalt/281219
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/364993
        example_subject_type: sockg_WaterQualityConc
    - object:
        example_object: https://lod.nal.usda.gov/nalt/7259
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/513777
        example_subject_type: sockg_WeatherStation
    - object:
        example_object: https://lod.nal.usda.gov/nalt/281219
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/55858
        example_subject_type: sockg_GasNutrientLoss
    - object:
        example_object: https://lod.nal.usda.gov/nalt/281219
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/624572
        example_subject_type: sockg_WindErosionArea
    - object:
        example_object: https://lod.nal.usda.gov/nalt/7140
        example_object_type: uri
        example_predicate: rdfs:seeAlso
        example_subject: sockg:individuals/624587
        example_subject_type: sockg_YieldNutrientUptake
    from_schema: soc-kg
    rank: 1000
    slot_uri: rdfs:seeAlso
    alias: rdfs_seeAlso
    owner: sockg_Tillage
    domain_of:
    - sockg_Amendment
    - sockg_BioMassCarbohydrate
    - sockg_BioMassEnergy
    - sockg_BioMassMineral
    - sockg_City
    - sockg_County
    - sockg_CropGrowthStage
    - sockg_Experiment
    - sockg_ExperimentalUnit
    - sockg_Field
    - sockg_GasNutrientLoss
    - sockg_GasSample
    - sockg_Grazing
    - sockg_GrazingManagementEvent
    - sockg_Harvest
    - sockg_HarvestFraction
    - sockg_NutrientEfficiency
    - sockg_Organization
    - sockg_Person
    - sockg_Pesticide
    - sockg_PlantingEvent
    - sockg_Project
    - sockg_Publication
    - sockg_ResearchUnit
    - sockg_ResidueManagementEvent
    - sockg_Rotation
    - sockg_Site
    - sockg_Soil
    - sockg_SoilBiologicalSample
    - sockg_SoilChemicalSample
    - sockg_SoilCover
    - sockg_SoilPhysicalSample
    - sockg_State
    - sockg_Tillage
    - sockg_Treatment
    - sockg_WaterQualityArea
    - sockg_WaterQualityConc
    - sockg_WeatherObservation
    - sockg_WeatherStation
    - sockg_WindErosionArea
    - sockg_YieldNutrientUptake
    range: uri
  sockg_tillageEventMethod:
    name: sockg_tillageEventMethod
    annotations:
      string:
        tag: string
        value: 24342
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Tandem Disk
        example_object_type: string
        example_predicate: sockg:tillageEventMethod
        example_subject: sockg:individuals/336419
        example_subject_type: sockg_Tillage
    from_schema: soc-kg
    rank: 1000
    slot_uri: sockg:tillageEventMethod
    alias: sockg_tillageEventMethod
    owner: sockg_Tillage
    domain_of:
    - sockg_Tillage
    range: string
  sockg_tillageEvent:
    name: sockg_tillageEvent
    annotations:
      string:
        tag: string
        value: 27137
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Disk
        example_object_type: string
        example_predicate: sockg:tillageEvent
        example_subject: sockg:individuals/336419
        example_subject_type: sockg_Tillage
    from_schema: soc-kg
    rank: 1000
    slot_uri: sockg:tillageEvent
    alias: sockg_tillageEvent
    owner: sockg_Tillage
    domain_of:
    - sockg_Tillage
    range: string
  sockg_mgtTillage_UID:
    name: sockg_mgtTillage_UID
    annotations:
      string:
        tag: string
        value: 27137
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: AgCros_NEMLTCRS_105N_1987-04-30_Zea_mays_Corn_
        example_object_type: string
        example_predicate: sockg:mgtTillage_UID
        example_subject: sockg:individuals/336419
        example_subject_type: sockg_Tillage
    from_schema: soc-kg
    rank: 1000
    domain: sockg_Tillage
    slot_uri: sockg:mgtTillage_UID
    alias: sockg_mgtTillage_UID
    owner: sockg_Tillage
    domain_of:
    - sockg_Tillage
    range: string
  sockg_tillageEventDepth_cm:
    name: sockg_tillageEventDepth_cm
    annotations:
      double:
        tag: double
        value: 26709
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '15.0'
        example_object_type: double
        example_predicate: sockg:tillageEventDepth_cm
        example_subject: sockg:individuals/336419
        example_subject_type: sockg_Tillage
    from_schema: soc-kg
    rank: 1000
    slot_uri: sockg:tillageEventDepth_cm
    alias: sockg_tillageEventDepth_cm
    owner: sockg_Tillage
    domain_of:
    - sockg_Tillage
    range: double
  sockg_startDate:
    name: sockg_startDate
    annotations:
      string:
        tag: string
        value: 27137
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: '2012-06-05'
        example_object_type: string
        example_predicate: sockg:startDate
        example_subject: sockg:individuals/0
        example_subject_type: sockg_Amendment
    - object:
        example_object: '2006-05-08'
        example_object_type: string
        example_predicate: sockg:startDate
        example_subject: sockg:individuals/170955
        example_subject_type: sockg_GrazingManagementEvent
    - object:
        example_object: '1987-04-30'
        example_object_type: string
        example_predicate: sockg:startDate
        example_subject: sockg:individuals/336419
        example_subject_type: sockg_Tillage
    - object:
        example_object: '2007-04-01'
        example_object_type: string
        example_predicate: sockg:startDate
        example_subject: sockg:individuals/51906
        example_subject_type: sockg_Experiment
    - object:
        example_object: '2009-01-01'
        example_object_type: string
        example_predicate: sockg:startDate
        example_subject: sockg:individuals/51937
        example_subject_type: sockg_ExperimentalUnit
    - object:
        example_object: '2004-11-04'
        example_object_type: string
        example_predicate: sockg:startDate
        example_subject: sockg:individuals/203988
        example_subject_type: sockg_PlantingEvent
    from_schema: soc-kg
    see_also:
    - https://lod.nal.usda.gov/nalt/9183
    rank: 1000
    slot_uri: sockg:startDate
    alias: sockg_startDate
    owner: sockg_Tillage
    domain_of:
    - sockg_Amendment
    - sockg_Experiment
    - sockg_ExperimentalUnit
    - sockg_GrazingManagementEvent
    - sockg_PlantingEvent
    - sockg_Tillage
    union_of:
    - '{''domain'': ''sockg_ExperimentalUnit''}'
    - '{''domain'': ''sockg_GrazingManagementEvent''}'
    - '{''domain'': ''sockg_WeatherStation''}'
    - '{''domain'': ''sockg_Experiment''}'
    - '{''domain'': ''sockg_Amendment''}'
    range: Any
    any_of:
    - range: date
    - range: string
class_uri: sockg:Tillage

```
</details>