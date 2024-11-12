### @explicitHints true

# Treehouse

## Build this

```blocks
player.onChat("t", function () {
    positions2.save(posCamera(0, 0, 2))
    blocks.fill(
    LOG_SPRUCE,
    positions2.load(0, 0, 0),
    positions2.load(0, 5, 0),
    FillOperation.Replace
    )
    shapes.sphere(
    blocks.blockWithData(blocks.blockById(18), 8),
    positions2.load(0, 9, 0),
    5,
    ShapeOperation.Hollow
    )
    blocks.fill(
    blocks.blockWithData(LADDER, 2),
    positions2.load(0, 0, -1),
    positions2.load(0, 5, -1),
    FillOperation.Replace
    )
    blocks.place(BED, positions2.load(2, 6, 1))
})
```

```template
{}
```

## Try it!

Say **t** in the chat to build a treehouse.