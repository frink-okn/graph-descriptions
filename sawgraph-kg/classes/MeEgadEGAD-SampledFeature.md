

# Class: EGAD - Sampled Feature (me_egad_EGAD-SampledFeature)


_No class (type) description specified_






This class occurs 8040 times.


URI: [me_egad:EGAD-SampledFeature](http://sawgraph.spatialai.org/v1/me-egad#EGAD-SampledFeature)






```mermaid
 classDiagram
    class MeEgadEGAD-SampledFeature
    click MeEgadEGAD-SampledFeature href "../MeEgadEGAD-SampledFeature"
      CosoSampledFeature <|-- MeEgadEGAD-SampledFeature
        click CosoSampledFeature href "../CosoSampledFeature"
      
      MeEgadEGAD-SampledFeature : me_egad_sampledFeatureType
        
          
    
    
    MeEgadEGAD-SampledFeature --> "0..1" Any : me_egad_sampledFeatureType
    click Any href "../Any"

        
      MeEgadEGAD-SampledFeature : rdfs_label
        
          
    
    
    MeEgadEGAD-SampledFeature --> "0..1" String : rdfs_label
    click String href "../String"

        
      
```





## Inheritance
* [CosoSampledFeature](../classes/CosoSampledFeature.md)
    * **MeEgadEGAD-SampledFeature**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [me_egad_sampledFeatureType](../slots/me_egad_sampledFeatureType.md) | 0..1 <br/> [MeEgadEGAD-SamplePointType](../classes/MeEgadEGAD-SamplePointType.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No slot (predicate) description specified <br/>  | direct | 16042 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 8040 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_hasFeatureOfInterest](../slots/coso_hasFeatureOfInterest.md) | any_of[range] | [MeEgadEGAD-SampledFeature](../classes/MeEgadEGAD-SampledFeature.md) |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | [coso_pointFromFeature](../slots/coso_pointFromFeature.md) | any_of[range] | [MeEgadEGAD-SampledFeature](../classes/MeEgadEGAD-SampledFeature.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: me_egad_EGAD-SampledFeature
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 8040
description: No class (type) description specified
title: EGAD - Sampled Feature
from_schema: sawgraph-kg
rank: 1000
is_a: coso_SampledFeature
slots:
- me_egad_sampledFeatureType
- rdfs_label
slot_usage:
  me_egad_sampledFeatureType:
    name: me_egad_sampledFeatureType
    annotations:
      me_egad_EGAD-SamplePointType:
        tag: me_egad_EGAD-SamplePointType
        value: 8021
      owl_NamedIndividual:
        tag: owl_NamedIndividual
        value: 8021
  rdfs_label:
    name: rdfs_label
    annotations:
      string:
        tag: string
        value: 8040
class_uri: me_egad:EGAD-SampledFeature

```
</details>

### Induced

<details>

```yaml
name: me_egad_EGAD-SampledFeature
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 8040
description: No class (type) description specified
title: EGAD - Sampled Feature
from_schema: sawgraph-kg
rank: 1000
is_a: coso_SampledFeature
slot_usage:
  me_egad_sampledFeatureType:
    name: me_egad_sampledFeatureType
    annotations:
      me_egad_EGAD-SamplePointType:
        tag: me_egad_EGAD-SamplePointType
        value: 8021
      owl_NamedIndividual:
        tag: owl_NamedIndividual
        value: 8021
  rdfs_label:
    name: rdfs_label
    annotations:
      string:
        tag: string
        value: 8040
attributes:
  me_egad_sampledFeatureType:
    name: me_egad_sampledFeatureType
    annotations:
      me_egad_EGAD-SamplePointType:
        tag: me_egad_EGAD-SamplePointType
        value: 8021
      owl_NamedIndividual:
        tag: owl_NamedIndividual
        value: 8021
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: me_egad_data:featureType.MW
        example_object_type: me_egad_EGAD-SamplePointType
        example_predicate: me_egad:sampledFeatureType
        example_subject: me_egad_data:sampledFeature.100410
        example_subject_type: me_egad_EGAD-SampledFeature
    - object:
        example_object: me_egad_data:featureType.MW
        example_object_type: owl_NamedIndividual
        example_predicate: me_egad:sampledFeatureType
        example_subject: me_egad_data:sampledFeature.100410
        example_subject_type: me_egad_EGAD-SampledFeature
    from_schema: sawgraph-kg
    rank: 1000
    slot_uri: me_egad:sampledFeatureType
    alias: me_egad_sampledFeatureType
    owner: me_egad_EGAD-SampledFeature
    domain_of:
    - me_egad_EGAD-SampledFeature
    range: Any
    any_of:
    - range: me_egad_EGAD-SamplePointType
    - range: owl_NamedIndividual
  rdfs_label:
    name: rdfs_label
    annotations:
      string:
        tag: string
        value: 8040
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Microgram per Kilogram
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: http://qudt.org/vocab/unit/MicroGM-PER-KiloGM
        example_subject_type: qudt_Unit
    - object:
        example_object: AB
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: me_egad_data:AB
        example_subject_type: prov_Agent
    - object:
        example_object: COMPOUND IS FOUND IN THE ASSOCIATED METHOD BLANK (ORGANIC)
          OR THE REPORTED VALUE WAS LESS THAN THE REPORTING LIMIT BUT GREATER THAN
          OR EQUAL TO THE IDL. (INORGANIC)
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: me_egad_data:concentrationQualifier.B
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: ALPHA ANALYTICAL LAB - WESTBOROUGH, MA
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: me_egad_data:organization.lab.AA
        example_subject_type: prov_Organization
    - object:
        example_object: EGAD PFAS measurements for sample EP001
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: me_egad_data:result.101365P.NA.20130507.1763231
        example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
    - object:
        example_object: EGAD PFAS measurements for sample EP001
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: me_egad_data:result.101365P.NA.20130507.DEP18010
        example_subject_type: me_egad_EGAD-AggregatePFAS-Concentration
    - object:
        example_object: EGAD sample BETH WILLIAMS ACF
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: me_egad_data:sample.AAL210144001R.20210112
        example_subject_type: me_egad_EGAD-Sample
    - object:
        example_object: EGAD sample point 100410
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: me_egad_data:samplePoint.100410
        example_subject_type: me_egad_EGAD-SamplePoint
    - object:
        example_object: EGAD sampled feature associated with sample point 100410
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: me_egad_data:sampledFeature.100410
        example_subject_type: me_egad_EGAD-SampledFeature
    - object:
        example_object: MAINE ARMY NATIONAL GUARD - BANGOR RANGE
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: me_egad_data:site.100843
        example_subject_type: me_egad_EGAD-Site
    - object:
        example_object: FARMINGTON VILLAGE CORPORATION
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: me_egad_data:site.131980
        example_subject_type: me_egad_EGAD-PFAS-Site
    - object:
        example_object: Single Contamiant Concentration Quantity
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: coso:SingleContaminantConcentrationQuantityKind
        example_subject_type: coso_ContaminantConcentrationQuantityKind
    - object:
        example_object: Non-Detect
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: coso:non-detect
        example_subject_type: qudt_EnumeratedValue
    - object:
        example_object: Enumerated Quantity
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: qudt:EnumeratedQuantity
        example_subject_type: None
    - object:
        example_object: EGAD PFAS observation for sample BETH WILLIAMS ACF
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
        example_subject_type: me_egad_EGAD-PFAS-Observation
    from_schema: sawgraph-kg
    rank: 1000
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: me_egad_EGAD-SampledFeature
    domain_of:
    - owl_NamedIndividual
    - owl_OntologyProperty
    - qudt_AspectClass
    - qudt_BitEncodingType
    - qudt_BooleanEncodingType
    - qudt_ByteEncodingType
    - qudt_CardinalityType
    - qudt_CharEncodingType
    - qudt_DateTimeStringEncodingType
    - qudt_EndianType
    - qudt_EnumeratedValue
    - qudt_FloatingPointEncodingType
    - qudt_IntegerEncodingType
    - qudt_OrderedType
    - qudt_SignednessType
    - qudt_Unit
    - vaem_#CatalogEntry
    - vaem_#GraphMetaData
    - vaem_#Party
    - coso_ContaminantConcentrationQuantityKind
    - coso_ContaminantVolumeQuantityKind
    - coso_Substance
    - coso_SubstanceCollection
    - me_egad_EGAD-AggregatePFAS-Concentration
    - me_egad_EGAD-AnalysisMethod
    - me_egad_EGAD-ConcentrationQualifier
    - me_egad_EGAD-PFAS-Observation
    - me_egad_EGAD-PFAS-ParameterName
    - me_egad_EGAD-PFAS-Site
    - me_egad_EGAD-ResultType
    - me_egad_EGAD-Sample
    - me_egad_EGAD-SampleCollectionMethod
    - me_egad_EGAD-SampleDetailedLocation
    - me_egad_EGAD-SampleMaterialType
    - me_egad_EGAD-SampleMaterialTypeQualifier
    - me_egad_EGAD-SamplePoint
    - me_egad_EGAD-SamplePointType
    - me_egad_EGAD-SampleTreatmentStatus
    - me_egad_EGAD-SampledFeature
    - me_egad_EGAD-SinglePFAS-Concentration
    - me_egad_EGAD-Site
    - me_egad_EGAD-SiteType
    - me_egad_EGAD-ValidationLevel
    - prov_Agent
    - prov_Organization
    range: string
class_uri: me_egad:EGAD-SampledFeature

```
</details>