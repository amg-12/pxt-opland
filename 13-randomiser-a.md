### @explicitHints true

# Randomiser

## Build this

```blocks
player.onTravelled(WALK, function () {
    blocks.replace(
    blocks.blockById(randint(1, 252)),
    ENDSTONE,
    pos(-5, -1, -5),
    pos(5, 5, 5)
    )
    blocks.replace(
    blocks.blockById(randint(1, 252)),
    OBSIDIAN,
    pos(-5, -1, -5),
    pos(5, 5, 5)
    )
    player.execute(
    "kill @e[type=item]"
    )
})
```

```template
{}
```

## Try it!

Walk around and watch the blocks change.