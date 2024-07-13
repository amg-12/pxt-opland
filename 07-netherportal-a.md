### @explicitHints true
### @diffs true

# Nether Portal

## Step 1

Build this

```blocks
let location: Position = null
location = world(48, 62, 73)
```

```template
{}
```

```customts
player.onChat("clear", function () {
    blocks.fill(
    AIR,
    positions.add(
    location,
    pos(0, 1, 0)
    ),
    positions.add(
    location,
    pos(0, 4, 3)
    ),
    FillOperation.Replace
    )
})
```

## Step 2

Build this

```blocks
player.onChat("portal", function () {
    blocks.fill(
    OBSIDIAN,
    location,
    positions.add(
    location,
    pos(0, 4, 3)
    ),
    FillOperation.Replace
    )
})
```

## Step 3

Complete the code

```blocks
player.onChat("portal", function () {
    blocks.fill(
    OBSIDIAN,
    location,
    positions.add(
    location,
    pos(0, 4, 3)
    ),
    FillOperation.Replace
    )
    blocks.fill(
    AIR,
    positions.add(
    location,
    pos(0, 1, 1)
    ),
    positions.add(
    location,
    pos(0, 3, 2)
    ),
    FillOperation.Replace
    )
    blocks.place(FIRE, positions.add(
    location,
    pos(0, 1, 1)
    ))
})
```

## Try it!

Say **portal** in the chat.