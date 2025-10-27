

# Class: No class (entity type) name specified -- this class is noted as a superclass of another class in this graph but has not itself been defined. (sudokn_GeopoliticalSite)





URI: [sudokn:GeopoliticalSite](http://asu.edu/semantics/SUDOKN/GeopoliticalSite)






```mermaid
 classDiagram
    class SudoknGeopoliticalSite
    click SudoknGeopoliticalSite href "../SudoknGeopoliticalSite"
      OboBFO0000029 <|-- SudoknGeopoliticalSite
        click OboBFO0000029 href "../OboBFO0000029"
      

      SudoknGeopoliticalSite <|-- SudoknCity
        click SudoknCity href "../SudoknCity"
      SudoknGeopoliticalSite <|-- SudoknCountry
        click SudoknCountry href "../SudoknCountry"
      SudoknGeopoliticalSite <|-- SudoknCounty
        click SudoknCounty href "../SudoknCounty"
      SudoknGeopoliticalSite <|-- SudoknState
        click SudoknState href "../SudoknState"
      
      
      
```





## Inheritance
* [OboBFO0000029](../classes/OboBFO0000029.md)
    * **SudoknGeopoliticalSite**
        * [SudoknCity](../classes/SudoknCity.md)
        * [SudoknCountry](../classes/SudoknCountry.md)
        * [SudoknCounty](../classes/SudoknCounty.md)
        * [SudoknState](../classes/SudoknState.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_GeopoliticalSite
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:sudokn-kg
rank: 1000
is_a: obo_BFO_0000029
class_uri: sudokn:GeopoliticalSite

```
</details>

### Induced

<details>

```yaml
name: sudokn_GeopoliticalSite
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: okns:sudokn-kg
rank: 1000
is_a: obo_BFO_0000029
class_uri: sudokn:GeopoliticalSite

```
</details>