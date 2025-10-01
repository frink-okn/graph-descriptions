

# Class: HttpsIdir.uta.eduSockg-ontology#Rotation




This class occurs 66 times.


URI: [https://idir.uta.edu/sockg-ontology#Rotation](https://idir.uta.edu/sockg-ontology#Rotation)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#Rotation
    click HttpsIdir.uta.eduSockg-ontology#Rotation href "../HttpsIdir.uta.eduSockg-ontology#Rotation"
      HttpsIdir.uta.eduSockg-ontology#Rotation : dct_description
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Rotation --> "0..1" String : dct_description
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [dct_description](../slots/dct_description.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | Description may include but is not limited to: an abstract, a table of conten... <br/> description: An account of the resource. | direct | 66 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#hasRotation](../slots/https___idir.uta.edu_sockg_ontology#hasRotation.md) | range | [HttpsIdir.uta.eduSockg-ontology#Rotation](../classes/HttpsIdir.uta.eduSockg-ontology#Rotation.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Rotation
from_schema: okns:soc-kg
rank: 1000
slots:
- dct_description
class_uri: https://idir.uta.edu/sockg-ontology#Rotation

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Rotation
from_schema: okns:soc-kg
rank: 1000
attributes:
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
    owner: https___idir.uta.edu_sockg-ontology#Rotation
    domain_of:
    - qudt_BinaryPrefix
    - qudt_CardinalityType
    - qudt_ContextualUnit
    - qudt_CountingUnit
    - qudt_DecimalPrefix
    - qudt_DerivedUnit
    - qudt_DimensionlessUnit
    - qudt_LogarithmicUnit
    - qudt_Unit
    - vaem_GraphRole
    - https___idir.uta.edu_sockg-ontology#AnimalSpecies
    - https___idir.uta.edu_sockg-ontology#CoverCrop
    - https___idir.uta.edu_sockg-ontology#FertilizerAmendment
    - https___idir.uta.edu_sockg-ontology#GrazingRate
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Proceedings
    - https___idir.uta.edu_sockg-ontology#Project
    - https___idir.uta.edu_sockg-ontology#ProjectScenario
    - https___idir.uta.edu_sockg-ontology#ResidueRemoval
    - https___idir.uta.edu_sockg-ontology#Rotation
    - https___idir.uta.edu_sockg-ontology#Thesis
    - https___idir.uta.edu_sockg-ontology#Tillage
    - https___idir.uta.edu_sockg-ontology#Timing
    - https___idir.uta.edu_sockg-ontology#Treatment
    subproperty_of: dc_description
    range: string
class_uri: https://idir.uta.edu/sockg-ontology#Rotation

```
</details>