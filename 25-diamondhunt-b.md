### @explicitHints true

# Diamond Hunt

## Complete the code

You can use **right-click** and **Duplicate**.

```blocks
player.onChat("d", function () {
    for (let index = 0; index < randint(1, 8); index++) {
        blocks.place(DIAMOND_ORE, pos(randint(-50, 50), randint(-20, 20), randint(-50, 50)))
    }
    for (let index = 0; index < randint(1, 3); index++) {
        blocks.place(DIAMOND_BLOCK, pos(randint(-50, 50), randint(-20, 20), randint(-50, 50)))
    }
})
```

```template
player.onChat("d", function () {
    for (let index = 0; index < randint(1, 8); index++) {
        blocks.place(DIAMOND_ORE, pos(randint(-50, 50), randint(-20, 20), randint(-50, 50)))
    }
})
```

## Try it!

Say **d** in the chat to fill the caves with diamonds.