### @explicitHints true

# Enchanter

## Build this

```blocks
player.onChat("e", function () {
    positions2.save(posCamera(0, 0, 4))
    blocks.fill(
    BOOKSHELF,
    positions2.load(-2, 0, -2),
    positions2.load(2, 1, 2),
    FillOperation.Replace
    )
    blocks.fill(
    AIR,
    positions2.load(-1, 0, -1),
    positions2.load(1, 1, 1),
    FillOperation.Replace
    )
    blocks.fill(
    AIR,
    positions2.load(0, 0, 0),
    positions2.load(0, 1, 2),
    FillOperation.Replace
    )
    blocks.place(ENCHANTMENT_TABLE, positions2.load(0, 0, 0))
})
```

```template
{}
```

## Try it!

Say **e** in the chat to build an enchanting station.