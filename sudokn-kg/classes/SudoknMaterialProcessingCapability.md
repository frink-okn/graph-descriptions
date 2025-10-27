

# Class: material processing capability (sudokn_MaterialProcessingCapability)





URI: [sudokn:MaterialProcessingCapability](http://asu.edu/semantics/SUDOKN/MaterialProcessingCapability)






```mermaid
 classDiagram
    class SudoknMaterialProcessingCapability
    click SudoknMaterialProcessingCapability href "../SudoknMaterialProcessingCapability"
      IoscProductionCapability <|-- SudoknMaterialProcessingCapability
        click IoscProductionCapability href "../IoscProductionCapability"
      

      SudoknMaterialProcessingCapability <|-- SudoknCarbideProcessingCapability
        click SudoknCarbideProcessingCapability href "../SudoknCarbideProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknCarbonProcessingCapability
        click SudoknCarbonProcessingCapability href "../SudoknCarbonProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknCeramicProcessingCapability
        click SudoknCeramicProcessingCapability href "../SudoknCeramicProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknChemicalsProcessingCapability
        click SudoknChemicalsProcessingCapability href "../SudoknChemicalsProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknCompositeProcessingCapability
        click SudoknCompositeProcessingCapability href "../SudoknCompositeProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknElectronicProcessingCapability
        click SudoknElectronicProcessingCapability href "../SudoknElectronicProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknExoticMaterialProcessingCapability
        click SudoknExoticMaterialProcessingCapability href "../SudoknExoticMaterialProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknFiberProcessingCapability
        click SudoknFiberProcessingCapability href "../SudoknFiberProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknFoamProcessingCapability
        click SudoknFoamProcessingCapability href "../SudoknFoamProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknGlassProcessingCapability
        click SudoknGlassProcessingCapability href "../SudoknGlassProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknMetalProcessingCapability
        click SudoknMetalProcessingCapability href "../SudoknMetalProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknPlasticProcessingCapability
        click SudoknPlasticProcessingCapability href "../SudoknPlasticProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknRubberProcessingCapability
        click SudoknRubberProcessingCapability href "../SudoknRubberProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknSiliconeProcessingCapability
        click SudoknSiliconeProcessingCapability href "../SudoknSiliconeProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknTeflonProcessingCapability
        click SudoknTeflonProcessingCapability href "../SudoknTeflonProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknUrethaneProcessingCapability
        click SudoknUrethaneProcessingCapability href "../SudoknUrethaneProcessingCapability"
      SudoknMaterialProcessingCapability <|-- SudoknWoodProcessingCapability
        click SudoknWoodProcessingCapability href "../SudoknWoodProcessingCapability"
      
      
      
```





## Inheritance
* [IoscProductionCapability](../classes/IoscProductionCapability.md)
    * **SudoknMaterialProcessingCapability**
        * [SudoknCarbideProcessingCapability](../classes/SudoknCarbideProcessingCapability.md)
        * [SudoknCarbonProcessingCapability](../classes/SudoknCarbonProcessingCapability.md)
        * [SudoknCeramicProcessingCapability](../classes/SudoknCeramicProcessingCapability.md)
        * [SudoknChemicalsProcessingCapability](../classes/SudoknChemicalsProcessingCapability.md)
        * [SudoknCompositeProcessingCapability](../classes/SudoknCompositeProcessingCapability.md)
        * [SudoknElectronicProcessingCapability](../classes/SudoknElectronicProcessingCapability.md)
        * [SudoknExoticMaterialProcessingCapability](../classes/SudoknExoticMaterialProcessingCapability.md)
        * [SudoknFiberProcessingCapability](../classes/SudoknFiberProcessingCapability.md)
        * [SudoknFoamProcessingCapability](../classes/SudoknFoamProcessingCapability.md)
        * [SudoknGlassProcessingCapability](../classes/SudoknGlassProcessingCapability.md)
        * [SudoknMetalProcessingCapability](../classes/SudoknMetalProcessingCapability.md)
        * [SudoknPlasticProcessingCapability](../classes/SudoknPlasticProcessingCapability.md)
        * [SudoknRubberProcessingCapability](../classes/SudoknRubberProcessingCapability.md)
        * [SudoknSiliconeProcessingCapability](../classes/SudoknSiliconeProcessingCapability.md)
        * [SudoknTeflonProcessingCapability](../classes/SudoknTeflonProcessingCapability.md)
        * [SudoknUrethaneProcessingCapability](../classes/SudoknUrethaneProcessingCapability.md)
        * [SudoknWoodProcessingCapability](../classes/SudoknWoodProcessingCapability.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_hasMaterialCapability](../slots/sudokn_hasMaterialCapability.md) | any_of[range] | [SudoknMaterialProcessingCapability](../classes/SudoknMaterialProcessingCapability.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_MaterialProcessingCapability
title: material processing capability
from_schema: okns:sudokn-kg
rank: 1000
is_a: iosc_ProductionCapability
class_uri: sudokn:MaterialProcessingCapability

```
</details>

### Induced

<details>

```yaml
name: sudokn_MaterialProcessingCapability
title: material processing capability
from_schema: okns:sudokn-kg
rank: 1000
is_a: iosc_ProductionCapability
class_uri: sudokn:MaterialProcessingCapability

```
</details>