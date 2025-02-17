

# Class: No class (type) name specified (sudokn_PostalAddress)


_No class (type) description specified_






This class occurs 20728 times.


URI: [sudokn:PostalAddress](http://asu.edu/semantics/SUDOKN/PostalAddress)






```mermaid
 classDiagram
    class SudoknPostalAddress
    click SudoknPostalAddress href "../SudoknPostalAddress"
      IoPhysicalLocationIdentifier <|-- SudoknPostalAddress
        click IoPhysicalLocationIdentifier href "../IoPhysicalLocationIdentifier"
      
      SudoknPostalAddress : iosc_hasTextValue
        
          
    
    
    SudoknPostalAddress --> "0..1" String : iosc_hasTextValue
    click String href "../String"

        
      
```





## Inheritance
* [IoPhysicalLocationIdentifier](../classes/IoPhysicalLocationIdentifier.md)
    * **SudoknPostalAddress**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [iosc_hasTextValue](../slots/iosc_hasTextValue.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 19102 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_hasPostalAddress](../slots/sudokn_hasPostalAddress.md) | any_of[range] | [SudoknPostalAddress](../classes/SudoknPostalAddress.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_hasPostalAddress](../slots/sudokn_hasPostalAddress.md) | any_of[range] | [SudoknPostalAddress](../classes/SudoknPostalAddress.md) |
| [SudoknGeospatialLocation](../classes/SudoknGeospatialLocation.md) | [sudokn_hasPostalAddress](../slots/sudokn_hasPostalAddress.md) | any_of[range] | [SudoknPostalAddress](../classes/SudoknPostalAddress.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_PostalAddress
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 20728
description: No class (type) description specified
title: No class (type) name specified
from_schema: sudokn-kg
rank: 1000
is_a: io_PhysicalLocationIdentifier
slots:
- iosc_hasTextValue
slot_usage:
  iosc_hasTextValue:
    name: iosc_hasTextValue
    annotations:
      string:
        tag: string
        value: 19102
class_uri: sudokn:PostalAddress

```
</details>

### Induced

<details>

```yaml
name: sudokn_PostalAddress
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 20728
description: No class (type) description specified
title: No class (type) name specified
from_schema: sudokn-kg
rank: 1000
is_a: io_PhysicalLocationIdentifier
slot_usage:
  iosc_hasTextValue:
    name: iosc_hasTextValue
    annotations:
      string:
        tag: string
        value: 19102
attributes:
  iosc_hasTextValue:
    name: iosc_hasTextValue
    annotations:
      string:
        tag: string
        value: 19102
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 10255 BEECH AVENUE
        example_object_type: string
        example_predicate: iosc:hasTextValue
        example_subject: sudokn:101PIPE-PostalAddress
        example_subject_type: sudokn_PostalAddress
    from_schema: sudokn-kg
    rank: 1000
    slot_uri: iosc:hasTextValue
    alias: iosc_hasTextValue
    owner: sudokn_PostalAddress
    domain_of:
    - sudokn_PostalAddress
    range: string
class_uri: sudokn:PostalAddress

```
</details>