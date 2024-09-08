### @explicitHints true

# TNT Sniper

## Complete the code

```blocks
let z = 0
player.onArrowShot(function () {
    z = -1
    for (let index = 0; index < 20; index++) {
        if (!(blocks.testForBlock(AIR, pos(0, 1, -z)))) {
            mobs.spawn(PRIMED_TNT, pos(0, 1, -z))
            break;
        }
        z += -1
    }
})
```

```template
let z = 0
player.onArrowShot(function () {
    z = -1
    for (let index = 0; index < 20; index++) {
        if (!(blocks.testForBlock(AIR, pos(0, 1, -z)))) {}
        z += -1
    }
})
```

## Try it!

Shoot an arrow and it will spawn TNT.