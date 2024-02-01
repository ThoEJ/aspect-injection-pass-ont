# aspect-injection-pass-ont
Extension of the [Standard-PASS-Ontology](https://github.com/I2PM/Standard-PASS-Ontology) aiming to support aspect-oriented modeling with the Parallel Activity Specification Schema (PASS).

It specifies additional concepts needed for enriching standard PASS models with aspects - groups of advice process models whose behavior is later injected into core PASS process models according to pointcut definitions associated with the individual advice models.

Version History:

Version 0.5.2 (11.01.2024):
 - Adjusted the aip:joinPointType data type so that the listed options conform to the updated injection points of the newest version of the interpreter specification.
   
Version 0.5.1 (02.11.2023):
 - Added comments to all new classes, object properties, data properties, and data types.

Version 0.5.0 (27.10.2023):
 - Initial specification completed (all concepts needed for defining basic advice process models were added).
