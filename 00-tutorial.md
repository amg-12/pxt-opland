### @explicitHints true

# Tutorial

Right-click with the shovel to dig.

```template
player.onChat("t", function () {
    mobs.teleportToPosition(
    mobs.target(LOCAL_PLAYER),
    world(-17, 63, 60)
    )
})
```

Say **t** in the chat to teleport to OP Land!