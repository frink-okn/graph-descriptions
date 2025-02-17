

# Class: No class (type) name specified (sudokn_WebAddress)


_No class (type) description specified_






This class occurs 1 times.


URI: [sudokn:WebAddress](http://asu.edu/semantics/SUDOKN/WebAddress)






```mermaid
 classDiagram
    class SudoknWebAddress
    click SudoknWebAddress href "../SudoknWebAddress"
      SudoknVitualLocationIdentifier <|-- SudoknWebAddress
        click SudoknVitualLocationIdentifier href "../SudoknVitualLocationIdentifier"
      
      
```





## Inheritance
* [IoIdentifier](../classes/IoIdentifier.md)
    * [SudoknVitualLocationIdentifier](../classes/SudoknVitualLocationIdentifier.md)
        * **SudoknWebAddress**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_hasWebAddress](../slots/sudokn_hasWebAddress.md) | any_of[range] | [SudoknWebAddress](../classes/SudoknWebAddress.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_hasWebAddress](../slots/sudokn_hasWebAddress.md) | any_of[range] | [SudoknWebAddress](../classes/SudoknWebAddress.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_WebAddress
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 1
description: No class (type) description specified
title: No class (type) name specified
from_schema: sudokn-kg
rank: 1000
is_a: sudokn_VitualLocationIdentifier
class_uri: sudokn:WebAddress

```
</details>

### Induced

<details>

```yaml
name: sudokn_WebAddress
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 1
description: No class (type) description specified
title: No class (type) name specified
from_schema: sudokn-kg
rank: 1000
is_a: sudokn_VitualLocationIdentifier
class_uri: sudokn:WebAddress

```
</details>