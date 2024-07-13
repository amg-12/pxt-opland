### @explicitHints true

# Auto Strip Mining

## Step 1

Build this

```blocks
mobs.give(
mobs.target(LOCAL_PLAYER),
DIAMOND_PICKAXE,
1
)
```

```template
{}
```

## Step 2

Build this

```blocks
player.onItemInteracted(DIAMOND_PICKAXE, function () {
    blocks.fill(
    AIR,
    posCamera(0, 0, 0),
    posCamera(1, 1, 60),
    FillOperation.Destroy
    )
})
```

## Try it!

Right-click with the pickaxe to mine a strip in front of you.