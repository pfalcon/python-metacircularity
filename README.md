Python Meta-circularity Story
=============================

This project surveys and catalogues tools related to meta-circularity in
relation to the Python programming language. Meta-circularity is considered
in a very wide sense, as tools written in Python dealing with processing
of the Python language itself. This ranges from meta-circular evaluators
(interpreters) to multi-level and multi-stage compilers. The focus is on
the simple, reusable tools which can be combined to implement arbitrary
complex and advanced processing.

Tokenizers
----------

Also known as lexical analyzers.

* Python standard library includes [tokenize](https://docs.python.org/3/library/tokenize.html)
  module.

Parsers
-------

Parsing to AST (Abstract Syntax Tree) and CST (Concrete Syntax Tree).

* Python stdlib allows to parse Python source (as string) to AST using
  `ast.parse()`.

Compilers
---------

* Python has a builtin function to compile Python source or AST to bytecode:
  `compile()`.


---
This list is compiled and maintained by Paul Sokolovsky, and released under
[Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).
