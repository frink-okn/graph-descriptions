

# Class: Quantity value (qudt_QuantityValue)


_A <i>Quantity Value</i> expresses the magnitude and kind of a quantity and is given by the product of a numerical value <code>n</code> and a unit of measure <code>U</code>. The number multiplying the unit is referred to as the numerical value of the quantity expressed in that unit. Refer to <a href="http://physics.nist.gov/Pubs/SP811/sec07.html">NIST SP 811 section 7</a> for more on quantity values._







URI: [qudt:QuantityValue](http://qudt.org/schema/qudt/QuantityValue)






```mermaid
 classDiagram
    class QudtQuantityValue
    click QudtQuantityValue href "../QudtQuantityValue"
      QudtQuantifiable <|-- QudtQuantityValue
        click QudtQuantifiable href "../QudtQuantifiable"
      
      
```





## Inheritance
* [QudtQuantifiable](../classes/QudtQuantifiable.md)
    * **QudtQuantityValue**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [qudt_quantityValue](../slots/qudt_quantityValue.md) | any_of[range] | [QudtQuantityValue](../classes/QudtQuantityValue.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [qudt_quantityValue](../slots/qudt_quantityValue.md) | any_of[range] | [QudtQuantityValue](../classes/QudtQuantityValue.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: qudt_QuantityValue
conforms_to: No schema conformance document specified
description: A <i>Quantity Value</i> expresses the magnitude and kind of a quantity
  and is given by the product of a numerical value <code>n</code> and a unit of measure
  <code>U</code>. The number multiplying the unit is referred to as the numerical
  value of the quantity expressed in that unit. Refer to <a href="http://physics.nist.gov/Pubs/SP811/sec07.html">NIST
  SP 811 section 7</a> for more on quantity values.
title: Quantity value
from_schema: sawgraph-kg
source: http://qudt.org/2.1/schema/qudt
rank: 1000
is_a: qudt_Quantifiable
class_uri: qudt:QuantityValue

```
</details>

### Induced

<details>

```yaml
name: qudt_QuantityValue
conforms_to: No schema conformance document specified
description: A <i>Quantity Value</i> expresses the magnitude and kind of a quantity
  and is given by the product of a numerical value <code>n</code> and a unit of measure
  <code>U</code>. The number multiplying the unit is referred to as the numerical
  value of the quantity expressed in that unit. Refer to <a href="http://physics.nist.gov/Pubs/SP811/sec07.html">NIST
  SP 811 section 7</a> for more on quantity values.
title: Quantity value
from_schema: sawgraph-kg
source: http://qudt.org/2.1/schema/qudt
rank: 1000
is_a: qudt_Quantifiable
class_uri: qudt:QuantityValue

```
</details>