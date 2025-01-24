

# Class: No class name specified (rdfs_Resource)


_No class (type) description specified_





URI: [rdfs:Resource](http://www.w3.org/2000/01/rdf-schema#Resource)






```mermaid
 classDiagram
    class RdfsResource
    click RdfsResource href "../RdfsResource"
      RdfsResource : dc_description
        
          
    
    
    RdfsResource --> "0..1" String : dc_description
    click String href "../String"

        
      RdfsResource : dct_conformsTo
        
          
    
    
    RdfsResource --> "0..1" Any : dct_conformsTo
    click Any href "../Any"

        
      RdfsResource : dct_format
        
          
    
    
    RdfsResource --> "0..1" String : dct_format
    click String href "../String"

        
      RdfsResource : hsdo_name
        
          
    
    
    RdfsResource --> "0..1" String : hsdo_name
    click String href "../String"

        
      RdfsResource : hsdo_provider
        
          
    
    
    RdfsResource --> "0..1" Any : hsdo_provider
    click Any href "../Any"

        
      RdfsResource : hsdo_subjectOf
        
          
    
    
    RdfsResource --> "0..1" Any : hsdo_subjectOf
    click Any href "../Any"

        
      RdfsResource : http___geosciences.ca_def_hydraulic#contains
        
          
    
    
    RdfsResource --> "0..1" Uri : http___geosciences.ca_def_hydraulic#contains
    click Uri href "../Uri"

        
      RdfsResource : http___rdfs.org_ns_void#property
        
          
    
    
    RdfsResource --> "0..1" Uri : http___rdfs.org_ns_void#property
    click Uri href "../Uri"

        
      RdfsResource : http___rdfs.org_ns_void#target
        
          
    
    
    RdfsResource --> "0..1" Any : http___rdfs.org_ns_void#target
    click Any href "../Any"

        
      RdfsResource : http___www.opengeospatial.org_standards_geosparql_sfContains
        
          
    
    
    RdfsResource --> "0..1" HttpGeosciences.caDefGroundwater#GWWell : http___www.opengeospatial.org_standards_geosparql_sfContains
    click HttpGeosciences.caDefGroundwater#GWWell href "../HttpGeosciences.caDefGroundwater#GWWell"

        
      RdfsResource : http___www.opengeospatial.org_standards_geosparql_sfIntersects
        
          
    
    
    RdfsResource --> "0..1" Any : http___www.opengeospatial.org_standards_geosparql_sfIntersects
    click Any href "../Any"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_catchmentRealization
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_catchmentRealization
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment
        
          
    
    
    RdfsResource --> "0..1" Any : https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment
    click Any href "../Any"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_encompassingCatchment
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_encompassingCatchment
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_exorheicDrainage
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_exorheicDrainage
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_hydrometricNetwork
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_hydrometricNetwork
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_inflow
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_inflow
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_lowerCatchment
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_lowerCatchment
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_networkStation
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_networkStation
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_nexusRealization
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_nexusRealization
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_outflow
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_outflow
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_realizedCatchment
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_realizedCatchment
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_realizedNexus
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_realizedNexus
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_receivingCatchment
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_receivingCatchment
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : https___www.opengis.net_def_hy_features_ontology_hyf_upperCatchment
        
          
    
    
    RdfsResource --> "0..1" Any : https___www.opengis.net_def_hy_features_ontology_hyf_upperCatchment
    click Any href "../Any"

        
      RdfsResource : owl_equivalentClass
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : owl_equivalentClass
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : owl_sameAs
        
          
    
    
    RdfsResource --> "0..1" Any : owl_sameAs
    click Any href "../Any"

        
      RdfsResource : rdf_type
        
          
    
    
    RdfsResource --> "0..1" Uri : rdf_type
    click Uri href "../Uri"

        
      RdfsResource : rdfs_label
        
          
    
    
    RdfsResource --> "0..1" String : rdfs_label
    click String href "../String"

        
      RdfsResource : rdfs_subClassOf
        
          
    
    
    RdfsResource --> "0..1" RdfsResource : rdfs_subClassOf
    click RdfsResource href "../RdfsResource"

        
      RdfsResource : schema_provider
        
          
    
    
    RdfsResource --> "0..1" Any : schema_provider
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [https___www.opengis.net_def_hy_features_ontology_hyf_inflow](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_inflow.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 99 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | No slot (predicate) description specified <br/> 1498 occurrences with subject type rdfs_Resource and object type rdfs_Resource.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.<br/>5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type http___geosciences.ca_def_groundwater#GW_Well. | direct |
| [http___geosciences.ca_def_hydraulic#contains](../slots/http___geosciences.ca_def_hydraulic#contains.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) | No slot (predicate) description specified <br/> 1 occurrences with subject type rdfs_Resource and object type uri. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_realizedCatchment](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_realizedCatchment.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 789 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [http___www.opengeospatial.org_standards_geosparql_sfContains](../slots/http___www.opengeospatial.org_standards_geosparql_sfContains.md) | 0..1 <br/> [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | No slot (predicate) description specified <br/> 14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_Well.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type http___geosciences.ca_def_groundwater#GW_Well. | direct |
| [dc_description](../slots/dc_description.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.<br/>2 occurrences with subject type rdfs_Resource and object type string. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_networkStation](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_networkStation.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 74 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1514 occurrences with subject type rdfs_Resource and object type string.<br/>3204 occurrences with untyped subjects and object type string.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>5 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type string.<br/>5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type string. | direct |
| [rdf_type](../slots/rdf_type.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) | No slot (predicate) description specified <br/> 34 occurrences with subject type rdfs_Resource and object type uri. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_realizedNexus](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_realizedNexus.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 187 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [http___rdfs.org_ns_void#target](../slots/http___rdfs.org_ns_void#target.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | No slot (predicate) description specified <br/> 1 occurrences with subject type rdfs_Resource and object type http___rdfs.org_ns_void#Dataset.<br/>1 occurrences with subject type rdfs_Resource and object type uri. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_exorheicDrainage](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_exorheicDrainage.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 187 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [dct_format](../slots/dct_format.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 7697 occurrences with untyped subjects and object type string.<br/>3 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.<br/>6 occurrences with subject type rdfs_Resource and object type string. | direct |
| [rdfs_subClassOf](../slots/rdfs_subClassOf.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 43 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [http___www.opengeospatial.org_standards_geosparql_sfIntersects](../slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | No slot (predicate) description specified <br/> 14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type rdfs_Resource.<br/>13 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type uri.<br/>108 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.<br/>14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.<br/>108 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type rdfs_Resource. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_upperCatchment](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_upperCatchment.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 374 occurrences with subject type rdfs_Resource and object type rdfs_Resource.<br/>2 occurrences with subject type rdfs_Resource and object type uri. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_nexusRealization](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_nexusRealization.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 187 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 1 occurrences with subject type rdfs_Resource and object type uri.<br/>374 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_outflow](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_outflow.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 374 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [hsdo_subjectOf](../slots/hsdo_subjectOf.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | No slot (predicate) description specified <br/> 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type http___rdfs.org_ns_void#Dataset.<br/>2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type rdfs_Resource.<br/>3227 occurrences with subject type rdfs_Resource and object type uri.<br/>6 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type uri.<br/>15 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type uri. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_receivingCatchment](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_receivingCatchment.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 99 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [http___rdfs.org_ns_void#property](../slots/http___rdfs.org_ns_void#property.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) | No slot (predicate) description specified <br/> 1 occurrences with subject type rdfs_Resource and object type uri. | direct |
| [dct_conformsTo](../slots/dct_conformsTo.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string) | No slot (predicate) description specified <br/> 56432 occurrences with subject type schema_DataDownload and object type string.<br/>3194 occurrences with untyped subjects and object type uri.<br/>2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.<br/>4 occurrences with subject type rdfs_Resource and object type uri. | direct |
| [schema_provider](../slots/schema_provider.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[SchemaGovernmentOrganization](../classes/SchemaGovernmentOrganization.md)&nbsp;or&nbsp;<br />[schema_url](../slots/schema_url.md) | No slot (predicate) description specified <br/> 28216 occurrences with subject type schema_Dataset and object type schema_GovernmentOrganization.<br/>1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.<br/>2 occurrences with subject type rdfs_Resource and object type uri.<br/>98534 occurrences with subject type schema_Place and object type schema_url.<br/>185872 occurrences with subject type hyf__HY_HydroLocation and object type uri.<br/>13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_GovernmentOrganization. | direct |
| [owl_equivalentClass](../slots/owl_equivalentClass.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 17 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1 occurrences with subject type rdfs_Resource and object type string.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork and object type string.<br/>2 occurrences with subject type hsdo_Person and object type string.<br/>3 occurrences with subject type hsdo_Organization and object type string.<br/>48677 occurrences with subject type hsdo_WebPage and object type string.<br/>3 occurrences with subject type hsdo_ListItem and object type string.<br/>1 occurrences with subject type hsdo_WebSite and object type string. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_catchmentRealization](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_catchmentRealization.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 789 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [hsdo_provider](../slots/hsdo_provider.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string) | No slot (predicate) description specified <br/> 3194 occurrences with untyped subjects and object type uri.<br/>1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.<br/>2 occurrences with subject type rdfs_Resource and object type uri.<br/>48672 occurrences with subject type hsdo_WebPage and object type string. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_encompassingCatchment](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_encompassingCatchment.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 187 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_lowerCatchment](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_lowerCatchment.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 374 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |
| [https___www.opengis.net_def_hy_features_ontology_hyf_hydrometricNetwork](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_hydrometricNetwork.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 74 occurrences with subject type rdfs_Resource and object type rdfs_Resource. | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | [http___www.opengeospatial.org_standards_geosparql_sfIntersects](../slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | [hsdo_subjectOf](../slots/hsdo_subjectOf.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | [http___www.opengeospatial.org_standards_geosparql_sfIntersects](../slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | [http___www.opengeospatial.org_standards_geosparql_sfWithin](../slots/http___www.opengeospatial.org_standards_geosparql_sfWithin.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | [hsdo_subjectOf](../slots/hsdo_subjectOf.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | [hsdo_subjectOf](../slots/hsdo_subjectOf.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_inflow](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_inflow.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_realizedCatchment](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_realizedCatchment.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_networkStation](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_networkStation.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_realizedNexus](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_realizedNexus.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_exorheicDrainage](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_exorheicDrainage.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [rdfs_subClassOf](../slots/rdfs_subClassOf.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [http___www.opengeospatial.org_standards_geosparql_sfIntersects](../slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_upperCatchment](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_upperCatchment.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_nexusRealization](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_nexusRealization.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_outflow](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_outflow.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [hsdo_subjectOf](../slots/hsdo_subjectOf.md) | any_of[range] | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_receivingCatchment](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_receivingCatchment.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [owl_equivalentClass](../slots/owl_equivalentClass.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_catchmentRealization](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_catchmentRealization.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_encompassingCatchment](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_encompassingCatchment.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_lowerCatchment](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_lowerCatchment.md) | range | [RdfsResource](../classes/RdfsResource.md) |
| [RdfsResource](../classes/RdfsResource.md) | [https___www.opengis.net_def_hy_features_ontology_hyf_hydrometricNetwork](../slots/https___www.opengis.net_def_hy_features_ontology_hyf_hydrometricNetwork.md) | range | [RdfsResource](../classes/RdfsResource.md) |







## Examples

| Value |
| --- |
| http://geosciences.ca/def/groundwater#GW_AquiferSystem |


## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rdfs:Resource |
| native | geoconnex/:RdfsResource |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: rdfs_Resource
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class name specified
notes:
- Class with 1527 occurrences.
examples:
- value: http://geosciences.ca/def/groundwater#GW_AquiferSystem
from_schema: geoconnex
rank: 1000
slots:
- https___www.opengis.net_def_hy_features_ontology_hyf_inflow
- owl_sameAs
- http___geosciences.ca_def_hydraulic#contains
- https___www.opengis.net_def_hy_features_ontology_hyf_realizedCatchment
- http___www.opengeospatial.org_standards_geosparql_sfContains
- dc_description
- https___www.opengis.net_def_hy_features_ontology_hyf_networkStation
- rdfs_label
- rdf_type
- https___www.opengis.net_def_hy_features_ontology_hyf_realizedNexus
- http___rdfs.org_ns_void#target
- https___www.opengis.net_def_hy_features_ontology_hyf_exorheicDrainage
- dct_format
- rdfs_subClassOf
- http___www.opengeospatial.org_standards_geosparql_sfIntersects
- https___www.opengis.net_def_hy_features_ontology_hyf_upperCatchment
- https___www.opengis.net_def_hy_features_ontology_hyf_nexusRealization
- https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment
- https___www.opengis.net_def_hy_features_ontology_hyf_outflow
- hsdo_subjectOf
- https___www.opengis.net_def_hy_features_ontology_hyf_receivingCatchment
- http___rdfs.org_ns_void#property
- dct_conformsTo
- schema_provider
- owl_equivalentClass
- hsdo_name
- https___www.opengis.net_def_hy_features_ontology_hyf_catchmentRealization
- hsdo_provider
- https___www.opengis.net_def_hy_features_ontology_hyf_encompassingCatchment
- https___www.opengis.net_def_hy_features_ontology_hyf_lowerCatchment
- https___www.opengis.net_def_hy_features_ontology_hyf_hydrometricNetwork
class_uri: rdfs:Resource

```
</details>

### Induced

<details>
```yaml
name: rdfs_Resource
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class name specified
notes:
- Class with 1527 occurrences.
examples:
- value: http://geosciences.ca/def/groundwater#GW_AquiferSystem
from_schema: geoconnex
rank: 1000
attributes:
  https___www.opengis.net_def_hy_features_ontology_hyf_inflow:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_inflow
    description: No slot (predicate) description specified
    comments:
    - 99 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu_nexus/041504081604-inflow
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/inflow
        example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081604
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/inflow
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_inflow
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  owl_sameAs:
    name: owl_sameAs
    description: No slot (predicate) description specified
    comments:
    - 1498 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    - 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.
    - 2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
      and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.
    - 5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well
      and object type http___geosciences.ca_def_groundwater#GW_Well.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/nat_aq/N100GLCIAL
        example_predicate: owl:sameAs
        example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N100GLCIAL
    - description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      object:
        example_object: https://geoconnex.ca/id/hydrogeounits/Richelieu1
        example_predicate: owl:sameAs
        example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    - description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → http___geosciences.ca_def_groundwater#GW_AquiferSystem
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB
        example_predicate: owl:sameAs
        example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB
    - description: http___geosciences.ca_def_groundwater#GW_Well → http___geosciences.ca_def_groundwater#GW_Well
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201
        example_predicate: owl:sameAs
        example_subject: https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201
    from_schema: geoconnex
    rank: 1000
    slot_uri: owl:sameAs
    alias: owl_sameAs
    owner: rdfs_Resource
    domain_of:
    - http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    - http___geosciences.ca_def_groundwater#GW_Well
    - rdfs_Resource
    range: Any
    any_of:
    - range: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    - range: http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - range: rdfs_Resource
    - range: http___geosciences.ca_def_groundwater#GW_Well
  http___geosciences.ca_def_hydraulic#contains:
    name: http___geosciences.ca_def_hydraulic#contains
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type rdfs_Resource and object type uri.
    examples:
    - description: rdfs_Resource → uri
      object:
        example_object: https://geoconnex.ca/id/featureCollection/wellsIn02OJ_CA
        example_predicate: http://geosciences.ca/def/hydraulic#contains
        example_subject: https://geoconnex.ca/id/catchment/02OJ*CA
    from_schema: geoconnex
    rank: 1000
    slot_uri: http://geosciences.ca/def/hydraulic#contains
    alias: http___geosciences.ca_def_hydraulic#contains
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: uri
  https___www.opengis.net_def_hy_features_ontology_hyf_realizedCatchment:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_realizedCatchment
    description: No slot (predicate) description specified
    comments:
    - 789 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081604-drainage_basin
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/realizedCatchment
        example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081604-drainage_basin_hydronetwork
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/realizedCatchment
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_realizedCatchment
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  http___www.opengeospatial.org_standards_geosparql_sfContains:
    name: http___www.opengeospatial.org_standards_geosparql_sfContains
    description: No slot (predicate) description specified
    comments:
    - 14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_Well.
    - 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
      and object type http___geosciences.ca_def_groundwater#GW_Well.
    examples:
    - description: rdfs_Resource → http___geosciences.ca_def_groundwater#GW_Well
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/well/USGS-443646073124901
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfContains
        example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N100GLCIAL
    - description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → http___geosciences.ca_def_groundwater#GW_Well
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfContains
        example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN
    from_schema: geoconnex
    rank: 1000
    slot_uri: http://www.opengeospatial.org/standards/geosparql/sfContains
    alias: http___www.opengeospatial.org_standards_geosparql_sfContains
    owner: rdfs_Resource
    domain_of:
    - http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - rdfs_Resource
    range: http___geosciences.ca_def_groundwater#GW_Well
  dc_description:
    name: dc_description
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      string.
    - 2 occurrences with subject type rdfs_Resource and object type string.
    examples:
    - description: http___rdfs.org_ns_void#Dataset → string
      object:
        example_object: 'Representation of the data node: catalog of features i.e.
          /id/s. Contains triples like: CAN_Watershed gsip:inNodeCatalog /id/CAN_LOD_Node'
        example_predicate: dc:description
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
    - description: rdfs_Resource → string
      object:
        example_object: 'Representation containing links between data nodes. Only
          contains triples like: /id/CAN_LOD_Node connectedTo /id/US_LOD_Node'
        example_predicate: dc:description
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    from_schema: geoconnex
    rank: 1000
    slot_uri: dc:description
    alias: dc_description
    owner: rdfs_Resource
    domain_of:
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    range: string
  https___www.opengis.net_def_hy_features_ontology_hyf_networkStation:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_networkStation
    description: No slot (predicate) description specified
    comments:
    - 74 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/gage/04271815
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/networkStation
        example_subject: https://geoconnex.us/chyld-pilot/id/gage_hu_network/041504081603
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/networkStation
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_networkStation
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  rdfs_label:
    name: rdfs_label
    description: No slot (predicate) description specified
    comments:
    - 1514 occurrences with subject type rdfs_Resource and object type string.
    - 3204 occurrences with untyped subjects and object type string.
    - 2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type string.
    - 5 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      string.
    - 2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
      and object type string.
    - 5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well
      and object type string.
    examples:
    - description: rdfs_Resource → string
      object:
        example_object: Aquifer System
        example_predicate: rdfs:label
        example_subject: http://geosciences.ca/def/groundwater#GW_AquiferSystem
    - description: None → string
      object:
        example_object: Aquifer Summary Page
        example_predicate: rdfs:label
        example_subject: http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html
    - description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → string
      object:
        example_object: 'Hydrogeologic unit : Southern St Lawrence Platform'
        example_predicate: rdfs:label
        example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    - description: http___rdfs.org_ns_void#Dataset → string
      object:
        example_object: Hydrography Linked Data Node - United States of America
        example_predicate: rdfs:label
        example_subject: https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node
    - description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → string
      object:
        example_object: New York sandstone aquifers
        example_predicate: rdfs:label
        example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN
    - description: http___geosciences.ca_def_groundwater#GW_Well → string
      object:
        example_object: VT-PFW    8
        example_predicate: rdfs:label
        example_subject: https://geoconnex.us/chyld-pilot/id/well/USGS-434217073010601
    from_schema: geoconnex
    rank: 1000
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: rdfs_Resource
    domain_of:
    - http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    - http___geosciences.ca_def_groundwater#GW_Well
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    range: string
  rdf_type:
    name: rdf_type
    description: No slot (predicate) description specified
    comments:
    - 34 occurrences with subject type rdfs_Resource and object type uri.
    examples:
    - description: rdfs_Resource → uri
      object:
        example_object: rdfs:Class
        example_predicate: rdf:type
        example_subject: http://geosciences.ca/def/groundwater#GW_AquiferSystem
    from_schema: geoconnex
    rank: 1000
    slot_uri: rdf:type
    alias: rdf_type
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: uri
  https___www.opengis.net_def_hy_features_ontology_hyf_realizedNexus:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_realizedNexus
    description: No slot (predicate) description specified
    comments:
    - 187 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu_nexus/041504090000-inflow
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/realizedNexus
        example_subject: https://geoconnex.us/chyld-pilot/id/hu_outlet/041504081604
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/realizedNexus
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_realizedNexus
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  http___rdfs.org_ns_void#target:
    name: http___rdfs.org_ns_void#target
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type rdfs_Resource and object type http___rdfs.org_ns_void#Dataset.
    - 1 occurrences with subject type rdfs_Resource and object type uri.
    examples:
    - description: rdfs_Resource → http___rdfs.org_ns_void#Dataset
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node
        example_predicate: http://rdfs.org/ns/void#target
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    - description: rdfs_Resource → uri
      object:
        example_object: https://geoconnex.ca/id/CAN_LOD_Node
        example_predicate: http://rdfs.org/ns/void#target
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    from_schema: geoconnex
    rank: 1000
    slot_uri: http://rdfs.org/ns/void#target
    alias: http___rdfs.org_ns_void#target
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: Any
    any_of:
    - range: uri
    - range: http___rdfs.org_ns_void#Dataset
  https___www.opengis.net_def_hy_features_ontology_hyf_exorheicDrainage:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_exorheicDrainage
    description: No slot (predicate) description specified
    comments:
    - 187 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081604
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/exorheicDrainage
        example_subject: https://geoconnex.us/chyld-pilot/id/hu/04150408
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/exorheicDrainage
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_exorheicDrainage
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  dct_format:
    name: dct_format
    description: No slot (predicate) description specified
    comments:
    - 7697 occurrences with untyped subjects and object type string.
    - 3 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      string.
    - 6 occurrences with subject type rdfs_Resource and object type string.
    examples:
    - description: None → string
      object:
        example_object: text/html
        example_predicate: dct:format
        example_subject: http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html
    - description: http___rdfs.org_ns_void#Dataset → string
      object:
        example_object: application/ld+json
        example_predicate: dct:format
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
    - description: rdfs_Resource → string
      object:
        example_object: application/ld+json
        example_predicate: dct:format
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    from_schema: geoconnex
    rank: 1000
    slot_uri: dct:format
    alias: dct_format
    owner: rdfs_Resource
    domain_of:
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    range: string
  rdfs_subClassOf:
    name: rdfs_subClassOf
    description: No slot (predicate) description specified
    comments:
    - 43 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://www.opengis.net/def/hy_features/ontology/hyf/HY_HydrometricNetwork
        example_predicate: rdfs:subClassOf
        example_subject: https://www.opengis.net/def/hy_features/ontology/hyf/HY_HydrometricNetwork
    from_schema: geoconnex
    rank: 1000
    slot_uri: rdfs:subClassOf
    alias: rdfs_subClassOf
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  http___www.opengeospatial.org_standards_geosparql_sfIntersects:
    name: http___www.opengeospatial.org_standards_geosparql_sfIntersects
    description: No slot (predicate) description specified
    comments:
    - 14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type rdfs_Resource.
    - 13 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type uri.
    - 108 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.
    - 14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.
    - 108 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
      and object type rdfs_Resource.
    examples:
    - description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081507-drainage_basin
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
        example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    - description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → uri
      object:
        example_object: https://cida-test.er.usgs.gov/chyld-pilot/id/hu/041504081005
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
        example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    - description: rdfs_Resource → http___geosciences.ca_def_groundwater#GW_AquiferSystem
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
        example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081604
    - description: rdfs_Resource → http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      object:
        example_object: https://geoconnex.ca/id/hydrogeounits/Richelieu1
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
        example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081507-drainage_basin
    - description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081604
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
        example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB
    from_schema: geoconnex
    rank: 1000
    slot_uri: http://www.opengeospatial.org/standards/geosparql/sfIntersects
    alias: http___www.opengeospatial.org_standards_geosparql_sfIntersects
    owner: rdfs_Resource
    domain_of:
    - http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    - rdfs_Resource
    range: Any
    any_of:
    - range: uri
    - range: http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - range: rdfs_Resource
    - range: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
  https___www.opengis.net_def_hy_features_ontology_hyf_upperCatchment:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_upperCatchment
    description: No slot (predicate) description specified
    comments:
    - 374 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    - 2 occurrences with subject type rdfs_Resource and object type uri.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081603-drainage_basin
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/upperCatchment
        example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081604
    - description: rdfs_Resource → uri
      object:
        example_object: https://cida-test.er.usgs.gov/chyld-pilot/id/hu/041504081604
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/upperCatchment
        example_subject: https://geoconnex.ca/id/catchment/02OJ*CA
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/upperCatchment
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_upperCatchment
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: Any
    any_of:
    - range: uri
    - range: rdfs_Resource
  https___www.opengis.net_def_hy_features_ontology_hyf_nexusRealization:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_nexusRealization
    description: No slot (predicate) description specified
    comments:
    - 187 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu_outlet/041504081604
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/nexusRealization
        example_subject: https://geoconnex.us/chyld-pilot/id/hu_nexus/041504090000-inflow
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/nexusRealization
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_nexusRealization
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type rdfs_Resource and object type uri.
    - 374 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → uri
      object:
        example_object: https://cida-test.er.usgs.gov/chyld-pilot/id/hu_nexus/02OJ*CA-inflow
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/contributingCatchment
        example_subject: https://geoconnex.ca/id/catchment/02OJ*CA
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081603-drainage_basin
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/contributingCatchment
        example_subject: https://geoconnex.us/chyld-pilot/id/hu_nexus/041504081604-inflow
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/contributingCatchment
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: Any
    any_of:
    - range: uri
    - range: rdfs_Resource
  https___www.opengis.net_def_hy_features_ontology_hyf_outflow:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_outflow
    description: No slot (predicate) description specified
    comments:
    - 374 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu_nexus/02OJ*CA-inflow
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/outflow
        example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081604-drainage_basin
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/outflow
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_outflow
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  hsdo_subjectOf:
    name: hsdo_subjectOf
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      http___rdfs.org_ns_void#Dataset.
    - 2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      rdfs_Resource.
    - 3227 occurrences with subject type rdfs_Resource and object type uri.
    - 6 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
      and object type uri.
    - 15 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well
      and object type uri.
    examples:
    - description: http___rdfs.org_ns_void#Dataset → http___rdfs.org_ns_void#Dataset
      object:
        example_object: https://info.geoconnex.us/chyld-pilot/data/node/all
        example_predicate: hsdo:subjectOf
        example_subject: https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node
    - description: http___rdfs.org_ns_void#Dataset → rdfs_Resource
      object:
        example_object: https://info.geoconnex.us/chyld-pilot/data/node/cross
        example_predicate: hsdo:subjectOf
        example_subject: https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node
    - description: rdfs_Resource → uri
      object:
        example_object: https://cida.usgs.gov/nldi/nwissite/USGS-04271500
        example_predicate: hsdo:subjectOf
        example_subject: https://geoconnex.us/chyld-pilot/id/gage/04271500
    - description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → uri
      object:
        example_object: http://water.usgs.gov/ogw/aquiferbasics/sandston.html
        example_predicate: hsdo:subjectOf
        example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN
    - description: http___geosciences.ca_def_groundwater#GW_Well → uri
      object:
        example_object: http://waterdata.usgs.gov/nwis/inventory?search_site_no=434217073010601&search_site_no_match_type=exact&sort_key=site_no&group_key=NONE&sitefile_output_format=html_table&column_name=agency_cd&column_name=site_no&column_name=station_nm&format=station_manuscript&list_of_search_criteria=search_site_no
        example_predicate: hsdo:subjectOf
        example_subject: https://geoconnex.us/chyld-pilot/id/well/USGS-434217073010601
    from_schema: geoconnex
    rank: 1000
    slot_uri: hsdo:subjectOf
    alias: hsdo_subjectOf
    owner: rdfs_Resource
    domain_of:
    - http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - http___geosciences.ca_def_groundwater#GW_Well
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    range: Any
    any_of:
    - range: uri
    - range: rdfs_Resource
    - range: http___rdfs.org_ns_void#Dataset
  https___www.opengis.net_def_hy_features_ontology_hyf_receivingCatchment:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_receivingCatchment
    description: No slot (predicate) description specified
    comments:
    - 99 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081604
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/receivingCatchment
        example_subject: https://geoconnex.us/chyld-pilot/id/hu_nexus/041504081604-inflow
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/receivingCatchment
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_receivingCatchment
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  http___rdfs.org_ns_void#property:
    name: http___rdfs.org_ns_void#property
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type rdfs_Resource and object type uri.
    examples:
    - description: rdfs_Resource → uri
      object:
        example_object: https://geoconnex.ca/id/properties/connectedTo
        example_predicate: http://rdfs.org/ns/void#property
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    from_schema: geoconnex
    rank: 1000
    slot_uri: http://rdfs.org/ns/void#property
    alias: http___rdfs.org_ns_void#property
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: uri
  dct_conformsTo:
    name: dct_conformsTo
    description: No slot (predicate) description specified
    comments:
    - 56432 occurrences with subject type schema_DataDownload and object type string.
    - 3194 occurrences with untyped subjects and object type uri.
    - 2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      uri.
    - 4 occurrences with subject type rdfs_Resource and object type uri.
    examples:
    - description: schema_DataDownload → string
      object:
        example_object: https://labs.waterdata.usgs.gov/docs/sensorthings/index.html
        example_predicate: dct:conformsTo
        example_subject: _:b1000004
    - description: None → uri
      object:
        example_object: https://github.com/NRCan/GSIP
        example_predicate: dct:conformsTo
        example_subject: http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html
    - description: http___rdfs.org_ns_void#Dataset → uri
      object:
        example_object: https://github.com/NRCan/GSIP
        example_predicate: dct:conformsTo
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
    - description: rdfs_Resource → uri
      object:
        example_object: https://github.com/NRCan/GSIP
        example_predicate: dct:conformsTo
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    from_schema: geoconnex
    rank: 1000
    slot_uri: dct:conformsTo
    alias: dct_conformsTo
    owner: rdfs_Resource
    domain_of:
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    - schema_DataDownload
    range: Any
    any_of:
    - range: uri
    - range: string
  schema_provider:
    name: schema_provider
    description: No slot (predicate) description specified
    comments:
    - 28216 occurrences with subject type schema_Dataset and object type schema_GovernmentOrganization.
    - 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      uri.
    - 2 occurrences with subject type rdfs_Resource and object type uri.
    - 98534 occurrences with subject type schema_Place and object type schema_url.
    - 185872 occurrences with subject type hyf__HY_HydroLocation and object type uri.
    - 13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_GovernmentOrganization.
    examples:
    - description: schema_Dataset → schema_GovernmentOrganization
      object:
        example_object: https://gleaner.io/xid/genid/cri6355vd7os738ck6h0
        example_predicate: schema:provider
        example_subject: https://gleaner.io/xid/genid/cri6355vd7os738ck6jg
    - description: http___rdfs.org_ns_void#Dataset → uri
      object:
        example_object: https://labs.waterdata.usgs.gov
        example_predicate: schema:provider
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
    - description: rdfs_Resource → uri
      object:
        example_object: https://labs.waterdata.usgs.gov
        example_predicate: schema:provider
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    - description: schema_Place → schema_url
      object:
        example_object: https://nid.usace.army.mil
        example_predicate: schema:provider
        example_subject: https://geoconnex.us/ref/dams/1000001
    - description: hyf__HY_HydroLocation → uri
      object:
        example_object: https://waterdata.usgs.gov
        example_predicate: schema:provider
        example_subject: https://geoconnex.us/ref/gages/1000001
    - description: hyf__HY_HydroLocation → schema_GovernmentOrganization
      object:
        example_object: _:b850488
        example_predicate: schema:provider
        example_subject: https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900'
    from_schema: geoconnex
    rank: 1000
    slot_uri: schema:provider
    alias: schema_provider
    owner: rdfs_Resource
    domain_of:
    - http___rdfs.org_ns_void#Dataset
    - hyf__HY_HydroLocation
    - rdfs_Resource
    - schema_Dataset
    - schema_Place
    range: Any
    any_of:
    - range: uri
    - range: schema_GovernmentOrganization
    - range: schema_url
  owl_equivalentClass:
    name: owl_equivalentClass
    description: No slot (predicate) description specified
    comments:
    - 17 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://www.opengis.net/def/hy_features/ontology/hyf/HY_HydrometricNetwork
        example_predicate: owl:equivalentClass
        example_subject: https://www.opengis.net/def/hy_features/ontology/hyf/HY_HydrometricNetwork
    from_schema: geoconnex
    rank: 1000
    slot_uri: owl:equivalentClass
    alias: owl_equivalentClass
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  hsdo_name:
    name: hsdo_name
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type rdfs_Resource and object type string.
    - 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type string.
    - 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
      and object type string.
    - 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork
      and object type string.
    - 2 occurrences with subject type hsdo_Person and object type string.
    - 3 occurrences with subject type hsdo_Organization and object type string.
    - 48677 occurrences with subject type hsdo_WebPage and object type string.
    - 3 occurrences with subject type hsdo_ListItem and object type string.
    - 1 occurrences with subject type hsdo_WebSite and object type string.
    examples:
    - description: rdfs_Resource → string
      object:
        example_object: 'Watershed : Little River - Riviere Richelieu'
        example_predicate: hsdo:name
        example_subject: https://geoconnex.ca/id/catchment/02OJ*CA
    - description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → string
      object:
        example_object: 'Hydrogeologic unit : Southern St Lawrence Platform'
        example_predicate: hsdo:name
        example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    - description: https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
        → string
      object:
        example_object: Waunakee Marsh-Sixmile Creek
        example_predicate: hsdo:name
        example_subject: https://geoconnex.us/SELFIE/usgs/huc/huc12obs/070900020601
    - description: https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork
        → string
      object:
        example_object: Waunakee Marsh-Sixmile Creek Monitoring Network
        example_predicate: hsdo:name
        example_subject: https://geoconnex.us/SELFIE/usgs/hydrometricnetwork/huc12obs/070900020601
    - description: hsdo_Person → string
      object:
        example_object: Kyle Onda
        example_predicate: hsdo:name
        example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pl0
    - description: hsdo_Organization → string
      object:
        example_object: Esri
        example_predicate: hsdo:name
        example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27plg
    - description: hsdo_WebPage → string
      object:
        example_object: Home
        example_predicate: hsdo:name
        example_subject: https://internetofwater.org/
    - description: hsdo_ListItem → string
      object:
        example_object: Home
        example_predicate: hsdo:name
        example_subject: https://internetofwater.org/#listItem
    - description: hsdo_WebSite → string
      object:
        example_object: Internet of Water
        example_predicate: hsdo:name
        example_subject: https://internetofwater.org/#website
    from_schema: geoconnex
    rank: 1000
    slot_uri: hsdo:name
    alias: hsdo_name
    owner: rdfs_Resource
    domain_of:
    - hsdo_ListItem
    - hsdo_Organization
    - hsdo_Person
    - hsdo_WebPage
    - hsdo_WebSite
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    - https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
    - https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork
    - rdfs_Resource
    range: string
  https___www.opengis.net_def_hy_features_ontology_hyf_catchmentRealization:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_catchmentRealization
    description: No slot (predicate) description specified
    comments:
    - 789 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081604-drainage_basin_hydronetwork
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/catchmentRealization
        example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081604-drainage_basin
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/catchmentRealization
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_catchmentRealization
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  hsdo_provider:
    name: hsdo_provider
    description: No slot (predicate) description specified
    comments:
    - 3194 occurrences with untyped subjects and object type uri.
    - 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      uri.
    - 2 occurrences with subject type rdfs_Resource and object type uri.
    - 48672 occurrences with subject type hsdo_WebPage and object type string.
    examples:
    - description: None → uri
      object:
        example_object: https://labs.waterdata.usgs.gov
        example_predicate: hsdo:provider
        example_subject: http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html
    - description: http___rdfs.org_ns_void#Dataset → uri
      object:
        example_object: https://labs.waterdata.usgs.gov
        example_predicate: hsdo:provider
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
    - description: rdfs_Resource → uri
      object:
        example_object: https://labs.waterdata.usgs.gov
        example_predicate: hsdo:provider
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    - description: hsdo_WebPage → string
      object:
        example_object: https://epa.gov
        example_predicate: hsdo:provider
        example_subject: https://geoconnex.us/epa/hmw/010100020101
    from_schema: geoconnex
    rank: 1000
    slot_uri: hsdo:provider
    alias: hsdo_provider
    owner: rdfs_Resource
    domain_of:
    - hsdo_WebPage
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    range: Any
    any_of:
    - range: uri
    - range: string
  https___www.opengis.net_def_hy_features_ontology_hyf_encompassingCatchment:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_encompassingCatchment
    description: No slot (predicate) description specified
    comments:
    - 187 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu/04150408
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/encompassingCatchment
        example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081604
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/encompassingCatchment
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_encompassingCatchment
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  https___www.opengis.net_def_hy_features_ontology_hyf_lowerCatchment:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_lowerCatchment
    description: No slot (predicate) description specified
    comments:
    - 374 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.ca/id/catchment/02OJ*CA
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/lowerCatchment
        example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081604-drainage_basin
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/lowerCatchment
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_lowerCatchment
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
  https___www.opengis.net_def_hy_features_ontology_hyf_hydrometricNetwork:
    name: https___www.opengis.net_def_hy_features_ontology_hyf_hydrometricNetwork
    description: No slot (predicate) description specified
    comments:
    - 74 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    examples:
    - description: rdfs_Resource → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/gage_hu_network/041504081201
        example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/hydrometricNetwork
        example_subject: https://geoconnex.us/chyld-pilot/id/gage/04292810
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/hydrometricNetwork
    alias: https___www.opengis.net_def_hy_features_ontology_hyf_hydrometricNetwork
    owner: rdfs_Resource
    domain_of:
    - rdfs_Resource
    range: rdfs_Resource
class_uri: rdfs:Resource

```
</details>