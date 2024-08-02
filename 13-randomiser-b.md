### @explicitHints true

# Randomiser

## Complete the code

```blocks
player.onTravelled(WALK, function () {
    blocks.replace(
    blocks.blockById(randint(1, 252)),
    ENDSTONE,
    pos(-15, -15, -15),
    pos(15, 15, 15)
    )
    blocks.replace(
    blocks.blockById(randint(1, 252)),
    OBSIDIAN,
    pos(-15, -15, -15),
    pos(15, 15, 15)
    )
})
```

```template
player.onTravelled(WALK, function () {
    blocks.replace(
    blocks.blockById(randint(1, 252)),
    ENDSTONE,
    pos(-15, -15, -15),
    pos(15, 15, 15)
    )
})
```

## Try it!

Walk around and watch the blocks change.