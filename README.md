# SCP-682-EXILED

 ## Description:

939-89 has a configurable chance to be SCP-682 when he spawn,
he spawn as increased 939-89 with a configurable amount of hp.

### SCP-682 can:

- regenerate himself a configurable amount of hp(default 5) every configurable time(default 5 seconds),

- destroy doors like 096(you can turn it off in config or you can set a % chance for this),

- kill humans one hit (you can turn it off in config),

- gets a configurable amount of hp when he kills someone,

- pry gates like 096 (you can turn it off in config).

## Config
```s_c_p682:
  is_enabled: true
  spawn_chance: 100
  spawn_message: <b>You are <color=red>SCP-682</color></b>
  spawn_message_duration: 10
  # is the SCP-682 supposed to kill with one bite
  can_kill_on_oneshot: true
  # whether SCP-682 is to be able to Pry Gates?
  can_pry_gates: true
  # how much hp should SCP-682 get when he damage a human
  heal_hp_when_eat: 5
  # max hp
  max_hp: 2200
  # every how many seconds SCP-682 health should regenerate?
  heal_time: 5
  # how much hp should be regenerated?
  heal_hp: 5
  # can scp 682 destroy doors?
  scp682_can_destroy_door: true
  # how many % chance should SCP-682 have to destroy the door
  scp682_destroy_door_chance: 100
