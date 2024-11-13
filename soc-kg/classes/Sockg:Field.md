

# Class: TODO -- what's a good name for what this class (type) describes? (sockg:Field)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:Field](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/Field)






```mermaid
 classDiagram
    class Sockg:Field
    click Sockg:Field href "../Sockg:Field"
      Sockg:Field : sockg:elevation_m
        
          
    
    
    Sockg:Field --> "0..1" Double : sockg:elevation_m
    click Double href "../Double"

        
      Sockg:Field : sockg:fieldId
        
          
    
    
    Sockg:Field --> "0..1" String : sockg:fieldId
    click String href "../String"

        
      Sockg:Field : sockg:latitude_decimal_deg
        
          
    
    
    Sockg:Field --> "0..1" Double : sockg:latitude_decimal_deg
    click Double href "../Double"

        
      Sockg:Field : sockg:longitude_decimal_deg
        
          
    
    
    Sockg:Field --> "0..1" Double : sockg:longitude_decimal_deg
    click Double href "../Double"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg:longitude_decimal_deg](../slots/sockg:longitude_decimal_deg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:elevation_m](../slots/sockg:elevation_m.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:fieldId](../slots/sockg:fieldId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:latitude_decimal_deg](../slots/sockg:latitude_decimal_deg.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Sockg:ExperimentalUnit](../classes/Sockg:ExperimentalUnit.md) | [sockg:locatedInField](../slots/sockg:locatedInField.md) | range | [Sockg:Field](../classes/Sockg:Field.md) |
| [Sockg:Site](../classes/Sockg:Site.md) | [sockg:hasField](../slots/sockg:hasField.md) | range | [Sockg:Field](../classes/Sockg:Field.md) |
| [Sockg:WaterQualityArea](../classes/Sockg:WaterQualityArea.md) | [sockg:waterQualityAreaDataAt](../slots/sockg:waterQualityAreaDataAt.md) | range | [Sockg:Field](../classes/Sockg:Field.md) |
| [Sockg:WaterQualityConc](../classes/Sockg:WaterQualityConc.md) | [sockg:waterQualityConcDataAt](../slots/sockg:waterQualityConcDataAt.md) | range | [Sockg:Field](../classes/Sockg:Field.md) |
| [Sockg:WeatherObservation](../classes/Sockg:WeatherObservation.md) | [sockg:weatherAtField](../slots/sockg:weatherAtField.md) | range | [Sockg:Field](../classes/Sockg:Field.md) |
| [Sockg:WeatherStation](../classes/Sockg:WeatherStation.md) | [sockg:recordsWeatherForField](../slots/sockg:recordsWeatherForField.md) | range | [Sockg:Field](../classes/Sockg:Field.md) |
| [Sockg:WindErosionArea](../classes/Sockg:WindErosionArea.md) | [sockg:windErosionDataAt](../slots/sockg:windErosionDataAt.md) | range | [Sockg:Field](../classes/Sockg:Field.md) |
| [Sockg:YieldNutrientUptake](../classes/Sockg:YieldNutrientUptake.md) | [sockg:yieldNutrUptakeDataAt](../slots/sockg:yieldNutrUptakeDataAt.md) | range | [Sockg:Field](../classes/Sockg:Field.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#55585 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: soc-kg/main




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sockg:Field |
| native | soc-kg/main/:Sockg:Field |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg:Field
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 58 instances of this class.
examples:
- value: neo4j://graph.individuals#55585
from_schema: soc-kg/main
slots:
- sockg:longitude_decimal_deg
- sockg:elevation_m
- sockg:fieldId
- sockg:latitude_decimal_deg
class_uri: sockg:Field

```
</details>

### Induced

<details>
```yaml
name: sockg:Field
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 58 instances of this class.
examples:
- value: neo4j://graph.individuals#55585
from_schema: soc-kg/main
attributes:
  sockg:longitude_decimal_deg:
    name: sockg:longitude_decimal_deg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 58 occurrences with subject type sockg:Field and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#55600 sockg:longitude_decimal_deg nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:longitude_decimal_deg
    alias: sockg:longitude_decimal_deg
    owner: sockg:Field
    domain_of:
    - sockg:Field
    range: double
  sockg:elevation_m:
    name: sockg:elevation_m
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 58 occurrences with subject type sockg:Field and object type xsd:double.
    - 12 occurrences with subject type sockg:WeatherStation and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#55601 sockg:elevation_m nan
    - value: neo4j://graph.individuals#509298 sockg:elevation_m nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:elevation_m
    alias: sockg:elevation_m
    owner: sockg:Field
    domain_of:
    - sockg:Field
    - sockg:WeatherStation
    range: double
  sockg:fieldId:
    name: sockg:fieldId
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 2791 occurrences with subject type sockg:NutrientEfficiency and object type
      string.
    - 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
    - 667 occurrences with subject type sockg:WaterQualityArea and object type string.
    - 429 occurrences with subject type sockg:YieldNutrientUptake and object type
      string.
    - 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
    - 15 occurrences with subject type sockg:WindErosionArea and object type string.
    - 58 occurrences with subject type sockg:Field and object type string.
    examples:
    - value: neo4j://graph.individuals#201298 sockg:fieldId NELITCSE
    - value: neo4j://graph.individuals#55677 sockg:fieldId WIPDBARN
    - value: neo4j://graph.individuals#360040 sockg:fieldId WIPDBARN
    - value: neo4j://graph.individuals#509384 sockg:fieldId ALAURye
    - value: neo4j://graph.individuals#361395 sockg:fieldId WIPDBARN
    - value: neo4j://graph.individuals#509301 sockg:fieldId TXBSWEWC
    - value: neo4j://graph.individuals#55606 sockg:fieldId NELITCSE
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:fieldId
    alias: sockg:fieldId
    owner: sockg:Field
    domain_of:
    - sockg:Field
    - sockg:GasNutrientLoss
    - sockg:NutrientEfficiency
    - sockg:WaterQualityArea
    - sockg:WaterQualityConc
    - sockg:WindErosionArea
    - sockg:YieldNutrientUptake
    range: string
  sockg:latitude_decimal_deg:
    name: sockg:latitude_decimal_deg
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 58 occurrences with subject type sockg:Field and object type xsd:double.
    examples:
    - value: neo4j://graph.individuals#55604 sockg:latitude_decimal_deg nan
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:latitude_decimal_deg
    alias: sockg:latitude_decimal_deg
    owner: sockg:Field
    domain_of:
    - sockg:Field
    range: double
class_uri: sockg:Field

```
</details>