

# Class: HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration




This class occurs 539086 times.


URI: [http://w3id.org/sawgraph/v1/me-egad#EGAD-SinglePFAS-Concentration](http://w3id.org/sawgraph/v1/me-egad#EGAD-SinglePFAS-Concentration)






```mermaid
 classDiagram
    class HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration
    click HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration"
      SosaResult <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration
        click SosaResult href "../SosaResult"
      
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : coso_measurementUnit
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" Any : coso_measurementUnit
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : coso_measurementValue
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" Any : coso_measurementValue
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : coso_resultAnnotation
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" Any : coso_resultAnnotation
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : http___w3id.org_sawgraph_v1_me_egad#labQualifier
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" Any : http___w3id.org_sawgraph_v1_me_egad#labQualifier
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" Any : http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : http___w3id.org_sawgraph_v1_me_egad#reportingLimit
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" Any : http___w3id.org_sawgraph_v1_me_egad#reportingLimit
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : http___w3id.org_sawgraph_v1_me_egad#validationLevel
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" Any : http___w3id.org_sawgraph_v1_me_egad#validationLevel
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : http___w3id.org_sawgraph_v1_me_egad#validationQualifier
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" Any : http___w3id.org_sawgraph_v1_me_egad#validationQualifier
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : owl_sameAs
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" OwlThing : owl_sameAs
    click OwlThing href "../OwlThing"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : qudt_hasQuantityKind
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" Any : qudt_hasQuantityKind
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : qudt_quantityValue
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" QudtQuantityValue : qudt_quantityValue
    click QudtQuantityValue href "../QudtQuantityValue"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : rdfs_label
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration : stad_hasQualityKind
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration --> "0..1" Any : stad_hasQualityKind
    click Any href "../Any"

        
      
```





## Inheritance
* [SosaResult](../classes/SosaResult.md)
    * **HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [coso_resultAnnotation](../slots/coso_resultAnnotation.md) | 0..1 <br/> [MeEgadEGAD-ConcentrationQualifier](../classes/MeEgadEGAD-ConcentrationQualifier.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-MethodDetectionLimit](../classes/MeEgadEGAD-MethodDetectionLimit.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ValidationLevel](../classes/MeEgadEGAD-ValidationLevel.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ReportingLimit](../classes/MeEgadEGAD-ReportingLimit.md) | A relation between a result and additional metadata about the result <br/>  | direct | 3280330 |
| [coso_measurementValue](../slots/coso_measurementValue.md) | 0..1 <br/> [xsd:decimal](http://www.w3.org/2001/XMLSchema#decimal)&nbsp;or&nbsp;<br />[QudtEnumeratedValue](../classes/QudtEnumeratedValue.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[QudtConcept](../classes/QudtConcept.md)&nbsp;or&nbsp;<br />[QudtVerifiable](../classes/QudtVerifiable.md) | The numeric value or enumerated value that quantifies or qualifies the result <br/>  | direct | 1387183 |
| [http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit.md) | 0..1 <br/> [CosoResultQualifier](../classes/CosoResultQualifier.md)&nbsp;or&nbsp;<br />[CosoDetectionLimit](../classes/CosoDetectionLimit.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit.md)&nbsp;or&nbsp;<br />[QudtQuantifiable](../classes/QudtQuantifiable.md)&nbsp;or&nbsp;<br />[QudtQuantity](../classes/QudtQuantity.md)&nbsp;or&nbsp;<br />[QudtConcept](../classes/QudtConcept.md)&nbsp;or&nbsp;<br />[StadDatapoint](../classes/StadDatapoint.md) |  <br/>  | direct | 540043 |
| [qudt_hasQuantityKind](../slots/qudt_hasQuantityKind.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[QudtQuantityKind](../classes/QudtQuantityKind.md) |  <br/>  | direct | 1078172 |
| [http___w3id.org_sawgraph_v1_me_egad#validationQualifier](../slots/http___w3id.org_sawgraph_v1_me_egad#validationQualifier.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier.md) |  <br/>  | direct | 954611 |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md) | The property that determines that two given individuals are equal <br/>  | direct | 539086 |
| [coso_measurementUnit](../slots/coso_measurementUnit.md) | 0..1 <br/> [QudtConcept](../classes/QudtConcept.md)&nbsp;or&nbsp;<br />[QudtUnit](../classes/QudtUnit.md) | The unit of measurement the describes the result <br/>  | direct | 232464 |
| [qudt_quantityValue](../slots/qudt_quantityValue.md) | 0..1 <br/> [QudtQuantityValue](../classes/QudtQuantityValue.md) |  <br/>  | direct | 539449 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 539164 |
| [http___w3id.org_sawgraph_v1_me_egad#labQualifier](../slots/http___w3id.org_sawgraph_v1_me_egad#labQualifier.md) | 0..1 <br/> [OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier.md) |  <br/>  | direct | 928720 |
| [http___w3id.org_sawgraph_v1_me_egad#reportingLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#reportingLimit.md) | 0..1 <br/> [CosoQuantitationLimit](../classes/CosoQuantitationLimit.md)&nbsp;or&nbsp;<br />[CosoResultQualifier](../classes/CosoResultQualifier.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[QudtQuantifiable](../classes/QudtQuantifiable.md)&nbsp;or&nbsp;<br />[QudtQuantity](../classes/QudtQuantity.md)&nbsp;or&nbsp;<br />[QudtConcept](../classes/QudtConcept.md)&nbsp;or&nbsp;<br />[StadDatapoint](../classes/StadDatapoint.md) |  <br/>  | direct | 541392 |
| [stad_hasQualityKind](../slots/stad_hasQualityKind.md) | 0..1 <br/> [OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[QudtQuantityKind](../classes/QudtQuantityKind.md)&nbsp;or&nbsp;<br />[CosoContaminantConcentrationQuantityKind](../classes/CosoContaminantConcentrationQuantityKind.md)&nbsp;or&nbsp;<br />[CosoContaminationProperty](../classes/CosoContaminationProperty.md)&nbsp;or&nbsp;<br />[StadQualityKind](../classes/StadQualityKind.md) |  <br/>  | direct | 1078172 |
| [http___w3id.org_sawgraph_v1_me_egad#validationLevel](../slots/http___w3id.org_sawgraph_v1_me_egad#validationLevel.md) | 0..1 <br/> [HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md) |  <br/>  | direct | 1059080 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_hasResult](../slots/coso_hasResult.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) | [coso_hasResult](../slots/coso_hasResult.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_hasResult](../slots/coso_hasResult.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
from_schema: okns:sawgraph-kg
rank: 1000
is_a: sosa_Result
slots:
- coso_resultAnnotation
- coso_measurementValue
- http___w3id.org_sawgraph_v1_me-egad#methodDetectionLimit
- qudt_hasQuantityKind
- http___w3id.org_sawgraph_v1_me-egad#validationQualifier
- owl_sameAs
- coso_measurementUnit
- qudt_quantityValue
- rdfs_label
- http___w3id.org_sawgraph_v1_me-egad#labQualifier
- http___w3id.org_sawgraph_v1_me-egad#reportingLimit
- stad_hasQualityKind
- http___w3id.org_sawgraph_v1_me-egad#validationLevel
class_uri: http://w3id.org/sawgraph/v1/me-egad#EGAD-SinglePFAS-Concentration

```
</details>

### Induced

<details>

```yaml
name: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
from_schema: okns:sawgraph-kg
rank: 1000
is_a: sosa_Result
attributes:
  coso_resultAnnotation:
    name: coso_resultAnnotation
    description: A relation between a result and additional metadata about the result.
    title: result annotation
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: coso:resultAnnotation
    alias: coso_resultAnnotation
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    domain_of:
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    - me_egad_EGAD-AggregatePFAS-Concentration
    - me_egad_EGAD-SinglePFAS-Concentration
    range: Any
    any_of:
    - range: me_egad_EGAD-ConcentrationQualifier
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ValidationLevel
    - range: owl_NamedIndividual
    - range: me_egad_EGAD-MethodDetectionLimit
    - range: me_egad_EGAD-ValidationLevel
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
    - range: owl_Thing
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ConcentrationQualifier
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-MethodDetectionLimit
    - range: me_egad_EGAD-ReportingLimit
  coso_measurementValue:
    name: coso_measurementValue
    description: The numeric value or enumerated value that quantifies or qualifies
      the result.
    title: measurement value
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: coso:measurementValue
    alias: coso_measurementValue
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    domain_of:
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    - me_egad_EGAD-AggregatePFAS-Concentration
    - me_egad_EGAD-SinglePFAS-Concentration
    union_of:
    - sosa_Result
    - coso_ContaminantMeasurement
    - owl_Thing
    - qudt_Quantifiable
    - qudt_Quantity
    - qudt_Concept
    - stad_Datapoint
    range: Any
    any_of:
    - range: decimal
    - range: qudt_EnumeratedValue
    - range: double
    - range: qudt_Concept
    - range: qudt_Verifiable
  http___w3id.org_sawgraph_v1_me-egad#methodDetectionLimit:
    name: http___w3id.org_sawgraph_v1_me-egad#methodDetectionLimit
    title: egad - method detection limit
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: http://w3id.org/sawgraph/v1/me-egad#methodDetectionLimit
    alias: http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    domain_of:
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    subproperty_of: coso_resultAnnotation
    range: Any
    any_of:
    - range: coso_ResultQualifier
    - range: coso_DetectionLimit
    - range: owl_Thing
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-MethodDetectionLimit
    - range: qudt_Quantifiable
    - range: qudt_Quantity
    - range: qudt_Concept
    - range: stad_Datapoint
  qudt_hasQuantityKind:
    name: qudt_hasQuantityKind
    title: has quantity kind
    from_schema: okns:qudt
    source: http://qudt.org/schema/qudt
    slot_uri: qudt:hasQuantityKind
    alias: qudt_hasQuantityKind
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    domain_of:
    - qudt_ContextualUnit
    - qudt_CountingUnit
    - qudt_CurrencyUnit
    - qudt_DerivedUnit
    - qudt_DimensionlessUnit
    - qudt_LogarithmicUnit
    - qudt_Unit
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    - me_egad_EGAD-AggregatePFAS-Concentration
    - me_egad_EGAD-SinglePFAS-Concentration
    range: Any
    any_of:
    - range: uri
    - range: qudt_QuantityKind
  http___w3id.org_sawgraph_v1_me-egad#validationQualifier:
    name: http___w3id.org_sawgraph_v1_me-egad#validationQualifier
    title: egad - validation qualifier
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: http://w3id.org/sawgraph/v1/me-egad#validationQualifier
    alias: http___w3id.org_sawgraph_v1_me_egad#validationQualifier
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    domain_of:
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    subproperty_of: coso_resultAnnotation
    range: Any
    any_of:
    - range: owl_Thing
    - range: owl_NamedIndividual
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ConcentrationQualifier
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
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
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
  coso_measurementUnit:
    name: coso_measurementUnit
    description: The unit of measurement the describes the result.
    title: measurement unit
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: coso:measurementUnit
    alias: coso_measurementUnit
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    domain_of:
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    - me_egad_EGAD-AggregatePFAS-Concentration
    - me_egad_EGAD-SinglePFAS-Concentration
    union_of:
    - sosa_Result
    - coso_ContaminantMeasurement
    - owl_Thing
    - qudt_Quantifiable
    - qudt_Quantity
    - qudt_Concept
    - stad_Datapoint
    range: Any
    any_of:
    - range: qudt_Concept
    - range: qudt_Unit
  qudt_quantityValue:
    name: qudt_quantityValue
    title: quantity value
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:qudt
    source: http://qudt.org/schema/qudt
    slot_uri: qudt:quantityValue
    alias: qudt_quantityValue
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    domain_of:
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    - http___w3id.org_sawgraph_v1_us-wqp#Single-PFAS-Concentration
    - me_egad_EGAD-AggregatePFAS-Concentration
    - me_egad_EGAD-SinglePFAS-Concentration
    range: qudt_QuantityValue
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    domain_of:
    - dcam_VocabularyEncodingScheme
    - dct_AgentClass
    - sdos_ActionStatusType
    - sdos_AdultOrientedEnumeration
    - sdos_BoardingPolicyType
    - sdos_BodyMeasurementTypeEnumeration
    - sdos_BookFormatType
    - sdos_Boolean
    - sdos_CarUsageType
    - sdos_CertificationStatusEnumeration
    - sdos_ContactPointOption
    - sdos_DataType
    - sdos_DayOfWeek
    - sdos_DeliveryMethod
    - sdos_DigitalDocumentPermissionType
    - sdos_DigitalPlatformEnumeration
    - sdos_DriveWheelConfigurationValue
    - sdos_DrugCostCategory
    - sdos_DrugPregnancyCategory
    - sdos_DrugPrescriptionStatus
    - sdos_EUEnergyEfficiencyEnumeration
    - sdos_EnergyStarEnergyEfficiencyEnumeration
    - sdos_EventAttendanceModeEnumeration
    - sdos_EventStatusType
    - sdos_FulfillmentTypeEnumeration
    - sdos_GameAvailabilityEnumeration
    - sdos_GamePlayMode
    - sdos_GameServerStatus
    - sdos_GenderType
    - sdos_GovernmentBenefitsType
    - sdos_HealthAspectEnumeration
    - sdos_IPTCDigitalSourceEnumeration
    - sdos_IncentiveQualifiedExpenseType
    - sdos_IncentiveStatus
    - sdos_IncentiveType
    - sdos_InfectiousAgentClass
    - sdos_ItemAvailability
    - sdos_ItemListOrderType
    - sdos_LegalForceStatus
    - sdos_LegalValueLevel
    - sdos_MapCategoryType
    - sdos_MeasurementMethodEnum
    - sdos_MediaManipulationRatingEnumeration
    - sdos_MedicalAudienceType
    - sdos_MedicalDevicePurpose
    - sdos_MedicalEvidenceLevel
    - sdos_MedicalImagingTechnique
    - sdos_MedicalObservationalStudyDesign
    - sdos_MedicalProcedureType
    - sdos_MedicalSpecialty
    - sdos_MedicalStudyStatus
    - sdos_MedicalTrialDesign
    - sdos_MedicineSystem
    - sdos_MerchantReturnEnumeration
    - sdos_MusicAlbumProductionType
    - sdos_MusicAlbumReleaseType
    - sdos_MusicReleaseFormatType
    - sdos_NLNonprofitType
    - sdos_OfferItemCondition
    - sdos_OrderStatus
    - sdos_PaymentMethodType
    - sdos_PaymentStatusType
    - sdos_PhysicalActivityCategory
    - sdos_PhysicalExam
    - sdos_PriceComponentTypeEnumeration
    - sdos_PriceTypeEnumeration
    - sdos_ProductReturnEnumeration
    - sdos_PurchaseType
    - sdos_RefundTypeEnumeration
    - sdos_ReservationStatusType
    - sdos_RestrictedDiet
    - sdos_ReturnFeesEnumeration
    - sdos_ReturnLabelSourceEnumeration
    - sdos_ReturnMethodEnumeration
    - sdos_RsvpResponseType
    - sdos_SizeSystemEnumeration
    - sdos_SteeringPositionValue
    - sdos_TierBenefitEnumeration
    - sdos_UKNonprofitType
    - sdos_USNonprofitType
    - sdos_WearableMeasurementTypeEnumeration
    - sdos_WearableSizeGroupEnumeration
    - sdos_WearableSizeSystemEnumeration
    - rdf_List
    - rdfs_Datatype
    - qudt_AspectClass
    - qudt_BinaryPrefix
    - qudt_BitEncodingType
    - qudt_BooleanEncodingType
    - qudt_ByteEncodingType
    - qudt_CardinalityType
    - qudt_CharEncodingType
    - qudt_ContextualUnit
    - qudt_CountingUnit
    - qudt_CurrencyUnit
    - qudt_DateTimeStringEncodingType
    - qudt_DecimalPrefix
    - qudt_DerivedUnit
    - qudt_DimensionlessUnit
    - qudt_EndianType
    - qudt_FloatingPointEncodingType
    - qudt_IntegerEncodingType
    - qudt_LogarithmicUnit
    - qudt_OrderedType
    - qudt_SignednessType
    - qudt_Unit
    - vaem_GraphMetaData
    - vaem_GraphRole
    - vaem_Party
    - time_DayOfWeek
    - time_TemporalUnit
    - rdf_DatatypeProperty
    - vaem_CatalogEntry
    - voag_Attribution
    - voag_AttributionLogo
    - voag_ChangeFrequency
    - voag_ChangeType
    - voag_ConfidentialityLevel
    - voag_CreativeCommonsPermission
    - voag_CreativeCommonsProhibition
    - voag_CreativeCommonsRequirement
    - voag_Governance
    - voag_GovernanceRole
    - voag_Icon
    - voag_IssueStatus
    - voag_LicenseModel
    - voag_Logo
    - voag_Maturity
    - voag_OrganizationLogo
    - voag_Pedigree
    - voag_PriorityValue
    - voag_ProductLogo
    - voag_Provenance
    - voag_PublicationStatus
    - voag_SchemaGraph
    - kwgo_AirPollutant
    - kwgo_BlueskyWildfireObservableProperty
    - kwgo_CensusObservableProperty
    - kwgo_ClimateObservableProperty
    - kwgo_CroplandObservableProperty
    - kwgo_DroughtIntensity
    - kwgo_FireCause
    - kwgo_HelipadAvailability
    - kwgo_HospitalStatus
    - kwgo_HospitalType
    - kwgo_ImpactObservableProperty
    - kwgo_LSADArea
    - kwgo_MTBSFireObservableProperty
    - kwgo_MagnitudeObservableProperty
    - kwgo_NIFCFireObservableProperty
    - kwgo_PublicHealthObservableProperty
    - kwgo_RoadType
    - kwgo_SmokePlumeObservableProperty
    - kwgo_SoilMapUnitObservableProperty
    - kwgo_StormTrackObservableProperty
    - kwgo_StormTrackletObservableProperty
    - kwgo_VulnerabilityObservableProperty
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
    - coso_PlantMaterialSample
    - coso_SubstanceCollection
    - coso_WaterSample
    - http___w3id.org_comptox_CompTox_ChemicalEntity
    - http___w3id.org_comptox_v1_ChemicalEntity
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AnalysisMethod
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-ConcentrationQualifier
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-ParameterName
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Site
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
    - http___w3id.org_sawgraph_v1_us-wqp#AnalyticalMethod
    - http___w3id.org_sawgraph_v1_us-wqp#Characteristic
    - http___w3id.org_sawgraph_v1_us-wqp#DefWQPGroundWaterFeatureType
    - http___w3id.org_sawgraph_v1_us-wqp#DefWQPSurfaceWaterFeatureType
    - http___w3id.org_sawgraph_v1_us-wqp#DefWQPWasteWaterFeatureType
    - http___w3id.org_sawgraph_v1_us-wqp#Federal_USGovernment_Organization
    - http___w3id.org_sawgraph_v1_us-wqp#LocationType
    - http___w3id.org_sawgraph_v1_us-wqp#Observation
    - http___w3id.org_sawgraph_v1_us-wqp#PrivateNon-Industrial_Organization
    - http___w3id.org_sawgraph_v1_us-wqp#ResultMeasureQualifier
    - http___w3id.org_sawgraph_v1_us-wqp#Sample
    - http___w3id.org_sawgraph_v1_us-wqp#SampleMedia
    - http___w3id.org_sawgraph_v1_us-wqp#SampledFeature
    - http___w3id.org_sawgraph_v1_us-wqp#Site
    - http___w3id.org_sawgraph_v1_us-wqp#StateGovernmentUS_Organization
    - http___w3id.org_sawgraph_v1_us-wqp#State_USGovernment_Organization
    - http___w3id.org_sawgraph_v1_us-wqp#Taxon
    - http___w3id.org_sawgraph_v1_us-wqp#TaxonGroup.FishNekton
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
    - obo_NCBITaxon_126735
    - obo_NCBITaxon_13106
    - obo_NCBITaxon_147949
    - obo_NCBITaxon_154811
    - obo_NCBITaxon_184451
    - obo_NCBITaxon_225060
    - obo_NCBITaxon_225389
    - obo_NCBITaxon_27706
    - obo_NCBITaxon_27778
    - obo_NCBITaxon_283036
    - obo_NCBITaxon_34816
    - obo_NCBITaxon_381124
    - obo_NCBITaxon_46259
    - obo_NCBITaxon_6550
    - obo_NCBITaxon_6604
    - obo_NCBITaxon_66912
    - obo_NCBITaxon_66913
    - obo_NCBITaxon_75288
    - obo_NCBITaxon_7971
    - obo_NCBITaxon_7998
    - obo_NCBITaxon_8010
    - obo_NCBITaxon_8022
    - obo_NCBITaxon_8032
    - obo_NCBITaxon_8038
    - obo_NCBITaxon_8167
    - obo_NCBITaxon_8182
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
  http___w3id.org_sawgraph_v1_me-egad#labQualifier:
    name: http___w3id.org_sawgraph_v1_me-egad#labQualifier
    title: egad - lab qualifier
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: http://w3id.org/sawgraph/v1/me-egad#labQualifier
    alias: http___w3id.org_sawgraph_v1_me_egad#labQualifier
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    domain_of:
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    subproperty_of: coso_resultAnnotation
    range: Any
    any_of:
    - range: owl_NamedIndividual
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ConcentrationQualifier
  http___w3id.org_sawgraph_v1_me-egad#reportingLimit:
    name: http___w3id.org_sawgraph_v1_me-egad#reportingLimit
    title: egad - reporting limit
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: http://w3id.org/sawgraph/v1/me-egad#reportingLimit
    alias: http___w3id.org_sawgraph_v1_me_egad#reportingLimit
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    domain_of:
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    subproperty_of: coso_resultAnnotation
    range: Any
    any_of:
    - range: coso_QuantitationLimit
    - range: coso_ResultQualifier
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
    - range: owl_Thing
    - range: qudt_Quantifiable
    - range: qudt_Quantity
    - range: qudt_Concept
    - range: stad_Datapoint
  stad_hasQualityKind:
    name: stad_hasQualityKind
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: stad:hasQualityKind
    alias: stad_hasQualityKind
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    domain_of:
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    range: Any
    any_of:
    - range: owl_NamedIndividual
    - range: qudt_QuantityKind
    - range: coso_ContaminantConcentrationQuantityKind
    - range: coso_ContaminationProperty
    - range: stad_QualityKind
  http___w3id.org_sawgraph_v1_me-egad#validationLevel:
    name: http___w3id.org_sawgraph_v1_me-egad#validationLevel
    title: egad - validation level
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: http://w3id.org/sawgraph/v1/me-egad#validationLevel
    alias: http___w3id.org_sawgraph_v1_me_egad#validationLevel
    owner: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    domain_of:
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
    subproperty_of: coso_resultAnnotation
    range: Any
    any_of:
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ValidationLevel
    - range: owl_NamedIndividual
    - range: owl_Thing
class_uri: http://w3id.org/sawgraph/v1/me-egad#EGAD-SinglePFAS-Concentration

```
</details>