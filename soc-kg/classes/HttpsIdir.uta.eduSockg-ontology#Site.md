

# Class: HttpsIdir.uta.eduSockg-ontology#Site




This class occurs 60 times.


URI: [https://idir.uta.edu/sockg-ontology#Site](https://idir.uta.edu/sockg-ontology#Site)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#Site
    click HttpsIdir.uta.eduSockg-ontology#Site href "../HttpsIdir.uta.eduSockg-ontology#Site"
      GeoFeature <|-- HttpsIdir.uta.eduSockg-ontology#Site
        click GeoFeature href "../GeoFeature"
      
      HttpsIdir.uta.eduSockg-ontology#Site : dct_identifier
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Site --> "0..1" RdfsLiteral : dct_identifier
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpsIdir.uta.eduSockg-ontology#Site : kwgo_sfContains
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Site --> "0..1" Any : kwgo_sfContains
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#Site : kwgo_sfWithin
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Site --> "0..1" Any : kwgo_sfWithin
    click Any href "../Any"

        
      HttpsIdir.uta.eduSockg-ontology#Site : sdos_postalCode
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Site --> "0..1" SdosText : sdos_postalCode
    click SdosText href "../SdosText"

        
      HttpsIdir.uta.eduSockg-ontology#Site : spatial_connectedTo
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Site --> "0..1" Any : spatial_connectedTo
    click Any href "../Any"

        
      
```





## Inheritance
* [GeoSpatialObject](../classes/GeoSpatialObject.md)
    * [GeoFeature](../classes/GeoFeature.md)
        * **HttpsIdir.uta.eduSockg-ontology#Site**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [kwgo_sfContains](../slots/kwgo_sfContains.md) | 0..1 <br/> [Any](../classes/Any.md) | KWG's spatial contains relation <br/>  | direct | 3808 |
| [dct_identifier](../slots/dct_identifier.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | Recommended practice is to identify the resource by means of a string conform... <br/> description: An unambiguous reference to the resource within a given context. | direct | 60 |
| [spatial_connectedTo](../slots/spatial_connectedTo.md) | 0..1 <br/> [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#Site](../classes/HttpsIdir.uta.eduSockg-ontology#Site.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)&nbsp;or&nbsp;<br />[HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |  <br/>  | direct | 134 |
| [sdos_postalCode](../slots/sdos_postalCode.md) | 0..1 <br/> [SdosText](../classes/SdosText.md) | The postal code <br/>  | direct | 59 |
| [kwgo_sfWithin](../slots/kwgo_sfWithin.md) | 0..1 <br/> [Any](../classes/Any.md) | KWG's spatial within relation <br/>  | direct | 227 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Site](../classes/HttpsIdir.uta.eduSockg-ontology#Site.md) |
| [HttpsIdir.uta.eduSockg-ontology#Site](../classes/HttpsIdir.uta.eduSockg-ontology#Site.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Site](../classes/HttpsIdir.uta.eduSockg-ontology#Site.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Site](../classes/HttpsIdir.uta.eduSockg-ontology#Site.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Site
from_schema: okns:soc-kg
rank: 1000
is_a: geo_Feature
slots:
- kwgo_sfContains
- dct_identifier
- spatial_connectedTo
- sdos_postalCode
- kwgo_sfWithin
class_uri: https://idir.uta.edu/sockg-ontology#Site

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Site
from_schema: okns:soc-kg
rank: 1000
is_a: geo_Feature
attributes:
  kwgo_sfContains:
    name: kwgo_sfContains
    description: KWG's spatial contains relation
    title: contains (simple feature)
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:kwg
    slot_uri: kwgo:sfContains
    alias: kwgo_sfContains
    owner: https___idir.uta.edu_sockg-ontology#Site
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Site
    subproperty_of: kwgo_spatialRelation
    range: Any
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
    owner: https___idir.uta.edu_sockg-ontology#Site
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Site
    - https___idir.uta.edu_sockg-ontology#Treatment
    subproperty_of: dc_identifier
    range: rdfs_Literal
  spatial_connectedTo:
    name: spatial_connectedTo
    title: topological connection (spatial contact) (sawgraph)
    from_schema: okns:soc-kg
    rank: 1000
    slot_uri: spatial:connectedTo
    alias: spatial_connectedTo
    owner: https___idir.uta.edu_sockg-ontology#Site
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Site
    - kwgo_S2Cell_Level13
    subproperty_of: spatial_spatiallyRelatedTo
    range: Any
    any_of:
    - range: kwgo_AdministrativeRegion_2
    - range: https___idir.uta.edu_sockg-ontology#Site
    - range: kwgo_S2Cell_Level13
    - range: https___idir.uta.edu_sockg-ontology#Location
  sdos_postalCode:
    name: sdos_postalCode
    description: The postal code. For example, 94043.
    title: postalCode
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:sdo
    source: https://github.com/schemaorg/schemaorg/issues/2506
    slot_uri: sdos:postalCode
    alias: sdos_postalCode
    owner: https___idir.uta.edu_sockg-ontology#Site
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Site
    union_of:
    - sdos_PostalAddress
    - sdos_DefinedRegion
    - sdos_GeoShape
    - sdos_GeoCoordinates
    range: sdos_Text
  kwgo_sfWithin:
    name: kwgo_sfWithin
    description: KWG's spatial within relation
    title: within (simple feature)
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:kwg
    slot_uri: kwgo:sfWithin
    alias: kwgo_sfWithin
    owner: https___idir.uta.edu_sockg-ontology#Site
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Site
    - kwgo_S2Cell_Level13
    subproperty_of: kwgo_spatialRelation
    range: Any
class_uri: https://idir.uta.edu/sockg-ontology#Site

```
</details>