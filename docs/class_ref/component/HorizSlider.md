# HorizSlider
- extends VBoxContainer
- script "res://ui/8Way/HorizSlider.gd"
- scene "res://ui/8Way/HorizSlider.tscn"
- version 1.10.0





---
## Property Descriptions

### var default
- var default : Node = $Direction.value

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var centered
- var centered : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var _c_EnableThisToUseMinAndMaxValue
- var _c_EnableThisToUseMinAndMaxValue : int = 0

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var apply_top_node_range
- var apply_top_node_range : bool = false

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var _c_DisabledByDefaultForBackwardCompatibility
- var _c_DisabledByDefaultForBackwardCompatibility : int = 0

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var min_value
- var min_value : int = 0

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var max_value
- var max_value : int = 100

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var buffer_value_changed
- var buffer_value_changed : bool = false

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')




---
## Method Descriptions

### func _input
- func _input(event:InputEvent)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _ready
- func _ready()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func on_value_changed
- func on_value_changed(value)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _process
- func _process(_delta)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_value
- func get_value() -> int

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_data
- func get_data() -> Dictionary

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')




---
## Signal Descriptions

### signal data_changed
- signal data_changed()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')




