

# Class: No class (type) name specified (sudokn_TwoDimensionalCartesianSpatialCoordinateDatum)


_No class (type) description specified_






This class occurs 20728 times.


URI: [sudokn:TwoDimensionalCartesianSpatialCoordinateDatum](http://asu.edu/semantics/SUDOKN/TwoDimensionalCartesianSpatialCoordinateDatum)






```mermaid
 classDiagram
    class SudoknTwoDimensionalCartesianSpatialCoordinateDatum
    click SudoknTwoDimensionalCartesianSpatialCoordinateDatum href "../SudoknTwoDimensionalCartesianSpatialCoordinateDatum"
      IoInformationContentEntity <|-- SudoknTwoDimensionalCartesianSpatialCoordinateDatum
        click IoInformationContentEntity href "../IoInformationContentEntity"
      
      SudoknTwoDimensionalCartesianSpatialCoordinateDatum : sudokn_hasLatitudeValue
        
          
    
    
    SudoknTwoDimensionalCartesianSpatialCoordinateDatum --> "0..1" Any : sudokn_hasLatitudeValue
    click Any href "../Any"

        
      SudoknTwoDimensionalCartesianSpatialCoordinateDatum : sudokn_hasLongitudeValue
        
          
    
    
    SudoknTwoDimensionalCartesianSpatialCoordinateDatum --> "0..1" Any : sudokn_hasLongitudeValue
    click Any href "../Any"

        
      
```





## Inheritance
* [IoInformationContentEntity](../classes/IoInformationContentEntity.md)
    * **SudoknTwoDimensionalCartesianSpatialCoordinateDatum**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [sudokn_hasLatitudeValue](../slots/sudokn_hasLatitudeValue.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 19082 |
| [sudokn_hasLongitudeValue](../slots/sudokn_hasLongitudeValue.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 19083 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SudoknGeospatialLocation](../classes/SudoknGeospatialLocation.md) | [sudokn_hasSpatialCoordinates](../slots/sudokn_hasSpatialCoordinates.md) | range | [SudoknTwoDimensionalCartesianSpatialCoordinateDatum](../classes/SudoknTwoDimensionalCartesianSpatialCoordinateDatum.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 20728
description: No class (type) description specified
title: No class (type) name specified
from_schema: sudokn-kg
rank: 1000
is_a: io_InformationContentEntity
slots:
- sudokn_hasLatitudeValue
- sudokn_hasLongitudeValue
slot_usage:
  sudokn_hasLatitudeValue:
    name: sudokn_hasLatitudeValue
    annotations:
      string:
        tag: string
        value: 19082
  sudokn_hasLongitudeValue:
    name: sudokn_hasLongitudeValue
    annotations:
      string:
        tag: string
        value: 19083
class_uri: sudokn:TwoDimensionalCartesianSpatialCoordinateDatum

```
</details>

### Induced

<details>

```yaml
name: sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 20728
description: No class (type) description specified
title: No class (type) name specified
from_schema: sudokn-kg
rank: 1000
is_a: io_InformationContentEntity
slot_usage:
  sudokn_hasLatitudeValue:
    name: sudokn_hasLatitudeValue
    annotations:
      string:
        tag: string
        value: 19082
  sudokn_hasLongitudeValue:
    name: sudokn_hasLongitudeValue
    annotations:
      string:
        tag: string
        value: 19083
attributes:
  sudokn_hasLatitudeValue:
    name: sudokn_hasLatitudeValue
    annotations:
      string:
        tag: string
        value: 19082
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: '34.0677902'
        example_object_type: string
        example_predicate: sudokn:hasLatitudeValue
        example_subject: sudokn:101PIPE-site-FONTANA-92335-coordinates
        example_subject_type: sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
    from_schema: sudokn-kg
    rank: 1000
    slot_uri: sudokn:hasLatitudeValue
    alias: sudokn_hasLatitudeValue
    owner: sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
    domain_of:
    - sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
    range: Any
    any_of:
    - range: uri
    - range: string
  sudokn_hasLongitudeValue:
    name: sudokn_hasLongitudeValue
    annotations:
      string:
        tag: string
        value: 19083
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: '-117.4708951'
        example_object_type: string
        example_predicate: sudokn:hasLongitudeValue
        example_subject: sudokn:101PIPE-site-FONTANA-92335-coordinates
        example_subject_type: sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
    from_schema: sudokn-kg
    rank: 1000
    slot_uri: sudokn:hasLongitudeValue
    alias: sudokn_hasLongitudeValue
    owner: sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
    domain_of:
    - sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
    range: Any
    any_of:
    - range: uri
    - range: string
class_uri: sudokn:TwoDimensionalCartesianSpatialCoordinateDatum

```
</details>