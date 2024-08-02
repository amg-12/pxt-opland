### @explicitHints true

# Charged Creeper

## Build this

```blocks
player.onChat("s", function () {
    mobs.spawn(mobs.monster(CREEPER), pos(0, 0, 5))
    mobs.spawn(LIGHTNING_BOLT, pos(0, 0, 5))
})
```

```template
{}
```

## Try it!

Say **s** in the chat to summon a charged creeper.