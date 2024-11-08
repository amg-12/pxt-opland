### @explicitHints true

# Firepits

## Build this

```blocks
player.onChat("f", function () {
    positions2.save(posCamera(0, 0, 4))
    blocks.fill(
    PLANKS_DARK_OAK,
    positions2.load(-1, 0, -1),
    positions2.load(1, 0, 1),
    FillOperation.Replace
    )
    blocks.fill(
    COBBLESTONE,
    positions2.load(-2, -1, -2),
    positions2.load(2, -1, 2),
    FillOperation.Replace
    )
    blocks.place(CAMPFIRE, positions2.load(0, 0, 0))
})
```

```template
{}
```

## Try it!

Say **f** in the chat to build a firepit.