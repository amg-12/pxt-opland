### @explicitHints true

# Always Daytime

## Build this

```blocks
loops.forever(function () {
    gameplay.timeSet(gameplay.time(MIDDAY))
    loops.pause(60000)
})
```

```template
{}
```

## Try it!

Night will never fall again.