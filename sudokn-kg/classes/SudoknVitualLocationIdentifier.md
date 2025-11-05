

# Class: virtual location identifier (sudokn_VitualLocationIdentifier)





URI: [sudokn:VitualLocationIdentifier](http://asu.edu/semantics/SUDOKN/VitualLocationIdentifier)






```mermaid
 classDiagram
    class SudoknVitualLocationIdentifier
    click SudoknVitualLocationIdentifier href "../SudoknVitualLocationIdentifier"
      IoIdentifier <|-- SudoknVitualLocationIdentifier
        click IoIdentifier href "../IoIdentifier"
      

      SudoknVitualLocationIdentifier <|-- SudoknEmailAddress
        click SudoknEmailAddress href "../SudoknEmailAddress"
      SudoknVitualLocationIdentifier <|-- SudoknWebAddress
        click SudoknWebAddress href "../SudoknWebAddress"
      
      
      
```





## Inheritance
* [IoIdentifier](../classes/IoIdentifier.md)
    * **SudoknVitualLocationIdentifier**
        * [SudoknEmailAddress](../classes/SudoknEmailAddress.md)
        * [SudoknWebAddress](../classes/SudoknWebAddress.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_VitualLocationIdentifier
title: virtual location identifier
from_schema: okns:sudokn-kg
rank: 1000
is_a: io_Identifier
class_uri: sudokn:VitualLocationIdentifier

```
</details>

### Induced

<details>

```yaml
name: sudokn_VitualLocationIdentifier
title: virtual location identifier
from_schema: okns:sudokn-kg
rank: 1000
is_a: io_Identifier
class_uri: sudokn:VitualLocationIdentifier

```
</details>