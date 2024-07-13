### @explicitHints true

# Diggy Diggy Hole

## Step 1

Build this

```blocks
mobs.give(mobs.target(LOCAL_PLAYER), IRON_SHOVEL, 1)
```

```template
{}
```

## Step 2

Build this

```blocks
player.onItemInteracted(IRON_SHOVEL, function () {
    for (let index = 0; index <= 60; index++) {
        mobs.spawn(PRIMED_TNT, posCamera(0, index * -1, 5))
    }
})
```

## Try it!

Right-click with the shovel to dig.

