### @explicitHints true

# Time Machine

## Build this

```blocks
loops.forever(function () {
    while (time_machine) {
        gameplay.timeSet(Math.round((270 - player.getOrientation()) * 66.66))
    }
})
player.onItemInteracted(CLOCK, function () {
    time_machine = !(time_machine)
    gameplay.title(mobs.target(LOCAL_PLAYER), "Time Machine: " + time_machine, "")
})
let time_machine = false
mobs.give(
mobs.target(LOCAL_PLAYER),
CLOCK,
1
)
```

```template
{}
```

## Try it!

**Right-click** with the **clock** to turn the time machine on or off. Turn your head to turn time.