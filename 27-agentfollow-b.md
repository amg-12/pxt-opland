### @explicitHints true

# Agent Follow

## Complete the code

```blocks
loops.forever(function () {
    positions2.save(posCamera(0, 0, -2))
    agent.teleport(positions2.load(0, 0, 0), positions.toCompassDirection(player.getOrientation()))
})
```

```template
loops.forever(function () {
    positions2.save(posCamera(0, 0, -2))
})
```

## Try it!

Your agent will follow you.