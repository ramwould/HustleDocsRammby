# BaseObj
- class_name BaseObj
- extends Node2D
- script "res://obj/BaseObj.gd"
- scene "res://obj/BaseObj.tscn"
- version 1.10.0

Class containing functionality that both [``Fighter``](class_ref/Fighter) and [``BaseProjectile``](class_ref/BaseProjectile) use.\n\n_**Note:** This class is missing functionality that is added by [``Fighter``](class_ref/Fighter) and [``BaseProjectile``](class_ref/BaseProjectile).  Despite its name, all game objects that are not Fighters should extend [``BaseProjectile``](class_ref/BaseProjectile), not BaseObj directly._



---
## Property Descriptions

### var id
- var id : int = 1

The id of the object. Decides which player owns what.

id = 1: Player 1
id = 2: Player 2



### var dummy
- var dummy : bool = false

{{ Missing Description }}



### var _c_MovementAttributes
- var _c_MovementAttributes : int = 0

{{ Missing Description }}



### var gravity
- var gravity : String = "0.8"

The speed in which this object falls while airborne

Only takes effect while in a state with [`apply_grav`](class_ref/ObjectState.md?id=var-apply_grav) on.



### var ground_friction
- var ground_friction : String = "2.5"

The amount of speed this object lose per tick while grounded, scaled by how close it is to max speed. (e.g. while at half of max speed, half of this variables value takes effect)

Only takes effect while in a state with [`apply_fric`](class_ref/ObjectState.md?id=var-apply_fric) on.



### var air_friction
- var air_friction : String = "0.2"

The amount of speed this object lose per tick while aerial, scaled by how close it is to max speed. (e.g. while at half of max speed, half of this variables value takes effect)

Only takes effect while in a state with [`apply_fric`](class_ref/ObjectState.md?id=var-apply_fric) on.



### var max_ground_speed
- var max_ground_speed : String = "15"

The maximum speed this object's x velocity will be clamped to while grounded



### var max_air_speed
- var max_air_speed : String = "10"

The maximum speed this object's x velocity will be clamped to while airborne



### var max_fall_speed
- var max_fall_speed : String = "15"

The maximum speed this object's y velocity will be clamped to while falling



### var damages_own_team
- var damages_own_team : bool = false

Allows this object to interact with other objects of the same id



### var has_projectile_parry_window
- var has_projectile_parry_window : bool = true

{{ Missing Description }}



### var always_parriable
- var always_parriable : bool = false

{{ Missing Description }}



### var throw_positions
- var throw_positions : Dictionary = {}

{{ Missing Description }}



### var collision_box
- var collision_box : Node = $CollisionBox

Direct reference to this object's collisionbox



### var hurtbox
- var hurtbox : Node = $Hurtbox

Direct reference to this object's hurtbox



### var particles
- var particles : Node = $"%Particles"

Direct reference to this object's "Particles" node



### var state_machine
- var state_machine : Node = $StateMachine

Direct reference to this object's "StateMachine" node



### var sprite
- var sprite : Node = $"%Sprite"

Direct reference to this object's sprite node



### var flip
- var flip : Node = $Flip

Direct reference to this object's "Flip" node



### var debug_label
- var debug_label : Node

{{ Missing Description }}



### var chara
- var chara : FGObject = FGObject.new()

{{ Missing Description }}



### var stage_width
- var stage_width : int = 0

Accounts for the current width of the stage. `stage_width` accounts for the width of the stage to the right. `-stage_width` accounts for the width of the stage to the left.



### var ceiling_height
- var ceiling_height : int = 0

{{ Missing Description }}



### var has_ceiling
- var has_ceiling : bool = false

Accounts for if the stage currently has a ceiling.



### var obj_name
- var obj_name : String

The name of this object stored in-game when created.

**Note:** Using `name` returns the same thing.



### var custom_hitspark
- var custom_hitspark : Node

{{ Missing Description }}



### var custom_hitspark_config
- var custom_hitspark_config : Node = null

{{ Missing Description }}



### var data
- var data : Dictionary

{{ Missing Description }}



### var obj_data
- var obj_data : Dictionary

{{ Missing Description }}



### var current_tick
- var current_tick : int = 0

{{ Missing Description }}



