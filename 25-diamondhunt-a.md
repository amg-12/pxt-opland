### @explicitHints true

# Diamond Hunt

## Step 1

Make this function.

```blocks
function populate (iterations: number, block: number) {
    for (let index = 0; index < iterations; index++) {
        random_position = randpos(
        pos(-5, -5, -5),
        pos(5, 5, 5)
        )
        blocks.replace(
        STONE,
        block,
        random_position,
        random_position
        )
    }
}
```
## Step 2

Add this chat command.

```blocks
player.onChat("d", function () {
    populate(50, DIAMOND_ORE)
    populate(5, DIAMOND_BLOCK)
})
function populate (iterations: number, block: number) {
    for (let index = 0; index < iterations; index++) {
        random_position = randpos(
        pos(-5, -5, -5),
        pos(5, 5, 5)
        )
        blocks.replace(
        STONE,
        block,
        random_position,
        random_position
        )
    }
}
```

```template
{}
```

## Try it!

Say **d** in the chat to fill the caves with diamonds.