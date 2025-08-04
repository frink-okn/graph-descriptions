

# Class: HttpTemplekg.orgOntologyWeatherEvent




This class occurs 89 times.


URI: [http://templekg.org/ontology/WeatherEvent](http://templekg.org/ontology/WeatherEvent)






```mermaid
 classDiagram
    class HttpTemplekg.orgOntologyWeatherEvent
    click HttpTemplekg.orgOntologyWeatherEvent href "../HttpTemplekg.orgOntologyWeatherEvent"
      HttpTemplekg.orgOntologyWeatherEvent : dct_description
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" String : dct_description
    click String href "../String"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_ChildOf
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" Any : http___templekg.org_ontology_ChildOf
    click Any href "../Any"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_collapsed_uuids
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" String : http___templekg.org_ontology_collapsed_uuids
    click String href "../String"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_ComparedTo
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" Any : http___templekg.org_ontology_ComparedTo
    click Any href "../Any"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_Outputs
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" Any : http___templekg.org_ontology_Outputs
    click Any href "../Any"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_RunBy
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" Any : http___templekg.org_ontology_RunBy
    click Any href "../Any"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_TargetsLocation
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" Any : http___templekg.org_ontology_TargetsLocation
    click Any href "../Any"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_UsedIn
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" Any : http___templekg.org_ontology_UsedIn
    click Any href "../Any"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_UUID
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" String : http___templekg.org_ontology_UUID
    click String href "../String"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_ValidatedBy
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" Any : http___templekg.org_ontology_ValidatedBy
    click Any href "../Any"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_wikidata_description
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" String : http___templekg.org_ontology_wikidata_description
    click String href "../String"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_wikidata_ids
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" String : http___templekg.org_ontology_wikidata_ids
    click String href "../String"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_WikiHasEffect
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" Any : http___templekg.org_ontology_WikiHasEffect
    click Any href "../Any"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_WikiHasParts
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" Any : http___templekg.org_ontology_WikiHasParts
    click Any href "../Any"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_WikiInstanceOf
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" Any : http___templekg.org_ontology_WikiInstanceOf
    click Any href "../Any"

        
      HttpTemplekg.orgOntologyWeatherEvent : http___templekg.org_ontology_WikiSubclassOf
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" Any : http___templekg.org_ontology_WikiSubclassOf
    click Any href "../Any"

        
      HttpTemplekg.orgOntologyWeatherEvent : prov_atLocation
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" ProvLocation : prov_atLocation
    click ProvLocation href "../ProvLocation"

        
      HttpTemplekg.orgOntologyWeatherEvent : rdfs_label
        
          
    
    
    HttpTemplekg.orgOntologyWeatherEvent --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___templekg.org_ontology_wikidata_description](../slots/http___templekg.org_ontology_wikidata_description.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 19 |
| [http___templekg.org_ontology_WikiInstanceOf](../slots/http___templekg.org_ontology_WikiInstanceOf.md) | 0..1 <br/> [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md) |  <br/>  | direct | 1 |
| [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | 0..1 <br/> [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md) |  <br/>  | direct | 21 |
| [http___templekg.org_ontology_wikidata_ids](../slots/http___templekg.org_ontology_wikidata_ids.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 19 |
| [dct_description](../slots/dct_description.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | Description may include but is not limited to: an abstract, a table of conten... <br/> description: An account of the resource. | direct | 78 |
| [http___templekg.org_ontology_collapsed_uuids](../slots/http___templekg.org_ontology_collapsed_uuids.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 6 |
| [http___templekg.org_ontology_WikiSubclassOf](../slots/http___templekg.org_ontology_WikiSubclassOf.md) | 0..1 <br/> [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md) |  <br/>  | direct | 9 |
| [http___templekg.org_ontology_UUID](../slots/http___templekg.org_ontology_UUID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 89 |
| [http___templekg.org_ontology_ValidatedBy](../slots/http___templekg.org_ontology_ValidatedBy.md) | 0..1 <br/> [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md) |  <br/>  | direct | 1 |
| [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | 0..1 <br/> [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) |  <br/>  | direct | 4 |
| [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | 0..1 <br/> [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md) |  <br/>  | direct | 115 |
| [http___templekg.org_ontology_RunBy](../slots/http___templekg.org_ontology_RunBy.md) | 0..1 <br/> [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md) |  <br/>  | direct | 3 |
| [prov_atLocation](../slots/prov_atLocation.md) | 0..1 <br/> [ProvLocation](../classes/ProvLocation.md) | The Location of any resource <br/> description: This property has multiple RDFS domains to suit multiple OWL Profiles. See <a href="#owl-profile">PROV-O OWL Profile</a>.<br/>No occurrences of this slot in the graph. | direct | 16 |
| [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | 0..1 <br/> [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md) |  <br/>  | direct | 490 |
| [http___templekg.org_ontology_Outputs](../slots/http___templekg.org_ontology_Outputs.md) | 0..1 <br/> [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md) |  <br/>  | direct | 4 |
| [http___templekg.org_ontology_WikiHasParts](../slots/http___templekg.org_ontology_WikiHasParts.md) | 0..1 <br/> [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) |  <br/>  | direct | 5 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 89 |
| [http___templekg.org_ontology_WikiHasEffect](../slots/http___templekg.org_ontology_WikiHasEffect.md) | 0..1 <br/> [HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) |  <br/>  | direct | 3 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md) | [http___templekg.org_ontology_ProvidedBy](../slots/http___templekg.org_ontology_ProvidedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md) | [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md) | [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md) | [http___templekg.org_ontology_Outputs](../slots/http___templekg.org_ontology_Outputs.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md) | [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md) | [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md) | [http___templekg.org_ontology_ValidatedBy](../slots/http___templekg.org_ontology_ValidatedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) | [http___templekg.org_ontology_ProvidedBy](../slots/http___templekg.org_ontology_ProvidedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) | [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) | [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) | [http___templekg.org_ontology_Outputs](../slots/http___templekg.org_ontology_Outputs.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) | [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) | [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) | [http___templekg.org_ontology_WikiSubclassOf](../slots/http___templekg.org_ontology_WikiSubclassOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) | [http___templekg.org_ontology_WikiDifferentFrom](../slots/http___templekg.org_ontology_WikiDifferentFrom.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) | [http___templekg.org_ontology_WikiHasCause](../slots/http___templekg.org_ontology_WikiHasCause.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) | [http___templekg.org_ontology_ValidatedBy](../slots/http___templekg.org_ontology_ValidatedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) | [http___templekg.org_ontology_WikiHasParts](../slots/http___templekg.org_ontology_WikiHasParts.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) | [http___templekg.org_ontology_ProvidedBy](../slots/http___templekg.org_ontology_ProvidedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) | [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) | [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) | [http___templekg.org_ontology_Outputs](../slots/http___templekg.org_ontology_Outputs.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) | [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) | [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) | [http___templekg.org_ontology_WikiSubclassOf](../slots/http___templekg.org_ontology_WikiSubclassOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) | [http___templekg.org_ontology_WikiDifferentFrom](../slots/http___templekg.org_ontology_WikiDifferentFrom.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) | [http___templekg.org_ontology_ValidatedBy](../slots/http___templekg.org_ontology_ValidatedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) | [http___templekg.org_ontology_WikiHasParts](../slots/http___templekg.org_ontology_WikiHasParts.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) | [http___templekg.org_ontology_ProvidedBy](../slots/http___templekg.org_ontology_ProvidedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) | [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) | [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) | [http___templekg.org_ontology_Outputs](../slots/http___templekg.org_ontology_Outputs.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) | [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) | [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) | [http___templekg.org_ontology_WikiSubclassOf](../slots/http___templekg.org_ontology_WikiSubclassOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) | [http___templekg.org_ontology_ValidatedBy](../slots/http___templekg.org_ontology_ValidatedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) | [http___templekg.org_ontology_WikiHasParts](../slots/http___templekg.org_ontology_WikiHasParts.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md) | [http___templekg.org_ontology_WikiDifferentFrom](../slots/http___templekg.org_ontology_WikiDifferentFrom.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md) | [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md) | [http___templekg.org_ontology_WikiHasCause](../slots/http___templekg.org_ontology_WikiHasCause.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md) | [http___templekg.org_ontology_WikiSubclassOf](../slots/http___templekg.org_ontology_WikiSubclassOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md) | [http___templekg.org_ontology_ValidatedBy](../slots/http___templekg.org_ontology_ValidatedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md) | [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md) | [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md) | [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md) | [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md) | [http___templekg.org_ontology_WikiSubclassOf](../slots/http___templekg.org_ontology_WikiSubclassOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md) | [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md) | [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md) | [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md) | [http___templekg.org_ontology_Outputs](../slots/http___templekg.org_ontology_Outputs.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) | [http___templekg.org_ontology_ProvidedBy](../slots/http___templekg.org_ontology_ProvidedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) | [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) | [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) | [http___templekg.org_ontology_Outputs](../slots/http___templekg.org_ontology_Outputs.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) | [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) | [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) | [http___templekg.org_ontology_WikiSubclassOf](../slots/http___templekg.org_ontology_WikiSubclassOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) | [http___templekg.org_ontology_WikiDifferentFrom](../slots/http___templekg.org_ontology_WikiDifferentFrom.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) | [http___templekg.org_ontology_WikiHasCause](../slots/http___templekg.org_ontology_WikiHasCause.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) | [http___templekg.org_ontology_ValidatedBy](../slots/http___templekg.org_ontology_ValidatedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) | [http___templekg.org_ontology_WikiHasParts](../slots/http___templekg.org_ontology_WikiHasParts.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyPaper](../classes/HttpTemplekg.orgOntologyPaper.md) | [http___templekg.org_ontology_Mention](../slots/http___templekg.org_ontology_Mention.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) | [http___templekg.org_ontology_ProvidedBy](../slots/http___templekg.org_ontology_ProvidedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) | [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) | [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) | [http___templekg.org_ontology_Outputs](../slots/http___templekg.org_ontology_Outputs.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) | [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) | [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) | [http___templekg.org_ontology_WikiSubclassOf](../slots/http___templekg.org_ontology_WikiSubclassOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) | [http___templekg.org_ontology_WikiDifferentFrom](../slots/http___templekg.org_ontology_WikiDifferentFrom.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) | [http___templekg.org_ontology_ValidatedBy](../slots/http___templekg.org_ontology_ValidatedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) | [http___templekg.org_ontology_WikiHasParts](../slots/http___templekg.org_ontology_WikiHasParts.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) | [http___templekg.org_ontology_ProvidedBy](../slots/http___templekg.org_ontology_ProvidedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) | [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) | [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) | [http___templekg.org_ontology_Outputs](../slots/http___templekg.org_ontology_Outputs.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) | [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) | [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) | [http___templekg.org_ontology_WikiSubclassOf](../slots/http___templekg.org_ontology_WikiSubclassOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) | [http___templekg.org_ontology_WikiDifferentFrom](../slots/http___templekg.org_ontology_WikiDifferentFrom.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) | [http___templekg.org_ontology_ValidatedBy](../slots/http___templekg.org_ontology_ValidatedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) | [http___templekg.org_ontology_WikiHasParts](../slots/http___templekg.org_ontology_WikiHasParts.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md) | [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md) | [http___templekg.org_ontology_WikiSubclassOf](../slots/http___templekg.org_ontology_WikiSubclassOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md) | [http___templekg.org_ontology_ValidatedBy](../slots/http___templekg.org_ontology_ValidatedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md) | [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md) | [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md) | [http___templekg.org_ontology_WikiHasParts](../slots/http___templekg.org_ontology_WikiHasParts.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md) | [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md) | [http___templekg.org_ontology_Outputs](../slots/http___templekg.org_ontology_Outputs.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) | [http___templekg.org_ontology_ProvidedBy](../slots/http___templekg.org_ontology_ProvidedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) | [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) | [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) | [http___templekg.org_ontology_Outputs](../slots/http___templekg.org_ontology_Outputs.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) | [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) | [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) | [http___templekg.org_ontology_WikiSubclassOf](../slots/http___templekg.org_ontology_WikiSubclassOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) | [http___templekg.org_ontology_WikiDifferentFrom](../slots/http___templekg.org_ontology_WikiDifferentFrom.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) | [http___templekg.org_ontology_WikiHasCause](../slots/http___templekg.org_ontology_WikiHasCause.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) | [http___templekg.org_ontology_ValidatedBy](../slots/http___templekg.org_ontology_ValidatedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) | [http___templekg.org_ontology_WikiHasParts](../slots/http___templekg.org_ontology_WikiHasParts.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) | [http___templekg.org_ontology_ComparedTo](../slots/http___templekg.org_ontology_ComparedTo.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) | [http___templekg.org_ontology_WikiSubclassOf](../slots/http___templekg.org_ontology_WikiSubclassOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) | [http___templekg.org_ontology_ValidatedBy](../slots/http___templekg.org_ontology_ValidatedBy.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) | [http___templekg.org_ontology_UsedIn](../slots/http___templekg.org_ontology_UsedIn.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) | [http___templekg.org_ontology_TargetsLocation](../slots/http___templekg.org_ontology_TargetsLocation.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) | [http___templekg.org_ontology_ChildOf](../slots/http___templekg.org_ontology_ChildOf.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) | [http___templekg.org_ontology_Outputs](../slots/http___templekg.org_ontology_Outputs.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |
| [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) | [http___templekg.org_ontology_WikiHasParts](../slots/http___templekg.org_ontology_WikiHasParts.md) | any_of[range] | [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___templekg.org_ontology_WeatherEvent
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- http___templekg.org_ontology_wikidata_description
- http___templekg.org_ontology_WikiInstanceOf
- http___templekg.org_ontology_ComparedTo
- http___templekg.org_ontology_wikidata_ids
- dct_description
- http___templekg.org_ontology_collapsed_uuids
- http___templekg.org_ontology_WikiSubclassOf
- http___templekg.org_ontology_UUID
- http___templekg.org_ontology_ValidatedBy
- http___templekg.org_ontology_UsedIn
- http___templekg.org_ontology_TargetsLocation
- http___templekg.org_ontology_RunBy
- prov_atLocation
- http___templekg.org_ontology_ChildOf
- http___templekg.org_ontology_Outputs
- http___templekg.org_ontology_WikiHasParts
- rdfs_label
- http___templekg.org_ontology_WikiHasEffect
class_uri: http://templekg.org/ontology/WeatherEvent

```
</details>

### Induced

<details>

```yaml
name: http___templekg.org_ontology_WeatherEvent
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  http___templekg.org_ontology_wikidata_description:
    name: http___templekg.org_ontology_wikidata_description
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/wikidata_description
    alias: http___templekg.org_ontology_wikidata_description
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: string
  http___templekg.org_ontology_WikiInstanceOf:
    name: http___templekg.org_ontology_WikiInstanceOf
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/WikiInstanceOf
    alias: http___templekg.org_ontology_WikiInstanceOf
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: Any
    any_of:
    - range: http___templekg.org_ontology_Platform
    - range: http___templekg.org_ontology_Variable
    - range: http___templekg.org_ontology_Model
    - range: http___templekg.org_ontology_Others
    - range: http___templekg.org_ontology_Provider
    - range: http___templekg.org_ontology_Location
    - range: http___templekg.org_ontology_Instrument
    - range: sdos_Project
  http___templekg.org_ontology_ComparedTo:
    name: http___templekg.org_ontology_ComparedTo
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/ComparedTo
    alias: http___templekg.org_ontology_ComparedTo
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: Any
    any_of:
    - range: http___templekg.org_ontology_Platform
    - range: http___templekg.org_ontology_WeatherEvent
    - range: http___templekg.org_ontology_Teleconnection
    - range: http___templekg.org_ontology_Variable
    - range: http___templekg.org_ontology_Model
    - range: http___templekg.org_ontology_Others
    - range: http___templekg.org_ontology_Provider
    - range: http___templekg.org_ontology_Experiment
    - range: http___templekg.org_ontology_Location
    - range: http___templekg.org_ontology_Instrument
    - range: http___templekg.org_ontology_NaturalHazard
    - range: http___templekg.org_ontology_OceanCirculation
    - range: sdos_Project
  http___templekg.org_ontology_wikidata_ids:
    name: http___templekg.org_ontology_wikidata_ids
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/wikidata_ids
    alias: http___templekg.org_ontology_wikidata_ids
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: string
  dct_description:
    name: dct_description
    description: 'Description may include but is not limited to: an abstract, a table
      of contents, a graphical representation, or a free-text account of the resource.'
    title: Description
    comments:
    - 'description: An account of the resource.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:description
    alias: dct_description
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    subproperty_of: dc_description
    range: string
  http___templekg.org_ontology_collapsed_uuids:
    name: http___templekg.org_ontology_collapsed_uuids
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/collapsed_uuids
    alias: http___templekg.org_ontology_collapsed_uuids
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: string
  http___templekg.org_ontology_WikiSubclassOf:
    name: http___templekg.org_ontology_WikiSubclassOf
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/WikiSubclassOf
    alias: http___templekg.org_ontology_WikiSubclassOf
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: Any
    any_of:
    - range: http___templekg.org_ontology_Platform
    - range: http___templekg.org_ontology_WeatherEvent
    - range: http___templekg.org_ontology_Variable
    - range: http___templekg.org_ontology_Model
    - range: http___templekg.org_ontology_Others
    - range: http___templekg.org_ontology_Provider
    - range: http___templekg.org_ontology_Location
    - range: http___templekg.org_ontology_Instrument
    - range: http___templekg.org_ontology_NaturalHazard
    - range: http___templekg.org_ontology_OceanCirculation
    - range: sdos_Project
  http___templekg.org_ontology_UUID:
    name: http___templekg.org_ontology_UUID
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/UUID
    alias: http___templekg.org_ontology_UUID
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Paper
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: string
  http___templekg.org_ontology_ValidatedBy:
    name: http___templekg.org_ontology_ValidatedBy
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/ValidatedBy
    alias: http___templekg.org_ontology_ValidatedBy
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: Any
    any_of:
    - range: http___templekg.org_ontology_Platform
    - range: http___templekg.org_ontology_WeatherEvent
    - range: http___templekg.org_ontology_Teleconnection
    - range: http___templekg.org_ontology_Variable
    - range: http___templekg.org_ontology_Model
    - range: http___templekg.org_ontology_Others
    - range: http___templekg.org_ontology_Provider
    - range: http___templekg.org_ontology_Experiment
    - range: http___templekg.org_ontology_Instrument
    - range: http___templekg.org_ontology_NaturalHazard
    - range: http___templekg.org_ontology_OceanCirculation
    - range: sdos_Project
  http___templekg.org_ontology_UsedIn:
    name: http___templekg.org_ontology_UsedIn
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/UsedIn
    alias: http___templekg.org_ontology_UsedIn
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: Any
    any_of:
    - range: http___templekg.org_ontology_Platform
    - range: http___templekg.org_ontology_WeatherEvent
    - range: http___templekg.org_ontology_Teleconnection
    - range: http___templekg.org_ontology_Variable
    - range: http___templekg.org_ontology_Model
    - range: http___templekg.org_ontology_Others
    - range: http___templekg.org_ontology_Provider
    - range: http___templekg.org_ontology_Experiment
    - range: sdos_Project
    - range: http___templekg.org_ontology_Location
    - range: http___templekg.org_ontology_NaturalHazard
    - range: http___templekg.org_ontology_OceanCirculation
    - range: http___templekg.org_ontology_Instrument
  http___templekg.org_ontology_TargetsLocation:
    name: http___templekg.org_ontology_TargetsLocation
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/TargetsLocation
    alias: http___templekg.org_ontology_TargetsLocation
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: Any
    any_of:
    - range: http___templekg.org_ontology_Platform
    - range: http___templekg.org_ontology_WeatherEvent
    - range: http___templekg.org_ontology_Teleconnection
    - range: http___templekg.org_ontology_Variable
    - range: http___templekg.org_ontology_Model
    - range: http___templekg.org_ontology_Others
    - range: http___templekg.org_ontology_Provider
    - range: http___templekg.org_ontology_Experiment
    - range: http___templekg.org_ontology_Location
    - range: http___templekg.org_ontology_Instrument
    - range: http___templekg.org_ontology_NaturalHazard
    - range: http___templekg.org_ontology_OceanCirculation
    - range: sdos_Project
  http___templekg.org_ontology_RunBy:
    name: http___templekg.org_ontology_RunBy
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/RunBy
    alias: http___templekg.org_ontology_RunBy
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_WeatherEvent
    range: Any
    any_of:
    - range: http___templekg.org_ontology_Platform
    - range: http___templekg.org_ontology_Teleconnection
    - range: http___templekg.org_ontology_Model
    - range: http___templekg.org_ontology_Others
    - range: http___templekg.org_ontology_Provider
    - range: http___templekg.org_ontology_Experiment
    - range: http___templekg.org_ontology_Location
    - range: http___templekg.org_ontology_OceanCirculation
    - range: sdos_Project
  prov_atLocation:
    name: prov_atLocation
    description: The Location of any resource.
    title: atLocation
    comments:
    - 'description: This property has multiple RDFS domains to suit multiple OWL Profiles.
      See <a href="#owl-profile">PROV-O OWL Profile</a>.'
    - No occurrences of this slot in the graph.
    from_schema: okns:prov
    source: http://www.w3.org/ns/prov-o#
    slot_uri: prov:atLocation
    alias: prov_atLocation
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: prov_Location
  http___templekg.org_ontology_ChildOf:
    name: http___templekg.org_ontology_ChildOf
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/ChildOf
    alias: http___templekg.org_ontology_ChildOf
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: Any
    any_of:
    - range: http___templekg.org_ontology_Platform
    - range: http___templekg.org_ontology_WeatherEvent
    - range: http___templekg.org_ontology_Variable
    - range: http___templekg.org_ontology_Model
    - range: http___templekg.org_ontology_Others
    - range: http___templekg.org_ontology_Provider
    - range: http___templekg.org_ontology_Location
    - range: http___templekg.org_ontology_Instrument
    - range: http___templekg.org_ontology_NaturalHazard
    - range: http___templekg.org_ontology_OceanCirculation
    - range: sdos_Project
  http___templekg.org_ontology_Outputs:
    name: http___templekg.org_ontology_Outputs
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/Outputs
    alias: http___templekg.org_ontology_Outputs
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: Any
    any_of:
    - range: http___templekg.org_ontology_Platform
    - range: http___templekg.org_ontology_WeatherEvent
    - range: http___templekg.org_ontology_Teleconnection
    - range: http___templekg.org_ontology_Variable
    - range: http___templekg.org_ontology_Model
    - range: http___templekg.org_ontology_Others
    - range: http___templekg.org_ontology_Provider
    - range: http___templekg.org_ontology_Experiment
    - range: http___templekg.org_ontology_Instrument
    - range: http___templekg.org_ontology_NaturalHazard
    - range: http___templekg.org_ontology_OceanCirculation
    - range: sdos_Project
  http___templekg.org_ontology_WikiHasParts:
    name: http___templekg.org_ontology_WikiHasParts
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/WikiHasParts
    alias: http___templekg.org_ontology_WikiHasParts
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: Any
    any_of:
    - range: http___templekg.org_ontology_Platform
    - range: http___templekg.org_ontology_WeatherEvent
    - range: http___templekg.org_ontology_Teleconnection
    - range: http___templekg.org_ontology_Variable
    - range: http___templekg.org_ontology_Others
    - range: http___templekg.org_ontology_Provider
    - range: sdos_Project
    - range: http___templekg.org_ontology_Location
    - range: http___templekg.org_ontology_Instrument
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - owl_OntologyProperty
    - rdf_List
    - rdfs_Datatype
    - sdos_ActionStatusType
    - sdos_AdultOrientedEnumeration
    - sdos_BoardingPolicyType
    - sdos_BodyMeasurementTypeEnumeration
    - sdos_BookFormatType
    - sdos_Boolean
    - sdos_CarUsageType
    - sdos_CertificationStatusEnumeration
    - sdos_ContactPointOption
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
    - dcam_VocabularyEncodingScheme
    - http___templekg.org_ontology_Experiment
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Location
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_OceanCirculation
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Paper
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_Provider
    - http___templekg.org_ontology_Teleconnection
    - http___templekg.org_ontology_Variable
    - http___templekg.org_ontology_WeatherEvent
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
  http___templekg.org_ontology_WikiHasEffect:
    name: http___templekg.org_ontology_WikiHasEffect
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: http://templekg.org/ontology/WikiHasEffect
    alias: http___templekg.org_ontology_WikiHasEffect
    owner: http___templekg.org_ontology_WeatherEvent
    domain_of:
    - http___templekg.org_ontology_Instrument
    - http___templekg.org_ontology_Model
    - http___templekg.org_ontology_NaturalHazard
    - http___templekg.org_ontology_Others
    - http___templekg.org_ontology_Platform
    - http___templekg.org_ontology_WeatherEvent
    range: Any
    any_of:
    - range: http___templekg.org_ontology_NaturalHazard
    - range: sdos_Project
    - range: http___templekg.org_ontology_Instrument
    - range: http___templekg.org_ontology_Others
class_uri: http://templekg.org/ontology/WeatherEvent

```
</details>