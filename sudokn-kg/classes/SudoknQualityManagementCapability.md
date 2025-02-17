

# Class: No class (type) name specified (sudokn_QualityManagementCapability)


_No class (type) description specified_






This class occurs 1 times.


URI: [sudokn:QualityManagementCapability](http://asu.edu/semantics/SUDOKN/QualityManagementCapability)






```mermaid
 classDiagram
    class SudoknQualityManagementCapability
    click SudoknQualityManagementCapability href "../SudoknQualityManagementCapability"
      IoscProductionCapability <|-- SudoknQualityManagementCapability
        click IoscProductionCapability href "../IoscProductionCapability"
      
      
```





## Inheritance
* [IoscProductionCapability](../classes/IoscProductionCapability.md)
    * **SudoknQualityManagementCapability**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_hasManagementCapability](../slots/sudokn_hasManagementCapability.md) | any_of[range] | [SudoknQualityManagementCapability](../classes/SudoknQualityManagementCapability.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_hasManagementCapability](../slots/sudokn_hasManagementCapability.md) | any_of[range] | [SudoknQualityManagementCapability](../classes/SudoknQualityManagementCapability.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_attestsTo](../slots/sudokn_attestsTo.md) | any_of[range] | [SudoknQualityManagementCapability](../classes/SudoknQualityManagementCapability.md) |
| [SudoknAS9100Certificate](../classes/SudoknAS9100Certificate.md) | [sudokn_attestsTo](../slots/sudokn_attestsTo.md) | any_of[range] | [SudoknQualityManagementCapability](../classes/SudoknQualityManagementCapability.md) |
| [SudoknISO9000Certificate](../classes/SudoknISO9000Certificate.md) | [sudokn_attestsTo](../slots/sudokn_attestsTo.md) | any_of[range] | [SudoknQualityManagementCapability](../classes/SudoknQualityManagementCapability.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_QualityManagementCapability
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 1
description: No class (type) description specified
title: No class (type) name specified
from_schema: sudokn-kg
rank: 1000
is_a: iosc_ProductionCapability
class_uri: sudokn:QualityManagementCapability

```
</details>

### Induced

<details>

```yaml
name: sudokn_QualityManagementCapability
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 1
description: No class (type) description specified
title: No class (type) name specified
from_schema: sudokn-kg
rank: 1000
is_a: iosc_ProductionCapability
class_uri: sudokn:QualityManagementCapability

```
</details>