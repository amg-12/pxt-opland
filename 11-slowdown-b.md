### @explicitHints true

# Slowdown Sword

## Complete the code

```blocks
player.onItemInteracted(NETHERITE_SWORD, function () {
    mobs.applyEffect(SLOWNESS, mobs.target(ALL_ENTITIES), 15, 80)
    mobs.clearEffect(mobs.target(NEAREST_PLAYER))
})
player.onChat("s", function () {
    mobs.give(
    mobs.target(LOCAL_PLAYER),
    NETHERITE_SWORD,
    1
    )
})
```

```template
player.onChat("s", function () {
    mobs.give(
    mobs.target(LOCAL_PLAYER),
    NETHERITE_SWORD,
    1
    )
})
```

## Try it!

Say **s** in the chat to get a sword, then **right-click with the sword** to slow down enemies.