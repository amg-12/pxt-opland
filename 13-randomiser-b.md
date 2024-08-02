### @explicitHints true

# Randomiser

## Fill in the numbers

```blocks
player.onTravelled(WALK, function () {
    blocks.replace(
    blocks.blockById(randint(1, 252)),
    ENDSTONE,
    pos(-15, -15, -15),
    pos(15, 15, 15)
    )
})
```

```template
player.onTravelled(WALK, function () {
    blocks.replace(
    blocks.blockById(randint(0, 0)),
    GRASS,
    pos(0, 0, 0),
    pos(0, 0, 0)
    )
})
```

## Try it!

Walk around and watch the blocks change.