### @explicitHints true

# Ender Portal

## Try it!

Say **s** in the chat to build the ender portal.

```template
player.onChat("s", function () {
    shapes.line(
    blocks.blockWithData(END_PORTAL, 4),
    positions.add(
    location,
    pos(1, 0, 0)
    ),
    positions.add(
    location,
    pos(3, 0, 0)
    )
    )
    shapes.line(
    blocks.blockWithData(END_PORTAL, 5),
    positions.add(
    location,
    pos(4, 0, 1)
    ),
    positions.add(
    location,
    pos(4, 0, 3)
    )
    )
    shapes.line(
    blocks.blockWithData(END_PORTAL, 6),
    positions.add(
    location,
    pos(1, 0, 4)
    ),
    positions.add(
    location,
    pos(3, 0, 4)
    )
    )
    shapes.line(
    blocks.blockWithData(END_PORTAL, 7),
    positions.add(
    location,
    pos(0, 0, 1)
    ),
    positions.add(
    location,
    pos(0, 0, 3)
    )
    )
    blocks.fill(
    blocks.blockById(119),
    positions.add(
    location,
    pos(1, 0, 1)
    ),
    positions.add(
    location,
    pos(3, 0, 3)
    ),
    FillOperation.Replace
    )
})
let location: Position = null
location = world(20, 80, 87)
```

```customts
player.onChat("clear", function () {
    blocks.fill(
    AIR,
    positions.add(
    location,
    pos(0, 0, 1)
    ),
    positions.add(
    location,
    pos(4, 0, 3)
    ),
    FillOperation.Replace
    )
    blocks.fill(
    AIR,
    positions.add(
    location,
    pos(1, 0, 0)
    ),
    positions.add(
    location,
    pos(3, 0, 4)
    ),
    FillOperation.Replace
    )
})
```