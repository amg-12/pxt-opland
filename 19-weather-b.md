### @explicitHints true

# Weather Change

## Complete the code

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
player.onChat("r", function () {
    gameplay.setWeather(RAIN)
})
player.onChat("t", function () {
    gameplay.setWeather(THUNDER)
})
```

## Try it!

Say **r**, **t**, or **c** in the chat to change the weather.