### @explicitHints true

# Nether Portal

## Try it!

Say **portal** in the chat.

```template
let location: Position = null
location = world(48, 62, 73)
player.onChat("portal", function () {
    blocks.fill(
    OBSIDIAN,
    location,
    positions.add(
    location,
    pos(0, 4, 3)
    ),
    FillOperation.Replace
    )
    blocks.fill(
    AIR,
    positions.add(
    location,
    pos(0, 1, 1)
    ),
    positions.add(
    location,
    pos(0, 3, 2)
    ),
    FillOperation.Replace
    )
    blocks.place(FIRE, positions.add(
    location,
    pos(0, 1, 1)
    ))
})
```

```customts
player.onChat("clear", function () {
    blocks.fill(
    AIR,
    positions.add(
    location,
    pos(0, 1, 0)
    ),
    positions.add(
    location,
    pos(0, 4, 3)
    ),
    FillOperation.Replace
    )
})
```