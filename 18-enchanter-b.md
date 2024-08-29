### @explicitHints true

# Enchanter

## Complete the code

```blocks
player.onChat("e", function () {
    blocks.fill(
    BOOKSHELF,
    pos(1, 0, 1),
    pos(2, 1, 5),
    FillOperation.Replace
    )
    blocks.fill(
    AIR,
    pos(1, 0, 2),
    pos(1, 1, 4),
    FillOperation.Replace
    )
    blocks.place(ENCHANTMENT_TABLE, pos(1, 0, 3))
})
```

```template
player.onChat("e", function () {
    blocks.fill(
    BOOKSHELF,
    pos(1, 0, 1),
    pos(2, 1, 5),
    FillOperation.Replace
    )
    blocks.fill(
    AIR,
    pos(1, 0, 2),
    pos(1, 1, 4),
    FillOperation.Replace
    )
})
```

## Try it!

Say **e** in the chat to build an enchanting station.