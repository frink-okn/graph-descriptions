

# Class: energy industry (sudokn_EnergyIndustry)





URI: [sudokn:EnergyIndustry](http://asu.edu/semantics/SUDOKN/EnergyIndustry)






```mermaid
 classDiagram
    class SudoknEnergyIndustry
    click SudoknEnergyIndustry href "../SudoknEnergyIndustry"
      IoscIndustry <|-- SudoknEnergyIndustry
        click IoscIndustry href "../IoscIndustry"
      

      SudoknEnergyIndustry <|-- SudoknCoalIndustry
        click SudoknCoalIndustry href "../SudoknCoalIndustry"
      SudoknEnergyIndustry <|-- SudoknNuclearEnergyIndustry
        click SudoknNuclearEnergyIndustry href "../SudoknNuclearEnergyIndustry"
      SudoknEnergyIndustry <|-- SudoknOilAndGasIndustry
        click SudoknOilAndGasIndustry href "../SudoknOilAndGasIndustry"
      SudoknEnergyIndustry <|-- SudoknRenewableEnergyIndustry
        click SudoknRenewableEnergyIndustry href "../SudoknRenewableEnergyIndustry"
      
      
      
```





## Inheritance
* [IoscIndustry](../classes/IoscIndustry.md)
    * **SudoknEnergyIndustry**
        * [SudoknCoalIndustry](../classes/SudoknCoalIndustry.md)
        * [SudoknNuclearEnergyIndustry](../classes/SudoknNuclearEnergyIndustry.md)
        * [SudoknOilAndGasIndustry](../classes/SudoknOilAndGasIndustry.md)
        * [SudoknRenewableEnergyIndustry](../classes/SudoknRenewableEnergyIndustry.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_EnergyIndustry
title: energy industry
from_schema: okns:sudokn-kg
rank: 1000
is_a: iosc_Industry
class_uri: sudokn:EnergyIndustry

```
</details>

### Induced

<details>

```yaml
name: sudokn_EnergyIndustry
title: energy industry
from_schema: okns:sudokn-kg
rank: 1000
is_a: iosc_Industry
class_uri: sudokn:EnergyIndustry

```
</details>