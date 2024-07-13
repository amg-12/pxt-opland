### @explicitHints true

# Panda Panic

## Try it!

Walk around and spawn pandas.

```template
player.onTravelled(WALK, function () {
    mobs.spawn(PANDA, pos(0, 0, 0))
})
```