### var game_tick
- var game_tick : int = 0

{{ Missing Description }}



### var hitlag_ticks
- var hitlag_ticks : int = 0

{{ Missing Description }}



### var combo_count
- var combo_count : int = 0

{{ Missing Description }}



### var gravity_enabled
- var gravity_enabled : bool = true

{{ Missing Description }}



### var last_hit_frame
- var last_hit_frame : int = 0

{{ Missing Description }}



### var is_ghost
- var is_ghost : bool = false

Is `true` if this object was created in the predictions as an afterimage.



### var spawn_data
- var spawn_data : Dictionary = null

{{ Missing Description }}



### var disabled
- var disabled : bool = false

{{ Missing Description }}



### var creator_name
- var creator_name : String = null

{{ Missing Description }}



### var creator
- var creator : BaseObj = null

{{ Missing Description }}



### var can_update_sprite
- var can_update_sprite : bool = true

{{ Missing Description }}



### var fixed
- var fixed : FixedMath = FixedMath.new()

{{ Missing Description }}



### var native
- var native : NativeMethods = NativeMethods.new()

{{ Missing Description }}



### var state_interruptable
- var state_interruptable : bool = true

{{ Missing Description }}



### var state_hit_cancellable
- var state_hit_cancellable : bool = false

{{ Missing Description }}



### var invulnerable
- var invulnerable : bool = false

{{ Missing Description }}



### var grounded_attack_immune
- var grounded_attack_immune : bool = false

{{ Missing Description }}



### var aerial_attack_immune
- var aerial_attack_immune : bool = false

{{ Missing Description }}



### var use_platforms
- var use_platforms : bool = false

*Unused.*



### var last_object_hit
- var last_object_hit : String = ""

{{ Missing Description }}



