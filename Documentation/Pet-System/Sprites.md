have a system where you give one sprite, and get all sprites returned in a struct:

service_sprite.get_sprite(_original_sprite)
returns: struct ->
```gml
{
    original: "spr_something_original",
    idle: "spr_something_idle",
    walk: "spr_something_walk",
    run: "spr_something_run",
    jump: "spr_something_jump",
    play: "spr_something_play",
    eat: "spr_something_eat",
    sleep: "spr_something_sleep",
    sick: "spr_something_sick",
    sad: "spr_something_sad",
    happy: "spr_something_happy",
    mad: "spr_something_mad"
}
```
