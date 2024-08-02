### @explicitHints true

# Bomber

## Try it!

Fly around and rain destruction.

```template
player.onTravelled(FLY, function () {
    mobs.spawn(PRIMED_TNT, pos(0, -1, 0))
})
```