### @explicitHints true

# Swapping Game Mode

## Complete the code

```blocks
player.onChat("creative", function () {
    gameplay.setGameMode(
    CREATIVE,
    mobs.target(ALL_PLAYERS)
    )
})
player.onChat("survival", function () {
    gameplay.setGameMode(
    SURVIVAL,
    mobs.target(ALL_PLAYERS)
    )
})
player.onChat("adventure", function () {
    gameplay.setGameMode(
    ADVENTURE,
    mobs.target(LOCAL_PLAYER)
    )
})
```

```template
player.onChat("survival", function () {
    gameplay.setGameMode(
    SURVIVAL,
    mobs.target(ALL_PLAYERS)
    )
})
player.onChat("adventure", function () {
    gameplay.setGameMode(
    ADVENTURE,
    mobs.target(LOCAL_PLAYER)
    )
})
```

## Try it!

Say **creative**, **survival**, or **adventure** in the chat to change your game mode.