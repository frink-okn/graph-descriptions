

# Class: HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample




This class occurs 14713 times.


URI: [http://w3id.org/sawgraph/v1/me-egad-data#DefEGADGroundWaterSample](http://w3id.org/sawgraph/v1/me-egad-data#DefEGADGroundWaterSample)






```mermaid
 classDiagram
    class HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample
    click HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample href "../HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample"
      SosaSample <|-- HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample
        click SosaSample href "../SosaSample"
      
      HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample : coso_fromSamplePoint
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample --> "0..1" Any : coso_fromSamplePoint
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample : coso_isSampleOf
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample --> "0..1" Any : coso_isSampleOf
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample : coso_sampleAnnotation
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample --> "0..1" Any : coso_sampleAnnotation
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample : coso_sampleOfMaterialType
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample --> "0..1" Any : coso_sampleOfMaterialType
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample : dct_identifier
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample --> "0..1" RdfsLiteral : dct_identifier
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample : http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample --> "0..1" Any : http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample : http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample --> "0..1" Any : http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample : http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample --> "0..1" Any : http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample : owl_sameAs
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample --> "0..1" OwlThing : owl_sameAs
    click OwlThing href "../OwlThing"

        
      HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample : prov_wasAttributedTo
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample --> "0..1" ProvAgent : prov_wasAttributedTo
    click ProvAgent href "../ProvAgent"

        
      HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample : rdfs_label
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample : sosa_isSampleOf
        
          
    
    
    HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample --> "0..1" HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature : sosa_isSampleOf
    click HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature"

        
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * [SosaSample](../classes/SosaSample.md)
        * **HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [coso_isSampleOf](../slots/coso_isSampleOf.md) | 0..1 <br/> [CosoSampledFeature](../classes/CosoSampledFeature.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[CosoFeature](../classes/CosoFeature.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md) | A relation between a physcial material sample and the geographic feature the ... <br/>  | direct | 14719 |
| [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | 0..1 <br/> [MeEgadEGAD-SampleCollectionMethod](../classes/MeEgadEGAD-SampleCollectionMethod.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleDetailedLocation](../classes/MeEgadEGAD-SampleDetailedLocation.md)&nbsp;or&nbsp;<br />[CosoSampleAnnotation](../classes/CosoSampleAnnotation.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleTreatmentStatus](../classes/MeEgadEGAD-SampleTreatmentStatus.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod.md) | A relation between a material sample and additional metadata about the sample <br/>  | direct | 80504 |
| [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation.md) | 0..1 <br/> [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[CosoSampleAnnotation](../classes/CosoSampleAnnotation.md) |  <br/>  | direct | 25830 |
| [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod.md)&nbsp;or&nbsp;<br />[CosoSampleAnnotation](../classes/CosoSampleAnnotation.md) |  <br/>  | direct | 29272 |
| [dct_identifier](../slots/dct_identifier.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | Recommended practice is to identify the resource by means of a string conform... <br/> description: An unambiguous reference to the resource within a given context. | direct | 14718 |
| [http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus.md)&nbsp;or&nbsp;<br />[CosoSampleAnnotation](../classes/CosoSampleAnnotation.md) |  <br/>  | direct | 25402 |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md) | The property that determines that two given individuals are equal <br/>  | direct | 44139 |
| [prov_wasAttributedTo](../slots/prov_wasAttributedTo.md) | 0..1 <br/> [ProvAgent](../classes/ProvAgent.md) | Attribution is the ascribing of an entity to an agent <br/> description: Attribution is the ascribing of an entity to an agent. | direct | 26680 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 14718 |
| [sosa_isSampleOf](../slots/sosa_isSampleOf.md) | 0..1 <br/> [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md) |  <br/>  | direct | 14719 |
| [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | 0..1 <br/> [OboFOODON03411183](../classes/OboFOODON03411183.md)&nbsp;or&nbsp;<br />[OboFOODON03411057](../classes/OboFOODON03411057.md)&nbsp;or&nbsp;<br />[OboNCBITaxon283036](../classes/OboNCBITaxon283036.md)&nbsp;or&nbsp;<br />[OboFOODON02010107](../classes/OboFOODON02010107.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#SampleMedia](../classes/HttpW3id.orgSawgraphV1Us-wqp#SampleMedia.md)&nbsp;or&nbsp;<br />[OboFOODON00003572](../classes/OboFOODON00003572.md)&nbsp;or&nbsp;<br />[B37977f50d3140da51a9630b8a57396a1](../classes/B37977f50d3140da51a9630b8a57396a1.md)&nbsp;or&nbsp;<br />[OboFOODON03420147](../classes/OboFOODON03420147.md)&nbsp;or&nbsp;<br />[B215b3a432e1c482d3680398a554edbbf](../classes/B215b3a432e1c482d3680398a554edbbf.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleMaterialTypeQualifier](../classes/MeEgadEGAD-SampleMaterialTypeQualifier.md)&nbsp;or&nbsp;<br />[B036a3008450d6ce37e35cf5a98355a60](../classes/B036a3008450d6ce37e35cf5a98355a60.md)&nbsp;or&nbsp;<br />[OboNCBITaxon66912](../classes/OboNCBITaxon66912.md)&nbsp;or&nbsp;<br />[OboNCBITaxon7971](../classes/OboNCBITaxon7971.md)&nbsp;or&nbsp;<br />[OboFOODON03411566](../classes/OboFOODON03411566.md)&nbsp;or&nbsp;<br />[OboFOODON03420194](../classes/OboFOODON03420194.md)&nbsp;or&nbsp;<br />[OboNCBITaxon381124](../classes/OboNCBITaxon381124.md)&nbsp;or&nbsp;<br />[Bf584e1bfd1c74de0eb37e7b926538b83](../classes/Bf584e1bfd1c74de0eb37e7b926538b83.md)&nbsp;or&nbsp;<br />[OboFOODON00001093](../classes/OboFOODON00001093.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#Taxon](../classes/HttpW3id.orgSawgraphV1Us-wqp#Taxon.md)&nbsp;or&nbsp;<br />[OboNCBITaxon8022](../classes/OboNCBITaxon8022.md)&nbsp;or&nbsp;<br />[B44bec873efc8b96cad5f525429c64e0a](../classes/B44bec873efc8b96cad5f525429c64e0a.md)&nbsp;or&nbsp;<br />[OboFOODON00002477](../classes/OboFOODON00002477.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[B27231c83f17c76e178e0c9f5e10acc55](../classes/B27231c83f17c76e178e0c9f5e10acc55.md)&nbsp;or&nbsp;<br />[OboNCBITaxon6550](../classes/OboNCBITaxon6550.md)&nbsp;or&nbsp;<br />[OboFOODON02021651](../classes/OboFOODON02021651.md)&nbsp;or&nbsp;<br />[Ba6d85f816540f9fec5b71ba42fc2cca6](../classes/Ba6d85f816540f9fec5b71ba42fc2cca6.md)&nbsp;or&nbsp;<br />[CosoWaterSample](../classes/CosoWaterSample.md)&nbsp;or&nbsp;<br />[OboNCBITaxon225389](../classes/OboNCBITaxon225389.md)&nbsp;or&nbsp;<br />[B423a0e253807f20386fc3ccbbd7e0378](../classes/B423a0e253807f20386fc3ccbbd7e0378.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleMaterialType](../classes/MeEgadEGAD-SampleMaterialType.md)&nbsp;or&nbsp;<br />[OboNCBITaxon8182](../classes/OboNCBITaxon8182.md)&nbsp;or&nbsp;<br />[OboFOODON02010012](../classes/OboFOODON02010012.md)&nbsp;or&nbsp;<br />[Bbefc37cbdd03cae92dadef76b34dbf16](../classes/Bbefc37cbdd03cae92dadef76b34dbf16.md)&nbsp;or&nbsp;<br />[OboFOODON03420150](../classes/OboFOODON03420150.md)&nbsp;or&nbsp;<br />[B085dcda89ed6aae0d3b229e767f0a1ca](../classes/B085dcda89ed6aae0d3b229e767f0a1ca.md)&nbsp;or&nbsp;<br />[Bb0125be5bc4dc7be7e8452e7d22445f6](../classes/Bb0125be5bc4dc7be7e8452e7d22445f6.md)&nbsp;or&nbsp;<br />[B0d427a711311f1499a234aa8af2c66d1](../classes/B0d427a711311f1499a234aa8af2c66d1.md)&nbsp;or&nbsp;<br />[OboFOODON03411236](../classes/OboFOODON03411236.md)&nbsp;or&nbsp;<br />[OboNCBITaxon6604](../classes/OboNCBITaxon6604.md)&nbsp;or&nbsp;<br />[OboFOODON03301761](../classes/OboFOODON03301761.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialType.md)&nbsp;or&nbsp;<br />[B7728f65369357f97de36b133c9d1d5e0](../classes/B7728f65369357f97de36b133c9d1d5e0.md)&nbsp;or&nbsp;<br />[Be047d68edc8eb3ce96d7edbad5217bfc](../classes/Be047d68edc8eb3ce96d7edbad5217bfc.md)&nbsp;or&nbsp;<br />[OboNCBITaxon8032](../classes/OboNCBITaxon8032.md)&nbsp;or&nbsp;<br />[OboFOODON03420181](../classes/OboFOODON03420181.md)&nbsp;or&nbsp;<br />[OboFOODON02010045](../classes/OboFOODON02010045.md)&nbsp;or&nbsp;<br />[OboNCBITaxon154811](../classes/OboNCBITaxon154811.md)&nbsp;or&nbsp;<br />[OboNCBITaxon27778](../classes/OboNCBITaxon27778.md)&nbsp;or&nbsp;<br />[Be497d3b0c2656040c05e303873a2d541](../classes/Be497d3b0c2656040c05e303873a2d541.md)&nbsp;or&nbsp;<br />[OboFOODON00004460](../classes/OboFOODON00004460.md)&nbsp;or&nbsp;<br />[Beb77c26f8c395403edc359fd5f6dfb28](../classes/Beb77c26f8c395403edc359fd5f6dfb28.md)&nbsp;or&nbsp;<br />[B611b8dff312692e7f32a69834c787a60](../classes/B611b8dff312692e7f32a69834c787a60.md)&nbsp;or&nbsp;<br />[OboFOODON03411324](../classes/OboFOODON03411324.md)&nbsp;or&nbsp;<br />[B75e45ed04b2b903b9029968cada06faa](../classes/B75e45ed04b2b903b9029968cada06faa.md)&nbsp;or&nbsp;<br />[OboFOODON03420116](../classes/OboFOODON03420116.md)&nbsp;or&nbsp;<br />[OboNCBITaxon225060](../classes/OboNCBITaxon225060.md)&nbsp;or&nbsp;<br />[B75dbc5841338872cea35dced609fcd77](../classes/B75dbc5841338872cea35dced609fcd77.md)&nbsp;or&nbsp;<br />[CosoSampleMaterialType](../classes/CosoSampleMaterialType.md)&nbsp;or&nbsp;<br />[OboFOODON00003083](../classes/OboFOODON00003083.md)&nbsp;or&nbsp;<br />[OboNCBITaxon147949](../classes/OboNCBITaxon147949.md)&nbsp;or&nbsp;<br />[OboFOODON03411325](../classes/OboFOODON03411325.md)&nbsp;or&nbsp;<br />[OboNCBITaxon7998](../classes/OboNCBITaxon7998.md)&nbsp;or&nbsp;<br />[OboNCBITaxon8010](../classes/OboNCBITaxon8010.md)&nbsp;or&nbsp;<br />[B3cc7b3721547b07a4068dc98b6444b8b](../classes/B3cc7b3721547b07a4068dc98b6444b8b.md)&nbsp;or&nbsp;<br />[OboNCBITaxon8038](../classes/OboNCBITaxon8038.md)&nbsp;or&nbsp;<br />[OboNCBITaxon184451](../classes/OboNCBITaxon184451.md)&nbsp;or&nbsp;<br />[OboFOODON02010015](../classes/OboFOODON02010015.md)&nbsp;or&nbsp;<br />[Bbf63deb85414ddecd89e46bce27e7f0a](../classes/Bbf63deb85414ddecd89e46bce27e7f0a.md)&nbsp;or&nbsp;<br />[OboFOODON00004172](../classes/OboFOODON00004172.md)&nbsp;or&nbsp;<br />[OboFOODON03411457](../classes/OboFOODON03411457.md)&nbsp;or&nbsp;<br />[OboNCBITaxon75288](../classes/OboNCBITaxon75288.md)&nbsp;or&nbsp;<br />[OboFOODON03413378](../classes/OboFOODON03413378.md)&nbsp;or&nbsp;<br />[OboFOODON02010042](../classes/OboFOODON02010042.md)&nbsp;or&nbsp;<br />[B4fd286b2a5a12e342d61412628b6e4c2](../classes/B4fd286b2a5a12e342d61412628b6e4c2.md)&nbsp;or&nbsp;<br />[Bf04685c17c0e71ae3c98e08c75cbdfcc](../classes/Bf04685c17c0e71ae3c98e08c75cbdfcc.md)&nbsp;or&nbsp;<br />[B623b56ef58fd82dd088819e22d655c08](../classes/B623b56ef58fd82dd088819e22d655c08.md)&nbsp;or&nbsp;<br />[OboFOODON00003425](../classes/OboFOODON00003425.md)&nbsp;or&nbsp;<br />[B5e93e815b548435105d9273d424fa0e8](../classes/B5e93e815b548435105d9273d424fa0e8.md)&nbsp;or&nbsp;<br />[OboFOODON00002165](../classes/OboFOODON00002165.md)&nbsp;or&nbsp;<br />[OboFOODON03411669](../classes/OboFOODON03411669.md)&nbsp;or&nbsp;<br />[B53622dee107de372b2d0566f64ab6e3a](../classes/B53622dee107de372b2d0566f64ab6e3a.md)&nbsp;or&nbsp;<br />[OboNCBITaxon8167](../classes/OboNCBITaxon8167.md)&nbsp;or&nbsp;<br />[OboFOODON02020892](../classes/OboFOODON02020892.md)&nbsp;or&nbsp;<br />[OboNCBITaxon27706](../classes/OboNCBITaxon27706.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#TaxonGroup.FishNekton](../classes/HttpW3id.orgSawgraphV1Us-wqp#TaxonGroup.FishNekton.md)&nbsp;or&nbsp;<br />[OboFOODON00003042](../classes/OboFOODON00003042.md)&nbsp;or&nbsp;<br />[OboFOODON02021803](../classes/OboFOODON02021803.md)&nbsp;or&nbsp;<br />[OboNCBITaxon46259](../classes/OboNCBITaxon46259.md)&nbsp;or&nbsp;<br />[OboNCBITaxon34816](../classes/OboNCBITaxon34816.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier.md)&nbsp;or&nbsp;<br />[Bb71af62f2f3e5e5b5e0fe81f24eca409](../classes/Bb71af62f2f3e5e5b5e0fe81f24eca409.md)&nbsp;or&nbsp;<br />[OboNCBITaxon66913](../classes/OboNCBITaxon66913.md)&nbsp;or&nbsp;<br />[OboFOODON03411583](../classes/OboFOODON03411583.md)&nbsp;or&nbsp;<br />[OboFOODON03411328](../classes/OboFOODON03411328.md)&nbsp;or&nbsp;<br />[OboFOODON00004436](../classes/OboFOODON00004436.md)&nbsp;or&nbsp;<br />[OboFOODON02021805](../classes/OboFOODON02021805.md)&nbsp;or&nbsp;<br />[OboFOODON03413358](../classes/OboFOODON03413358.md)&nbsp;or&nbsp;<br />[OboFOODON02010032](../classes/OboFOODON02010032.md)&nbsp;or&nbsp;<br />[OboFOODON02020840](../classes/OboFOODON02020840.md)&nbsp;or&nbsp;<br />[OboNCBITaxon126735](../classes/OboNCBITaxon126735.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[OboNCBITaxon13106](../classes/OboNCBITaxon13106.md)&nbsp;or&nbsp;<br />[B8aa8791a0418cd594c8b56ad21351f72](../classes/B8aa8791a0418cd594c8b56ad21351f72.md)&nbsp;or&nbsp;<br />[B00af777bec4da87c5aebb51d94b2d478](../classes/B00af777bec4da87c5aebb51d94b2d478.md) | A relation between a material sample and the type of material <br/>  | direct | 29768 |
| [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | 0..1 <br/> [GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#Site](../classes/HttpW3id.orgSawgraphV1Us-wqp#Site.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[CosoSamplePoint](../classes/CosoSamplePoint.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[CosoPoint](../classes/CosoPoint.md) | A relation between a physical material sample and the location where the samp... <br/>  | direct | 14719 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_analyzedSample](../slots/coso_analyzedSample.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_hasAnyFeatureOfInterest](../slots/coso_hasAnyFeatureOfInterest.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) | [coso_analyzedSample](../slots/coso_analyzedSample.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_analyzedSample](../slots/coso_analyzedSample.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_hasAnyFeatureOfInterest](../slots/coso_hasAnyFeatureOfInterest.md) | any_of[range] | [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
from_schema: okns:sawgraph-kg
rank: 1000
is_a: sosa_Sample
slots:
- coso_isSampleOf
- coso_sampleAnnotation
- http___w3id.org_sawgraph_v1_me-egad#sampleCollectionLocation
- http___w3id.org_sawgraph_v1_me-egad#sampleCollectionMethod
- dct_identifier
- http___w3id.org_sawgraph_v1_me-egad#sampleTreatmentStatus
- owl_sameAs
- prov_wasAttributedTo
- rdfs_label
- sosa_isSampleOf
- coso_sampleOfMaterialType
- coso_fromSamplePoint
class_uri: http://w3id.org/sawgraph/v1/me-egad-data#DefEGADGroundWaterSample

```
</details>

### Induced

<details>

```yaml
name: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
from_schema: okns:sawgraph-kg
rank: 1000
is_a: sosa_Sample
attributes:
  coso_isSampleOf:
    name: coso_isSampleOf
    description: A relation between a physcial material sample and the geographic
      feature the sample was taken from.
    title: is sample of
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: coso:isSampleOf
    alias: coso_isSampleOf
    owner: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    domain_of:
    - coso_AnimalBloodSample
    - coso_AnimalMaterialSample
    - coso_AnimalMilkSample
    - coso_AnimalOrganSample
    - coso_AnimalTissueSample
    - coso_PlantMaterialSample
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
    subproperty_of: sosa_isSampleOf
    union_of:
    - owl_Thing
    - coso_MaterialSample
    - sosa_Sample
    range: Any
    any_of:
    - range: coso_SampledFeature
    - range: geo_Feature
    - range: owl_Thing
    - range: coso_Feature
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampledFeature
    - range: sosa_FeatureOfInterest
    - range: geo_SpatialObject
  coso_sampleAnnotation:
    name: coso_sampleAnnotation
    description: A relation between a material sample and additional metadata about
      the sample.
    title: sample annotation
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: coso:sampleAnnotation
    alias: coso_sampleAnnotation
    owner: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    domain_of:
    - coso_AnimalBloodSample
    - coso_AnimalMaterialSample
    - coso_AnimalMilkSample
    - coso_AnimalOrganSample
    - coso_AnimalTissueSample
    - coso_PlantMaterialSample
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
    - me_egad_EGAD-Sample
    union_of:
    - owl_Thing
    - coso_MaterialSample
    - sosa_Sample
    range: Any
    any_of:
    - range: me_egad_EGAD-SampleCollectionMethod
    - range: owl_NamedIndividual
    - range: me_egad_EGAD-SampleDetailedLocation
    - range: coso_SampleAnnotation
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleDetailedLocation
    - range: me_egad_EGAD-SampleTreatmentStatus
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleTreatmentStatus
    - range: owl_Thing
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleCollectionMethod
  http___w3id.org_sawgraph_v1_me-egad#sampleCollectionLocation:
    name: http___w3id.org_sawgraph_v1_me-egad#sampleCollectionLocation
    title: egad - sample collection location
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: http://w3id.org/sawgraph/v1/me-egad#sampleCollectionLocation
    alias: http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation
    owner: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    domain_of:
    - coso_AnimalOrganSample
    - coso_AnimalTissueSample
    - coso_PlantMaterialSample
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
    subproperty_of: coso_sampleAnnotation
    union_of:
    - owl_Thing
    - coso_MaterialSample
    - sosa_Sample
    range: Any
    any_of:
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleDetailedLocation
    - range: owl_Thing
    - range: owl_NamedIndividual
    - range: coso_SampleAnnotation
  http___w3id.org_sawgraph_v1_me-egad#sampleCollectionMethod:
    name: http___w3id.org_sawgraph_v1_me-egad#sampleCollectionMethod
    title: egad - sample collection method
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: http://w3id.org/sawgraph/v1/me-egad#sampleCollectionMethod
    alias: http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod
    owner: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    domain_of:
    - coso_AnimalBloodSample
    - coso_AnimalMaterialSample
    - coso_AnimalMilkSample
    - coso_AnimalOrganSample
    - coso_AnimalTissueSample
    - coso_PlantMaterialSample
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
    subproperty_of: coso_sampleAnnotation
    union_of:
    - owl_Thing
    - coso_MaterialSample
    - sosa_Sample
    range: Any
    any_of:
    - range: owl_Thing
    - range: owl_NamedIndividual
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleCollectionMethod
    - range: coso_SampleAnnotation
  dct_identifier:
    name: dct_identifier
    description: Recommended practice is to identify the resource by means of a string
      conforming to an identification system. Examples include International Standard
      Book Number (ISBN), Digital Object Identifier (DOI), and Uniform Resource Name
      (URN).  Persistent identifiers should be provided as HTTP URIs.
    title: Identifier
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: An unambiguous reference to the resource within a given context.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:identifier
    alias: dct_identifier
    owner: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    domain_of:
    - __Ba76635ffb4afc02e78b9ef49973d089f
    - __Beb7217b5b32080b9606028314249e33b
    - coso_AnimalBloodSample
    - coso_AnimalMaterialSample
    - coso_AnimalMilkSample
    - coso_AnimalOrganSample
    - coso_AnimalTissueSample
    - coso_PlantMaterialSample
    - coso_SubstanceCollection
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-ParameterName
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Site
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
    - me_egad_EGAD-PFAS-Site
    - me_egad_EGAD-Sample
    - me_egad_EGAD-SamplePoint
    subproperty_of: dc_identifier
    range: rdfs_Literal
  http___w3id.org_sawgraph_v1_me-egad#sampleTreatmentStatus:
    name: http___w3id.org_sawgraph_v1_me-egad#sampleTreatmentStatus
    title: egad - sample treatment status
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: http://w3id.org/sawgraph/v1/me-egad#sampleTreatmentStatus
    alias: http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus
    owner: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    domain_of:
    - coso_AnimalMilkSample
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
    subproperty_of: coso_sampleAnnotation
    union_of:
    - owl_Thing
    - coso_MaterialSample
    - sosa_Sample
    range: Any
    any_of:
    - range: owl_Thing
    - range: owl_NamedIndividual
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleTreatmentStatus
    - range: coso_SampleAnnotation
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
    owner: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
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
  prov_wasAttributedTo:
    name: prov_wasAttributedTo
    description: Attribution is the ascribing of an entity to an agent.
    title: wasAttributedTo
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: Attribution is the ascribing of an entity to an agent.'
    from_schema: okns:prov
    source: http://www.w3.org/ns/prov-o#
    domain: prov_Entity
    slot_uri: prov:wasAttributedTo
    alias: prov_wasAttributedTo
    owner: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    domain_of:
    - coso_AnimalMaterialSample
    - coso_AnimalMilkSample
    - coso_AnimalOrganSample
    - coso_AnimalTissueSample
    - coso_PlantMaterialSample
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
    - http___w3id.org_sawgraph_v1_us-wqp#Observation
    - http___w3id.org_sawgraph_v1_us-wqp#Site
    - me_egad_EGAD-PFAS-Observation
    - me_egad_EGAD-Sample
    subproperty_of: prov_wasInfluencedBy
    range: prov_Agent
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
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
  sosa_isSampleOf:
    name: sosa_isSampleOf
    title: No slot (predicate) name specified -- this slot is noted as a subproperty
      of another slot in this graph but has not itself been defined.
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: sosa:isSampleOf
    alias: sosa_isSampleOf
    owner: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    domain_of:
    - coso_AnimalBloodSample
    - coso_AnimalMaterialSample
    - coso_AnimalMilkSample
    - coso_AnimalOrganSample
    - coso_AnimalTissueSample
    - coso_PlantMaterialSample
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
    range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampledFeature
  coso_sampleOfMaterialType:
    name: coso_sampleOfMaterialType
    description: A relation between a material sample and the type of material.
    title: sample of material type
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: coso:sampleOfMaterialType
    alias: coso_sampleOfMaterialType
    owner: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    domain_of:
    - coso_AnimalBloodSample
    - coso_AnimalMaterialSample
    - coso_AnimalMilkSample
    - coso_AnimalOrganSample
    - coso_AnimalTissueSample
    - coso_PlantMaterialSample
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
    - http___w3id.org_sawgraph_v1_us-wqp#Sample
    - me_egad_EGAD-Sample
    union_of:
    - owl_Thing
    - coso_MaterialSample
    - sosa_Sample
    range: Any
    any_of:
    - range: obo_FOODON_03411183
    - range: obo_FOODON_03411057
    - range: obo_NCBITaxon_283036
    - range: obo_FOODON_02010107
    - range: http___w3id.org_sawgraph_v1_us-wqp#SampleMedia
    - range: obo_FOODON_00003572
    - range: __B37977f50d3140da51a9630b8a57396a1
    - range: obo_FOODON_03420147
    - range: __B215b3a432e1c482d3680398a554edbbf
    - range: me_egad_EGAD-SampleMaterialTypeQualifier
    - range: __B036a3008450d6ce37e35cf5a98355a60
    - range: obo_NCBITaxon_66912
    - range: obo_NCBITaxon_7971
    - range: obo_FOODON_03411566
    - range: obo_FOODON_03420194
    - range: obo_NCBITaxon_381124
    - range: __Bf584e1bfd1c74de0eb37e7b926538b83
    - range: obo_FOODON_00001093
    - range: http___w3id.org_sawgraph_v1_us-wqp#Taxon
    - range: obo_NCBITaxon_8022
    - range: __B44bec873efc8b96cad5f525429c64e0a
    - range: obo_FOODON_00002477
    - range: owl_Thing
    - range: __B27231c83f17c76e178e0c9f5e10acc55
    - range: obo_NCBITaxon_6550
    - range: obo_FOODON_02021651
    - range: __Ba6d85f816540f9fec5b71ba42fc2cca6
    - range: coso_WaterSample
    - range: obo_NCBITaxon_225389
    - range: __B423a0e253807f20386fc3ccbbd7e0378
    - range: me_egad_EGAD-SampleMaterialType
    - range: obo_NCBITaxon_8182
    - range: obo_FOODON_02010012
    - range: __Bbefc37cbdd03cae92dadef76b34dbf16
    - range: obo_FOODON_03420150
    - range: __B085dcda89ed6aae0d3b229e767f0a1ca
    - range: __Bb0125be5bc4dc7be7e8452e7d22445f6
    - range: __B0d427a711311f1499a234aa8af2c66d1
    - range: obo_FOODON_03411236
    - range: obo_NCBITaxon_6604
    - range: obo_FOODON_03301761
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleMaterialType
    - range: __B7728f65369357f97de36b133c9d1d5e0
    - range: __Be047d68edc8eb3ce96d7edbad5217bfc
    - range: obo_NCBITaxon_8032
    - range: obo_FOODON_03420181
    - range: obo_FOODON_02010045
    - range: obo_NCBITaxon_154811
    - range: obo_NCBITaxon_27778
    - range: __Be497d3b0c2656040c05e303873a2d541
    - range: obo_FOODON_00004460
    - range: __Beb77c26f8c395403edc359fd5f6dfb28
    - range: __B611b8dff312692e7f32a69834c787a60
    - range: obo_FOODON_03411324
    - range: __B75e45ed04b2b903b9029968cada06faa
    - range: obo_FOODON_03420116
    - range: obo_NCBITaxon_225060
    - range: __B75dbc5841338872cea35dced609fcd77
    - range: coso_SampleMaterialType
    - range: obo_FOODON_00003083
    - range: obo_NCBITaxon_147949
    - range: obo_FOODON_03411325
    - range: obo_NCBITaxon_7998
    - range: obo_NCBITaxon_8010
    - range: __B3cc7b3721547b07a4068dc98b6444b8b
    - range: obo_NCBITaxon_8038
    - range: obo_NCBITaxon_184451
    - range: obo_FOODON_02010015
    - range: __Bbf63deb85414ddecd89e46bce27e7f0a
    - range: obo_FOODON_00004172
    - range: obo_FOODON_03411457
    - range: obo_NCBITaxon_75288
    - range: obo_FOODON_03413378
    - range: obo_FOODON_02010042
    - range: __B4fd286b2a5a12e342d61412628b6e4c2
    - range: __Bf04685c17c0e71ae3c98e08c75cbdfcc
    - range: __B623b56ef58fd82dd088819e22d655c08
    - range: obo_FOODON_00003425
    - range: __B5e93e815b548435105d9273d424fa0e8
    - range: obo_FOODON_00002165
    - range: obo_FOODON_03411669
    - range: __B53622dee107de372b2d0566f64ab6e3a
    - range: obo_NCBITaxon_8167
    - range: obo_FOODON_02020892
    - range: obo_NCBITaxon_27706
    - range: http___w3id.org_sawgraph_v1_us-wqp#TaxonGroup.FishNekton
    - range: obo_FOODON_00003042
    - range: obo_FOODON_02021803
    - range: obo_NCBITaxon_46259
    - range: obo_NCBITaxon_34816
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleMaterialTypeQualifier
    - range: __Bb71af62f2f3e5e5b5e0fe81f24eca409
    - range: obo_NCBITaxon_66913
    - range: obo_FOODON_03411583
    - range: obo_FOODON_03411328
    - range: obo_FOODON_00004436
    - range: obo_FOODON_02021805
    - range: obo_FOODON_03413358
    - range: obo_FOODON_02010032
    - range: obo_FOODON_02020840
    - range: obo_NCBITaxon_126735
    - range: owl_NamedIndividual
    - range: obo_NCBITaxon_13106
    - range: __B8aa8791a0418cd594c8b56ad21351f72
    - range: __B00af777bec4da87c5aebb51d94b2d478
  coso_fromSamplePoint:
    name: coso_fromSamplePoint
    description: A relation between a physical material sample and the location where
      the sample was taken.
    title: from sample point
    from_schema: okns:sawgraph-kg
    rank: 1000
    slot_uri: coso:fromSamplePoint
    alias: coso_fromSamplePoint
    owner: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    domain_of:
    - coso_AnimalBloodSample
    - coso_AnimalMaterialSample
    - coso_AnimalMilkSample
    - coso_AnimalOrganSample
    - coso_AnimalTissueSample
    - coso_PlantMaterialSample
    - http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
    - http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
    - http___w3id.org_sawgraph_v1_us-wqp#Sample
    - me_egad_EGAD-Sample
    union_of:
    - owl_Thing
    - coso_MaterialSample
    - sosa_Sample
    range: Any
    any_of:
    - range: geo_Feature
    - range: uri
    - range: http___w3id.org_sawgraph_v1_us-wqp#Site
    - range: owl_Thing
    - range: me_egad_EGAD-SamplePoint
    - range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
    - range: geo_SpatialObject
    - range: coso_SamplePoint
    - range: sosa_FeatureOfInterest
    - range: coso_Point
class_uri: http://w3id.org/sawgraph/v1/me-egad-data#DefEGADGroundWaterSample

```
</details>