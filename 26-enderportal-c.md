### @explicitHints true

# Ender Portal

## Try it!

Say **s** in the chat to build the ender portal.

```template
player.onChat("p", function () {
    positions2.save(world(20, 80, 87))
    shapes.line(
    blocks.blockWithData(END_PORTAL, 4),
    positions2.load(1, 0, 0),
    positions2.load(3, 0, 0)
    )
    shapes.line(
    blocks.blockWithData(END_PORTAL, 5),
    positions2.load(4, 0, 1),
    positions2.load(4, 0, 3)
    )
    shapes.line(
    blocks.blockWithData(END_PORTAL, 6),
    positions2.load(1, 0, 4),
    positions2.load(3, 0, 4)
    )
    shapes.line(
    blocks.blockWithData(END_PORTAL, 7),
    positions2.load(0, 0, 1),
    positions2.load(0, 0, 3)
    )
    blocks.fill(
    blocks.blockById(119),
    positions2.load(1, 0, 1),
    positions2.load(3, 0, 3),
    FillOperation.Replace
    )
})
```