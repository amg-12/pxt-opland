### @explicitHints true
### @diffs true

# Nether Portal

## Step 1

Build this

```blocks
player.onChat("p", function () {
    positions2.save(world(48, 62, 73))
})
```

```template
{}
```

## Step 2

Build this

```blocks
player.onChat("p", function () {
    positions2.save(world(48, 62, 73))
    blocks.fill(
    OBSIDIAN,
    positions2.load(0, 0, 0),
    positions2.load(0, 4, 3),
    FillOperation.Replace
    )
    blocks.fill(
    AIR,
    positions2.load(0, 1, 1),
    positions2.load(0, 3, 2),
    FillOperation.Replace
    )
})
```

## Step 3

Complete the code

```blocks
player.onChat("p", function () {
    positions2.save(world(48, 62, 73))
    blocks.fill(
    OBSIDIAN,
    positions2.load(0, 0, 0),
    positions2.load(0, 4, 3),
    FillOperation.Replace
    )
    blocks.fill(
    AIR,
    positions2.load(0, 1, 1),
    positions2.load(0, 3, 2),
    FillOperation.Replace
    )
    blocks.place(FIRE, positions2.load(0, 1, 1))
})
```

## Try it!

Say **p** in the chat.