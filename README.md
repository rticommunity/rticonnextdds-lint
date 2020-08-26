# RTI Connext DDS Lint

This repository contains a set of configuration rules and scripts to apply RTI
coding style standards using tools like clang-format, clang-tidy, and
markdownlint.

## clang-format

`.clang-format` defines a set of formatting rules to format C and C++ source
and header files using [clang-format](https://https://clang.llvm.org/docs/ClangFormat.html).

The rules we define require clang-format version 9 or greater.

## clang-tidy

`.clang-tidy` defines a set of naming rules for types and identifiers to apply
the RTI coding style standards using [clang-tidy](https://clang.llvm.org/extra/clang-tidy/).

## markdownlint

`.mdl.rb` and `.markdownlint.json` define a set of rules to format Markdown
files according to the RTI coding style. These files can be used with different
utilities, such as this [Markdown Lint Tool](https://github.com/markdownlint/markdownlint)
and this [Node.js style checker for Markdown/CommonMark](https://github.com/DavidAnson/markdownlint).
