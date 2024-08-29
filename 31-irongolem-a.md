### @explicitHints true

# Iron Golem

## Build this

```blocks
player.onChat("g", function () {
    blocks.place(IRON_BLOCK, pos(1, 0, 1))
    blocks.place(IRON_BLOCK, pos(1, 1, 1))
    blocks.place(IRON_BLOCK, pos(0, 1, 1))
    blocks.place(IRON_BLOCK, pos(2, 1, 1))
    blocks.place(JACK_O_LANTERN, pos(1, 2, 1))
})
```

```template
{}
```

## Try it!

Say **g** in the chat to spawn an iron golem.