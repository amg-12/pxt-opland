### @explicitHints true

# Treehouse

## Try it!

Say **t** in the chat to build a treehouse.

```template
player.onChat("t", function () {
    shapes.sphere(
    blocks.blockWithData(blocks.blockById(18), 8),
    pos(2, 9, 0),
    5,
    ShapeOperation.Hollow
    )
    blocks.fill(
    LOG_SPRUCE,
    pos(2, 0, 0),
    pos(2, 5, 0),
    FillOperation.Replace
    )
    blocks.fill(
    blocks.blockWithData(LADDER, 4),
    pos(1, 0, 0),
    pos(1, 5, 0),
    FillOperation.Replace
    )
    blocks.place(BED, pos(4, 6, 1))
})
```