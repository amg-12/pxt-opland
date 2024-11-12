### @explicitHints true

# Agent Follow

## Build this

```blocks
loops.forever(function () {
    agent.teleport(posCamera(0, 0, -1), positions.toCompassDirection(player.getOrientation()))
})
```

```template
{}
```

## Try it!

Your agent will follow you.