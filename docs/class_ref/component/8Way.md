# 8Way
- class_name 8Way
- extends Control
- script "res://ui/8Way/8Way.gd"
- scene "res://ui/8Way/8Way.tscn"
- version 1.10.0





---
## Property Descriptions

### var consider_facing
- var consider_facing : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var force_neutral_when_invisible
- var force_neutral_when_invisible : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var facing
- var facing : int = 1

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var pressed_button
- var pressed_button : Node = null

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var NW
- var NW : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var N
- var N : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var NE
- var NE : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var W
- var W : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var Neutral
- var Neutral : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var E
- var E : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var SW
- var SW : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var S
- var S : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var SE
- var SE : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')




---
## Method Descriptions

### func set_facing
- func set_facing(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_NW
- func set_NW(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_N
- func set_N(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_NE
- func set_NE(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_W
- func set_W(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_Neutral
- func set_Neutral(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_E
- func set_E(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_SW
- func set_SW(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_S
- func set_S(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_SE
- func set_SE(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_dir
- func set_dir(dir, force_absolute:bool=false)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_sensible_default
- func set_sensible_default(attempted_dir, emit_signal:bool=true)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_dir_from_data
- func set_dir_from_data(data)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_dir
- func get_dir() -> String

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_dir_name
- func get_dir_name() -> String

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_button
- func get_button(button_name) -> Node

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_buttons
- func get_buttons() -> Array

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_value
- func get_value(dir) -> get_vec_int

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_data
- func get_data() -> String

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_vec_int
- func get_vec_int(x:int, y:int) -> Dictionary

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func try_hide_section
- func try_hide_section(section)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func reverse_dir
- func reverse_dir(dir) -> String

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func dir_to_facing
- func dir_to_facing(dir) -> reverse_dir

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _on_button_pressed
- func _on_button_pressed(button)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _on_button_pressed_no_signal
- func _on_button_pressed_no_signal(button)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _ready
- func _ready()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func init
- func init()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _prepare
- func _prepare()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func try_hide_sections
- func try_hide_sections()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')




---
## Constant Descriptions

### const DIRS
- const DIRS : Array = ["Neutral", "E", "NE", "SE", "N", "S", "W", "NW", "SW"]

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const DIRS_LEFT
- const DIRS_LEFT : Array = ["Neutral", "W", "NW", "SW", "N", "S", "E", "NE", "SE"]

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')




---
## Signal Descriptions

### signal data_changed
- signal data_changed()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')




