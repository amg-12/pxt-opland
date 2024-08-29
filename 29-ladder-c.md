### @explicitHints true

# Infinite Ladder

## Try it!

Say **l** in the chat to build a ladder, then climb it infinitely.

```template
player.onTravelled(CLIMB, function () {
    shapes.line(
    PLANKS_OAK,
    pos(1, 0, 0),
    pos(1, 4, 0)
    )
    shapes.line(
    blocks.blockWithData(LADDER, 4),
    pos(0, 0, 0),
    pos(0, 4, 0)
    )
})
player.onChat("l", function () {
    shapes.line(
    PLANKS_OAK,
    pos(1, 0, 0),
    pos(1, 4, 0)
    )
    shapes.line(
    blocks.blockWithData(LADDER, 4),
    pos(0, 0, 0),
    pos(0, 4, 0)
    )
})
```