Table of Contents
=================

Guide
-----

  1. [Introduction](0_Introduction.markdown)
  2. [Usage of basic components](2_Usage_of_basic_components.markdown)
  3. [Other node tree representations](3_Other_node_tree_representations.markdown)

Component documentation
-----------------------

  * [Name resolution](component/Name_resolution.markdown)
    * Name resolver options
    * Name resolution context
  * [Pretty printing](component/Pretty_printing.markdown)
    * Converting AST back to PHP code
    * Customizing formatting
    * Formatting-preserving code transformations
  * [AST builders](component/AST_builders.markdown)
    * Fluent builders for AST nodes
  * [Lexer](component/Lexer.markdown)
    * Lexer options
    * Token and file positions for nodes
    * Custom attributes
  * [Error handling](component/Error_handling.markdown)
    * Column information for errors
    * Error recovery (parsing of syntactically incorrect code)
  * [Constant expression evaluation](component/Constant_expression_evaluation.markdown)
    * Evaluating constant/property/etc initializers
    * Handling errors and unsupported expressions
  * [Performance](component/Performance.markdown)
    * Disabling XDebug
    * Reusing objects
    * Garbage collection impact
  * [Frequently asked questions](component/FAQ.markdown)
    * Parent and sibling references
