### @explicitHints true

# Firework Spawner

## Build this

```blocks
let position: Position = null
player.onChat("f", function () {
    position = positions.add(
    player.position(),
    pos(4, 0, 4)
    )
    blocks.fill(
    PLANKS_DARK_OAK,
    pos(3, 0, 3),
    pos(5, 0, 5),
    FillOperation.Replace
    )
    blocks.fill(
    COBBLESTONE,
    pos(2, -1, 2),
    pos(6, -1, 6),
    FillOperation.Replace
    )
    blocks.place(SHROOMLIGHT, position)
    for (let index = 0; index < 99999; index++) {
        mobs.spawn(FIREWORKS_ROCKET, position)
        loops.pause(randint(500, 3000))
    }
})
```

```template
{}
```

## Try it!

Say **f** in the chat to build a firework spawner.