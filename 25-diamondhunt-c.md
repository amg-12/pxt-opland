### @explicitHints true

# Diamond Hunt

## Try it!

Say **d** in the chat to fill the caves with diamonds.

```template
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
        block,
        STONE,
        random_position,
        random_position
        )
    }
}
```