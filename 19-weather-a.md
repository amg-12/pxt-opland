### @explicitHints true

# Weather Change

## Build this

```blocks
player.onChat("r", function () {
    gameplay.setWeather(RAIN)
})
player.onChat("t", function () {
    gameplay.setWeather(THUNDER)
})
player.onChat("c", function () {
    gameplay.setWeather(CLEAR)
})
```

```template
{}
```

## Try it!

Say **r**, **t**, or **c** in the chat to change the weather.