### @explicitHints true

# Iron Golem

## Build this

```blocks
player.onChat("g", function () {
    positions2.save(posCamera(0, 0, 3))
    blocks.fill(
    AIR,
    positions2.load(-1, 0, 0),
    positions2.load(1, 2, 0),
    FillOperation.Replace
    )
    shapes.circle(
    IRON_BLOCK,
    positions2.load(0, 1, 0),
    1,
    Axis.Z,
    ShapeOperation.Replace
    )
    blocks.place(JACK_O_LANTERN, positions2.load(0, 2, 0))
})
```

```template
{}
```

## Try it!

Say **g** in the chat to spawn an iron golem.