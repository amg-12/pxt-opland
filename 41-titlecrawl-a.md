### @explicitHints true

# Title Crawl

## Build this

```block
let y_pos = 0
player.onChat("w", function () {
    y_pos = 15
    blocks.print(
    "Hello!",
    GOLD_BLOCK,
    pos(-10, y_pos, -10),
    EAST
    )
    while (y_pos > -10) {
        loops.pause(500)
        blocks.clone(
        pos(-10, y_pos, -10),
        pos(30, y_pos + 5, -10),
        pos(-10, y_pos - 1, -10),
        CloneMask.Masked,
        CloneMode.Move
        )
        y_pos += -1
    }
})
```

```template
{}
```

## Try it!

Say **w** in the chat to create a moving text.