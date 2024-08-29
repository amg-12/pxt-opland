### @explicitHints true

# Wingardium Leviosa

## Try it!

**Right-click** with the **stick** to make mobs float.

```template
player.onItemInteracted(STICK, function () {
    player.say("It's leviOsa, not levioSA!")
    mobs.applyEffect(LEVITATION, mobs.near(
    mobs.target(ALL_ENTITIES),
    player.position(),
    8
    ), 600, 1)
    mobs.clearEffect(mobs.target(LOCAL_PLAYER))
})
mobs.give(
mobs.target(LOCAL_PLAYER),
STICK,
1
)
```