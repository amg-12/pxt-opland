### @explicitHints true

# Creeper Deterrent

## Complete the code

```blocks
loops.forever(function () {
    if (creeper_deterrent) {
        mobs.spawn(CAT, posCamera(0, 0, 5))
        loops.pause(100)
        mobs.kill(
        mobs.entitiesByType(CAT)
        )
    }
})
player.onChat("c", function () {
    creeper_deterrent = !(creeper_deterrent)
})
let creeper_deterrent = false
creeper_deterrent = false
```

```template
player.onChat("c", function () {
    creeper_deterrent = !(creeper_deterrent)
})
let creeper_deterrent = false
creeper_deterrent = false
```

## Try it!

Say **c** in the chat to turn the creeper deterrent on or off.