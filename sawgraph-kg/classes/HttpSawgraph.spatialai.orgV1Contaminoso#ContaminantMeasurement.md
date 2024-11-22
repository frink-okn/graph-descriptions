

# Class: TODO -- this class is noted as a superclass of another class in this graph but has not itself been defined. (http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement)


_TODO -- tell the world what this class (type) describes._





URI: [http://sawgraph.spatialai.org/v1/contaminoso#ContaminantMeasurement](http://sawgraph.spatialai.org/v1/contaminoso#ContaminantMeasurement)






```mermaid
 classDiagram
    class HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement
    click HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement href "../HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement"
      SosaResult <|-- HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement
        click SosaResult href "../SosaResult"
      
      HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement : http___qudt.org_schema_qudt_quantityValue
        
          
    
    
    HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement --> "0..1" Uri : http___qudt.org_schema_qudt_quantityValue
    click Uri href "../Uri"

        
      HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement : http___sawgraph.spatialai.org_v1_contaminoso#resultAnnotation
        
          
    
    
    HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement --> "0..1" Any : http___sawgraph.spatialai.org_v1_contaminoso#resultAnnotation
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement : http___sawgraph.spatialai.org_v1_me_egad#labQualifier
        
          
    
    
    HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement --> "0..1" HttpSawgraph.spatialai.orgV1Contaminoso#ResultQualifier : http___sawgraph.spatialai.org_v1_me_egad#labQualifier
    click HttpSawgraph.spatialai.orgV1Contaminoso#ResultQualifier href "../HttpSawgraph.spatialai.orgV1Contaminoso#ResultQualifier"

        
      HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement : http___sawgraph.spatialai.org_v1_me_egad#validationLevel
        
          
    
    
    HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement --> "0..1" Any : http___sawgraph.spatialai.org_v1_me_egad#validationLevel
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement : http___sawgraph.spatialai.org_v1_me_egad#validationQualifier
        
          
    
    
    HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement --> "0..1" Any : http___sawgraph.spatialai.org_v1_me_egad#validationQualifier
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement : https___qudt.org_schema_qudt_quantityValue
        
          
    
    
    HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement --> "0..1" HttpSawgraph.spatialai.orgV1Us-sdwis#Amount : https___qudt.org_schema_qudt_quantityValue
    click HttpSawgraph.spatialai.orgV1Us-sdwis#Amount href "../HttpSawgraph.spatialai.orgV1Us-sdwis#Amount"

        
      HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement : rdfs_label
        
          
    
    
    HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```





## Inheritance
* [SosaResult](../classes/SosaResult.md)
    * **HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [http___sawgraph.spatialai.org_v1_me_egad#labQualifier](../slots/http___sawgraph.spatialai.org_v1_me_egad#labQualifier.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Contaminoso#ResultQualifier](../classes/HttpSawgraph.spatialai.orgV1Contaminoso#ResultQualifier.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [https___qudt.org_schema_qudt_quantityValue](../slots/https___qudt.org_schema_qudt_quantityValue.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Us-sdwis#Amount](../classes/HttpSawgraph.spatialai.orgV1Us-sdwis#Amount.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [http___sawgraph.spatialai.org_v1_me_egad#validationLevel](../slots/http___sawgraph.spatialai.org_v1_me_egad#validationLevel.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpSawgraph.spatialai.orgV1Contaminoso#ResultQualifier](../classes/HttpSawgraph.spatialai.orgV1Contaminoso#ResultQualifier.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [http___sawgraph.spatialai.org_v1_contaminoso#resultAnnotation](../slots/http___sawgraph.spatialai.org_v1_contaminoso#resultAnnotation.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpSawgraph.spatialai.orgV1Contaminoso#ResultQualifier](../classes/HttpSawgraph.spatialai.orgV1Contaminoso#ResultQualifier.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [http___sawgraph.spatialai.org_v1_me_egad#validationQualifier](../slots/http___sawgraph.spatialai.org_v1_me_egad#validationQualifier.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpSawgraph.spatialai.orgV1Contaminoso#ResultQualifier](../classes/HttpSawgraph.spatialai.orgV1Contaminoso#ResultQualifier.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [http___qudt.org_schema_qudt_quantityValue](../slots/http___qudt.org_schema_qudt_quantityValue.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantObservation](../classes/HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantObservation.md) | [sosa_hasResult](../slots/sosa_hasResult.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement](../classes/HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement.md) |






## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sawgraph-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://sawgraph.spatialai.org/v1/contaminoso#ContaminantMeasurement |
| native | sawgraph-kg/:HttpSawgraph.spatialai.orgV1Contaminoso#ContaminantMeasurement |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
description: TODO -- tell the world what this class (type) describes.
title: TODO -- this class is noted as a superclass of another class in this graph
  but has not itself been defined.
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 143064 occurences.
from_schema: sawgraph-kg
is_a: sosa_Result
slots:
- http___sawgraph.spatialai.org_v1_me-egad#labQualifier
- https___qudt.org_schema_qudt_quantityValue
- http___sawgraph.spatialai.org_v1_me-egad#validationLevel
- rdfs_label
- http___sawgraph.spatialai.org_v1_contaminoso#resultAnnotation
- http___sawgraph.spatialai.org_v1_me-egad#validationQualifier
- http___qudt.org_schema_qudt_quantityValue
class_uri: http://sawgraph.spatialai.org/v1/contaminoso#ContaminantMeasurement

```
</details>

### Induced

<details>
```yaml
name: http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
description: TODO -- tell the world what this class (type) describes.
title: TODO -- this class is noted as a superclass of another class in this graph
  but has not itself been defined.
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 143064 occurences.
from_schema: sawgraph-kg
is_a: sosa_Result
attributes:
  http___sawgraph.spatialai.org_v1_me-egad#labQualifier:
    name: http___sawgraph.spatialai.org_v1_me-egad#labQualifier
    description: TODO -- tell the world what this slot (predicate) describes.
    title: egad - lab qualifier
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 40705 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
      and object type http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier.
    - 13237 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
      and object type http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier.
    examples:
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.1763231
        http://sawgraph.spatialai.org/v1/me-egad#labQualifier http://sawgraph.spatialai.org/v1/me-egad#concentrationQualifier.J
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018
        http://sawgraph.spatialai.org/v1/me-egad#labQualifier http://sawgraph.spatialai.org/v1/me-egad#concentrationQualifier.J
    from_schema: sawgraph-kg
    rank: 1000
    slot_uri: http://sawgraph.spatialai.org/v1/me-egad#labQualifier
    alias: http___sawgraph.spatialai.org_v1_me_egad#labQualifier
    owner: http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    domain_of:
    - http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
    - http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    subproperty_of: http___sawgraph.spatialai.org_v1_contaminoso#resultAnnotation
    range: http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier
  https___qudt.org_schema_qudt_quantityValue:
    name: https___qudt.org_schema_qudt_quantityValue
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 21 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
      and object type http___sawgraph.spatialai.org_v1_us-sdwis#Amount.
    examples:
    - value: http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-PFASConcentration.ME0309196.03162022.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA
        https://qudt.org/schema/qudt/quantityValue http://sawgraph.spatialai.org/v1/us-sdwis-data#d.Amount.ME0309196.Sample-03162022.Chemical-PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA
    from_schema: sawgraph-kg
    rank: 1000
    slot_uri: https://qudt.org/schema/qudt/quantityValue
    alias: https___qudt.org_schema_qudt_quantityValue
    owner: http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    domain_of:
    - http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    range: http___sawgraph.spatialai.org_v1_us-sdwis#Amount
  http___sawgraph.spatialai.org_v1_me-egad#validationLevel:
    name: http___sawgraph.spatialai.org_v1_me-egad#validationLevel
    description: TODO -- tell the world what this slot (predicate) describes.
    title: egad - validation level
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 113547 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
      and object type http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier.
    - 26147 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
      and object type http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier.
    - 490 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
      and object type uri.
    - 64 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
      and object type uri.
    examples:
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.1763231
        http://sawgraph.spatialai.org/v1/me-egad#validationLevel http://sawgraph.spatialai.org/v1/me-egad#validationLevel.DEP
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018
        http://sawgraph.spatialai.org/v1/me-egad#validationLevel http://sawgraph.spatialai.org/v1/me-egad#validationLevel.DEP
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.170094201.VAL.20170725.108427538
        http://sawgraph.spatialai.org/v1/me-egad#validationLevel http://sawgraph.spatialai.org/v1/me-egad#validationLevel.TierII-EPA-NE-REGION-1-GUIDELINES
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.170098413.VAL.20170802.DEP18016
        http://sawgraph.spatialai.org/v1/me-egad#validationLevel http://sawgraph.spatialai.org/v1/me-egad#validationLevel.TierII-EPA-NE-REGION-1-GUIDELINES
    from_schema: sawgraph-kg
    rank: 1000
    slot_uri: http://sawgraph.spatialai.org/v1/me-egad#validationLevel
    alias: http___sawgraph.spatialai.org_v1_me_egad#validationLevel
    owner: http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    domain_of:
    - http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
    - http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    subproperty_of: http___sawgraph.spatialai.org_v1_contaminoso#resultAnnotation
    range: Any
    any_of:
    - range: uri
    - range: http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier
  rdfs_label:
    name: rdfs_label
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 66 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier
      and object type string.
    - 33 occurrences with subject type http___sawgraph.spatialai.org_v1_il-isgs#WellPurpose
      and object type string.
    - 109 occurrences with subject type http___sawgraph.spatialai.org_v1_me-egad#EGAD-SamplePointType
      and object type string.
    - 94 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#Substance
      and object type string.
    - 12 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ObservationAnnotation
      and object type string.
    - 160 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#SampleAnnotation
      and object type string.
    - 97 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#MaterialType
      and object type string.
    - 1249 occurrences with subject type http___sawgraph.spatialai.org_v1_me-egad#EGAD-AnalysisMethod
      and object type string.
    - 3 occurrences with subject type http___qudt.org_vocab_unitUnit and object type
      string.
    - 300 occurrences with subject type prov_Organization and object type string.
    - 115887 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
      and object type string.
    - 26294 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
      and object type string.
    - 23031 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#MaterialSample
      and object type string.
    - 8324 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#Point
      and object type string.
    - 171069 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#Feature
      and object type string.
    - 957 occurrences with subject type http___sawgraph.spatialai.org_v1_me-egad#EGAD-Site
      and object type string.
    - 62 occurrences with subject type http___sawgraph.spatialai.org_v1_me-egad#EGAD-SiteType
      and object type string.
    - 142181 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ContaminantObservation
      and object type string.
    examples:
    - value: http://sawgraph.spatialai.org/me-egad#concentrationQualifier.* rdfs:label
        QC RESULTS NOT WITHIN CONTROL LIMITS
    - value: http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-WellPurpose.CROP
        rdfs:label Outcrop
    - value: http://sawgraph.spatialai.org/v1/me-egad#featureType.AST rdfs:label ABOVEGROUND
        STORAGE TANK
    - value: http://sawgraph.spatialai.org/v1/me-egad#parameter.10-2_FTS_A rdfs:label
        10:2 FLUOROTELOMER SULFONIC ACID
    - value: http://sawgraph.spatialai.org/v1/me-egad#resultType.TRG rdfs:label TARGET/REGULAR
        RESULT
    - value: http://sawgraph.spatialai.org/v1/me-egad#sampleLocation.AF rdfs:label
        AFTER FILTERS
    - value: http://sawgraph.spatialai.org/v1/me-egad#sampleMaterialType.AS rdfs:label
        ASH (BOTTOM & FLY)
    - value: http://sawgraph.spatialai.org/v1/me-egad#testMethod.CALCULATED rdfs:label
        CALCULATED
    - value: http://sawgraph.spatialai.org/v1/me-egad#unit.MG-KG rdfs:label MILLIGRAMS
        PER KILOGRAM
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#organization.lab.AA rdfs:label
        ALPHA ANALYTICAL LAB - WESTBOROUGH, MA
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.1028303.ELL.20190405.45298906
        rdfs:label EGAD PFAS measurements for sample 722
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.1028303.ELL.20190405.DEP18010
        rdfs:label EGAD PFAS measurements for sample 722
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#sample.1028303.ELL.20190405
        rdfs:label EGAD sample 722
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.100410 rdfs:label
        EGAD sample point 100410
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#sampledFeature.100410 rdfs:label
        EGAD sampled festure associated with sample point 100410
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#site.100843 rdfs:label
        EGAD site 100843
    - value: http://sawgraph.spatialai.org/v1/me-egad#siteType.AGRICCHEM rdfs:label
        AGRICULTURAL CHEMICAL USE
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#observation.1028303.ELL.20190405.45298906
        rdfs:label EGAD PFAS observation for sample 722
    from_schema: sawgraph-kg
    rank: 1000
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    domain_of:
    - http___qudt.org_vocab_unitUnit
    - http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
    - http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    - http___sawgraph.spatialai.org_v1_contaminoso#ContaminantObservation
    - http___sawgraph.spatialai.org_v1_contaminoso#Feature
    - http___sawgraph.spatialai.org_v1_contaminoso#MaterialSample
    - http___sawgraph.spatialai.org_v1_contaminoso#MaterialType
    - http___sawgraph.spatialai.org_v1_contaminoso#ObservationAnnotation
    - http___sawgraph.spatialai.org_v1_contaminoso#Point
    - http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier
    - http___sawgraph.spatialai.org_v1_contaminoso#SampleAnnotation
    - http___sawgraph.spatialai.org_v1_contaminoso#Substance
    - http___sawgraph.spatialai.org_v1_il-isgs#WellPurpose
    - http___sawgraph.spatialai.org_v1_me-egad#EGAD-AnalysisMethod
    - http___sawgraph.spatialai.org_v1_me-egad#EGAD-SamplePointType
    - http___sawgraph.spatialai.org_v1_me-egad#EGAD-Site
    - http___sawgraph.spatialai.org_v1_me-egad#EGAD-SiteType
    - prov_Organization
    range: Any
    any_of:
    - range: uri
    - range: string
  http___sawgraph.spatialai.org_v1_contaminoso#resultAnnotation:
    name: http___sawgraph.spatialai.org_v1_contaminoso#resultAnnotation
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 180161 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
      and object type http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier.
    - 44340 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
      and object type http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier.
    - 535 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
      and object type uri.
    - 72 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
      and object type uri.
    - 283759 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier
      and object type http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier.
    examples:
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.1763231
        http://sawgraph.spatialai.org/v1/contaminoso#resultAnnotation http://sawgraph.spatialai.org/v1/me-egad#validationLevel.DEP
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018
        http://sawgraph.spatialai.org/v1/contaminoso#resultAnnotation http://sawgraph.spatialai.org/v1/me-egad#validationLevel.DEP
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.170094201.VAL.20170725.108427538
        http://sawgraph.spatialai.org/v1/contaminoso#resultAnnotation http://sawgraph.spatialai.org/v1/me-egad#validationLevel.TierII-EPA-NE-REGION-1-GUIDELINES
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.170098413.VAL.20170802.DEP18016
        http://sawgraph.spatialai.org/v1/contaminoso#resultAnnotation http://sawgraph.spatialai.org/v1/me-egad#validationLevel.TierII-EPA-NE-REGION-1-GUIDELINES
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#mdl.WG17410824.AAWH.20230125.DEP18018
        http://sawgraph.spatialai.org/v1/contaminoso#resultAnnotation http://sawgraph.spatialai.org/v1/me-egad-data#rl.WG17410824.AAWH.20230125.DEP18018
    from_schema: sawgraph-kg
    rank: 1000
    slot_uri: http://sawgraph.spatialai.org/v1/contaminoso#resultAnnotation
    alias: http___sawgraph.spatialai.org_v1_contaminoso#resultAnnotation
    owner: http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    domain_of:
    - http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
    - http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    - http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier
    range: Any
    any_of:
    - range: uri
    - range: http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier
  http___sawgraph.spatialai.org_v1_me-egad#validationQualifier:
    name: http___sawgraph.spatialai.org_v1_me-egad#validationQualifier
    description: TODO -- tell the world what this slot (predicate) describes.
    title: egad - validation qualifier
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 60592 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
      and object type http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier.
    - 17314 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
      and object type http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier.
    - 45 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
      and object type uri.
    - 8 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
      and object type uri.
    examples:
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.1763231
        http://sawgraph.spatialai.org/v1/me-egad#validationQualifier http://sawgraph.spatialai.org/v1/me-egad#concentrationQualifier.J
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018
        http://sawgraph.spatialai.org/v1/me-egad#validationQualifier http://sawgraph.spatialai.org/v1/me-egad#concentrationQualifier.J
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.320623561.TA.20200701.335671
        http://sawgraph.spatialai.org/v1/me-egad#validationQualifier http://sawgraph.spatialai.org/v1/me-egad#concentrationQualifier.M
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.320623562.TA.20200701.DEP18010
        http://sawgraph.spatialai.org/v1/me-egad#validationQualifier http://sawgraph.spatialai.org/v1/me-egad#concentrationQualifier.M
    from_schema: sawgraph-kg
    rank: 1000
    slot_uri: http://sawgraph.spatialai.org/v1/me-egad#validationQualifier
    alias: http___sawgraph.spatialai.org_v1_me_egad#validationQualifier
    owner: http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    domain_of:
    - http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
    - http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    subproperty_of: http___sawgraph.spatialai.org_v1_contaminoso#resultAnnotation
    range: Any
    any_of:
    - range: uri
    - range: http___sawgraph.spatialai.org_v1_contaminoso#ResultQualifier
  http___qudt.org_schema_qudt_quantityValue:
    name: http___qudt.org_schema_qudt_quantityValue
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 115882 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
      and object type uri.
    - 26293 occurrences with subject type http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
      and object type uri.
    examples:
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.1028303.ELL.20190405.45298906
        http://qudt.org/schema/qudt/quantityValue http://sawgraph.spatialai.org/v1/me-egad-data#quantityValue.1028303.ELL.20190405.45298906
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#result.1028303.ELL.20190405.DEP18010
        http://qudt.org/schema/qudt/quantityValue http://sawgraph.spatialai.org/v1/me-egad-data#quantityValue.1028303.ELL.20190405.DEP18010
    from_schema: sawgraph-kg
    rank: 1000
    slot_uri: http://qudt.org/schema/qudt/quantityValue
    alias: http___qudt.org_schema_qudt_quantityValue
    owner: http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    domain_of:
    - http___sawgraph.spatialai.org_v1_contaminoso#AggregateContaminantMeasurement
    - http___sawgraph.spatialai.org_v1_contaminoso#ContaminantMeasurement
    range: uri
class_uri: http://sawgraph.spatialai.org/v1/contaminoso#ContaminantMeasurement

```
</details>