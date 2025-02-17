

# Class: No class (type) name specified (sudokn_AssemblyCapibility)


_No class (type) description specified_






This class occurs 1 times.


URI: [sudokn:AssemblyCapibility](http://asu.edu/semantics/SUDOKN/AssemblyCapibility)






```mermaid
 classDiagram
    class SudoknAssemblyCapibility
    click SudoknAssemblyCapibility href "../SudoknAssemblyCapibility"
      SudoknManufacturingProcessCapability <|-- SudoknAssemblyCapibility
        click SudoknManufacturingProcessCapability href "../SudoknManufacturingProcessCapability"
      

      SudoknAssemblyCapibility <|-- SudoknFabricatingCapability
        click SudoknFabricatingCapability href "../SudoknFabricatingCapability"
      SudoknAssemblyCapibility <|-- SudoknKittingCapability
        click SudoknKittingCapability href "../SudoknKittingCapability"
      SudoknAssemblyCapibility <|-- SudoknWireHarnessAssemblyCapability
        click SudoknWireHarnessAssemblyCapability href "../SudoknWireHarnessAssemblyCapability"
      
      
      
```





## Inheritance
* [IoscProductionCapability](../classes/IoscProductionCapability.md)
    * [SudoknManufacturingProcessCapability](../classes/SudoknManufacturingProcessCapability.md)
        * **SudoknAssemblyCapibility**
            * [SudoknFabricatingCapability](../classes/SudoknFabricatingCapability.md)
            * [SudoknKittingCapability](../classes/SudoknKittingCapability.md)
            * [SudoknWireHarnessAssemblyCapability](../classes/SudoknWireHarnessAssemblyCapability.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_hasProcessCapability](../slots/sudokn_hasProcessCapability.md) | any_of[range] | [SudoknAssemblyCapibility](../classes/SudoknAssemblyCapibility.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_hasProcessCapability](../slots/sudokn_hasProcessCapability.md) | any_of[range] | [SudoknAssemblyCapibility](../classes/SudoknAssemblyCapibility.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_AssemblyCapibility
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 1
description: No class (type) description specified
title: No class (type) name specified
from_schema: sudokn-kg
rank: 1000
is_a: sudokn_ManufacturingProcessCapability
class_uri: sudokn:AssemblyCapibility

```
</details>

### Induced

<details>

```yaml
name: sudokn_AssemblyCapibility
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 1
description: No class (type) description specified
title: No class (type) name specified
from_schema: sudokn-kg
rank: 1000
is_a: sudokn_ManufacturingProcessCapability
class_uri: sudokn:AssemblyCapibility

```
</details>