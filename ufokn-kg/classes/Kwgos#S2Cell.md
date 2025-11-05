

# Class: Kwgos#S2Cell




This class occurs 11717916 times.


URI: [kwgos:#S2Cell](https://stko-kwg.geog.ucsb.edu/lod/ontology#S2Cell)






```mermaid
 classDiagram
    class Kwgos#S2Cell
    click Kwgos#S2Cell href "../Kwgos#S2Cell"
      Kwgos#S2Cell : sdos_additionalType
        
          
    
    
    Kwgos#S2Cell --> "0..1" Any : sdos_additionalType
    click Any href "../Any"

        
      Kwgos#S2Cell : sdos_description
        
          
    
    
    Kwgos#S2Cell --> "0..1" Any : sdos_description
    click Any href "../Any"

        
      Kwgos#S2Cell : sdos_name
        
          
    
    
    Kwgos#S2Cell --> "0..1" SdosText : sdos_name
    click SdosText href "../SdosText"

        
      Kwgos#S2Cell : sdos_value
        
          
    
    
    Kwgos#S2Cell --> "0..1" Any : sdos_value
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [sdos_description](../slots/sdos_description.md) | 0..1 <br/> [SdosTextObject](../classes/SdosTextObject.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md) | A description of the item <br/>  | direct | 11717916 |
| [sdos_name](../slots/sdos_name.md) | 0..1 <br/> [SdosText](../classes/SdosText.md) | The name of the item <br/>  | direct | 11717916 |
| [sdos_additionalType](../slots/sdos_additionalType.md) | 0..1 <br/> [SdosURL](../classes/SdosURL.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md) | An additional type for the item, typically used for adding more specific type... <br/>  | direct | 11717916 |
| [sdos_value](../slots/sdos_value.md) | 0..1 <br/> [SdosNumber](../classes/SdosNumber.md)&nbsp;or&nbsp;<br />[SdosStructuredValue](../classes/SdosStructuredValue.md)&nbsp;or&nbsp;<br />[SdosBoolean](../classes/SdosBoolean.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md) | The value of a [[QuantitativeValue]] (including [[Observation]]) or property ... <br/>  | direct | 11717916 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: kwgos_#S2Cell
from_schema: okns:ufokn-kg
rank: 1000
slots:
- sdos_description
- sdos_name
- sdos_additionalType
- sdos_value
class_uri: kwgos:#S2Cell

```
</details>

### Induced

<details>

```yaml
name: kwgos_#S2Cell
from_schema: okns:ufokn-kg
rank: 1000
attributes:
  sdos_description:
    name: sdos_description
    description: A description of the item.
    title: description
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:sdo
    exact_mappings:
    - http://purl.org/dc/terms/description
    domain: sdos_Thing
    slot_uri: sdos:description
    alias: sdos_description
    owner: kwgos_#S2Cell
    domain_of:
    - kwgos_#S2Cell
    range: Any
    any_of:
    - range: sdos_TextObject
    - range: sdos_Text
  sdos_name:
    name: sdos_name
    description: The name of the item.
    title: name
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:sdo
    exact_mappings:
    - http://purl.org/dc/terms/title
    domain: sdos_Thing
    slot_uri: sdos:name
    alias: sdos_name
    owner: kwgos_#S2Cell
    domain_of:
    - kwgos_#S2Cell
    subproperty_of: rdfs_label
    range: sdos_Text
  sdos_additionalType:
    name: sdos_additionalType
    description: An additional type for the item, typically used for adding more specific
      types from external vocabularies in microdata syntax. This is a relationship
      between something and a class that the thing is in. Typically the value is a
      URI-identified RDF class, and in this case corresponds to the␊    use of rdf:type
      in RDF. Text values can be used sparingly, for cases where useful information
      can be added without their being an appropriate schema to reference. In the
      case of text values, the class label should follow the schema.org <a href="https://schema.org/docs/styleguide.html">style
      guide</a>.
    title: additionalType
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:sdo
    domain: sdos_Thing
    slot_uri: sdos:additionalType
    alias: sdos_additionalType
    owner: kwgos_#S2Cell
    domain_of:
    - kwgos_#S2Cell
    subproperty_of: rdf_type
    range: Any
    any_of:
    - range: sdos_URL
    - range: sdos_Text
  sdos_value:
    name: sdos_value
    description: The value of a [[QuantitativeValue]] (including [[Observation]])
      or property value node.\n\n* For [[QuantitativeValue]] and [[MonetaryAmount]],
      the recommended type for values is 'Number'.\n* For [[PropertyValue]], it can
      be 'Text', 'Number', 'Boolean', or 'StructuredValue'.\n* Use values from 0123456789
      (Unicode 'DIGIT ZERO' (U+0030) to 'DIGIT NINE' (U+0039)) rather than superficially
      similar Unicode symbols.\n* Use '.' (Unicode 'FULL STOP' (U+002E)) rather than
      ',' to indicate a decimal point. Avoid using these symbols as a readability
      separator.
    title: value
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:sdo
    contributors:
    - https://schema.org/docs/collab/GoodRelationsTerms
    slot_uri: sdos:value
    alias: sdos_value
    owner: kwgos_#S2Cell
    domain_of:
    - kwgos_#S2Cell
    union_of:
    - sdos_MonetaryAmount
    - sdos_PropertyValue
    - sdos_QuantitativeValue
    range: Any
    any_of:
    - range: sdos_Number
    - range: sdos_StructuredValue
    - range: sdos_Boolean
    - range: sdos_Text
class_uri: kwgos:#S2Cell

```
</details>