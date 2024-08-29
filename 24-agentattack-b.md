### @explicitHints true

# Agent Attack!

## Complete the code

```blocks
player.onChat("attack", function () {
    agent.teleportToPlayer()
    for (let index = 0; index < 500; index++) {
        agent.attack(FORWARD)
    }
})
```

```template
player.onChat("attack", function () {
    agent.teleportToPlayer()
})
```

## Try it!

Say **attack** in the chat to make the agent attack.