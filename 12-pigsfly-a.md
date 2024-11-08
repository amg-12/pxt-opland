### @explicitHints true

# Making Pigs Fly

## Build this

```blocks
player.onChat("fly", function () {
    for (let index = 0; index < 20; index++) {
        mobs.spawn(PIG, randpos(
        pos(-10, 0, -10),
        pos(10, 0, 10)
        ))
    }
    mobs.applyEffect(LEVITATION, mobs.entitiesByType(PIG), 2, 35)
})
```

```template
{}
```

## Try it!

Say **fly** in the chat to summon pigs and make them fly.