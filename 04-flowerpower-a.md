### @explicitHints true

# Flower Power

## Step 1

Build this

```blocks
player.onTravelled(WALK, function () {
    blocks.place(YELLOW_FLOWER, pos(-1, 0, 0))
    blocks.place(CORNFLOWER, pos(0, 0, 0))
    blocks.place(POPPY, pos(1, 0, 0))
})
```

```template
{}
```

## Try it!

Walk around and spawn flowers.