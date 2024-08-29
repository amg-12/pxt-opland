### @explicitHints true

# Forest Generation

## Build this

```blocks
player.onChat("trees", function () {
    for (let index = 0; index < 10; index++) {
        agent.setItem(OAK_SAPLING, 1, 1)
        agent.setItem(BONE_MEAL, 64, 2)
        agent.teleport(randpos(
        pos(-20, 0, -20),
        pos(20, 0, 20)
        ), WEST)
        agent.setSlot(1)
        agent.place(FORWARD)
        agent.setSlot(2)
        for (let index = 0; index < 5; index++) {
            agent.place(FORWARD)
        }
    }
})
```

```template
{}
```

## Try it!

Say **trees** in the chat to create a forest.