### @explicitHints true

# TNT Nuke

## Try it!

Say **nuke** in the chat.

```template
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