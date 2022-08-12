<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

# ESCCompiler

**Extends:** [Resource](../Resource)

## Description

Compiler of the ESC language

## Constants Descriptions

### COMMAND\_DIRECTORIES

```gdscript
const COMMAND_DIRECTORIES: String = "escoria/main/command_directories"
```

This must match ESCProjectSettingsManager.COMMAND_DIRECTORIES.
We do not reference it directly to avoid circular dependencies.

### COMMENT\_REGEX

```gdscript
const COMMENT_REGEX: String = "^\\s*#.*$"
```

A RegEx for comment lines
.*$'

### EMPTY\_REGEX

```gdscript
const EMPTY_REGEX: String = "^\\s*$"
```

A RegEx for empty lines

### INDENT\_REGEX

```gdscript
const INDENT_REGEX: String = "^(?<indent>\\s*)"
```

### INDENT\_REGEX\_GROUP

```gdscript
const INDENT_REGEX_GROUP: String = "indent"
```

A RegEx for finding out the indent of a line

## Method Descriptions

### load\_esc\_file

```gdscript
func load_esc_file(path: String) -> ESCScript
```

Load an ESC file from a file resource

### compile

```gdscript
func compile(lines: Array, path: String = "") -> ESCScript
```

Compiles an array of ESC script strings to an ESCScript