### @explicitHints true

# Auto Strip Mining

## Try it!

Right-click with the pickaxe to mine a strip in front of you.

```template
mobs.give(
mobs.target(LOCAL_PLAYER),
DIAMOND_PICKAXE,
1
)
player.onItemInteracted(DIAMOND_PICKAXE, function () {
    blocks.fill(
    AIR,
    posCamera(0, 0, 0),
    posCamera(1, 1, 60),
    FillOperation.Destroy
    )
})
```