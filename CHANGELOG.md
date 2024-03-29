# Change Log

## 0.0.1

- Initial release

## 0.0.3

- Support endpoint attributes in IPC
- Fixes in the IPC syntax

## 0.1.0

- Support for formatting GML files with Serenity's own GML formatter.

## 0.1.1

- Fixed GML formatting behavior. A temporary file is used instead of saving the file in order to avoid formatting loops.
- Fixes to IPC and GML syntax highlighting mostly aimed at better compatibility with more themes.

## 0.2.0

- Add Web-Idl language support

## 0.2.1

- IDL: Fix an issue with Unions in dictionaries
- IDL: Fix ExtendedAttributes before optional arguments
- GML: Allow object lookups of arbitrary namespace depth

## 0.2.2

- IDL: Colour brace-pairs
- GML: Remove one trailing comma to reenable the highlighting

## 0.3.0

- Bytecode: Added a new highlighter for LibJS' Bytecode serialization format

## 0.3.1

- Bytecode: Account for more than 10 entries in Identifier- and String-Tables
- Bytecode: Don't require a newline to terminate Tables
- Bytecode: Account for merged block names as labels
