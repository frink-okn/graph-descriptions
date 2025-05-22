

# Class: Quantity Kind (qudt_QuantityKind)


_A <b>Quantity Kind</b> is any observable property that can be  measured and quantified numerically. Familiar examples include physical properties such as length, mass, time, force, energy, power, electric charge, etc. Less familiar examples include currency, interest rate, price to earning ratio, and information capacity._







URI: [qudt:QuantityKind](http://qudt.org/schema/qudt/QuantityKind)






```mermaid
 classDiagram
    class QudtQuantityKind
    click QudtQuantityKind href "../QudtQuantityKind"
      StadQualityKind <|-- QudtQuantityKind
        click StadQualityKind href "../StadQualityKind"
      
      
```





## Inheritance
* [StadQualityKind](../classes/StadQualityKind.md)
    * **QudtQuantityKind**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | [qudt_hasQuantityKind](../slots/qudt_hasQuantityKind.md) | any_of[range] | [QudtQuantityKind](../classes/QudtQuantityKind.md) |
| [QudtUnit](../classes/QudtUnit.md) | [qudt_hasQuantityKind](../slots/qudt_hasQuantityKind.md) | any_of[range] | [QudtQuantityKind](../classes/QudtQuantityKind.md) |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [qudt_hasQuantityKind](../slots/qudt_hasQuantityKind.md) | any_of[range] | [QudtQuantityKind](../classes/QudtQuantityKind.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [qudt_hasQuantityKind](../slots/qudt_hasQuantityKind.md) | any_of[range] | [QudtQuantityKind](../classes/QudtQuantityKind.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: qudt_QuantityKind
conforms_to: No schema conformance document specified
description: A <b>Quantity Kind</b> is any observable property that can be  measured
  and quantified numerically. Familiar examples include physical properties such as
  length, mass, time, force, energy, power, electric charge, etc. Less familiar examples
  include currency, interest rate, price to earning ratio, and information capacity.
title: Quantity Kind
from_schema: sawgraph-kg
source: http://qudt.org/2.1/schema/qudt
rank: 1000
is_a: stad_QualityKind
class_uri: qudt:QuantityKind

```
</details>

### Induced

<details>

```yaml
name: qudt_QuantityKind
conforms_to: No schema conformance document specified
description: A <b>Quantity Kind</b> is any observable property that can be  measured
  and quantified numerically. Familiar examples include physical properties such as
  length, mass, time, force, energy, power, electric charge, etc. Less familiar examples
  include currency, interest rate, price to earning ratio, and information capacity.
title: Quantity Kind
from_schema: sawgraph-kg
source: http://qudt.org/2.1/schema/qudt
rank: 1000
is_a: stad_QualityKind
class_uri: qudt:QuantityKind

```
</details>