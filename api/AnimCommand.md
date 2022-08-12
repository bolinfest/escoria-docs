<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

# AnimCommand

**Extends:** [ESCBaseCommand](../ESCBaseCommand) < [Resource](../Resource)

## Description

`anim object name [reverse]`

Executes the animation specified in "name" on "object" without blocking.
The next command in the event will be executed immediately after the
animation is started.

**Parameters**

* *object*: Global ID of the object with the animation
* *name*: Name of the animation to play
* *reverse*: Plays the animation in reverse when true

@ESC

## Method Descriptions

### configure

```gdscript
func configure() -> ESCCommandArgumentDescriptor
```

Return the descriptor of the arguments of this command

### validate

```gdscript
func validate(arguments: Array)
```

Validate whether the given arguments match the command descriptor

### run

```gdscript
func run(command_params: Array) -> int
```

Run the command

### interrupt

```gdscript
func interrupt()
```

Function called when the command is interrupted.