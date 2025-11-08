

# Class: EGAD - Reporting Limit (http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit)




This class occurs 4480 times.


URI: [http://w3id.org/sawgraph/v1/me-egad#EGAD-ReportingLimit](http://w3id.org/sawgraph/v1/me-egad#EGAD-ReportingLimit)






```mermaid
 classDiagram
    class HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit
    click HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit
        click OwlThing href "../OwlThing"
      
      HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit : owl_sameAs
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit --> "0..1" OwlThing : owl_sameAs
    click OwlThing href "../OwlThing"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit : qudt_hasUnit
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit --> "0..1" Any : qudt_hasUnit
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit : qudt_numericValue
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit --> "0..1" QudtNumericUnion : qudt_numericValue
    click QudtNumericUnion href "../QudtNumericUnion"

        
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * **HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [qudt_hasUnit](../slots/qudt_hasUnit.md) | 0..1 <br/> [QudtUnit](../classes/QudtUnit.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[QudtContextualUnit](../classes/QudtContextualUnit.md)&nbsp;or&nbsp;<br />[QudtLogarithmicUnit](../classes/QudtLogarithmicUnit.md)&nbsp;or&nbsp;<br />[QudtCurrencyUnit](../classes/QudtCurrencyUnit.md)&nbsp;or&nbsp;<br />[QudtDerivedUnit](../classes/QudtDerivedUnit.md)&nbsp;or&nbsp;<br />[QudtCountingUnit](../classes/QudtCountingUnit.md) | This property relates a factor unit its unit <br/> description: This property relates a factor unit to its unit or a system of units with a unit of measure that is either a) defined by the system, or b) accepted for use by the system and is convertible to a unit of equivalent dimension that is defined by the system. Systems of units may distinguish between base and derived units. Base units are the units which measure the base quantities for the corresponding system of quantities. The base units are used to define units for all other quantities as products of powers of the base units. Such units are called derived units for the system.<br/>title: hasUnit | direct | 8960 |
| [qudt_numericValue](../slots/qudt_numericValue.md) | 0..1 <br/> [QudtNumericUnion](../types/QudtNumericUnion.md) |  <br/>  | direct | 4480 |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md) | The property that determines that two given individuals are equal <br/>  | direct | 4480 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) | [coso_resultAnnotation](../slots/coso_resultAnnotation.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#reportingLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#reportingLimit.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) | [coso_resultAnnotation](../slots/coso_resultAnnotation.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#reportingLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#reportingLimit.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md) |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [coso_resultAnnotation](../slots/coso_resultAnnotation.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [coso_resultAnnotation](../slots/coso_resultAnnotation.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
title: EGAD - Reporting Limit
from_schema: okns:sawgraph-kg
rank: 1000
is_a: owl_Thing
slots:
- qudt_hasUnit
- qudt_numericValue
- owl_sameAs
class_uri: http://w3id.org/sawgraph/v1/me-egad#EGAD-ReportingLimit

```
</details>

### Induced

<details>

```yaml
name: http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
title: EGAD - Reporting Limit
from_schema: okns:sawgraph-kg
rank: 1000
is_a: owl_Thing
attributes:
  qudt_hasUnit:
    name: qudt_hasUnit
    description: This property relates a factor unit its unit
    title: has unit
    comments:
    - 'description: This property relates a factor unit to its unit or a system of
      units with a unit of measure that is either a) defined by the system, or b)
      accepted for use by the system and is convertible to a unit of equivalent dimension
      that is defined by the system. Systems of units may distinguish between base
      and derived units. Base units are the units which measure the base quantities
      for the corresponding system of quantities. The base units are used to define
      units for all other quantities as products of powers of the base units. Such
      units are called derived units for the system.'
    - 'title: hasUnit'
    from_schema: okns:qudt
    source: http://qudt.org/schema/qudt
    slot_uri: qudt:hasUnit
    alias: qudt_hasUnit
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
    domain_of:
    - coso_DetectQuantityValue
    - coso_NonDetectQuantityValue
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-MethodDetectionLimit
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
    - http___w3id.org_sawgraph_v1_us-wqp#InstrumentDetectionLevel
    - http___w3id.org_sawgraph_v1_us-wqp#LaboratoryReportingLevel
    - http___w3id.org_sawgraph_v1_us-wqp#LowerQuantitationLimit
    - http___w3id.org_sawgraph_v1_us-wqp#LowerReportingLimit
    - http___w3id.org_sawgraph_v1_us-wqp#MethodDetectionLevel
    - http___w3id.org_sawgraph_v1_us-wqp#Sample-SpecificQuantitationLimit
    - me_egad_EGAD-MethodDetectionLimit
    - me_egad_EGAD-ReportingLimit
    range: Any
    any_of:
    - range: qudt_Unit
    - range: uri
    - range: qudt_ContextualUnit
    - range: qudt_LogarithmicUnit
    - range: qudt_CurrencyUnit
    - range: qudt_DerivedUnit
    - range: qudt_CountingUnit
  qudt_numericValue:
    name: qudt_numericValue
    title: numeric value
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:qudt
    source: http://qudt.org/schema/qudt
    slot_uri: qudt:numericValue
    alias: qudt_numericValue
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
    domain_of:
    - coso_DetectQuantityValue
    - coso_NonDetectQuantityValue
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-MethodDetectionLimit
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
    - http___w3id.org_sawgraph_v1_us-wqp#InstrumentDetectionLevel
    - http___w3id.org_sawgraph_v1_us-wqp#LaboratoryReportingLevel
    - http___w3id.org_sawgraph_v1_us-wqp#LowerQuantitationLimit
    - http___w3id.org_sawgraph_v1_us-wqp#LowerReportingLimit
    - http___w3id.org_sawgraph_v1_us-wqp#MethodDetectionLevel
    - http___w3id.org_sawgraph_v1_us-wqp#Sample-SpecificQuantitationLimit
    - me_egad_EGAD-MethodDetectionLimit
    - me_egad_EGAD-ReportingLimit
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
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
    domain_of:
    - __B00af777bec4da87c5aebb51d94b2d478
    - __B036a3008450d6ce37e35cf5a98355a60
    - __B085dcda89ed6aae0d3b229e767f0a1ca
    - __B0d427a711311f1499a234aa8af2c66d1
    - __B215b3a432e1c482d3680398a554edbbf
    - __B27231c83f17c76e178e0c9f5e10acc55
    - __B37977f50d3140da51a9630b8a57396a1
    - __B3cc7b3721547b07a4068dc98b6444b8b
    - __B423a0e253807f20386fc3ccbbd7e0378
    - __B44bec873efc8b96cad5f525429c64e0a
    - __B4fd286b2a5a12e342d61412628b6e4c2
    - __B53622dee107de372b2d0566f64ab6e3a
    - __B5e93e815b548435105d9273d424fa0e8
    - __B611b8dff312692e7f32a69834c787a60
    - __B623b56ef58fd82dd088819e22d655c08
    - __B75dbc5841338872cea35dced609fcd77
    - __B75e45ed04b2b903b9029968cada06faa
    - __B7728f65369357f97de36b133c9d1d5e0
    - __B8aa8791a0418cd594c8b56ad21351f72
    - __Ba6d85f816540f9fec5b71ba42fc2cca6
    - __Ba76635ffb4afc02e78b9ef49973d089f
    - __Bb0125be5bc4dc7be7e8452e7d22445f6
    - __Bb71af62f2f3e5e5b5e0fe81f24eca409
    - __Bbefc37cbdd03cae92dadef76b34dbf16
    - __Bbf63deb85414ddecd89e46bce27e7f0a
    - __Be047d68edc8eb3ce96d7edbad5217bfc
    - __Be497d3b0c2656040c05e303873a2d541
    - __Beb7217b5b32080b9606028314249e33b
    - __Beb77c26f8c395403edc359fd5f6dfb28
    - __Bf04685c17c0e71ae3c98e08c75cbdfcc
    - __Bf584e1bfd1c74de0eb37e7b926538b83
    - coso_AnimalBloodSample
    - coso_AnimalMaterialSample
    - coso_AnimalMilkSample
    - coso_AnimalOrganSample
    - coso_AnimalTissueSample
    - coso_ContaminantConcentrationQuantityKind
    - coso_ContaminantVolumeQuantityKind
    - coso_ContaminationProperty
    - coso_DetectQuantityValue
    - coso_NonDetectQuantityValue
    - coso_PlantMaterialSample
    - coso_SubstanceCollection
    - coso_WaterSample
    - http___w3id.org_comptox_CompTox_ChemicalEntity
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AnalysisMethod
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-ConcentrationQualifier
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-MethodDetectionLimit
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-ParameterName
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Site
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-ResultType
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleCollectionMethod
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleDetailedLocation
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleMaterialType
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleMaterialTypeQualifier
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePointType
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleTreatmentStatus
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SampledFeature
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SiteType
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-ValidationLevel
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
    - kwgo_S2Cell_Level13
    - me_egad_EGAD-AggregatePFAS-Concentration
    - me_egad_EGAD-AnalysisMethod
    - me_egad_EGAD-ConcentrationQualifier
    - me_egad_EGAD-MethodDetectionLimit
    - me_egad_EGAD-PFAS-Observation
    - me_egad_EGAD-PFAS-ParameterName
    - me_egad_EGAD-PFAS-Site
    - me_egad_EGAD-ReportingLimit
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
    - me_egad_EGAD-SiteType
    - me_egad_EGAD-ValidationLevel
    - obo_FOODON_00001093
    - obo_FOODON_00002165
    - obo_FOODON_00002477
    - obo_FOODON_00003042
    - obo_FOODON_00003083
    - obo_FOODON_00003425
    - obo_FOODON_00003572
    - obo_FOODON_00004172
    - obo_FOODON_00004436
    - obo_FOODON_00004460
    - obo_FOODON_02010012
    - obo_FOODON_02010015
    - obo_FOODON_02010032
    - obo_FOODON_02010042
    - obo_FOODON_02010045
    - obo_FOODON_02010107
    - obo_FOODON_02020840
    - obo_FOODON_02020892
    - obo_FOODON_02021651
    - obo_FOODON_02021803
    - obo_FOODON_02021805
    - obo_FOODON_03301761
    - obo_FOODON_03411057
    - obo_FOODON_03411183
    - obo_FOODON_03411236
    - obo_FOODON_03411324
    - obo_FOODON_03411325
    - obo_FOODON_03411328
    - obo_FOODON_03411457
    - obo_FOODON_03411566
    - obo_FOODON_03411583
    - obo_FOODON_03411669
    - obo_FOODON_03413358
    - obo_FOODON_03413378
    - obo_FOODON_03420116
    - obo_FOODON_03420147
    - obo_FOODON_03420150
    - obo_FOODON_03420181
    - obo_FOODON_03420194
    - obo_NCBITaxon_147949
    - obo_NCBITaxon_27706
    - obo_NCBITaxon_381124
    - obo_NCBITaxon_8010
    - obo_NCBITaxon_8038
    - obo_NCBITaxon_8182
    - stad_QualityKind
    - stad_StatisticalQuantityKind
    range: owl_Thing
class_uri: http://w3id.org/sawgraph/v1/me-egad#EGAD-ReportingLimit

```
</details>