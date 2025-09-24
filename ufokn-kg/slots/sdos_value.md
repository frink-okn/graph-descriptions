

# Slot: value (sdos_value)


_The value of a [[QuantitativeValue]] (including [[Observation]]) or property value node.\n\n* For [[QuantitativeValue]] and [[MonetaryAmount]], the recommended type for values is 'Number'.\n* For [[PropertyValue]], it can be 'Text', 'Number', 'Boolean', or 'StructuredValue'.\n* Use values from 0123456789 (Unicode 'DIGIT ZERO' (U+0030) to 'DIGIT NINE' (U+0039)) rather than superficially similar Unicode symbols.\n* Use '.' (Unicode 'FULL STOP' (U+002E)) rather than ',' to indicate a decimal point. Avoid using these symbols as a readability separator._






This slot occurs 15925805 times.


URI: [sdos:value](https://schema.org/value)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Kwgos#S2Cell](../classes/Kwgos#S2Cell.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosNumber](../classes/SdosNumber.md)&nbsp;or&nbsp;<br />[SdosStructuredValue](../classes/SdosStructuredValue.md)&nbsp;or&nbsp;<br />[SdosBoolean](../classes/SdosBoolean.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md)







## LinkML Source

<details>

```yaml
name: sdos_value
description: The value of a [[QuantitativeValue]] (including [[Observation]]) or property
  value node.\n\n* For [[QuantitativeValue]] and [[MonetaryAmount]], the recommended
  type for values is 'Number'.\n* For [[PropertyValue]], it can be 'Text', 'Number',
  'Boolean', or 'StructuredValue'.\n* Use values from 0123456789 (Unicode 'DIGIT ZERO'
  (U+0030) to 'DIGIT NINE' (U+0039)) rather than superficially similar Unicode symbols.\n*
  Use '.' (Unicode 'FULL STOP' (U+002E)) rather than ',' to indicate a decimal point.
  Avoid using these symbols as a readability separator.
title: value
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
contributors:
- https://schema.org/docs/collab/GoodRelationsTerms
slot_uri: sdos:value
domain_of:
- kwgos_#S2Cell
union_of:
- sdos_MonetaryAmount
- sdos_PropertyValue
- sdos_QuantitativeValue
range: Any
any_of:
- range: sdos_Number
- range: sdos_StructuredValue
- range: sdos_Boolean
- range: sdos_Text

```
</details>