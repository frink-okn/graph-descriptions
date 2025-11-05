

# Class: carbon processing capability (sudokn_CarbonProcessingCapability)





URI: [sudokn:CarbonProcessingCapability](http://asu.edu/semantics/SUDOKN/CarbonProcessingCapability)






```mermaid
 classDiagram
    class SudoknCarbonProcessingCapability
    click SudoknCarbonProcessingCapability href "../SudoknCarbonProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknCarbonProcessingCapability
        click SudoknMaterialProcessingCapability href "../SudoknMaterialProcessingCapability"
      

      SudoknCarbonProcessingCapability <|-- SudoknGraphiteProcessingCapability
        click SudoknGraphiteProcessingCapability href "../SudoknGraphiteProcessingCapability"
      
      
      
```





## Inheritance
* [IoscProductionCapability](../classes/IoscProductionCapability.md)
    * [SudoknMaterialProcessingCapability](../classes/SudoknMaterialProcessingCapability.md)
        * **SudoknCarbonProcessingCapability**
            * [SudoknGraphiteProcessingCapability](../classes/SudoknGraphiteProcessingCapability.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_CarbonProcessingCapability
title: carbon processing capability
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_MaterialProcessingCapability
class_uri: sudokn:CarbonProcessingCapability

```
</details>

### Induced

<details>

```yaml
name: sudokn_CarbonProcessingCapability
title: carbon processing capability
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_MaterialProcessingCapability
class_uri: sudokn:CarbonProcessingCapability

```
</details>