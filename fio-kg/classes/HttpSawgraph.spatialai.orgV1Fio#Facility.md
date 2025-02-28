

# Class: No class (type) name specified (http___sawgraph.spatialai.org_v1_fio#Facility)


_No class (type) description specified_





URI: [http://sawgraph.spatialai.org/v1/fio#Facility](http://sawgraph.spatialai.org/v1/fio#Facility)






```mermaid
 classDiagram
    class HttpSawgraph.spatialai.orgV1Fio#Facility
    click HttpSawgraph.spatialai.orgV1Fio#Facility href "../HttpSawgraph.spatialai.orgV1Fio#Facility"
      B1 <|-- HttpSawgraph.spatialai.orgV1Fio#Facility
        click B1 href "../B1"
      

      HttpSawgraph.spatialai.orgV1Fio#Facility <|-- UsfrsFRS-Facility
        click UsfrsFRS-Facility href "../UsfrsFRS-Facility"
      
      
      HttpSawgraph.spatialai.orgV1Fio#Facility : geo_hasGeometry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Uri : geo_hasGeometry
    click Uri href "../Uri"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : http___sawgraph.spatialai.org_v1_fio#ofAgency
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : http___sawgraph.spatialai.org_v1_fio#ofAgency
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : http___sawgraph.spatialai.org_v1_fio#ofIndustry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : http___sawgraph.spatialai.org_v1_fio#ofIndustry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : http___stko_kwg.geog.ucsb.edu_lod_ontology_sfWithin
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Uri : http___stko_kwg.geog.ucsb.edu_lod_ontology_sfWithin
    click Uri href "../Uri"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : http___stko_kwg.geog.ucsb.edu_lod_ontology_spatialRelation
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : http___stko_kwg.geog.ucsb.edu_lod_ontology_spatialRelation
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : rdfs_label
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_aces_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_aces_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_air_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_air_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_airs_afs_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_airs_afs_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_caaIndustry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_caaIndustry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_camdbs_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_camdbs_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_cedri_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_cedri_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_cwaIndustry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_cwaIndustry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_e_ggrt_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_e_ggrt_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_ecrm_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Uri : usfrs_ecrm_Industry
    click Uri href "../Uri"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_eia_860_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_eia_860_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_eis_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_eis_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_environmentalInterestType
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_environmentalInterestType
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_epcraIndustry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_epcraIndustry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_eps_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_eps_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_fifraIndustry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Uri : usfrs_fifraIndustry
    click Uri href "../Uri"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasACESId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasACESId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasAIRId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasAIRId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasAIRSAFSId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasAIRSAFSId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasCAMDBSId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasCAMDBSId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasCEDRIId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasCEDRIId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasECRMId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasECRMId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasEGGRTId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasEGGRTId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasEIA860Id
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasEIA860Id
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasEISId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasEISId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasEPSId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasEPSId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasFRSId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasFRSId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasICISId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasICISId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasMEEFISId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasMEEFISId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasMNTEMPOId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasMNTEMPOId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasNJNJEMSId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasNJNJEMSId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasNPDESId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasNPDESId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasOSHAOISId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasOSHAOISId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasRCRAINFOId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasRCRAINFOId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasRMPId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasRMPId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_hasTRISId
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" String : usfrs_hasTRISId
    click String href "../String"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_icis_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_icis_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_me_efis_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_me_efis_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_mn_tempo_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_mn_tempo_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_ncdb_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Uri : usfrs_ncdb_Industry
    click Uri href "../Uri"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_nj_njems_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_nj_njems_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_npdes_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_npdes_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_nv_fp_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Uri : usfrs_nv_fp_Industry
    click Uri href "../Uri"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_oh_core_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Uri : usfrs_oh_core_Industry
    click Uri href "../Uri"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_osha_ois_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_osha_ois_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_primaryIndustry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_primaryIndustry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_rblc_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Uri : usfrs_rblc_Industry
    click Uri href "../Uri"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_rcrainfo_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_rcrainfo_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_rmp_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_rmp_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_secondaryIndustry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_secondaryIndustry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_ssts_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Uri : usfrs_ssts_Industry
    click Uri href "../Uri"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_stateIndustry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_stateIndustry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_tris_Industry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Any : usfrs_tris_Industry
    click Any href "../Any"

        
      HttpSawgraph.spatialai.orgV1Fio#Facility : usfrs_tscaIndustry
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Facility --> "0..1" Uri : usfrs_tscaIndustry
    click Uri href "../Uri"

        
      
```





## Inheritance
* [B1](../classes/B1.md)
    * **HttpSawgraph.spatialai.orgV1Fio#Facility**
        * [UsfrsFRS-Facility](../classes/UsfrsFRS-Facility.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [usfrs_me_efis_Industry](../slots/usfrs_me_efis_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_hasRMPId](../slots/usfrs_hasRMPId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_hasCAMDBSId](../slots/usfrs_hasCAMDBSId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_hasICISId](../slots/usfrs_hasICISId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [http___stko_kwg.geog.ucsb.edu_lod_ontology_spatialRelation](../slots/http___stko_kwg.geog.ucsb.edu_lod_ontology_spatialRelation.md) | 0..1 <br/> [B1](../classes/B1.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_hasEIA860Id](../slots/usfrs_hasEIA860Id.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [geo_hasGeometry](../slots/geo_hasGeometry.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_ssts_Industry](../slots/usfrs_ssts_Industry.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Section Seven Tracking System (pesticides programs) Industry Code | [B1](../classes/B1.md) |
| [usfrs_hasEISId](../slots/usfrs_hasEISId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_osha_ois_Industry](../slots/usfrs_osha_ois_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Occupational Safety and Health Administration Information System Industry Cod... | [B1](../classes/B1.md) |
| [usfrs_hasFRSId](../slots/usfrs_hasFRSId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_nv_fp_Industry](../slots/usfrs_nv_fp_Industry.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_e_ggrt_Industry](../slots/usfrs_e_ggrt_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Electronic Greenhous Gas Reporting Tool Industry Code | [B1](../classes/B1.md) |
| [usfrs_eis_Industry](../slots/usfrs_eis_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Emissions Inventory System Industry Code | [B1](../classes/B1.md) |
| [usfrs_hasMNTEMPOId](../slots/usfrs_hasMNTEMPOId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_ncdb_Industry](../slots/usfrs_ncdb_Industry.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | National Compliance Database System (pesticide/ toxic substances programs) In... | [B1](../classes/B1.md) |
| [usfrs_rblc_Industry](../slots/usfrs_rblc_Industry.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | RACT/BACT/LAER CLEARINGHOUSE Industry Code | [B1](../classes/B1.md) |
| [usfrs_rmp_Industry](../slots/usfrs_rmp_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Risk Management Plan Industry Code | [B1](../classes/B1.md) |
| [usfrs_rcrainfo_Industry](../slots/usfrs_rcrainfo_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_tscaIndustry](../slots/usfrs_tscaIndustry.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Toxic Substances Control Act Industry Code | [B1](../classes/B1.md) |
| [usfrs_mn_tempo_Industry](../slots/usfrs_mn_tempo_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_hasRCRAINFOId](../slots/usfrs_hasRCRAINFOId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_hasAIRId](../slots/usfrs_hasAIRId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_hasEPSId](../slots/usfrs_hasEPSId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_hasOSHAOISId](../slots/usfrs_hasOSHAOISId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_oh_core_Industry](../slots/usfrs_oh_core_Industry.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_eia_860_Industry](../slots/usfrs_eia_860_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Energy Information Administration-860 database Industry Code | [B1](../classes/B1.md) |
| [usfrs_caaIndustry](../slots/usfrs_caaIndustry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Clean Air Act (Air) programs Industry Code | [B1](../classes/B1.md) |
| [usfrs_hasECRMId](../slots/usfrs_hasECRMId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_ecrm_Industry](../slots/usfrs_ecrm_Industry.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_hasACESId](../slots/usfrs_hasACESId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_nj_njems_Industry](../slots/usfrs_nj_njems_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_hasEGGRTId](../slots/usfrs_hasEGGRTId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_cwaIndustry](../slots/usfrs_cwaIndustry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Clean Water Act programs Industry Code | [B1](../classes/B1.md) |
| [usfrs_hasMEEFISId](../slots/usfrs_hasMEEFISId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_environmentalInterestType](../slots/usfrs_environmentalInterestType.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_cedri_Industry](../slots/usfrs_cedri_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Compliance and Emissions data reporting Interface Industry Code | [B1](../classes/B1.md) |
| [usfrs_hasNJNJEMSId](../slots/usfrs_hasNJNJEMSId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_hasTRISId](../slots/usfrs_hasTRISId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_primaryIndustry](../slots/usfrs_primaryIndustry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_camdbs_Industry](../slots/usfrs_camdbs_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | CAM (Compliance Assurance Monitoring) database system Industry Code | [B1](../classes/B1.md) |
| [usfrs_airs_afs_Industry](../slots/usfrs_airs_afs_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_epcraIndustry](../slots/usfrs_epcraIndustry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Emergency Planning and Community Right-to-Know Act Industry Code | [B1](../classes/B1.md) |
| [usfrs_hasNPDESId](../slots/usfrs_hasNPDESId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_secondaryIndustry](../slots/usfrs_secondaryIndustry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_aces_Industry](../slots/usfrs_aces_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [http___stko_kwg.geog.ucsb.edu_lod_ontology_sfWithin](../slots/http___stko_kwg.geog.ucsb.edu_lod_ontology_sfWithin.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_air_Industry](../slots/usfrs_air_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_fifraIndustry](../slots/usfrs_fifraIndustry.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Federal Insecticide, Fungicide and Rodenticide Act Industry Code | [B1](../classes/B1.md) |
| [usfrs_icis_Industry](../slots/usfrs_icis_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Integrated Compliance Information System Industry Code | [B1](../classes/B1.md) |
| [usfrs_eps_Industry](../slots/usfrs_eps_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Electronic Permit System Industry Code | [B1](../classes/B1.md) |
| [usfrs_hasAIRSAFSId](../slots/usfrs_hasAIRSAFSId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_hasCEDRIId](../slots/usfrs_hasCEDRIId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | [B1](../classes/B1.md) |
| [usfrs_stateIndustry](../slots/usfrs_stateIndustry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | State programs Industry Code | [B1](../classes/B1.md) |
| [usfrs_npdes_Industry](../slots/usfrs_npdes_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | National Pollutant Discharge Elimination system Industry Code | [B1](../classes/B1.md) |
| [usfrs_tris_Industry](../slots/usfrs_tris_Industry.md) | 0..1 <br/> [HttpSawgraph.spatialai.orgV1Fio#Industry](../classes/HttpSawgraph.spatialai.orgV1Fio#Industry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | Toxic Release Inventory program Industry Code | [B1](../classes/B1.md) |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [B1](../classes/B1.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [B1](../classes/B1.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsBarge-Facility](../classes/UsfrsBarge-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsBarge-Facility](../classes/UsfrsBarge-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsBrownfieldsSite-Facility](../classes/UsfrsBrownfieldsSite-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsBrownfieldsSite-Facility](../classes/UsfrsBrownfieldsSite-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsContaminatedSite-Facility](../classes/UsfrsContaminatedSite-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsContaminatedSite-Facility](../classes/UsfrsContaminatedSite-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsContaminationAddressed-Facility](../classes/UsfrsContaminationAddressed-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsContaminationAddressed-Facility](../classes/UsfrsContaminationAddressed-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsEPA-PFAS-Facility](../classes/UsfrsEPA-PFAS-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsEPA-PFAS-Facility](../classes/UsfrsEPA-PFAS-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsFRS-Facility](../classes/UsfrsFRS-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsFRS-Facility](../classes/UsfrsFRS-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsFederal-Facility](../classes/UsfrsFederal-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsFederal-Facility](../classes/UsfrsFederal-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsMonitoringStation-Facility](../classes/UsfrsMonitoringStation-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsMonitoringStation-Facility](../classes/UsfrsMonitoringStation-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsPortable-Facility](../classes/UsfrsPortable-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsPortable-Facility](../classes/UsfrsPortable-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsPotentiallyContaminatedSite-Facility](../classes/UsfrsPotentiallyContaminatedSite-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsPotentiallyContaminatedSite-Facility](../classes/UsfrsPotentiallyContaminatedSite-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsStationary-Facility](../classes/UsfrsStationary-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsStationary-Facility](../classes/UsfrsStationary-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsWaterSystem-Facility](../classes/UsfrsWaterSystem-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsWaterSystem-Facility](../classes/UsfrsWaterSystem-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsWaterfrontFacility-Facility](../classes/UsfrsWaterfrontFacility-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofIndustry](../slots/http___sawgraph.spatialai.org_v1_fio#ofIndustry.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |
| [UsfrsWaterfrontFacility-Facility](../classes/UsfrsWaterfrontFacility-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | domain | [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) |






## Identifier and Mapping Information







### Schema Source


* from schema: fio-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://sawgraph.spatialai.org/v1/fio#Facility |
| native | fio-kg/:HttpSawgraph.spatialai.orgV1Fio#Facility |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: http___sawgraph.spatialai.org_v1_fio#Facility
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 300936 occurrences.
from_schema: fio-kg
rank: 1000
is_a: __b1
class_uri: http://sawgraph.spatialai.org/v1/fio#Facility

```
</details>

### Induced

<details>
```yaml
name: http___sawgraph.spatialai.org_v1_fio#Facility
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 300936 occurrences.
from_schema: fio-kg
rank: 1000
is_a: __b1
attributes:
  usfrs_me-efis-Industry:
    name: usfrs_me-efis-Industry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 1482 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 2085 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110071441892 usfrs:me-efis-Industry naics:NAICS-IndustryCode-321113
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:me-efis-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3724
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:me-efis-Industry
    alias: usfrs_me_efis_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: usfrs_stateIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_hasRMPId:
    name: usfrs_hasRMPId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 1951 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314375 usfrs:hasRMPId 100000184392
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasRMPId
    alias: usfrs_hasRMPId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_hasCAMDBSId:
    name: usfrs_hasCAMDBSId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 200 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000382069 usfrs:hasCAMDBSId 2843
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasCAMDBSId
    alias: usfrs_hasCAMDBSId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_hasICISId:
    name: usfrs_hasICISId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 1065 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000383166 usfrs:hasICISId 6679785
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasICISId
    alias: usfrs_hasICISId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  http___stko-kwg.geog.ucsb.edu_lod_ontology_spatialRelation:
    name: http___stko-kwg.geog.ucsb.edu_lod_ontology_spatialRelation
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 716825 occurrences with untyped subjects and object type _:b1.
    - 716825 occurrences with subject type __b1 and object type uri.
    examples:
    - value: https://datacommons.org/browser/geoId/2303187985 http://stko-kwg.geog.ucsb.edu/lod/ontology/spatialRelation
        usfrsdata:d.FRS-Facility.110071537786
    - value: usfrsdata:d.FRS-Facility.110000314204 http://stko-kwg.geog.ucsb.edu/lod/ontology/spatialRelation
        http://stko-kwg.geog.ucsb.edu/lod/resource/administrativeRegion.USA.23031
    from_schema: fio-kg
    rank: 1000
    slot_uri: http://stko-kwg.geog.ucsb.edu/lod/ontology/spatialRelation
    alias: http___stko_kwg.geog.ucsb.edu_lod_ontology_spatialRelation
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: Any
    any_of:
    - range: __b1
    - range: uri
  usfrs_hasEIA860Id:
    name: usfrs_hasEIA860Id
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 23 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000389847 usfrs:hasEIA860Id 54207
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasEIA860Id
    alias: usfrs_hasEIA860Id
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  geo_hasGeometry:
    name: geo_hasGeometry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 210390 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 geo:hasGeometry usfrsdata:d.FRS-Facility-Geometry.110000314204
    from_schema: fio-kg
    rank: 1000
    slot_uri: geo:hasGeometry
    alias: geo_hasGeometry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: uri
  http___sawgraph.spatialai.org_v1_fio#ofIndustry:
    name: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 71468 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 68041 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110071441892 http://sawgraph.spatialai.org/v1/fio#ofIndustry
        naics:NAICS-IndustryCode-321113
    - value: usfrsdata:d.FRS-Facility.110000314204 http://sawgraph.spatialai.org/v1/fio#ofIndustry
        http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3724
    from_schema: fio-kg
    rank: 1000
    domain: http___sawgraph.spatialai.org_v1_fio#Facility
    slot_uri: http://sawgraph.spatialai.org/v1/fio#ofIndustry
    alias: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_ssts-Industry:
    name: usfrs_ssts-Industry
    description: Section Seven Tracking System (pesticides programs) Industry Code
    title: No slot (predicate) name specified
    comments:
    - 1797 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314384 usfrs:ssts-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3699
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:ssts-Industry
    alias: usfrs_ssts_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: usfrs_fifraIndustry
    range: uri
  usfrs_hasEISId:
    name: usfrs_hasEISId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 15807 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:hasEISId 8024911
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasEISId
    alias: usfrs_hasEISId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_osha-ois-Industry:
    name: usfrs_osha-ois-Industry
    description: Occupational Safety and Health Administration Information System
      Industry Code
    title: No slot (predicate) name specified
    comments:
    - 6130 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 1474 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110070347958 usfrs:osha-ois-Industry naics:NAICS-IndustryCode-321113
    - value: usfrsdata:d.FRS-Facility.110000314240 usfrs:osha-ois-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3732
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:osha-ois-Industry
    alias: usfrs_osha_ois_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_hasFRSId:
    name: usfrs_hasFRSId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 300920 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:hasFRSId 110000314204
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasFRSId
    alias: usfrs_hasFRSId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_nv-fp-Industry:
    name: usfrs_nv-fp-Industry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 1 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110059863376 usfrs:nv-fp-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3089
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:nv-fp-Industry
    alias: usfrs_nv_fp_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: uri
  usfrs_e-ggrt-Industry:
    name: usfrs_e-ggrt-Industry
    description: Electronic Greenhous Gas Reporting Tool Industry Code
    title: No slot (predicate) name specified
    comments:
    - 510 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 24 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110071232175 usfrs:e-ggrt-Industry naics:NAICS-IndustryCode-325199
    - value: usfrsdata:d.FRS-Facility.110000385164 usfrs:e-ggrt-Industry naics:NAICS-IndustryCode-336111
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:e-ggrt-Industry
    alias: usfrs_e_ggrt_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: usfrs_caaIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_eis-Industry:
    name: usfrs_eis-Industry
    description: Emissions Inventory System Industry Code
    title: No slot (predicate) name specified
    comments:
    - 15210 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 465 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110071314778 usfrs:eis-Industry naics:NAICS-IndustryCode-327992
    - value: usfrsdata:d.FRS-Facility.110000314455 usfrs:eis-Industry naics:NAICS-IndustryCode-322121
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:eis-Industry
    alias: usfrs_eis_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: usfrs_caaIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_hasMNTEMPOId:
    name: usfrs_hasMNTEMPOId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 6 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110005824867 usfrs:hasMNTEMPOId 50326
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasMNTEMPOId
    alias: usfrs_hasMNTEMPOId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_ncdb-Industry:
    name: usfrs_ncdb-Industry
    description: National Compliance Database System (pesticide/ toxic substances
      programs) Industry Code
    title: No slot (predicate) name specified
    comments:
    - 536 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314464 usfrs:ncdb-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3441
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:ncdb-Industry
    alias: usfrs_ncdb_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: usfrs_tscaIndustry
    range: uri
  usfrs_rblc-Industry:
    name: usfrs_rblc-Industry
    description: RACT/BACT/LAER CLEARINGHOUSE Industry Code
    title: No slot (predicate) name specified
    comments:
    - 126 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314570 usfrs:rblc-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-2611
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:rblc-Industry
    alias: usfrs_rblc_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: usfrs_caaIndustry
    range: uri
  usfrs_rmp-Industry:
    name: usfrs_rmp-Industry
    description: Risk Management Plan Industry Code
    title: No slot (predicate) name specified
    comments:
    - 2212 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 135 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110071649276 usfrs:rmp-Industry naics:NAICS-IndustryCode-49311
    - value: usfrsdata:d.FRS-Facility.110000314507 usfrs:rmp-Industry naics:NAICS-IndustryCode-33511
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:rmp-Industry
    alias: usfrs_rmp_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_rcrainfo-Industry:
    name: usfrs_rcrainfo-Industry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 25770 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 7132 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110018896523 usfrs:rcrainfo-Industry naics:NAICS-IndustryCode-562211
    - value: usfrsdata:d.FRS-Facility.110000314455 usfrs:rcrainfo-Industry naics:NAICS-IndustryCode-322121
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:rcrainfo-Industry
    alias: usfrs_rcrainfo_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_tscaIndustry:
    name: usfrs_tscaIndustry
    description: Toxic Substances Control Act Industry Code
    title: No slot (predicate) name specified
    comments:
    - 536 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314464 usfrs:tscaIndustry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3441
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:tscaIndustry
    alias: usfrs_tscaIndustry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: uri
  usfrs_mn-tempo-Industry:
    name: usfrs_mn-tempo-Industry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 19 occurrences with subject type __b1 and object type uri.
    - 6 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    examples:
    - value: usfrsdata:d.FRS-Facility.110001342690 usfrs:mn-tempo-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-0919
    - value: usfrsdata:d.FRS-Facility.110069137008 usfrs:mn-tempo-Industry naics:NAICS-IndustryCode-811121
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:mn-tempo-Industry
    alias: usfrs_mn_tempo_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_hasRCRAINFOId:
    name: usfrs_hasRCRAINFOId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 30246 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:hasRCRAINFOId MED000791681
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasRCRAINFOId
    alias: usfrs_hasRCRAINFOId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_hasAIRId:
    name: usfrs_hasAIRId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 22529 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:hasAIRId ME0000002303100002
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasAIRId
    alias: usfrs_hasAIRId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_hasEPSId:
    name: usfrs_hasEPSId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 29 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314393 usfrs:hasEPSId EPS10053496
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasEPSId
    alias: usfrs_hasEPSId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_hasOSHAOISId:
    name: usfrs_hasOSHAOISId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 10004 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:hasOSHAOISId 342133618
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasOSHAOISId
    alias: usfrs_hasOSHAOISId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_oh-core-Industry:
    name: usfrs_oh-core-Industry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 14161 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000381337 usfrs:oh-core-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-2731
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:oh-core-Industry
    alias: usfrs_oh_core_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: uri
  usfrs_eia-860-Industry:
    name: usfrs_eia-860-Industry
    description: Energy Information Administration-860 database Industry Code
    title: No slot (predicate) name specified
    comments:
    - 18 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 5 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110070665765 usfrs:eia-860-Industry naics:NAICS-IndustryCode-32731
    - value: usfrsdata:d.FRS-Facility.110000395117 usfrs:eia-860-Industry naics:NAICS-IndustryCode-322122
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:eia-860-Industry
    alias: usfrs_eia_860_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_caaIndustry:
    name: usfrs_caaIndustry
    description: Clean Air Act (Air) programs Industry Code
    title: No slot (predicate) name specified
    comments:
    - 36246 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 41982 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110071314778 usfrs:caaIndustry naics:NAICS-IndustryCode-327992
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:caaIndustry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3724
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:caaIndustry
    alias: usfrs_caaIndustry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_hasECRMId:
    name: usfrs_hasECRMId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 1 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110028675958 usfrs:hasECRMId 103
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasECRMId
    alias: usfrs_hasECRMId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_ecrm-Industry:
    name: usfrs_ecrm-Industry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 1 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110028675958 usfrs:ecrm-Industry naics:NAICS-IndustryCode-421510
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:ecrm-Industry
    alias: usfrs_ecrm_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: uri
  usfrs_hasACESId:
    name: usfrs_hasACESId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 80 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000429821 usfrs:hasACESId 170000102270
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasACESId
    alias: usfrs_hasACESId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_nj-njems-Industry:
    name: usfrs_nj-njems-Industry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 3 occurrences with subject type __b1 and object type uri.
    - 3 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    examples:
    - value: usfrsdata:d.FRS-Facility.110014836357 usfrs:nj-njems-Industry naics:NAICS-IndustryCode-517110
    - value: usfrsdata:d.FRS-Facility.110070611273 usfrs:nj-njems-Industry naics:NAICS-IndustryCode-621111
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:nj-njems-Industry
    alias: usfrs_nj_njems_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_hasEGGRTId:
    name: usfrs_hasEGGRTId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 497 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314375 usfrs:hasEGGRTId 1009581
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasEGGRTId
    alias: usfrs_hasEGGRTId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_cwaIndustry:
    name: usfrs_cwaIndustry
    description: Clean Water Act programs Industry Code
    title: No slot (predicate) name specified
    comments:
    - 9162 occurrences with subject type __b1 and object type uri.
    - 110 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:cwaIndustry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3724
    - value: usfrsdata:d.FRS-Facility.110071358118 usfrs:cwaIndustry naics:NAICS-IndustryCode-721191
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:cwaIndustry
    alias: usfrs_cwaIndustry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_hasMEEFISId:
    name: usfrs_hasMEEFISId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 1723 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:hasMEEFISId FN000000001212506427
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasMEEFISId
    alias: usfrs_hasMEEFISId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_environmentalInterestType:
    name: usfrs_environmentalInterestType
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 100661 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:environmentalInterestType
        AIR SYNTHETIC MINOR
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:environmentalInterestType
    alias: usfrs_environmentalInterestType
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_cedri-Industry:
    name: usfrs_cedri-Industry
    description: Compliance and Emissions data reporting Interface Industry Code
    title: No slot (predicate) name specified
    comments:
    - 1 occurrences with subject type __b1 and object type uri.
    - 37 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000382979 usfrs:cedri-Industry naics:NAICS-IndustryCode-336112
    - value: usfrsdata:d.FRS-Facility.110071343304 usfrs:cedri-Industry naics:NAICS-IndustryCode-327310
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:cedri-Industry
    alias: usfrs_cedri_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: usfrs_caaIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_hasNJNJEMSId:
    name: usfrs_hasNJNJEMSId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 4 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110014836357 usfrs:hasNJNJEMSId 124450
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasNJNJEMSId
    alias: usfrs_hasNJNJEMSId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  rdfs_label:
    name: rdfs_label
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 15 occurrences with subject type http___sawgraph.spatialai.org_v1_fio#Agency
      and object type string.
    - 2129 occurrences with subject type http___sawgraph.spatialai.org_v1_fio#Industry
      and object type string.
    - 300917 occurrences with subject type __b1 and object type string.
    examples:
    - value: 'http://sawgraph.spatialai.org/v1/fio#d.Agency.C1017 rdfs:label Agriculture:
        Agricultural Research Service'
    - value: naics:NAICS-IndustryCode-11111 rdfs:label Soybean Farming
    - value: usfrsdata:d.FRS-Facility.110000314204 rdfs:label PRATT & WHITNEY
    from_schema: fio-kg
    rank: 1000
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    - http___sawgraph.spatialai.org_v1_fio#Agency
    - http___sawgraph.spatialai.org_v1_fio#Industry
    range: Any
    any_of:
    - range: uri
    - range: string
  http___sawgraph.spatialai.org_v1_fio#ofAgency:
    name: http___sawgraph.spatialai.org_v1_fio#ofAgency
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 44 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Agency.
    examples:
    - value: usfrsdata:d.FRS-Facility.110064794496 http://sawgraph.spatialai.org/v1/fio#ofAgency
        http://sawgraph.spatialai.org/v1/fio#d.Agency.D2100
    from_schema: fio-kg
    rank: 1000
    domain: http___sawgraph.spatialai.org_v1_fio#Facility
    slot_uri: http://sawgraph.spatialai.org/v1/fio#ofAgency
    alias: http___sawgraph.spatialai.org_v1_fio#ofAgency
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: Any
    any_of:
    - range: uri
    - range: http___sawgraph.spatialai.org_v1_fio#Agency
  usfrs_hasTRISId:
    name: usfrs_hasTRISId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 6452 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:hasTRISId 03906PRTTWROUTE
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasTRISId
    alias: usfrs_hasTRISId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_primaryIndustry:
    name: usfrs_primaryIndustry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 66519 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 62931 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110071441892 usfrs:primaryIndustry naics:NAICS-IndustryCode-321113
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:primaryIndustry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3724
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:primaryIndustry
    alias: usfrs_primaryIndustry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_camdbs-Industry:
    name: usfrs_camdbs-Industry
    description: CAM (Compliance Assurance Monitoring) database system Industry Code
    title: No slot (predicate) name specified
    comments:
    - 196 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 102 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110070828208 usfrs:camdbs-Industry naics:NAICS-IndustryCode-221112
    - value: usfrsdata:d.FRS-Facility.110000382069 usfrs:camdbs-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-4911
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:camdbs-Industry
    alias: usfrs_camdbs_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: usfrs_caaIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_airs-afs-Industry:
    name: usfrs_airs-afs-Industry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 22236 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 30138 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110070834566 usfrs:airs-afs-Industry naics:NAICS-IndustryCode-221112
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:airs-afs-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3724
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:airs-afs-Industry
    alias: usfrs_airs_afs_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: usfrs_caaIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_epcraIndustry:
    name: usfrs_epcraIndustry
    description: Emergency Planning and Community Right-to-Know Act Industry Code
    title: No slot (predicate) name specified
    comments:
    - 6070 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 4402 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110071440284 usfrs:epcraIndustry naics:NAICS-IndustryCode-332919
    - value: usfrsdata:d.FRS-Facility.110000314231 usfrs:epcraIndustry naics:NAICS-IndustryCode-331111
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:epcraIndustry
    alias: usfrs_epcraIndustry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_hasNPDESId:
    name: usfrs_hasNPDESId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 112 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314357 usfrs:hasNPDESId ME0022314
    from_schema: fio-kg
    rank: 1000
    domain: usfrs_FRS-Facility
    slot_uri: usfrs:hasNPDESId
    alias: usfrs_hasNPDESId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_secondaryIndustry:
    name: usfrs_secondaryIndustry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 3345 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 3654 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110071328288 usfrs:secondaryIndustry naics:NAICS-IndustryCode-212319
    - value: usfrsdata:d.FRS-Facility.110000314357 usfrs:secondaryIndustry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-5171
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:secondaryIndustry
    alias: usfrs_secondaryIndustry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_aces-Industry:
    name: usfrs_aces-Industry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 177 occurrences with subject type __b1 and object type uri.
    - 70 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000429279 usfrs:aces-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-1521
    - value: usfrsdata:d.FRS-Facility.110064144750 usfrs:aces-Industry naics:NAICS-IndustryCode-324110
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:aces-Industry
    alias: usfrs_aces_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  http___stko-kwg.geog.ucsb.edu_lod_ontology_sfWithin:
    name: http___stko-kwg.geog.ucsb.edu_lod_ontology_sfWithin
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 716825 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 http://stko-kwg.geog.ucsb.edu/lod/ontology/sfWithin
        http://stko-kwg.geog.ucsb.edu/lod/resource/administrativeRegion.USA.23031
    from_schema: fio-kg
    rank: 1000
    slot_uri: http://stko-kwg.geog.ucsb.edu/lod/ontology/sfWithin
    alias: http___stko_kwg.geog.ucsb.edu_lod_ontology_sfWithin
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: uri
  usfrs_air-Industry:
    name: usfrs_air-Industry
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 19652 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 26036 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110070834566 usfrs:air-Industry naics:NAICS-IndustryCode-221112
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:air-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3724
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:air-Industry
    alias: usfrs_air_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: usfrs_caaIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_fifraIndustry:
    name: usfrs_fifraIndustry
    description: Federal Insecticide, Fungicide and Rodenticide Act Industry Code
    title: No slot (predicate) name specified
    comments:
    - 2331 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314384 usfrs:fifraIndustry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3699
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:fifraIndustry
    alias: usfrs_fifraIndustry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: uri
  usfrs_icis-Industry:
    name: usfrs_icis-Industry
    description: Integrated Compliance Information System Industry Code
    title: No slot (predicate) name specified
    comments:
    - 3856 occurrences with subject type __b1 and object type uri.
    - 1128 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314507 usfrs:icis-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-5065
    - value: usfrsdata:d.FRS-Facility.110070239066 usfrs:icis-Industry naics:NAICS-IndustryCode-486110
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:icis-Industry
    alias: usfrs_icis_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_eps-Industry:
    name: usfrs_eps-Industry
    description: Electronic Permit System Industry Code
    title: No slot (predicate) name specified
    comments:
    - 26 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 3 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110064777148 usfrs:eps-Industry naics:NAICS-IndustryCode-321113
    - value: usfrsdata:d.FRS-Facility.110008062602 usfrs:eps-Industry naics:NAICS-IndustryCode-322121
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:eps-Industry
    alias: usfrs_eps_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_hasAIRSAFSId:
    name: usfrs_hasAIRSAFSId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 26613 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:hasAIRSAFSId 2303100002
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasAIRSAFSId
    alias: usfrs_hasAIRSAFSId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_hasCEDRIId:
    name: usfrs_hasCEDRIId
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 38 occurrences with subject type __b1 and object type string.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000382979 usfrs:hasCEDRIId CEDRI82641
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:hasCEDRIId
    alias: usfrs_hasCEDRIId
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    range: string
  usfrs_stateIndustry:
    name: usfrs_stateIndustry
    description: State programs Industry Code
    title: No slot (predicate) name specified
    comments:
    - 1482 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 2085 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110071441892 usfrs:stateIndustry naics:NAICS-IndustryCode-321113
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:stateIndustry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3724
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:stateIndustry
    alias: usfrs_stateIndustry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: http___sawgraph.spatialai.org_v1_fio#ofIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_npdes-Industry:
    name: usfrs_npdes-Industry
    description: National Pollutant Discharge Elimination system Industry Code
    title: No slot (predicate) name specified
    comments:
    - 9162 occurrences with subject type __b1 and object type uri.
    - 110 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    examples:
    - value: usfrsdata:d.FRS-Facility.110000314204 usfrs:npdes-Industry http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3724
    - value: usfrsdata:d.FRS-Facility.110071358118 usfrs:npdes-Industry naics:NAICS-IndustryCode-721191
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:npdes-Industry
    alias: usfrs_npdes_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: usfrs_cwaIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
  usfrs_tris-Industry:
    name: usfrs_tris-Industry
    description: Toxic Release Inventory program Industry Code
    title: No slot (predicate) name specified
    comments:
    - 6070 occurrences with subject type __b1 and object type http___sawgraph.spatialai.org_v1_fio#Industry.
    - 4402 occurrences with subject type __b1 and object type uri.
    examples:
    - value: usfrsdata:d.FRS-Facility.110071440284 usfrs:tris-Industry naics:NAICS-IndustryCode-332919
    - value: usfrsdata:d.FRS-Facility.110000314231 usfrs:tris-Industry naics:NAICS-IndustryCode-331111
    from_schema: fio-kg
    rank: 1000
    slot_uri: usfrs:tris-Industry
    alias: usfrs_tris_Industry
    owner: http___sawgraph.spatialai.org_v1_fio#Facility
    domain_of:
    - __b1
    subproperty_of: usfrs_epcraIndustry
    range: Any
    any_of:
    - range: http___sawgraph.spatialai.org_v1_fio#Industry
    - range: uri
class_uri: http://sawgraph.spatialai.org/v1/fio#Facility

```
</details>