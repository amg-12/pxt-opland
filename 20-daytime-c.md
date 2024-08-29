### @explicitHints true

# Always Daytime

## Try it!

Night will never fall again.

```template
loops.forever(function () {
    gameplay.timeSet(gameplay.time(MIDDAY))
    loops.pause(60000)
})
```