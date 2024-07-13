### @explicitHints true

# Flower Power

## Try it!

Walk around and spawn flowers.

```template
player.onTravelled(WALK, function () {
    blocks.place(YELLOW_FLOWER, pos(-1, 0, 0))
    blocks.place(CORNFLOWER, pos(0, 0, 0))
    blocks.place(POPPY, pos(1, 0, 0))
})
```