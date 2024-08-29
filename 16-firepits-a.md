### @explicitHints true

# Firepits

## Build this

```blocks
player.onChat("f", function () {
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
    blocks.place(CAMPFIRE, pos(4, 0, 4))
})
```

```template
{}
```

## Try it!

Say **f** in the chat to build a firepit.