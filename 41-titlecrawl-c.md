### @explicitHints true

# Title Crawl

## Try it!

Say **w** in the chat to create a moving text.

```template
player.onChat("w", function () {
    positions2.save(posCamera(-15, 15, 10))
    blocks.print(
    "Hello!",
    GOLD_BLOCK,
    positions2.load(0, 0, 0),
    SOUTH
    )
    for (let index = 0; index <= 25; index++) {
        loops.pause(500)
        blocks.clone(
        positions2.load(0, 0 - index, 0),
        positions2.load(0, 5 - index, 40),
        positions2.load(0, -1 - index, 0),
        CloneMask.Masked,
        CloneMode.Move
        )
    }
})
```