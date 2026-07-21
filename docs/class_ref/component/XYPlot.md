# XYPlot
- class_name XYPlot
- extends Container
- script "res://ui/8Way/XYPlot.gd"
- scene "res://ui/8Way/XYPlot.tscn"
- version 1.10.0





---
## Property Descriptions

### var panel
- var panel : Node = $PlotPanel

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var nub
- var nub : Node = $PlotPanelNub

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var x_label
- var x_label : Node = $XLabel

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var y_label
- var y_label : Node = $YLabel

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var update_timer
- var update_timer : Node = $"%UpdateTimer"

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var panel_type
- var panel_type : UNKNOWN_TYPE = PanelType.Full

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var always_max
- var always_max : bool = false

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var snap
- var snap : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var limit_angle
- var limit_angle : bool = false

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var normalize_display
- var normalize_display : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var left_quarter
- var left_quarter : bool = false

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var bottom_half
- var bottom_half : bool = false

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var min_length
- var min_length : float = 0.0

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var limit_range_degrees
- var limit_range_degrees : float = 90.0

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var limit_center_degrees
- var limit_center_degrees : float = 0.0

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var limit_symmetrical
- var limit_symmetrical : bool = false

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var snap_angles
- var snap_angles : int = 8

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var snap_align_to_limit_center
- var snap_align_to_limit_center : bool = true

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var snap_radius
- var snap_radius : float = 0.0

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var default_value
- var default_value : Vector2 = Vector2(0, 0)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var plot_panel_size
- var plot_panel_size : Vector2 = Vector2(50, 50)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var plot_panel_padding
- var plot_panel_padding : Vector2 = Vector2(0, 0)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var mouse_over
- var mouse_over : bool = false

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var mouse_clicked
- var mouse_clicked : bool = false

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var buffer_changed
- var buffer_changed : bool = false

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var buffer_update
- var buffer_update : bool = false

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var was_game_paused
- var was_game_paused : bool = false

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var value_float
- var value_float : Vector2 = Vector2()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var last_di_pos
- var last_di_pos : UNKNOWN_TYPE = null

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var panel_radius
- var panel_radius : UNKNOWN_TYPE = plot_panel_size.x

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### var facing
- var facing : int = 1

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')




---
## Method Descriptions

### func _get_property_list
- func _get_property_list() -> UNKNOWN_TYPE

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func property_can_revert
- func property_can_revert(property:String) -> bool

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func property_get_revert
- func property_get_revert(property:String) -> UNKNOWN_TYPE

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_panel_type
- func set_panel_type(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_always_max
- func set_always_max(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_snap
- func set_snap(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_limit_angle
- func set_limit_angle(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_normalize_display
- func set_normalize_display(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_left_quarter
- func set_left_quarter(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_bottom_half
- func set_bottom_half(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_min_length
- func set_min_length(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_limit_range_degrees
- func set_limit_range_degrees(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_limit_center_degrees
- func set_limit_center_degrees(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_limit_symmetrical
- func set_limit_symmetrical(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_snap_angles
- func set_snap_angles(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_snap_align_to_limit_center
- func set_snap_align_to_limit_center(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_snap_radius
- func set_snap_radius(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_default_value
- func set_default_value(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _ready
- func _ready()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _process
- func _process(_delta)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func update
- func update()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _rect_for
- func _rect_for(child) -> Rect2

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _notification
- func _notification(what)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _on_update_timer_timeout
- func _on_update_timer_timeout()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _on_plot_mouse_entered
- func _on_plot_mouse_entered()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _on_plot_mouse_exited
- func _on_plot_mouse_exited()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_update_speed
- func get_update_speed() -> UNKNOWN_TYPE

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func _on_plot_mouse_input_event
- func _on_plot_mouse_input_event(event:InputEventMouseButton)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func midpoint
- func midpoint() -> Vector2

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func update_value
- func update_value(p=null, set_buffer_update:bool=true, ignore_snap:bool=false)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_panel_size
- func get_panel_size() -> UNKNOWN_TYPE

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_panel_padding
- func get_panel_padding() -> UNKNOWN_TYPE

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_flash
- func set_flash(on)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func reset
- func reset()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_facing
- func set_facing(val)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_label
- func set_label(text)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_limit_vec
- func get_limit_vec() -> UNKNOWN_TYPE

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_limit_center
- func get_limit_center() -> get_limit_vec

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_limit_range
- func get_limit_range() -> deg2rad

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_default_value
- func get_default_value() -> UNKNOWN_TYPE

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_data
- func get_data() -> as_percentage_int_vec

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_value_float
- func set_value_float(value)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func as_percentage_int_vec
- func as_percentage_int_vec(vec2:Vector2) -> Dictionary

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func get_value_float
- func get_value_float() -> UNKNOWN_TYPE

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### func set_last_di
- func set_last_di(di)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')




---
## Constant Descriptions

### const PROPERTY_DEFAULTS
- const PROPERTY_DEFAULTS : Dictionary = {

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const TOP_LABEL_SIZE
- const TOP_LABEL_SIZE : int = 11

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const BOTTOM_LABEL_SIZE
- const BOTTOM_LABEL_SIZE : int = 11

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const LABEL_NEGATIVE_PADDING
- const LABEL_NEGATIVE_PADDING : int = 3

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const PLOT_PANEL_BASE_PADDING
- const PLOT_PANEL_BASE_PADDING : Vector2 = Vector2(10, TOP_LABEL_SIZE+BOTTOM_LABEL_SIZE-(LABEL_NEGATIVE_PADDING*2))

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const FULL_CIRCLE_SIZE
- const FULL_CIRCLE_SIZE : Vector2 = Vector2(50, 50)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const HALF_CIRCLE_SIZE
- const HALF_CIRCLE_SIZE : Vector2 = Vector2(80, 40)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const QUARTER_CIRCLE_SIZE
- const QUARTER_CIRCLE_SIZE : Vector2 = Vector2(45, 45)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const FULL_CIRCLE_PADDING
- const FULL_CIRCLE_PADDING : Vector2 = Vector2(0, 0)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const HALF_CIRCLE_PADDING
- const HALF_CIRCLE_PADDING : Vector2 = Vector2(0, 5)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const QUARTER_CIRCLE_PADDING
- const QUARTER_CIRCLE_PADDING : Vector2 = Vector2(2.5, 2.5)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const PERCENT_MAX
- const PERCENT_MAX : int = 100

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### const SNAP_AMOUNT
- const SNAP_AMOUNT : float = 0.1

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')




---
## Signal Descriptions

### signal data_changed
- signal data_changed()

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')



### signal pos_data_changed
- signal pos_data_changed(pos, change)

[](https://hustledocs.trimaydev.com/docs/missing-description.md ':include')




