### @explicitHints true

# Flower Power

## Step 1

Fill in the flowers

```blocks
player.onTravelled(WALK, function () {
    blocks.place(YELLOW_FLOWER, pos(-1, 0, 0))
    blocks.place(CORNFLOWER, pos(0, 0, 0))
    blocks.place(POPPY, pos(1, 0, 0))
})
```

```template
player.onTravelled(WALK, function () {
    blocks.place(DEAD_BUSH, pos(-1, 0, 0))
    blocks.place(DEAD_BUSH, pos(0, 0, 0))
    blocks.place(DEAD_BUSH, pos(1, 0, 0))
})
```

## Try it!

Walk around and spawn flowers.