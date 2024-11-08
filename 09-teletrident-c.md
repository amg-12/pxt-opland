### @explicitHints true

# Tele Trident

## Try it!

Say **t** in the chat to get a trident, then **right-click with the trident** to teleport..

```template
player.onChat("t", function () {
    mobs.give(
    mobs.target(LOCAL_PLAYER),
    TRIDENT,
    1
    )
})
player.onItemInteracted(TRIDENT, function () {
    mobs.teleportToPosition(
    mobs.target(LOCAL_PLAYER),
    positions.groundPosition(posLocal(0, 0, 50))
    )
})
```