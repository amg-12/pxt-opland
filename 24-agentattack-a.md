### @explicitHints true

# Agent Attack!

## Build this

```blocks
let closest_monster = mobs.target(ALL_ENTITIES)
closest_monster.addRule("family", "monster")
closest_monster.addRule("c", "1")
while (true) {
    mobs.teleportToPlayer(
    mobs.target(MY_AGENT),
    closest_monster
    )
    agent.attack(FORWARD)
}
```

```template
{}
```

## Try it!

Say **attack** in the chat to make the agent attack.