# Summary

Tree-sitter is a parser generator tool and an incremental parsing library. It can build a concrete syntax tree for a source
file and efficiently update the syntax tree as the source file is edited. Tree-sitter aims to be:

General enough to parse any programming language
Fast enough to parse on every keystroke in a text editor
Robust enough to provide useful results even in the presence of syntax errors
Dependency-free so that the runtime library (which is written in pure C) can be embedded in any application

[Introduction](./index.md)

# User Guide

- [Using Parsers](./using-parsers/index.md)
  - [Getting Started](./using-parsers/1-getting-started.md)
  - [Basic Parsing](./using-parsers/2-basic-parsing.md)
  - [Advanced Parsing](./using-parsers/3-advanced-parsing.md)
  - [Walking Trees](./using-parsers/4-walking-trees.md)
  - [Queries](./using-parsers/queries/index.md)
    - [Basic Syntax](./using-parsers/queries/1-syntax.md)
    - [Operators](./using-parsers/queries/2-operators.md)
    - [Predicates and Directives](./using-parsers/queries/3-predicates-and-directives.md)
    - [API](./using-parsers/queries/4-api.md)
  - [Static Node Types](./using-parsers/6-static-node-types.md)
- [Creating Parsers](./creating-parsers/index.md)
  - [Getting Started](./creating-parsers/1-getting-started.md)
  - [The Grammar DSL](./creating-parsers/2-the-grammar-dsl.md)
  - [Writing the Grammar](./creating-parsers/3-writing-the-grammar.md)
  - [External Scanners](./creating-parsers/4-external-scanners.md)
  - [Writing Tests](./creating-parsers/5-writing-tests.md)
- [Syntax Highlighting](./3-syntax-highlighting.md)
- [Code Navigation](./4-code-navigation.md)
- [Implementation](./5-implementation.md)
- [Contributing](./6-contributing.md)
- [Playground](./7-playground.md)

# Reference Guide

- [Command Line Interface](./cli/index.md)
  - [Init Config](./cli/init-config.md)
  - [Init](./cli/init.md)
  - [Generate](./cli/generate.md)
  - [Build](./cli/build.md)
  - [Parse](./cli/parse.md)
  - [Test](./cli/test.md)
  - [Version](./cli/version.md)
  - [Fuzz](./cli/fuzz.md)
  - [Query](./cli/query.md)
  - [Highlight](./cli/highlight.md)
  - [Tags](./cli/tags.md)
  - [Playground](./cli/playground.md)
  - [Dump Languages](./cli/dump-languages.md)
  - [Complete](./cli/complete.md)