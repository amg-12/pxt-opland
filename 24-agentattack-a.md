### @explicitHints true

# Agent Attack!

## Build this

```blocks
player.onChat("attack", function () {
    agent.teleportToPlayer()
    for (let index = 0; index < 500; index++) {
        agent.attack(FORWARD)
    }
})
```

```template
{}
```

## Try it!

Say **attack** in the chat to make the agent attack.