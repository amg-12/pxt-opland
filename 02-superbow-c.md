### @explicitHints true

# Super Bow

## Try it!

Shoot the Super Bow.

```template
mobs.give(mobs.target(LOCAL_PLAYER), BOW, 1)
mobs.give(mobs.target(LOCAL_PLAYER), ARROW, 64)
player.onArrowShot(function () {
    for (let index = 0; index <= 10; index++) {
        mobs.spawn(PRIMED_TNT, posLocal(0, 1, index * 2 + 5))
    }
})
```