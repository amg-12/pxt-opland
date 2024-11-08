### @explicitHints true

# Randomiser

## Try it!

```template
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

```customts
loops.forever(function () {
	player.execute("kill @e[type=item]")
})
```