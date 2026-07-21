# Fighter
- class_name Fighter
- extends BaseObj
- script "res://characters/BaseChar.gd"
- scene "res://characters/BaseChar.tscn"
- version 1.10.0





---
## Property Descriptions

### var MAX_HEALTH
- var MAX_HEALTH : int = 1500

{{ Missing Description }}



### var parry_combo_scaling
- var parry_combo_scaling : UNKNOWN_TYPE = PARRY_COMBO_SCALING

{{ Missing Description }}



### var burst_parry_combo_scaling
- var burst_parry_combo_scaling : UNKNOWN_TYPE = BURST_PARRY_COMBO_SCALING

{{ Missing Description }}



### var HOLD_RESTARTS
- var HOLD_RESTARTS : Array = [

{{ Missing Description }}



### var HOLD_FORCE_STATES
- var HOLD_FORCE_STATES : Dictionary = {

{{ Missing Description }}



### var _c_NEW_MODDED_CHARACTERS_IMPORTANT
- var _c_NEW_MODDED_CHARACTERS_IMPORTANT : int = 0

{{ Missing Description }}



### var _c_ENABLE_THIS_SETTING_IF_YOU_WANT_CONSISTENCY_WITH_THE_BASE_CAST
- var _c_ENABLE_THIS_SETTING_IF_YOU_WANT_CONSISTENCY_WITH_THE_BASE_CAST : int = 0

{{ Missing Description }}



### var enable_extra_aesthetic_hitstop
- var enable_extra_aesthetic_hitstop : bool = false

{{ Missing Description }}



### var _c_THANK_YOU
- var _c_THANK_YOU : int = 0

{{ Missing Description }}



### var num_air_movements
- var num_air_movements : int = 2

{{ Missing Description }}



### var lose_one_air_option_in_neutral
- var lose_one_air_option_in_neutral : bool = true

{{ Missing Description }}



### var use_air_option_bar
- var use_air_option_bar : bool = false

{{ Missing Description }}



### var air_option_bar_max
- var air_option_bar_max : int = 100

{{ Missing Description }}



### var air_option_bar
- var air_option_bar : int = 0

{{ Missing Description }}



### var air_option_bar_name
- var air_option_bar_name : String = "Air Options"

{{ Missing Description }}



### var you_label
- var you_label : Node = $YouLabel

{{ Missing Description }}



### var actionable_label
- var actionable_label : Node = $ActionableLabel

{{ Missing Description }}



### var quitter_label
- var quitter_label : Node = $"%QuitterLabel"

{{ Missing Description }}



### var velocity_label_container
- var velocity_label_container : Node = $VelocityLabelContainer

{{ Missing Description }}



### var grounded_indicator
- var grounded_indicator : Node = $GroundedIndicator

{{ Missing Description }}



### var block_frame_label
- var block_frame_label : Node = $BlockFrameLabel

{{ Missing Description }}



### var hit_frame_label
- var hit_frame_label : Node = $HitFrameLabel

{{ Missing Description }}



### var input_state
- var input_state : InputState = InputState.new()

{{ Missing Description }}



### var color
- var color : Color = Color.white

{{ Missing Description }}



### var style_extra_color_1
- var style_extra_color_1 : UNKNOWN_TYPE = extra_color_1

{{ Missing Description }}



### var style_extra_color_2
- var style_extra_color_2 : UNKNOWN_TYPE = extra_color_2

{{ Missing Description }}



### var damage_taken_modifier
- var damage_taken_modifier : fixed = "1.0"

{{ Missing Description }}



### var knockback_taken_modifier
- var knockback_taken_modifier : fixed = "1.0"

{{ Missing Description }}



### var di_modifier
- var di_modifier : fixed = "1.0"

{{ Missing Description }}



### var num_feints
- var num_feints : int = 2

{{ Missing Description }}



### var use_extra_color_1
- var use_extra_color_1 : bool = false

{{ Missing Description }}



### var extra_color_1
- var extra_color_1 : CALLS:Color = Color("ff00ff")

{{ Missing Description }}



### var use_extra_color_2
- var use_extra_color_2 : bool = false

{{ Missing Description }}



### var extra_color_2
- var extra_color_2 : CALLS:Color = Color("ff00ff")

{{ Missing Description }}



### var global_damage_modifier
- var global_damage_modifier : fixed = "1.0"

{{ Missing Description }}



### var global_hitstun_modifier
- var global_hitstun_modifier : fixed = "1.0"

{{ Missing Description }}



### var global_hitstop_modifier
- var global_hitstop_modifier : fixed = "1.0"

{{ Missing Description }}



### var min_di_scaling
- var min_di_scaling : fixed = "1.0"

{{ Missing Description }}



### var max_di_scaling
- var max_di_scaling : fixed = "6.0"

{{ Missing Description }}



### var di_combo_limit
- var di_combo_limit : int = 15

{{ Missing Description }}



### var ghost_blocked_melee_attack
- var ghost_blocked_melee_attack : int = -1

{{ Missing Description }}



### var ghost_got_hit
- var ghost_got_hit : bool = false

{{ Missing Description }}



### var opponent
- var opponent : UNKNOWN_TYPE

{{ Missing Description }}



### var actions
- var actions : int = 0

{{ Missing Description }}



### var visible_combo_count
- var visible_combo_count : int = 0

{{ Missing Description }}



### var buffered_global_hitlag
- var buffered_global_hitlag : int = 0

{{ Missing Description }}



### var queued_action
- var queued_action : UNKNOWN_TYPE = null

{{ Missing Description }}



### var queued_data
- var queued_data : UNKNOWN_TYPE = null

{{ Missing Description }}



### var queued_extra
- var queued_extra : UNKNOWN_TYPE = null

{{ Missing Description }}



### var buffered_input
- var buffered_input : Dictionary = {}

{{ Missing Description }}



### var last_input
- var last_input : Dictionary = {}

{{ Missing Description }}



### var previous_input
- var previous_input : Dictionary = {}

{{ Missing Description }}



### var use_buffer
- var use_buffer : bool = false

{{ Missing Description }}



### var hit_out_of_brace
- var hit_out_of_brace : bool = false

{{ Missing Description }}



### var braced_attack
- var braced_attack : bool = false

{{ Missing Description }}



### var brace_effect_applied_yet
- var brace_effect_applied_yet : bool = false

{{ Missing Description }}



### var dummy_interruptable
- var dummy_interruptable : bool = false

{{ Missing Description }}



### var game_over
- var game_over : bool = false

{{ Missing Description }}



### var forfeit
- var forfeit : bool = false

{{ Missing Description }}



### var will_forfeit
- var will_forfeit : bool = false

{{ Missing Description }}



### var applied_style
- var applied_style : UNKNOWN_TYPE = null

{{ Missing Description }}



### var is_color_active
- var is_color_active : bool = false

{{ Missing Description }}



### var is_aura_active
- var is_aura_active : bool = false

{{ Missing Description }}



### var is_style_active
- var is_style_active : UNKNOWN_TYPE = null

{{ Missing Description }}



### var touching_wall
- var touching_wall : bool = false

{{ Missing Description }}



### var was_my_turn
- var was_my_turn : bool = false

{{ Missing Description }}



### var touch_of_death
- var touch_of_death : bool = true

{{ Missing Description }}



### var ivy_effect
- var ivy_effect : bool = false

{{ Missing Description }}



### var ivy_effect_t
- var ivy_effect_t : float = 0.0

{{ Missing Description }}



### var colliding_with_opponent
- var colliding_with_opponent : bool = true

{{ Missing Description }}



### var air_movements_left
- var air_movements_left : int = 0

{{ Missing Description }}



### var action_cancels
- var action_cancels : Dictionary = {

{{ Missing Description }}



### var ghost_ready_tick
- var ghost_ready_tick : UNKNOWN_TYPE = null

{{ Missing Description }}



### var ghost_ready_set
- var ghost_ready_set : bool = false

{{ Missing Description }}



### var got_parried
- var got_parried : bool = false

{{ Missing Description }}



### var got_blocked
- var got_blocked : bool = false

{{ Missing Description }}



### var block_used_air_movement
- var block_used_air_movement : bool = false

{{ Missing Description }}



### var di_enabled
- var di_enabled : bool = true

{{ Missing Description }}



### var prorated_di
- var prorated_di : bool = true

{{ Missing Description }}



### var combo_proration_ready
- var combo_proration_ready : bool = false

{{ Missing Description }}



### var turbo_mode
- var turbo_mode : bool = false

{{ Missing Description }}



### var extremely_turbo_mode
- var extremely_turbo_mode : bool = false

{{ Missing Description }}



### var infinite_resources
- var infinite_resources : bool = false

{{ Missing Description }}



### var one_hit_ko
- var one_hit_ko : bool = false

{{ Missing Description }}



### var burst_enabled
- var burst_enabled : bool = true

{{ Missing Description }}



### var always_perfect_parry
- var always_perfect_parry : bool = false

{{ Missing Description }}



### var blocked_last_hit
- var blocked_last_hit : bool = false

{{ Missing Description }}



### var blocked_last_turn
- var blocked_last_turn : bool = false

{{ Missing Description }}



### var sadness_enabled
- var sadness_enabled : bool = false

{{ Missing Description }}



### var last_turn_block
- var last_turn_block : bool = false

{{ Missing Description }}



### var trail_hp
- var trail_hp : int = MAX_HEALTH

{{ Missing Description }}



### var hp
- var hp : int = 0

{{ Missing Description }}



### var super_meter
- var super_meter : int = 0

{{ Missing Description }}



### var supers_available
- var supers_available : int = 0

{{ Missing Description }}



### var combo_proration
- var combo_proration : int = 0

{{ Missing Description }}



### var combo_proration_set
- var combo_proration_set : bool = false

{{ Missing Description }}



### var last_parry_tick
- var last_parry_tick : int = 0

{{ Missing Description }}



### var parried_last_state
- var parried_last_state : bool = false

{{ Missing Description }}



### var initiative_effect
- var initiative_effect : bool = false

{{ Missing Description }}



### var clipping_wall
- var clipping_wall : bool = false

{{ Missing Description }}



### var burst_meter
- var burst_meter : int = 0

{{ Missing Description }}



### var bursts_available
- var bursts_available : int = 0

{{ Missing Description }}



### var turn_frames
- var turn_frames : int = 0

{{ Missing Description }}



### var busy_interrupt
- var busy_interrupt : bool = false

{{ Missing Description }}



### var any_available_actions
- var any_available_actions : bool = true

{{ Missing Description }}



### var refresh_prediction
- var refresh_prediction : bool = false

{{ Missing Description }}



### var burst_cancel_combo
- var burst_cancel_combo : bool = false

{{ Missing Description }}



### var parry_chip_divisor
- var parry_chip_divisor : UNKNOWN_TYPE = PARRY_CHIP_DIVISOR

{{ Missing Description }}



### var parry_chip_projectile_divisor
- var parry_chip_projectile_divisor : UNKNOWN_TYPE = PARRY_CHIP_PROJECILE_DIVISOR

{{ Missing Description }}



### var parry_knockback_divisor
- var parry_knockback_divisor : UNKNOWN_TYPE = PARRY_KNOCKBACK_DIVISOR

{{ Missing Description }}



### var moved_forward
- var moved_forward : bool = false

{{ Missing Description }}



### var buffer_moved_forward
- var buffer_moved_forward : bool = false

{{ Missing Description }}



### var moved_backward
- var moved_backward : bool = false

{{ Missing Description }}



### var buffer_moved_backward
- var buffer_moved_backward : bool = false

{{ Missing Description }}



### var blocked_hitbox_plus_frames
- var blocked_hitbox_plus_frames : int = 0

{{ Missing Description }}



### var had_sadness
- var had_sadness : bool = false

{{ Missing Description }}



### var state_changed
- var state_changed : bool = false

{{ Missing Description }}



### var on_the_ground
- var on_the_ground : bool = false

{{ Missing Description }}



### var nudge_amount
- var nudge_amount : fixed = "1.0"

{{ Missing Description }}



### var used_air_dodge
- var used_air_dodge : bool = false

{{ Missing Description }}



### var used_buffer
- var used_buffer : bool = false

{{ Missing Description }}



### var has_hyper_armor
- var has_hyper_armor : bool = false

{{ Missing Description }}



### var has_projectile_armor
- var has_projectile_armor : bool = false

{{ Missing Description }}



### var hit_during_armor
- var hit_during_armor : bool = false

{{ Missing Description }}



### var projectile_hit_cancelling
- var projectile_hit_cancelling : bool = false

{{ Missing Description }}



### var melee_attack_combo_scaling_applied
- var melee_attack_combo_scaling_applied : bool = false

{{ Missing Description }}



### var wall_slams
- var wall_slams : int = 0

{{ Missing Description }}



### var counterhit_this_turn
- var counterhit_this_turn : bool = false

{{ Missing Description }}



### var guard_broken_this_turn
- var guard_broken_this_turn : bool = false

{{ Missing Description }}



### var gained_whiff_meter
- var gained_whiff_meter : bool = false

{{ Missing Description }}



### var last_pos
- var last_pos : UNKNOWN_TYPE = null

{{ Missing Description }}



### var penalty
- var penalty : int = 0

{{ Missing Description }}



### var penalty_buffer
- var penalty_buffer : int = 0

{{ Missing Description }}



### var penalty_ticks
- var penalty_ticks : int = 0

{{ Missing Description }}



### var blockstun_ticks
- var blockstun_ticks : int = 0

{{ Missing Description }}



### var sadness_immunity_ticks
- var sadness_immunity_ticks : int = 0

{{ Missing Description }}



### var emote_tween
- var emote_tween : SceneTreeTween

{{ Missing Description }}



### var feints
- var feints : int = 2

{{ Missing Description }}



### var feinted_last
- var feinted_last : bool = false

{{ Missing Description }}



### var feint_parriable
- var feint_parriable : bool = false

{{ Missing Description }}



### var grounded_last_frame
- var grounded_last_frame : bool = true

{{ Missing Description }}



### var super_meter_used_recently
- var super_meter_used_recently : int = 0

{{ Missing Description }}



### var super_meter_grace_ticks
- var super_meter_grace_ticks : int = 0

{{ Missing Description }}



### var ghost_was_in_air
- var ghost_was_in_air : bool = false

{{ Missing Description }}



### var ghost_wrong_block
- var ghost_wrong_block : String = ""

{{ Missing Description }}



### var current_nudge
- var current_nudge : Dictionary = {

{{ Missing Description }}



### var current_di
- var current_di : Dictionary = {

{{ Missing Description }}



### var last_vel
- var last_vel : Dictionary = {

{{ Missing Description }}



### var last_aerial_vel
- var last_aerial_vel : Dictionary = {

{{ Missing Description }}



### var combo_moves_used
- var combo_moves_used : Dictionary = {}

{{ Missing Description }}



### var reverse_state
- var reverse_state : bool = false

{{ Missing Description }}



### var ghost_reverse
- var ghost_reverse : bool = false

{{ Missing Description }}



### var nudge_distance_left
- var nudge_distance_left : int = 0

{{ Missing Description }}



### var can_nudge
- var can_nudge : bool = false

{{ Missing Description }}



### var parried
- var parried : bool = false

{{ Missing Description }}



### var busy
- var busy : bool = false

{{ Missing Description }}



### var initiative
- var initiative : bool = false

{{ Missing Description }}



### var aura_particles
- var aura_particles : Array = []

{{ Missing Description }}



### var aura_entries
- var aura_entries : Array = []

{{ Missing Description }}



### var aura_particle
- var aura_particle : UNKNOWN_TYPE = null

{{ Missing Description }}



### var aura_particle_2
- var aura_particle_2 : UNKNOWN_TYPE = null

{{ Missing Description }}



### var aura_particle_3
- var aura_particle_3 : UNKNOWN_TYPE = null

{{ Missing Description }}



### var style_aura_got_hit_tick
- var style_aura_got_hit_tick : int = -100000

{{ Missing Description }}



### var style_aura_projectile_spawn_tick
- var style_aura_projectile_spawn_tick : int = -100000

{{ Missing Description }}



### var style_aura_projectiles_active_tick
- var style_aura_projectiles_active_tick : int = -100000

{{ Missing Description }}



### var style_aura_combo_active_tick
- var style_aura_combo_active_tick : int = -100000

{{ Missing Description }}



### var style_aura_being_comboed_tick
- var style_aura_being_comboed_tick : int = -100000

{{ Missing Description }}



### var style_aura_melee_attack_tick
- var style_aura_melee_attack_tick : int = -100000

{{ Missing Description }}



### var style_aura_burst_tick
- var style_aura_burst_tick : int = -100000

{{ Missing Description }}



### var style_aura_perfect_parry_tick
- var style_aura_perfect_parry_tick : int = -100000

{{ Missing Description }}



### var style_aura_install_super_tick
- var style_aura_install_super_tick : int = -100000

{{ Missing Description }}



### var style_aura_taunt_tick
- var style_aura_taunt_tick : int = -100000

{{ Missing Description }}



### var style_aura_parry_combo_tick
- var style_aura_parry_combo_tick : int = -100000

{{ Missing Description }}



### var style_aura_manual_action_pending
- var style_aura_manual_action_pending : bool = false

{{ Missing Description }}



### var style_aura_in_manual_state
- var style_aura_in_manual_state : bool = false

{{ Missing Description }}



### var style_aura_combo_started_tick
- var style_aura_combo_started_tick : int = -100000

{{ Missing Description }}



### var style_aura_being_comboed_started_tick
- var style_aura_being_comboed_started_tick : int = -100000

{{ Missing Description }}



### var style_aura_melee_attack_started_tick
- var style_aura_melee_attack_started_tick : int = -100000

{{ Missing Description }}



### var style_aura_projectiles_first_active_tick
- var style_aura_projectiles_first_active_tick : int = -100000

{{ Missing Description }}



### var style_aura_taunt_started_tick
- var style_aura_taunt_started_tick : int = -100000

{{ Missing Description }}



### var was_taunting_for_aura
- var was_taunting_for_aura : bool = false

{{ Missing Description }}



### var style_aura_parry_combo_started_tick
- var style_aura_parry_combo_started_tick : int = -100000

{{ Missing Description }}



### var was_parry_combo_active_for_aura
- var was_parry_combo_active_for_aura : bool = false

{{ Missing Description }}



### var was_combo_active_for_aura
- var was_combo_active_for_aura : bool = false

{{ Missing Description }}



### var was_being_comboed_for_aura
- var was_being_comboed_for_aura : bool = false

{{ Missing Description }}



### var was_projectiles_active_for_aura
- var was_projectiles_active_for_aura : bool = false

{{ Missing Description }}



### var _aura_rising_edge_initialized
- var _aura_rising_edge_initialized : bool = false

{{ Missing Description }}



### var in_blockstring
- var in_blockstring : bool = false

{{ Missing Description }}



### var brace_enabled
- var brace_enabled : bool = false

{{ Missing Description }}



### var parry_combo
- var parry_combo : bool = false

{{ Missing Description }}



### var parried_burst_combo
- var parried_burst_combo : bool = false

{{ Missing Description }}



### var feinting
- var feinting : bool = false

{{ Missing Description }}



### var clashing
- var clashing : bool = false

{{ Missing Description }}



### var last_action
- var last_action : int = 0

{{ Missing Description }}



### var stance
- var stance : String = "Normal"

{{ Missing Description }}



### var parried_hitboxes
- var parried_hitboxes : Array = []

{{ Missing Description }}



### var grounded_hits_taken
- var grounded_hits_taken : int = 0

{{ Missing Description }}



### var throw_pos_x
- var throw_pos_x : int = 16

{{ Missing Description }}



### var throw_pos_y
- var throw_pos_y : int = -5

{{ Missing Description }}



### var combo_supers
- var combo_supers : int = 0

{{ Missing Description }}



### var combo_damage
- var combo_damage : int = 0

{{ Missing Description }}



### var hitlag_applied
- var hitlag_applied : int = 0

{{ Missing Description }}



### var forfeit_ticks
- var forfeit_ticks : int = 0

{{ Missing Description }}



### var minus_frames
- var minus_frames : int = 0

{{ Missing Description }}



### var hitstun_decay_combo_count
- var hitstun_decay_combo_count : int = 0

{{ Missing Description }}



### var lowest_tick
- var lowest_tick : int = 0

{{ Missing Description }}



### var wakeup_throw_immunity_ticks
- var wakeup_throw_immunity_ticks : int = 0

{{ Missing Description }}




---
## Method Descriptions

### func clash
- func clash()

{{ Missing Description }}



### func get_visual_hp
- func get_visual_hp() -> UNKNOWN_TYPE

{{ Missing Description }}



### func init
- func init(pos=null)

{{ Missing Description }}



### func _aura_attach_limb
- func _aura_attach_limb(settings) -> String

{{ Missing Description }}



### func _resolved_attach_limb
- func _resolved_attach_limb(entry:Dictionary) -> String

{{ Missing Description }}



### func _aura_position_for_limb
- func _aura_position_for_limb(limb_name:String) -> Vector2

{{ Missing Description }}



### func _aura_rotation_for_limb
- func _aura_rotation_for_limb(limb_name:String) -> float

{{ Missing Description }}



### func _aura_flipped_for_limb
- func _aura_flipped_for_limb(limb_name:String) -> bool

{{ Missing Description }}



### func _aura_hidden_for_limb
- func _aura_hidden_for_limb(limb_name:String) -> bool

{{ Missing Description }}



### func _update_style_aura_trackers
- func _update_style_aura_trackers()

{{ Missing Description }}



### func _update_aura_threshold_trackers
- func _update_aura_threshold_trackers(particle, settings:Dictionary)

{{ Missing Description }}



### func _aura_trigger_active
- func _aura_trigger_active(particle, settings:Dictionary) -> bool

{{ Missing Description }}



### func _aura_trigger_event_fired
- func _aura_trigger_event_fired(particle, settings:Dictionary) -> bool

{{ Missing Description }}



### func _apply_aura_state
- func _apply_aura_state(particle, entry:Dictionary)

{{ Missing Description }}



### func is_ivy
- func is_ivy() -> bool

{{ Missing Description }}



### func apply_style
- func apply_style(style)

{{ Missing Description }}



### func reset_color
- func reset_color()

{{ Missing Description }}



### func reset_aura
- func reset_aura()

{{ Missing Description }}



### func reset_style
- func reset_style()

{{ Missing Description }}



### func reapply_style
- func reapply_style()

{{ Missing Description }}



### func start_super
- func start_super(freeze_ticks:int=0)

{{ Missing Description }}



### func change_stance_to
- func change_stance_to(stance)

{{ Missing Description }}



### func show_you_label
- func show_you_label()

{{ Missing Description }}



### func is_you
- func is_you(default:bool=true) -> UNKNOWN_TYPE

{{ Missing Description }}



### func unlock_achievement
- func unlock_achievement(achievement_name, multiplayer_only:bool=false)

{{ Missing Description }}



### func can_unlock_achievements
- func can_unlock_achievements() -> bool

{{ Missing Description }}



### func _ready
- func _ready()

{{ Missing Description }}



### func on_state_changed
- func on_state_changed(states_stack)

{{ Missing Description }}



### func on_got_hit
- func on_got_hit()

{{ Missing Description }}



### func on_got_hit_by_fighter
- func on_got_hit_by_fighter()

{{ Missing Description }}



### func on_got_hit_by_projectile
- func on_got_hit_by_projectile()

{{ Missing Description }}



### func gain_burst_meter
- func gain_burst_meter(amount=null)

{{ Missing Description }}



### func copy_to
- func copy_to(f)

{{ Missing Description }}



### func gain_burst
- func gain_burst()

{{ Missing Description }}



### func load_last_input_into_buffer
- func load_last_input_into_buffer()

{{ Missing Description }}



### func use_buffer
- func use_buffer()

{{ Missing Description }}



### func use_burst
- func use_burst()

{{ Missing Description }}



### func use_burst_meter
- func use_burst_meter(amount)

{{ Missing Description }}



### func get_total_super_meter
- func get_total_super_meter() -> UNKNOWN_TYPE

{{ Missing Description }}



### func use_super_bar
- func use_super_bar()

{{ Missing Description }}



### func use_super_meter
- func use_super_meter(amount)

{{ Missing Description }}



### func stack_move_in_combo
- func stack_move_in_combo(move_name)

{{ Missing Description }}



### func meter_gain_modified
- func meter_gain_modified(amount) -> int

{{ Missing Description }}



### func gain_super_meter
- func gain_super_meter(amount, stale_amount:fixed="1.0")

{{ Missing Description }}



### func gain_super_meter_raw
- func gain_super_meter_raw(amount)

{{ Missing Description }}



### func drain_super_meter
- func drain_super_meter(amount)

{{ Missing Description }}



### func spawn_object
- func spawn_object(projectile:PackedScene, pos_x:int, pos_y:int, relative:bool=true, data=null, local:bool=true) -> UNKNOWN_TYPE

{{ Missing Description }}



### func combo_stale_meter
- func combo_stale_meter(meter:int) -> UNKNOWN_TYPE

{{ Missing Description }}



### func update_data
- func update_data()

{{ Missing Description }}



### func emote
- func emote(message)

{{ Missing Description }}



### func set_emote_visible
- func set_emote_visible(amount:float)

{{ Missing Description }}



### func get_playback_input
- func get_playback_input() -> UNKNOWN_TYPE

{{ Missing Description }}



### func get_global_throw_pos
- func get_global_throw_pos() -> UNKNOWN_TYPE

{{ Missing Description }}



### func emit_hit_by_signal
- func emit_hit_by_signal(hitbox)

{{ Missing Description }}



### func reset_combo
- func reset_combo()

{{ Missing Description }}



### func create_speed_after_image
- func create_speed_after_image(color:Color=Color.white, lifetime:float=0.2)

{{ Missing Description }}



### func create_speed_after_image_from_style
- func create_speed_after_image_from_style(which:int=2)

{{ Missing Description }}



### func _create_speed_after_image
- func _create_speed_after_image(color:Color=Color.white, lifetime:float=0.2)

{{ Missing Description }}



### func incr_combo
- func incr_combo(scale:bool=true, projectile:bool=false, force:bool=false, combo_scale_amount:int=1)

{{ Missing Description }}



### func is_colliding_with_opponent
- func is_colliding_with_opponent() -> UNKNOWN_TYPE

{{ Missing Description }}



### func on_state_started
- func on_state_started(state)

{{ Missing Description }}



### func is_in_install_super
- func is_in_install_super() -> bool

{{ Missing Description }}



### func thrown_by
- func thrown_by(hitbox:ThrowBox)

{{ Missing Description }}



### func on_grabbed
- func on_grabbed()

{{ Missing Description }}



### func hitbox_from_name
- func hitbox_from_name(hitbox_name) -> UNKNOWN_TYPE

{{ Missing Description }}



### func _process
- func _process(delta)

{{ Missing Description }}



### func debug_text
- func debug_text()

{{ Missing Description }}



### func has_armor
- func has_armor() -> UNKNOWN_TYPE

{{ Missing Description }}



### func has_autoblock_armor
- func has_autoblock_armor() -> bool

{{ Missing Description }}



### func has_projectile_armor
- func has_projectile_armor() -> UNKNOWN_TYPE

{{ Missing Description }}



### func increment_opponent_combo
- func increment_opponent_combo(hitbox)

{{ Missing Description }}



### func apply_hitlag
- func apply_hitlag(hitbox, global:bool=true)

{{ Missing Description }}



### func get_active_projectiles
- func get_active_projectiles() -> UNKNOWN_TYPE

{{ Missing Description }}



### func launched_by
- func launched_by(hitbox)

{{ Missing Description }}



### func on_launched
- func on_launched()

{{ Missing Description }}



### func on_roll_started
- func on_roll_started()

{{ Missing Description }}



### func can_counter_hitbox
- func can_counter_hitbox(hitbox) -> bool

{{ Missing Description }}



### func is_bracing
- func is_bracing() -> UNKNOWN_TYPE

{{ Missing Description }}



### func prediction_effect
- func prediction_effect(ticks:int=7)

{{ Missing Description }}



### func counter_hitbox
- func counter_hitbox(hitbox)

{{ Missing Description }}



### func hit_by
- func hit_by(hitbox, force_hit:bool=false) -> CALLS:thrown_by

{{ Missing Description }}



### func block_hitbox
- func block_hitbox(hitbox, force_parry:bool=false, force_block:bool=false, ignore_guard_break:bool=false, autoblock_armor:bool=false)

{{ Missing Description }}



### func on_parried
- func on_parried()

{{ Missing Description }}



### func projectile_free_cancel
- func projectile_free_cancel()

{{ Missing Description }}



### func on_blocked_something
- func on_blocked_something()

{{ Missing Description }}



### func set_block_stun
- func set_block_stun(total_plus_frames, block_hitlag=null)

{{ Missing Description }}



### func parry_effect
- func parry_effect(location, absolute:bool=false)

{{ Missing Description }}



### func set_throw_position
- func set_throw_position(x:int, y:int)

{{ Missing Description }}



### func get_penalty_damage_modifier
- func get_penalty_damage_modifier() -> fixed

{{ Missing Description }}



### func take_damage
- func take_damage(damage:int, minimum:int=0, meter_gain_modifier:fixed="1.0", combo_scaling_offset:int=0, damage_taken_meter_gain_modifier:fixed="1.0", self_hit:bool=false, armor_block:bool=false)

{{ Missing Description }}



### func get_guts
- func get_guts() -> UNKNOWN_TYPE

{{ Missing Description }}



### func get_combo_stale
- func get_combo_stale(count) -> UNKNOWN_TYPE

{{ Missing Description }}



### func guts_stale_damage
- func guts_stale_damage(damage:int) -> UNKNOWN_TYPE

{{ Missing Description }}



### func combo_stale_damage
- func combo_stale_damage(damage:int, combo_scaling_offset:int=0, self_hit:bool=false) -> UNKNOWN_TYPE

{{ Missing Description }}



### func _is_self_hit
- func _is_self_hit(hitbox) -> bool

{{ Missing Description }}



### func can_perfect_parry
- func can_perfect_parry() -> bool

{{ Missing Description }}



### func can_parry_hitbox
- func can_parry_hitbox(hitbox) -> bool

{{ Missing Description }}



### func set_color
- func set_color(color, extra_color_1=null, extra_color_2=null)

{{ Missing Description }}



### func release_opponent
- func release_opponent()

{{ Missing Description }}



### func on_attack_blocked
- func on_attack_blocked()

{{ Missing Description }}



### func get_di_scaling
- func get_di_scaling(brace:bool=true, lookahead:int=0) -> fixed

{{ Missing Description }}



### func can_guard_break
- func can_guard_break() -> bool

{{ Missing Description }}



### func get_scaled_di
- func get_scaled_di(di) -> UNKNOWN_TYPE

{{ Missing Description }}



### func consume_feint
- func consume_feint()

{{ Missing Description }}



### func process_extra
- func process_extra(extra)

{{ Missing Description }}



### func super_effect
- func super_effect(freeze_ticks:int=0)

{{ Missing Description }}



### func ex_effect
- func ex_effect(freeze_ticks:int=0)

{{ Missing Description }}



### func use_air_movement
- func use_air_movement()

{{ Missing Description }}



### func refresh_air_movements
- func refresh_air_movements()

{{ Missing Description }}



### func refresh_feints
- func refresh_feints()

{{ Missing Description }}



### func clean_parried_hitboxes
- func clean_parried_hitboxes()

{{ Missing Description }}



### func get_opponent_dir
- func get_opponent_dir() -> UNKNOWN_TYPE

{{ Missing Description }}



### func get_dir_vec
- func get_dir_vec(pos, normalized:bool=true) -> Dictionary

{{ Missing Description }}



### func get_opponent_dir_vec
- func get_opponent_dir_vec(normalized:bool=true) -> Dictionary

{{ Missing Description }}



### func get_opponent
- func get_opponent() -> UNKNOWN_TYPE

{{ Missing Description }}



### func update_property_list
- func update_property_list()

{{ Missing Description }}



### func get_advantage
- func get_advantage() -> bool

{{ Missing Description }}



### func check_initiative
- func check_initiative() -> bool

{{ Missing Description }}



### func was_moving_forward
- func was_moving_forward() -> UNKNOWN_TYPE

{{ Missing Description }}



### func was_moving_backward
- func was_moving_backward() -> UNKNOWN_TYPE

{{ Missing Description }}



### func set_lowest_tick
- func set_lowest_tick(tick)

{{ Missing Description }}



### func update_advantage
- func update_advantage()

{{ Missing Description }}



### func on_state_initiative_start
- func on_state_initiative_start()

{{ Missing Description }}



### func clear_buffer
- func clear_buffer()

{{ Missing Description }}



### func process_continue
- func process_continue() -> bool

{{ Missing Description }}



### func tick_before
- func tick_before()

{{ Missing Description }}



### func process_action
- func process_action(queued_action)

{{ Missing Description }}



### func touching_which_wall
- func touching_which_wall() -> UNKNOWN_TYPE

{{ Missing Description }}



### func turn_end_effects
- func turn_end_effects()

{{ Missing Description }}



### func turn_start_effects
- func turn_start_effects()

{{ Missing Description }}



### func toggle_quit_graphic
- func toggle_quit_graphic(on=null)

{{ Missing Description }}



### func get_sadness_distance_penalty
- func get_sadness_distance_penalty() -> int

{{ Missing Description }}



### func can_be_thrown
- func can_be_thrown() -> UNKNOWN_TYPE

{{ Missing Description }}



### func tick
- func tick()

{{ Missing Description }}



### func passive_sadness_gain
- func passive_sadness_gain()

{{ Missing Description }}



### func landing_effect
- func landing_effect()

{{ Missing Description }}



### func get_move_dir
- func get_move_dir() -> UNKNOWN_TYPE

{{ Missing Description }}



### func get_opponent_distance
- func get_opponent_distance() -> CALLS:obj_distance

{{ Missing Description }}



### func can_block_cancel
- func can_block_cancel() -> bool

{{ Missing Description }}



### func add_penalty
- func add_penalty(amount, ignore_min_distance:bool=false)

{{ Missing Description }}



### func has_super_meter
- func has_super_meter() -> UNKNOWN_TYPE

{{ Missing Description }}



### func reset_penalty
- func reset_penalty()

{{ Missing Description }}



### func is_in_hurt_state
- func is_in_hurt_state(count_all:bool=true) -> UNKNOWN_TYPE

{{ Missing Description }}



### func set_ghost_colors
- func set_ghost_colors()

{{ Missing Description }}



### func set_facing
- func set_facing(facing:int, force:bool=false)

{{ Missing Description }}



### func update_facing
- func update_facing()

{{ Missing Description }}



### func on_state_interruptable
- func on_state_interruptable(state=null)

{{ Missing Description }}



### func on_state_hit_cancellable
- func on_state_hit_cancellable(projectile:bool=false, state=null)

{{ Missing Description }}



### func _arm_prorated_di
- func _arm_prorated_di()

{{ Missing Description }}



### func get_fighter
- func get_fighter() -> UNKNOWN_TYPE

{{ Missing Description }}



### func on_action_selected
- func on_action_selected(action, data, extra)

{{ Missing Description }}



### func drain_air_option_bar
- func drain_air_option_bar(amount)

{{ Missing Description }}



### func gain_free_cancel
- func gain_free_cancel(amount:int=1)

{{ Missing Description }}



### func gain_air_option_bar
- func gain_air_option_bar(amount)

{{ Missing Description }}



### func get_state_hash
- func get_state_hash() -> UNKNOWN_TYPE

{{ Missing Description }}



### func start_sadness_immunity
- func start_sadness_immunity()

{{ Missing Description }}



### func should_free_cancel_allow_grounded_and_aerial_states
- func should_free_cancel_allow_grounded_and_aerial_states() -> bool

{{ Missing Description }}



### func start_wakeup_throw_immunity
- func start_wakeup_throw_immunity()

{{ Missing Description }}



### func forfeit
- func forfeit()

{{ Missing Description }}



### func on_blocked_melee_attack
- func on_blocked_melee_attack()

{{ Missing Description }}



### func _draw
- func _draw()

{{ Missing Description }}




---
## Constant Descriptions

### const MAX_STALES
- const MAX_STALES : int = 15

{{ Missing Description }}



### const MIN_STALE_MODIFIER
- const MIN_STALE_MODIFIER : fixed = "0.2"

{{ Missing Description }}



### const WALL_SLAM_DAMAGE
- const WALL_SLAM_DAMAGE : fixed = "0.75"

{{ Missing Description }}



### const DI_SNAP_DISTANCE
- const DI_SNAP_DISTANCE : fixed = "0.01"

{{ Missing Description }}



### const DAMAGE_SUPER_GAIN_DIVISOR
- const DAMAGE_SUPER_GAIN_DIVISOR : int = 1

{{ Missing Description }}



### const DAMAGE_TAKEN_SUPER_GAIN_DIVISOR
- const DAMAGE_TAKEN_SUPER_GAIN_DIVISOR : int = 3

{{ Missing Description }}



### const HITLAG_COLLISION_TICKS
- const HITLAG_COLLISION_TICKS : int = 4

{{ Missing Description }}



### const PROJECTILE_PERFECT_PARRY_WINDOW
- const PROJECTILE_PERFECT_PARRY_WINDOW : int = 3

{{ Missing Description }}



### const BURST_ON_DAMAGE_AMOUNT
- const BURST_ON_DAMAGE_AMOUNT : int = 5

{{ Missing Description }}



### const AUTO_PARRY_TICKS
- const AUTO_PARRY_TICKS : int = 20

{{ Missing Description }}



### const SADNESS_IMMUNITY_TICKS
- const SADNESS_IMMUNITY_TICKS : int = 60

{{ Missing Description }}



### const VISUAL_GUTS_RATIO
- const VISUAL_GUTS_RATIO : float = 1.5

{{ Missing Description }}



### const MAX_WALL_SLAMS
- const MAX_WALL_SLAMS : int = 3

{{ Missing Description }}



### const COUNTER_HIT_ADDITIONAL_HITLAG_FRAMES
- const COUNTER_HIT_ADDITIONAL_HITLAG_FRAMES : int = 0

{{ Missing Description }}



### const MAX_GROUNDED_HITS
- const MAX_GROUNDED_HITS : int = 7

{{ Missing Description }}



### const PREDICTION_CORRECT_SUPER_GAIN
- const PREDICTION_CORRECT_SUPER_GAIN : int = 30

{{ Missing Description }}



### const INCORRECT_PREDICTION_LAG
- const INCORRECT_PREDICTION_LAG : int = 7

{{ Missing Description }}



### const PARRY_CHIP_DIVISOR
- const PARRY_CHIP_DIVISOR : int = 3

{{ Missing Description }}



### const PARRY_CHIP_PROJECILE_DIVISOR
- const PARRY_CHIP_PROJECILE_DIVISOR : int = 4

{{ Missing Description }}



### const PUSH_BLOCK_CHIP_MODIFIER
- const PUSH_BLOCK_CHIP_MODIFIER : fixed = "0.33"

{{ Missing Description }}



### const PARRY_KNOCKBACK_DIVISOR
- const PARRY_KNOCKBACK_DIVISOR : fixed = "3"

{{ Missing Description }}



### const PARRY_COMBO_SCALING
- const PARRY_COMBO_SCALING : fixed = "0.85"

{{ Missing Description }}



### const BURST_PARRY_COMBO_SCALING
- const BURST_PARRY_COMBO_SCALING : fixed = "0.85"

{{ Missing Description }}



### const PARRY_GROUNDED_KNOCKBACK_DIVISOR
- const PARRY_GROUNDED_KNOCKBACK_DIVISOR : fixed = "1.5"

{{ Missing Description }}



### const PUSH_BLOCK_FORCE
- const PUSH_BLOCK_FORCE : fixed = "-10"

{{ Missing Description }}



### const PUSH_BLOCK_DIST
- const PUSH_BLOCK_DIST : fixed = "220"

{{ Missing Description }}



### const PUSH_BLOCK_ADVANTAGE_PENALTY
- const PUSH_BLOCK_ADVANTAGE_PENALTY : int = 0

{{ Missing Description }}



### const AIR_BLOCK_PUSHBACK_MODIFIER
- const AIR_BLOCK_PUSHBACK_MODIFIER : fixed = "0.35"

{{ Missing Description }}



### const WAKEUP_THROW_IMMUNITY_TICKS
- const WAKEUP_THROW_IMMUNITY_TICKS : int = 3

{{ Missing Description }}



### const GLOBAL_HITLAG_MODIIFER
- const GLOBAL_HITLAG_MODIIFER : float = 0.6

{{ Missing Description }}



### const GLOBAL_BLOCKLAG_MODIFIER
- const GLOBAL_BLOCKLAG_MODIFIER : float = 0.25

{{ Missing Description }}



### const MAX_GLOBAL_HITLAG
- const MAX_GLOBAL_HITLAG : int = 10

{{ Missing Description }}



### const BASE_PLUS_FRAMES
- const BASE_PLUS_FRAMES : int = 0

{{ Missing Description }}



### const VS_AERIAL_ADDITIONAL_PLUS_FRAMES
- const VS_AERIAL_ADDITIONAL_PLUS_FRAMES : int = 2

{{ Missing Description }}



### const WRONG_HIT_HEIGHT_ADDITIONAL_PLUS_FRAMES
- const WRONG_HIT_HEIGHT_ADDITIONAL_PLUS_FRAMES : int = 2

{{ Missing Description }}



### const DISTANCE_EXTRA_SADNESS
- const DISTANCE_EXTRA_SADNESS : fixed = "180"

{{ Missing Description }}



### const MIN_DIST_SADNESS
- const MIN_DIST_SADNESS : fixed = "128"

{{ Missing Description }}



### const GUARD_BREAK_SCALING
- const GUARD_BREAK_SCALING : int = 1

{{ Missing Description }}



### const MISSED_BRACE_DAMAGE_MULTIPLIER
- const MISSED_BRACE_DAMAGE_MULTIPLIER : fixed = "1.0"

{{ Missing Description }}



### const SUCCESSFUL_BRACE_HITSTUN_MODIFIER
- const SUCCESSFUL_BRACE_HITSTUN_MODIFIER : fixed = "0.35"

{{ Missing Description }}



### const SUCCESSFUL_BRACE_DI_MODIFIER
- const SUCCESSFUL_BRACE_DI_MODIFIER : fixed = "1.5"

{{ Missing Description }}



### const COUNTER_HIT_DAMAGE_MODIFIER
- const COUNTER_HIT_DAMAGE_MODIFIER : fixed = "1.1"

{{ Missing Description }}



### const P1_COLOR
- const P1_COLOR : CALLS:Color = Color("aca2ff")

{{ Missing Description }}



### const P2_COLOR
- const P2_COLOR : CALLS:Color = Color("ff7a81")

{{ Missing Description }}



### const GUTS_REDUCTIONS
- const GUTS_REDUCTIONS : Dictionary = {

{{ Missing Description }}



### const GUTS_REDUCTIONS_OLD
- const GUTS_REDUCTIONS_OLD : Dictionary = {

{{ Missing Description }}



### const MAX_GUTS
- const MAX_GUTS : int = 10

{{ Missing Description }}



### const MAX_BURSTS
- const MAX_BURSTS : int = 1

{{ Missing Description }}



### const BURST_BUILD_SPEED
- const BURST_BUILD_SPEED : int = 4

{{ Missing Description }}



### const MAX_BURST_METER
- const MAX_BURST_METER : int = 1500

{{ Missing Description }}



### const START_BURSTS
- const START_BURSTS : int = 1

{{ Missing Description }}



### const MAX_SUPER_METER
- const MAX_SUPER_METER : int = 125

{{ Missing Description }}



### const MAX_SUPERS
- const MAX_SUPERS : int = 9

{{ Missing Description }}



### const VEL_SUPER_GAIN_DIVISOR
- const VEL_SUPER_GAIN_DIVISOR : int = 4

{{ Missing Description }}



### const AERIAL_VELOCITY_SUPER_GAIN_MODIFIER
- const AERIAL_VELOCITY_SUPER_GAIN_MODIFIER : fixed = "0.5"

{{ Missing Description }}



### const NUDGE_DISTANCE
- const NUDGE_DISTANCE : int = 20

{{ Missing Description }}



### const PARRY_METER
- const PARRY_METER : int = 50

{{ Missing Description }}



### const METER_GAIN_MODIFIER
- const METER_GAIN_MODIFIER : fixed = "0.85"

{{ Missing Description }}



### const CLASH_MOVE_BACK
- const CLASH_MOVE_BACK : int = 3

{{ Missing Description }}



### const MIN_PENALTY
- const MIN_PENALTY : int = -20

{{ Missing Description }}



### const MAX_PENALTY
- const MAX_PENALTY : int = 75

{{ Missing Description }}



### const PENALTY_MIN_DISPLAY
- const PENALTY_MIN_DISPLAY : int = 50

{{ Missing Description }}



### const PENALTY_TICKS
- const PENALTY_TICKS : int = 120

{{ Missing Description }}



### const SUPER_METER_GRACE_PERIOD
- const SUPER_METER_GRACE_PERIOD : int = 3

{{ Missing Description }}



### const SUPER_METER_GRACE_DIVISOR
- const SUPER_METER_GRACE_DIVISOR : int = 2

{{ Missing Description }}



### const _TRIGGER_ACTIVE_ROWS
- const _TRIGGER_ACTIVE_ROWS : Array = [

{{ Missing Description }}



### const _TRIGGER_EVENT_ROWS
- const _TRIGGER_EVENT_ROWS : Array = [

{{ Missing Description }}




---
## Signal Descriptions

### signal action_selected
- signal action_selected(action, data)

{{ Missing Description }}



### signal super_started
- signal super_started(freeze_ticks)

{{ Missing Description }}



### signal parried
- signal parried()

{{ Missing Description }}



### signal got_parried
- signal got_parried()

{{ Missing Description }}



### signal undo
- signal undo()

{{ Missing Description }}



### signal forfeit
- signal forfeit()

{{ Missing Description }}



### signal clashed
- signal clashed()

{{ Missing Description }}



### signal blocked_melee_attack
- signal blocked_melee_attack()

{{ Missing Description }}



### signal blocked_melee_attack_at_frame
- signal blocked_melee_attack_at_frame(frame)

{{ Missing Description }}



### signal predicted
- signal predicted(freeze_ticks)

{{ Missing Description }}