### var default_hurtbox
- var default_hurtbox : Dictionary = {

{{ Missing Description }}



### var projectile_invulnerable
- var projectile_invulnerable : bool = false

{{ Missing Description }}



### var throw_invulnerable
- var throw_invulnerable : bool = false

{{ Missing Description }}



### var roll_projectile_invulnerable
- var roll_projectile_invulnerable : bool = false

{{ Missing Description }}



### var state_variables
- var state_variables : Array = ["id", "roll_projectile_invulnerable", "grounded_attack_immune", "game_tick", "match_seed", "aerial_attack_immune", "last_object_hit", "can_update_sprite", "last_hit_frame", "damages_own_team", "ceiling_height", "has_ceiling", "has_projectile_parry_window", "always_parriable", "use_platforms", "gravity", "ground_friction", "air_friction", "max_ground_speed", "max_air_speed", "max_fall_speed", "projectile_invulnerable", "gravity_enabled", "default_hurtbox", "throw_invulnerable", "creator_name", "name", "obj_name", "stage_width", "hitlag_ticks", "combo_count", "invulnerable", "current_tick", "disabled", "state_interruptable", "state_hit_cancellable"]

{{ Missing Description }}



### var hitboxes
- var hitboxes : Array = []

{{ Missing Description }}



### var previous_state
- var previous_state : String = ""

{{ Missing Description }}



### var fighter_owner
- var fighter_owner : Fighter

{{ Missing Description }}



### var initialized
- var initialized : bool = false

{{ Missing Description }}



### var rng
- var rng : BetterRng = BetterRng.new()

{{ Missing Description }}



### var objs_map
- var objs_map : Dictionary = {

A list of all objects spawned during a game. Starts off only containing the fighter objects as 'P1' and 'P2', then every other object as '3', '4', etc.



### var sounds
- var sounds : Dictionary = {

{{ Missing Description }}



### var logic_rng
- var logic_rng : BetterRng

{{ Missing Description }}



### var logic_rng_static
- var logic_rng_static : BetterRng

{{ Missing Description }}



### var logic_rng_seed
- var logic_rng_seed : int = 0

{{ Missing Description }}



### var logic_rng_static_seed
- var logic_rng_static_seed : int = 0

{{ Missing Description }}



### var hooks
- var hooks : ObjHooks.gd = null

{{ Missing Description }}



### var _init_hook_fired
- var _init_hook_fired : bool = false

{{ Missing Description }}




---
## Method Descriptions

### func _enter_tree
- func _enter_tree()

{{ Missing Description }}



### func get_p1
- func get_p1() -> CALLS:obj_from_name

Returns the [Fighter](class_ref/Fighter) object with an id of 1



### func get_p2
- func get_p2() -> CALLS:obj_from_name

Returns the [Fighter](class_ref/Fighter) object with an id of 2



### func _ready
- func _ready()

{{ Missing Description }}



### func global_hitlag
- func global_hitlag(amount, force:bool=false)

{{ Missing Description }}



### func play_sound
- func play_sound(sound_name)

Plays the sound from [sounds](#var-sounds) with a matching `sound_name`. Does nothing if that sound does not exist.

**Note:** Add AudioStreamPlayer or AudioStreamPlayer2D child nodes to the object's "Sounds" node to populate the list with each node's name.



### func stop_sound
- func stop_sound(sound_name)

Stops the sound from [sounds](#var-sounds) with a matching `sound_name` from playing. 



### func refresh_hitboxes
- func refresh_hitboxes()

{{ Missing Description }}



### func setup_hitbox_names
- func setup_hitbox_names()

{{ Missing Description }}



### func _on_state_exited
- func _on_state_exited(state)

{{ Missing Description }}



### func on_got_push_blocked
- func on_got_push_blocked()

{{ Missing Description }}



### func get_owner
- func get_owner() -> Fighter

{{ Missing Description }}



### func current_state
- func current_state() -> ObjectState

Gets the object's current state.



### func is_otg
- func is_otg() -> bool

Checks if the object's current state is "Knockdown" or "HardKnockdown".



### func init
- func init(pos=null)

{{ Missing Description }}



### func _fire_init_hook
- func _fire_init_hook()

{{ Missing Description }}



### func reset_hurtbox
- func reset_hurtbox()

{{ Missing Description }}



### func rumble
- func rumble(amount:float, ticks:int)

{{ Missing Description }}



### func set_rumble
- func set_rumble(amount)

{{ Missing Description }}



### func change_state
- func change_state(state_name, state_data=null, enter:bool=true, exit:bool=true)

{{ Missing Description }}



### func obj_from_name
- func obj_from_name(name) -> BaseObj

{{ Missing Description }}



### func _on_hit_something
- func _on_hit_something(obj, hitbox)

{{ Missing Description }}



### func hit_fighter_last
- func hit_fighter_last() -> bool

{{ Missing Description }}



### func can_be_thrown
- func can_be_thrown() -> bool

{{ Missing Description }}



### func _copy_state_variables_to
- func _copy_state_variables_to(o:BaseObj)

{{ Missing Description }}



### func copy_to
- func copy_to(o:BaseObj)

{{ Missing Description }}



### func get_frames
- func get_frames() -> Dictionary

{{ Missing Description }}



### func stop_particles
- func stop_particles()

{{ Missing Description }}



### func get_hitbox_x_dir
- func get_hitbox_x_dir(hitbox) -> fixed

{{ Missing Description }}



### func get_current_sprite_frame
- func get_current_sprite_frame() -> Texture

{{ Missing Description }}



### func get_current_sprite_frame_path
- func get_current_sprite_frame_path() -> String

{{ Missing Description }}



### func get_current_sprite_frame_number
- func get_current_sprite_frame_number() -> int

{{ Missing Description }}



### func turn_around
- func turn_around()

Flips the object's facing. Shorthand for `set_facing(get_facing_int() * -1)`



### func update_data
- func update_data()

{{ Missing Description }}



### func obj_local_pos
- func obj_local_pos(obj:BaseObj) -> Dictionary

{{ Missing Description }}



### func obj_local_center
- func obj_local_center(obj:BaseObj) -> Dictionary

{{ Missing Description }}



### func get_global_center
- func get_global_center()

*Unused. Doesn't do anything.*



### func get_facing
- func get_facing() -> String

Gets the current facing of the object and returns it as a string `"Left"` or `"Right"` respectively.



### func get_opponent
- func get_opponent() -> Fighter

Gets the [Fighter](class_ref/Fighter) object with the opposing id of this object.


### func get_fighter
- func get_fighter() -> Fighter

Gets the [Fighter](class_ref/Fighter) object with the same id as this object.



### func hash_static_rng
- func hash_static_rng()

{{ Missing Description }}



### func hash_rng
- func hash_rng()

{{ Missing Description }}



### func obj_distance
- func obj_distance(obj) -> fixed

{{ Missing Description }}



### func spawn_object
- func spawn_object(projectile:PackedScene, pos_x:int, pos_y:int, relative:bool=true, data=null, local:bool=true) -> BaseObj

Spawns an object

- `projectile`: What you're spawning
- `pos_x`: `y` position you wish to spawn it
- `pos_y`: `x` position you wish to spawn it
  - **NOTE**: This is affected by `relative` and `local`
- `relative`: If the positions you inputted are affected by the direction the player is currently facing.
  - **NOTE**: Multiplies the value by `get_facing_int()`
- `data`: Data you wish to pass to the projectile.
  - **NOTE**: This needs to be coded in if you wish to use this, but it is commonly used to pass velocities to the projectile.
- `local`: Whether or not the position is relative to the fighter or to their global position. While relative to fighter (0,0) is the bottom center of the fighter. While relative to global position (0,0) the bottom center of the stage.



### func get_hurtbox_center
- func get_hurtbox_center() -> Dictionary

{{ Missing Description }}



### func get_hurtbox_center_float
- func get_hurtbox_center_float() -> Vector2

{{ Missing Description }}



### func hurtbox_pos_relative
- func hurtbox_pos_relative() -> Dictionary

{{ Missing Description }}



### func hurtbox_pos_float
- func hurtbox_pos_float() -> Vector2

{{ Missing Description }}



### func hurtbox_pos_relative_float
- func hurtbox_pos_relative_float() -> Vector2

{{ Missing Description }}



### func start_throw_invulnerability
- func start_throw_invulnerability()

{{ Missing Description }}



### func end_throw_invulnerability
- func end_throw_invulnerability()

{{ Missing Description }}



### func start_projectile_invulnerability
- func start_projectile_invulnerability()

{{ Missing Description }}



### func end_projectile_invulnerability
- func end_projectile_invulnerability()

{{ Missing Description }}



### func start_roll_projectile_invulnerability
- func start_roll_projectile_invulnerability()

{{ Missing Description }}



### func end_roll_projectile_invulnerability
- func end_roll_projectile_invulnerability()

{{ Missing Description }}



### func start_aerial_attack_invulnerability
- func start_aerial_attack_invulnerability()

{{ Missing Description }}



### func end_aerial_attack_invulnerability
- func end_aerial_attack_invulnerability()

{{ Missing Description }}



### func start_grounded_attack_invulnerability
- func start_grounded_attack_invulnerability()

{{ Missing Description }}



### func end_grounded_attack_invulnerability
- func end_grounded_attack_invulnerability()

{{ Missing Description }}



### func start_invulnerability
- func start_invulnerability()

{{ Missing Description }}



### func end_invulnerability
- func end_invulnerability()

{{ Missing Description }}



### func spawn_particle_effect
- func spawn_particle_effect(particle_effect:PackedScene, pos:Vector2, dir:Vector2=Vector2.RIGHT)

{{ Missing Description }}



### func spawn_particle_effect_relative
- func spawn_particle_effect_relative(particle_effect:PackedScene, pos:Vector2=Vector2(), dir:Vector2=Vector2.RIGHT)

{{ Missing Description }}



### func _spawn_particle_effect
- func _spawn_particle_effect(particle_effect:PackedScene, pos:Vector2, dir:Vector2=Vector2.RIGHT) -> ParticleEffect

{{ Missing Description }}



### func get_camera
- func get_camera() -> GoodCamera

{{ Missing Description }}



### func grab_camera_focus
- func grab_camera_focus()

Centers the camera onto the object that called it. Use [release_camera_focus](#func-release_camera_focus) to reset the camera back to normal.



### func release_camera_focus
- func release_camera_focus()

Resets camera focus after [grab_camera_focus](#func-grab_camera_focus) was called.



### func screen_bump
- func screen_bump(dir:Vector2=Vector2(), screenshake_amount:float=2.0, screenshake_time:float=0.1)

{{ Missing Description }}



### func update_collision_boxes
- func update_collision_boxes()

{{ Missing Description }}



### func set_facing
- func set_facing(facing:int)

Sets the object's facing direction to `facing`. If `facing` is not 1 or -1 then it will by default set the facing to `1`.



### func fixed_dot
- func fixed_dot(x1:String, y1:String, x2:String, y2:String) -> String

{{ Missing Description }}



### func fixed_inverse_lerp
- func fixed_inverse_lerp(a:String, b:String, v:String) -> String

{{ Missing Description }}



### func fixed_map
- func fixed_map(i_min:String, i_max:String, o_min:String, o_max:String, v:String) -> fixed

{{ Missing Description }}



### func set_vel
- func set_vel(x, y)

Sets the velocity to `x` and `y`, which both must either be integers or strings.



### func get_vel
- func get_vel() -> Dictionary

Returns the velocity of the object as a dictionary of 2 integers `x` and `y`.

It is advised to call [`update_data`](#func-update_data) before `get_vel()` if the object's velocity was changed on the same frame before `get_vel()` is called.



### func get_facing_int
- func get_facing_int() -> int

Gets the object's current facing as an integer. 1 is facing right, -1 is facing left.



### func detect
- func detect(obj)

{{ Missing Description }}



### func check_params
- func check_params(x, y)

{{ Missing Description }}



### func set_x
- func set_x(x:int)

Sets the object's x position relative to the stage. For setting both x and y, see [`set_pos`](#func-set_pos).



### func set_y
- func set_y(y:int)

Sets the object's y position relative to the stage. For setting both x and y, see [`set_pos`](#func-set_pos).



### func get_center_position_float
- func get_center_position_float() -> Vector2

{{ Missing Description }}



### func set_pos
- func set_pos(x, y)

Sets an object's position relative to the stage. For setting position relative to the objects current position, see [`move_directly`](#func-move_directly)



### func set_snap_to_ground
- func set_snap_to_ground(snap:bool)

{{ Missing Description }}



### func get_snap_to_ground
- func get_snap_to_ground() -> UNKNOWN_TYPE

{{ Missing Description }}



### func get_data
- func get_data() -> UNKNOWN_TYPE

{{ Missing Description }}



### func get_active_hitboxes
- func get_active_hitboxes() -> Array

{{ Missing Description }}



### func sort_hitboxes
- func sort_hitboxes(a, b) -> bool

{{ Missing Description }}



### func apply_force
- func apply_force(x, y)

{{ Missing Description }}



### func apply_force_relative
- func apply_force_relative(x, y)

{{ Missing Description }}



### func apply_forces
- func apply_forces()

{{ Missing Description }}



### func apply_forces_no_limit
- func apply_forces_no_limit()

{{ Missing Description }}



### func set_gravity_modifier
- func set_gravity_modifier(modifier:String)

{{ Missing Description }}



### func apply_grav_custom
- func apply_grav_custom(grav:String, fall_speed:String)

{{ Missing Description }}



### func apply_grav
- func apply_grav()

{{ Missing Description }}



### func apply_fric
- func apply_fric()

{{ Missing Description }}



### func apply_x_fric
- func apply_x_fric(fric)

{{ Missing Description }}



### func apply_y_fric
- func apply_y_fric(fric)

{{ Missing Description }}



### func limit_speed
- func limit_speed(limit)

{{ Missing Description }}



### func limit_x_speed
- func limit_x_speed(limit)

{{ Missing Description }}



### func limit_y_speed
- func limit_y_speed(limit)

{{ Missing Description }}



### func get_object_dir
- func get_object_dir(obj) -> CALLS:get_facing_int

Returns  1 or -1 if [`obj`](#class_ref/BaseObj.md) is to the right or left of this object respectively.



### func get_object_dir_vec
- func get_object_dir_vec(obj) -> Dictionary

{{ Missing Description }}



### func move_directly
- func move_directly(x, y)

Sets an object's position relative to it's current position. For setting position relative to the stage, see [set_pos](#func-set_pos)



### func move_directly_relative
- func move_directly_relative(x, y)

Same as [move_directly](#func-move_directly), except relative to the object's facing, positive will always be forward, negative will always be backward



### func _process
- func _process(delta)

{{ Missing Description }}



### func debug_text
- func debug_text()

{{ Missing Description }}



### func debug_info
- func debug_info(data)

{{ Missing Description }}



### func debug_dict
- func debug_dict(text, dict) -> String

{{ Missing Description }}



### func reset_momentum
- func reset_momentum()

{{ Missing Description }}



### func is_grounded
- func is_grounded() -> bool

Returns `true` if the object is touching the floor.



### func set_grounded
- func set_grounded(on)

{{ Missing Description }}



### func add_pushback
- func add_pushback(pushback)

{{ Missing Description }}



### func reset_pushback
- func reset_pushback()

{{ Missing Description }}



### func update_grounded
- func update_grounded()

{{ Missing Description }}



### func on_got_parried
- func on_got_parried()

{{ Missing Description }}



### func get_state
- func get_state(state_name) -> ObjectState

{{ Missing Description }}



### func on_got_blocked
- func on_got_blocked()

{{ Missing Description }}



### func on_got_parried_by
- func on_got_parried_by(who)

{{ Missing Description }}



### func on_got_blocked_by
- func on_got_blocked_by(who)

{{ Missing Description }}



### func deactivate_current_hitbox
- func deactivate_current_hitbox()

{{ Missing Description }}



### func deactivate_hitboxes
- func deactivate_hitboxes()

{{ Missing Description }}



### func hit_by
- func hit_by(hitbox:Hitbox)

{{ Missing Description }}



### func get_pos
- func get_pos() -> Dictionary

Returns the position of the object as a dictionary of 2 integers `x` and `y`relative to the stage.

It is advised to call [`update_data`](#func-update_data) before `get_pos()` if the object was moved on the same frame before `get_pos()` is called.



### func xy_to_dir
- func xy_to_dir(x, y, mul:fixed="1.0", div:fixed="100.0") -> Dictionary

Takes 2 integers `x` and `y` and 2 [`fixed number strings`](class_ref/FixedMath.md?id=FixedMath), returns a Dictionary of each divided by 4th input and multiplied by 3rd input in that order.

This is primarily useful with XYPlot data which give you two integers between -100 and +100, thus the default for `div` is "100" so that you can scale down XYPlot data this function to any max value you want using only the `mul` input.  For example:
```gdscript
extends CharacterState

func _frame_5():
    var force = host.xy_to_dir(data.x, data.y, "7.5")
    host.apply_force(force.x, force.y)
```



### func on_state_started
- func on_state_started(state)

{{ Missing Description }}



### func on_state_ended
- func on_state_ended(state)

{{ Missing Description }}



### func get_collision_box
- func get_collision_box() -> Dictionary

{{ Missing Description }}



### func get_pos_visual
- func get_pos_visual() -> Vector2

{{ Missing Description }}



### func distance_to
- func distance_to(object:BaseObj) -> fixed

{{ Missing Description }}



### func tick
- func tick()

{{ Missing Description }}



### func on_hit_ceiling
- func on_hit_ceiling()

{{ Missing Description }}



### func state_tick
- func state_tick()

{{ Missing Description }}



### func get_states
- func get_states() -> Array

{{ Missing Description }}



### func get_limb_data
- func get_limb_data() -> Dictionary

{{ Missing Description }}



### func get_current_limb_sprite_node
- func get_current_limb_sprite_node() -> Node

{{ Missing Description }}



### func get_current_limb_sprite_texture
- func get_current_limb_sprite_texture() -> Texture

{{ Missing Description }}



### func get_current_limb_sprite_node_for
- func get_current_limb_sprite_node_for(_limb_name:String) -> CALLS:get_current_limb_sprite_node

{{ Missing Description }}



### func get_current_limb_sprite_texture_for
- func get_current_limb_sprite_texture_for(limb_name:String) -> Texture

{{ Missing Description }}



### func get_limb_entry
- func get_limb_entry(limb_name:String) -> UNKNOWN_TYPE

{{ Missing Description }}



### func is_limb_absent_on_current_sprite
- func is_limb_absent_on_current_sprite(limb_name:String) -> bool

{{ Missing Description }}



### func get_limb_pos
- func get_limb_pos(limb_name:String) -> Vector2

{{ Missing Description }}



### func get_limb_dir
- func get_limb_dir(limb_name:String) -> Vector2

{{ Missing Description }}



### func get_limb_local_pos
- func get_limb_local_pos(limb_name:String) -> Vector2

{{ Missing Description }}



### func get_limb_sprite_parent_dir
- func get_limb_sprite_parent_dir(limb_name:String) -> UNKNOWN_TYPE

{{ Missing Description }}



### func get_limb_local_dir
- func get_limb_local_dir(limb_name:String) -> UNKNOWN_TYPE

{{ Missing Description }}



### func has_limb_entry_on_current_sprite
- func has_limb_entry_on_current_sprite(limb_name:String) -> bool

{{ Missing Description }}



### func get_limb_pixel_pos
- func get_limb_pixel_pos(limb_name:String) -> Vector2

{{ Missing Description }}



### func get_limb_pixel_dir
- func get_limb_pixel_dir(limb_name:String) -> Vector2

{{ Missing Description }}



### func is_limb_flipped
- func is_limb_flipped(limb_name:String) -> bool

{{ Missing Description }}



### func _limb_pixel_to_world
- func _limb_pixel_to_world(sprite_node:Node2D, tex:Texture, pixel_pos:Vector2) -> Vector2

{{ Missing Description }}



### func _limb_dir_to_world
- func _limb_dir_to_world(sprite_node:Node2D, dir:Vector2) -> Vector2

{{ Missing Description }}



### func fixed_deg_to_rad
- func fixed_deg_to_rad(n) -> fixed

{{ Missing Description }}



### func randi_
- func randi_() -> int

{{ Missing Description }}



### func randi_range
- func randi_range(a:int, b:int) -> int

{{ Missing Description }}



### func randi_percent
- func randi_percent(n:int) -> bool

{{ Missing Description }}



### func randi_choice
- func randi_choice(choices:Array) -> Variant

{{ Missing Description }}



### func randi_weighted_choice
- func randi_weighted_choice(choices:Array, weights:Array) -> Variant

{{ Missing Description }}



### func randi_static
- func randi_static() -> int

{{ Missing Description }}



### func randi_range_static
- func randi_range_static(a:int, b:int) -> int

{{ Missing Description }}



### func randi_percent_static
- func randi_percent_static(n:int) -> bool

{{ Missing Description }}



### func randi_choice_static
- func randi_choice_static(choices:Array) -> Variant

{{ Missing Description }}



### func randi_weighted_choice_static
- func randi_weighted_choice_static(choices:Array, weights:Array) -> Variant

{{ Missing Description }}



### func should_hide_rng
- func should_hide_rng() -> bool

{{ Missing Description }}



### func tick_after
- func tick_after()

{{ Missing Description }}



### func previous_state
- func previous_state() -> ObjectState

Returns the object's previous state. Will return `null` if there isn't one.



### func normal_tick
- func normal_tick()

{{ Missing Description }}



### func get_knockback_force
- func get_knockback_force(hitbox) -> Dictionary

{{ Missing Description }}



### func compare
- func compare(obj)

{{ Missing Description }}



### func _draw
- func _draw()

{{ Missing Description }}




---
## Constant Descriptions

### const RUMBLE_MODIFIER
- const RUMBLE_MODIFIER : float = 4.0

{{ Missing Description }}



### const MAX_RUMBLE
- const MAX_RUMBLE : int = 10

{{ Missing Description }}



### const MIN_VELOCITY
- const MIN_VELOCITY : fixed = "0.0001"

{{ Missing Description }}




---
## Signal Descriptions

### signal object_spawned
- signal object_spawned(object)

{{ Missing Description }}



### signal particle_effect_spawned
- signal particle_effect_spawned(particle)

{{ Missing Description }}



### signal initialized
- signal initialized()

{{ Missing Description }}



### signal got_hit
- signal got_hit()

{{ Missing Description }}



### signal got_hit_by_fighter
- signal got_hit_by_fighter()

{{ Missing Description }}



### signal got_hit_by_projectile
- signal got_hit_by_projectile()

{{ Missing Description }}



### signal hitbox_refreshed
- signal hitbox_refreshed(hitbox)

{{ Missing Description }}



### signal global_hitlag
- signal global_hitlag(amount)

{{ Missing Description }}




