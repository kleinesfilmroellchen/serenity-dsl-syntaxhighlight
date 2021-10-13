# serenity-dsl-syntaxhighlight – Syntax highlighting for SerenityOS' DSLs

Syntax highlighting for SerenityOS' Domain Specific Languages:

* `.ipc`: Endpoint specification for the Inter Process Communication protocol.
* `.gml`: Graphical Markup Language for creating SerenityOS GUI application layouts.
* `.sh`: SerenityOS Shell scripting language.

## Features

Provides TextMate Grammar-based syntax highlighting for the IPC, Shell and GML languages. Syntax highlighting is mostly compliant with SerenityOS' own syntax highlighters (in the case of GML) and code generators (in the case of IPC).

### GML syntax highlighting
![](./img/gml-highlight.png)
### IPC syntax highlighting
![](./img/ipc-highlight.png)

### Shell syntax highlighting
![](./img/shell-highlight.png)

## Known Issues

GML uses the .gml extension, which is also used for the GameMaker language. You may have to set the language for each file manually.

Shell uses the .sh extension, which is already in use for normal shells. You may have to set the language for each file manually.
