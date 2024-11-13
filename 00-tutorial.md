### @explicitHints true

# Tutorial

## Try it!

```template
player.onChat("t", function () {
    mobs.teleportToPosition(
    mobs.target(LOCAL_PLAYER),
    world(-17, 63, 60)
    )
})
```

Say **t** in the chat to teleport to OP Land!