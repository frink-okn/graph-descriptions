

# Class: email address (sudokn_EmailAddress)


_TODO -- tell the world what this class (type) describes._





URI: [sudokn:EmailAddress](http://asu.edu/semantics/SUDOKN/EmailAddress)






```mermaid
 classDiagram
    class SudoknEmailAddress
    click SudoknEmailAddress href "../SudoknEmailAddress"
      SudoknVitualLocationIdentifier <|-- SudoknEmailAddress
        click SudoknVitualLocationIdentifier href "../SudoknVitualLocationIdentifier"
      
      
```





## Inheritance
* [IoIdentifier](../classes/IoIdentifier.md)
    * [SudoknVitualLocationIdentifier](../classes/SudoknVitualLocationIdentifier.md)
        * **SudoknEmailAddress**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_hasEmailAddress](../slots/sudokn_hasEmailAddress.md) | any_of[range] | [SudoknEmailAddress](../classes/SudoknEmailAddress.md) |







## Examples

| Value |
| --- |
| sudokn:/EmailAddress_1 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sudokn-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sudokn:EmailAddress |
| native | sudokn-kg/:SudoknEmailAddress |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sudokn_EmailAddress
description: TODO -- tell the world what this class (type) describes.
title: email address
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 1 occurences.
examples:
- value: sudokn:/EmailAddress_1
from_schema: sudokn-kg
is_a: sudokn_VitualLocationIdentifier
class_uri: sudokn:EmailAddress

```
</details>

### Induced

<details>
```yaml
name: sudokn_EmailAddress
description: TODO -- tell the world what this class (type) describes.
title: email address
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 1 occurences.
examples:
- value: sudokn:/EmailAddress_1
from_schema: sudokn-kg
is_a: sudokn_VitualLocationIdentifier
class_uri: sudokn:EmailAddress

```
</details>