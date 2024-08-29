### @explicitHints true

# Agent Follow

## Try it!

Your agent will follow you.

```template
loops.forever(function () {
    agent.teleportToPlayer()
    loops.pause(3000)
})
```