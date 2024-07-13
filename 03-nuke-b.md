### @explicitHints true

# TNT Nuke

## Step 1

Complete the code

```blocks
player.onChat("nuke", function () {
    blocks.fill(
    TNT,
    pos(1, 1, 1),
    pos(15, 15, 15),
    FillOperation.Replace
    )
    mobs.spawn(PRIMED_TNT, pos(8, 8, 8))
})
```

```template
player.onChat("nuke", function () {
    blocks.fill(
    TNT,
    pos(1, 1, 1),
    pos(15, 15, 15),
    FillOperation.Replace
    )
})
```

## Try it!

Say **nuke** in the chat.