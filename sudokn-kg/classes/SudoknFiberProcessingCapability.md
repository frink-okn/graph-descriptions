

# Class: fiber processing capability (sudokn_FiberProcessingCapability)





URI: [sudokn:FiberProcessingCapability](http://asu.edu/semantics/SUDOKN/FiberProcessingCapability)






```mermaid
 classDiagram
    class SudoknFiberProcessingCapability
    click SudoknFiberProcessingCapability href "../SudoknFiberProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknFiberProcessingCapability
        click SudoknMaterialProcessingCapability href "../SudoknMaterialProcessingCapability"
      

      SudoknFiberProcessingCapability <|-- SudoknManMadeFiberProcessingCapability
        click SudoknManMadeFiberProcessingCapability href "../SudoknManMadeFiberProcessingCapability"
      SudoknFiberProcessingCapability <|-- SudoknNaturalFiberProcessingCapability
        click SudoknNaturalFiberProcessingCapability href "../SudoknNaturalFiberProcessingCapability"
      
      
      
```





## Inheritance
* [IoscProductionCapability](../classes/IoscProductionCapability.md)
    * [SudoknMaterialProcessingCapability](../classes/SudoknMaterialProcessingCapability.md)
        * **SudoknFiberProcessingCapability**
            * [SudoknManMadeFiberProcessingCapability](../classes/SudoknManMadeFiberProcessingCapability.md)
            * [SudoknNaturalFiberProcessingCapability](../classes/SudoknNaturalFiberProcessingCapability.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_FiberProcessingCapability
title: fiber processing capability
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_MaterialProcessingCapability
class_uri: sudokn:FiberProcessingCapability

```
</details>

### Induced

<details>

```yaml
name: sudokn_FiberProcessingCapability
title: fiber processing capability
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_MaterialProcessingCapability
class_uri: sudokn:FiberProcessingCapability

```
</details>