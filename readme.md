# SNOMED CT Expression Constraint Language Parser

An Open Source Java library for parsing ECL, a SNOMED CT domain specific language.

## ANTLR4 Grammar
The official SNOMED International ABNF syntax definition for ECL has been converted to ANTLR4 in order to generate tooling support.
- [ECL ANTLR4 grammar file](parser-generation/ECL-ABNF-source.txt)
- [How to generate ANTLR4 grammar from ABNF](generate_antlr4_grammar.md)

## Capabilities
- Validate the syntax of ECL
- Convert valid ECL into Java objects for further processing
  - The object factory can be extended in order to have the ECL Java objects instantiated using your own classes.

## Example
For code examples see [unit tests](https://github.com/IHTSDO/snomed-ecl-parser/blob/develop/src/test/java/org/snomed/langauges/ecl/ECLQueryBuilderTest.java#L22).
