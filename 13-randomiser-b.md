### @explicitHints true

# Randomiser

## Complete the code

Remember you can duplicate!

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
})
```

```template
player.onTravelled(WALK, function () {
    blocks.replace(
    blocks.blockById(randint(1, 252)),
    ENDSTONE,
    pos(-5, -1, -5),
    pos(5, 5, 5)
    )
})
```

```customts
loops.forever(function () {
	player.execute("kill @e[type=item]")
})
```

## Try it!

Walk around and watch the blocks change.