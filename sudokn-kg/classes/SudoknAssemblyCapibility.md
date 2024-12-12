

# Class: assembly capability (sudokn_AssemblyCapibility)


_No type description provided_





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

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_hasProcessCapability](../slots/sudokn_hasProcessCapability.md) | any_of[range] | [SudoknAssemblyCapibility](../classes/SudoknAssemblyCapibility.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_hasProcessCapability](../slots/sudokn_hasProcessCapability.md) | any_of[range] | [SudoknAssemblyCapibility](../classes/SudoknAssemblyCapibility.md) |







## Examples

| Value |
| --- |
| sudokn:/AssemblyCapability_1 |

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
| self | sudokn:AssemblyCapibility |
| native | sudokn-kg/:SudoknAssemblyCapibility |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sudokn_AssemblyCapibility
description: No type description provided
title: assembly capability
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 1 occurences.
examples:
- value: sudokn:/AssemblyCapability_1
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
description: No type description provided
title: assembly capability
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 1 occurences.
examples:
- value: sudokn:/AssemblyCapability_1
from_schema: sudokn-kg
rank: 1000
is_a: sudokn_ManufacturingProcessCapability
class_uri: sudokn:AssemblyCapibility

```
</details>