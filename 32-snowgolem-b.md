### @explicitHints true

# Snow Golem

## Complete the code

```block
player.onChat("g", function () {
    blocks.place(SNOW, pos(1, 0, 1))
    blocks.place(SNOW, pos(1, 1, 1))
    blocks.place(CARVED_PUMPKIN, pos(1, 2, 1))
})
```

```template
player.onChat("g", function () {
    blocks.place(SNOW, pos(1, 0, 1))
    blocks.place(SNOW, pos(1, 1, 1))
})
```

## Try it!

Say **g** in the chat to spawn a snow golem.