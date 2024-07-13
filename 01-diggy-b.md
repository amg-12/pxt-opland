### @explicitHints true

# Diggy Diggy Hole

## Step 1

Build this

```blocks
mobs.give(mobs.target(LOCAL_PLAYER), IRON_SHOVEL, 1)
```

## Try it!

Right-click with the shovel to dig.

```template
player.onItemInteracted(IRON_SHOVEL, function () {
    for (let index = 0; index <= 60; index++) {
        mobs.spawn(PRIMED_TNT, posCamera(0, index * -1, 5))
    }
})
```