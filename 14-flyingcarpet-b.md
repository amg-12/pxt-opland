### @explicitHints true

# Flying Carpet

## Complete the code

```blocks
player.onTravelled(WALK, function () {
    magic_carpet()
})
player.onTravelled(FALL, function () {
    magic_carpet()
})
function magic_carpet () {
    blocks.fill(
    WOOL,
    posCamera(2, -1, 2),
    posCamera(-2, -1, -2),
    FillOperation.Replace
    )
    blocks.fill(
    AIR,
    posCamera(3, 0, 3),
    posCamera(-3, -2, -3),
    FillOperation.Outline
    )
}
```

```template
function magic_carpet () {
    blocks.fill(
    WOOL,
    posCamera(2, -1, 2),
    posCamera(-2, -1, -2),
    FillOperation.Replace
    )
    blocks.fill(
    AIR,
    posCamera(3, 0, 3),
    posCamera(-3, -2, -3),
    FillOperation.Outline
    )
}
```

## Try it!

Walk off a ledge and fly on your flying carpet.